# Lab Report 2
## Implementing String Server
**My Code for String Server:**

```
import java.io.IOException;
import java.net.URI;

class Handler implements URLHandler {
    // The one bit of state on the server: a number that will be manipulated by
    // various requests.
    int numOfMessages = 0;
    String userSees = "";

    public String handleRequest(URI url) {
        if (url.getPath().equals("/add-message")) {
            String[] parameters = url.getQuery().split("=");
            if (parameters[0].equals("s")) {
                numOfMessages++;
                if (numOfMessages == 1) {
                    userSees = parameters[1];
                } else {
                    userSees += "\n" + parameters[1];
                }
                return userSees;
            } else {
                return "404 Not Found";
            }
        } else {
            return "404 Not Found!";
        }
    }
}

class StringServer {
    public static void main(String[] args) throws IOException {
        if (args.length == 0) {
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}
```

**Screenshot 1:**

<img width="935" alt="Screen Shot 2023-01-28 at 3 48 12 PM" src="https://user-images.githubusercontent.com/52465268/215296315-839e439f-331f-4d5b-bf75-d8626a922b93.png">

Methods: handleRequest(), getPath(), getQuery()
Arguments: URI url
Fields: String userSees, int numOfMessages
userSees updated from "" to "Hello! It is Risab and his StringServer."
numOfMessages updated from 0 to 1

**Screenshot 2:**

<img width="901" alt="Screen Shot 2023-01-28 at 3 49 15 PM" src="https://user-images.githubusercontent.com/52465268/215296340-b593adb7-164c-4825-aaac-92fd6ecfdfc8.png">

Methods: handleRequest(), getPath(), getQuery()
Arguments: URI url
Fields: String userSees, int numOfMessages
userSees updated from "Hello! It is Risab and his StringServer." to "Hello! It is Risab and his StringServer.\nGlad to have you here."
numOfMessages updated from 1 to 2

The methods in my code that are called for each screenshot are handleRequest. handleRequest checks to see that the path that is requested is `"add-message," using the getPath() method in the URI imported library. It then acquires the query by using the getQuery() method and uses the split method to separate the query into separate elements of an erray separated off of "=" signs. After it verifies this information, it updates the String that is then returned to the user on the website. To start the website, the StringServer class uses the start method in the Server.java class to start up the website locally.

The handleRequest() method has a relevant argument which is the url of the website. getPath() and getQuery() do not have arguments in them. Relevant fields of the class include the numOfMessages instance variable that is used to keep track of the number of messages. Additionally, userSees is a String that is updated with every new message and then returned to the user.

The numOfMessages field is updated with every new message as it is incremented by 1 each time. Similarly, the String userSees is updated with every new message. The argument of handleRequest changes based on the URL that is inputted by the user. Other than that, no other values change as the argument remians constant regardless of the change in the url and the number of messages that have been sent through to the user.

##Bugs

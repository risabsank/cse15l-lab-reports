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
**Screenshot 2:**
<img width="901" alt="Screen Shot 2023-01-28 at 3 49 15 PM" src="https://user-images.githubusercontent.com/52465268/215296340-b593adb7-164c-4825-aaac-92fd6ecfdfc8.png">


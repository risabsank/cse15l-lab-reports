# Lab Report 3
## Researching Commands (the grep command)
**`grep - r`**
Examples:

Example 1:

Input:

```
grep -r "Lucayans" skill-demo1-data
```

Output:

```
skill-demo1-data/written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
skill-demo1-data/written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```

Example 2:

Input:

```
grep -r "Erevia" skill-demo1-data
```

Output:

```
skill-demo1-data/written_2/non-fiction/OUP/Castro/chQ.txt:A booklet by Angela Erevia provides an outline of the Catholic Mass including biblical readings and a schedule of the types of classes required of a young lady. Michele Salcedo’s book is a planning guide that discusses everything from the dress to the invitations, the music, the limousine, and the food, including the recipes. Internet sites are now available to guide a parent in planning every aspect of this ritual.
skill-demo1-data/written_2/non-fiction/OUP/Castro/chQ.txt:References Chavéz 1983; Davalos 1996; Erevia 1980; Horowitz 1993; Martinez-Chavez 1989; Ortiz 1992; Salcedo 1997; Siporin 1984; Vigil 1998
```

Explanation of What The Command Does:

Source: https://en.wikibooks.org/wiki/Grep

`grep -r` searches the files in a directory recursively, looking for the particular word or phrase that you have typed in the quotation marks next to the command in each text file in the directory. Once it identifies where these phrases in text files are located in the folder, it returns where in the text file that the word/phrase was found as well as a path to identify how to get to to the file in which that word was found. The `grep -r` command is useful in navigating through a large directory when looking for a specific thing.

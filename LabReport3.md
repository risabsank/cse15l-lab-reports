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

`grep -r` searches the files in a directory recursively, looking for the particular word or phrase that you have typed in the quotation marks next to the command in each text file in the directory. Once it identifies where these phrases in text files are located in the folder, it returns where in the text file that the word/phrase was found as well as a path to identify how to get to to the file in which that word was found. The `grep -r` command is useful in navigating through a large directory when looking for a specific thing.

Source: https://en.wikibooks.org/wiki/Grep

**`grep -i`**
Examples:

Example 1:

Input:

```
grep -i "and" Algarve-Intro.txt
```


Output:

```
the ALGARVE andITS People
For much of the world, the Algarve is synonymous with Portugal, yet the Portuguese will tell you the exact opposite: the region has little in common with the rest of the country. The southern stretch of coast is more reminiscent of a North African landscape than a European one. It has no cosmopolitan cities, like Lisbon and Porto, which are farther north. Most of Portugal is known for quaint towns, medieval castles, and grand palaces. The Algarve is more recognizable for impenetrable blocks of tourist apartments, hotels, and meticulously manicured golf courses.
And beaches. Think Algarve and the mind pictures long, glorious stretches of golden sands, secluded coves framed by odd ochre-colored rock formations, and deep green waters. With about 160 km (100 miles) of coastline, Portugal’s southern province is one of Europe’s premier beach destinations. The occasionally chilly ocean is the Atlantic, but the Algarve has a sultry Mediterranean feel.
Its consistent climate is the best in Portugal, and one of the kindest in the world: more than 250 days of sunshine a year — more than almost any other international resort area. The moderating effect of the Gulf Stream produces a fresh springtime breeze throughout winter, and in late January and February, white almond blossoms blanket the fields. In summer the heat is intense but rarely unbearable, and regardless, beautiful beaches and innumerable pools are always just a dive away.
Magnificent year-round weather has made the Algarve a huge destination for sporting vacations. Superb golf facilities abound — several with tees dramatically clinging to cliffs and fairways just skirting the edge of the ocean — and horseback riding, tennis, big-game fishing, sailing, and windsurfing are immensely popular.
Sports, beaches and hospitable weather — not to mention easily organized package vacations — are surely the reasons the Algarve receives as many visitors as the rest of Portugal in its entirety. But it’s not just international tourists that descend on the Algarve; many Portuguese from Lisbon and elsewhere in the north have holiday homes and spend their summer vacations here.
The coast is neatly divided into the rugged Barlavento to the west and the flat beauty of Sotavento to the east. West is where you’ll find the famous orange cliffs and surreal eroded rock stacks. Near Cabo de São Vicente and Sagres, the extreme western point, the terrain is surprisingly barren and the facilities decidedly low-key. The ocean can also be forbiddingly cold.
Tourist resorts clutter the entire middle of the coast, from Lagos to Faro, with a spectrum of homes away from home — monster high-rises to low-rider villas — spilling across the rolling hills and lining the beaches. Resorts like Portimão, Albufeira and Vilamoura would appear to have little room left to grow, yet tourist facilities seem to mate with each other and reproduce overnight. Much of the unstoppable growth is crass and frighteningly commercial, and the crowds in summer unbearable.
The eastern third of the Algarve is a more sedate marriage of coast and ocean, with warm waters and hot sands stretching past the wetlands of Ria Formosa to the Spanish border. The Algarve’s most picturesque town, Tavira, is along this section of the coast.
Away from the coast, the terrain slopes through pines, mimosa, eucalyptus, and heather to an altitude of nearly 915 m (3,000 ft). Vacationers wishing to escape the maddening beach crowds can run for the hills, especially the tantalizing Serra de Monchique.
The region’s exotic name is derived from the Arabic,Al-Gharb, meaning “country of the west.” The westernmost territory of Europe was highly prized by North African Moors, who occupied it from the eighth to the 13th centuries. Their half millennium here left indelible traces, seen today in whitewashed houses, hilltop castles, and colorful ceramic tiles.
Following the Reconquest of Iberia by Christians, the Algarve led Portugal to glory and fortune. Prince Henry the Navigator established his legendary Navigation School along Portugal’s southern coast (financing expeditions with royalties from the Algarve fishing industry), and intrepid explorers set out in caravels from Lagos and Sagres. In the 15th and 16th centuries, they ushered in an Age of Discovery, rounding Africa’s Cape of Good Hope and eventually reaching India and the Pacific. Others found their way to the Americas and Brazil. Opening world trade routes across the globe, they established Portugal as a maritime superpower. Spices, gold, and diamonds flowed across the seas to Lisbon.
Portugal soon lapsed into decline, though, tattered by wars and constitutional crises, and for two centuries or more the Algarve remained isolated from the rest of Europe. Even though the coast received many illustrious visitors from Roman times through the Middle Ages and up to the Edwardian period (when travelers came to luxuriate in Monchique’s spa waters), the Algarve’s elite vacation status is a relatively recent phenomenon. The first resort on the coast, Praia da Rocha, was only “discovered” in the 1930s, and the real build-up didn’t kick into overdrive until the beginning of the 1980s.
Spain’s Costa del Sol developed earlier and more rapidly (and some would say, more disastrously). Yet the lessons of rampant, ill-advised development across the border were not heeded. Only recently has environmental and aesthetic consciousness at least mandated that newer developments be limited to low-rises.
Yet — quite remarkably, in the face of the ongoing tourism onslaught — parts of the Algarve retain their old-fashioned charm. The main road along the coast, EN-125, is lined with ceramic shops and stifled with summertime traffic, but the agricultural countryside to the north is a different world. Flowering orchards and gentle grain fields replace hotels, apartments, and snack bars. A slow, rural lifestyle perseveres against the rush of modern life.
For centuries, fishing has been the Algarve’s lifeblood. Small fishing villages preserve their simple and unaffected ways, seemingly oblivious to the tourist hordes. Scrappy crews of small hand-painted boats troll the waters just offshore, and trawlers fish deep in the Atlantic for big shoals of bacalhau (cod) so beloved by the Portuguese.
A visit to the local fish market is a revealing window into Algarvian life. Negotiations are serious but friendly. The same scenario is played out a thousand times a day at markets all across the region; every town has a market day at least once a month. Farmers bring their livestock to trade, and artisans and itinerant vendors sell their wares.
Not a large area, the Algarve is relatively easy to get around, whether by train or car (an effort that is much more relaxing outside of the main summer season). The distances between mega-resorts and unspoiled villages are surprisingly small.
Besides beaches, the Algarve’s major attractions are towns that lived through centuries of adventure, triumph, and disaster. Faro, Tavira, and Lagos are towns with a strong Moorish influence, and quiet mountain towns like Silves, Alte, and Salir are reminders of the days before golf courses and hotel chains.
Despite the region’s ancient roots, few historic monuments survive from before 1755, when the Algarve was rocked by a monumental earthquake that took thousands of lives and leveled buildings as far north as Lisbon. Still, you’ll find vestiges of a vibrant past, including evocative castle ruins and churches with extraordinary displays of Portuguese glazed tiles. Even the humblest village has a classic white church, a sleepy plaza shaded by vivid purple jacaranda, and, if you time it right, the drama of the local market.
The Portuguese are famously hospitable, if reserved. And they remain tolerant and helpful, even though they know that their lovely coast is no longer just theirs.
```

Example 2:

Input:

```
grep -i "algarve" algarve-intro.txt
```

Output:

```
the ALGARVE andITS People
For much of the world, the Algarve is synonymous with Portugal, yet the Portuguese will tell you the exact opposite: the region has little in common with the rest of the country. The southern stretch of coast is more reminiscent of a North African landscape than a European one. It has no cosmopolitan cities, like Lisbon and Porto, which are farther north. Most of Portugal is known for quaint towns, medieval castles, and grand palaces. The Algarve is more recognizable for impenetrable blocks of tourist apartments, hotels, and meticulously manicured golf courses.
And beaches. Think Algarve and the mind pictures long, glorious stretches of golden sands, secluded coves framed by odd ochre-colored rock formations, and deep green waters. With about 160 km (100 miles) of coastline, Portugal’s southern province is one of Europe’s premier beach destinations. The occasionally chilly ocean is the Atlantic, but the Algarve has a sultry Mediterranean feel.
Magnificent year-round weather has made the Algarve a huge destination for sporting vacations. Superb golf facilities abound — several with tees dramatically clinging to cliffs and fairways just skirting the edge of the ocean — and horseback riding, tennis, big-game fishing, sailing, and windsurfing are immensely popular.
Sports, beaches and hospitable weather — not to mention easily organized package vacations — are surely the reasons the Algarve receives as many visitors as the rest of Portugal in its entirety. But it’s not just international tourists that descend on the Algarve; many Portuguese from Lisbon and elsewhere in the north have holiday homes and spend their summer vacations here.
The eastern third of the Algarve is a more sedate marriage of coast and ocean, with warm waters and hot sands stretching past the wetlands of Ria Formosa to the Spanish border. The Algarve’s most picturesque town, Tavira, is along this section of the coast.
Following the Reconquest of Iberia by Christians, the Algarve led Portugal to glory and fortune. Prince Henry the Navigator established his legendary Navigation School along Portugal’s southern coast (financing expeditions with royalties from the Algarve fishing industry), and intrepid explorers set out in caravels from Lagos and Sagres. In the 15th and 16th centuries, they ushered in an Age of Discovery, rounding Africa’s Cape of Good Hope and eventually reaching India and the Pacific. Others found their way to the Americas and Brazil. Opening world trade routes across the globe, they established Portugal as a maritime superpower. Spices, gold, and diamonds flowed across the seas to Lisbon.
Portugal soon lapsed into decline, though, tattered by wars and constitutional crises, and for two centuries or more the Algarve remained isolated from the rest of Europe. Even though the coast received many illustrious visitors from Roman times through the Middle Ages and up to the Edwardian period (when travelers came to luxuriate in Monchique’s spa waters), the Algarve’s elite vacation status is a relatively recent phenomenon. The first resort on the coast, Praia da Rocha, was only “discovered” in the 1930s, and the real build-up didn’t kick into overdrive until the beginning of the 1980s.
Yet — quite remarkably, in the face of the ongoing tourism onslaught — parts of the Algarve retain their old-fashioned charm. The main road along the coast, EN-125, is lined with ceramic shops and stifled with summertime traffic, but the agricultural countryside to the north is a different world. Flowering orchards and gentle grain fields replace hotels, apartments, and snack bars. A slow, rural lifestyle perseveres against the rush of modern life.
For centuries, fishing has been the Algarve’s lifeblood. Small fishing villages preserve their simple and unaffected ways, seemingly oblivious to the tourist hordes. Scrappy crews of small hand-painted boats troll the waters just offshore, and trawlers fish deep in the Atlantic for big shoals of bacalhau (cod) so beloved by the Portuguese.
Not a large area, the Algarve is relatively easy to get around, whether by train or car (an effort that is much more relaxing outside of the main summer season). The distances between mega-resorts and unspoiled villages are surprisingly small.
Besides beaches, the Algarve’s major attractions are towns that lived through centuries of adventure, triumph, and disaster. Faro, Tavira, and Lagos are towns with a strong Moorish influence, and quiet mountain towns like Silves, Alte, and Salir are reminders of the days before golf courses and hotel chains.
Despite the region’s ancient roots, few historic monuments survive from before 1755, when the Algarve was rocked by a monumental earthquake that took thousands of lives and leveled buildings as far north as Lisbon. Still, you’ll find vestiges of a vibrant past, including evocative castle ruins and churches with extraordinary displays of Portuguese glazed tiles. Even the humblest village has a classic white church, a sleepy plaza shaded by vivid purple jacaranda, and, if you time it right, the drama of the local market.
```

Explanation of What The Command Does:

`grep -i` searches for a specific pattern in a text file, but ignores case sensitivity. In the examples above, regardless if and was capitalized as "And" or left as "and," it returned wherever this pattern was found regardless of the uppercase. This is also seen with "algarve" in that all the times in which "algarve" was used with uppercase in the file was also returned to the user.

Source: https://www.thegeekstuff.com/2009/03/15-practical-unix-grep-command-examples/


# Lab Report 3

CSE15L_WI23 | Joy Lee (A17608409) | 13 February 2023<br />

---

###### This page explains 4 interesting command-line options for the command grep.

---

1st option: -c
-c commmand displays the number of lines that matches the given string.
path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/OUP/Castro
joy-lee-mbp:Castro JoyL$ grep -c "legend" chA.txt
4
path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/travel_guides/berlitz1
joy-lee-mbp:berlitz1 JoyL$ grep -c "island" WhatToHawaii.txt
10

2nd option: -l
-l command displays the files that contains the given string.
path:/Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/OUP/Rybczynski
joy-lee-mbp:Rybczynski JoyL$ grep -l "living" *
ch1.txt
ch3.txt

path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/travel_guides/berlitz1
joy-lee-mbp:berlitz1 JoyL$ grep -l "hope" *
HistoryHongKong.txt
HistoryItaly.txt
HistoryJamaica.txt
HistoryJapan.txt
HistoryJerusalem.txt
HistoryMallorca.txt
IntroEdinburgh.txt
IntroIndia.txt
IntroIsrael.txt
IntroJapan.txt
IntroJerusalem.txt
WhatToGreek.txt
WhatToIndia.txt
WhereToDublin.txt
WhereToFrance.txt
WhereToHongKong.txt
WhereToIbiza.txt
WhereToIndia.txt
WhereToJapan.txt
WhereToJerusalem.txt
WhereToMalaysia.txt
WhereToMallorca.txt

3rd option: -o
-o command displays only the matched string.
path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/OUP/Abernathy
joy-lee-mbp:Abernathy JoyL$ grep -o "clothing" ch9.txt
clothing
clothing
clothing
clothing

path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/travel_guides/berlitz2
joy-lee-mbp:berlitz2 JoyL$ grep -o "style" PuertoRico-WhatToDo.txt
style
style
style

4th option: -n
-n command displays 
path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/OUP/Kauffman
joy-lee-mbp:Kauffman JoyL$ grep -n "coconstruction" ch8.txt
192:In short, there must be a self-consistent coconstruction of a biosphere in which organisms, ways of making a living, and search mechanisms jointly and self-consistently come into existence. Organisms are not solving arbitrary problems. We are solving the kinds of problems we can solve given our solution procedures. How could it be otherwise?

path: /Users/JoyL/Documents/GitHub/skill-demo1-data/written_2/travel_guides/berlitz2

joy-lee-mbp:berlitz2 Doyeon$ grep -n "gambling" California-WhereToGo.txt
175:The city of Las Vegas grew out of a stopover at a natural oasis, which burgeoned after Nevada’s legalization of gambling in 1931. Today, visitors converge on Vegas from all over America. Many are still here for a bit of fun and titillation, and to lose a few bucks at roulette or blackjack, but Las Vegas now touts itself as a family destination.
179:There are also alternatives to gambling — the big casinos offer live stage shows with all kinds of entertainment, from major singing stars to leggy extravaganzas like the Folies Bergères to world-title boxing matches. If you want to get out and about, there are opportunities for almost every type of recreation activity, including winter sports, within an hour of the city.

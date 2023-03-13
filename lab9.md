# Lab Report 5

CSE15L_WI23 | Joy Lee (A17608409) | 13 March 2023<br />

---

###### This page explains 4 interesting command-line options for the command `find`.
###### Each command has two examples to show how the command-line options work as well as show the path using `pwd` command.

---

### 1st option: `-name` command
`-name` commmand can be used when you know the name of a file but cannot remember where you saved it.<br />
###### (Source used: https://www.redhat.com/sysadmin/linux-find-command)

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ find -name "chA.txt"
>./non-fiction/OUP/Castro/chA.txt
>```

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ find -name "WhatToHawaii.txt"
>./travel_guides/berlitz1/WhatToHawaii.txt
>```

### 2nd option: `-iname` command
`-iname` command can be used if you cannot remember the full name of the file,
or you are not sure whether you capitalized any characters.<br />
###### (Source used: https://www.redhat.com/sysadmin/linux-find-command)

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ find -iname "*ch*txt"
>./non-fiction/OUP/Abernathy/ch1.txt
>./non-fiction/OUP/Abernathy/ch14.txt
>./non-fiction/OUP/Abernathy/ch15.txt
>./non-fiction/OUP/Abernathy/ch2.txt
>./non-fiction/OUP/Abernathy/ch3.txt
>./non-fiction/OUP/Abernathy/ch6.txt
>./non-fiction/OUP/Abernathy/ch7.txt
>./non-fiction/OUP/Abernathy/ch8.txt
>./non-fiction/OUP/Abernathy/ch9.txt
>./non-fiction/OUP/Berk/ch1.txt
>./non-fiction/OUP/Berk/ch2.txt
>./non-fiction/OUP/Berk/CH4.txt
>./non-fiction/OUP/Berk/ch7.txt
>./non-fiction/OUP/Castro/chA.txt
>./non-fiction/OUP/Castro/chB.txt
>./non-fiction/OUP/Castro/chC.txt
>./non-fiction/OUP/Castro/chL.txt
>./non-fiction/OUP/Castro/chM.txt
>./non-fiction/OUP/Castro/chN.txt
>./non-fiction/OUP/Castro/chO.txt
>./non-fiction/OUP/Castro/chP.txt
>./non-fiction/OUP/Castro/chQ.txt
>./non-fiction/OUP/Castro/chR.txt
>./non-fiction/OUP/Castro/chV.txt
>./non-fiction/OUP/Castro/chW.txt
>./non-fiction/OUP/Castro/chY.txt
>./non-fiction/OUP/Castro/chZ.txt
>./non-fiction/OUP/Fletcher/ch1.txt
>./non-fiction/OUP/Fletcher/ch10.txt
>./non-fiction/OUP/Fletcher/ch2.txt
>./non-fiction/OUP/Fletcher/ch5.txt
>./non-fiction/OUP/Fletcher/ch6.txt
>./non-fiction/OUP/Fletcher/ch9.txt
>./non-fiction/OUP/Kauffman/ch1.txt
>./non-fiction/OUP/Kauffman/ch10.txt
>./non-fiction/OUP/Kauffman/ch3.txt
>./non-fiction/OUP/Kauffman/ch4.txt
>./non-fiction/OUP/Kauffman/ch5.txt
>./non-fiction/OUP/Kauffman/ch6.txt
>./non-fiction/OUP/Kauffman/ch7.txt
>./non-fiction/OUP/Kauffman/ch8.txt
>./non-fiction/OUP/Kauffman/ch9.txt
>./non-fiction/OUP/Rybczynski/ch1.txt
>./non-fiction/OUP/Rybczynski/ch2.txt
>./non-fiction/OUP/Rybczynski/ch3.txt
>./travel_guides/berlitz2/China-History.txt
>./travel_guides/berlitz2/China-WhatToDo.txt
>./travel_guides/berlitz2/China-WhereToGo.txt
>```

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2
>$ find -iname "*Intro*txt"
>./travel_guides/berlitz1/IntroDublin.txt
>./travel_guides/berlitz1/IntroEdinburgh.txt
>./travel_guides/berlitz1/IntroEgypt.txt
>./travel_guides/berlitz1/IntroFrance.txt
>./travel_guides/berlitz1/IntroFWI.txt
>./travel_guides/berlitz1/IntroGreek.txt
>./travel_guides/berlitz1/IntroHongKong.txt
>./travel_guides/berlitz1/IntroIbiza.txt
>./travel_guides/berlitz1/IntroIndia.txt
>./travel_guides/berlitz1/IntroIsrael.txt
>./travel_guides/berlitz1/IntroIstanbul.txt
>./travel_guides/berlitz1/IntroItaly.txt
>./travel_guides/berlitz1/IntroJamaica.txt
>./travel_guides/berlitz1/IntroJapan.txt
>./travel_guides/berlitz1/IntroJerusalem.txt
>./travel_guides/berlitz1/IntroLakeDistrict.txt
>./travel_guides/berlitz1/IntroLasVegas.txt
>./travel_guides/berlitz1/IntroLosAngeles.txt
>./travel_guides/berlitz1/IntroMadeira.txt
>./travel_guides/berlitz1/IntroMadrid.txt
>./travel_guides/berlitz1/IntroMalaysia.txt
>./travel_guides/berlitz1/IntroMallorca.txt
>./travel_guides/berlitz2/Algarve-Intro.txt
>./travel_guides/berlitz2/Amsterdam-Intro.txt
>./travel_guides/berlitz2/Athens-Intro.txt
>./travel_guides/berlitz2/Bahamas-Intro.txt
>```

### 3rd option: `-type d` command
`-type d` command displays lists of directories.<br />
###### (Source used: https://www.redhat.com/sysadmin/linux-find-command)

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/non-fiction
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/non-fiction
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Abernathy
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Berk
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Castro
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Fletcher
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Kauffman
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction/OUP/Rybczynski
>```

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/travel_guides
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2/travel_guides
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/travel_guides
>$ find ~/skill-demo1-data/written_2/travel_guides -type d
>/c/Users/Joy Lee/skill-demo1-data/written_2/travel_guides
>/c/Users/Joy Lee/skill-demo1-data/written_2/travel_guides/berlitz1
>/c/Users/Joy Lee/skill-demo1-data/written_2/travel_guides/berlitz2
>```

### 4th option: `-size` command
`-size` command can be used to help find files larger (using `+` sign) or smaller (using `-` sign) than a specified size.<br />
For the first example, I used `+100k`, where 'k' is for Kilobytes, resulting in searching for files that are larger than 100 Kilobytes.<br />
For the second example, I used `-10k`, where 'k' is for Kilobytes, resulting in searching for files that are larger than 10 Kilobytes
###### (Source used: https://geekflare.com/how-to-use-find-command-in-linux/)

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/non-fiction
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2/non-fiction
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/non-fiction
>$ find -size +100k
>./OUP/Berk/ch2.txt
>./OUP/Berk/CH4.txt
>```

>```ruby
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/travel_guides
>$ pwd
>/c/Users/Joy Lee/skill-demo1-data/written_2/travel_guides
>
>Joy Lee@Pineapple-Kim MINGW64 ~/skill-demo1-data/written_2/travel_guides
>$ find -size -10k
>.
>./berlitz1
>./berlitz1/HandRHongKong.txt
>./berlitz1/HandRIbiza.txt
>./berlitz1/HandRIstanbul.txt
>./berlitz1/HandRJerusalem.txt
>./berlitz1/HandRLakeDistrict.txt
>./berlitz1/HandRLasVegas.txt
>./berlitz1/HandRLisbon.txt
>./berlitz1/HandRLosAngeles.txt
>./berlitz1/HandRMadeira.txt
>./berlitz1/HandRMallorca.txt
>./berlitz1/IntroDublin.txt
>./berlitz1/IntroEgypt.txt
>./berlitz1/IntroFWI.txt
>./berlitz1/IntroGreek.txt
>./berlitz1/IntroHongKong.txt
>./berlitz1/IntroIbiza.txt
>./berlitz1/IntroIsrael.txt
>./berlitz1/IntroIstanbul.txt
>./berlitz1/IntroLosAngeles.txt
>./berlitz1/IntroMalaysia.txt
>./berlitz1/JungleMalaysia.txt
>./berlitz1/WhatToFrance.txt
>./berlitz1/WhatToHawaii.txt
>./berlitz1/WhereToHawaii.txt
>./berlitz2
>./berlitz2/Algarve-Intro.txt
>./berlitz2/Amsterdam-Intro.txt
>./berlitz2/Athens-Intro.txt
>./berlitz2/Bahamas-Intro.txt
>```

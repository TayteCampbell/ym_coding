# youth_coding
#This is a repository for activities to teach coding in python. It contains lists and dictionaries that can be copied to save time in class

###State list

###In this activity students are given a number which identifies a mystery state. The number is created by adding the value of the letters (A=1,B=2, etc.) and students are guided through using the provided list and dictionary to identify the mystery state.

states = ["Alabama",    "Alaska",       "Arizona",      "Arkansas",     "California",  \
 "Colorado",     "Connecticut",  "Delaware",     "Florida",      "Georgia",      "Hawai\
i",       "Idaho",        "Illinois",     "Indiana",      "Iowa", "Kansas",       "Kent\
ucky",     "Louisiana",    "Maine",        "Maryland",     "Massachusetts",        "Mic\
higan",     "Minnesota",    "Mississippi",  "Missouri",     "Montana",      "Nebraska",\
     "Nevada",       "New Hampshire",        "New Jersey",   "New Mexico",   "New York"\
,     "North Carolina",       "North Dakota", "Ohio", "Oklahoma",     "Oregon",       "\
Pennsylvania", "Rhode Island", "South Carolina",       "South Dakota", "Tennessee",    \
"Texas",        "Utah", "Vermont",      "Virginia",     "Washington",   "West Virginia"\
,        "Wisconsin",    "Wyoming"]

###State letter dictionary

code_dict = {" ":0,  "a":1,     "b":2,  "c":3,  "d":4,  "e":5,  "f":6,  "g":7,  "h":8,  "i":9,  "j":10, "k":11, "l":12, "m":13, "n":14, "o":15, "p":16, "q":17, "r":18, "s":19, "t":20, "u":21, "v":22, "w":23, "x":24, "y":25, "z":26, "A":1,  "B":2,  "C":3,  "D":4,  "E":5,  "F":6,  "G":7,  "H":8,  "I":9,  "J":10, "K":11, "L":12, "M":13, "N":14, "O":15, "P":16, "Q":17, "R":18, "S":19, "T":20, "U":21, "V":22, "W":23, "X":24, "Y":25, "Z":26}



####Secret message: A secret message has been created using the encode dictionary to swap random characters for letters. Give students the secret message and the decode library and have them decode the secret message. They can then use the encode dictionary to create their own secret message.

"140-+85-! 8 14++4) +70$ -6!;. 4/&!828+ 8 14++4) +70$ 8#&!828+. 8#&!4 8 14++4) +70$ 2%#&!4/. 2%#&!4/ 8 14++4) +70$ 2%#&!820+43. 5!0+ 8 14++4) +70$ $4+43. &0)4 8 14++4) +70$ 34$4. )403018!8+; 2%-$+. &4280! 204 0)4$'+ &4280! 4$%-67 +% 1)40@ +74 )-!4. 0!+7%-67 &)02+820!8+; 140+ &-)8+;. 4))%) 7%-!3 $4<4) &0 8!4$+!;. -$!4 4/&!828+!; 8!4$243. 8$ +74 5024 %5 0#186-8+;, )45-4 +74 +4#&+0+8%$ +% 6-4. +74)4 7%-!3 14 %$4 0$3 &)454)01!; %$!; %$4 %1<8%- >0; +% 3% 8+. 0!+7%-67 +70+ >0; #0; $%+ 14 %1<8%- 0+ 58)+ -$!4 ;%-')4 3-+27. $%> 8 14++4) +70$ $4<4). 0!+7%-67 $4<4) 8 %5+4$ 14++4) +70$ )867+ $%>. 85 +74 8#&!4#4$+0+8%$ 8 70)3 +% 4/&!08$, 8+' 0 103 8340. 85 +74 8#&!4#4$+0+8%$ 8 40; +% 4/&!08$, 8+ #0; 14 0 6%%3 8340. $0#4&024 0)4 %$4 7%$@8$6 6)40+ 8340 !4+' 3% #%)4 %5 +7%4!"


####Encode Dictionary

encode_dict = {"a":"0", "b":"1",        "c":"2",        "d":"3",        "e":"4",       \
 "f":"5",        "g":"6",        "h":"7",        "i":"8",        "j":"9",        "k":"@\
",        "l":"!",        "m":"#",        "n":"$",        "o":"%",        "p":"&",     \
   "q":"(",        "r":")",        "s":"*",        "t":"+",        "u":"-",        "v":\
"<",        "w":">",        "x":"/",        "y":";",        "z":"=",        "A":"0",   \
     "B":"1",        "C":"2",        "D":"3",        "E":"4",        "F":"5",        "G\
":"6",        "H":"7",        "I":"8",        "J":"9",        "K":"@",        "L":"!", \
       "M":"#",        "N":"$",        "O":"%",        "P":"&",        "Q":"(",        \
"R":")",        "S":"*",        "T":"+",        "U":"-",        "V":"<",        "W":">"\
,        "X":"/",        "Y":";",        "Z":"="," ":" ",",":",",".":".","'":"'"}

#####Decode Dictionary


decode_dict = {"0":"a", "1":"b",        "2":"c",        "3":"d",        "4":"e",       \
 "5":"f",        "6":"g",        "7":"h",        "8":"i",        "9":"j",        "@":"k\
",        "!":"l",        "#":"m",        "$":"n",        "%":"o",        "&":"p",     \
   "(":"q",        ")":"r",        "*":"s",        "+":"t",        "-":"u",        "<":\
"v",        ">":"w",        "/":"x",        ";":"y",        "=":"z"," ":" ",",":",","."\
:".","'":"'"}


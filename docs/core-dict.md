Hex    | Stack effect      | English definition                                                                     | Class
------ | ----------------- | -------------------------------------------------------------------------------------- | ----------------------
05     | ( w -- w )        | Generic honorific                                                                      | Simple word
06     | ( -- n )          | 0 / Positive numeric initiator                                                         | Number (Initiator)
07     | ( -- n )          | -0 / Negative numeric initiator                                                        | Number (Initiator)
11     | ( -- n )          | 1                                                                                      | Number
22     | ( -- n )          | 2                                                                                      | Number
33     | ( -- n )          | 3                                                                                      | Number
44     | ( -- n )          | 4                                                                                      | Number
55     | ( -- n )          | 5                                                                                      | Number
66     | ( -- n )          | 6                                                                                      | Number
77     | ( -- n )          | 7                                                                                      | Number
88     | ( -- n )          | 8                                                                                      | Number
99     | ( -- n )          | 9                                                                                      | Number
aa     | ( -- n )          | a (10)                                                                                 | Number
bb     | ( -- n )          | b (11)                                                                                 | Number
cc     | ( -- n )          | c (12)                                                                                 | Number
dd     | ( -- n )          | d (13)                                                                                 | Number
ee     | ( -- n )          | e (14)                                                                                 | Number
ff     | ( -- n )          | f (15)                                                                                 | Number
f6     | ( -- n )          | Infinite                                                                               | Number
f7     | ( -- n )          | Negative infinite                                                                      | Number
0321   | ( n1 n2 -- n )    | n1 plus n2                                                                             | Number
0323   | ( -- w )          | Addition                                                                               | Number
0421   | ( n1 n2 -- n )    | n1 minus n2                                                                            | Number
0423   | ( -- w )          | Subtraction                                                                            | Number
0621   | ( n1 n2 -- n )    | n1 multiplied by n2                                                                    | Number
0623   | ( -- w )          | Multiplication                                                                         | Number
0721   | ( n1 n2 -- n )    | n1 divided by n2                                                                       | Number
0723   | ( -- w )          | Division                                                                               | Number
0643   | ( w1 w2 -- w )    | n1 is greater than n2 in value                                                         | Simple word
0743   | ( w1 w2 -- w )    | n1 is less than n2 in value                                                            | Simple word
03     | ( w1 w2 -- w )    | w1 and w2                                                                              | Simple word
0306   | ( w# -- w )       | w# and w# and w#...                                                                    | Simple numeric
03a0   | ( w -- w w )      | Duplicate a word                                                                       | Stack word
03a6   | ( w -- w# )       | Duplicate a word multiple times                                                        | Stack numeric
04     | ( w1 w2 -- w )    | w1 or w2                                                                               | Simple word
0406   | ( w# -- w )       | w# or w# or w#                                                                         | Simple numeric
04a0   | ( w -- )          | Forget a word                                                                          | Stack word
04a6   | ( w# -- )         | Forget multiple words                                                                  | Stack numeric
06c3   | ( -- w )          | Positive response                                                                      | Simple word
07c3   | ( -- w )          | Negative response                                                                      | Simple word 
12     | ( w1 w2 -- w )    | The w1 property of w2                                                                  | Simple word
13     | ( w1 w2 -- w )    | w1 has the property w2                                                                 | Simple word
14     | ( n1 n2 -- n )    | n1 through n2                                                                          | Number
1d     | ( w x -- w )      | Coins x with the implication of w as an honorific                                      | Contextual word
1e     | ( w x -- w )      | Coin a reference to w as x ((Nick)name someone/something)                              | Contextual word
1f     | ( w x -- w )      | Coin x with the meaning of w                                                           | Contextual word
31     | ( w -- w )        | Apply the interrogative mood / Question the existence/truth of w                       | Simple word
32     | ( w -- w )        | Apply the deductive mood / Express that w has been deductively proven to exist/be true | Simple word
33     | ( w -- w )        | Apply the potential mood / Express that w may exist/be true                            | Simple word
34     | ( -- w )          | Symbol (Generic indefinite pronoun)                                                    | Pronoun
43     | ( w1 w2 -- w )    | w1 is the same as w2                                                                   | Simple word
44     | ( -- w )          | Number / amount / point                                                                | Simple word
45     | ( w1 w2 -- w )    | Apply a number to a word / Pluralize                                                   | Simple word
46     | ( w1 w2 -- w )    | w1 is related to w2                                                                    | Simple word
47     | ( w -- n )        | Facts in w                                                                             | Simple word
48     | ( w1 w2 -- w )    | w1 exists as w2                                                                        | Simple word
49     | ( w1 w2 -- w )    | w1 controls w2                                                                         | Simple word
4a     | ( w1 w2 -- w )    | w1 has w2                                                                              | Simple word
4d     | ( w1 w2 -- w )    | w1 is (typological) w2                                                                 | Simple word
51     | ( -- w )          | Thought / Instance of knowledge                                                        | Simple word
52     | ( -- w )          | Question                                                                               | Simple word
53     | ( -- w )          | Demand / Wish                                                                          | Simple word
54     | ( -- w )          | Event / Action                                                                         | Simple word
56     | ( -- w )          | Cause                                                                                  | Simple word
57     | ( -- w )          | Effect                                                                                 | Simple word
58     | ( w1 w2 -- w )    | w1 does w2                                                                             | Simple word
59     | ( w1 w2 -- w )    | w1 activates w2                                                                        | Simple word
63     | ( w1 w2 -- w )    | If w1 then w2                                                                          | Simple word
67     | ( w1 w2 w3 -- w ) | If w1 then w2, otherwise w3                                                            | Simple word
71     | ( -- )            | Topic marker of the previous word                                                      | Contextual word
72     | ( -- )            | Comment marker of the previous word                                                    | Contextual word
73     | ( w -- q )        | Quote                                                                                  | Simple word    
74     | ( w1 w2 -- q )    | Quote w1 as being from w2                                                              | Simple word    
7f     | ( -- n )          | Number above 1                                                                         | Number
8f     | ( w -- w )        | Negative (Not)                                                                         | Simple word
91     | ( -- w )          | Hard topic pronoun                                                                     | Pronoun
92     | ( -- w )          | Hard comment pronoun                                                                   | Pronoun
a1     | ( w -- w )        | Soft topic pronoun                                                                     | Pronoun
a2     | ( w -- w )        | Soft comment pronoun                                                                   | Pronoun
a3     | ( -- w )          | Equivalent 2st person pronoun                                                          | Pronoun
a7     | ( -- w )          | Associative 2st person pronoun                                                         | Pronoun
b1     | ( w -- w )        | Apply the indicative mood / Express that w is true                                     | Simple word
b2     | ( w -- w )        | Apply the commisive mood / Promise w                                                   | Simple word
b3     | ( -- w )          | Equivalent 1st person pronoun                                                          | Pronoun
b5     | ( w -- w )        | Apply the evidential mood / Express that w is evidently existant/true                  | Simple word
b6     | ( w -- w )        | Apply the directive mood / Demand w                                                    | Simple word
b7     | ( -- w )          | Associative 1st person pronoun                                                         | Pronoun
c2     | ( w -- w )        | Apply the volitive mood / Express desire/need of w                                     | Simple word
c3     | ( -- w )          | Neutral response                                                                       | Simple word
cd     | ( w -- w )        | Apply the neutral tense                                                                | Simple word
ce     | ( w1 w2 -- w )    | State that w1 will/has been be fulfilled when w2 is/was fulfilled                      | Simple word
d1     | ( -- w )          | Part                                                                                   | Simple word
d2     | ( -- w )          | Shape                                                                                  | Simple word
d3     | ( -- w )          | Direction / Line                                                                       | Simple word
d4     | ( -- w )          | Angle                                                                                  | Simple word
d5     | ( w1 w2 -- w )    | w1 relative to w2                                                                      | Simple word
d6     | ( w1 w2 -- w )    | w1 from w2                                                                             | Simple word
d7     | ( w1 w2 -- w )    | w1 towards w2                                                                          | Simple word
d9     | ( -- w )          | Empty space                                                                            | Simple word
da     | ( -- w )          | Surface (of something)                                                                 | Simple word
db     | ( -- w )          | Contact                                                                                | Simple word
e1     | ( w1 w2 -- w )    | w1 creates w2                                                                          | Simple word
e2     | ( w1 w2 -- w )    | w1 changes w2                                                                          | Simple word
e3     | ( w1 w2 -- w )    | w1 via w2                                                                              | Simple word
e4     | ( -- w )          | Possibility                                                                            | Simple word
e5     | ( -- w )          | Uncertainty                                                                            | Simple word
e6     | ( -- w )          | Predictable                                                                            | Simple word
e7     | ( -- w )          | Movement                                                                               | Simple word
e8     | ( -- w )          | Overlap                                                                                | Simple word
e9     | ( w1 w2 -- w )    | w1 between w2                                                                          | Simple word
ea     | ( -- w )          | Progress                                                                               | Simple word
eb     | ( -- w )          | Time                                                                                   | Simple word
ec     | ( w -- w )        | Apply the past tense                                                                   | Simple word
ed     | ( w -- w )        | Apply the present tense                                                                | Simple word
ef     | ( w -- w )        | Apply the future tense                                                                 | Simple word
f0     | ( w -- w )        | All w                                                                                  | Simple word
f1     | ( w n -- w )      | w happens n times                                                                      | Simple word

0x73 and 0x74 are literal quotes without a specified method of communication, the only information that is given from these is something that was said somehow, and in the case of 0x74, the speaker.

(w) is a word, (q) is also a word but is exclusively used to refer to quotes.

(n) is a number.



Note that most of the current hex values are not guarenteed for the final version of HACAL, though they will be grouped into categories, where each member of a category will be adjecent to another member of the same category.

The generic honorific and static numbers such as 06 and 22 will remain the same, as well as b3, b7, a3, a7, 1d, 1e, and 1f.

They will not take 0x spots that have not already been taken. Members of categories will generally share consonants with eachother and be placed adjacent to eachother as well.

Categories (In lowest to highest order):
- Other numbers
- Stack words
- Contextual words
- Pronouns
- Moods
- Quote words
- Otherwise uncategorized ( w1 w2 -- w )
- Otherwise uncategorized ( w -- w )
- Otherwise uncategorized ( -- w )
- Everything else

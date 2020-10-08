Hex    | Latin      | Stack effect      | English definition                                                                     | Class
------ | ---------- | ----------------- | -------------------------------------------------------------------------------------- | ----------------------
06     | Ee         | ( -- n )          | 0 / Positive numeric initiator                                                         | Number (Initiator)
07     | Ii         | ( -- n )          | -0 / Negative numeric initiator                                                        | Number (Initiator)
11     | Pa         | ( -- n )          | 1                                                                                      | Number
22     | Te         | ( -- n )          | 2                                                                                      | Number
33     | Ki         | ( -- n )          | 3                                                                                      | Number
44     | Su         | ( -- n )          | 4                                                                                      | Number
55     | Caa        | ( -- n )          | 5                                                                                      | Number
66     | Fee        | ( -- n )          | 6                                                                                      | Number
77     | Lii        | ( -- n )          | 7                                                                                      | Number
88     | Juu        | ( -- n )          | 8                                                                                      | Number
99     | Ra,        | ( -- n )          | 9                                                                                      | Number
aa     | Nu,        | ( -- n )          | a (10)                                                                                 | Number
bb     | Ma;        | ( -- n )          | b (11)                                                                                 | Number
cc     | Gu;        | ( -- n )          | c (12)                                                                                 | Number
dd     | Hv         | ( -- n )          | d (13)                                                                                 | Number
ee     | Xvv        | ( -- n )          | e (14)                                                                                 | Number
ff     | Tcv,       | ( -- n )          | f (15)                                                                                 | Number
f6     | Tcee       | ( -- n )          | Infinite                                                                               | Number
f7     | Tcii       | ( -- n )          | Negative infinite                                                                      | Number
0321   | Ita        | ( n1 n2 -- n )    | n1 plus n2                                                                             | Number
0323   | Iti        | ( -- w )          | Addition                                                                               | Number
0421   | Uta        | ( n1 n2 -- n )    | n1 minus n2                                                                            | Number
0423   | Uti        | ( -- w )          | Subtraction                                                                            | Number
0621   | Eeta       | ( n1 n2 -- n )    | n1 multiplied by n2                                                                    | Number
0623   | Eeti       | ( -- w )          | Multiplication                                                                         | Number
0721   | Iita       | ( n1 n2 -- n )    | n1 divided by n2                                                                       | Number
0723   | Iiti       | ( -- w )          | Division                                                                               | Number
0643   | Eesi       | ( w1 w2 -- w )    | n1 is greater than n2 in value                                                         | Simple word
0743   | Iisi       | ( w1 w2 -- w )    | n1 is less than n2 in value                                                            | Simple word
03     | I          | ( w1 w2 -- w )    | w1 and w2                                                                              | Simple word
0306   | Iee        | ( w# -- w )       | w# and w# and w#...                                                                    | Simple numeric
03a0   | In         | ( w -- w w )      | Duplicate a word                                                                       | Stack word
03a6   | Inee       | ( w -- w# )       | Duplicate a word multiple times                                                        | Stack numeric
04     | U          | ( w1 w2 -- w )    | w1 or w2                                                                               | Simple word
0406   | Uee        | ( w# -- w )       | w# or w# or w#                                                                         | Simple numeric
04a0   | Un         | ( w -- )          | Forget a word                                                                          | Stack word
04a6   | Unee       | ( w# -- )         | Forget multiple words                                                                  | Stack numeric
06c3   | Eegi       | ( -- w )          | Positive response                                                                      | Simple word
07c3   | Iigi       | ( -- w )          | Negative response                                                                      | Simple word 
12     | Pe         | ( w1 w2 -- w )    | The w1 property of w2                                                                  | Simple word
13     | Pi         | ( w1 w2 -- w )    | w1 has the property w2                                                                 | Simple word
14     | Pu         | ( n1 n2 -- n )    | n1 through n2                                                                          | Number
1e     | Pvv        | ( w x -- w )      | Coin a reference to w as x ((Nick)name someone/something)                              | Contextual word
1f     | Pv,        | ( w x -- w )      | Coin x with the meaning of w                                                           | Contextual word
31     | Ka         | ( w -- w )        | Apply the interrogative mood / Question the existence/truth of w                       | Simple word
32     | Ke         | ( w -- w )        | Apply the deductive mood / Express that w has been deductively proven to exist/be true | Simple word
33     | Ki         | ( w -- w )        | Apply the potential mood / Express that w may exist/be true                            | Simple word
34     | Ku         | ( -- w )          | Symbol (Generic indefinite pronoun)                                                    | Pronoun
43     | Si         | ( w1 w2 -- w )    | w1 is the same as w2                                                                   | Simple word
44     | Su         | ( -- w )          | Number / amount / point                                                                | Simple word
45     | Saa        | ( w1 w2 -- w )    | Apply a number to a word / Pluralize                                                   | Simple word
46     | See        | ( w1 w2 -- w )    | w1 is related to w2                                                                    | Simple word
47     | Sii        | ( w -- w )        | Is mostly true/existant                                                                | Simple word
48     | Suu        | ( w1 w2 -- w )    | w1 exists as w2                                                                        | Simple word
49     | Sa,        | ( w1 w2 -- w )    | w1 controls w2                                                                         | Simple word
4a     | Su,        | ( w1 w2 -- w )    | w1 contains w2                                                                         | Simple word
4d     | Sv         | ( w1 w2 -- w )    | w1 is (typological) w2                                                                 | Simple word
51     | Ca         | ( -- w )          | Thought / Instance of knowledge                                                        | Simple word
52     | Ce         | ( -- w )          | Question                                                                               | Simple word
53     | Ci         | ( -- w )          | Demand / Wish                                                                          | Simple word
54     | Cu         | ( -- w )          | Event / Action                                                                         | Simple word
56     | Cee        | ( -- w )          | Cause                                                                                  | Simple word
57     | Cii        | ( -- w )          | Effect                                                                                 | Simple word
58     | Cuu        | ( w1 w2 -- w )    | w1 does w2                                                                             | Simple word
59     | Ca,        | ( w1 w2 -- w )    | w1 activates w2                                                                        | Simple word
63     | Fi         | ( w1 w2 -- w )    | If w1 then w2                                                                          | Simple word
67     | Fii        | ( w1 w2 w3 -- w ) | If w1 then w2, otherwise w3                                                            | Simple word
71     | La         | ( -- )            | Topic marker of the previous word                                                      | Contextual word
72     | Le         | ( -- )            | Comment marker of the previous word                                                    | Contextual word
7f     | Lv,        | ( -- n )          | Number above 1                                                                         | Number
8f     | Jv,        | ( w -- w )        | Negative (Not)                                                                         | Simple word
91     | Ra         | ( -- w )          | Hard topic pronoun                                                                     | Pronoun
92     | Re         | ( -- w )          | Hard comment pronoun                                                                   | Pronoun
a1     | Na         | ( w -- w )        | Soft topic pronoun                                                                     | Pronoun
a2     | Ne         | ( w -- w )        | Soft comment pronoun                                                                   | Pronoun
a3     | Ni         | ( -- w )          | Equivalent 2st person pronoun                                                          | Pronoun
a7     | Nii        | ( -- w )          | Associative 2st person pronoun                                                         | Pronoun
b1     | Ma         | ( w -- w )        | Apply the indicative mood / Express that w is true                                     | Simple word
b2     | Me         | ( w -- w )        | Apply the commisive mood / Promise w                                                   | Simple word
b3     | Mi         | ( -- w )          | Equivalent 1st person pronoun                                                          | Pronoun
b5     | Maa        | ( w -- w )        | Apply the evidential mood / Express that w is evidently existant/true                  | Simple word
b6     | Mee        | ( w -- w )        | Apply the directive mood / Demand w                                                    | Simple word
b7     | Mii        | ( -- w )          | Associative 1st person pronoun                                                         | Pronoun
c2     | Ge         | ( w -- w )        | Apply the volitive mood / Express desire/need of w                                     | Simple word
c3     | Gi         | ( -- w )          | Neutral response                                                                       | Simple word
cd     | Gv         | ( w -- w )        | Apply the neutral tense                                                                | Simple word
ce     | Gvv        | ( w1 w2 -- w )    | State that w1 will/has been be fulfilled when w2 is/was fulfilled                      | Simple word
d1     | Ha         | ( -- w )          | Size                                                                                   | Simple word
d2     | He         | ( -- w )          | Shape                                                                                  | Simple word
d3     | Hi         | ( -- w )          | Direction / Line                                                                       | Simple word
d4     | Hu         | ( -- w )          | Angle                                                                                  | Simple word
d5     | Haa        | ( w1 w2 -- w )    | w1 relative to w2                                                                      | Simple word
d6     | Hee        | ( w1 w2 -- w )    | w1 from w2                                                                             | Simple word
d7     | Hii        | ( w1 w2 -- w )    | w1 towards w2                                                                          | Simple word
d9     | Ha,        | ( -- w )          | Empty space                                                                            | Simple word
da     | Hu,        | ( -- w )          | Surface (of something)                                                                 | Simple word
db     | Ha;        | ( -- w )          | Contact                                                                                | Simple word
e1     | Xa         | ( w1 w2 -- w )    | w1 creates w2                                                                          | Simple word
e2     | Xe         | ( w1 w2 -- w )    | w1 changes w2                                                                          | Simple word
e3     | Xi         | ( w1 w2 -- w )    | w1 via w2                                                                              | Simple word
e4     | Xu         | ( -- w )          | Possibility                                                                            | Simple word
e5     | Xaa        | ( -- w )          | Uncertainty                                                                            | Simple word
e6     | Xee        | ( -- w )          | Predictable                                                                            | Simple word
e7     | Xii        | ( -- w )          | Movement                                                                               | Simple word
e8     | Xuu        | ( -- w )          | Overlap                                                                                | Simple word
e9     | Xa,        | ( w1 w2 -- w )    | w1 between w2                                                                          | Simple word
ea     | Xu,        | ( -- w )          | Progress                                                                               | Simple word
eb     | Xa;        | ( -- w )          | Time                                                                                   | Simple word
ec     | Xu;        | ( w -- w )        | Apply the past tense                                                                   | Simple word
ed     | Xv         | ( w -- w )        | Apply the present tense                                                                | Simple word
ef     | Xv,        | ( w -- w )        | Apply the future tense                                                                 | Simple word

# Draft core words

These words are words whose future existence as a core word or as a standard coin are uncertain. For until they can be defined as a coin using any non-draft core words they will remain as a core word.

Hex    | Latin      | Stack effect      | English definition                                                                     | Class
------ | ---------- | ----------------- | -------------------------------------------------------------------------------------- | ----------------------
73     | Li         | ( -- w )          | Undulation (Not necessarily even or predictable)                                       | Simple word
0f     | V,         | ( -- w )          | A full turn of a circle                                                                | Simple word 
0e     | Vv         | ( w -- w )        | The middle of w                                                                        | Simple word

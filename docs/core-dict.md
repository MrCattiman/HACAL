Hex    | Latin      | Stack effect      | English definition                                                                   | Class
------ | ---------- | ----------------- | ------------------------------------------------------------------------------------ | ----------------------
03     | I          | ( w1 w2 -- w )    | w1 and w2                                                                            | Verb
0306   | Iee        | ( w# -- w )       | w# and w# and w#...                                                                  | Simple numeric
03a0   | In         | ( w -- w w )      | Duplicate a word                                                                     | Stack word
03a6   | Inee       | ( w -- w# )       | Duplicate a word multiply                                                            | Stack numeric
04     | U          | ( w1 w2 -- w )    | w1 or w2                                                                             | Verb
0406   | Uee        | ( w# -- w )       | w# or w# or w#                                                                       | Simple numeric
04a0   | Un         | ( w -- )          | Forget a word                                                                        | Stack word
04a6   | Unee       | ( w# -- )         | Forget words                                                                         | Stack numeric
13     | Pi         | ( w1 w2 -- w )    | w1 is of the property w2                                                             | Simple word
45     | Saa        | ( w n -- w )      | Apply a number to a word                                                             | Number
06     | Ee         | ( -- n )          | 0 / Positive numeric initiator                                                       | Number (Initiator)
07     | Ii         | ( -- n )          | -0 / Negative numeric initiator                                                      | Number (Initiator)
11     | Pa         | ( -- n )          | 1                                                                                    | Number
22     | Te         | ( -- n )          | 2                                                                                    | Number
33     | Ki         | ( -- n )          | 3                                                                                    | Number
44     | Su         | ( -- n )          | 4                                                                                    | Number
55     | Caa        | ( -- n )          | 5                                                                                    | Number
66     | Fee        | ( -- n )          | 6                                                                                    | Number
77     | Lii        | ( -- n )          | 7                                                                                    | Number
88     | Juu        | ( -- n )          | 8                                                                                    | Number
99     | Ra,        | ( -- n )          | 9                                                                                    | Number
aa     | Nu,        | ( -- n )          | a (10)                                                                               | Number
bb     | Ma;        | ( -- n )          | b (11)                                                                               | Number
cc     | Gu;        | ( -- n )          | c (12)                                                                               | Number
dd     | Hv         | ( -- n )          | d (13)                                                                               | Number
ee     | Xvv        | ( -- n )          | e (14)                                                                               | Number
ff     | Tcv,       | ( -- n )          | f (15)                                                                               | Number
f6     | Tcee       | ( -- n )          | Infinite                                                                             | Number
f7     | Tcii       | ( -- n )          | Negative infinite                                                                    | Number
7f     | Lv,        | ( -- n )          | Number above 1                                                                       | Number
077f   | Iilv,      | ( w -- w )        | Negative (Not)                                                                       | Simple word
14     | Pu         | ( n1 n2 -- n )    | n1 through n2                                                                        | Number
0321   | Ita        | ( n1 n2 -- n )    | n1 plus n2                                                                           | Number
0421   | Uta        | ( n1 n2 -- n )    | n1 minus n2                                                                          | Number
0621   | Eeta       | ( n1 n2 -- n )    | n1 multiplied by n2                                                                  | Number
0721   | Iita       | ( n1 n2 -- n )    | n1 divided by n2                                                                     | Number
7f21   | Lv,ta      | ( n1 n2 -- n )    | n1 to the power of n2                                                                | Number
077f21 | Iilv,ta    | ( n1 n2 -- n )    | The n2 root of n1                                                                    | Number

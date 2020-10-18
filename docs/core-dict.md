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
12     | ( n1 n2 -- n )    | n1 + n2                                                                                | Number
13     | ( n1 n2 -- n )    | n1 - n2                                                                                | Number
14     | ( n1 n2 -- n )    | n1 times n2                                                                            | Number
15     | ( n1 n2 -- n )    | n1 divided by n2                                                                       | Number
16     | ( n1 n2 -- n )    | n1 bitwise AND n2                                                                      | Number
17     | ( n1 n2 -- n )    | n1 bitwise OR n2                                                                       | Number
18     | ( n1 n2 -- n )    | n1 bitwise NOT n2                                                                      | Number
19     | ( n1 n2 -- n )    | n1 is less than n2 in value                                                            | Number
1a     | ( n1 n2 -- n )    | n1 is equal to n2 in value                                                             | Number
1b     | ( n1 n2 -- n )    | n1 is greater than n2 in value                                                         | Number
1c     | ( n1 n2 -- n )    | n1 through n2                                                                          | Number
1d     | ( w x -- )        | Coins x as an honorific with the implication of w                                      | Contextual word
1e     | ( w x -- )        | Coin a reference to w as x ((Nick)name someone/something)                              | Contextual word
1f     | ( w x -- )        | Coin x with the meaning of w                                                           | Contextual word
21     | ( w -- w# )       | Duplicate w once or, if numeric, # times                                               | Stack (numeric)
23     | ( w# -- )         | Forget a word or, if numeric, forget # words                                           | Stack (numeric)
24     | ( -- )            | Topic marker of the previous word                                                      | Contextual word
25     | ( -- )            | Comment marker of the previous word                                                    | Contextual word
26     | ( -- w )          | Hard topic pronoun                                                                     | Pronoun
27     | ( -- w )          | Hard comment pronoun                                                                   | Pronoun
28     | ( -- w )          | Soft topic pronoun                                                                     | Pronoun
29     | ( -- w )          | Soft comment pronoun                                                                   | Pronoun
2a     | ( -- w )          | Indefinite pronoun                                                                     | Pronoun
31     | ( w -- w )        | Question the existence/truth of w (Interrogative mood)                                 | Simple word
32     | ( w -- w )        | Express that w has been deductively proven to exist/be true (Deductive mood)           | Simple word
34     | ( w -- w )        | Express that w may exist/be true (Potential mood)                                      | Simple word
35     | ( w -- w )        | Express that w is true (Indicitive mood)                                               | Simple word
36     | ( w -- w )        | Promise w (Comissive mood)                                                             | Simple word
37     | ( w -- w )        | Express that w is evidently existant/true (Evidential mood)                            | Simple word
38     | ( w -- w )        | Demand w (Directive mood)                                                              | Simple word
39     | ( w -- w )        | Express desire/need of w (Volitive mood)                                               | Simple word
3a     | ( w -- w )        | Apply the neutral tense                                                                | Simple word
3b     | ( w -- w )        | Apply the past tense                                                                   | Simple word
3c     | ( w -- w )        | Apply the present tense                                                                | Simple word
3d     | ( w -- w )        | Apply the future tense                                                                 | Simple word
41     | ( w -- q )        | Quote w                                                                                | Simple word
42     | ( w1 w2 -- q )    | Quote w1 as being from w2                                                              | Simple word
51     | ( w# -- w )       | w1 and w2 / (If numeric) w#, w#... and w#                                              | Simple (numeric)
52     | ( w# -- w )       | w1 or w2 / (If numeric) w#, w#... or w#                                                | Simple (numeric)
53     | ( w1 w2 -- w )    | The w1 property of w2                                                                  | Simple word
54     | ( w1 w2 -- w )    | w1 has the property w2                                                                 | Simple word
56     | ( w1 w2 -- w )    | w1 is the same as w2                                                                   | Simple word
57     | ( w1 w2 -- w )    | w1 is related to w2                                                                    | Simple word
58     | ( w1 w2 -- w )    | w1 is the same kind of thing as w2                                                     | Simple word
59     | ( w1 w2 -- w )    | w1 has w2                                                                              | Simple word
5a     | ( w1 w2 -- w )    | w1 does w2                                                                             | Simple word
5b     | ( w1 w2 -- w )    | w1 as/when w2                                                                          | Simple word
5c     | ( w1 w2 -- w )    | w1 relative to w2                                                                      | Simple word
5d     | ( w1 w2 -- w )    | w1 from w2                                                                             | Simple word
5e     | ( w1 w2 -- w )    | w1 towards w2                                                                          | Simple word
5f     | ( w1 w2 -- w )    | w1 because w2                                                                          | Simple word
61     | ( w1 w2 -- w )    | w1 creates w2                                                                          | Simple word
62     | ( w1 w2 -- w )    | w1 changes w2                                                                          | Simple word
63     | ( w1 w2 -- w )    | w1 via w2                                                                              | Simple word
71     | ( w -- w )        | Negative (Not)                                                                         | Simple word
72     | ( w -- w )        | All w                                                                                  | Simple word
81     | ( -- w )          | Number / Amount / Point / Representative value / Symbol                                | Simple word
82     | ( -- w )          | Thought                                                                                | Simple word
83     | ( -- w )          | Question                                                                               | Simple word
84     | ( -- w )          | Demand / Wish                                                                          | Simple word
85     | ( -- w )          | Event / Action                                                                         | Simple word
86     | ( -- w )          | Cause                                                                                  | Simple word
87     | ( -- w )          | Effect                                                                                 | Simple word
88     | ( -- w )          | Part                                                                                   | Simple word
89     | ( -- w )          | Progress                                                                               | Simple word
8a     | ( -- w )          | Time                                                                                   | Simple word
8b     | ( -- w )          | Object                                                                                 | Simple word
f1     | ( w1 w2 -- w )    | If w1 then w2                                                                          | Simple word
f2     | ( w1 w2 w3 -- w ) | If w1 then w2 otherwise w3                                                             | Simple word
f3     | ( w -- n )        | Facts in w                                                                             | Number
f4     | ( w n --  w )     | w happens n times                                                                      | Simple word

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
- Moods / tenses
- Quote words
- Otherwise uncategorized ( w1 w2 -- w )
- Otherwise uncategorized ( w -- w )
- Otherwise uncategorized ( -- w )
- Everything else
- Responses and logic (As late as possible)

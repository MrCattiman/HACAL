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
19     | ( n1 n2 -- n )    | n1 bit shift by n2 (right if negative, left if positive)                               | Number
1a     | ( n1 n2 -- n )    | n1 is less than n2 in value                                                            | Number
1b     | ( n1 n2 -- n )    | n1 is equal to n2 in value                                                             | Number
1c     | ( n1 n2 -- n )    | n1 is greater than n2 in value                                                         | Number
1d     | ( n1 n2 -- n )    | n1 through n2                                                                          | Number
21     | ( w1 r (n) -- w1 )| Context registry setter                                                                | Contextual numeric
23     | ( r -- w )        | Context registry pronoun (caller)                                                      | Numeric pronoun
24     | ( -- w )          | Indefinite pronoun                                                                     | Pronoun
31     | ( w -- w )        | w is a statement                                                                       | Simple word
32     | ( w -- w )        | w is a question                                                                        | Simple word
33     | ( w -- w )        | w has a neutral tense                                                                  | Simple word
34     | ( w -- w )        | w has the past tense                                                                   | Simple word
35     | ( w -- w )        | w has the present tense                                                                | Simple word
36     | ( w -- w )        | w has the future tense                                                                 | Simple word
41     | ( w -- q )        | Quote w                                                                                | Simple word
42     | ( w1 w2 -- q )    | Quote w1 as being from w2                                                              | Simple word
43     | ( q w -- w )      | q is encoded in w                                                                      | Simple word
51     | ( w# -- w )       | w1 and w2 / (If numeric) w#, w#... and w#                                              | Simple (numeric)
52     | ( w# -- w )       | w1 or w2 / (If numeric) w#, w#... or w# (exclusive)                                    | Simple (numeric)
53     | ( w# -- w )       | w1 or w2 / (If numeric) w#, w#... or w# (inclusive)                                    | Simple (numeric)
54     | ( w1 w2 -- w )    | w1 of w2  (genitive)                                                                   | Simple word
55     | ( w1 w2 -- w )    | w2 with w1 (reverse genitive)                                                          | Simple word
56     | ( w1 w2 -- w )    | w1 is w2                                                                               | Simple word
57     | ( w1 w2 -- w )    | w1 executes (performs) w2                                                              | Simple word
58     | ( w1 w2 -- w )    | w1 from w2                                                                             | Simple word
59     | ( w1 w2 -- w )    | w1 towards w2                                                                          | Simple word
5a     | ( w1 w2 -- w )    | w1 because w2                                                                          | Simple word
5b     | ( w1 w2 -- w )    | w1 makes/causes w2                                                                     | Simple word
5c     | ( w1 w2 -- w )    | w1 then w2 (Temporal)                                                                  | Simple word
5d     | ( w1 w2 -- w )    | w1 before w2 (Temporal)                                                                | Simple word
5e     | ( w1 w2 -- w )    | w2 wants or needs w1                                                                   | Simple word
5f     | ( w1 w2 -- w )    | between w1 and w2                                                                      | Simple word
71     | ( w -- w )        | Negative (Not)                                                                         | Simple word
72     | ( w -- w )        | All w                                                                                  | Simple word
73     | ( w -- w )        | w changes or moves                                                                     | Simple word
81     | ( -- w )          | Number / Amount / Point / Representative value / Symbol                                | Simple word
82     | ( -- w )          | Thought                                                                                | Simple word
83     | ( -- w )          | Question                                                                               | Simple word
84     | ( -- w )          | Demand / Wish / Command                                                                | Simple word
85     | ( -- w )          | Event / Action                                                                         | Simple word
86     | ( -- w )          | Time                                                                                   | Simple word
87     | ( -- w )          | Object / Thing                                                                         | Simple word
a1     | ( -- w )          | Second person pronoun (equivalent)                                                     | Pronoun
a2     | ( -- w )          | Second person pronoun (associative)                                                    | Pronoun
a3     | ( -- w )          | First person pronoun (equivalent)                                                      | Pronoun
a4     | ( -- w )          | First person pronoun (associative)                                                     | Pronoun
e1     | ( w x -- )        | Coins x as an honorific with the implication of w                                      | Contextual word
e2     | ( w x -- )        | Coin a reference to w as x ((Nick)name someone/something)                              | Contextual word
e3     | ( w x -- )        | Coin x with the meaning of w                                                           | Contextual word
f1     | ( w1 w2 -- w )    | If w1 then w2                                                                          | Simple word
f2     | ( w1 w2 w3 -- w ) | If w1 then w2 otherwise w3                                                             | Simple word
f3     | ( w -- n )        | Facts in w                                                                             | Number
f4     | ( w n -- w )      | w happens n times                                                                      | Simple word

# Special words, invalid outside of their appropriate contexts

Hex    | Stack effect      | English definition                                                                     | Class
------ | ----------------- | -------------------------------------------------------------------------------------- | --------------
de     | ( -- w# )         | Push # nonce words to the stack, only usable in definitions                            | Simple numeric
df     | ( w# -- )         | Consume # words, only usable in definitions                                            | Simple numeric

(w) is a phrase, (q) is also a phrase but is exclusively used to refer to quotes.

(r) is the significant noun (A word that pushes meaning onto the stack without taking any parameters), which is also the noun that is being referenced by the pronoun. In the case that there are two or more of the same noun, an additional number is required, which should equal the amount of words that should be skipped over from the beginning of the phrase to arrive at the word that is referenced. If no number is given, then the first instance of the significant noun is used. The significant noun may be more than one word.

(n) is a number, numbers can also be used as phrasess.



Note that most of the current hex values are not guarenteed for the final version of HACAL, though they will be grouped into categories, where each member of a category will be adjecent to another member of the same category.

The generic honorific and static numbers such as 06 and 22 will remain the same, as well as b3, b8, a3, a8, 1d, 1e, and 1f.

They will not take 0x spots that have not already been taken. Members of categories will generally share consonants with eachother and be placed adjacent to eachother as well.

Categories (In lowest to highest order):
- Other numbers
- Pronouns and context registry
- Moods / tenses
- Quote words
- Otherwise uncategorized ( w1 w2 -- w )
- Otherwise uncategorized ( w -- w )
- Otherwise uncategorized ( -- w )
- Everything else
- coiners (at 0xeX)
- Responses and logic (At 0xfX)

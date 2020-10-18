# Phonology/Orthography

## Hex format, phonotactics, and nulls
In HACAL, each consonant and vowel is designated a number from 0 to 15. 0 as a consonant or vowel (A null consonant/vowel) is not pronounced, the null vowel may optionally be pronounced as a mid vowel, though. When representing HACAL in hexadecimal, a vowel always follows a consonant, so 0xdddd would be pronounced as /høhø/. HACAL is also primarilly a syllabic language, the only consonants that can precede another or not have a following vowel are nasals and /l/.
- 0 - | No required pronunciation
- 0 / | No required pronunciation
	- Optionally /ə/

## Consonants
Hex | Latin   | Sound
--- | ------- | ----------------------------------------------------
1   | P       | /p/
2   | T       | /t/
3   | K       | /k/
4   | S       | /s/
5   | C       | /ʃ/
6   | F       | /f/
7   | L       | /l/, /ɾ/, or /ɹ/
8   | J       | /j/
9   | R       | /r/ or /ʀ/
a   | N       | /n/
b   | M       | /m/
c   | G       | /ŋ/ or /ɴ/
d   | H       | /h/
e   | W or Q  | /w/ or /q/
f   | Z       | /ts/ or /tʃ/

Voiced variations of the same consonants, such as /b/ in place of /p/ are also accepted, ones that are already voiced do not have legal unvoiced counterparts.

## Vowels
Hex | Latin           | Sound
--- | --------------- | ------------
1   | A or A-         | /a/
2   | E or E-         | /e/
3   | I or I-         | /i/
4   | U or U-         | /u/
5   | Ā or Aa         | /aː/
6   | Ē or Ee         | /eː/
7   | Ī or Ii         | /iː/
8   | Ū or Uu         | /uː/
9   | Ą or Av         | /ã/
a   | Ę or Ev         | /ẽ/
b   | Į or Iv         | /ĩ/
c   | Ų or Uv         | /ũ/
d   | Ä or Ay         | /aiɣ/
e   | Ë or Ey         | /eiɣ/
f   | Ü or Uy         | /uiɣ/

Note that, instead of /ɣ/,  /ħ/ or /x/ can be used.

# Misc.
Duplicate vowels, or triphthongs should be interrupted by /ʔ/ each time the length of a long vowel is met.

Examples (Without the consonant bits):

0x555 /aːʔaːʔaː/

0x1111 /aʔaʔaʔa/

0x123 /aeʔi/

0x523 /aːeʔi/

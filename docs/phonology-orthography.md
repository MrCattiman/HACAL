#Phonology/Orthography

##Hex format, phonotactics, and nulls
In HACAL, each consonant and vowel is designated a number from 0 to 15. 0 as a consonant or vowel (A null consonant/vowel) is not pronounced, the null vowel may optionally be pronounced as a mid vowel, though. When representing HACAL in hexadecimal, a vowel always follows a consonant, so 0xdddd would be pronounced as /høhø/. HACAL is also primarilly a syllabic language, the only consonants that can precede another or not have a following vowel are nasals and /l/.
- 0 - | No required pronunciation
- 0 / | No required pronunciation
	- Optionally /ə/

##Stops
- 1 P | /p/
- 2 T | /t/
- 3 K | /k/
- 4 S | /s/
- 5 C | /ʃ/
- 6 F | /f/
- 7 L | /l/
- 8 J | /j/
- 9 R | (Rhotic trill, tap, or similar sound, or uvular trill)
- a N | /n/
- b M | /m/
- c G | /ŋ/ or /ɴ/
- d H | /x/ or /h/
- e X | /θ/
- f Tc or Z | /ts/ or /tʃ/

Voiced variations of the same consonants, such as /b/ in place of /p/ are also accepted, ones that are already voiced do not have legal unvoiced counterparts.

##Vowels
- 1 A | /a/
- 2 E | /e/
- 3 I | /i/
- 4 U | /u/
- 5 Aa | /aː/
- 6 Ee | /eː/
- 7 Ii | /iː/
- 8 Uu | /uː/
- 9 A, or Ą | /ã/ or /ẽ/
- a U, or Ų | /ĩ/ or /ũ/
- b Aa; or Ąą | /ãː/ or /ẽː/
- c Uu; or Ųų | /ĩː/ or /ũː/
- d V | /ø/
- e Vv | /øː/
- f V, or V̨ | /ø̃/

#Misc.
Duplicate vowels, or triphthongs should be interrupted by /ʔ/ each time the length of a long vowel is met.

Examples (Without the consonant byte):

0x555 /aːʔaːʔaː/

0x1111 /aʔaʔaʔa/

0x123 /aeʔi/

0x523 /aːeʔi/

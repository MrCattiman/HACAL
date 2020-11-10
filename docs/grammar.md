# Word classes

# Basic grammar
## Basics
Sentences in HACAL are based on a stack model, with leftover values on a stack representing a sentence, and each real word representing a modification or addition of a value on a stack.

There are few distinct word classes in HACAL:
- Simple word
  - Adds meaning to the stack.
- Number
  - Represents a number in hexadecimal.
  - Can be concatenated with other numbers without a space (null).
  - Must be concatenated if the number is above 15 or below 0.
  - The most significant digit of a number is always spoken first.
  - Some numbers cannot be affixed to another, specifically any number that does not represent a positive integer from 0 to 15.
- Numeric
  - Has subclasses based on other word classes (Such as "Contextual numeric")
  - A verb with a variable amount of inputs, the number of input indicated by a number affixed to it, the number not requiring an initiator.
- Contextual word
  - Adds context to a conversation, or defines a word to be remembered.
- Coin
  - A word defined in HACAL using a contextual word, can never be a core word.
  - (Nick)Name
    - A reference to something/someone.
    - Interpreted as a normal (non-name) coin unless consumed by a word or there is no other normal coin with the same value.
  - Honorific
    - Tells that the previous word is a name and may imply additional information about them.
    - Consumes a word.
    - The generic honorific isn't a coin, and instead a simple word
- Pronoun
  - A word that references the instance of another word that has been used previously.

## The meanings of sentences
Every word in HACAL is singular, indicative, and tense-neutral by default.

The following tenses exist in HACAL:
- Past
- Present
- Future
- Neutral 

Please note that, because there is no distinction between nouns and verbs, any word may have a tense and mood. Also, the meaning of a noun without a verb in HACAL, in English could be interpreted as "(a) [noun] is (true)".

## Pronouns
### The word registry
Words can be referred to in a definitive manner without names using word registry words.

Word registry words are all numerics, the number in the numeric represents the id of a register where the word's context is stored.

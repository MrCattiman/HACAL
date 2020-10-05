# Basic grammar
## Basics
Sentences in HACAL are based on a stack model, with leftover values on a stack representing a sentence, and each word representing a modification or addition of a value on a stack.

There are few distinct word classes in HACAL, the letter in parentheses is shorthand for the type of the word in a definition of stack effects for a word:
- Simple word
  - Adds meaning to the stack.
- Stack word
  - Removes, swaps, duplicates, or otherwise effects the stack without necessarily adding information.
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
- Pronoun
  - A word that references the instance of another word that has been used previously.

Words in HACAL can be described as nouns, intransitive verbs, and transitive verbs, depending on how many values are added or removed from the stack. A noun would add a value to the stack and not require any values, an intransitive verb would add a value to the stack and also require a value, and a transitive verb would add a value to the stack and also require multiple values.

The format for the definition of a word in this documentation is as follows:

HEX LATIN ( -- ) DEFINITION

HEX represents the hexadecimal representation of a word, LATIN represents the latin representation of a word, the contents of the parentheses is the stack effect (The parentheses will not be omitted or replaced), and DEFINITION is the definition of the word, in english. Text on the left side of the -- represents input values, and text on the right represents output values.

An example of a definition:

11 Pa ( w1 w2 -- w) w1 of w2; w2's w1

Please note that this is not the real definition of "Pa", and is just an example of a definition.

## The meanings of sentences
Every word in HACAL is singular, indicative, and tense-neutral by default.

The following moods exist in HACAL:
- Realis (Not a separate mood)
  - Indicative
  - Evidential
- Irrealis (Not a separate mood)
  - Deontic (Not a separate mood)
    - Commisive
    - Directive
    - Volitive
  - Epistemic
    - Interrogative
    - Assumptive
      - Speculative
    - Deductive
    - Potential

The following tenses exist in HACAL:
- Past
- Present
- Future
- Neutral 

Please note that, because there is no distinction between nouns and verbs, any word may have a tense and mood. Also, the meaning of a noun without a verb in HACAL is "(a) [noun] is (true)".

## Pronouns
In HACAL, there are definite pronouns for the 1st person, the 2nd person, the topic, and the comment. Topic and comment pronouns reference another word that was specifically marked as being a topic or comment. There are equivalent and associative forms of the 1st person and 2nd person pronouns, and there are hard and soft forms of the topic and comment pronouns.

The equivalent pronouns for the 1st person and the 2nd person, when made plural, refer to mostly indistinguishable instances of the 1st person/2nd person, as well as the 1st person/2nd person themselves. The associative pronouns for the 1st person and 2nd person, when made plural, refer to the 1st person/2nd person and things associated with them.

Soft topic/comment pronouns require a word and refer to a word of the same kind that was marked as a topic/comment. Hard topic/comment pronouns simply refer to the previous word that was marked as a topic/comment.

There is also a generic indefinite pronoun, which will be referred to as the symbol.

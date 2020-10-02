# Basic grammar
## Basics
Sentences in HACAL are based on the stack datatype, with leftover values on a stack representing a sentence, and each word representing a modification or addition of a value on a stack.

There are few distinct word classes in HACAL, the letter in parentheses is shorthand for the type of the word in a definition of stack effects for a word:
- Simple word
  - Adds meaning to the stack.
- Stack word
  - Removes, swaps, duplicates, or otherwise effects the stack without necessarily adding information.
- Number
  - Represents a number.
- Contextual word
  - Adds context to a conversation, or defines a word to be remembered.

Words in HACAL can be described as nouns, intransitive verbs, and transitive verbs, depending on how many values are added or removed from the stack. A noun would add a value to the stack and not require any values, an intransitive verb would add a value to the stack and also require a value, and a transitive verb would add a value to the stack and also require multiple values.

The format for the definition of a word in this documentation is as follows:

HEX LATIN ( -- ) DEFINITION

HEX represents the hexadecimal representation of a word, LATIN represents the latin representation of a word, the contents of the parentheses is the stack effect (The parentheses will not be omitted or replaced), and DEFINITION is the definition of the word, in english. Text on the left side of the -- represents input values, and text on the right represents output values.

An example of a definition:

11 Pa ( w1 w2 -- w) w1 of w2; w2's w1

Please note that this is not the real definition of "Pa", and is just an example of a definition.

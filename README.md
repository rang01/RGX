# RGX
ReGular expression eXchange format for controlled language application

Regular expressions are used for various applications. In some cases to validate input in a textfield based on controlled language.
RGX wants to document various attributes for regular expressions to transfer their use.

Common applications:
- segment detection in translations for example for correct use of spaces before units
- applying controlled language rules in editors
- checking text for character sequences

Attribute types:

- searchString, formulated as a RegularExpression
- ruleType, different types: Grammar, Words, Units, 
- shortDescription, short Description for the writer/translator/editor to read
- ruleExplanation, explanation of the rule for a writer/translator/editor to better understand the intention of the rule
- ruleType, rule types communicate to the writer if a rule should be taken as a "Note", "Warning" or "Forbidden" scenario of the detected character sequence
- negativeExample, an example sentence that contains the searchString as a negative example to be read by the writer/translator/editor
- positiveExample, a positive example of the sentence for the writer/translator/editor

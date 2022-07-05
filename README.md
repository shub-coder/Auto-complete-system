# Auto-complete-system

Sentence word nlp autocomplete

An autocomplete can be helpful, faster, convenient and also correct any grammatical / spelling error at the same time.

Suppose we have a situation in which a representative of a company is required to answer or ask same question over and over again to the customers, 
on the company's online platform. A system like auto complete can be of great help. Instead of typing same sentences or words again and again, 
the representative can get suggestions after typing few words. All such sugestions can help the representative to increase his speed of interaction.

If you were to type: `What is your`,
the tool would suggest:
> What is your account number?,
 What is your order number?,
 What is your phone number?

If you were to type: `How can I`,
the tool would suggest:
> How can I help you?,
 How can I call you?

The Natural Language Processing Model used here is based on probability. Language model assigns the probability to a sequence of words, in a way that more "likely" sequences receive higher scores. 
While a variety of language models have been developed, this project uses N-grams, a simple but powerful method for language modeling.

N-grams are also used in machine translation and speech recognition.

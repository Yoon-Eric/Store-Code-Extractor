Summary:
Whenever you make a purchase with a credit or debit card, it gets recorded in your account. The merchant information is an unstructured string with a 'store number' embedded somewhere in the string. In this project, I wrote scripts (non learning based vs learning based) to extract the correct store numbers from the merchant descriptors. I deleted some parts where the merchant descriptor is visible due to privacy concerns.

Method 1: I made a non-learning model first because I thought it will be very effective for this particular assignment. I used regular expression library and several if and then statements to make a function that can pick out the store number from transaction information string.

Method 2: I made a learning-based model using SpaCy library. I trained a transformer based neural network algorithm for NER in SpaCy library. I don't have a powerful GPU myself, so I couldn't design my own archetecture and experiment with pytorch.

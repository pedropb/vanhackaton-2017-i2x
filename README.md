# i2x Vanhackaton challenge of 2017.

Oh, no!

You have just completed a lengthy document when you have an unfortunate Find/Replace mishap. You have accidentally removed all spaces, punctuation, and capitalisation in the document.

A sentence like "I reset the computer. It still didn't boot!" would become iresetthecomputeritstilldidntboot".

You figure that you can add back in the punctation and capitalisation later, once you get the individual words properly separated. Most of the words will be in a dictionary, but some strings, like proper names, will not.


Given a dictionary (a list of words), design an algorithm to find the optimal way of "unconcatenating" a sequence of words. In this case, "optimal" is defined to be the parsing which minimizes the number of unrecognized sequences of characters.


For example, the string "jesslookedjustliketimherbrother" would be optimally parsed as "JESS looked just like TIM her brother". This parsing has seven unrecognized characters, which we have capitalised for clarity.
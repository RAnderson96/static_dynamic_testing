### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card): 
    if card.value = 1: # This should be card.value == 1 to make the condition a boolean statement
      return True
    else # This should be else:
      return False
   

  dif highest_card(self, card1 card2): # def not dif, and in the parameters card1 is missing a comma
  if card1.value > card2.value: # This and below code block all needs indented to the right
    return card # should be card1 not card
  else:
    return card2
  


def cards_total(self, cards): # Entire code block should be indented to right to be part of class CardGame
  total # This variable should be initialised equal to 0
  for card in cards: 
    total += card.value 
    return "You have a total of" + total # Indentation is incorrect, should be on same level as for loop, also total needs to be made to type String to be concatenated, should be a space after "of" to read better.
  
```

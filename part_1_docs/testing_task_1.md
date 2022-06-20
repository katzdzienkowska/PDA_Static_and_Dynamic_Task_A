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
    if card.value = 1:
  #above we are not assigning values, but comparing them, so incorrect operator has been used, should be: if card.value == 1:
      return True
    else
  #missing colon, should be: else:
      return False


  dif highest_card(self, card1 card2):
  #mispelled defining the method and missing coma between the arguments, should be: def highest_card(self, card1, card2):
  if card1.value > card2.value:
  #incorrectly indented method, everything starting from the line above to the bottom should be pushed two spaces right
    return card
  #card variable hasn't been defined in this function, should be: return card1
  else:
    return card2
  #what if these two cards are equal? missing statement to cover this possibility
  


def cards_total(self, cards):
#incorrectly indented method, should be withing the Class, so pushed two spaces right
  total
#the total variable has not been declared correctly, it should equal something, as 0, so: total = 0
  for card in cards:
    total += card.value
    return "You have a total of" + total
#incorrectly indented return, it should be outside of the loop, so pushed two spaces left
#also, the returned string is not formatted correctly, it should be for example: return f"You have a total of {total}"
  
```

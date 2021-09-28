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

# missing  : after else and add extra = after card.value
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# dif should be def
# missing coma between card1 and card2
# missing indentation on the if statement
# returning card will give error. (Card1 and Card2 only)
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# fuction needs to be indented as the function is not inside the CardGame
# total not defined
# return is not outside. Needs to be outside the loop.
# missing string interpolation
# The last return won't work if total is not a string.
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```

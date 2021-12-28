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
# in line below: = should be '=='
    if card.value = 1:
      return True
# in line below: add a ':' after else, ie: 'else:'
    else
      return False
   

# in line below: dif should be 'def' and there should be a comma between card1 and card2). 
  dif highest_card(self, card1 card2):
# in line below: add indent for all subsequent lines.
  if card1.value > card2.value:
# in line below: card should be 'card1'
    return card
  else:
    return card2
  

# in function below: indentation is incorrect. All should be indented once, and the final line should be in-line with 'for card in cards'.
def cards_total(self, cards):
# in line below: total should be 'total = 0'
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```

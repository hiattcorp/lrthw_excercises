>Rubicop Output- This is the same as ex 9. I could fix the errors and make it output the right thing but I would lose the code it is trying to teach in this exercise.

```
Offenses:

ex10.rb:5:11: W: Combine "" and "\nI'll do a list:\n\t* Cat food\n\t* Fishies\n\t* Catnip\n\t* Grass\n" into a single string literal, rather than using implicit string concatenation.
fat_cat = """
          ^^^
ex10.rb:5:11: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
fat_cat = """
          ^^
ex10.rb:5:13: W: Combine "\nI'll do a list:\n\t* Cat food\n\t* Fishies\n\t* Catnip\n\t* Grass\n" and "" into a single string literal, rather than using implicit string concatenation.
fat_cat = """
            ^
ex10.rb:10:2: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
"""
 ^^

1 file inspected, 4 offenses detected

18:42:02 - INFO - Guard is now watching at '/Users/jerinhiatt/workspace/davinci_coders_t1_2016/homework/lrthw_excercises/chapter_10'
[1] guard(main)>
```

>Study Question-Use ''' (triple-single-quote) instead. Can you see why you might use that instead of """?

###No, I cannot see why. Everytime I tried it to code did not work.

> Rubocop Output

>It does not appear as though these errors can be fixed based on RuboCop and still have the code work the way it is written

```
Offenses:

ex9.rb:7:6: W: Combine "" and "\nThere's something going on here.\nWith the three double-quotes.\nWe'll be able to type as much as we like.\nEven 4 lines if we want, or 5, or 6.\n" into a single string literal, rather than using implicit string concatenation. Or, if they were intended to be separate method arguments, separate them with a comma.
puts """
     ^^^
ex9.rb:7:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts """
     ^^
ex9.rb:7:8: W: Combine "\nThere's something going on here.\nWith the three double-quotes.\nWe'll be able to type as much as we like.\nEven 4 lines if we want, or 5, or 6.\n" and "" into a single string literal, rather than using implicit string concatenation. Or, if they were intended to be separate method arguments, separate them with a comma.
puts """
       ^
ex9.rb:12:2: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
"""
 ^^

1 file inspected, 4 offenses detected

[1] guard(main)>
```


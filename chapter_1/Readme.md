>Here is an example of the offenses I recieved with Guard:
ex1.rb:1:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "Hello World!"

>I decided to go ahead and fix the errors at first changing the double quotes to single quotes. I did this because I think the single quotes are more simple and simple is better when it comes to coding. However, I found that even more errors were created by doing this becasue there were other words with double quotes inside the output. I ultimately changed it back to the double quotes and ignored the error.



###Rubocop Output

```
09:20:10 - INFO - Inspecting Ruby code style: chapter_1/ex1.rb
Inspecting 1 file
.

1 file inspected, no offenses detected
[1] guard(main)>
```

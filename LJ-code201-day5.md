# Day 5

> var x = (prompt('enter some text')).toLowerCase();

When one cancels this prompt, instead of providing a value, the .toLowerCase() function produces a null value exception  error because the return value of the prompt is null (the prompt was canceled) and the .toLowerCase() doesn't have anything to work on.

Of course I could do the .toLowerCase() after the prompt is complete and check for null values then, but there has to be a more elegant way to do it in one line...

Or not: https://www.codecademy.com/en/forum_questions/55f497a151b887a5370000fc
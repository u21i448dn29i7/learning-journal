# Day 4

The island appears deserted save for a few random crustaceans. But there is plenty of rum.

Oh. No, no, no. That was just Fantasy Island after the hurricane.

Related to JavaScript, I learned scripts can be placed in the head or body of an html document.(<https://www.w3schools.com/js/js_whereto.asp>)

I've always placed them in the head, for the dinky little things I've done, under the assumption that if you wanted to them to act on HTML they must be loaded and compiled before the HTML renders.

"Placing scripts at the bottom of the \<body\> element improves the display speed, because script compilation slows down the display." -<https://www.w3schools.com/js/js_whereto.asp>

That's rational. Ok, so load the HTML first, then the scripts can be downloaded and compiled. Got it.

Except....
Those stupid pages I see all the time that hide elements with JavaScript but don't load fast enough for you not see the unadorned page before the JavaScript has a chance to do it's thing. The next time I see one of these, I'll bet the JS is at the bottom of the \<body\> and isn't loaded/compiled before the HTML starts to render. It usually looks like a screen flicker or late styling.
# Trivia Game
Homewook involves a trivia game with content limited to Roc Nation trivai. The structure of the game is more like the advanced option in that items are presented individually.

There is still work to do on this one, but the general structure is here.

Unfortunately, after the start of the game, we get stuck in a while loop... infinte loop. Ran out of time in trying to fix this.

Another assignment in which I am having difficulty in managing events. This seems to be my nemesis. 


## Overview
This assignment involves building a trivia game, which is essentially a multiple-choice quiz. There are right and wrong answers, and we keep score. It provides an opportunity to develop JavaScript, jQuery, and event-handling tools.  

We make use of sets once again. I just love this data structure. I define a set objects following documentation from Mozilla at

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/

and at

http://www.collectionsjs.com/set 

Set utilities will be my toolbox of sorts going forward. These are under the javascript directory. 

I continue to work with Bootstrap 4, which is currently in alpha release. Bootstrap itself requires jQuery.


## Viewing the Websites... not yet

Would have deployed to gh-pages if it had run. But see no sense deploying an application that goes into an infinite loop. That would not be nice to users.


## Technologies Used

- HTML
- CSS (style.css after Bootstrap 4 css and Yeti Bootswatch)
- JavaScript (via Bootstrap 4) 
- Set data structures implemented via JavaScript objects
- Git/GitHub
- Bootstrap and Bootstrap components for responsive design
- jQuery for event handling


## Code Explanation

- We start with GitHub, setting up the TriviaGame repostory. We set up directories and subdirectories according to the assignment definitions. And we added bootstap as a directory, using much the same structure as in previous assignments. The javascript directory includes my JavaScript code. The images directory can contain images, but these are not essential for the game logic itself. A separate js directory was set up for the jQuery code. A separate bootstrap directory accommodates the bootstrap css and js files, as well as the Yeti css theme. (Because I like to be able to continue working when I have no connection to the Internet, I include copies of files in the repositories. Both human-readable and minified versions of JQuery were included because I am learning jQuery, and would like to inspect code for functions/methods on occasion.) 
- Set up the structure a la bootstrap.
- Set up method for choosing multiple-choice alternatives.
- Did a bit of JavaScrip coding for the game itself. There are still rough edges that need work but the general structure is in place.


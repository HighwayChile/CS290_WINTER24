# assignment04
cs290_winter2024

# REQUIREMENTS
Create a webpage with enough elements and styles that allow you to show off some JavaScript capabilities  
and include at least the following JavaScript features:  
  
input (perhaps using an input element),  - DONE
output (maybe inside a <p> or in a fancier element),  - DONE
variables of a few datatypes (at least number, string, boolean, and a couple objects),  - NEED Num
show off some common errors and how you might avoid them,  
conditionals,  - DONE
repetition,  - DONE
arrays,  - DONE
functions,  - DONE
demonstrate scope,  - DONE
objects and events  - DONE, BUT COULD USE MORE


Go find a JavaScript library that has some features that you think might be useful and be ready to discuss  
some of this with the class  

    Attempt to use that library to create another page that demonstrates some key features of the library  
    (perhaps by going through a tutorial for that library?)  
  
# DESIGN  

This week, I want to tear down, and rebuild my site in a more intuitive way for the user  
<br>  

# PLANS  
1. create search function  - need more javascript - cancelled for this week  
2. add rating system - two buttons: rough and diamond - cancelled for now  
3. finish movie page design - must make user-submitted review here. - Almost working
4. provide text field for user-provided reviews - input text, submit and write to page?  
    - (method="post" or "get") these are two main methods to send info  
5. add nav menus instead of current tables(also remove side menus from main and styles)  
    get ready for pop-out side-menu. should collapse into side (use collapsable?) - PRIORITIZE
6. perhaps move the movielist/loulist to the browse page - DONE
7. must change the "loulsit" id for the loulist cells. Those should be a class, if anything.  - DONE
8. make pages, scripts, and the rest in their own folders  - DONE
9. For library portion: use: ReactJS(react.js), Angular.js, Node.js, Socket.io



# REFLECTION NOTES

So tired... wish I had got more done. I am considering moving on to a different site next week, but I  
kinda like louvie.com 

Please discount my "Test page," it is mostly copy/pasted code from random places. (some is my code :)

My best use of input is in the "pages" section, because each individual movie page has a movie review  
input field! My plan is to write this info to a json file in the future so it can be recalled.  
The output is also on those same pages, although it disappears on refresh
I have variables all over the place, and I had to technically get a boolean operation in my if/else statement.  
I never found a good place to use numbers.
One common error that I displayed throughout my code is the snake_case vs camelCase. I am a little confused  
after so much C and Python and I know I mixed it on some pages. I think I did a good job of keeping my functions
camelCase.
Conditionals, repetition, arrays and functions are all taken care of in: ./pages/review_script.js
objects and events are also in review_script.js
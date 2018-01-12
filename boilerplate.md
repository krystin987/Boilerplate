### This is a basic guide to setting up a basic webapp. 
###### Anyone is free to clone this repo and submit pull requests for edits (in fact, it's encouraged), but please don't provide codeblock solutions. This guide is meant to be followed using the internet to search for any concepts or terms you may not understand.

## step 1: Directory
  Make a folder, name it something like 'myapp'
  I strongly suggest never using spaces to name folders. You can use any of the following:

  ```camelCase```

  ```kebab-case```

  ```under_case```

## step 2: Files
  Make 3 files:

    index.html

    styles.css

    scripts.js

  The names should always be lower case, but that's a personal style preference, not an actual rule. Whether the ```'styles.css``` filename is plural or singular, and anything else, is purely choosing your own adventure.

## step 3: HTML Boilerplate
  Put any old html boilerplate into the index.html file. In the atom text editor, if you type 'ht' followed by tab, it'll give you some boilerplate. Otherwise, search for it on the internet. MDN and W3C Schools will typically have solid information. I never sit there and type out the first 10 lines of html, but it is helpful to type it out when you first start coding.

  It'll look something like:

    <!DOCTYPE html>

    <html>

  And, it'll end with ```</html>``` and in between there's a head, a meta tag, and a body. Stuff like that. If there's any need for disambiguation, go for HTML5 syntax.

## Step 4: CSS linking and testing

  Link the css file. You'll use a link tag in the html file, right under the meta tag. It'll have details such as a path to the file in your directory. When it's in the same directory as index.html, it'll be something like ```"styles.css"``` without any folder pathing. If it were in a separate directory, it would have a path, such as: ```"css/styles.css"``` where css is the sub-directory name.

  After that, you'll want to test if this thing is even working before doing too much more work. In the css file, add any kind of styling on the body. Usually, I select for the body and give it a ```background-color: magenta;``` or something like that. *NOTE: The text appears as a codeblock because I used 3 tickmarks - a somewhat universal syntax to designate a code block where markup is permitted. It can be used in email and other places (slack, even facebook messenger) to share code snippets. You can view the raw version of this file here on github (top righthand side) to see how the markdown syntax is affecting editing.*

  Open the index.html file. It should automatically render in your default browser. If the background is the color you picked, it proves the HTML and CSS are working. If not, debug and figure out why, then fix it. Start with the link tags. Where are they? Do I need a closing tag? Why? Why not?

## Step 5: JavaScript linking and testing

  In the html file, before the closing ```</body>``` tag, add the link to the javascript file. It will be a ```<script>``` tag with a closing ```</script>``` tag with some ```src=""``` linking in between. You can always search for it on the internet. This goes at the bottom of the body for document loading reasons and many others that can also be found on the internet. 

  Once the script tag exists above the closing body tag, open the ```scripts.js``` file and add an alert event to assure the javascript file is hooked up. There's no need for a parent function or any complicated coding. A simple ```alert("message");``` is all you need to create the desire feedback. It can be the only line on othe whole page because JavaScript works directly on the document (the document is the webpage itself). You can test for the desired behavior by opening or refreshing the index.html page. 


## Conclusion

This is the basic framework for creating an end user facing webapp. These files linked together with a layout, style, and user interaction behaviors **are** a webapp, even if the only behavior is a box that pops up with a link to a Rick Astley video. From here, building out a page can begin. Getting used to this basic setup will help a ton moving forward.

Once you have the basic boilerplate, you can copy it every time you make a webapp. You may want to come up with a more robust version of your own 'basic' layout that you reuse. The main goal here is linking the files together using proper script and link tags. That's how files can see one another and have access to their instructions.

HTML is the **layout** of a website or app. Think: newspapers, top to bottom in general, sometimes with side widgets, such as ads.

CSS is how a webpage is **styled** ([CSS Zen Garden](http://www.csszengarden.com/) is a great reference for proving styling is completely handled in css).

JavaScript is the **behavior** created for (or by) user interaction. (buttons, input boxes, animated paper clips of the future).

If you're feeling bold, or you want me to look at a bug (in this, or anything else) make a repository on github and send me a link. 

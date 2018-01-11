#### This is a basic guide to setting up a basic webapp. Anyone is free to clone this repo and submit pull requests for edits (in fact, it's encouraged), but please don't provide codeblock solutions. This guide is meant to be followed using google for any facets or terms you may not understand.

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

  The names should always be lower case, but that's a personal style preference. Whether styles is plural is singular, and anything else, is purely choosing your own adventure.

## step 3: HTML Boilerplate
  Put any old html boilerplate into the index.html file. In the atom text editor, if you type 'ht' followed by tab, it'll give you some boilerplate. Otherwise, google it. I never sit there and type out the first 10 lines of html, but it is helpful to type it out when you first start coding.

  It'll look something like:

    ```<!DOCTYPE html>

       <html>.... ```

  And, it'll end with ```</html>``` and in between there's like a head, a meta tag, and a body. Stuff like that. If there's any need for disambiguation, go for HTML5.

## Step 4: CSS linking and testing

  Connect the css file. You'll use a link tag in the html file, right under the meta tag. It'll have details such as a pointer to the file in your tree. When it's in the same place as index.html, it'll be something like ```"styles.css"``` without any folder syntax. If it were in a css file by itself (or with a mess of css files) it would be more like ```"./css/styles.css"``` where css is the folder name, etc.

  After that, you'll want to make sure this thing is even working. In the css file, add any kind of styling on the body. Usually, I select for the body and give it a ```background-color: magenta;``` or something like that. *NOTE: The text appears as a codeblock because I used 3 tickmarks - a somewhat universal syntax to designate a code block where markup is permitted. It can be used in email and other places (slack, even facebook messenger) to share code snippets.*

  Open the index.html file, it'll render in a browser, and if the background is the color you picked, it should prove the files are working. If not, debug and figure out why, then fix it.

## Step 5: JavaScript linking and testing

  In the html file, before the closing </body> tag, is where you add the link to the javascript file. It will be a <script> tag with a closing </script> tag with some src="" linking in between. Google, as always.

  Once the script tag exists above the closing body tag, open the scripts.js file and add an alert event to assure the javascript file is hooked up. There's no need for a parent function or any super hardcore syntax. A simple ```alert("message");``` is all you need to create the desire feedback. Because JavaScript works directly on the 'document' which is just fancy talk for the webpage itself. You test it by opening or refreshing the index.html page.


## Conclusion

This is the basic framework for doing anything you want with a webapp. These files working together **are** a webapp. Just that little alert showing up is a webapp. From here, you can fiddle around however you want. Getting used to this basic setup will help a ton moving forward, because it's never going away.

Once you have the basic boilerplate, you can copy it every time you go to make a website (or app, depending on the architecture). You may even come up with a more robust version of your own 'basic' layout that you reuse. The key factors are making the pages 'talk' via those script and link tags. That's how files can see one another and have access to their tools.

HTML is always layout (think newspapers, top to bottom in general, sometimes some annoying widgets, such as ads, on the sides)
CSS is always styling (http://www.csszengarden.com/ is a great reference for proving styling is completely handled in css)
JavaScript is the behavior (buttons, input boxes, literally anything user interaction)

If you're feeling really froggy, or you want me to look at a bug (in this, or anything else) make a repository on github and put it there. Same with the boilerplates you decide on. Once there's a remote repository they'll always be there, ready to use.

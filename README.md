## EduBlocks Class Project

# Introduction
Hi! If you're reading this, you probally are doing EduBlocks for Coach Austin's to make a web app.
You also probally don't know what the hell html even is or css, but that's okay. That's why I am is here to
briefly explain what each block does and how to use it. 👍

I'll also add links to tools you might need at the very bottom.

# Blocks
 This is split into sections by the catogories of the blocks with each catogory having a small description. If there isn't a explanation for a certain
 block or piece, it is probally just irrelavent.
 
## Page
The base of your website/app

<html>
Your HTML (Hyper Text Markup Language) block is the base of your website and most of your elements (text, media, ect) go into here.
### <head>
The head block is where you put your title block which is used to name your website/app. (Not completely a necessity, but helps with tidiness)
### <title>
The Title block names your website/app at the top, either in your tab or window name.
### <body>
The Body block goes is what holds all of the elements (text, media, etc) inside the HTML block.

## Structure
The structure of your text elements (Primarily used to organize your website/app without being to messy)
### <div>
The Div (Division) block allows for organizing of your text by grouping other organizing blocks together (Header, Footer, Section, Article, etc)
### <header>
The Header block pushes your element to the top of the page and is like a title at the top of your website/app
### <footer>
The Footer block is the oppisite of the Header block and pushes the elements inside to the bottom of the page, this can be used for 
stuff like credits
### <section>
The Section block is basically the same as the last two but it doesn't push the elements to a certain area and is mostly just used to 
section off parts like an About Us or a FAQ
### <article>
The Article block is like the section block but since it is self-contained which means it can just be used by itself and/or be distributed to elsewhere, 
an example of this is a social media post, blog post, etc. (This is really useless for what we are doing)
### <br>
The BR block breaks the line of text in the case that you don't want to start a new line of text, an example is if you are writing in a <p> and don't want to make a new one
(You can ignore this one mostly, it's mostly for optimization)
### <hr>
The HR block creates a horizontal rule, which just means it makes a split in the website/app. (This just makes a visual divide in content. You can ignore this to depending
on what you are making)

## Text
Just text elements
### <h 1 ___ > Heading </h>
The H block is a little confusing so I'll split this up a little.
The H block usually goes into a structure block and is used as the header for that structure block.
The 1 element inside of the H block is used for text size.
The blank part inside of the H block is used for elementid or classname. (Skip to Attributes for explaination)
The text box saying Heading is where you type your text.
### <p ___> Paragraph </p>
The P block is pretty self explainatory with the same rules from the H block applying to this block also. (This element using Styling for text size, don't ask why, I don't know why,
I just document, and I know it's dumb 😭)
### <span ___> Span </span>
Same rules apply to the Span block, the Span block is useless, don't ask why, it just is.
### Text Bubble / Quotation Text Bubble
Just a text bubble you can use to add functions to blocks (You don't really need this as blocks already come with them)

## Attributes
An id added to a block so it can be called upon in something like Styling (There's only 2 you need to know)
### id=
The Element ID attribute lets a block be called upon to be changed by a function (Usually Styling)
### class=
The Class element is just an alternative to Element ID and I actually recommend you use this over Element IDs

##S tyling
Allows for elements to be styled like changing text color, changing background of website/app, etc.
### <style>
The Style block is the base of your styling blocks. This block should never go into the HTML block. All Styling blocks should go into this block (text-color, text-allign, background-color, etc)
### .classname
The .classname block allows for styling blocks only apply to other elements with the same classname. (Highly Recommended to Use)
### :before/:after/:focus/:hover
These blocks allow for effects to happen on buttons when an action is done. For example when I hover my mouse over an element, it enlarges slightly to add depth.
### Color Block
The color block can be used to color things, one issue is doesn't have as much color customization as RGBA or Hex Code. (I don't know how else to explain and it is insanely easy to understand)
### rgba
The RGBA block is quite hard to explain but it uses numbers to color instead of a UI or Hex Code. (Link for RGBA Color Picker at the bottom)
### Text Styling
Theres not much to explain here and all the blocks are pretty self explainatory
Also in the text-color you can drag a RGBA, Hex Code, or a Color Block into the little area that says some gibberish to pick the color.
### Display Styling
Theres only one Thing you need to know for this one and it is the Display block which is the first one you will see.
The display block can make you element act like a box or make it flex, you won't really need this but I only told you because it can help with some issues.
### Spacing
I won't explain each block but this is one of the most important Styling catogories so I'll give you the defintion for margin and padding.
In CSS, padding refers to the space between the content of an element and its border. It is used to create space inside an element, pushing the content away from the edges of the element's border.
In CSS, margin is the space outside an element's border. It creates distance between the element and surrounding elements. Essentially, the margin pushes the element away from its neighbors, allowing for spacing between them.
### Background
Pretty self explainatory and the features should be pretty simple if you been following along 🙄
### Border
These blocks add a border to your elements
### Other (Cursor)
The Cursor block lets you change the cursor that shows on your website/app

## Media
Media is pretty self explainatory and all the blocks have mostly the same rules just a different type of media.
The only thing you need to know is how to get iage urls, which there should be a youtube video showing you how. I'm sorry if you can get it on mobile

## Forms
These blocks allow the user to summit data to the website/app

## Tables
These blocks allow for creating tables which can be used to organize or display data.

## Lists
I don't know, make lists?

## Script
I don't recommend this, but if you really want to flex, I guess you can? I don't want compition, so I ain't explaining this. Go find an HTML tutorial on how to use emmbedded JS or something.

# Links
### EduBlocks
https://edublocks.org/
### Color Picker / Hex Picker
https://www.google.com/search?client=firefox-b-e&q=google+color+picker
### RGBA Color Picker
https://rgbacolorpicker.com/
### How To Get Image URL For Media Blocks
https://youtu.be/AjG9Kwhmwok?si=ZrSRddU73SyTD7WU

And that's all. If you still don't understand, come talk to me or Coach Austin and we can help, but I don't know aobut Coach Austin, he might just send you to me.
Also this is bugged for some reason so some headers might now show up :(

# Credits?
Made by your's truly, Everett :)

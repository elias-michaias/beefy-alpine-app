# alpine-template

A template for the web using Alpine.js.
Based off of `create-alpine-app`, it includes conveniences like Tailwind and PostCSS.

Beyond those, I've also included several libraries and plugins with the purpose of 
completing Alpine and building it into a more monolithic framework.

The goal of this template is to fully actualize HTML as a cohesive language on its own,
and optimize productivity. Alpine's native features make front-end seamless, Tailwind
removes the need for fiddling with CSS, Alpine AJAX makes server requests
a breeze from any element, and the other libraries included like VimeshUI and Pinecone Router bring in 
conveniences like component abstraction and routing that Alpine would normally expect
a back-end templating solution for. This is my personal setup for doing as much development
as possible without leaving my markup. 

## "Why not HTMX?"
While HTMX is a fine solution, I personally prefer doing things the Alpine way, and Alpine AJAX
completes Alpine in the realm of client-server communication, making HTMX unnecessary for me.
While Alpine and HTMX are certainly used together fairly often, I find that I don't need to use HTMX
to meet my needs.

## "Why not React/Vue/Svelte?"
Doing as much inside of my markup as possible is a very appealing idea for me. If it is for you,
then this template may also be for you. If not, that's perfectly fine! 

## "This template isn't viable for enterprise."
Correct.

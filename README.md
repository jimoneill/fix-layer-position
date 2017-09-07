# Fix Layer Position

A Sketch plugin that lets you quickly move a layer to a predetermined (X,Y) position.

## Why?

This plugin is designed to speed up the following repetitive task that I do every day (and I assume I'm not alone):

1. View some page in my web application, in a browser.
2. Take a screenshot of the browser window, at the same viewport size every time.
3. Paste the screenshot into Sketch, using the same artboard size every time, so that I can start designing & editing on top of the screenshot.

When I quickly snap a screenshot of my browser window, I get the viewport – which I want – but I also get the browser bar, outer chrome, and Apple's big ol' window drop shadow. I don't need any of that! I could crop each screenshot after I take it, but that sounds like work, which sucks. Instead I really just want to move the screenshot on my artboard so that the viewport lines up with the artboard dimensions – in other words, so that the top left corner of the viewport (in the screenshot) is at position (0,0) on my artboard.

This is precisely the task for which Fix Layer Position was built.

## What it does

1. Lets you configure the (X,Y) position you want to use as a target.
2. Moves a selected layer instantly to that position.

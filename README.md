# Fix Layer Position

A Sketch plugin that lets you quickly move a layer to a predetermined (X,Y) position.

## Why?

This plugin is designed to speed up the following repetitive task that I do every day (and I assume I'm not alone):

1. View some page in my web application, in a browser.
2. Take a screenshot of the browser window, at the same viewport size every time.
3. Paste the screenshot into Sketch, using the same artboard size every time, so that I can start designing & editing on top of the screenshot.

When I quickly snap a screenshot of my browser window, I get the viewport – which I want – but I also get the browser bar, outer chrome, and Apple's big ol' window drop shadow. I don't need any of that! I could crop each screenshot after I take it, but that sounds like work, which sucks. Instead I really just want to move the screenshot on my artboard so that the viewport lines up with the artboard dimensions – in other words, so that the top left corner of the viewport (in the screenshot) is at position (0,0) on my artboard.

This is precisely the task for which Fix Layer Position was built.

## Usage

The plugin has two actions available:

**Configure Target Position:** Set this up once, the way you want it, and Sketch will store & remember your target position. The default is 0,0 but you can pick any X,Y coordinate position.

_Example:_ I work on a web application that's desktop-only. The minimum window size we design for is 1400x720, so that's the size I make all my screens as I design them, and that's the size at which I snap screenshots of the current app, to bring them into Sketch and play around with them. Through manual repositioning, I discovered that when I snap a screenshot of my app in Chrome, and bring it into Sketch, I need to place it at (-56,-106) relative to my 1400x720 artboard, so that the browser bar and drop shadow are hidden beyond the artboard edges. Therefore, I configure my target position to be -56,-106.

**Fix Layer Position** _(ctrl+shift+9)_: If a layer is selected, instantly move that layer to your target position.

## Installation

You can download and install manually, but that also sounds like work. Why not...

### Install with Sketch Runner

With Sketch Runner, just go to the `install` command and search for `Fix Layer Position`. Runner allows you to manage plugins and do much more to speed up your workflow in Sketch. [Download Runner here](http://www.sketchrunner.com).

<a href="http://bit.ly/SketchRunnerWebsite">
  <img src="http://bit.ly/RunnerBadgeBlue">
</a>

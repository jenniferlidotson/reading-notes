# Class 10 Reading Notes

## Debugging - Troubleshooting JavaScript.

- Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!

- Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

## The JavaScript Debugger

- The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

- Source code:Set breakpoints where you want to pause execution. 

 ## Debugging HTML
 
- "End tag li implied, but there were open elements" (2 instances): These messages indicate that an element is open that should be closed. The ending tag is implied, but not actually there. The line/column information points to the first line after the line where the closing tag should really be, but this is a good enough clue to see what is wrong.

- "Unclosed element strong": This is really easy to understand — a <strong> element is unclosed, and the line/column information points right to where it is.

- "End tag strong violates nesting rules": This points out the incorrectly nested elements, and the line/column information points out where they are.

- "End of file reached when inside an attribute value. Ignoring tag": This one is rather cryptic; it refers to the fact that there is an attribute value not properly formed somewhere, possibly near the end of the file because the end of the file appears inside the attribute value. The fact that the browser doesn't render the link should give us a good clue as to what element is at fault.

- "End of file seen and there were open elements": This is a bit ambiguous, but basically refers to the fact there are open elements that need to be properly closed. The line numbers point to the last few lines of the file, and this error message comes with a line of code that points out an example of an open element
 
## Debugging CSS

- Inspecting the applied CSS: Select an element on your page, either by right/ctrl-clicking on it and selecting Inspect, or selecting it from the HTML tree on the left of the DevTools display. Try selecting the element with the class of box1; this is the first element on the page with a bordered box drawn around it.
 
- Click on the little arrow to expand the view, showing the different longhand properties and their values.

- You can toggle values in the Rules view on and off when that panel is active — if you hold your mouse over it, checkboxes will appear. Uncheck a rule's checkbox, for example border-radius, and the CSS will stop applying.

- You can use this to do an A/B comparison, deciding if something looks better with a rule applied or not, and also to help debug it — for example, if a layout is going wrong and you are trying to work out which property is causing the problem.
 
### Things I want to know more about

- Is something else overriding my CSS?

- Find out more about the DevTools

- Solving specificity issues

- Understanding the box model

#### Link to my github portfolio [https://github.com/jenniferlidotson](https://github.com/jenniferlidotson)

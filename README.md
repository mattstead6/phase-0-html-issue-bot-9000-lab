# HTML Issue Bot 9000

## Learning Goals

1. Demonstrate writing valid HTML

## Introduction

Let's practice using the W3C's HTML Validator!

## Demonstrate Writing Valid HTML

In this lab we'll use the W3C Validator to make our invalid HTML happy!
You might need to change how you work this problem depending on your 
work environment. Either way you'll learn to fix invalid HTML.

## Getting Started

Fork and clone this lesson into your local environment. Navigate into its directory
in the terminal, then run `code .` to open the files in Visual Studio Code. Finally,
run `bundle` to install the lab's dependencies.

### Steps

1. Open index.html in a browser. See how it, well, doesn't look _quite_ right?
2. Open index.html in your text editor
3. Visit the W3C validator at: [http://validator.w3.org/#validate_by_input][VBI]
4. Copy the code from index.html and paste it into the text area
5. Click the large "Check" button
6. Use the error messages to correct the code your copy of `index.html`
7. Repeat steps 3-6 until the Html Validator reports: "Document checking
   completed. No errors or warnings to show."
8. Not only is the document now W3C-valid, it no longer looks weird

### Submitting the Lab

When your document is valid, go to the terminal and type:

`rspec`

Since you're verifying the HTML structure via W3C, the test here is not
robust at all.

## Resources

* [W3C HTML Validator - Validate Direct Input][VBI]

[VBI]: http://validator.w3.org/#validate_by_input

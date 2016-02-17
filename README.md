### How to use handlebars

An easy way to play around with a handlebars template and make sure it is working properly is with the render-cli tool

    npm install -g render-cli

To use this tool, simply input the template, specify the template engine (handlebars), the template data, and the output location.

To use the data in this repo try:

    render test.tpl.html --engine handlebars --context test.json --output test.html

Looking through the files should give you a good idea of how to do the basics with handlebars.
# Tranzt Emails

Emails are written with [MJML](https://documentation.mjml.io/) template syntax.

## Generate email

1. Run `npx mjml [path to input] -o [path to output]` to generate the html. Output folder is `dist`
2. Copy the html. Go to https://putsmail.com/inliner and paste the html to inline the css.
3. Copy the output. That's all.

## VSCode extension

Install this extension for live previews as your build the templates.
[Link](https://marketplace.visualstudio.com/items?itemName=mjmlio.vscode-mjml)

# Central Advancement Design Tokens

It is now a best practice to invest in a design system for teams building and maintaining several web 
properties. Beyond the web, design teams have even extrapolated...

## More Setup

The guide at https://support.invisionappcom/hc/en-us/articles/360049950151-The-Design-Tokens-Practice 
is being followed. 

The Style Dictionary project was chosen to be the build tool:
https://amzn.github.io/style-dictionary/#/README

## History

...something with Salesforce and their Lightning Design System.

## Main components

- Typography - The font style, font weights, line height, and other typographic properties.
- Colors - The color palette representing the brand of Central Advancement.
- Spacing - The spacing between elements used in padding, margins, breakpoints, and other layout 
  properties.
- Borders - The border properties for elements.
- Shadows - The shadow properties for elements.
- Animations - The animation properties for elements.s
- Variants - The variant properties for design components. These are used to change the appearance of 
  components based on the context of the page and user interaction.

## Actual Design Tokens

Design tokens are commonly exported in either YAML or JSON formats. We will provide both.

- YAML - ...
- JSON - ...

## Applying Design Tokens

- [Using the JSON format](#using-the-json-format) - this example shows how to use the JSON format on 
  a simple website.

### Using the JSON format

We will take the JSON design token file and generate a CSS file that can be used on a website.

```bash
yarn gen:css
```


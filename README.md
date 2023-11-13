# HubSpot-Standalone-Theme
## This is a HubSpot Theme customised for easy module development with less restrictions.

The Highlight of this theme is the nonDND.module, it's a powerful module that gives flexibility to almost everything you need. Is a repeater for sections with settings that range from background types to column withs.

The overwrite section is used to add extra modules/css/js that will overwrite the original one without the change effecting the integral part of the theme.

CSS: I am using a custom grid system build by me based on the bootstrap idea. stripped down to only the neccecery code.

## DND.module
This is a plain theme with minimal settings to support easy future development. Is functionality heavy due to DND.module which takes the functionality from all the available fields that HubSpot supports and adds them to one big module. 
The module supports the following features:
- changing Background(image, gradient, color)
- Is a repeater
  - supports multi-column, has a setting to choose the width of the column from1 - 12 column width.(Bootstrap concept but Grid system, not flexbox)
  - individual background change
  - spacing
  - alignment
  - border(including: width, color, radius)
- for specific fields like image, I have an optional setting to fit-to-container
- and many more...

## The ideal scenario
Hoping making the development envirnment a bit easier and the idea would be to clone this theme to a portal, do the neccesery theme settings, font-family, font-sizes, etc. Set up navigation and footer and start building your pages, start with the DND module,  see what it can be built with that and all the settings and then start building your own modules to fit your requirements.

# How to Use:

1. Upload it to your portal [HubSpot CLI](https://developers.hubspot.com/docs/cms/developer-reference/local-development-cli).
2. Set up the Theme settings.
3. Build your pages using only one module (nonDND).

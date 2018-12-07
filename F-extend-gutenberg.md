# How we extended Gutenberg core blocks to build in AMP support - Miina Sikk

## Gutenberg Blocks + AMP

https://www.ampproject.org/learn/overview/

Github.com/miina/wcus18
Wordpress.org/plugins/amp/
xwp.com

<img> -> <amp-img>
<video> -> <amp-video>
<amp-fit-text>
<amp-facebook>

1. Handle disallowed elements
2. Use AMP components

## Why extend core blocks?

Hooks for extending
1. Blocks.registerBlockType
2. Blocks.getSaveElement
3. Editor.BlockEdit
4. Blocks.getSaveContent.extraProps

_Amp-fit-text_
1. Register settings
2. Add visible controls
3. Modify what gets saved

## Gallery shortcodes
Optional _amp-carousel_ usage
1. Register the settings
2. Add visible controls
3. Modify what gets saved
4. PHP: Process output

## AMP lightbox
Optional _amp-lightbox_
1. Register the settings
2. Add visible controls
3. Modify what gets saved
4. PHP: Process output

## Challenges


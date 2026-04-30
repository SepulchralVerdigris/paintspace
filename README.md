# PaintSpace
A 3D visualisation of the properties of miniatures paints.

[Try it online.](https://sepulchralverdigris.github.io/paintspace/)

Notice: PaintSpace was created with generative AI. 

## To add your paints
Create a CSV file in this format: 

| Paint Name | Brand | Hex Code | Owned | Type |
| -- | -- | -- | -- | -- |
| Pink | Company | #d47a83 | 1 | Normal |

### Owned

"1" means the paint is in your collection. Otherwise, the paint is treated as a "Tester" -- it will be displayed so you can see what its properties are, for example to help you decide whether to purchase it. 

### Type

Normal, Metallic, Air, Wash, Contrast, Technical and Fluo (Fluorescent). You can add other types if you like. Air, Metallic, Wash and Contrast swatches are visually distinct. 

### Hexcode 

The six-character code used for web colours. For example, #000000 is black and #ffffff is white. Citadel paints hexcodes are available [from DakkaDakka](https://www.dakkadakka.com/wiki/en/Paint_Range_Compatibility_Chart). 

You can use the "paint dropper" tool in any image software (Paint, Inkscape, etc) to find the hexcode of a colour. 

If you want "true" colours (as close as computers can get), you could buy Tale of Painters' swatches and then use the paint dropper tool to find hexcodes. 

## Using PaintSpace
Import CSV files to populate your PaintSpace. By default, it has my paint collection installed. You can clear this with the "Clear palette" button. 

### Visualise your paints and paints you are thinking of buying

There are different "views": by Hue x Saturation, Hue x Value and Saturation x Value. This will give you a sense of what properties different paints have. 

### Find colour matches

You can type a hexcode into the "Colour Match" option to find the nearest colours. Toggle "Tester" on or off to only look for matches among paints you own, versus among all paints you have loaded into the program. 

As well as helping with colour matching, this gives you a sense of *how* your current paints differ from the target colour. Are they darker, lighter, duller or too brilliant? Do you have nearby paints that, if mixed, might be closer to the target colour?

### Identify gaps in your collection

Finally, if you have uploaded any "tester" paints, the "Gap Analysis" tool will tell you which tester paints are furthest away from any paint you currently own. This can help you identify gaps. 

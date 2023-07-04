# Colored Markers

on this project I´m create different types of colors

from primary colors
There are three more tertiary colors: chartreuse green (green + yellow), azure (blue + cyan), and rose (red + magenta).

To create chartreuse green, update the rgb function in the .one rule so that red is at 127, and set green to the max value.

For azure, update the rgb function in the .two rule so that green is at 127 and blue is at the max value.

And for rose, which is sometimes called bright pink, update the rgb function in the .three rule so that blue is at 127 and red is at the max value.

## hexagonal color model

Exist 16 diferent values from 0-9 to A-F it`s like rgb model, but on this model, beggins with # character and make in pairs, the first pair is for red, second for green and last one for blue, the intensity is defined by de values 00 = 0% FF = 100% and combination of these can turn the color more light or dark.

in the gradients Even without the color-stops, you might have noticed that the colors for the green marker transition at the same points as the red marker. The first color is at the start (0%), the second is in the middle (50%), and the last is at the end (100%) of the gradient line.

The linear-gradient function automatically calculates these values for you, and places colors evenly along the gradient line by default.

### HSL color model

The HSL color model, or hue, saturation, and lightness, is another way to represent colors.

The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.

If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.

Saturation is the intensity of a color from 0%, or gray, to 100% for pure color.

Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.

#### gradient

A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.

One thing to remember is that the linear-gradient function actually creates an image element, and is usually paired with the background property which can accept an image as a value.

The first color is at the start (0%), the second is in the middle (50%), and the last is at the end (100%) of the gradient line.

The linear-gradient function automatically calculates these values for you, and places colors evenly along the gradient line by default.

If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default.

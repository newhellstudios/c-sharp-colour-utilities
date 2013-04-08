c-sharp-colour-utilities
========================

This is set of classes that help with colour manipulation. 
 - A harmony colour helper for a giving colour
 - Match the closest colour to one contained into a list of colours.

WPF colour utils

Colour class
It provides the ability to convert a colour from RGBto HSL or from HSLto RGBColours can be create from a System.Drawing.Color or RGB values or HSL values.
A Colour can be compared with another colour by using == or != or with the method getIsColourMatch.

ColourHarmoniesHelper class
It provides the ability to get different colour harmonies which are highlighted in this website (http://www.easyrgb.com/index.php?X=WEEL).
Triadic, Split complements, Analogous, Monochromatic, Complement

ColourRange class
It provides the ability to find the closest colour to one specifed in a list of colours.



A test project is included which illustrates how the library works.
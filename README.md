# Python Munsell

Python Munsell provides a MunsellColor object for Python.  The MunsellColor
object can be used to represent munsell colors and convert them to RGB.


## Dictionary Structure ##

The dictionary is keyed by the Munsell specification and returns the CIE xyY value where x and y define the hue in a two-dimensional plane and Y is the luminance. (The xyY variables are derived from CIE XYZ.)

**Dict Object**

Key: H V C

Value: x y Y


| Munsell Spec. | Definition            |
| ------------: |:----------------------|
| **H**         | Hue                   |
| **V**         | Value (lightness)     |
| **C**         | Chroma (color purity) |


| CIE xyY       | Definition            |
| ------------: |:----------------------|
| **x**         | Chrominance           |
| **y**         | Chrominance           |
| **Y**         | Luminance             |

## Munsell Hue Notation ##

### Principal Hues ###

**R** Red

**P** Purple

**B** Blue

**G** Green

**Y** Yellow

### Intermediate Hues ###

Intermediate hues are constructed by combining the principal hues. Example: YR Yellow-Red; GY Green-Yellow.


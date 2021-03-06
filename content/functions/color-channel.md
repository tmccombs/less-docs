<a id="hue"></a>
## hur

> Extracts the hue channel of a color object.

Parameters: `color` - a color object.
Returns: `integer` `0-360`
Example: `hue(hsl(90, 100%, 50%))`
Output: `90`


<a id="saturation"></a>
## saturation

> Extracts the saturation channel of a color object.

Parameters: `color` - a color object.
Returns: `percentage` `0-100`
Example: `saturation(hsl(90, 100%, 50%))`
Output: `100%`


<a id="lightness"></a>
## lightness

> Extracts the lightness channel of a color object.

Parameters: `color` - a color object.
Returns: `percentage` `0-100`
Example: `lightness(hsl(90, 100%, 50%))`
Output: `50%`


<a id="hsvhue"></a>
## hsvhue

> Extracts the hue channel of a color object in the HSV color space.

Parameters: `color` - a color object.
Returns: `integer` `0-360`
Example: `hsvhue(hsv(90, 100%, 50%))`
Output: `90`


<a id="hsvsaturation"></a>
## hsvsaturation

> Extracts the saturation channel of a color object in the HSV color space.

Parameters: `color` - a color object.
Returns: `percentage` 0-100
Example: `hsvsaturation(hsv(90, 100%, 50%))`
Output: `100%`


<a id="hsvvalue"></a>
## hsvvalue

> Extracts the value channel of a color object in the HSV color space.

Parameters: `color` - a color object.
Returns: `percentage` 0-100
Example: `hsvvalue(hsv(90, 100%, 50%))`
Output: `50%`


<a id="red"></a>
## red

> Extracts the red channel of a color object.

Parameters: `color` - a color object.
Returns: `integer` `0-255`
Example: `red(rgb(10, 20, 30))`
Output: `10`


<a id="green"></a>
## green

> Extracts the green channel of a color object.

Parameters: `color` - a color object.
Returns: `integer` 0-255
Example: `green(rgb(10, 20, 30))`
Output: `20`


<a id="blue"></a>
## blue

> Extracts the blue channel of a color object.

Parameters: `color` - a color object.
Returns: `integer` 0-255
Example: `blue(rgb(10, 20, 30))`
Output: `30`


<a id="alpha"></a>
## alpha

> Extracts the alpha channel of a color object.

Parameters: `color` - a color object.
Returns: `float` `0-1`
Example: `alpha(rgba(10, 20, 30, 0.5))`
Output: `0.5`


<a id="luma"></a>
## luma

> Calculates the [luma](http://en.wikipedia.org/wiki/Luma_(video)) (perceptual brightness) of a color object.

Uses **SMPTE C / Rec. 709** coefficients, as recommended in [WCAG 2.0](http://www.w3.org/TR/2008/REC-WCAG20-20081211/#relativeluminancedef). This calculation is also used in the contrast function.

Parameters: `color` - a color object.
Returns: `percentage` 0-100%
Example: `luma(rgb(100, 200, 30))`
Output: `65%`

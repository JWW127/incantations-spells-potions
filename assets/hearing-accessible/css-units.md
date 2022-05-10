# CSS Units Explained

## Absolute Units

px - 1/96 of 1 inch
pt - 1/72 of 1 inch
pc - 12pt = 1pc
cm - centimeter
mm - millimeter
in - inches

### Downside of absolute units?

Absolute units a not responsive, will not scale with change to screen size.

## Relative Units

% - percent - relative to parent element
em - relative to current font size
rem - relative to font of root of the document html
ch - Equal to the width of "0" character
vh - relative to the height of the viewport
vw - relative to the width of the viewport
vmin - relative to viewport's current smallest dimension
vmax - relative to viewport's current largest dimension
ex - relative to lowercase "x" of current font

### Downside of relative units?

Relative units can be hard to predict, especially units dependent on device orientation like vmin/vmax.

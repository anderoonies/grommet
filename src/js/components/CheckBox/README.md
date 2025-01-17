## CheckBox
A checkbox toggle control.

[![](https://cdn-images-1.medium.com/fit/c/120/120/1*TD1P0HtIH9zF0UEH28zYtw.png)](https://storybook.grommet.io/?selectedKind=Input-CheckBox&full=0&stories=1&panelRight=0) [![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/grommet/grommet-sandbox?initialpath=/checkbox&module=%2Fsrc%2FCheckBox.js)
## Usage

```javascript
import { CheckBox } from 'grommet';
<CheckBox />
```

## Properties

**a11yTitle**

Custom label to be used by screen readers.
      When provided, an aria-label will be added to the element.

```
string
```

**checked**

Same as React <input checked={} />

```
boolean
```

**children**

Function that will be called to render the visual representation.
      It will be passed an object indicating whether the button is checked. It
      should return a react element.
      For example:
      `children={({ checked, indeterminate }) => <Box ...>{...}</Box>}`
      

```
function
```

**disabled**

Same as React <input disabled={} />. Also adds a hidden input element
      with the same name so form submissions work.

```
boolean
```

**fill**

Whether the checkbox and label expand to fill all of the available
         width and/or height of their container.

```
boolean
```

**id**

The DOM id attribute value to use for the underlying <input/> element.

```
string
```

**label**

Label text to place next to the control. 
      Can be used instead of a11yTitle to meet accessibility requirements

```
node
```

**name**

The DOM name attribute value to use for the underlying <input/> 
      element.

```
string
```

**onChange**

Function that will be called when the user clicks the check box. It
      will be passed a React event object. The current state can be accessed
      via event.target.checked. Same as React <input onChange={} />.

```
function
```

**pad**

The amount of padding on the container 
    surrounding the checkbox and its label. An object can be specified to 
    distinguish horizontal padding, vertical padding, and padding on a 
    particular side of the container. Defaults to `none`.

```
none
xxsmall
xsmall
small
medium
large
xlarge
{
  bottom: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  end: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  horizontal: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  left: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  right: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  start: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  top: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string,
  vertical: 
    xxsmall
    xsmall
    small
    medium
    large
    xlarge
    string
}
string
```

**reverse**

Whether to show the label in front of the checkbox.

```
boolean
```

**toggle**

Whether to visualize it as a toggle switch.

```
boolean
```

**indeterminate**

Whether state is indeterminate.
NOTE: This can only be used with non-toggle components

```
boolean
```
  
## Intrinsic element

```
input
```
## Theme
  
**checkBox.border.color**

The border color when unchecked. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
{ dark: 'rgba(255, 255, 255, 0.5)', light: 'rgba(0, 0, 0, 0.15)' }
```

**checkBox.border.width**

The border width when unchecked. Expects `string`.

Defaults to

```
2px
```

**checkBox.check.extend**

Any additional style for checked CheckBox. Expects `string | (props) => {}`.

Defaults to

```
undefined
```

**checkBox.check.radius**

The radius of the checked icon. Expects `string`.

Defaults to

```
4px
```

**checkBox.check.thickness**

The stroke width of the checked icon. Expects `string`.

Defaults to

```
4px
```

**checkBox.color**

The stroke color for the CheckBox icon, and the border when checked. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
undefined
```

**checkBox.extend**

Any additional style for CheckBox. Expects `string | (props) => {}`.

Defaults to

```
undefined
```

**checkBox.gap**

The right margin of the CheckBox to its label. Expects `string`.

Defaults to

```
undefined
```

**checkBox.hover.border.color**

The border color on hover. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
{ dark: 'white', light: 'black' }
```

**checkBox.hover.background.color**

The background color of the Box surrounding the RadioButton 
    when hovered over. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
undefined
```

**checkBox.icon.size**

The size of the checked icon. Expects `string`.

Defaults to

```
undefined
```

**checkBox.icon.extend**

Any additional style for CheckBox icon. Expects `string | (props)=>{}`.

Defaults to

```
undefined
```

**checkBox.icons.checked**

The icon to use when checked. Expects `React.Element`.

Defaults to

```
undefined
```

**checkBox.icons.indeterminate**

The icon to use when indeterminate. Expects `React.Element`.

Defaults to

```
undefined
```

**checkBox.label.align**

How to align the checkbox and label. Expects `string`.

Defaults to

```
center
```

**checkBox.pad**

The pad around the CheckBox and its label. Expects `string | object`.

Defaults to

```
undefined
```

**checkBox.size**

The height and width used for the CheckBox icon. Expects `string`.

Defaults to

```
24px
```

**checkBox.toggle.background**

The background color of the toggle. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
undefined
```

**checkBox.toggle.color**

The color of the toggle knob. Expects `string | { 'dark': string, 'light': string }`.

Defaults to

```
{ dark: '#d9d9d9', light: '#d9d9d9' }
```

**checkBox.toggle.extend**

Any additional style for CheckBox toggle. Expects `string | (props) => {}`.

Defaults to

```
undefined
```

**checkBox.toggle.knob.extend**

Any additional style for the CheckBox toggle knob. Expects `string | (props) => {}`.

Defaults to

```
undefined
```

**checkBox.toggle.radius**

The border radius used for the toggle and the knob. Expects `string`.

Defaults to

```
24px
```

**checkBox.toggle.size**

The width size of the toggle. Expects `string`.

Defaults to

```
48px
```

---
name: carbon-component-radio-button-group
description: Carbon RadioButtonGroup component props and usage examples.
---

# RadioButtonGroup

## Import
`import RadioButtonGroup from "carbon-sage/lib/components/radio-button";`

## Source
- Export: `./components/radio-button`
- Props interface: `RadioButtonGroupProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| id | string \| undefined | No |  | Unique identifier for the component. Will use a randomly generated GUID if none is provided. |  |
| adaptiveLegendBreakpoint | number \| undefined | No |  | Breakpoint for adaptive legend (inline labels change to top aligned). Enables the adaptive behaviour when set |  |
| adaptiveSpacingBreakpoint | number \| undefined | No |  | Breakpoint for adaptive spacing (left margin changes to 0). Enables the adaptive behaviour when set |  |
| children | React.ReactNode | Yes |  | The RadioButton objects to be rendered in the group |  |
| inline | boolean \| undefined | No |  | When true, RadioButtons children are in line | false |
| labelSpacing | 1 \| 2 \| undefined | No |  | Spacing between labels and radio buttons, given number will be multiplied by base spacing unit (8) | 1 |
| legend | string \| undefined | No |  | The content for the RadioButtonGroup Legend |  |
| legendHelp | string \| undefined | No |  | The content for the RadioButtonGroup hint text, will only be rendered when `validationRedesignOptIn` is true. |  |
| legendAlign | "left" \| "right" \| undefined | No |  | [Legacy] Text alignment of legend when inline | "left" |
| legendInline | boolean \| undefined | No |  | [Legacy] When true, legend is placed in line with the RadioButtons | false |
| legendSpacing | 1 \| 2 \| undefined | No |  | [Legacy] Spacing between legend and field for inline legend, number multiplied by base spacing unit (8) |  |
| legendWidth | number \| undefined | No |  | [Legacy] Percentage width of legend (only when legend is inline) |  |
| name | string | Yes |  | Specifies the name prop to be applied to each button in the group |  |
| onBlur | ((ev: React.FocusEvent<HTMLInputElement>) => void) \| undefined | No |  | Callback fired when each RadioButton is blurred |  |
| onChange | (ev: React.ChangeEvent<HTMLInputElement>) => void | Yes |  | Callback fired when the user selects a RadioButton |  |
| required | boolean \| undefined | No |  | Flag to configure component as mandatory |  |
| value | string | Yes |  | value of the selected RadioButton |  |
| tooltipPosition | "left" \| "right" \| "bottom" \| "top" \| undefined | No |  | [Legacy] Overrides the default tooltip position |  |
| validationMessagePositionTop | boolean \| undefined | No |  | Render the ValidationMessage above the RadioButton inputs when validationRedesignOptIn flag is set | true |
| error | string \| boolean \| undefined | No |  | Indicate that error has occurred. |  |
| info | string \| boolean \| undefined | No |  | [Legacy] Indicate additional information. |  |
| warning | string \| boolean \| undefined | No |  | Indicate that warning has occurred. |  |
| m | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| margin | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| mt | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| marginTop | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| mb | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| marginBottom | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| ml | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| marginLeft | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| mr | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| marginRight | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| my | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| marginY | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| mx | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| marginX | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |

## Examples
### Default

**Args**

```tsx
{
    children: [],
  }
```


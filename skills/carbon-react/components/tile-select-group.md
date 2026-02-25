---
name: carbon-component-tile-select-group
description: Carbon TileSelectGroup component props and usage examples.
---

# TileSelectGroup

## Import
`import { TileSelectGroup } from "carbon-sage/lib/components/tile-select";`

## Source
- Export: `./components/tile-select`
- Props interface: `TileSelectGroupProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | Yes |  | The TileSelect components to be rendered in the group |  |
| legend | string \| undefined | No |  | The content for the TileSelectGroup Legend |  |
| description | string \| undefined | No |  | Description to be rendered below the legend |  |
| value | string \| null \| undefined | No |  | The currently selected value - only for single select mode. |  |
| name | string | Yes |  | The name to apply to the input - only for single select mode. |  |
| onChange | ((ev: React.ChangeEvent<HTMLInputElement> \| TileSelectDeselectEvent) => void) \| undefined | No |  | A callback triggered when one of tiles is selected - only for single select mode. |  |
| onBlur | ((ev: React.FocusEvent<HTMLInputElement>) => void) \| undefined | No |  | A callback triggered when one of tiles is blurred - only for single select mode. |  |
| multiSelect | boolean \| undefined | No |  | When passed as true TileSelectGroup serves only visual purpose It wraps TileSelects in fieldset element and renders the legend and description props content onChange, onBlur, value, checked and name props are meant to be passed individually on each of the TileSelects | false |
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


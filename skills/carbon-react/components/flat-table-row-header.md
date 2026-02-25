---
name: carbon-component-flat-table-row-header
description: Carbon FlatTableRowHeader component props and usage examples.
---

# FlatTableRowHeader

## Import
`import { FlatTableRowHeader } from "carbon-sage/lib/components/flat-table";`

## Source
- Export: `./components/flat-table`
- Props interface: `FlatTableRowHeaderProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| align | TableCellAlign \| undefined | No |  | Content alignment | "left" |
| children | React.ReactNode | No |  | RowHeader content |  |
| width | number \| undefined | No |  | Column width, pass a number to set a fixed width in pixels |  |
| truncate | boolean \| undefined | No |  | Truncate cell content and add ellipsis to any text that overflows |  |
| title | string \| undefined | No |  | Title text to display if cell content truncates |  |
| verticalBorder | TableBorderSize \| undefined | No |  | Sets a custom vertical right border |  |
| verticalBorderColor | string \| undefined | No |  | Sets the color of the right border |  |
| stickyAlignment | "left" \| "right" \| undefined | No |  | Defines whether the column should be sticky on the left or right hand side of the Table | "left" |
| colspan | string \| number \| undefined | No |  | Number of columns that a header cell should span |  |
| rowspan | string \| number \| undefined | No |  | Number of rows that a header cell should span |  |
| id | string \| undefined | No |  | Sets an id string on the element |  |
| p | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top, left, bottom and right |  |
| padding | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top, left, bottom and right |  |
| pt | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top |  |
| paddingTop | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top |  |
| pb | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on bottom |  |
| paddingBottom | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on bottom |  |
| pl | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left |  |
| paddingLeft | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left |  |
| pr | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on right |  |
| paddingRight | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on right |  |
| py | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top and bottom |  |
| paddingY | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top and bottom |  |
| px | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left and right |  |
| paddingX | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left and right |  |
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


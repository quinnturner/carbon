---
name: carbon-component-list
description: Carbon List component props and usage examples.
---

# List

## Import
`import List from "carbon-sage/lib/components/typography";`

## Source
- Export: `./components/typography`
- Props interface: `ListProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | No |  |  |  |
| as | React.ElementType<any, keyof React.JSX.IntrinsicElements> \| undefined | No |  | Override the variant component | "ul" |
| id | string \| undefined | No |  | Set the ID attribute of the Typography component |  |
| variant | "small" \| "p" \| "sub" \| "b" \| "big" \| "em" \| "h1" \| "h2" \| "h3" \| "h4" \| "h5" \| "ol" \| "span" \| "strong" \| "sup" \| "ul" \| "h1-large" \| "segment-header" \| "segment-header-small" \| "segment-subheader" \| "segment-subheader-alt" \| undefined | No |  | The visual style to apply to the component | "p" |
| fontSize | string \| undefined | No |  | Override the variant font-size |  |
| fontWeight | string \| undefined | No |  | Override the variant font-weight |  |
| lineHeight | string \| undefined | No |  | Override the variant line-height |  |
| textTransform | string \| undefined | No |  | Override the variant text-transform |  |
| textDecoration | string \| undefined | No |  | Override the variant text-decoration |  |
| display | string \| undefined | No |  | Override the variant display |  |
| listStyleType | string \| undefined | No |  | Override the list-style-type |  |
| whiteSpace | string \| undefined | No |  | Override the white-space |  |
| wordBreak | string \| undefined | No |  | Override the word-break |  |
| wordWrap | string \| undefined | No |  | Override the word-wrap |  |
| textAlign | string \| undefined | No |  | Override the text-align |  |
| textOverflow | string \| undefined | No |  | Override the text-overflow |  |
| truncate | boolean \| undefined | No |  | Apply truncation |  |
| color | string \| undefined | No |  | Override the color style |  |
| backgroundColor | string \| undefined | No |  | Override the backgroundColor style |  |
| bg | string \| undefined | No |  | Override the bg value shorthand for backgroundColor |  |
| opacity | string \| number \| undefined | No |  | Override the opacity value |  |
| screenReaderOnly | boolean \| undefined | No |  | Set whether it will be visually hidden NOTE: This is for screen readers only and will make a lot of the other props redundant |  |
| isDisabled | boolean \| undefined | No |  |  |  |
| aria-hidden | "true" \| "false" \| undefined | No |  |  |  |
| className | string \| undefined | No |  |  |  |
| data-component | string \| undefined | No |  |  |  |
| m | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| margin | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| mt | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| marginTop | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| mr | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| marginRight | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| mb | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| marginBottom | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| ml | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| marginLeft | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| mx | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| marginX | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| my | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| marginY | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| p | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top, left, bottom and right |  |
| padding | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top, left, bottom and right |  |
| pt | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top |  |
| paddingTop | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top |  |
| pr | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on right |  |
| paddingRight | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on right |  |
| pb | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on bottom |  |
| paddingBottom | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on bottom |  |
| pl | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left |  |
| paddingLeft | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left |  |
| px | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left and right |  |
| paddingX | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on left and right |  |
| py | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top and bottom |  |
| paddingY | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Padding on top and bottom |  |
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |

## Examples
No Storybook examples found.
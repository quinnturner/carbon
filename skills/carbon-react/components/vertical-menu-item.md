---
name: carbon-component-vertical-menu-item
description: Carbon VerticalMenuItem component props and usage examples.
---

# VerticalMenuItem

## Import
`import { VerticalMenuItem } from "carbon-sage/lib/components/vertical-menu";`

## Source
- Export: `./components/vertical-menu`
- Props interface: `VerticalMenuItemProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | No |  | Children of the menu item - another level of VerticalMenuItems |  |
| customIcon | React.ReactNode | No |  | Custom icon to be displayed. Takes precedence over `iconType` if both are specified. |  |
| defaultOpen | boolean \| undefined | No |  | Default open state of the component | false |
| title | string | Yes |  | Title of the menu item |  |
| adornment | React.ReactNode \| ((isOpen: boolean) => React.ReactNode) | No |  | Adornment of the menu item meant to be rendered on the right side |  |
| iconType | IconType \| undefined | No |  | The Carbon icon to be displayed. Defers to `customIcon` if both are defined. |  |
| active | boolean \| ((isOpen: boolean) => boolean) \| undefined | No |  | Whether the menu item is active or not |  |
| height | string \| undefined | No |  | Height of the menu item | "56px" |
| href | string \| undefined | No |  | Href, when passed the menu item will be rendered as an anchor tag |  |
| onClick | ((event: VerticalMenuItemClickEvent) => void) \| undefined | No |  | A custom click handler to run when the menu item is clicked |  |
| component | T \| undefined | No |  | Optional component to render instead of the default div, useful for rendering router link components |  |
| ariaCurrent | boolean \| "location" \| "page" \| "time" \| "true" \| "false" \| "step" \| "date" \| undefined | No |  | Marks the element as the current item within a navigation context. |  |
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


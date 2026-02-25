---
name: carbon-component-icon-button
description: Carbon IconButton component props and usage examples.
---

# IconButton

## Import
`import IconButton from "carbon-sage/lib/components/icon-button";`

## Source
- Export: `./components/icon-button`
- Props interface: `IconButtonProps`
- Deprecated: Yes
- Deprecation reason: `IconButton` has been deprecated. See the Carbon documentation for migration details.

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| aria-label | string \| undefined | No |  | Prop to specify the aria-label of the icon-button component |  |
| children | React.ReactElement<IconProps, string \| React.JSXElementConstructor<any>> | Yes |  | Icon meant to be rendered, should be an Icon component |  |
| onBlur | ((ev: React.FocusEvent<HTMLButtonElement>) => void) \| undefined | No |  | Callback triggered on blur |  |
| onFocus | ((ev: React.FocusEvent<HTMLButtonElement>) => void) \| undefined | No |  | Callback triggered on focus |  |
| onMouseEnter | ((ev: React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  | Callback triggered on mouse enter |  |
| onMouseLeave | ((ev: React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  | Callback triggered on mouse leave |  |
| disabled | boolean \| undefined | No |  | Set the button to disabled |  |
| onClick | ((e: React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  | Callback triggered on click |  |
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
### Default

**Render**

```tsx
() => {
  return (
    <IconButton aria-label="icon-button" onClick={() => {}}>
      <Icon type="home" />
    </IconButton>
  );
}
```


### With Tooltip

**Render**

```tsx
() => {
  return (
    <IconButton aria-label="icon-button" onClick={() => {}}>
      <Icon type="home" tooltipMessage="Hey I'm a tooltip!" />
    </IconButton>
  );
}
```


### Disabled

**Render**

```tsx
() => {
  return (
    <IconButton disabled aria-label="icon-button" onClick={() => {}}>
      <Icon type="home" />
    </IconButton>
  );
}
```


---
name: carbon-component-loader-next
description: Carbon LoaderNext component props and usage examples.
---

# LoaderNext

## Import
`import LoaderNext from "carbon-sage/lib/components/loader/__next__/loader.component";`

## Source
- Export: `./components/loader/__next__/loader.component`
- Props interface: `LoaderProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
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
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| loaderLabel | string \| undefined | No |  | Specify a label for the loader |  |
| showLabel | boolean \| undefined | No |  | Specify if the label should be visible or not | true |
| hasMotion | boolean \| undefined | No |  | If set to `false` all motion will be suspended | true |
| isTracked | boolean \| undefined | No |  | If set to `true` the animation type will become tracked, this is used specifically for when wait times are predictable | false |
| animationTime | number \| undefined | No |  | Specify a custom animation time for the loader |  |
| inverse | boolean \| undefined | No |  | Toggle the inverse color scheme | false |
| loaderType | LOADER_TYPES \| undefined | No |  | The loader type can be specified in order to change the loader | "standalone" |
| size | LOADER_SIZES \| undefined | No |  | The size prop allows a specific size to be set ranging from `extra-small` to `large` |  |
| variant | LOADER_VARIANTS \| undefined | No |  | Toggle between the different Loader variants |  |
| isSuccess | boolean \| undefined | No |  | Enable the success state for the ring loader when it is tracked | false |
| isError | boolean \| undefined | No |  | Enable the error state for the ring loader when it is tracked | false |

## Examples
No Storybook examples found.
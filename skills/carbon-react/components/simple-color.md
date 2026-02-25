---
name: carbon-component-simple-color
description: Carbon SimpleColor component props and usage examples.
---

# SimpleColor

## Import
`import { SimpleColor } from "carbon-sage/lib/components/simple-color-picker";`

## Source
- Export: `./components/simple-color-picker`
- Props interface: `SimpleColorProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| aria-label | string \| undefined | No |  | the value of the label to pass to screen reader software |  |
| value | string | Yes |  | the value of the color that is represented by this SimpleColor |  |
| name | string \| undefined | No |  | the input name |  |
| id | string \| undefined | No |  | the input id |  |
| disabled | boolean \| undefined | No |  | if true, input will be disabled |  |
| onChange | ((ev: React.ChangeEvent<HTMLInputElement>) => void) \| undefined | No |  | called when the user selects or deselects this color option |  |
| onBlur | ((ev: React.FocusEvent<HTMLInputElement>) => void) \| undefined | No |  | Prop for `onBlur` events |  |
| onMouseDown | ((ev: React.MouseEvent<HTMLInputElement>) => void) \| undefined | No |  | Prop for `onMouseDown` events |  |
| checked | boolean \| undefined | No |  | determines if this color option is selected or unselected |  |
| defaultChecked | boolean \| undefined | No |  | determines if this color option is selected or unselected when component is used as uncontrolled |  |
| className | string \| undefined | No |  |  |  |

## Examples
### Default

**Args**

```tsx
{}
```


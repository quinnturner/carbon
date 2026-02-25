---
name: carbon-component-option-row
description: Carbon OptionRow component props and usage examples.
---

# OptionRow

## Import
`import { OptionRow } from "carbon-sage/lib/components/select";`

## Source
- Export: `./components/select`
- Props interface: `OptionRowProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| text | string | Yes |  | The option's visible text, displayed within <Textbox> of <Select> |  |
| children | React.ReactNode | Yes |  | Row content, should consist of multiple td elements |  |
| value | string \| Record<string, unknown> | Yes |  | The option's invisible internal value |  |
| id | string \| undefined | No |  | Unique identifier for the component. Will use a randomly generated GUID if none is provided. |  |
| disabled | boolean \| undefined | No |  | If true, the component will be disabled |  |
| onSelect | ((data: { id: string; text: string; value: string \| Record<string, unknown>; }) => void) \| undefined | No |  |  |  |
| index | number \| undefined | No |  |  |  |
| hidden | boolean \| undefined | No |  |  |  |
| style | CSSProperties \| undefined | No |  |  |  |
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |

## Examples
No Storybook examples found.
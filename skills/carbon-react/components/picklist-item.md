---
name: carbon-component-picklist-item
description: Carbon PicklistItem component props and usage examples.
---

# PicklistItem

## Import
`import { PicklistItem } from "carbon-sage/lib/components/duelling-picklist";`

## Source
- Export: `./components/duelling-picklist`
- Props interface: `PicklistItemProps`
- Deprecated: Yes
- Deprecation reason: `PicklistItem` has been deprecated. See the Carbon documentation for migration details.

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | Yes |  | Item content |  |
| type | "add" \| "remove" | Yes | add \| remove | Define if item is of type add or remove |  |
| onChange | (item: Item) => void | Yes |  | Handler invoked when add/remove button is clicked or when space/enter is pressed on the whole item |  |
| item | Item | Yes |  | Value passed to the onChange handler - can be a string, a number or an object |  |
| locked | boolean \| undefined | No |  | Disable the item |  |
| tooltipMessage | string \| undefined | No |  | Tooltip message for the locked icon (only present when locked prop is true) |  |
| index | number \| undefined | No |  |  |  |
| groupIndex | number \| undefined | No |  |  |  |
| listIndex | number \| undefined | No |  |  |  |
| isLastItem | boolean \| undefined | No |  |  |  |
| isLastGroup | boolean \| undefined | No |  |  |  |

## Examples
### Default

**Args**

```tsx
{
    children: [],
  }
```


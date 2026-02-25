---
name: carbon-component-sort
description: Carbon Sort component props and usage examples.
---

# Sort

## Import
`import { Sort } from "carbon-sage/lib/components/flat-table";`

## Source
- Export: `./components/flat-table`
- Props interface: `SortProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| sortType | "ascending" \| "descending" \| undefined | No |  | if `asc` it will show `sort_up` icon, if `desc` it will show `sort_down` |  |
| onClick | (() => void) \| undefined | No |  | Callback fired when the component is clicked |  |
| children | string \| undefined | No |  | Sets the text content of the component |  |
| accessibleName | string \| undefined | No |  | Sets the accessible name of the component |  |
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |

## Examples
### Default

**Args**

```tsx
{
    children: "",
  }
```


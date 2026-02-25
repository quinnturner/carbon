---
name: carbon-component-anchor-navigation-item
description: Carbon AnchorNavigationItem component props and usage examples.
---

# AnchorNavigationItem

## Import
`import { AnchorNavigationItem } from "carbon-sage/lib/components/anchor-navigation";`

## Source
- Export: `./components/anchor-navigation`
- Props interface: `AnchorNavigationItemProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| target | React.RefObject<HTMLElement> \| undefined | No |  | Reference to the section html element meant to be shown |  |
| href | string \| undefined | No |  | href to be passed to the anchor element, can be linked with id passed to the scrollable section |  |
| isSelected | boolean \| undefined | No |  | Indicates if component is selected |  |
| onClick | ((ev: React.MouseEvent<HTMLAnchorElement>) => void) \| undefined | No |  | onClick handler |  |
| onKeyDown | ((ev: React.KeyboardEvent<HTMLAnchorElement>) => void) \| undefined | No |  | OnKeyDown handler |  |
| tabIndex | number \| undefined | No |  | tabIndex passed to the anchor element |  |
| children | React.ReactNode | No |  | Children elements |  |

## Examples
### Default

**Args**

```tsx
{
    children: [],
  }
```


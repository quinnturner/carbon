---
name: carbon-component-crumb
description: Carbon Crumb component props and usage examples.
---

# Crumb

## Import
`import { Crumb } from "carbon-sage/lib/components/breadcrumbs";`

## Source
- Export: `./components/breadcrumbs`
- Props interface: `CrumbProps`

## Props
| Name | Type | Required | Literals | Deprecated | Deprecation reason | Description | Default |
| --- | --- | --- | --- | --- | --- | --- | --- |
| isCurrent | boolean \| undefined | No |  |  |  | This sets the Crumb to current, does not render Link |  |
| bold | boolean \| undefined | No |  |  |  | Sets the link style to bold |  |
| download | any | No |  |  |  |  |  |
| underline | "always" \| "hover" \| "never" \| undefined | No |  |  |  | Specifies when the link underline should be displayed. |  |
| data-element | string \| undefined | No |  |  |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  |  |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| href | string \| undefined | No |  |  |  | An href for an anchor tag. |  |
| onClick | ((ev: React.MouseEvent<HTMLAnchorElement> \| React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  |  |  | Function called when the mouse is clicked. |  |
| onKeyDown | ((ev: React.KeyboardEvent<HTMLAnchorElement> \| React.KeyboardEvent<HTMLButtonElement>) => void) \| undefined | No |  |  |  | Function called when a key is pressed. |  |
| onMouseDown | ((ev: React.MouseEvent<HTMLAnchorElement> \| React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  |  |  | Function called when a mouse down event triggers. |  |
| children | React.ReactNode | No |  |  |  | Child content to render in the link. |  |
| removeAriaLabelOnIcon | boolean \| undefined | No |  |  |  |  |  |
| hasFocus | boolean \| undefined | No |  |  |  |  |  |
| linkSize | "large" \| "medium" \| undefined | No |  |  |  | Sets the correct link size |  |
| aria-activedescendant | string \| undefined | No |  |  |  | Identifies the currently active element when DOM focus is on a composite widget, textbox, group, or application. |  |
| aria-atomic | Booleanish \| undefined | No |  |  |  | Indicates whether assistive technologies will present all, or only parts of, the changed region based on the change notifications defined by the aria-relevant attribute. |  |
| aria-autocomplete | "none" \| "inline" \| "list" \| "both" \| undefined | No |  |  |  | Indicates whether inputting text could trigger display of one or more predictions of the user's intended value for an input and specifies how predictions would be presented if they are made. |  |
| aria-braillelabel | string \| undefined | No |  |  |  | Indicates an element is being modified and that assistive technologies MAY want to wait until the modifications are complete before exposing them to the user. Defines a string value that labels the current element, which is intended to be converted into Braille. |  |
| aria-brailleroledescription | string \| undefined | No |  |  |  | Defines a human-readable, author-localized abbreviated description for the role of an element, which is intended to be converted into Braille. |  |
| aria-busy | Booleanish \| undefined | No |  |  |  |  |  |
| aria-checked | boolean \| "true" \| "false" \| "mixed" \| undefined | No |  |  |  | Indicates the current "checked" state of checkboxes, radio buttons, and other widgets. |  |
| aria-colcount | number \| undefined | No |  |  |  | Defines the total number of columns in a table, grid, or treegrid. |  |
| aria-colindex | number \| undefined | No |  |  |  | Defines an element's column index or position with respect to the total number of columns within a table, grid, or treegrid. |  |
| aria-colindextext | string \| undefined | No |  |  |  | Defines a human readable text alternative of aria-colindex. |  |
| aria-colspan | number \| undefined | No |  |  |  | Defines the number of columns spanned by a cell or gridcell within a table, grid, or treegrid. |  |
| aria-controls | string \| undefined | No |  |  |  | Identifies the element (or elements) whose contents or presence are controlled by the current element. |  |
| aria-current | boolean \| "location" \| "page" \| "time" \| "true" \| "false" \| "step" \| "date" \| undefined | No |  |  |  | Indicates the element that represents the current item within a container or set of related elements. |  |
| aria-describedby | string \| undefined | No |  |  |  | Identifies the element (or elements) that describes the object. |  |
| aria-description | string \| undefined | No |  |  |  | Defines a string value that describes or annotates the current element. |  |
| aria-details | string \| undefined | No |  |  |  | Identifies the element that provides a detailed, extended description for the object. |  |
| aria-disabled | Booleanish \| undefined | No |  |  |  | Indicates that the element is perceivable but disabled, so it is not editable or otherwise operable. |  |
| aria-dropeffect | "none" \| "copy" \| "link" \| "execute" \| "move" \| "popup" \| undefined | No |  | Yes | in ARIA 1.1 | Indicates what functions can be performed when a dragged object is released on the drop target. |  |
| aria-errormessage | string \| undefined | No |  |  |  | Identifies the element that provides an error message for the object. |  |
| aria-expanded | Booleanish \| undefined | No |  |  |  | Indicates whether the element, or another grouping element it controls, is currently expanded or collapsed. |  |
| aria-flowto | string \| undefined | No |  |  |  | Identifies the next element (or elements) in an alternate reading order of content which, at the user's discretion, allows assistive technology to override the general default of reading in document source order. |  |
| aria-grabbed | Booleanish \| undefined | No |  | Yes | in ARIA 1.1 | Indicates an element's "grabbed" state in a drag-and-drop operation. |  |
| aria-haspopup | boolean \| "grid" \| "dialog" \| "menu" \| "true" \| "false" \| "listbox" \| "tree" \| undefined | No |  |  |  | Indicates the availability and type of interactive popup element, such as menu or dialog, that can be triggered by an element. |  |
| aria-hidden | Booleanish \| undefined | No |  |  |  | Indicates whether the element is exposed to an accessibility API. |  |
| aria-invalid | boolean \| "true" \| "false" \| "grammar" \| "spelling" \| undefined | No |  |  |  | Indicates the entered value does not conform to the format expected by the application. |  |
| aria-keyshortcuts | string \| undefined | No |  |  |  | Indicates keyboard shortcuts that an author has implemented to activate or give focus to an element. |  |
| aria-label | string \| undefined | No |  |  |  | Defines a string value that labels the current element. |  |
| aria-labelledby | string \| undefined | No |  |  |  | Identifies the element (or elements) that labels the current element. |  |
| aria-level | number \| undefined | No |  |  |  | Defines the hierarchical level of an element within a structure. |  |
| aria-live | "off" \| "assertive" \| "polite" \| undefined | No |  |  |  | Indicates that an element will be updated, and describes the types of updates the user agents, assistive technologies, and user can expect from the live region. |  |
| aria-modal | Booleanish \| undefined | No |  |  |  | Indicates whether an element is modal when displayed. |  |
| aria-multiline | Booleanish \| undefined | No |  |  |  | Indicates whether a text box accepts multiple lines of input or only a single line. |  |
| aria-multiselectable | Booleanish \| undefined | No |  |  |  | Indicates that the user may select more than one item from the current selectable descendants. |  |
| aria-orientation | "horizontal" \| "vertical" \| undefined | No |  |  |  | Indicates whether the element's orientation is horizontal, vertical, or unknown/ambiguous. |  |
| aria-owns | string \| undefined | No |  |  |  | Identifies an element (or elements) in order to define a visual, functional, or contextual parent/child relationship between DOM elements where the DOM hierarchy cannot be used to represent the relationship. |  |
| aria-placeholder | string \| undefined | No |  |  |  | Defines a short hint (a word or short phrase) intended to aid the user with data entry when the control has no value. A hint could be a sample value or a brief description of the expected format. |  |
| aria-posinset | number \| undefined | No |  |  |  | Defines an element's number or position in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM. |  |
| aria-pressed | boolean \| "true" \| "false" \| "mixed" \| undefined | No |  |  |  | Indicates the current "pressed" state of toggle buttons. |  |
| aria-readonly | Booleanish \| undefined | No |  |  |  | Indicates that the element is not editable, but is otherwise operable. |  |
| aria-relevant | "text" \| "additions" \| "additions removals" \| "additions text" \| "all" \| "removals" \| "removals additions" \| "removals text" \| "text additions" \| "text removals" \| undefined | No |  |  |  | Indicates what notifications the user agent will trigger when the accessibility tree within a live region is modified. |  |
| aria-required | Booleanish \| undefined | No |  |  |  | Indicates that user input is required on the element before a form may be submitted. |  |
| aria-roledescription | string \| undefined | No |  |  |  | Defines a human-readable, author-localized description for the role of an element. |  |
| aria-rowcount | number \| undefined | No |  |  |  | Defines the total number of rows in a table, grid, or treegrid. |  |
| aria-rowindex | number \| undefined | No |  |  |  | Defines an element's row index or position with respect to the total number of rows within a table, grid, or treegrid. |  |
| aria-rowindextext | string \| undefined | No |  |  |  | Defines a human readable text alternative of aria-rowindex. |  |
| aria-rowspan | number \| undefined | No |  |  |  | Defines the number of rows spanned by a cell or gridcell within a table, grid, or treegrid. |  |
| aria-selected | Booleanish \| undefined | No |  |  |  | Indicates the current "selected" state of various widgets. |  |
| aria-setsize | number \| undefined | No |  |  |  | Defines the number of items in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM. |  |
| aria-sort | "none" \| "ascending" \| "descending" \| "other" \| undefined | No |  |  |  | Indicates if items in a table or grid are sorted in ascending or descending order. |  |
| aria-valuemax | number \| undefined | No |  |  |  | Defines the maximum allowed value for a range widget. |  |
| aria-valuemin | number \| undefined | No |  |  |  | Defines the minimum allowed value for a range widget. |  |
| aria-valuenow | number \| undefined | No |  |  |  | Defines the current value for a range widget. |  |
| aria-valuetext | string \| undefined | No |  |  |  | Defines the human readable text alternative of aria-valuenow for a range widget. |  |

## Examples
### Default

**Args**

```tsx
{
    children: [],
  }
```


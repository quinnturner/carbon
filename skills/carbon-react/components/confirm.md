---
name: carbon-component-confirm
description: Carbon Confirm component props and usage examples.
---

# Confirm

## Import
`import Confirm from "carbon-sage/lib/components/confirm";`

## Source
- Export: `./components/confirm`
- Props interface: `ConfirmProps`
- Deprecated: Yes
- Deprecation reason: See the Carbon documentation for migration details.

## Props
| Name | Type | Required | Literals | Deprecated | Deprecation reason | Description | Default |
| --- | --- | --- | --- | --- | --- | --- | --- |
| cancelButtonType | "primary" \| "secondary" \| "tertiary" \| "darkBackground" \| undefined | No |  |  |  | Color variants for new business themes: "primary" \| "secondary" \| "tertiary" \| "darkBackground" | "secondary" |
| confirmButtonType | "primary" \| "secondary" \| "tertiary" \| "darkBackground" \| undefined | No |  |  |  | Color variants for new business themes: "primary" \| "secondary" \| "tertiary" \| "darkBackground" | "primary" |
| cancelLabel | string \| undefined | No |  |  |  | Customise the cancel button label |  |
| confirmLabel | string \| undefined | No |  |  |  | Customise the confirm button label |  |
| cancelButtonDestructive | boolean \| undefined | No |  |  |  | Apply destructive style to the cancel button | false |
| confirmButtonDestructive | boolean \| undefined | No |  |  |  | Apply destructive style to the confirm button | false |
| cancelButtonIconPosition | "before" \| "after" \| undefined | No |  |  |  | Defines a cancel button Icon position related to the children: "before" \| "after" |  |
| cancelButtonIconType | IconType \| undefined | No |  |  |  | Defines an Icon type within the cancel button (see Icon for options) |  |
| confirmButtonIconPosition | "before" \| "after" \| undefined | No |  |  |  | Defines a cancel button Icon position related to the children: "before" \| "after" |  |
| confirmButtonIconType | IconType \| undefined | No |  |  |  | Defines an Icon type within the confirm button (see Icon for options) |  |
| cancelButtonDataProps | TagProps \| undefined | No |  |  |  | Data tag prop bag for cancelButton |  |
| confirmButtonDataProps | TagProps \| undefined | No |  |  |  | Data tag prop bag for confirmButton |  |
| disableCancel | boolean \| undefined | No |  |  |  | Makes cancel button disabled |  |
| disableConfirm | boolean \| undefined | No |  |  |  | Makes confirm button disabled |  |
| iconType | "error" \| "warning" \| undefined | No |  |  |  | Defines an Icon type within the button (see Icon for options) |  |
| isLoadingConfirm | boolean \| undefined | No |  |  |  | Adds isLoading state into confirm button |  |
| onConfirm | (ev: React.MouseEvent<HTMLButtonElement>) => void | Yes |  |  |  | A custom event handler when a confirmation takes place |  |
| fullscreen | boolean \| undefined | No |  |  |  | Whether the dialog is full-screen |  |
| data-element | string \| undefined | No |  |  |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  |  |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| restoreFocusOnClose | boolean \| undefined | No |  |  |  | Enables the automatic restoration of focus to the element that invoked the modal when the modal is closed. |  |
| topModalOverride | boolean \| undefined | No |  |  |  | Manually override the internal modal stacking order to set this as top |  |
| title | React.ReactNode | No |  |  |  | Title displayed at top of dialog. Its consumers' responsibility to set a suitable accessible name/description for the Dialog if they pass a node to title prop. |  |
| children | React.ReactNode | No |  |  |  | Child elements |  |
| aria-describedby | string \| undefined | No |  |  |  | Prop to specify the aria-describedby property of the Dialog component |  |
| aria-label | string \| undefined | No |  |  |  | Prop to specify the aria-label of the Dialog component. To be used only when the title prop is not defined, and the component is not labelled by any internal element. |  |
| aria-labelledby | string \| undefined | No |  |  |  | Prop to specify the aria-labelledby property of the Dialog component To be used when the title prop is a custom React Node, or the component is labelled by an internal element other than the title. |  |
| size | "auto" \| "large" \| "small" \| "medium" \| "extra-small" \| "medium-small" \| "medium-large" \| "extra-large" \| "maximise" \| undefined | No |  |  |  | Size of dialog, default size is 750px | "extra-small" |
| height | string \| undefined | No |  |  |  | Allows developers to specify a specific height for the dialog. |  |
| closeButtonDataProps | Pick<TagProps, "data-element" \| "data-role"> \| undefined | No |  |  |  | Data tag prop bag for close Button |  |
| contentRef | React.ForwardedRef<HTMLDivElement> \| undefined | No |  |  |  | Reference to the scrollable content element |  |
| disableAutoFocus | boolean \| undefined | No |  |  |  |  |  |
| disableContentPadding | boolean \| undefined | No |  | Yes | Use `contentPadding` instead. | [Legacy] Flag to remove padding from content. |  |
| focusFirstElement | HTMLElement \| React.RefObject<HTMLElement> \| null \| undefined | No |  |  |  | Optional reference to an element meant to be focused on open |  |
| greyBackground | boolean \| undefined | No |  |  |  | Change the background color of the content to grey |  |
| headerChildren | React.ReactNode | No |  |  |  | Container for components to be displayed in the header |  |
| highlightVariant | string \| undefined | No |  |  |  |  |  |
| onCancel | ((ev: React.KeyboardEvent<HTMLElement> \| KeyboardEvent \| React.MouseEvent<HTMLButtonElement>) => void) \| undefined | No |  |  |  | A custom close event handler |  |
| pagesStyling | boolean \| undefined | No |  | Yes | For legacy styling when used with Pages component. Do not use this unless using Pages within a full-screen Dialog |  |  |
| showCloseIcon | boolean \| undefined | No |  |  |  | Determines if the close icon is shown | false |
| subtitle | React.ReactNode | No |  |  |  | Subtitle displayed at top of dialog. Its consumers' responsibility to set a suitable accessible name/description for the Dialog if they pass a node to subtitle prop. |  |
| disableEscKey | boolean \| undefined | No |  |  |  | Determines if the Esc Key closes the modal |  |
| open | boolean | Yes |  |  |  | Sets the open state of the modal |  |

## Examples
### Default

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        cancelButtonDestructive
        title="Are you sure?"
        subtitle="Subtitle"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Default with Custom Data Tags

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        cancelButtonDestructive
        title="Are you sure?"
        subtitle="Subtitle"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
        cancelButtonDataProps={{
          "data-element": "bang",
          "data-role": "wallop",
        }}
        confirmButtonDataProps={{
          "data-element": "bar",
          "data-role": "wiz",
        }}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Single Action

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Cancel Button Destructive

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        cancelButtonDestructive
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Confirm Button Destructive

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        confirmButtonDestructive
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Disable Confirm

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        confirmButtonDestructive
        cancelButtonDestructive
        disableConfirm
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Disable Cancel

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        showCloseIcon
        disableCancel
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Cancel Button Type

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        cancelButtonType="tertiary"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Confirm Button Type

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        confirmButtonType="tertiary"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Buttons Icons

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        confirmButtonIconType="save"
        confirmButtonIconPosition="after"
        cancelButtonIconType="bin"
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


### Is Loading Confirm

**Render**

```tsx
() => {
  const [isOpen, setIsOpen] = useState(defaultOpenState);
  return (
    <>
      <Button onClick={() => setIsOpen(true)}>Open Confirm</Button>
      <Confirm
        title="Are you sure?"
        subtitle="Subtitle"
        isLoadingConfirm
        open={isOpen}
        onConfirm={() => setIsOpen(false)}
        onCancel={() => setIsOpen(false)}
      >
        Content
      </Confirm>
    </>
  );
}
```


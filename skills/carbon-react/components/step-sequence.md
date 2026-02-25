---
name: carbon-component-step-sequence
description: Carbon StepSequence component props and usage examples.
---

# StepSequence

## Import
`import { StepSequence } from "carbon-sage/lib/components/step-sequence";`

## Source
- Export: `./components/step-sequence`
- Props interface: `StepSequenceProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | Yes |  | Step sequence items to be rendered |  |
| orientation | "horizontal" \| "vertical" \| undefined | No |  | The direction that step sequence items should be rendered | "horizontal" |
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
    <StepSequence>
      <StepSequenceItem
        aria-label="Step 1 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="1"
        status="complete"
      >
        Name
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 2 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="2"
        status="complete"
      >
        Delivery Address
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 3 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="3"
        status="current"
      >
        Delivery Details
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 4 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="4"
        status="incomplete"
      >
        Payment
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 5 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="5"
        status="incomplete"
      >
        Confirm
      </StepSequenceItem>
    </StepSequence>
  );
}
```


### Vertical

**Render**

```tsx
() => {
  return (
    <Box height="600px">
      <StepSequence orientation="vertical">
        <StepSequenceItem
          aria-label="Step 1 of 5"
          hiddenCompleteLabel="Complete"
          hiddenCurrentLabel="Current"
          indicator="1"
          status="complete"
        >
          Name
        </StepSequenceItem>
        <StepSequenceItem
          aria-label="Step 2 of 5"
          hiddenCompleteLabel="Complete"
          hiddenCurrentLabel="Current"
          indicator="2"
          status="complete"
        >
          Delivery Address
        </StepSequenceItem>
        <StepSequenceItem
          aria-label="Step 3 of 5"
          hiddenCompleteLabel="Complete"
          hiddenCurrentLabel="Current"
          indicator="3"
          status="current"
        >
          Delivery Details
        </StepSequenceItem>
        <StepSequenceItem
          aria-label="Step 4 of 5"
          hiddenCompleteLabel="Complete"
          hiddenCurrentLabel="Current"
          indicator="4"
          status="incomplete"
        >
          Payment
        </StepSequenceItem>
        <StepSequenceItem
          aria-label="Step 5 of 5"
          hiddenCompleteLabel="Complete"
          hiddenCurrentLabel="Current"
          indicator="5"
          status="incomplete"
        >
          Confirm
        </StepSequenceItem>
      </StepSequence>
    </Box>
  );
}
```


### With Hidden Indicators

**Render**

```tsx
() => {
  return (
    <StepSequence>
      <StepSequenceItem
        aria-label="Step 1 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="1"
        status="complete"
      >
        Name
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 2 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="2"
        status="complete"
      >
        Delivery Address
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 3 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="3"
        hideIndicator
        status="current"
      >
        Delivery Details
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 4 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="4"
        hideIndicator
        status="incomplete"
      >
        Payment
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 5 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="5"
        hideIndicator
        status="incomplete"
      >
        Confirm
      </StepSequenceItem>
    </StepSequence>
  );
}
```


### Responsive Example

**Render**

```tsx
() => {
  const displayVertical = useMediaQuery("(max-width: 760px)");
  return (
    <StepSequence orientation={displayVertical ? "vertical" : "horizontal"}>
      <StepSequenceItem
        aria-label="Step 1 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="1"
        status="complete"
      >
        Name
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 2 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="2"
        status="complete"
      >
        Delivery Address
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 3 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="3"
        status="current"
      >
        Delivery Details
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 4 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="4"
        status="incomplete"
      >
        Payment
      </StepSequenceItem>
      <StepSequenceItem
        aria-label="Step 5 of 5"
        hiddenCompleteLabel="Complete"
        hiddenCurrentLabel="Current"
        indicator="5"
        status="incomplete"
      >
        Confirm
      </StepSequenceItem>
    </StepSequence>
  );
}
```


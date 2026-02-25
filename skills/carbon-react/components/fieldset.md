---
name: carbon-component-fieldset
description: Carbon Fieldset component props and usage examples.
---

# Fieldset

## Import
`import Fieldset from "carbon-sage/lib/components/fieldset";`

## Source
- Export: `./components/fieldset`
- Props interface: `FieldsetProps`

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| children | React.ReactNode | No |  | Child elements |  |
| legend | string \| undefined | No |  | The text for the fieldset's legend element. |  |
| required | boolean \| undefined | No |  | Flag to configure fields as mandatory. |  |
| m | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| margin | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top, left, bottom and right |  |
| mt | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| marginTop | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top |  |
| mb | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| marginBottom | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on bottom |  |
| ml | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| marginLeft | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left |  |
| mr | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| marginRight | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on right |  |
| my | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| marginY | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on top and bottom |  |
| mx | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| marginX | ResponsiveValue<TVal, ThemeType> \| undefined | No |  | Margin on left and right |  |
| data-element | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |
| data-role | string \| undefined | No |  | Identifier used for testing purposes, applied to the root element of the component. |  |

## Examples
### Default

**Render**

```tsx
() => (
  <CarbonProvider validationRedesignOptIn>
    <Form>
      <Fieldset legend="Fieldset">
        <Textbox label="Address Line 1" value={""} onChange={() => {}} />
        <Textbox label="Address Line 2" value={""} onChange={() => {}} />
        <Textbox label="City" value={""} onChange={() => {}} />
        <Select label="Country" value={""} onChange={() => {}}>
          <Option text="United Kingdom" value="uk" />
          <Option text="Spain" value="sp" />
          <Option text="France" value="fr" />
          <Option text="Germany" value="ge" />
        </Select>
        <Textbox
          label="Postcode"
          maxWidth="100px"
          value={""}
          onChange={() => {}}
        />
      </Fieldset>
    </Form>
  </CarbonProvider>
)
```


### With fieldSpacing

**Render**

```tsx
() => (
  <CarbonProvider validationRedesignOptIn>
    <Form fieldSpacing={1}>
      <Fieldset legend="Fieldset">
        <Textbox label="Address Line 1" value={""} onChange={() => {}} />
        <Textbox label="Address Line 2" value={""} onChange={() => {}} />
        <Textbox label="City" value={""} onChange={() => {}} />
        <Select label="Country" value={""} onChange={() => {}}>
          <Option text="United Kingdom" value="uk" />
          <Option text="Spain" value="sp" />
          <Option text="France" value="fr" />
          <Option text="Germany" value="ge" />
        </Select>
        <Textbox
          label="Postcode"
          maxWidth="100px"
          value={""}
          onChange={() => {}}
        />
      </Fieldset>
    </Form>
  </CarbonProvider>
)
```


### Required

**Render**

```tsx
() => (
  <CarbonProvider validationRedesignOptIn>
    <Form>
      <Fieldset legend="Fieldset" required>
        <Textbox label="Address Line 1" value={""} onChange={() => {}} />
        <Textbox label="Address Line 2" value={""} onChange={() => {}} />
        <Textbox label="City" value={""} onChange={() => {}} />
        <Select label="Country" value={""} onChange={() => {}}>
          <Option text="United Kingdom" value="uk" />
          <Option text="Spain" value="sp" />
          <Option text="France" value="fr" />
          <Option text="Germany" value="ge" />
        </Select>
        <Textbox
          label="Postcode"
          maxWidth="100px"
          value={""}
          onChange={() => {}}
        />
      </Fieldset>
    </Form>
  </CarbonProvider>
)
```


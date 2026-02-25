---
name: carbon-component-settings-row
description: Carbon SettingsRow component props and usage examples.
---

# SettingsRow

## Import
`import SettingsRow from "carbon-sage/lib/components/settings-row";`

## Source
- Export: `./components/settings-row`
- Props interface: `SettingsRowProps`
- Deprecated: Yes
- Deprecation reason: `SettingsRow` has been deprecated. See the Carbon documentation for migration details.

## Props
| Name | Type | Required | Literals | Description | Default |
| --- | --- | --- | --- | --- | --- |
| title | string \| undefined | No |  | A title for this group of settings. |  |
| headingType | HeadingType \| undefined | No |  | Defines the HTML heading element of the `title` within the component. | "h3" |
| children | React.ReactNode | No |  | Content to be rendered inside the component. |  |
| description | React.ReactNode | No |  | A string or JSX object that provides a short description about the group of settings. |  |
| divider | boolean \| undefined | No |  | Shows a divider below the component. | true |
| className | string \| undefined | No |  |  |  |
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
() => {
  return (
    <SettingsRow description="Description" title="Title">
      Content for settings
    </SettingsRow>
  );
}
```


### Heading Type

**Render**

```tsx
() => {
  return (
    <>
      <SettingsRow
        headingType="h1"
        description="Description"
        title="This is a h1 Title"
      >
        Content for settings
      </SettingsRow>
      <SettingsRow
        headingType="h2"
        description="Description"
        title="This is a h2 Title"
      >
        Content for settings
      </SettingsRow>
      <SettingsRow
        headingType="h3"
        description="Description"
        title="This is a h3 Title"
      >
        Content for settings
      </SettingsRow>
      <SettingsRow
        headingType="h4"
        description="Description"
        title="This is a h4 Title"
      >
        Content for settings
      </SettingsRow>
      <SettingsRow
        headingType="h5"
        description="Description"
        title="This is a h5 Title"
      >
        Content for settings
      </SettingsRow>
    </>
  );
}
```


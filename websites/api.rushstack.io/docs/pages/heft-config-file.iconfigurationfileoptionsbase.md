---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft-config-file](./heft-config-file.md) &gt; [IConfigurationFileOptionsBase](./heft-config-file.iconfigurationfileoptionsbase.md)

## IConfigurationFileOptionsBase interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 


**Signature:**

```typescript
export interface IConfigurationFileOptionsBase<TConfigurationFile> 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [jsonPathMetadata?](./heft-config-file.iconfigurationfileoptionsbase.jsonpathmetadata.md) |  | [IJsonPathsMetadata](./heft-config-file.ijsonpathsmetadata.md) | **_(BETA)_** _(Optional)_ Use this property to specify how JSON nodes are postprocessed. |
|  [projectRelativeFilePath](./heft-config-file.iconfigurationfileoptionsbase.projectrelativefilepath.md) |  | string | **_(BETA)_** A project root-relative path to the configuration file that should be loaded. |
|  [propertyInheritance?](./heft-config-file.iconfigurationfileoptionsbase.propertyinheritance.md) |  | [IPropertiesInheritance](./heft-config-file.ipropertiesinheritance.md)<></>&lt;TConfigurationFile&gt; | **_(BETA)_** _(Optional)_ Use this property to control how root-level properties are handled between parent and child configuration files. |
|  [propertyInheritanceDefaults?](./heft-config-file.iconfigurationfileoptionsbase.propertyinheritancedefaults.md) |  | [IPropertyInheritanceDefaults](./heft-config-file.ipropertyinheritancedefaults.md) | **_(BETA)_** _(Optional)_ Use this property to control how specific property types are handled between parent and child configuration files. |

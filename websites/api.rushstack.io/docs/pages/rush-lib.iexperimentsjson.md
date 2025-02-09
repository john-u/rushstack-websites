---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [IExperimentsJson](./rush-lib.iexperimentsjson.md)

## IExperimentsJson interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

This interface represents the raw experiments.json file which allows repo maintainers to enable and disable experimental Rush features.

**Signature:**

```typescript
export interface IExperimentsJson 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [buildCacheWithAllowWarningsInSuccessfulBuild?](./rush-lib.iexperimentsjson.buildcachewithallowwarningsinsuccessfulbuild.md) |  | boolean | **_(BETA)_** _(Optional)_ If true, build caching will respect the allowWarningsInSuccessfulBuild flag and cache builds with warnings. This will not replay warnings from the cached build. |
|  [cleanInstallAfterNpmrcChanges?](./rush-lib.iexperimentsjson.cleaninstallafternpmrcchanges.md) |  | boolean | **_(BETA)_** _(Optional)_ If true, perform a clean install after when running <code>rush install</code> or <code>rush update</code> if the <code>.npmrc</code> file has changed since the last install. |
|  [noChmodFieldInTarHeaderNormalization?](./rush-lib.iexperimentsjson.nochmodfieldintarheadernormalization.md) |  | boolean | **_(BETA)_** _(Optional)_ If true, the chmod field in temporary project tar headers will not be normalized. This normalization can help ensure consistent tarball integrity across platforms. |
|  [omitImportersFromPreventManualShrinkwrapChanges?](./rush-lib.iexperimentsjson.omitimportersfrompreventmanualshrinkwrapchanges.md) |  | boolean | **_(BETA)_** _(Optional)_ If using the 'preventManualShrinkwrapChanges' option, restricts the hash to only include the layout of external dependencies. Used to allow links between workspace projects or the addition/removal of references to existing dependency versions to not cause hash changes. |
|  [phasedCommands?](./rush-lib.iexperimentsjson.phasedcommands.md) |  | boolean | **_(BETA)_** _(Optional)_ If true, the phased commands feature is enabled. To use this feature, create a "phased" command in common/config/rush/command-line.json. |
|  [usePnpmFrozenLockfileForRushInstall?](./rush-lib.iexperimentsjson.usepnpmfrozenlockfileforrushinstall.md) |  | boolean | **_(BETA)_** _(Optional)_ By default, 'rush install' passes --no-prefer-frozen-lockfile to 'pnpm install'. Set this option to true to pass '--frozen-lockfile' instead. |
|  [usePnpmPreferFrozenLockfileForRushUpdate?](./rush-lib.iexperimentsjson.usepnpmpreferfrozenlockfileforrushupdate.md) |  | boolean | **_(BETA)_** _(Optional)_ By default, 'rush update' passes --no-prefer-frozen-lockfile to 'pnpm install'. Set this option to true to pass '--prefer-frozen-lockfile' instead. |


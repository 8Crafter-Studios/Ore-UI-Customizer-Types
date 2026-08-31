# v1.3.0

## Additions

-   Added the following fields to the `OreUICustomzierSettings` interface:
    -   `themes`
    -   `bundleEncodedThemeDataInConfigFile`
    -   `activeThemesDetails`
-   Added the `EncodedThemeData` interface.

## Changes

-   The `version` fields of dependencies are now optional.
-   Renamed the `themes` field of the `OreUICustomizerSettings` interface to `preloadedThemes`.

# v1.2.1

## Fixes

-   Fixed an issue where the `min_engine_version` field of the `header` field of the `ThemeManifestJSON` interface was missing.
-   Typo fixes.

# v1.2.0

## Additions

-   Added the `lite-play-screen-routes` built-in plugin ID.
-   Added the `Theme` interface.
-   Added the `ThemeColorReplacements` interface.
-   Added the `advancedColorReplacements` field to the `OreUICustomizerSettings` interface.
-   Added the `themes` field to the `OreUICustomizerSettings` interface.
-   Added the `namespace` field to the `header` field of the `ThemeManifestJSON` interface.
-   Add `@example` JSDoc tags to many `Plugin` and `EncodedPluginData` fields.

# v1.1.0

## Additions

-   Added the `make-export-world-button-visible` built-in plugin ID.

## Removals

-   Removed the unused `scripts` field from the `package.json`.

# v1.0.2

## Changes

-   Minor documentation changes.

## Fixes

-   Fixed a bug where in some environments, such as Electron, importing the package without making it a type only import (even if everything being imported was prefixed with `type`) would cause an error.

# v1.0.1

## Changes

-   Minor documentation changes.

## Fixes

-   Fixed a bug where many types in the `zip` namespace had `CompatibleUint8Array` in their names instead of just `Uint8Array`.

# v1.0.0

-   Initial Release

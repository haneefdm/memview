# Change Log

Please note that we are still in Preview mode. For those using the API, this can change in the near future as we refine our proposals

## [Unreleased]

-   Editing
-   Apply settings to workspace/user/all-views beyond the current view

## 0.0.9 - Sep 3, 2022

-   Initial release of most of the view settings. Applying settings more globally is not yet implemented -- until we finalize a per view set of settings.
-   Introducing 4-byte and 8-byte grouping. However, these groupings, you will not get the Decoded bytes. Instead however, you will see 32-bytes of data per row whereas you see 16-bytes per row in 1-byte mode
-   For 4-byte and 8-byte grouping, we also support little/big endian conversion
-   The top-left of a memory view now shows the start-address of the view. Note that this is different from the base-address which is always a multiple of 16. So, you start-address and base-address can be slightly different and base-address <= start-address. The start-address will always be on the first row though.

![vew-properties](./resources/vew-props.png)

## 0.0.8 - Aug 28, 2022

-   Initial release

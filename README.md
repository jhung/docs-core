# Documentation Core (docs-core)

This repository contains shared files, helpers, libraries, and components used by the `docs-template` project and derivative `docs-template` sites.

# Usage

`docs-core` is not used directly. `docs-core` will be fetched and deployed using `npm` by `docs-template` (and derivatives) as outlined in the `docs-template` instructions (source: https://github.com/fluid-project/docs-template).

# Getting Updates to Derivative sites

When updates are made `docs-core`, these changes should be adopted by derivative sites. To get the updates, run `npm install` from the derivative site.

# Zurb Foundation 5.5.2

The version of Foundation included with Docs-Core is a custom build. It includes:

* Grid, Block Grid
* Pagination, Side Nav, Icon Bar, Breadcrumbs, Sub Nav
* Buttons, Button Groups, Dropdown Buttons, Split Buttons
* Type, Keystrokes, Inline Lists, Labels
* Panels, Progress Bars, Tables, Visibility

All other components were not included in the build.

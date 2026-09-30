# AetherSwap push detail

Public static viewer for immutable market snapshots. Migrated from the EdgeOne viewer because its default domain restricts mainland access.

The viewer accepts the existing `?data=` and `?z=` links. It decodes data in the browser and does not connect to the local AetherSwap API. No account credentials, database or live snapshots are included.

CSS and JavaScript from the existing viewer are embedded in index.html for deployment without a build step. The original GPL-3.0 license is preserved.

Enable GitHub Pages from the main branch, root directory. Mainland network availability must be tested on the target phone.

# VexFlow (vendored)

- Version: 4.2.5
- File: `vexflow.min.js` (renamed from upstream `build/cjs/vexflow.js` — despite the `cjs` path this is a UMD bundle, safe to load via a plain `<script>` tag)
- Source: https://cdn.jsdelivr.net/npm/vexflow@4.2.5/build/cjs/vexflow.js
- Global exposed: `window.Vex` (namespace `Vex.Flow`)
- License: MIT (see https://github.com/0xfe/vexflow/blob/master/LICENSE)

To update: bump the version in the source URL above, re-download, and re-verify the file still starts with a UMD wrapper exposing `Vex` on `window`.

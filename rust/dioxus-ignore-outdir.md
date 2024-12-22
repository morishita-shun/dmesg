## Dioxus 0.6.0 ignores out_dir

ref:
- out_dir ignored when building for web #3328
  - [https://github.com/DioxusLabs/dioxus/issues/3328](https://github.com/DioxusLabs/dioxus/issues/3328)
- fix(cli): Updated logic to resolve out_dir paths relative to workspace #3393
  - [https://github.com/DioxusLabs/dioxus/pull/3393](https://github.com/DioxusLabs/dioxus/pull/3393)

After version 0.6.0, Dioxus doesn't use out_dir to output.
- output path: target/dx/PROJECT_NAME/release/web/public

### fix (Tauri)
Change `build.frontendDist` paratemer at `src-tauri/tauri.conf.json`
- "../dist" -> "../target/dx/PROJECT_NAME/release/web/public"

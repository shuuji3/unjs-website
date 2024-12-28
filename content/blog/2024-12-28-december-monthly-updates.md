---
title: Monthly updates (December 2024)
description: 28 releases this month! What's new in the UnJS ecosystem?
authors:
  - name:
    picture:
    twitter:
category:
  - releases
packages:
  - consola
  - jiti
  - knitwork
  - mkdist
  - pkg-types
  - srvx
  - unbuild
  - unctx
  - unhead
  - unifont
  - unplugin
  - unstorage
  - untyped
publishedAt: 2024-12-28T01:13:46.085Z
modifiedAt: 2024-12-28T01:13:46.085Z
---

## consola

This month, we release 4 new releases (0 major release, 1 minor release and 3 patch releases):

- [v3.3.3](https://github.com/unjs/consola/releases/tag/v3.3.3)
- [v3.3.2](https://github.com/unjs/consola/releases/tag/v3.3.2)
- [v3.3.1](https://github.com/unjs/consola/releases/tag/v3.3.1)
- [v3.3.0](https://github.com/unjs/consola/releases/tag/v3.3.0)

### fixes

- **fancy:** Fallback when`Intl` is unavailable ([#326](https://github.com/unjs/consola/pull/326))

### enhancements

- **utils:** `formatTree` utility ([#223](https://github.com/unjs/consola/pull/223))
- **formatTree:** Support max depth ([#267](https://github.com/unjs/consola/pull/267))
<img width="202" alt="image" src="https://github.com/user-attachments/assets/675cd06c-e26a-4cab-80ca-6e38e3b49bf5" />
- Print error `cause` ([#308](https://github.com/unjs/consola/pull/308))
<img width="774" alt="image" src="https://github.com/user-attachments/assets/1c95d422-4c9c-41a4-8aa3-973833aea2fd" />
- Export prompt option types ([#301](https://github.com/unjs/consola/pull/301))
- **prompt:** Configurable `cancel` strategy ([#325](https://github.com/unjs/consola/pull/325))
### fixes
- Use `initial` in `select` and `multiselect` prompts ([#232](https://github.com/unjs/consola/pull/232))
- Make box title color same as border ([#236](https://github.com/unjs/consola/pull/236))

### documentation

- Update screenshot ([205d9c8](https://github.com/unjs/consola/commit/205d9c8))
- Add vitest mocking note ([#182](https://github.com/unjs/consola/pull/182))
- Add note about raw method ([#271](https://github.com/unjs/consola/pull/271))
- Add jsdocs for utils functions ([#286](https://github.com/unjs/consola/pull/286))
- Add jsdocs for top-level functions ([#288](https://github.com/unjs/consola/pull/288))

### types

- Fix prompt with `select` type return value type ([#238](https://github.com/unjs/consola/pull/238))

## jiti

This month, we release 2 new releases (0 major release, 0 minor release and 2 patch releases):

- [v2.4.2](https://github.com/unjs/jiti/releases/tag/v2.4.2)
- [v1.21.7](https://github.com/unjs/jiti/releases/tag/v1.21.7)

### fixes

- **cache:** Add `+map` suffix to fs entries when `sourceMaps` enabled ([#352](https://github.com/unjs/jiti/pull/352))
- Use native require cache of loaded entries only for Node.js 22.12.+ compatibility ([#348](https://github.com/unjs/jiti/pull/348))

## knitwork

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v1.2.0](https://github.com/unjs/knitwork/releases/tag/v1.2.0)

### enhancements

- Expose `genObjectKey` and `wrapInDelimiters` utils ([227ec06](https://github.com/unjs/knitwork/commit/227ec06))

### documentation

- Correct jsdocs for `genObjectFromRaw` ([#97](https://github.com/unjs/knitwork/pull/97))

## mkdist

This month, we release 3 new releases (1 major release, 1 minor release and 1 patch release):

- [v2.1.0](https://github.com/unjs/mkdist/releases/tag/v2.1.0)
- [v2.0.1](https://github.com/unjs/mkdist/releases/tag/v2.0.1)
- [v2.0.0](https://github.com/unjs/mkdist/releases/tag/v2.0.0)

### enhancements

- Support `globOptions` ([#266](https://github.com/unjs/mkdist/pull/266))

### fixes

- Convert absolute gitignore patterns to relative ([#265](https://github.com/unjs/mkdist/pull/265))

### ⚠️ breaking changes

- **vue:** ⚠️  Refactor vue loader with vue/compiler-sfc ([#251](https://github.com/unjs/mkdist/pull/251))

## pkg-types

This month, we release 1 new release (0 major release, 1 minor release and 0 patch release):

- [v1.3.0](https://github.com/unjs/pkg-types/releases/tag/v1.3.0)

### enhancements

- **types:** Add `packageManager` field to `PackageJson` ([#204](https://github.com/unjs/pkg-types/pull/204))

## srvx

This month, we release 2 new releases (0 major release, 0 minor release and 2 patch releases):

- [v0.1.3](https://github.com/unjs/srvx/releases/tag/v0.1.3)
- [v0.1.2](https://github.com/unjs/srvx/releases/tag/v0.1.2)

### fixes

- **node:** Compute `hasBody` when accessing `req.body` ([a002185](https://github.com/unjs/srvx/commit/a002185))
- **node:** Body utils should respect buffer view offset ([5e4ec69](https://github.com/unjs/srvx/commit/5e4ec69))

### refactors

- **node:** Expose `request._url` ([8eb8f5d](https://github.com/unjs/srvx/commit/8eb8f5d))

### documentation

- Minor tweaks ([#9](https://github.com/unjs/srvx/pull/9))

### enhancements

- **node:** Add `NodeFastResponse.bytes()` ([#16](https://github.com/unjs/srvx/pull/16))
- **node:** Add `NodeRequestProxy.bytes()` ([07863f6](https://github.com/unjs/srvx/commit/07863f6))
### documentation
- Minor tweaks ([#9](https://github.com/unjs/srvx/pull/9))

## unbuild

This month, we release 3 new releases (1 major release, 1 minor release and 1 patch release):

- [v3.1.0](https://github.com/unjs/unbuild/releases/tag/v3.1.0)
- [v3.0.1](https://github.com/unjs/unbuild/releases/tag/v3.0.1)
- [v3.0.0](https://github.com/unjs/unbuild/releases/tag/v3.0.0)

### enhancements

- Support parallel builds ([af19b1b](https://github.com/unjs/unbuild/commit/af19b1b))
- Infer externals from package `name`, `exports`, and `imports` fields ([#469](https://github.com/unjs/unbuild/pull/469))
- **rollup:** Resolve with `"production"` condition by default ([#470](https://github.com/unjs/unbuild/pull/470), [#471](https://github.com/unjs/unbuild/pull/471))

### fixes

- Resolve presets with default export ([#465](https://github.com/unjs/unbuild/pull/465))

### what is coming next?

In parallel with maintaining stable releases of unbuild, We are experimenting with a new, faster, and more modern approach based on [OXC](https://oxc.rs/), [rolldown](https://rolldown.rs/), and native runtime ESM/TypeScript made possible with recent Node.js versions!

### changelog



### ⚠️ breaking changes

- Upgrade to rollup v4 ([#327](https://github.com/unjs/unbuild/pull/327))
- Default rollup build target to `esnext` ([#335](https://github.com/unjs/unbuild/pull/335))
- Upgrade to mkdist [v2.0.0](https://github.com/unjs/mkdist/releases/tag/v2.0.0)
### enhancements
- Upgrade to rollup v4 ([#327](https://github.com/unjs/unbuild/pull/327))
- Support disabling `preserveDynamicImports` ([#322](https://github.com/unjs/unbuild/pull/322))
- **rollup:** Default to `esnext` build target ([#335](https://github.com/unjs/unbuild/pull/335))
- Support `copy` builder ([#389](https://github.com/unjs/unbuild/pull/389))
- Experimental active watcher for rollup ([#364](https://github.com/unjs/unbuild/pull/364))
- **rollup:** Add `.mts` and `.cts` to supported extensions ([633ffe9](https://github.com/unjs/unbuild/commit/633ffe9))
- Support custom jiti plugins for stub mode ([#368](https://github.com/unjs/unbuild/pull/368))
- Upgrade to jiti v2 ([#409](https://github.com/unjs/unbuild/pull/409))
- Add `--config` to the CLI ([#440](https://github.com/unjs/unbuild/pull/440))
### fixes
- Don't clean root directory if set as `outDir` ([#343](https://github.com/unjs/unbuild/pull/343))
- Generate stub types of with explicit extension import if pkg type is module ([#371](https://github.com/unjs/unbuild/pull/371))
- Correct dts generation for stub mode ([#314](https://github.com/unjs/unbuild/pull/314))
- **rollup:** Handle aliases when checking for externals ([#384](https://github.com/unjs/unbuild/pull/384))
- **rollup:** Update `importAttributesKey` to `with` ([27bcba8](https://github.com/unjs/unbuild/commit/27bcba8))
- Type `RollupOptions.plugins` as array ([62fa930](https://github.com/unjs/unbuild/commit/62fa930))
- Add all loader extensions to esbuild include ([8ab22ff](https://github.com/unjs/unbuild/commit/8ab22ff))
- Enable jiti `interopDefault` for config loader and internals (ref: #409) ([#409](https://github.com/unjs/unbuild/issues/409))
- **rollup:** Keep empty (type-only) modules ([a9158e2](https://github.com/unjs/unbuild/commit/a9158e2))
- **rollup:** Keep empty type-only modules ([7a6469b](https://github.com/unjs/unbuild/commit/7a6469b))
- **untyped:** Use custom jiti instance ([00ded57](https://github.com/unjs/unbuild/commit/00ded57))
- Normalize resolved path ([2640083](https://github.com/unjs/unbuild/commit/2640083))
- **stub:** Enable `interopDefault` by default ([8e6f7e4](https://github.com/unjs/unbuild/commit/8e6f7e4))
- **config:** Only take default export ([fefafec](https://github.com/unjs/unbuild/commit/fefafec))
- Update to jiti 2.3 ([9147c3e](https://github.com/unjs/unbuild/commit/9147c3e))
- Untyped declaration output is optional ([5820182](https://github.com/unjs/unbuild/commit/5820182))
- **untyped:** Use schema module default export if is the only export ([cc26726](https://github.com/unjs/unbuild/commit/cc26726))

### refactors

- Use `jiti.import` for esm stubs and improve templates ([#300](https://github.com/unjs/unbuild/pull/300))
- Overhaul builders structure ([#410](https://github.com/unjs/unbuild/pull/410))
- Add explicit return types ([#412](https://github.com/unjs/unbuild/pull/412))
- Use colors from `consola/utils` ([6a8f36d](https://github.com/unjs/unbuild/commit/6a8f36d))
- Replace `globby` w/ `fast-glob` ([#418](https://github.com/unjs/unbuild/pull/418))
- Replace `fast`-glob with `tinyglobby` ([#426](https://github.com/unjs/unbuild/pull/426))

### documentation

- Update jsdocs for `inferEntries` ([#310](https://github.com/unjs/unbuild/pull/310))
- Add more jsdocs ([#363](https://github.com/unjs/unbuild/pull/363))
- Add examples ([#334](https://github.com/unjs/unbuild/pull/334))
- Fix typo ([#414](https://github.com/unjs/unbuild/pull/414))
- Add more usage info ([#401](https://github.com/unjs/unbuild/pull/401))

## unctx

This month, we release 2 new releases (0 major release, 1 minor release and 1 patch release):

- [v2.4.1](https://github.com/unjs/unctx/releases/tag/v2.4.1)
- [v2.4.0](https://github.com/unjs/unctx/releases/tag/v2.4.0)

### fixes

- Prefer asyncContext instance over currentInstance ([#101](https://github.com/unjs/unctx/pull/101))

### enhancements

- Update unplugin to v2 ([64574e6](https://github.com/unjs/unctx/commit/64574e6))
### fixes
- **transform:** Don't terminate single if statements ([#97](https://github.com/unjs/unctx/pull/97))

### refactors

- Strict typechecks ([4a5a4d1](https://github.com/unjs/unctx/commit/4a5a4d1))
- Fix plugin name ([#89](https://github.com/unjs/unctx/pull/89))

### documentation

- Add note about adding `callAsync` to `asyncFunctions` ([#94](https://github.com/unjs/unctx/pull/94))

## unhead

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v1.11.14](https://github.com/unjs/unhead/releases/tag/v1.11.14)

### bug fixes

- **useScript**: Allow `load()` to be called again once `remove()` is called - by @harlan-zw [<samp>(6a9b4)</samp>](https://github.com/unjs/unhead/commit/6a9b4e18)

## unifont

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v0.1.7](https://github.com/unjs/unifont/releases/tag/v0.1.7)

### bug fixes

- Preserve original URL for retry attempts - by @daopk in https://github.com/unjs/unifont/issues/79 [<samp>(b97df)</samp>](https://github.com/unjs/unifont/commit/b97df8e)

## unplugin

This month, we release 2 new releases (1 major release, 1 minor release and 0 patch release):

- [v2.1.0](https://github.com/unjs/unplugin/releases/tag/v2.1.0)
- [v2.0.0](https://github.com/unjs/unplugin/releases/tag/v2.0.0)

### breaking changes

- Drop node 16 & webpack 4 support - by @sxzz [<samp>(72abb)</samp>](https://github.com/unjs/unplugin/commit/72abb5f)
- Drop webpack 4 - by @sxzz in https://github.com/unjs/unplugin/issues/440 [<samp>(19c95)</samp>](https://github.com/unjs/unplugin/commit/19c95b1)
- Drop `meta.build` for esbuild - by @sxzz [<samp>(c9806)</samp>](https://github.com/unjs/unplugin/commit/c980632)

### features

- Support Vite 6 - by @sxzz [<samp>(d5d94)</samp>](https://github.com/unjs/unplugin/commit/d5d944b)

### bug fixes

- Type error - by @sxzz [<samp>(d7026)</samp>](https://github.com/unjs/unplugin/commit/d702641)
- Remove deprecated nodejs api - by @sxzz [<samp>(615b2)</samp>](https://github.com/unjs/unplugin/commit/615b209)
- **esbuild**: Compat esbuild before v0.14.3 - by @sxzz [<samp>(35c78)</samp>](https://github.com/unjs/unplugin/commit/35c78d2)
- **farm**: Serialized communication between js and rust - by @ErKeLost in https://github.com/unjs/unplugin/issues/442 [<samp>(c80f9)</samp>](https://github.com/unjs/unplugin/commit/c80f9ab)
- **rspack**: Plugin.__vfs is undefined - by @thinke5 in https://github.com/unjs/unplugin/issues/439 [<samp>(3c4b7)</samp>](https://github.com/unjs/unplugin/commit/3c4b79e)
- **webpack**: Lazy import webpack - by @sxzz [<samp>(c267c)</samp>](https://github.com/unjs/unplugin/commit/c267c44)

## unstorage

This month, we release 5 new releases (0 major release, 1 minor release and 4 patch releases):

- [v1.14.4](https://github.com/unjs/unstorage/releases/tag/v1.14.4)
- [v1.14.3](https://github.com/unjs/unstorage/releases/tag/v1.14.3)
- [v1.14.2](https://github.com/unjs/unstorage/releases/tag/v1.14.2)
- [v1.14.1](https://github.com/unjs/unstorage/releases/tag/v1.14.1)
- [v1.14.0](https://github.com/unjs/unstorage/releases/tag/v1.14.0)

### fixes

- **s3:** Use `/` as separator ([#545](https://github.com/unjs/unstorage/pull/545))

### documentation

- **cloudflare:** Fix example comments ([#534](https://github.com/unjs/unstorage/pull/534))

### 🌟 new drivers

- [Upstash Redis](https://unstorage.unjs.io/drivers/upstash) ([#500](https://github.com/unjs/unstorage/pull/500))
- [SQL Database (db0)](https://unstorage.unjs.io/drivers/database) ([#476](https://github.com/unjs/unstorage/pull/476))
- [Vercel Blob](https://unstorage.unjs.io/drivers/vercel) ([#472](https://github.com/unjs/unstorage/pull/472))
- [Deno KV](https://unstorage.unjs.io/drivers/deno) ([#521](https://github.com/unjs/unstorage/pull/521))
- [S3](https://unstorage.unjs.io/drivers/s3) ([#361](https://github.com/unjs/unstorage/pull/361))
- [UploadThing](https://unstorage.unjs.io/drivers/uploadthing) ([#390](https://github.com/unjs/unstorage/pull/390))

### enhancements

- **cloudflare-r2-binding:** Allow specify raw type ([#519](https://github.com/unjs/unstorage/pull/519))
- **indexedb:** Support raw storage ([#520](https://github.com/unjs/unstorage/pull/520))
- Typed storage Interface ([#509](https://github.com/unjs/unstorage/pull/509))
- Support raw conversion in runtimes without `Buffer` support ([#364](https://github.com/unjs/unstorage/pull/364))
### fixes
- **cloudflare-r2-binding:** Return `null` for non existing `getItem` ([fb8e00e](https://github.com/unjs/unstorage/commit/fb8e00e))
- **upstash:** Drop `base` prefix from `keyKeys` ([8711a94](https://github.com/unjs/unstorage/commit/8711a94))
- Capture stacktrace of thrown errors ([c704fef](https://github.com/unjs/unstorage/commit/c704fef))
- **http:** Return `arrayBuffer` for `getItemRaw` ([#527](https://github.com/unjs/unstorage/pull/527))
- **localstorage:** Use `base` for `clear` and `getKeys` ([#529](https://github.com/unjs/unstorage/pull/529))

### refactors

- More strict type checks ([c8ed5cf](https://github.com/unjs/unstorage/commit/c8ed5cf))
- **cloudflare-kv-http:** Use new bulk delete api for `clear()` ([0231775](https://github.com/unjs/unstorage/commit/0231775))
- Reuse `localstorage` logic for `session-storage` ([#530](https://github.com/unjs/unstorage/pull/530))
### documentation
- Add notes about nightly channel ([de31652](https://github.com/unjs/unstorage/commit/de31652))
- **netlify:** Add `consistency` option ([#525](https://github.com/unjs/unstorage/pull/525))
- **cloudflare:** Add note about r2 over http ([1f2d444](https://github.com/unjs/unstorage/commit/1f2d444))

## untyped

This month, we release 1 new release (0 major release, 0 minor release and 1 patch release):

- [v1.5.2](https://github.com/unjs/untyped/releases/tag/v1.5.2)

### fixes

- Escape keys in generated types ([#143](https://github.com/unjs/untyped/pull/143))

### refactors

- Implement cli with `citty` ([#150](https://github.com/unjs/untyped/pull/150))
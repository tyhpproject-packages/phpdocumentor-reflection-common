<!-- tyhp-readme:start -->
# tyhpdef/phpdocumentor-reflection-common

Tyhp type definitions for `phpdocumentor/reflection-common` `2.2.0`.

```bash
composer require --dev tyhpdef/phpdocumentor-reflection-common:2.2.0
```

This is a metapackage. Composer also installs `tyhpdef/phpdocumentor-reflection-common-impl` (type files).
Require **this** name, not `tyhpdef/phpdocumentor-reflection-common-impl`.

See https://tyhplang.com.

## Maintain `phpdocumentor/reflection-common`? Ship the types yourself

If you are a Packagist maintainer of `phpdocumentor/reflection-common`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/phpdocumentor-reflection-common-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `phpdocumentor/reflection-common` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/phpdocumentor-reflection-common": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `phpdocumentor/reflection-common` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `phpdocumentor/reflection-common` with a real constraint,
   `"replace": { "tyhpdef/phpdocumentor-reflection-common": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `phpdocumentor/reflection-common` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/phpdocumentor-reflection-common` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->

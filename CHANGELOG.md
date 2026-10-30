# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-10-30)

<section class="features">

### Features

-   [`ed8ea0c`](https://github.com/stdlib-js/stdlib/commit/ed8ea0c7808eec0735fa06e3f9929531e21e8f82) - add `fft/base/fftpack/float32/sinqi` [(#14808)](https://github.com/stdlib-js/stdlib/pull/14808)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`518731b`](https://github.com/stdlib-js/stdlib/commit/518731be8f6175e403a1dbf010b9dcea6d20b4df): use `Uint32Array` view

    -   To migrate, consumers should create a `Uint32Array` view of the factors section. This ensures we preserve accuracy for larger sequence lengths.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`518731b`](https://github.com/stdlib-js/stdlib/commit/518731be8f6175e403a1dbf010b9dcea6d20b4df) - **refactor:** update `fft/base/fftpack/float32/sinqi` to use integer array view [(#16361)](https://github.com/stdlib-js/stdlib/pull/16361) _(by Gunj Joshi, Athan Reines)_
-   [`ed8ea0c`](https://github.com/stdlib-js/stdlib/commit/ed8ea0c7808eec0735fa06e3f9929531e21e8f82) - **feat:** add `fft/base/fftpack/float32/sinqi` [(#14808)](https://github.com/stdlib-js/stdlib/pull/14808) _(by Gunj Joshi, Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gunj Joshi

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->


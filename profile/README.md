<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GeoThai/.github/main/profile/assets/geothai-horizontal-white.svg">
  <img alt="GeoThai" src="https://raw.githubusercontent.com/GeoThai/.github/main/profile/assets/geothai-horizontal-black.svg" height="64">
</picture>

Open data for every province, district, subdistrict and postal code of Thailand, checked against official sources.

Search it at [geothai.fasu.dev](https://geothai.fasu.dev).

## Features

- Official codes from the Department of Provincial Administration (DOPA), with Thai and English names
- Postal codes per subdistrict. A subdistrict that spans post office zones gets more than one code
- Seven sources check every value. Each disagreement gets a decision and its evidence
- Abolished areas keep their code and the date they ended
- One JSON line per area, so the data works in any language

## Status

| Part           | State                                                                                                                          |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Data pipeline  | Done, refreshes every week                                                                                                     |
| Public data    | Out: [GeoThai/data](https://github.com/GeoThai/data), first release `v2026.10.20`                                              |
| Website        | Live at [geothai.fasu.dev](https://geothai.fasu.dev): [GeoThai/website](https://github.com/GeoThai/website)                    |
| npm package    | Out: [`geothai`](https://www.npmjs.com/package/geothai) 4.0.0: [GeoThai/npm-packages](https://github.com/GeoThai/npm-packages) |
| Python package | Code done, release `3.0.0` next: [GeoThai/python-library](https://github.com/GeoThai/python-library)                           |

The old data, v1 to v4, stays on the [`archive`](https://github.com/GeoThai/data/tree/archive) branch of GeoThai/data and its `v1` to `v4` tags.

## Contact

[geothai@fasu.dev](mailto:geothai@fasu.dev)

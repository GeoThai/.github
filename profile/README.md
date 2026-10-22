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
- Abolished areas keep their code, the date they ended, and the codes that took their place
- One JSON line per area, so the data works in any language
- A private pipeline builds and checks the data. The steps and the evidence are in [GeoThai/data](https://github.com/GeoThai/data#how-it-is-built)

## Status

| Part           | State                                                                                                                        |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Data pipeline  | Done, refreshes every week                                                                                                   |
| Public data    | Out: [GeoThai/data](https://github.com/GeoThai/data), a dated release each time the data changes                             |
| Website        | Live at [geothai.fasu.dev](https://geothai.fasu.dev): [GeoThai/website](https://github.com/GeoThai/website)                  |
| npm package    | Out: [`geothai`](https://www.npmjs.com/package/geothai) 4.x: [GeoThai/npm-packages](https://github.com/GeoThai/npm-packages) |
| Python package | Out: [`geothai`](https://pypi.org/project/geothai/) 3.x: [GeoThai/python-library](https://github.com/GeoThai/python-library) |

The old data, v1 to v4, stays on the [`archive`](https://github.com/GeoThai/data/tree/archive) branch of GeoThai/data and its `v1` to `v4` tags.

## Contact

[geothai@fasu.dev](mailto:geothai@fasu.dev)

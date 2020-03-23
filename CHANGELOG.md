This changelog is for the fork.
See [`CHANGELOG-UPSTREAM.md`](CHANGELOG-UPSTREAM.md) of the changelog related to the [original mume library](https://github.com/shd101wyy/mume/).

## 0.23.0

- Upgrade vega-lite to 4.8.1 and vega-embed to 6.5.1

## 0.22.0

- Upgrade vega to 5.10.0, vega-lite to 4.5.1, vega-embed to 6.3.2 and apache-arrow to 0.16.0

## 0.21.0

- Upgrade vega-lite to 4.3.1

## 0.20.0

- Upgrade vega to 5.9.1, vega-lite to 4.1.1 and vega-embed to 6.2.2

## 0.19.0

- Upgrade vega-lite to 4.0.0-beta.11, fix outdated vega versions in CDN links (affects interactive mode only)

## 0.18.0

- Update apache-arrow to 0.15.0, vega to 5.7.3, vega-lite to 4.0.0-beta.10 and vega-embed to 6.0.0
- Merge from upstream (0.4.7)

## 0.17.0

- Upgrade vega to 5.7.0, vega-lite to 4.0.0-beta.8, vega-embed to 5.1.3 and vega-loader-arrow to 0.14.1

## 0.16.0

- Sync with upstream package to resolve various issues in the latest versions of editors (https://github.com/gicentre/mume-with-litvis/pull/1)

## 0.15.0

- Upgrade vega to 5.4.0 and vega-embed to 4.2.0
- Support apache-arrow files in vega specs (https://github.com/gicentre/litvis/issues/31)
- Fix incorrect parsing of keys in elm string representation (https://github.com/gicentre/litvis/issues/29#issuecomment-496008915)

## 0.14.4

- Upgrade vega to 5.3.5 and vega-lite to 3.2.1
- \[elm-string-representation] Allow any strings in keys except `" = "`

## 0.14.3

- Upgrade vega to 5.3.2, vega-lite to 3.0.2 and vega-embed to 4.0.0
- Use JSDelivr as lib CDN instead of CloudFlare

## 0.14.2

- Downgrade vega from 5.3.0 to 5.1.0 to avoid `Error: Cycle detected in dataflow graph`

## 0.14.1

- Fix a number of regressions in Elm output parsing and URL fetching
- Improve error handling in a couple of edge cases
- Upgrade vega to 5.3.0

## 0.14.0

- Upgrade vega to 5.0.0, vega-lite to 3.0.0-rc14 and vega-embed to 4.0.0-rc1s

## 0.13.0

- Add ability to highlight lines of code ([gicentre/litvis#9](https://github.com/gicentre/litvis/issues/9), [shd101wyy/mume#100](https://github.com/shd101wyy/mume/pull/100), [5074ca39](https://github.com/gicentre/mume-with-litvis/commit/5074ca39a24ff86ef8ddc63c35f33b212e2da984))

## 0.12.0

- Upgrade litvis-integration-mume (fix a few bugs)
- Upgrade vega to 4.4.0, vega-lite to 3.0.0-rc10 and vega-embed to 3.26.1

## 0.11.0

- Implement markdown output from litvis blocks ([gicentre/litvis#10](https://github.com/gicentre/litvis/pull/10))

## 0.6.0

- Improve parsing of narrative schemas, support label aliases and fix rules.

## 0.5.0

- Upgrade `vega` to `3.3.1`, `vega-lite` to `2.4.0` and `vega-embed` to `3.7.2` ([shd101wyy/mume#65](https://github.com/shd101wyy/mume/pull/65)).

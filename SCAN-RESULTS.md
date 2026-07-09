# Scan Results

Repository: `verademo-javascript-api`

Source data:
- `osv-scanner-baseline.json`
- `npm audit --package-lock-only --json`

Current status after remediation:
- `npm audit --package-lock-only --json`: `0` vulnerabilities
- `osv-scanner scan -r .`: `No issues found`

The inventory below documents the original vulnerable baseline that was present on `participant-start`.

## Summary

- `90` total findings in the baseline scan
- `85` unique package-version/advisory entries
- Severity split:
  - `30` Critical
  - `25` High
  - `25` Moderate
  - `10` Low

Workshop scoring matters most for `Critical` and `High`, but the inventory below includes the full set present in the repository baseline.

## Direct Vulnerable Dependencies

These are the vulnerable direct dependencies currently declared in `package.json`:

| Package | Declared version | Severity seen in audit |
|---|---|---|
| `curling` | `^0.3.0` | `high` |
| `djv` | `^2.1.2` | `critical` |
| `express` | `^4.17.3` | `high` |
| `lodash` | `^4.17.15` | `high` |
| `morgan` | `^1.10.0` | `low` |
| `swagger-jsdoc` | `5.0.1` | `moderate` |
| `url-parse` | `^1.5.3` | `critical` |
| `vm2` | `^3.9.5` | `critical` |

## Critical
| Package | Version | Advisory | CVE |
|---|---|---|---|
| `djv` | `2.1.2` | `GHSA-4hv7-3q38-97m8` | `CVE-2020-28464` |
| `handlebars` | `4.7.7` | `GHSA-2w6w-674q-4c4q` | `CVE-2026-33937` |
| `minimist` | `1.2.5` | `GHSA-xvch-5gv4-984h` | `CVE-2021-44906` |
| `url-parse` | `1.5.3` | `GHSA-hgjh-723h-mx2j` | `CVE-2022-0686` |
| `vm2` | `3.9.5` | `GHSA-248r-7h7q-cr24` | `CVE-2026-45411` |
| `vm2` | `3.9.5` | `GHSA-47x8-96vw-5wg6` | `CVE-2026-43997` |
| `vm2` | `3.9.5` | `GHSA-4w2j-2rg4-5mjw` | `CVE-2022-25893` |
| `vm2` | `3.9.5` | `GHSA-55hx-c926-fr95` | `CVE-2026-26332` |
| `vm2` | `3.9.5` | `GHSA-6j2x-vhqr-qr7q` | `CVE-2026-47210` |
| `vm2` | `3.9.5` | `GHSA-6pw2-5hjv-9pf7` | `CVE-2021-23555` |
| `vm2` | `3.9.5` | `GHSA-76w7-j9cq-rx2j` | `CVE-2026-47208` |
| `vm2` | `3.9.5` | `GHSA-7jxr-cg7f-gpgv` | `CVE-2023-29017` |
| `vm2` | `3.9.5` | `GHSA-8hg8-63c5-gwmx` | `CVE-2026-44007` |
| `vm2` | `3.9.5` | `GHSA-99p7-6v5w-7xg8` | `CVE-2026-22709` |
| `vm2` | `3.9.5` | `GHSA-9qj6-qjgg-37qq` | `CVE-2026-44008` |
| `vm2` | `3.9.5` | `GHSA-9vg3-4rfj-wgcm` | `CVE-2026-44009` |
| `vm2` | `3.9.5` | `GHSA-cchq-frgv-rjh5` | `CVE-2023-37466` |
| `vm2` | `3.9.5` | `GHSA-ch3r-j5x3-6q2m` | `CVE-2023-30547` |
| `vm2` | `3.9.5` | `GHSA-ffh4-j6h5-pg66` | `CVE-2026-26956` |
| `vm2` | `3.9.5` | `GHSA-g644-9gfx-q4q4` | `CVE-2023-37903` |
| `vm2` | `3.9.5` | `GHSA-grj5-jjm8-h35p` | `CVE-2026-24118` |
| `vm2` | `3.9.5` | `GHSA-m4wx-m65x-ghrr` | `CVE-2026-47137` |
| `vm2` | `3.9.5` | `GHSA-mrgp-mrhc-5jrq` | `CVE-2022-36067` |
| `vm2` | `3.9.5` | `GHSA-qcp4-v2jj-fjx8` | `CVE-2026-44006` |
| `vm2` | `3.9.5` | `GHSA-qvjj-29qf-hp7p` | `CVE-2026-24120` |
| `vm2` | `3.9.5` | `GHSA-rp36-8xq3-r6c4` | `CVE-2026-47140` |
| `vm2` | `3.9.5` | `GHSA-v37h-5mfm-c47c` | `CVE-2026-24781` |
| `vm2` | `3.9.5` | `GHSA-v6mx-mf47-r5wg` | `CVE-2026-47131` |
| `vm2` | `3.9.5` | `GHSA-whpj-8f3w-67p5` | `CVE-2023-32314` |
| `vm2` | `3.9.5` | `GHSA-xj72-wvfv-8985` | `CVE-2023-29199` |

## High
| Package | Version | Advisory | CVE |
|---|---|---|---|
| `ansi-regex` | `4.1.0` | `GHSA-93q8-gq69-wqmw` | `CVE-2021-3807` |
| `body-parser` | `1.19.2` | `GHSA-qwcr-r2fm-qrc7` | `CVE-2024-45590` |
| `braces` | `3.0.2` | `GHSA-grv7-fg5c-xmjg` | `CVE-2024-4068` |
| `curling` | `0.3.0` | `GHSA-xmxh-g7wj-8m4m` | `CVE-2019-10789` |
| `handlebars` | `4.7.7` | `GHSA-3mfm-83xf-c92r` | `CVE-2026-33938` |
| `handlebars` | `4.7.7` | `GHSA-9cx6-37pm-9jff` | `CVE-2026-33939` |
| `handlebars` | `4.7.7` | `GHSA-xhpv-hc6g-r9c6` | `CVE-2026-33940` |
| `handlebars` | `4.7.7` | `GHSA-xjpj-3mr7-gcpf` | `CVE-2026-33941` |
| `lodash` | `4.17.15` | `GHSA-35jh-r3h4-6jhm` | `CVE-2021-23337` |
| `lodash` | `4.17.15` | `GHSA-p6mc-m468-83gw` | `CVE-2020-8203` |
| `lodash` | `4.17.15` | `GHSA-r5fr-rjxr-66jc` | `CVE-2026-4800` |
| `lodash` | `4.17.21` | `GHSA-r5fr-rjxr-66jc` | `CVE-2026-4800` |
| `minimatch` | `3.1.2` | `GHSA-23c5-xmqv-rm74` | `CVE-2026-27904` |
| `minimatch` | `3.1.2` | `GHSA-3ppc-4f35-3m26` | `CVE-2026-26996` |
| `minimatch` | `3.1.2` | `GHSA-7r86-cg39-jmmj` | `CVE-2026-27903` |
| `path-to-regexp` | `0.1.7` | `GHSA-37ch-88jc-xwx2` | `CVE-2026-4867` |
| `path-to-regexp` | `0.1.7` | `GHSA-9wv6-86v2-598j` | `CVE-2024-45296` |
| `path-to-regexp` | `0.1.7` | `GHSA-rhx6-c78j-4q9w` | `CVE-2024-52798` |
| `picomatch` | `2.3.1` | `GHSA-c2c7-rcm5-vvqj` | `CVE-2026-33671` |
| `validator` | `13.7.0` | `GHSA-vghf-hv5q-vc2g` | `CVE-2025-12758` |
| `vm2` | `3.9.5` | `GHSA-6785-pvv7-mvg7` | `CVE-2026-44004` |
| `vm2` | `3.9.5` | `GHSA-c4cf-2hgv-2qv6` | `CVE-2026-47209` |
| `vm2` | `3.9.5` | `GHSA-hw58-p9xv-2mjh` | `CVE-2026-44001` |
| `vm2` | `3.9.5` | `GHSA-m5q2-4fm3-vfqp` | `CVE-2026-47135` |
| `vm2` | `3.9.5` | `GHSA-r9pm-gxmw-wv6p` | `CVE-2026-47139` |

## Moderate
| Package | Version | Advisory | CVE |
|---|---|---|---|
| `brace-expansion` | `1.1.11` | `GHSA-f886-m6hf-6m8v` | `CVE-2026-33750` |
| `express` | `4.17.3` | `GHSA-rv95-896h-c2vc` | `CVE-2024-29041` |
| `handlebars` | `4.7.7` | `GHSA-2qvq-rjwj-gvw9` | `CVE-2026-33916` |
| `handlebars` | `4.7.7` | `GHSA-7rx3-28cr-v5wh` | `-` |
| `js-yaml` | `3.14.0` | `GHSA-h67p-54hq-rp68` | `CVE-2026-53550` |
| `js-yaml` | `4.1.0` | `GHSA-h67p-54hq-rp68` | `CVE-2026-53550` |
| `js-yaml` | `3.14.0` | `GHSA-mh29-5h37-fv8m` | `CVE-2025-64718` |
| `js-yaml` | `4.1.0` | `GHSA-mh29-5h37-fv8m` | `CVE-2025-64718` |
| `lodash` | `4.17.15` | `GHSA-29mw-wpgm-hmr9` | `CVE-2020-28500` |
| `lodash` | `4.17.15` | `GHSA-f23m-r3pf-42rh` | `CVE-2026-2950` |
| `lodash` | `4.17.21` | `GHSA-f23m-r3pf-42rh` | `CVE-2026-2950` |
| `lodash` | `4.17.15` | `GHSA-xxjr-mmjv-4gpg` | `CVE-2025-13465` |
| `lodash` | `4.17.21` | `GHSA-xxjr-mmjv-4gpg` | `CVE-2025-13465` |
| `picomatch` | `2.3.1` | `GHSA-3v7f-55p6-f55p` | `CVE-2026-33672` |
| `qs` | `6.9.7` | `GHSA-6rw7-vpxm-498p` | `CVE-2025-15284` |
| `url-parse` | `1.5.3` | `GHSA-8v38-pw62-9cw2` | `CVE-2022-0639` |
| `url-parse` | `1.5.3` | `GHSA-jf5r-8hm2-f872` | `CVE-2022-0691` |
| `url-parse` | `1.5.3` | `GHSA-rqff-837h-mm52` | `CVE-2022-0512` |
| `validator` | `13.7.0` | `GHSA-9965-vmph-33xx` | `CVE-2025-56200` |
| `vm2` | `3.9.5` | `GHSA-2cm2-m3w5-gp2f` | `-` |
| `vm2` | `3.9.5` | `GHSA-9g8x-92q2-p28f` | `CVE-2026-47141` |
| `vm2` | `3.9.5` | `GHSA-mpf8-4hx2-7cjg` | `CVE-2026-44000` |
| `vm2` | `3.9.5` | `GHSA-p5gc-c584-jj6v` | `CVE-2023-32313` |
| `vm2` | `3.9.5` | `GHSA-v27g-jcqj-v8rw` | `CVE-2026-44002` |
| `vm2` | `3.9.5` | `GHSA-wp5r-2gw5-m7q7` | `CVE-2026-44003` |

## Low
| Package | Version | Advisory | CVE |
|---|---|---|---|
| `brace-expansion` | `1.1.11` | `GHSA-v6h2-p8h4-qcjw` | `CVE-2025-5889` |
| `cookie` | `0.4.2` | `GHSA-pxg6-pf52-xh8x` | `CVE-2024-47764` |
| `diff` | `4.0.2` | `GHSA-73rr-hh4g-fpgx` | `CVE-2026-24001` |
| `express` | `4.17.3` | `GHSA-qw6h-vgh9-j6wx` | `CVE-2024-43796` |
| `handlebars` | `4.7.7` | `GHSA-442j-39wm-28r2` | `-` |
| `on-headers` | `1.0.2` | `GHSA-76c9-3jph-rj3q` | `CVE-2025-7339` |
| `qs` | `6.9.7` | `GHSA-w7fw-mjwx-w883` | `CVE-2026-2391` |
| `send` | `0.17.2` | `GHSA-m6fv-jmcg-4jfg` | `CVE-2024-43799` |
| `serve-static` | `1.14.2` | `GHSA-cm22-4g7w-348p` | `CVE-2024-43800` |
| `vm2` | `3.9.5` | `GHSA-q3fm-4wcw-g57x` | `-` |

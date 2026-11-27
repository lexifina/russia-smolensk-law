<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Smolensk Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:54 UTC, Smolensk Oblast: Official Internet Portal of Legal Information (region67): 15 addresses read; 16 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Smolensk Oblast: Official Internet Portal of Legal Information (region67)](http://publication.pravo.gov.ru/documents/block/region67) | `zakony-<year>/` | daily | 2026-11-27 05:54 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:53](checks/2026-11.md#ru-pravo-smolensk-20261127t055316z) | pravo-smolensk | 15 | 16 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-smolensk-law/compare/65e8ea241d6e...db88d2841b6e) |
| [2026-11-26 05:59](checks/2026-11.md#ru-pravo-smolensk-20261126t055926z) | pravo-smolensk | 15 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:34](checks/2026-11.md#ru-pravo-smolensk-20261125t063452z) | pravo-smolensk | 15 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:50](checks/2026-11.md#ru-pravo-smolensk-20261124t145017z) | pravo-smolensk | 15 | 0 | 0 | 0 | 0 (0) | no change | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.

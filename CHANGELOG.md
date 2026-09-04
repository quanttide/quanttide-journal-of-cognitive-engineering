# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.3.0] - 2026-09-04

### Added

- Daily markdown logs per world (2026-08-19 ~ 2026-09-01, 46 entries across 24 worlds)
- 18 new worlds: `quanttide-{agent,asset,code,connect,course,crowd,docs,group,growth,human,knowl,learn,market,media,pay,relation,support,tech}`
- New entries in existing worlds: `quanttide-{business,meta,org,product,strategy,think}`

## [0.2.0] - 2026-08-19

### Added

- World-based directory structure: `default/` + `quanttide-{business,data,meta,org,product,sale,strategy,think,write}`
- Daily markdown logs per world (2026-08-14 ~ 2026-08-19, 44 entries)
- Raw thought records in daily logs, replacing the weekly YAML format

### Fixed

- Correct term: 文导小组 → 无领导小组 (leaderless group discussion)

## [0.1.0] - 2026-06-10

### Added

- 5 weeks of journal data (2026-W19 ~ 2026-W23) migrated from gallery
- Per-week directory structure: `{world}/{week}/{domain}.yaml`
- Each domain file contains: schemas, situations, intentions, relations, thoughts
- World metadata: `quanttide` (parent), `quanttide-founder`, `quanttide-tech`
- Domain metadata with `parent` field for hierarchy
- Raw thought records in `thoughts/` directory per week

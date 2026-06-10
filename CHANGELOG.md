# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.1.0] - 2026-06-10

### Added

- 5 weeks of journal data (2026-W19 ~ 2026-W23) migrated from gallery
- Per-week directory structure: `{world}/{week}/{domain}.yaml`
- Each domain file contains: schemas, situations, intentions, relations, thoughts
- World metadata: `quanttide` (parent), `quanttide-founder`, `quanttide-tech`
- Domain metadata with `parent` field for hierarchy
- Raw thought records in `thoughts/` directory per week

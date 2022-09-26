# Changelog - Pro Rec ingres
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2022-09-26
### Download
[pro-rec-ingres-v0.1.0.zip](https://github.com/pauloup/pro-rec-ingres/releases/download/v0.1.0/pro-rec-ingres-v0.1.0.zip)

### Overview
Audio bitrate increased from 96 kbps to 576 kbps for video recording.

### Added
- New default and max bitrate values for `aac` and `heaac`:

  ```
  -----------------------------------------
  codec          1ch      2ch       6ch
  
  aac (max)      96->288  192->576  96->768
  aac (default)  96->288  156->576  -
  heaac (max)    64->128  -         -
  -----------------------------------------
  ```

- New max channels value `1->2` for `aaceld`.

## Note
CHANGELOG standard: https://keepachangelog.com/en/1.0.0/

**Sections**: Added, Changed, Deprecated, Removed, Fixed




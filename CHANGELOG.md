# Changelog - Pro Rec ingres

## [Unreleased]

## [0.1.0] - 2022-09-26
### Initial release
Audio bitrate increased from 96 kbps to 576 kbps for video recording.

### Added
- New default and max bitrate for `aac` and `heaac`:

  ```
  -----------------------------------------
  codec          1ch      2ch       6ch
  
  aac (max)      96->288  192->576  96->768
  aac (default)  96->288  156->576  -
  heaac (max)    64->128  -         -
  -----------------------------------------
  ```

- New max channels `1->2` for `aaceld`.

## Note
CHANGELOG standard: https://keepachangelog.com/en/1.0.0/

**Sections**: Added, Changed, Deprecated, Removed, Fixed




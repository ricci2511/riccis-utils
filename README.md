# riccis-utils

A collection of utilities, tools, and scripts tailored for my homelab enthusiasts. Each tool serves a unique purpose, ranging from file organization to media processing.

## Utilities Overview

### [audio_transcode](https://github.com/ricci2511/audio_transcode)
A versatile shell script designed to:
- Transcode audio in video files to the AC3 format with customizable settings.
- Convert SSA/ASS subtitles to SRT format for broader compatibility.
- Seamlessly integrate with:
  - [Sonarr](https://github.com/Sonarr/Sonarr) and [Radarr](https://github.com/Radarr/Radarr) event hooks.
  - [sabnzbd](https://github.com/sabnzbd/sabnzbd) post-processing scripts.

### [filecollate](https://github.com/ricci2511/filecollate)
A lightweight `Go` package for concurrent file grouping based on customizable collation criteria. Perfect for automating file organization tasks in multi-threaded environments.

### [deduplo](https://github.com/ricci2511/deduplo)
A command-line tool for identifying and optionally deleting duplicate files. Built on top of `filecollate`, this tool is efficient and easy to use for managing redundant data.

---

Feel free to contribute or suggest enhancements via the respective GitHub repositories!

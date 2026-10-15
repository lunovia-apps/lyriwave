# Changelog

Notable user-facing changes to **LyriWave Desktop** are listed below, newest release first. For downloads and complete release information, see [GitHub Releases](https://github.com/lunovia-apps/lyriwave/releases).

## [1.2.0](https://github.com/lunovia-apps/lyriwave/releases/tag/v1.2.0)

### Added

- Explicit project duration with 15/30/60-second presets, custom duration, and Fit to Audio.
- Non-destructive audio placement, source trimming, volume, and Fade In/Out controls.
- Fit-to-Timeline zoom, six detailed zoom levels, and continuous seeking by dragging the Timeline ruler.
- Independent deletion of one or multiple lyric clips without removing their lyric lines, with Undo/Redo support.
- Batch insertion of lyric lines and regularly spaced Timeline clips.

### Improved

- Higher-resolution waveforms and more accurate audio duration handling, including low-sample-rate MP3 files.
- Recognizable imported-font names instead of generated asset filenames where metadata is available.
- Default MP4 filenames based on the project title or saved project filename.
- Export uses unsaved edits without automatically saving the project, and supports read-only projects.
- Existing MP4 files can be replaced after explicit overwrite confirmation; cancellation and encoding failure preserve the original output.

### Compatibility

- Projects from v1.0.0 and v1.1.0 can be opened and migrated to project schema 5.
- Projects saved in schema 5 cannot be opened by v1.0.0 or v1.1.0. Back up original projects, related assets, and user preset/Scene Template libraries before upgrading.

## [1.1.0](https://github.com/lunovia-apps/lyriwave/releases/tag/v1.1.0)

### Added

- Multi-selection of lyric rows and timeline clips for batch editing.
- Independent text-shadow opacity control.
- Eight text-placement presets and optional position snapping.
- Center and safe-area guides in Preview.
- New **Readable Outline** and **No Motion** built-in presets.

### Improved

- Apply typography, styling, Enter/Exit animations, presets, and Scene Templates to multiple selected items.
- Clearer display of mixed property values when editing multiple selections.
- Improved Lyrics, Inspector, Timeline, and responsive layouts.
- Group batch-editing operations into single Undo/Redo steps.
- Refined lyric selection after insertion and mixed-state handling for imported fonts.

### Compatibility

- Projects from v1.0.0 can be opened and migrated to project schema 4.
- Projects saved in schema 4 cannot be opened by v1.0.0. Back up original projects, related assets, and user preset/Scene Template libraries before upgrading.

## [1.0.0](https://github.com/lunovia-apps/lyriwave/releases/tag/v1.0.0)

### Initial Windows release

- Multiline lyric editing and timeline-based lyric timing.
- WAV and MP3 audio import with waveform display.
- Customizable typography, fonts, and backgrounds.
- Lyric entrance and exit animations.
- Text-style presets, animation presets, and Scene Templates.
- Synchronized Preview playback.
- MP4 export up to 1080p60.
- Undo/Redo and recovery of recent work after abnormal termination.

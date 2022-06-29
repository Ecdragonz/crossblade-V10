### 1.0.7
- [Fixed] Resolved error preventing rendering the sound layer configuration dialog on systems other than 5e

### 1.0.6
- [Changed] Updated README.md
- [Changed] The build process should now be packaging README.md and CHANGELOG.md with the module

### 1.0.5

- [Changed] Refactor of layer generation logic to reuse the main sound object if the same audio source is specified in a sound layer
- [Fixed] Resolved a number of cases that could cause sound layers to go out of sync from the base sound
- [Added] Crossblade-enabled sounds will now display a "⚔" icon next to their name in the playlist directory, so that they can be identified at a glance

!['Playlist Directory Icons'](https://github.com/Elemental-Re/crossblade/blob/main/project_assets/changelog/playlist-directory-icons.webp?raw=true "Playlist Directory Icons")

### 1.0.4

- [Changed] Update module.json

### 1.0.3

- [Fixed] Resolved bug causing all layers to fade out on complex layer configs involving a layer referencing the same sound as the base playlist sound

### 1.0.2

- [Fixed] Various minor bug fixes
- [Changed] Code cleanup

### 1.0.1

- [Changed] Improved the sound layer config form a bit: better styling and added some help tooltips

### 1.0.0

- Initial public release
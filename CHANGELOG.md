## [0.1.0] - June 25, 2019
	
**BREAKING CHANGES:** Migrated to use *AndroidX*.
	

## [0.0.4] - February 9, 2019

Upgraded to Dart 2 support and upgraded example project to match latest framework structure.

## [0.0.3] - April 29, 2018

Connected AudioPlaylistComponent to AudioPlaylist so that the component is rebuilt whenever the ancestor AudioPlaylist is rebuilt.

## [0.0.2] - April 29, 2018

Fixed iOS bug where platform was not reporting the 'playing' state after going to next song in playlist. This solution is a stopgap and the root cause needs to be found.

## [0.0.1] - April 28, 2018

Initial Release.  Audio can be streamed on Android and iOS.

* Flutter Widgets created: Audio, AudioPlaylist.
* Imperative Object available: AudioPlayer.
* URL playback is supported.
* FFT reporting on Android.

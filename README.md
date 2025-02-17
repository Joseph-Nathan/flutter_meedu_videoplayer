# flutter_meedu_videoplayer



## Cross-platform video player (web,macos not included)
- Android and Ios are using video player
- Desktop are using dart-vlc


## Used meedu player as a base and added (also fixed some errors)
- swipe to increase and decrease volume 
- swipe to seek 
- integrated wake lock in the code


## Setup For windows 
1.Add in main 
```dart
  initDartVlc();
```
Example:
```dart
void main() {
initDartVlc();
runApp(MyApp());
}
```


<img src="https://darwin-morocho.github.io/flutter-meedu-player/assets/q2.gif" alt="meedu_player" width="160" />
<br/>
<img src="https://darwin-morocho.github.io/flutter-meedu-player/assets/full.gif" alt="meedu_player" width="300" />
<img src="https://user-images.githubusercontent.com/15864336/94494352-9924d100-01b4-11eb-9c0f-54c88868331b.png" alt="meedu_player" width="300" />

| Features  | iOS | Android | windows | linux | macos
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Videos from Network  | ✅  | ✅ | ✅ | ✅ | x |
| Videos from Assets  | ✅  | ✅ | ✅ | ✅ | x |
| Videos from local files  | ✅  | ✅ | ✅ | ✅ | x|
| Looping  | ✅  | ✅ | ✅ | ✅ | x |
| Autoplay  | ✅  | ✅ | ✅ | ✅ | x |
| Swipe to increase and decrease Sound  | ✅  | ✅ | ✅ | ✅ | x|
| Swipe to seek in video | ✅  | ✅ | ✅ | ✅ | x|
| Fullscreen  | ✅  | ✅ | ✅ | ✅ | x |
| Launch Player as Fullscreen  | ✅  | ✅ | ✅ | ✅ |x |
| Playback Speed  | ✅  | ✅ | ✅ | ✅ | x |
| fastForward / Rewind  | ✅  | ✅ | ✅ | ✅ |x |
| srt subtitles  | ✅  | ✅ | X | X | X |
| Customize  | partially  | partially | ✅ | ✅ | x |

---

👋 👉 <b>[Complete documentation here](https://player.meedu.app)</b>

# Changelog

## 3.1.0+1

- Added `isWidgetTest` to set visibility detector instance update interval to `Duration.zero`.
- Added `flutter_lints` in dev dependecies.
- Updated sdk env to from `<3.0` to `<4.0`.

## 3.0.0+2

- Update documentation.

## 3.0.0

- Migrates to V2 using Flutter SDK 3.3.10.
- Add flutter_lints 2.0.0.
- Update example project.
- Update documentation.

## 2.0.1

- Bumps [visibility_detector](https://pub.dev/packages/visibility_detector) version to fix Flutter 2.8 builds.

## 2.0.0

- Promotes null safety to stable release.

## 2.0.0-nullsafety.0

- Migrates to null safety.

## 1.1.0+1

- Improves example project.
- Updates LICENSE file.
- Increases documentation.

## 1.1.0

- Adds [onVisibilityGained()](https://pub.dev/documentation/focus_detector/latest/focus_detector/FocusDetector/onVisibilityGained.html), [onVisibilityLost()](https://pub.dev/documentation/focus_detector/latest/focus_detector/FocusDetector/onVisibilityLost.html), [onForegroundGained()](https://pub.dev/documentation/focus_detector/latest/focus_detector/FocusDetector/onForegroundGained.html) and [onForegroundLost()](https://pub.dev/documentation/focus_detector/latest/focus_detector/FocusDetector/onForegroundLost.html) callbacks.
- Fixes a bug in which callbacks were being fired multiple times when using pop gesture on iOS.

## 1.0.3

- Upgrades dependencies.

## 1.0.2

- Fixes background/foreground transition on iOS.

## 1.0.0+1

- Simplifies example project.

## 1.0.0

- First release.

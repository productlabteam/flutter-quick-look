# Changelog

## 0.0.1

- Ability to open a single file in `QLPreviewController`.

## 0.0.2

- Ability to open muitiple assets with `openURLs(List<String> _)` method

## 0.0.3

- `README.md` typos fix

## 0.0.4

- Add documentation

## 0.0.5

- Update Android versions, so that it builds
- Update dependencies

## 0.0.6

- remove android support (was redundant) (#6)
- openURL futures now resolve after native modal closes (#5)

## 0.1.0

- move to pigeon for communication

## 0.1.1

- Add optional `isDismissable` param to `openURL` & `openURLs` (defaults to `true`, system default)
- Ability to check whether a file preview is supported by calling `canOpenURL(String url)`

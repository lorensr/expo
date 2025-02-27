# Changelog

## Unpublished

### 🛠 Breaking changes

- Dropped support for iOS 10.0 ([#11344](https://github.com/expo/expo/pull/11344) by [@tsapeta](https://github.com/tsapeta))

### 🎉 New features

- Created config plugin ([#11574](https://github.com/expo/expo/pull/11574) by [@EvanBacon](https://github.com/EvanBacon))

### 🐛 Bug fixes

## 8.4.0 — 2020-11-17

_This version does not introduce any user-facing changes._

## 8.3.0 — 2020-08-18

_This version does not introduce any user-facing changes._

## 8.2.3 — 2020-06-18

### 🐛 Bug fixes

- Fixed misuse of the native module that caused an unhandled Promise being rejected when `cancelApplePayRequestAsync` was called. ([#8864](https://github.com/expo/expo/pull/8864) by [@sjchmiela](https://github.com/sjchmiela))

## 8.2.2 — 2020-06-01

### 🐛 Bug fixes

- Upgraded `Stripe` pod on iOS to fix compatibility with Xcode 11.4. Now you can also customize the version of `Stripe` pod installed by setting `$StripeVersion` variable in your `Podfile`. ([#8594](https://github.com/expo/expo/pull/8594) by [@sjchmiela](https://github.com/sjchmiela))

## 8.2.1 — 2020-05-29

_This version does not introduce any user-facing changes._

## 8.2.0 — 2020-05-27

_This version does not introduce any user-facing changes._

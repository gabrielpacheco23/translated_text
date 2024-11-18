# translated_text

## TranslatedText Widget

You can use the `TranslatedText` widget as a replacement for the `Text` widget to get the benefits of `translate()` method directly in the widget tree (UI Layer).

```dart
TranslatedText(
  "Hello, World!",
  loadingText: 'Loading...',
  from: 'en',
  to: 'ar',
  style: TextStyle(fontSize: 20),
)

// prints مرحبا بالعالم!
```
&nbsp;

## Changes: 
Separated TranslatedText from translator package because of Flutter dependency reasons.

## Contribution: @moazelsawaf

## Disclaimer
This package is developed for educational purposes only. Do not depend on this package as it may break anytime as it is based on crawling the Google Translate website. Consider buying Official Google Translate API for other types of usage.


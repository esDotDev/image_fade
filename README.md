# ImageFade

**Requires Flutter 1.6.7 or higher.**

A widget for Flutter that displays a `placeholder` image while a specified `image` loads, then cross-fades to the loaded image.

If `image` is changed, it will cross-fade to the new image once it is finished loading. Setting `image` to `null` will cross-fade back to the placeholder.

![example image](https://gskinner.github.io/image_fade/example.gif)

You can set `color` (background color), `fadeDuration` and `fadeCurve`, as well as most `Image` properties:
`width`, `height`, `fit`, `alignment`, `repeat`, `matchTextDirection`, `excludeFromSemantics`
and `semanticLabel`.

You can also specify a `loadingBuilder` that will display load progress any time a new image is loaded.

## Example

See the example directory for a simple example.
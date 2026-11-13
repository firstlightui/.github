<a href="https://firstlightui.dev">
  <img src="https://raw.githubusercontent.com/firstlightui/firstlight-public/main/public/firstlight-icon.png" alt="Firstlight UI sunrise logo" width="96" height="96">
</a>

# Firstlight UI

We build open-source tools for Laravel developers creating native iOS and Android apps.

Firstlight is the app-shell layer for [NativePHP](https://nativephp.com): genuine SwiftUI and Jetpack Compose controls, with familiar Laravel validation, authorization, pagination, and testing. Write screens in PHP and Blade, and let each platform present its own native controls.

[Website](https://firstlightui.dev) · [Documentation](https://firstlightui.dev/docs) · [Component gallery](https://firstlightui.dev/components) · [Email](mailto:team@firstlightui.dev)

## What we're building

Our focus is the screens most forms apps need: searchable lists, detail screens, forms, settings, sheets, dialogs, and feedback. Firstlight connects those controls to Laravel Form Requests, Gates and Policies, and Pest tests.

Accessibility is part of that work, including native screen-reader semantics, text scaling, right-to-left layout, and reduced motion. A Laravel Boost guideline and skills help coding agents build from the same documented recipes.

Firstlight is currently a release candidate. Physical-device screen-reader checks, soak/performance testing, and wider application qualification remain part of the work toward 1.0.

## Explore the projects

| Repository | What's inside |
| --- | --- |
| [nativephp](https://github.com/firstlightui/nativephp) | The Firstlight package: Blade components, Laravel extensions, SwiftUI and Jetpack Compose renderers, and documentation. |
| [showcase](https://github.com/firstlightui/showcase) | A runnable app with example screens, recipes, and Pest tests. |
| [firstlight-public](https://github.com/firstlightui/firstlight-public) | The public website, documentation reader, and component gallery. |

Start with the [installation guide](https://firstlightui.dev/docs/getting-started/installation) or explore the [list and detail recipe](https://firstlightui.dev/docs/how-to/build-a-list-detail-flow).

## Plugins

NativePHP Mobile plugins for what the phone can do and NativePHP doesn't expose yet. Each one is free and MIT licensed, and works with or without Firstlight's controls. See them all on the [plugins page](https://firstlightui.dev/plugins).

| Plugin | Status | What it does |
| --- | --- | --- |
| [App Guard](https://github.com/firstlightui/app-guard) | Available | An app lock: hide the app in the app switcher, cover it when it returns after a timeout, keep protected screens closed, and copy secrets to a clipboard that clears itself. Start with the [app lock recipe](https://firstlightui.dev/docs/how-to/build-an-app-lock-screen). |
| [Local OCR](https://github.com/firstlightui/local-ocr) | Coming soon | Multi-page document capture and on-device text recognition: VisionKit and Apple Vision on iOS, ML Kit on Android. |
| [Local AI](https://github.com/firstlightui/local-ai) | Coming soon | Text generation with the phone's built-in model: Apple Foundation Models on iOS, Gemini Nano on Android. Prompts and output never leave the device. |

## Built on NativePHP

Firstlight builds on the SuperNative foundation created by [Shane Rosenthal](https://github.com/shanerbaner82) and [Simon Hamp](https://github.com/simonhamp). NativePHP provides navigation chrome and Mobile UI provides layout; Firstlight supplies controls and Laravel screen behaviour within them, keeping each platform's own presentation.

## Get involved

Try a recipe, report a reproducible bug, or suggest an improvement through the [package issue tracker](https://github.com/firstlightui/nativephp/issues). For other enquiries, reach us at [team@firstlightui.dev](mailto:team@firstlightui.dev).

The Firstlight package is available under the [MIT licence](https://github.com/firstlightui/nativephp/blob/main/LICENSE).

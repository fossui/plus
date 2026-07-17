# fossui_plus

> [!IMPORTANT]
> Pre-development. This is an early draft, not a released package. It is under
> very active work: the API is unsettled and changes constantly. Do not depend on
> it yet.

Composite UI components for Flutter, built on [fossui](https://github.com/fossui/fossui).

fossui ships the foundations: design tokens and atoms like Button, TextField,
Card, and Select. fossui_plus is the layer above it, the bigger composed pieces
most apps end up rebuilding by hand: charts, data tables, dashboard shells, auth
forms. Each one is assembled from fossui atoms, so it inherits the same theme and
rethemes with your app for free.

The fossui core comes bundled. Adding fossui_plus pulls it in, and a single
import gives you both the plus components and the fossui atoms and tokens.

## Status

Pre-development. The package is scaffolded, the API is unsettled, and components
are still being designed.

## Install

```yaml
dependencies:
  fossui_plus: ^0.0.1
```

One import gives you everything, plus components and the fossui core:

```dart
import 'package:fossui_plus/fossui_plus.dart';
```

## Topics

`flutter` `ui` `components` `design-system` `widgets` `charts` `dashboard` `data-table`

## License

MIT. Free, same as the core.

# Change Log

## [0.0.2] - 2025-08-13

### Added
- Comprehensive workbench theming: tabs, title/activity/status bars, sidebars, panels, lists/trees, inputs/buttons/dropdowns, notifications/quick pick/menus, editor gutters/indent guides/rulers/line numbers/selection/find/hover/brackets/inlay/sticky scroll, diff/peek, terminal (ANSI 16 + cursor), widgets, git decorations, settings, command center, notebooks, merge editor, bracket pair colorization, minimap, debug/testing, and search editor.
- Enabled semantic highlighting and mapped core token types: `keyword`, `modifier`, `operator`, `type`, `interface`, `typeParameter`, `namespace`, `class`, `enum`, `struct`, `function`, `parameter`, `decorator`.
- Extended and aligned language support and token colors for:
	- Web/JS: JavaScript/TypeScript + JSX/TSX (tags, attributes, punctuation; interface/extends/type/dom/builtins; function/async; operator/modifier fallbacks).
	- PHP + Laravel/Blade (directives, delimiters, tags/attrs, namespaces, classes including Route::, PHP open/close tags).
	- Python (keywords, decorators, builtins, f-strings/interpolation; semantic tokens for function/parameter/decorator).
	- Go (builtins, booleans/nil, types/packages, constants; semantic `struct`).
	- Ruby + ERB, C/C++, Kotlin, Swift, Dart, Scala, Lua, R, PowerShell, XML, Vue, Svelte, GraphQL.
- Added screenshots (public/img): Java, PHP, Python, React, Ruby.

### Changed
- Search/Find widgets, TSX/JSX opening tags and punctuation adjusted to avoid white accents and match the palette.
- README updated with Marketplace links and new screenshots.

### Fixed
- Replaced deprecated `editorIndentGuide.*` keys with `editorIndentGuide.background1/activeBackground1` (and background2 set).
- Corrected invalid schema keys and ensured required transparency for minimap selection highlight.
- Moved Blade token rules into `tokenColors` (fix schema placement error).

## [0.0.1] - 2025-04-06

### Added
- Initial release of the "frutiger-aero-dark" extension.


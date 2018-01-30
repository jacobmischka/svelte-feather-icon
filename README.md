# svelte-feather-icon

Simple wrapper component for [Feather Icons][feather-icons].

## Usage

```html
<FeatherIcon icon="feather" />
```

### Properties

- `icon`: Feather icon name. What you would put in the `data-feather` attribute.
- `attrs`: [Attributes you would pass to `feather.replace()`][attrs]

[feather-icons]: https://feathericons.com/
[attrs]: https://github.com/feathericons/feather#featherreplaceattrs

### Using with [Sapper][sapper]

Please import `svelte-feather-icon/FeatherIcon.html` directly (or configure your bundler to resolve `svelte` package fields, `rollup-plugin-svelte` does this out of the box, see [resolve.mainFields][resolve.mainFields] for webpack) and compile it from within your own project.

See [svelte#604](https://github.com/sveltejs/svelte/issues/604) for more information.

[sapper]: https://sapper.svelte.technology
[resolve.mainFields]: https://webpack.js.org/configuration/resolve/#resolve-mainfields

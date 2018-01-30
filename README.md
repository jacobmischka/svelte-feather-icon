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

Please import `svelte-feather-icon/FeatherIcon.html` directly and compile it from within your own project.

Please see [sapper#110](https://github.com/sveltejs/sapper/issues/110) for discussion of alternatives.

[sapper]: https://sapper.svelte.technology

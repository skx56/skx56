# skx56 profile banner

Add the assets below to the repository named `skx56` (the special GitHub profile
repository), then place this at the top of its `README.md`:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-light.svg">
  <img alt="Saksham - GitHub profile introduction" src="assets/profile-light.svg" width="100%">
</picture>
```

The two SVGs have no JavaScript or external dependencies. They use only native
SVG/SMIL animation and automatically choose the appropriate palette in GitHub.

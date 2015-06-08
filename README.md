solar-stellarorg
--------------

solar-stellarorg is a [solar css framework](https://github.com/stellar/solar) theme. It themes solar to Stellar Development Foundation's branding.

This is a [theme layer](https://github.com/stellar/solar/blob/master/docs/architecture.md#modules-and-themes) on solar. The lib/_index.scss and styles/_index.scss are each loaded after each of their respective core modules. The solar-stellarorg/lib/_index.scss file is loaded before solar-css/styles/_index.scss meaning that this theme library has a chance to affect how the core styles look via variables.

This theme is not limited to be used in interstellar but also on other Stellarorg projects. Also, while others can use solar-stellarorg, development of solar-stellarorg is targeted for our own use. Feel free to fork and develop into your own theme though.

## What lives in the stellarorg theme?
- **variables**: theming variables that other css code uses (colors, padding, border-radius)
- **typography**: overrides for type scale and custom fonts
- **organization gloabl sprites/icons**: small sprites use globally throughout stellarorg brand such as the Stellar rocket or [stroopy and friends](https://www.stellar.org/stories/adventures-in-galactic-consensus-chapter-1/)
- **custom**: any other styles to be used across multiple stellarorg projects

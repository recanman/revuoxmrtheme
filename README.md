## Revuo XMR Theme

The Revuo XMR theme is a customized theme for the Revuo Monero newsletter.

[Emerald](https://github.com/rottenwheel/revuo-monero-theme/) is the theme used by Revuo. It is a minimal and mobile-first blog theme, originally for Jekyll, ported to Hugo by [recanman](https://github.com/recanman).

## Setup & usage

Make sure you have Go and Hugo installed. If not, follow the instructions on the [Hugo website](https://gohugo.io/getting-started/installing/).

To use the Revuo XMR theme, clone the repository as a submodule and add it to your Hugo site:

```bash
git submodule add https://github.com/rottenwheel/revuoxmrtheme.git themes/revuo-xmr
```

Then, add the theme to your site's configuration file:

```toml
theme = "revuo-xmr"
```

## Customization

Please see [config.toml.example](./config.toml.example) for an example configuration file. You can copy this file to your site's root directory and rename it to `config.toml`.

## License
Revuo Monero is released under GNU Affero General Public License v3.0. See [LICENSE](./LICENSE) for more information.

# aceberg-bootswatch-fork


Fork of [bootswatch](https://github.com/thomaspark/bootswatch) with additional themes:
- Emerald
- Grass
- Ocean
- Sand

## How to add theme

1. Copy and rename an existing theme in `/dist`
2. Edit `_variables.scss`
3. Run `grunt swatch:new-theme`
4. Copy `docs/old-theme` to `docs/new-theme`, edit `index.html` there
5. Add theme in menu in `docs/index.html`
6. Run `grunt` to see result

## NPM

1. `npm login`
2. `npm publish`
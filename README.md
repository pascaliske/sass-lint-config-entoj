# Entoj Shareable sass-lint config
Shareable sass-lint config for the entoj project.

## Install
```bash
npm install sass-lint-config-entoj
```

## Usage
The sass-lint shareable configs can be used with the `config-file` feature of `.sass-lint.yml` files.

Learn more about [shareable configs](https://github.com/sasstools/sass-lint/blob/develop/docs/options/config-file.md) on the github wiki of sass-lint.

To use the Entoj shareable config, first run this:

```bash
npm install --save-dev sass-lint-config-entoj
```

Then, add this to your .sass-lint.yml file:

```
options:
  config-file: ./node_modules/sass-lint-config-entoj/sass-lint.yml
```

You can override settings from the shareable config by adding them directly into your
`.sass-lint.yml` file.

## Learn more

For the full listing of rules visit the [wiki](https://github.com/pascaliske/sass-lint-config-entoj/wiki).

## License

MIT. Copyright &copy; [Pascal Iske](https://pascal-iske.de).

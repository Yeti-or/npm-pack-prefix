# npm-pack-prefix

Working as intended:

```sh
npm install --prefix packages/nested
npm info --prefix packages/nested
npm owner ls --prefix packages/nested
```

Doesn't respect `--prefix`:

```sh
npm pack --prefix packages/nested
npm publish --prefix packages/nested
```


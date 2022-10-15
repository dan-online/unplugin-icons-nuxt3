# unplugin-icons-nuxt3

## Usage

```bash
$ yarn install unplugin-icons-nuxt3 unplugin-icons
$ npm install unplugin-icons-nuxt3 unplugin-icons
```

```ts
# nuxt.config.ts
export default defineNuxtConfig({,
  buildModules: [
    'unplugin-icons-nuxt3'
  ]
});
```

```json
# tsconfig.json
{
  "extends": "./.nuxt/tsconfig.json",
  "compilerOptions": {
    "types": ["unplugin-icons/types/vue"]
  }
}
```

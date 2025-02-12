# Rspress website

## Setup

## step 1

```bash
pnpm create rspress@latest # get "rspress": "^1.40.2"
```

## step 2

Ensure the bug exists in the latest version


```bash
pnpm up -L
```

get 

```json
{
  "dependencies": {
    "rspress": "^1.41.2"
  },
  "devDependencies": {
    "@types/node": "^22.13.1"
  }
}
```

## step 3

edit ["docs/guide/index.md"](docs/guide/index.md)

```diff
# line 211
+ ![img-1](/rspress-light-logo.png)
+ ![img-2](/rspress-light-logo.p_ng)
+ ![img-3](/rspress-light-logo.jpg)
```

Adding wrong path

## dev mode

```bash
pnpm run dev
```

![dev/mode](screenshot/dev_mode.jpg)
> dev mode show `200` OK

## preview mode

```bash
pnpm run build
pnpm run preview
```

![preview_mode](screenshot/preview_mode.jpg)
> preview mode status `404` not find

<!-- [[toc]] -->
# Hello VuePress
## js
## ts
### es2022
### es2021
VuePress 2 已经发布 :tada: ！

```ts{1,6-8}
import { defaultTheme, defineUserConfig } from 'vuepress'

export default defineUserConfig({
  title: '你好， VuePress',

  theme: defaultTheme({
    logo: 'https://vuejs.org/images/logo.png',
  }),
})
```

@[code](../a.ts)

这是默认主题内置的 `<Badge />` 组件 <Badge text="演示" />

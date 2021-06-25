# Vue 3 + Typescript + Vite

- VSCode 安装插件 EditorConfig for VS Code
- VSCode 编辑器使用 Prettier 配置需要下载插件 Prettier - Code formatter
- 如果在自动安装 eslint 步骤失败：npm i @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-airbnb-base eslint-plugin-import eslint-plugin-vue -D
- VSCode 使用 ESLint 配置文件需要去插件市场下载插件 ESLint 。

## 目录

```
├── publish/
└── src/
    ├── assets/                    // 静态资源目录
    ├── common/                    // 通用类库目录
    ├── components/                // 公共组件目录
    ├── router/                    // 路由配置目录
    ├── store/                     // 状态管理目录
    ├── style/                     // 通用 CSS 目录
    ├── utils/                     // 工具函数目录
    ├── views/                     // 页面组件目录
    ├── App.vue
    ├── main.ts
    ├── shims-vue.d.ts
├── tests/                         // 单元测试目录
├── index.html
├── tsconfig.json                  // TypeScript 配置文件
├── vite.config.ts                 // Vite 配置文件
└── package.json
```

## References

-   [从 0 开始手把手带你搭建一套规范的 Vue3.x 项目工程环境](https://mp.weixin.qq.com/s/4aYlFZO8Cr1OGbMMb232og)

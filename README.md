# Vite 开发 npm 包的简易模板 📦
包含 TS 配置 📝

> 一个简单的 Vite 模板，用于开发 npm 包，配备 TypeScript 支持 💻

 
### 使用方法 📚

1. 克隆仓库：`git clone https://github.com/CherishMvp/vite-npm-template.git`
2. 修改配置文件以及包名中的一些入口配置等
3. 安装依赖：`npm install` 或 `pnpm install`
4. 启动开发服务器：`npm run dev` 或 `pnpm dev`
5. 构建包：`npm run build` 或 `pnpm build`

### 配置文件 📝

* `tsconfig.json`：TypeScript 配置文件
* `vite.config.js`：Vite 配置文件
* `.npmignore`：不需要上传npm的配置
### 例子 📊

在 `src/index.ts` 中写入你的代码：
```typescript
export function add(a: number, b: number) {
  return a + b;
}
```
然后在 `test/index.test.ts` 中写入测试代码：
```typescript
import { add } from '../src/index';

test('add function', () => {
  expect(add(1, 2)).toBe(3);
});
```
### 发布包 🚀

1. 构建包：`npm run build` 或 `yarn build`
2. 登录 npm：`npm login`
3. 发布包：`npm publish` 或 `yarn publish`

🎉 如果对您有帮助请给个start😋😋 🎉

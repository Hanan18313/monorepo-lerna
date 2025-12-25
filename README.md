# monorepo-root-advance

This is the root of a monorepo.

# yarn https://yarn.nodejs.cn/
# lerna https://lerna.nodejs.cn/
# storybook https://storybook.org.cn/

### 安装步骤

```bash
# 安装依赖
npm install -g corepack
# 初始化
yarn init -2

# 安装 lerna
yarn add lerna -D
yarn add ci-info -D

# 验证安装lerna
yarn dlx lerna -v

# lerna 初始化
yarn dlx lerna init # 模式 1：固定版本（所有包共享版本号，默认）
yarn dlx lerna init --independent # 模式 2：独立版本号（每个包可以指定版本号）

```

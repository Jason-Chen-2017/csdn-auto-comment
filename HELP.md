## 使用教程

### 先安装 puppeteer

To use Puppeteer in your project, run:

```shell
npm i puppeteer
# or using yarn
yarn add puppeteer
# or using pnpm
pnpm i puppeteer
```

When you install Puppeteer, it automatically downloads a recent version of Chrome for Testing (~170MB macOS, ~282MB
Linux, ~280MB Windows) that is guaranteed to work with Puppeteer. The browser is downloaded to the
$HOME/.cache/puppeteer folder by default (starting with Puppeteer v19.0.0).

If you deploy a project using Puppeteer to a hosting provider, such as Render or Heroku, you might need to reconfigure
the location of the cache to be within your project folder (see an example below) because not all hosting providers
include $HOME/.cache into the project's deployment.

For a version of Puppeteer without the browser installation, see puppeteer-core.

If used with TypeScript, the minimum supported TypeScript version is 4.7.4.

### 安装依赖

执行：

```shell
npm install
````

### 启动

```shell
node ./comment_articles.js
```

## 功能

- [x] 支持自动评论
- [x] 支持自动点赞
- [x] 支持断点
- [x] 日志打印
- [x] 支持黑名单录入

## 声明

> 仅限用于学习

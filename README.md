# objects.xiqiqi.com

奇物 · 奇珍异宝

诅咒之物、宗教圣物、古代遗物、超前科技、失窃珍宝。

## 配置

- channel: `objects`
- domain: `objects.xiqiqi.com`
- accent: `#D99A2B`
- core: `^0.1.0`

## 部署

- 发布：GitHub Actions（`.github/workflows/deploy.yml`）
- 构建时检出 `oddities-core` 与 `oddities-and-mysteries`
- 自定义域名：见 `CNAME`，并在 Pages 设置中绑定
- 构建由 `oddities-core` 统一执行，本仓不写页面代码

## 目录

```text
site.config.ts   # 站点配置
CNAME            # 自定义域名
package.json     # core 版本
```

页面代码在 `oddities-core`，内容在 `oddities-and-mysteries`。
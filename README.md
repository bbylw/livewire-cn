<p align="center"><img width="300" src="https://raw.githubusercontent.com/livewire/livewire/4.x/art/logo.svg" alt="Livewire Logo"></p>

<p align="center">
    <a href="https://packagist.org/packages/livewire/livewire">
        <img src="https://poser.pugx.org/livewire/livewire/d/total.svg" alt="总下载量">
    </a>
    <a href="https://packagist.org/packages/livewire/livewire">
        <img src="https://poser.pugx.org/livewire/livewire/v/stable.svg" alt="最新稳定版本">
    </a>
    <a href="https://packagist.org/packages/livewire/livewire">
        <img src="https://poser.pugx.org/livewire/livewire/license.svg" alt="开源许可">
    </a>
</p>

## 简介

Livewire 是 Laravel 的全栈框架，让你无需脱离 PHP 即可构建动态 UI 组件。

## 官方文档

你可以在 [Livewire 官网](https://livewire.laravel.com/docs) 阅读官方文档。

## 本地开发

```bash
git clone git@github.com:livewire/livewire.git && cd livewire
composer setup
```

该命令会安装 PHP 与 JS 依赖，并为浏览器测试配置 ChromeDriver。

```bash
composer test:unit                                   # 单元测试
composer test:browser                                # 浏览器测试（无头模式）
composer test:browser:headed                         # 浏览器测试（打开 Chrome）
composer test:browser -- --filter="SupportCSP"       # 指定测试
```

改动后构建 JS 资源：`npm run build`

## 贡献

感谢你考虑为 Livewire 做出贡献！你可以[在此](https://github.com/livewire/livewire/blob/4.x/.github/CONTRIBUTING.md)阅读贡献指南。

## 行为准则

为了维护一个对所有人友好的 Laravel 社区，请阅读并遵守 Laravel 的[行为准则](https://laravel.com/docs/contributions#code-of-conduct)。

## 安全漏洞

请查阅我们的[安全策略](https://github.com/livewire/livewire/security/policy)，了解如何报告安全漏洞。

## 许可证

Livewire 是开源软件，基于 [MIT 许可证](https://github.com/livewire/livewire/blob/4.x/LICENSE.md)发布。

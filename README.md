# WP Table of Contents

[![Version](https://img.shields.io/badge/version-1.0.1-blue.svg)](https://github.com/tikhomirov/wp-toc-plugin/releases)
[![WordPress](https://img.shields.io/badge/WordPress-4.6%2B-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-8.0%2B-purple.svg)](https://php.net/)

Automatically inserts a table of contents into post content. Supports manual placement via marker or shortcode.

## Requirements

| Component | Minimum |
|-----------|---------|
| **WordPress** | 4.6 |
| **PHP** | 8.0 |
| **Theme CSS** | Bootstrap 5 styles recommended |

## Features

- Auto-insert TOC into post content on activation
- Manual marker: `<!--insert-toc-->`
- Shortcode: `[toc]`
- Composer package type `wordpress-plugin`

## Installation

### From Git (submodule)

```bash
git submodule add git@github.com:tikhomirov/wp-toc-plugin.git wp-content/plugins/wp-toc-plugin
```

### Manual

1. Download the [latest release](https://github.com/tikhomirov/wp-toc-plugin/releases).
2. Upload to `wp-content/plugins/wp-toc-plugin/`.
3. Activate **Post Table of Content**.
4. Add required TOC CSS to your theme.

## Usage

Automatic insertion after activation, or:

```
<!--insert-toc-->
```

```
[toc]
```

## License

GPL-2.0-or-later

## Author

Aleksey Tikhomirov — [rwsite.ru](https://rwsite.ru)

---

## Русский

Плагин автоматически вставляет оглавление в контент записи. Требуются стили темы (Bootstrap 5). Ручная вставка: `<!--insert-toc-->` или `[toc]`.

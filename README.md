# ACL Programming Language

**ACL** — компилируемый язык программирования низкого уровня с лаконичным синтаксисом. Язык сочетает простоту высокоуровневых языков с производительностью ассемблера.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-0.3-blue.svg)]()

---

## 📋 Содержание

- [Особенности](#-особенности)
- [Установка](#-установка)
- [Быстрый старт](#-быстрый-старт)
- [Синтаксис](#-синтаксис)
- [Примеры](#-примеры)
- [Документация](#-документация)
- [Лицензия](#-лицензия)

---

## ✨ Особенности

- ✅ Простой и понятный синтаксис
- ✅ Статическая типизация
- ✅ Поддержка списков
- ✅ Функции и рекурсия
- ✅ Импорт модулей с GitHub
- ✅ Высокая производительность (C-based)
- ✅ Кроссплатформенность (Windows/Linux/macOS)

---

## 🔧 Установка

### Windows

1. Скачай [w64devkit](https://github.com/skeeto/w64devkit/releases)
2. Распакуй в `C:\w64devkit`
3. Добавь `C:\w64devkit\bin` в PATH
4. Скачай `acl.exe` или скомпилируй:

```bash
git clone https://github.com/yourname/acl.git
cd acl
gcc -o acl.exe acl.c

# Codex for Data Journalists

Учебный репозиторий для мастер-класса по OpenAI Codex в GitHub Codespaces.

Задача занятия — показать, как ИИ-агент помогает дата-журналисту:
- быстро понять структуру таблицы
- найти аномалии
- построить первый график
- превратить находку в рабочую гипотезу

## Что в репозитории

- `births_regions_russia_2015_2020.csv` — основной датасет
- `births_regions_russia_by_sex_2015_2020.csv` — дополнительный датасет
- `.devcontainer/devcontainer.json` — настройка среды для Codespaces

## Что нужно

- аккаунт GitHub
- аккаунт ChatGPT с доступом к Codex
- Chrome или Edge

## Как начать

1. Откройте репозиторий в Codespaces.
2. Откройте терминал: `Terminal → New Terminal`
3. Запустите Codex:

```bash
codex
```
Если обычный вход не сработал, используйте:

```bash
codex login --device-auth

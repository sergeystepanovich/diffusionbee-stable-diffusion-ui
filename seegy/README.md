# SEEGY Artist Agent

Cursor-агент для артиста **SEEGY** (Progressive House / Melodic Techno, Interplay Records, Flowave).

## Что внутри

| Путь | Назначение |
| --- | --- |
| `BRAND.md` | Бренд-кит: голос, визуал, каталог, ссылки |
| `../AGENTS.md` | Always-on инструкции агента |
| `../.cursor/agents/seegy.md` | Сабагент `@seegy` |
| `../.cursor/skills/seegy-release/` | Пакет промо релиза |
| `../.cursor/skills/seegy-cover-art/` | Промпты обложек для DiffusionBee |
| `../.cursor/rules/seegy.mdc` | Правило бренда (always apply) |
| `../electron_app/src/modifiers.json` | Стили SEEGY в UI Styles |

## Как пользоваться

1. Обновляй факты в `BRAND.md` (релизы, ссылки, коллабы).
2. В чате Cursor: попроси релиз-пак или cover-art — подтянутся skills.
3. Явно: `@seegy` для сабагента артиста.
4. В DiffusionBee → Styles → секция **SEEGY** для чипов атмосферы обложки.

## Примеры запросов

- «Собери промо для The Wall (GIFTBACK Remix)»
- «Напиши IG-подпись на русском для In the Dark»
- «Дай 3 промпта обложки 1:1 для Guiding Light»
- «Короткое био EN + RU для пресс-кита»

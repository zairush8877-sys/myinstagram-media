# Карусель «Витамин C / Сияние» — слайды

Источник текста: `content/post-08-hochu-mogu-vitamin-c.md`
Пост: `content/queue/post-vitamin-c-hochu-mogu.md`

## Актуальные слайды (7 PNG, сгенерированы кодом)

Это то, что реально лежит в папке и на что ссылается пост.
Скрипт: `content/factory/render_carousel_vitamin_c.py` (до слияния историй
назывался `render_carousel.py` — имя занял «Хочу/Могу»-рендер из main).
Фото продуктов загружены с официальных сайтов брендов.

| № | Файл | Содержание |
|---|------|------------|
| 1 | `01-cover.png`    | Обложка: «Витамин C: вернуть коже сияние» |
| 2 | `02-sposob-1.png` | СПОСОБ 1 — Beauty of Joseon Glow Deep Serum — 1 700 ₽ |
| 3 | `03-sposob-2.png` | СПОСОБ 2 — Torriden Cellmazing Vita C Ampoule — 2 200 ₽ |
| 4 | `04-sposob-3.png` | СПОСОБ 3 — Endocare Glycoperfect Serum — 5 800 ₽ |
| 5 | `05-sposob-4.png` | СПОСОБ 4 — КОМБО: антиокс-сыворотка + SPF |
| 6 | `06-sposob-5.png` | СПОСОБ 5 |
| 7 | `07-cta.png`      | CTA: напиши запрос / share-триггер |

Сторис-версия: `stories/` (опубликована 2026-08-05).

### Перегенерировать

```bash
python3 content/factory/render_carousel_vitamin_c.py            # скачивает фото и рендерит
python3 content/factory/render_carousel_vitamin_c.py --dry-run  # только макет, без загрузки
python3 content/factory/render_carousel_vitamin_c.py --out /другая/папка/
```

## Альтернатива: слайды-флэтлэй в Canva

Параллельная версия карусели в формате «ХОЧУ vs МОГУ». Стиль утверждён Заирой 13.06
после отказа от бежевых «дюн» и AI-портретов: **флэтлэй реальных продуктов**
(champagne/blush, без AI-лиц). PNG этих слайдов в репозитории нет — только design_id.

| № | Canva design_id | Содержание |
|---|-----------------|------------|
| 1 | `DAHMfYdhBpM` | Обложка-флэтлэй: ХОЧУ vs МОГУ · вернуть сияние |
| 2 | `DAHMfbUbBuo` | Тусклая кожа → Beauty of Joseon Glow Deep Serum — 1700 ₽ |
| 3 | `DAHMfZg_i1Q` | Пятна → Torriden Cellmazing Ampoule — 2200 ₽ |
| 4 | `DAHMff2UEcI` | Проф → Endocare Glycoperfect Serum — 5800 ₽ |
| 5 | `DAHMfdEa4Rw` | КОМБО: антиокс + SPF (мастер-шаблон) |
| 6 | `DAHMfaoVCik` | Сохрани · отправь подруге (share-триггер) |

Мастер-шаблон флэтлэя для слайдов 2–6 — `DAHMfdEa4Rw`: 5 редактируемых полей,
ID полей сохраняются при `copy-design`.

Выгрузить PNG: `python scripts/canva_export.py` (нужен `CANVA_TOKEN`, домен
api.canva.com должен быть доступен) — либо вручную через Поделиться → Скачать → PNG.

> **Архив отклонённого.** Бежевые «дюны» `DAHMB8LAWZA` + слайды `DAHMB-o45MA` /
> `DAHMHUOjsZE` / `DAHMHYRNlLI` / `DAHMHSTelhY` / `DAHMHblbDkI`;
> AI-портрет с призмой `DAHMRbZTGEE` («искусственно, не нравится»).

## Статус публикации

Сторис опубликованы 2026-08-05, пост придержан (`status: ready` в файле поста).

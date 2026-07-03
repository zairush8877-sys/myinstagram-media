# Карусель «Витамин C / Сияние» — слайды (Canva → PNG)

Источник текста: `content/post-08-hochu-mogu-vitamin-c.md`
Стиль: `content/visual-style.md` — **флэтлэй реальных продуктов** (champagne/blush,
без AI-лиц). Утверждён Заирой 13.06 после отказа от бежевых «дюн» и AI-портретов.

Все 6 слайдов лежат в твоём аккаунте Canva. Чтобы карусель опубликовалась автоматически,
PNG этих слайдов должны лежать в этой папке под именами ниже.

| № | Файл | Canva design_id | Содержание |
|---|------|-----------------|------------|
| 1 | `01-cover.png`           | `DAHMfYdhBpM` | Обложка-флэтлэй: ХОЧУ vs МОГУ · вернуть сияние |
| 2 | `02-beauty-of-joseon.png`| `DAHMfbUbBuo` | Тусклая кожа → Beauty of Joseon Glow Deep Serum — 1700 ₽ |
| 3 | `03-torriden.png`        | `DAHMfZg_i1Q` | Пятна → Torriden Cellmazing Ampoule — 2200 ₽ |
| 4 | `04-endocare.png`        | `DAHMff2UEcI` | Проф → Endocare Glycoperfect Serum — 5800 ₽ |
| 5 | `05-combo.png`           | `DAHMfdEa4Rw` | КОМБО: антиокс + SPF (мастер-шаблон) |
| 6 | `06-cta.png`             | `DAHMfaoVCik` | Сохрани · отправь подруге (share-триггер) |

> Архив отклонённых баз: бежевые «дюны» `DAHMB8LAWZA` + слайды `DAHMB-o45MA`/`DAHMHUOjsZE`/
> `DAHMHYRNlLI`/`DAHMHSTelhY`/`DAHMHblbDkI`; AI-портрет с призмой `DAHMRbZTGEE` («искусственно»).
> Мастер-шаблон флэтлэя для слайдов 2–6 — `DAHMfdEa4Rw` (5 редактируемых полей, ID полей
> сохраняются при copy-design).

## Как получить PNG (два пути)
1. **Вручную (1 клик/слайд):** в Canva открой дизайн → Поделиться → Скачать → PNG →
   сохрани под именем из таблицы в эту папку.
2. **Автоматически:** `python scripts/canva_export.py` (нужен `CANVA_TOKEN`) — выгрузит
   все 6 по design_id сразу сюда. Запускать там, где есть доступ к api.canva.com
   (локально или в GitHub Actions; в этой sandbox-среде домен Canva заблокирован).

После появления PNG — выстави в `content/queue/post-vitamin-c-hochu-mogu.md`
`status: pending`, и движок опубликует карусель в Instagram + Telegram.

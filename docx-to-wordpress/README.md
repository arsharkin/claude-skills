# docx-to-wordpress

**RU:** Конвертирует статьи из `.docx` в готовый HTML для WordPress классического редактора — с автоматической проверкой грамматики и двумя версиями файлов: чистой и на согласование.

**EN:** Converts `.docx` articles into ready-to-paste HTML for the WordPress classic editor — with automatic grammar checks and two output files: a clean version and a review version.

---

## Что делает / What it does

Скилл берёт `.docx` файл (или папку с файлами), конвертирует текст в HTML и создаёт два файла:

- **`[название].html`** — чистая версия с применёнными правками, готова для вставки в WordPress
- **`[название] — на согласование.html`** — те же правки выделены `<strong>`, чтобы автор мог их проверить

Дополнительно генерирует EXCERPT и META DESCRIPTION для SEO-полей WordPress.

The skill takes a `.docx` file (or a folder of files), converts the text to HTML, and creates two output files:

- **`[name].html`** — clean version with fixes applied, ready to paste into WordPress
- **`[name] — на согласование.html`** — same fixes highlighted with `<strong>` for the author to review

Also generates EXCERPT and META DESCRIPTION for WordPress SEO fields.

---

## Как запустить / How to trigger

Скажите Claude / Say to Claude:

- «Обработай статью» + путь к файлу
- «Конвертируй docx»
- «Подготовь для WordPress»
- «Обработай папку со статьями» + путь к папке
- «docx-to-wordpress»
- «Сделай HTML из docx»

---

## Зависимости / Dependencies

Требуется утилита `markitdown`:

```
pip install markitdown
```

---

## Структура / Structure

```
docx-to-wordpress/
├── SKILL.md                          # Ядро скилла / Skill core
└── references/
    ├── html-rules.md                 # Правила HTML-разметки / HTML markup rules
    ├── template-clean.md             # Шаблон чистой версии / Clean output template
    └── template-review.md           # Шаблон версии на согласование / Review template
```

---

## Автор / Author

[Artem Sharkin](https://github.com/arsharkin)

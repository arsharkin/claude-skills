# skill-personal-print

**RU:** Вытаскивает уникальный личный «принт» человека через глубокую структурированную саморефлексию и формулирует его вербально так, чтобы человек узнал себя.

**EN:** Extracts a person's unique «personal print» through deep structured self-reflection and puts it into words the person can recognize as truly their own.

---

## Что такое принт / What is a «print»

Принт — это не то что человек выучил, а то как он устроен: уникальная комбинация качеств и паттернов поведения которая повторяется в разных контекстах — в работе, в хобби, в отношениях. То, что люди ощущают нутром после совместной работы с человеком — но часто не могут сформулировать словами.

A «print» is not what a person has learned, but how they are wired: a unique combination of qualities and behavioral patterns that show up consistently across different contexts — at work, in hobbies, in relationships. What people sense intuitively after working with someone — but often can't put into words.

**Результат / Output:** текст 5–8 абзацев. Критерий готовности: человек говорит «узнаю себя» — не «звучит правильно».

**Output:** 5–8 paragraphs. Readiness criterion: the person says «that's me» — not just «sounds right».

---

## Как работает / How it works

Скилл ведёт многоэтапный коучинговый диалог через конкретные кейсы из жизни человека. Claude задаёт вопросы последовательно, запоминает ответы и постепенно собирает картину — пока не появится формулировка которую человек узнаёт.

The skill runs a multi-step coaching conversation through concrete life stories. Claude asks questions sequentially, remembers the answers, and gradually builds a picture — until a formulation emerges that the person recognizes.

Процесс обычно занимает несколько сессий. Паузы между ними — часть процесса, не сбой.

The process usually takes several sessions. Breaks between them are part of the process, not a failure.

---

## Для кого / Who it's for

- Люди которые хотят понять свою уникальность и сильные стороны
- Те кто готовится к карьерным изменениям и хочет опереться на свою суть
- Все кому важна осознанность и самопознание

**Минимальный возраст: 25 лет.** До этого, согласно исследованиям, паттерны личности ещё нестабильны — результат будет предварительным.

**Minimum age: 25 years.** Prior to this, research shows that personality patterns are still unstable, so the result will be preliminary.

---

## Как запустить / How to trigger

Скажите Claude / Say to Claude:

- «Хочу понять свою уникальность»
- «Помоги разобраться кто я»
- «Что меня отличает от других»
- «Вытащи мой принт»
- «What makes me unique?»
- «Help me understand my strengths»
- «What are my superpowers?»

Claude сам начнёт процесс и объяснит механику перед стартом.

Claude will start the process itself and explain the mechanics before beginning.

---

## Структура / Structure

```
skill-personal-print/
├── SKILL.md                          # Ядро скилла / Skill core
└── references/
    ├── protocol.md                   # Детали каждого этапа / Stage details
    ├── coaching-principles.md        # Принципы ведения беседы / Coaching principles
    ├── clifton-integration.md        # Интеграция CliftonStrengths 34
    └── output-template.md           # Шаблон финального текста / Output template
```

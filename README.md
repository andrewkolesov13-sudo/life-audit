# LIFE AUDIT — Deep Personal Audit & Adaptive Interview

[Русский](#русский) · [English](#english)

---

## Русский

**LIFE AUDIT** — навык для Claude, который проводит глубокий и честный аудит жизни через адаптивное интервью.

Это не мотивационный коуч. Навык отделяет факты от самоописания, ищет расхождения между словами и поведением, находит главный системный узел и переводит анализ в маленькие проверяемые шаги.

> Сделать человеку сложнее врать самому себе, но не сломать его и не лишить способности действовать.

### Что делает

- **Интервью по одному вопросу.** Следующий вопрос выбирается по предыдущему ответу, без анкет.
- **Три блока:** точка А → ближайший горизонт → дальний вектор.
- **Детектор самообмана:** рационализации, «нет времени», цели без плана. Противоречия называются только на основе ответов самого человека.
- **Сводка после каждого блока.** Человек подтверждает собранные факты.
- **Финальный отчёт:** главный системный узел, неприятная правда, стоимость бездействия, 3 приоритета.
- **План на 14 дней:** 0–24 часа → день 2 → день 3 → неделя → две недели.
- **LIFE BASELINE:** зафиксированная точка А, с которой сравниваются следующие аудиты (через 14, 30 и 60–90 дней).

### Режимы

| Режим | Объём |
|---|---|
| Полный аудит | ~30–45 вопросов, можно в несколько сессий |
| Экспресс-аудит | ~12–15 вопросов |
| Повторный аудит | сравнение с сохранённым baseline |
| Отчёт за 14 дней | разбор выполнения плана |

### Установка

**Claude (claude.ai / desktop):** в настройках, в разделе Skills, загрузите папку `life-audit` (zip) или файл `SKILL.md`.

**Claude Code:** скопируйте папку `life-audit` в `~/.claude/skills/` (или в `.claude/skills/` проекта).

**Другие ассистенты:** содержимое `SKILL.md` (без блока frontmatter) можно использовать как системный промпт.

### Запуск

Напишите: «давай проведём аудит жизни», «разбери мою ситуацию», «где я сейчас». Для повторного цикла: «вот мой отчёт за 14 дней» и приложите сохранённый baseline.

### Важно

Навык не заменяет врача, психотерапевта, юриста или финансового консультанта и не ставит диагнозов. При признаках кризиса он останавливает интервью и рекомендует обратиться за профессиональной помощью.

Baseline и отчёт содержат личные данные. Храните их там, где вам комфортно.

---

## English

**LIFE AUDIT** is a Claude skill that runs a deep, honest life audit through an adaptive interview.

It is not a motivational coach. It separates facts from self-description, looks for gaps between words and behavior, identifies the core systemic bottleneck, and turns the analysis into small, testable steps.

> Make it harder for a person to lie to themselves — without breaking them or taking away their ability to act.

### What it does

- **One question at a time.** Each question is chosen based on the previous answer. No questionnaires.
- **Three blocks:** Point A → near horizon → long-term direction.
- **Self-deception detector:** rationalizations, "no time", goals without plans. Contradictions are raised only when grounded in the person's own answers.
- **Summary after each block** that the person confirms.
- **Final report:** core bottleneck, uncomfortable truths, cost of inaction, top 3 priorities.
- **14-day plan:** 0–24 hours → day 2 → day 3 → week 1 → two weeks.
- **LIFE BASELINE:** a saved Point A that later audits are compared against (at 14, 30 and 60–90 days).

### Modes

| Mode | Scope |
|---|---|
| Full audit | ~30–45 questions, can span several sessions |
| Express audit | ~12–15 questions |
| Follow-up audit | comparison with the saved baseline |
| 14-day report | review of the plan |

### Installation

**Claude (claude.ai / desktop):** in Settings, under Skills, upload the `life-audit` folder (zipped) or the `SKILL.md` file.

**Claude Code:** copy the `life-audit` folder to `~/.claude/skills/` (or a project's `.claude/skills/`).

**Other assistants:** the contents of `SKILL.md` (minus the frontmatter) work as a system prompt.

### Language

The skill is written in Russian and replies in the user's language.

### Disclaimer

This skill does not replace a doctor, therapist, lawyer or financial advisor, and does not diagnose. If signs of crisis appear, it pauses the interview and recommends professional help.

The baseline and report contain personal data. Store them wherever you feel comfortable.

---

## License

[MIT](LICENSE) © 2026 Andrew Kolesov

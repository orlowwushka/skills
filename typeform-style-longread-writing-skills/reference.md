# Гайд: как писать data report в стиле Typeform AI Report 2026

**Источник-референс:** [2026 Trends in Generative AI and the Marketer](https://www.typeform.com/AI-data-report-2026) (Typeform, опрос Get Real, n=2 256).  
**Зачем документ:** разобрать не «о чём статья», а **как устроена**, **как звучит**, **какие приёмы повторяются** — чтобы писать такие же лонгриды (любая тема и любой источник данных).  
**Дата:** 2026-05-27.

**Операционный скилл агента:** [SKILL.md](SKILL.md) · **этот файл** — полный справочник жанра и приёмов.

---

## 1. Что это за жанр (не блог и не white paper)

Typeform делает **продуктовый data report** — гибрид:


| Жанр                      | Что берут                                                         |
| ------------------------- | ----------------------------------------------------------------- |
| **Индустриальный отчёт**  | Большая выборка, главы, appendix, методология                     |
| **Журналистский лонгрид** | Цитаты, культурный контекст, риторические вопросы                 |
| **Лендинг продукта**      | Скролл, hero-цифры, CTA на подписку, «report built with Typeform» |
| **Thought leadership**    | Позиция бренда в финале («the AI future we’re building»)          |


**Не делают:** сухой PDF из 40 таблиц, академический тон, нейтральный пресс-релиз.

**Делают:** ощущение «мы пошли в поле, посчитали, поговорили с людьми — и вот что важно *вам*».

---

## 2. Архитектура всего отчёта (макро)

```
[Cover / Hero]
   └── Sample size badge: "2,256 people"
[Sticky TOC]
   └── 3 chapters + Appendix (якоря)
[Chapter 1: Adoption]     ── эмоция: momentum / relief
[Chapter 2: Trust]        ── эмоция: tension → nuance
[Chapter 3: Job security] ── эмоция: fear → hope
[Conclusion]              ── синтез + миссия бренда
[Appendix]                ── методология + bonus stats
[Brand block + CTA]       ── product proof + subscribe
```

### Три оси = три «фильма» в одном

Каждая глава отвечает на **разный страх/вопрос** аудитории:


| Глава        | Вопрос читателя              | Дуга главы                                            |
| ------------ | ---------------------------- | ----------------------------------------------------- |
| Adoption     | «Все уже в AI? Я отстаю?»    | Факт массовости → где ценность → оптимизм             |
| Trust        | «AI убьёт доверие к бренду?» | Хайп/паника → nuance (slop ≠ AI) → quality wins       |
| Job security | «Меня заменят?»              | Угроза → парадокс (копирайтеры) → partner, not threat |


**Правило для своих отчётов:** не одна тема на 20 экранов, а **3 независимых нарратива**, связанных одной большой темой (у них — AI; у Marquiz может быть «как устроены сильные квизы в недвижимости»).

### Сквозной сюжет (story spine)

1. **Универсальность** — «уже все» (95%).
2. **Нюанс** — «но не так, как думаете» (ценность в writing, не в video).
3. **Двойная оптика** — marketers vs consumers.
4. **Снятие катастрофы** — данные мягче, чем Twitter.
5. **Человек остаётся** — edit, pride, reskilling.
6. **Бренд как проводник** — Typeform = способ получить такие инсайты.

---

## 3. Анатомия одной главы (микро-шаблон)

Повторяющийся **beat sheet** — можно копировать почти 1:1:

```
A. Chapter label (ALL CAPS или H2)     → "THE ADOPTION OF AI"
B. Pull-quote (курсив/крупно)        → "AI really affects everything I do at work now"
C. Opening paragraph (контекст+стат)  → связный текст, 2–4 предложения, первая цифра
D. Hero stat #1                       → 95% (огромно)
E. Hero stat #2 (контраст)            → 5% avoid
F. Subhead + distribution             → "How reliant are marketers on AI?"
G. External authority (1 абзац)       → McKinsey 88%
H. Interpretation paragraph           → "The data's clear: ..."
I. Secondary chart / split insight    → common vs valuable use cases
J. Pivot question                     → "So where is AI most pivotal?"
K. Emotion block                      → hopeful / skeptical %
L. Quote carousel                     → MARKETER TAKE × 4–6
M. Secondary insight + hero stat      → 71% pride
N. Bridge to next tension             → "But what's next? Will consumers feel the same?"
O. Key takeaways (3 bullets)          → imperative verbs
```

**Соотношение:** примерно **40% цифры / 35% интерпретация / 25% голоса людей**.

### Переходы между блоками (как пишут)


| Тип перехода       | Пример Typeform                                                              | Когда использовать              |
| ------------------ | ---------------------------------------------------------------------------- | ------------------------------- |
| **Rhetorical Q**   | *So where is AI most pivotal?*                                               | Перед новым срезом данных       |
| **Contrast**       | *But there's a crucial nuance: AI slop.*                                     | Сломать ожидание                |
| **Short bridge**   | *But what's next?*                                                           | Конец главы → следующая тема    |
| **One-word pivot** | *Instead,* / *Luckily,* / *Despite*                                          | После неудобной цифры           |
| **Chapter recap**  | *Marketers have overwhelmingly adopted AI... But if AI's really boasting...* | Начало гл. 3, ссылка на гл. 1–2 |


**Пустые строки (`‍`)** в вёрстке = пауза для скролла; в тексте — аналог короткого абзаца из 1–2 предложений.

---

## 4. Tone of Voice (TOV)

### 4.1. Позиционирование голоса

- **Уверенный, но не высокомерный** — «the data is clear», не «очевидно же».
- **Эмпатичный к маркетологу** — under-resourced profession, relief, pride.
- **Сбалансированный** — признают страх (job loss, slop), не обесценивают.
- **Прагматичный** — almost every takeaway = **глагол действия** (Build, Use, Tap, Disclose).
- **Разговорный американский B2B** — contractions (it's, don't, won't), «kind of», «a lot».

### 4.2. Что избегают

- Категоричный хайп («AI изменит всё завтра»).
- Академические пассивы («было установлено, что…»).
- Вина читателя («вы всё делаете неправильно»).
- Юридическая сухость.

### 4.3. Фирменные формулы


| Формула                                    | Пример                                                                               |
| ------------------------------------------ | ------------------------------------------------------------------------------------ |
| **Stat + human label**                     | *95% of marketers use AI at work*                                                    |
| **Softener + hard stat**                   | *Nearly* 50% … *Only* 21% …                                                          |
| **Not X but Y**                            | *not the flashy visual use cases … It's getting to a decent piece of content faster* |
| **Thoughtful, not fearful**                | моральная рамка без менторства                                                       |
| **Partner, not threat**                    | финальная метафора AI                                                                |
| **The data doesn't support the narrative** | развенчание медиа-паники                                                             |


### 4.4. Длина предложений

- **Opening:** средние и длинные (20–35 слов), один абзац = контекст + surprise stat.
- **Interpretation:** короткие после цифр (8–15 слов).
- **Takeaways:** императив, 8–12 слов, без точки в конце допустимо.

### 4.5. Обращение к читателю

- **you / your** в takeaways и совете.
- **we / our** в методологии и бренд-блоке (*We heard from*, *our data*).
- **they / marketers / consumers** при описании выборки.

---

## 5. Как работают цифры (data storytelling)

### 5.1. Иерархия чисел

1. **Mega stat** — одно число на экран (95%, 71%, 91%).
2. **Contrast pair** — 95% vs 5%; 60% vs 40%; 59% vs 21%.
3. **Distribution** — 5 сегментов шкалы (rely / depend / regular…).
4. **Paradox pair** — разные аудитории, один вопрос (60% marketers vs 40% copywriters).
5. **Footnote** — *Respondents could select multiple answers*.

### 5.2. Правила подачи

- **Число всегда с подписью-человеком:** не «79%», а «79% — Copywriting or written content».
- **Сначала частота, потом ценность** — два разных графика; инсайт в **разрыве** между ними.
- **Внешний якорь** — 1 на главу (McKinsey), не перегружать.
- **Округление для ритма:** *Nearly* half, *More than* a third, *Close to* two-thirds.
- **Дроби вместо процентов** для драмы: *1/3 of marketers*.

### 5.3. Интерпретация после цифры (шаблоны)

```text
The data's clear: [insight in plain English].

[One sentence expanding why it matters for daily work.]

[Optional: surprise — it's not X, it's Y.]
```

```text
[Stat]. But [contrasting stat].

[One sentence resolving the tension.]
```

### 5.4. Заголовки под цифры

- Вопрос как H3: *How reliant are marketers on AI?*
- Тезис как H2: *Meanwhile, consumers crave transparency and quality.*
- Секция caps: *THE ADOPTION OF AI* (визуальный якорь при скролле).

---

## 6. Цитаты и социальное доказательство

### 6.1. Два формата


| Лейбл             | Кто               | Тон                      | Роль             |
| ----------------- | ----------------- | ------------------------ | ---------------- |
| **Marketer take** | Практики          | Смесь надежды и сомнения | «это про меня»   |
| **Consumer take** | Аудитория брендов | Страх + прагматизм       | empathy + stakes |


### 6.2. Как подбирают цитаты

- **Не только позитив** — threatened, icky-ness, hemorrhage followers.
- **Разговорная речь** — em dashes, «kind of», обрывы.
- **Конкретика** — graphic designer, emojis, 100 headline options in 2 minutes.
- **Перед цитатами — setup-вопрос:** *Does AI make their work better? Yes. But…*

### 6.3. Правила верстки (для своего отчёта)

- 4–6 цитат подряд = **карусель / колонка**, не один блок простынёй.
- Лейбл CAPS мелким: `MARKETER TAKE` — ритм как подпись в журнале.
- Длинные цитаты режут на 2–3 строки визуально.

**Для Marquiz:** вместо опросных цитат — **Quiz take**: анонимные фрагменты заголовков/CTA из реальных квизов + 1–2 интервью с клиентами (если будут).

---

## 7. Культурный слой (почему «2026» в заголовке)

В главе Trust — **5–6 новостных пулек** без глубокого разбора:

- Anti-AI-slop ads (Almond Breeze, Equinox)
- Rachel Karten ins/outs
- Ariana / Vogue / sixth finger
- Gary Vee
- «AI paranoia» / em dash

**Функция:** показать, что авторы **в потоке дискурса**, не в вакууме. Читатель узнаёт свою ленту.

**Формула блока:**

```text
[Current year] begins with [cultural moment].

[2–4 one-line references, no links required in print]

[Pivot:] But our data doesn't support the broader narrative.
```

**Для Marquiz (недвижимость):** ипотека, Dubai-каталоги, Циан/ДомКлик, закон о рекламе застройщиков, «квиз вместо лендинга» — 3–4 узнаваемых якоря, потом «в наших 1242 квизах…».

---

## 8. Двойная перспектива (marketers vs consumers)

Сильнейший приём доверия:

1. Одна тема — **два респондента**.
2. Separate survey paths (в appendix).
3. В тексте — **напряжение:** marketers не disclosing vs consumers want transparency.
4. Разрешение: **quality > AI label**.

**Шаблон для Marquiz:**


| «Маркетолог»                   | «Рынок / данные»         |
| ------------------------------ | ------------------------ |
| Что команда *хочет* делать     | Что *делают* 1242 квиза  |
| Интервью / опрос (опционально) | Поведение в enriched CSV |
| Ожидание: «нужен длинный квиз» | Факт: 87% short          |


---

## 9. Key takeaways — отдельный микрожанр

В конце **каждой** главы — ровно **3 буллета**:

```markdown
## Key takeaways on [topic]:

- [Imperative]. [Short reason or scope].
- [Imperative]. [Qualifier: when / how].
- [Imperative]. [Long-term frame].
```

**Паттерны глаголов:** Build, Get, Tap, Use, Disclose, Let, Raise, Re-skill.

**Не делают:** vague «consider exploring»; больше 3 пунктов; пассив.

**Связь с продуктом:** мягкая — takeaways про *workflow*, не «купите Typeform». CTA отдельно внизу.

---

## 10. Заключение и бренд-блок

### Conclusion (короткий)

- 2–3 абзаца **синтеза** без новых цифр.
- Поворот: *Rather than feeling threatened… they're leading adoption.*
- **We believe…** — миссия.
- **That's the [X] future we're building at [Brand].**

### Appendix

- «Take a peek behind the curtain» — разговорный вход.
- **Who** (n, сегменты) + **How** (типы вопросов) + **Bonus** stats.
- Повтор hero sample: *2,256 people*.

### Brand block (WHY TYPEFORM)

- Proof loop: *This report came from a Typeform survey* → *surveys that feel like conversations* → *Subscribe to Informed*.
- Тройное **real**: real answers, real people, real insights.

---

## 11. UX / упаковка (визуальные фишки страницы)

Даже без доступа к CSS, по структуре видно:


| Фишка                                     | Эффект                       |
| ----------------------------------------- | ---------------------------- |
| **Sample size в hero**                    | Мгновенный trust             |
| **Sticky TOC**                            | Ощущение «документа»         |
| **Pull-quote как H1 главы**               | Эмоция до аналитики          |
| **Огромная типографика %**                | Скриншотируемость в соцсетях |
| **ALL CAPS section labels**               | Ориентир при быстром скролле |
| **Чередование: stat → prose → quote**     | Не устаёт глаз               |
| **Разбивка «Nearly» / «50%» на 2 строки** | Драматургия                  |
| **Footnotes к графикам**                  | Честность методологии        |
| **Anchor links (#The-adoption-of-AI)**    | Шеринг конкретной главы      |


**Для Marquiz:** те же приёмы + уникальное — мини-схема воронки (`funnel_summary`), карта подниш, интерактивный фильтр.

---

## 12. Чеклист качества (перед публикацией)

### Структура

- 3 главы + appendix + conclusion
- У каждой главы: quote → stats → interpretation → voices → 3 takeaways
- Есть «парадокс» или контраст минимум 1 раз на главу
- Финал не вводит новых данных

### Тон

- Нет морализаторства и паники
- Есть эмпатия к «перегруженному маркетологу»
- Takeaways на «you» + императив
- Бренд говорит «we believe», не «мы лучшие»

### Данные

- n выборки в hero и appendix
- Методология в 10 предложениях
- Каждая mega-цифра с подписью
- Оговорки (multiple answers, SMB filter…)

### Engagement

- 3–5 культурных якорей года/ниши
- 4+ цитаты/голоса на отчёт
- 1 внешний якорь (рынок), не 10
- CTA один и понятный

---

## 13. Адаптация под Marquiz (недвижимость / top-5000)

### Замена «осей» Typeform → Marquiz


| Typeform     | Marquiz (пример)                                                  |
| ------------ | ----------------------------------------------------------------- |
| Adoption     | **Оффер и старт** — «35% без явного обещания»                     |
| Trust        | **Честность воронки** — форма на старте, disclosure результата    |
| Job security | **Что заменяет «длинный лендинг»** — short vs long, results 14.7% |


### Замена источника


| Typeform                | Marquiz                                                          |
| ----------------------- | ---------------------------------------------------------------- |
| Survey 2 256            | **1 242 квиза** (фильтр `niche_for_prompts = Недвижимость`, SMB) |
| Marketer/consumer takes | **Quiz take** (заголовки) + опционально 3 интервью               |
| Get Real / Typeform     | **backend.Analytic top-5000**, enriched CSV                      |


### Сохранить приёмы 1:1

- Hero 1242 + 25% SMB-базы
- 35% vs 32% (general vs price offer)
- 87% short vs long CR 4.0% vs 6.2%
- 14.7% results vs 40.6% education
- Appendix с `paths.py` и фильтрами
- CTA: шаблон / AI-генератор «Недвижимость»

### TOV Marquiz (рекомендация)

Typeform — американский conversational B2B. Для Marquiz RU:

- **На «вы»** в отчёте для рынка РФ/CIS или **на «ты»** для product-community — выбрать один раз и держать.
- Сохранить **спокойную уверенность** и **практичные takeaways**.
- Избегать канцелярита («осуществляется лидогенерация»).
- Честно: «данные топ-квизов по лидам, не A/B всех клиентов».

---

## 14. Шаблоны copy-paste

### Название отчёта

```text
[Год] [Тренд/тема]: [подзаголовок для профессии]
Пример: 2026: как устроены лидоген-квизы в недвижимости — 1 242 воронки с реальными лидами
```

### Pull-quote главы

```text
«[Прямая речь, 8–14 слов, эмоция или парадокс]»
Пример: «Большинство квизов обещают подбор — но не говорят, что именно получит человек»
```

### Opening paragraph

```text
[Контекст ниши в 1–2 предложениях]. [Почему сейчас важно]. 
Неудивительно, что [главная цифра] — при этом [контрастная цифра].
```

### Bridge в следующую главу

```text
Но [новый риск/вопрос]? [Одно предложение напряжения]. 
В следующем разделе — что показывают [другой срез данных].
```

### Key takeaway

```text
- [Глагол]. [Что сделать в панели/квизе завтра].
```

---

## 15. Антипаттерны (что убьёт «классность»)

1. **Wall of stats** — более 3 цифр подряд без прозы.
2. **Только среднее по больнице** — Typeform всегда даёт nuance; у нас не смешивать Dubai и новостройки без сегментов.
3. **Фейковые цитаты** — лучше реальные заголовки из CSV, помеченные «из выборки top-5000».
4. **Хайп про AI** без данных — у Marquiz сила в поведении квизов.
5. **10 CTA** — один основной + подписка.
6. **Скрытая методология** — без appendix доверие падает.
7. **Партнёрские промо в SMB-срезе** — у нас уже есть правило `training_bucket=SMB_leadgen`; Typeform так не делит, мы должны.

---

## 16. Следующие шаги (рабочий план)

1. Утвердить **3 оси** для отчёта «Недвижимость» (таблица §13).
2. Прогнать SQL/CSV-агрегаты под каждую ось (оффер, длина, results, подниши).
3. Собрать **12–15 Quiz take** из `top5000_quizzes_enriched.csv`.
4. Набросать лендинг по beat sheet §3 (можно в Notion / Marquiz Pages).
5. Peer review по чеклисту §12.

---

## Связанные материалы в brain

- `knowledge/products/top5000-quizzes/playbook.md`
- `knowledge/products/top5000-quizzes/insights-full.md`
- `.cursor/rules/top5000-quizzes.mdc`
- `data/reports/top5000-quizzes/structure/top5000_quizzes_enriched.csv`


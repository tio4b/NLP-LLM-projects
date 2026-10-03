### Prompt Engineering и базовая защита от Prompt Injection

- Провёл серию экспериментов с raw completion, chat templates, messages API и разными стратегиями prompting.
- Сравнил direct prompting, Chain of Thought, zero-shot и few-shot подходы на небольших задачах.
- Реализовал простой layered defense против prompt injection: detector, безопасную сборку messages и guarded helper перед вызовом модели.

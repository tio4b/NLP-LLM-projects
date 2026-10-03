# NLP / LLM Learning Projects

Часть моих личных проектов практики по nlp/llm 

## Проекты

### LLM-агент с инструментами

- Изучил путь от ручного форматирования prompt до tool calling и простого ReAct-агента.
- Разобрал работу chat templates, messages API, вызовов инструментов и передачу результатов tool calls обратно в модель.
- Реализовал учебный agent workflow с внешними инструментами и базовой логикой выбора действия.

### Prompt Engineering и базовая защита от Prompt Injection

- Провёл серию экспериментов с raw completion, chat templates, messages API и разными стратегиями prompting.
- Сравнил direct prompting, Chain of Thought, zero-shot и few-shot подходы на небольших задачах.
- Реализовал простой layered defense против prompt injection: detector, безопасную сборку messages и guarded helper перед вызовом модели.

### RAG-пайплайн с Rejection Sampling и SFT

- Собрал учебный RAG-пайплайн: chunking документов, embeddings, vector search и генерация ответа на основе найденного контекста.
- Использовал bi-encoder для retrieval, instruction-tuned генератор для ответа и reward model для оценки нескольких кандидатов.
- Реализовал rejection sampling: генерацию нескольких ответов, скоринг reward model и отбор лучшего ответа для SFT-датасета.
- Провёл короткий SFT-цикл генератора и sanity-check качества после дообучения.

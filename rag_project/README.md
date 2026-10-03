### RAG-пайплайн с Rejection Sampling и SFT

- Собрал учебный RAG-пайплайн: chunking документов, embeddings, vector search и генерация ответа на основе найденного контекста.
- Использовал bi-encoder для retrieval, instruction-tuned генератор для ответа и reward model для оценки нескольких кандидатов.
- Реализовал rejection sampling: генерацию нескольких ответов, скоринг reward model и отбор лучшего ответа для SFT-датасета.
- Провёл короткий SFT-цикл генератора и sanity-check качества после дообучения.

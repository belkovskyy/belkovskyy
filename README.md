ML Engineer. Табличный ML, LLM и RAG-системы, продакшен на Python.
Красноярск · анализ данных и NLP в РКЦ Минцифры

## Проекты

| Проект | О чём | Результат | Стек |
|---|---|---|---|
| [support-rag](https://github.com/belkovskyy/support-rag) | RAG по базе знаний поддержки с decision layer и абляциями | recall@5 0.88, MRR@10 0.74 | FAISS, LLM |
| [txt2sql](https://github.com/VanMose/txt2sql) | Командный проект вдвоём: генерация SQL на LangGraph с поиском схемы, LLM-критиком и исправлением запроса | execution accuracy 0.70 на 300 примерах Spider dev | LangGraph, Qdrant, Neo4j |
| [text2sql-guardrails](https://github.com/belkovskyy/text2sql-guardrails) | Запросы к PostgreSQL на естественном языке, SQL проверяется перед выполнением | 26 из 26 атак заблокировано против 20 из 26 у регулярных выражений | sqlparse, Ollama |
| [credit-scoring-b2b](https://github.com/belkovskyy/credit-scoring-b2b) | Скоринг юридических лиц: сравнение пяти моделей, отбор признаков, тюнинг Optuna | ROC-AUC 0.815 на лидерборде (Gini 0.63), 9 место из 70 | CatBoost, Optuna |
| [ltv-prediction](https://github.com/belkovskyy/ltv-prediction) | Прогноз GMV пользователя на 30 дней с временной валидацией | RMSLE 1.69 против 3.20 у базлайна | LightGBM, polars |
| [apparel-recsys](https://github.com/belkovskyy/apparel-recsys) | Рекомендации следующей покупки: история покупок и популярность | NDCG@100 вдвое выше популярного базлайна | polars |
| [nonferrous-export-forecast](https://github.com/belkovskyy/nonferrous-export-forecast) | Дипломная работа: прогноз помесячного экспорта меди, никеля и алюминия из России в Китай | sMAPE 17% против 37% у наивного прогноза по алюминию | ARIMA, XGBoost |
| [moex-trading-agent](https://github.com/belkovskyy/moex-trading-agent) | Торговый агент для MOEX: ML-фильтр, независимый риск-слой, walk-forward валидация | Sharpe 0.99, просадка 2.2% на бэктесте 2023-2026 | LightGBM, LLM |
| [ldpc-rate-adaptation](https://github.com/belkovskyy/ldpc-rate-adaptation) | Адаптация скорости LDPC-кода для квантового распределения ключей | квантильная регрессия QBER и политика выбора кода | LightGBM, Optuna |
| [mws-octapi-lua-agent](https://github.com/belkovskyy/mws-octapi-lua-agent) | Генерация Lua-кода локальной LLM с валидацией и автоисправлением | покрыт тестами | FastAPI, Ollama, Docker |
| [ML_projects](https://github.com/belkovskyy/ML_projects) | Учебные проекты: EDA, A/B-тесты, классический ML, NLP, CV | — | scikit-learn, PyTorch |

Ещё командный проект: [protechno-media-analyzer](https://github.com/TheAlexGrimes30/protechno-media-analyzer) — медиа-аналитика обращений, ИТ-кубок «ПроТехно», 1 место

## Стек

Python · PyTorch · scikit-learn · CatBoost · LightGBM · polars · FastAPI · PostgreSQL · Docker · LangGraph · FAISS · Qdrant · Ollama · SQL

## Контакты

belkovskyy@yandex.ru · Telegram [@vadddd](https://t.me/vadddd)

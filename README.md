# Рузель Салихов

**ML Engineer / Data Scientist · Intern / Junior**

Москва · [Telegram](https://t.me/ruzel_sali) · [Email](mailto:R89061187131@gmail.com)

Студент 3-го курса Финансового университета, «Прикладная математика и информатика»,
выпуск — 2028. Работаю с табличными данными, NLP/LLM и ML-сервисами:
подготовка данных → эксперименты → оценка качества → инференс в приложении.
Ищу стажировку или junior-позицию в ML / Data Science / NLP.

## Избранные проекты

### [PriceVision — оценка стоимости квартир](https://github.com/Ruzik707/Gazprom_project)

Самостоятельный проект ML-акселератора Газпромбанка × Финансового университета.
Собрал данные и ML-пайплайн, сравнил варианты CatBoost с текстовыми признаками,
добавил Optuna и Telegram-интерфейс с загрузкой Excel.

**Результат эксперимента:** MAPE ≈ 13.25%, R² для log(price) ≈ 0.934 на validation.
Методика и ограничения оценки раскрыты в README проекта.

`CatBoost` · `Optuna` · `bge-m3` · `PCA` · `DVC` · `aiogram`

[Сравнение моделей](https://github.com/Ruzik707/Gazprom_project#результаты-экспериментов) ·
[Код инференса](https://github.com/Ruzik707/Gazprom_project/blob/main/tg_bot/bot.py) ·
[Демо бота](https://github.com/Ruzik707/Gazprom_project/blob/main/docs/bot_demo.md)

### [SourceCraft Repo Health — объяснимый скоринг репозиториев](https://github.com/Ruzik707/SourceCraft_project)

Командный проект хакатона «Лидеры цифровой трансформации — 2026», кейс SourceCraft.
Шесть категорий, оценка 0–100, разбор факторов и рекомендации на каталоге
из **27 761 публичного репозитория**.

**Мой вклад:** EDA, feature engineering, методика скоринга и подбор весов через
Optuna (500 trials); участие в FastAPI-бэкенде и LLM-интеграции.
Сборщик и интерфейс разработали другие участники команды.

`Pandas` · `Optuna` · `FastAPI` · `SQLAlchemy` · `LLM` · `Docker Compose`

[Методика](https://github.com/Ruzik707/SourceCraft_project/blob/main/docs/methodology.md) ·
[Код скоринга](https://github.com/Ruzik707/SourceCraft_project/blob/main/scoring/normalizer.py) ·
[Примеры отчётов](https://github.com/Ruzik707/SourceCraft_project/tree/main/docs/examples)

## Дополнительные проекты

| Проект | Что показывает |
| --- | --- |
| [Tatar Text Detoxification](https://github.com/Ruzik707/NLP-Hakaton) | Подготовка и лингвистическая проверка 7 511 пар для малоресурсного NLP; участие в командном LoRA-эксперименте |
| [Speaker Recognition](https://github.com/Ruzik707/datathon-speaker-rec) | ECAPA-TDNN, аудиоэмбеддинги, FAISS, nearest-neighbour retrieval |
| [MayakBot](https://github.com/Ruzik707/MayakBot) | RAG с ChromaDB, два Telegram-сценария, LLM API и Docker Compose |
| [WB Parser](https://github.com/Ruzik707/wb-parser) | Асинхронный сбор данных, фильтрация, Excel и Telegram-уведомления |

<details>
<summary>Другие эксперименты</summary>

- [SmartSearch](https://github.com/Ruzik707/SmartSearch_LMpro) — остановленный
  эксперимент с CLIP и мультимодальным поиском товаров.
- [Cheese Shop Bot](https://github.com/Ruzik707/telegram_bot_kamil) — прототип
  Telegram-каталога для семейного бизнеса.

</details>

## Инструменты

**ML / Data:** Python, SQL, Pandas, NumPy, scikit-learn, CatBoost, Optuna.

**NLP / DL:** PyTorch, Hugging Face, Sentence Transformers, эмбеддинги, RAG.

**Разработка:** FastAPI, aiogram, Git, Docker Compose, DVC, S3, Linux.

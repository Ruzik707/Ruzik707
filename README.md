# Привет, я Рузель 👋

**ML / Data Science Intern**
Студент Финансового университета при Правительстве РФ, направление: **Прикладная математика и информатика / прикладное машинное обучение**.

Интересуюсь прикладным машинным обучением, NLP/LLM и end-to-end разработкой ML-решений: от сбора и анализа данных до обучения моделей, инференса и демо.

---

## Обо мне

* Учусь на направлении, связанном с прикладной математикой, информатикой и машинным обучением.
* Делаю проекты на стыке ML, NLP, парсинга данных и Python-автоматизации.
* Основной интерес сейчас: классический ML, табличные данные, NLP/LLM, PyTorch и ML-пайплайны.
* Усиливаю базу по ML/DL-теории, алгоритмам и подготовке к ML/Data Science стажировкам.

---

## Технологии

**ML / DL:**
Python, Scikit-learn, CatBoost, PyTorch, Hugging Face Transformers, PEFT/LoRA

**Data:**
Pandas, NumPy, SQL, JSONL, aiohttp, requests

**MLOps / Tools:**
Git, DVC, Pandera, S3, Jupyter, Google Colab, Telegram Bot API

---

## Ключевой проект

### [PriceVision / Flat Inspector](https://github.com/Ruzik707/Gazprom_project)

End-to-end ML-сервис для оценки стоимости квартир в Москве по параметрам объекта и текстовому описанию.

* Собрал пайплайн обработки данных по объявлениям о недвижимости: парсинг, очистка, EDA, feature engineering и подготовка признаков.
* Обучил `CatBoostRegressor` для предсказания логарифма цены квартиры; после Optuna tuning получил **R² ≈ 0.934** и **MAPE ≈ 13.25%** на validation.
* Добавил текстовые эмбеддинги описаний объявлений через `BAAI/bge-m3` и PCA для сокращения размерности.
* Реализовал Telegram-бота на `aiogram`: пользователь загружает Excel-шаблон с параметрами квартиры, выбирает категориальные признаки и получает оценку стоимости.
* Использовал DVC для версионирования данных, `uv` / `pyproject.toml` для зависимостей и отдельные notebook-эксперименты для EDA, feature engineering и tuning.

**Стек:** Python, Pandas, CatBoost, Optuna, Sentence Transformers, PCA, DVC, aiogram, Telegram Bot API

---

## Дополнительные проекты

### [Tatar Text Detoxification Hackathon](https://github.com/Ruzik707/NLP-Hakaton)

Командный NLP-проект в рамках хакатона «ИИ-ЗАМАН Хак» по детоксикации текста на татарском языке.

* Отвечал за data-centric часть проекта: сбор, очистку и проверку пар “токсичный текст → нейтральная формулировка”.
* Проверял корректность татарского языка, сохранение смысла и адекватность нейтрализации как носитель языка.
* Подготовил датасет из 7k+ пар текстов для экспериментов команды.
* Участвовал в исследовании LoRA fine-tuning подходов для low-resource NLP-задачи.

**Стек:** Python, JSONL, PyTorch, Hugging Face, LoRA, Unsloth

---

### [WB Product Monitoring Parser](https://github.com/Ruzik707/wb-parser)

Python-скрипт для мониторинга товарных карточек Wildberries, фильтрации предложений и экспорта результатов в Excel.

* Реализовал асинхронный сбор данных по категориям Wildberries.
* Извлекал цену, кешбэк, рейтинг, количество отзывов и ссылки на товары.
* Фильтровал товары по соотношению кешбэка и цены.
* Сохранял найденные товары в Excel для дальнейшего анализа.

**Стек:** Python, asyncio, aiohttp, Pandas, tqdm, openpyxl

---

## Сейчас прокачиваю

* Deep Learning School МФТИ: PyTorch, CNN, CV, NLP, Transformers
* Классический ML: валидация, метрики, leakage, бустинг, feature engineering
* Алгоритмы и структуры данных: LeetCode
* Подготовку к ML / Data Science стажировкам

---

## Контакты

* GitHub: [github.com/Ruzik707](https://github.com/Ruzik707)
* Telegram: [@ruzel_sali](https://t.me/ruzel_sali)
* Email: [R89061187131@gmail.com](mailto:R89061187131@gmail.com)

Открыт к ML / Data Science / NLP стажировкам.

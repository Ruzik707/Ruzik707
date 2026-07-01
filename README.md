# Привет, я Рузель 👋

**ML / Data Science Intern**
Студент Финансового университета при Правительстве РФ, направление: **Прикладная математика и информатика / прикладное машинное обучение**.

Интересуюсь прикладным ML, NLP/LLM и end-to-end разработкой ML-решений: от сбора и подготовки данных до обучения моделей, инференса и демо.

---

## Обо мне

* Учусь на программе, связанной с прикладной математикой, информатикой и машинным обучением.
* Делаю проекты на стыке ML, NLP, парсинга данных и автоматизации.
* Есть опыт работы с табличными данными, CatBoost/Scikit-learn, PyTorch, Hugging Face Transformers, DVC и Telegram Bot API.
* Прошел курс Газпром ML по end-to-end ML-пайплайнам; приглашен к участию в LLM-хакатоне Газпрома как один из сильных участников курса.
* Сейчас усиливаю базу по классическому ML, Deep Learning, алгоритмам и подготовке к ML/Data Science стажировкам.

---

## Технологии

**ML / DL:**
Python, Scikit-learn, CatBoost, PyTorch, Hugging Face Transformers, PEFT/LoRA

**Data:**
Pandas, NumPy, SQL, BeautifulSoup, requests

**MLOps / Tools:**
Git, DVC, Pandera, S3, Jupyter, Google Colab, Telegram Bot API

---

## Ключевые проекты

### PriceVision / Flat Inspector  (https://github.com/Ruzik707/Gazprom_project)

End-to-end ML-сервис для оценки стоимости квартир в Москве по параметрам объявления и текстовому описанию.

* Собрал пайплайн обработки данных по объявлениям о недвижимости: парсинг, очистка, EDA, feature engineering и подготовка признаков.
* Обучил CatBoostRegressor для предсказания логарифма цены квартиры; после Optuna tuning получил R² ≈ 0.934 и MAPE ≈ 13.25% на validation.
* Добавил текстовые эмбеддинги описаний объявлений через `BAAI/bge-m3` и PCA для сокращения размерности.
* Реализовал Telegram-бота на `aiogram`: пользователь загружает Excel-шаблон с параметрами квартиры, выбирает категориальные признаки и получает оценку стоимости.
* Использовал DVC для версионирования данных, `uv`/`pyproject.toml` для зависимостей и отдельные notebook-эксперименты для EDA, feature engineering и tuning.

**Стек:** Python, Pandas, CatBoost, Optuna, Sentence Transformers, PCA, DVC, aiogram, Telegram Bot API

---

### Tatar Text Detoxification Hackathon (https://github.com/Ruzik707/NLP-Hakaton)

Командный NLP-проект в рамках хакатона «ИИ-ЗАМАН Хак» по детоксикации текста на татарском языке.

* Отвечал за сбор, очистку и проверку качества пар “токсичный текст → нейтральная формулировка”.
* Проверял корректность татарского языка, сохранение смысла и адекватность нейтрализации как носитель языка.
* Подготовил датасет из 7к+ пар текстов для экспериментов команды.
* Участвовал в исследовании подходов к LoRA fine-tuning языковых моделей для low-resource NLP-задачи.

**Стек проекта:** Python, JSONL, PyTorch, Hugging Face, LoRA, Unsloth

---

### WB Arbitrage Parser & Alert System (https://github.com/Ruzik707/wb-parser)

Python-парсер для автоматического поиска арбитражных связок на Wildberries и отправки алертов в Telegram.

* Собирает данные по товарным карточкам: цена, отзывы, условия кешбэка.
* Фильтрует товары по правилу `cashback > price`.
* Экспортирует результаты в CSV/Excel.
* Отправляет найденные предложения в Telegram-канал.

**Стек:** Python, BeautifulSoup, requests, Pandas, Telegram Bot API

---

## Сейчас прокачиваю

* Deep Learning School МФТИ: PyTorch, CNN, CV, NLP, Transformers
* Классический ML: валидация, метрики, leakage, бустинг, feature engineering
* Алгоритмы и структуры данных: LeetCode
* Подготовку к ML/Data Science стажировкам

---

## Контакты

* GitHub: github.com/Ruzik707
* Telegram: @ruzel_sali
* Email: [R89061187131@gmail.com](mailto:R89061187131@gmail.com)

Открыт к ML / Data Science / NLP стажировкам.

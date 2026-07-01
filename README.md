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

### Real Estate Price Predictor / PriceVision (https://github.com/Ruzik707/Gazprom_project)

End-to-end проект для анализа объявлений о недвижимости и подготовки ML-пайплайна для прогнозирования цен.

* Реализован парсер объявлений с ЦИАН: цена, площадь, этаж, адрес, метро, характеристики, описание, ссылки на изображения.
* Данные сохраняются в JSONL и версионируются через DVC.
* Используются `uv`, `pyproject.toml`, структурированный `src/` и отдельные notebook-эксперименты.
* Следующий этап: EDA, feature engineering, CatBoost/LightGBM baseline, сравнение моделей и анализ ошибок.

**Стек:** Python, Pandas, BeautifulSoup, DVC, Pandera, CatBoost, S3

---

### Tatar Text Detoxification (https://github.com/Ruzik707/NLP-Hakaton)

NLP-проект по детоксификации текстов на татарском языке с сохранением исходного смысла.

* Собран датасет из 8,325 пар текстов: токсичная формулировка → нейтральная формулировка.
* Выполнен fine-tuning модели `Tweeties/tweety-7b-tatar-v24a` с использованием LoRA.
* Использовались PyTorch, Hugging Face Transformers, PEFT, TRL, Unsloth и 4-bit quantization.
* Подготовлены примеры работы модели и описание пайплайна обучения.

**Стек:** PyTorch, Hugging Face Transformers, LoRA, PEFT, TRL, Unsloth, Google Colab

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

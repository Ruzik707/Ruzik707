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

### Flat Inspector / Real Estate Price Predictor

End-to-end проект для анализа объявлений о недвижимости и подготовки ML-пайплайна для прогнозирования цен.

* Реализован парсер объявлений с ЦИАН: цена, площадь, этаж, адрес, метро, характеристики, описание, ссылки на изображения.
* Данные сохраняются в JSONL и версионируются через DVC.
* Используются `uv`, `pyproject.toml`, структурированный `src/` и отдельные notebook-эксперименты.
* Следующий этап: EDA, feature engineering, CatBoost/LightGBM baseline, сравнение моделей и анализ ошибок.

**Стек:** Python, Pandas, BeautifulSoup, DVC, Pandera, CatBoost, S3

---

### Tatar Text Detoxification

NLP-проект по детоксификации текстов на татарском языке с сохранением исходного смысла.

* Собран датасет из 8,325 пар текстов: токсичная формулировка → нейтральная формулировка.
* Выполнен fine-tuning модели `Tweeties/tweety-7b-tatar-v24a` с использованием LoRA.
* Использовались PyTorch, Hugging Face Transformers, PEFT, TRL, Unsloth и 4-bit quantization.
* Подготовлены примеры работы модели и описание пайплайна обучения.

**Стек:** PyTorch, Hugging Face Transformers, LoRA, PEFT, TRL, Unsloth, Google Colab

---

### WB Arbitrage Parser & Alert System

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









# 👋 Привет, я Рузель!

**ML / Data Science Intern** | Москва  
🎯 Ищу стажировку или Junior-позицию в ML/NLP

---

## 🚀 Обо мне
- 🎓 Финансовый университет: Прикладная математика и информатика (2022–2026)
- 🔥 Курсы: Газпром ML (end-to-end пайплайны), МФТИ Deep Learning, Stepik SQL
- 🛠 3+ проекта с production-элементами: DVC, Pandera, S3, Hugging Face deploy
- 🗣 NLP для low-resource языков: создал первый открытый датасет детоксификации татарского
- 🏆 Активный участник хакатонов, люблю решать реальные задачи

---

## 🛠 Технологии

**ML/DL:**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Hugging%20Face-FF8C00?style=for-the-badge&logo=huggingface&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-00881B?style=for-the-badge&logo=catboost&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Data & MLOps:**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/PostgreSQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Инструменты:**  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-00D4AA?style=for-the-badge&logo=python&logoColor=white)

---

## 📂 Ключевые проекты

### 🏠 [Real Estate Price Predictor](https://github.com/Ruzik707/Gazprom_project)
> End-to-end ML-пайплайн для прогнозирования цен на недвижимость  
> • Парсинг 20k+ объявлений с ЦИАН → валидация (Pandera) → версионирование (DVC) → S3  
> • Baseline CatBoost: R² = 0.86 (hold-out), в работе: текстовые эмбеддинги + категориальные фичи  
> **Стек:** Python, Pandas, CatBoost, DVC, Pandera, S3

### 🧬 [Tatar Text Detoxification](https://github.com/Ruzik707/NLP-Hakaton)
> Fine-tuning трансформеров для детоксификации текстов на татарском языке  
> • Создал первый открытый датасет: 10k+ пар «токсичный → нейтральный текст»  
> • Сравнение архитектур: mT5, ruT5, T5; train loss = 0.6, демо на Hugging Face  
> **Стек:** PyTorch, Transformers, Unsloth, Gradio  
> 🔗 [Демо](https://huggingface.co/Mochalka123/tatar-detox-merged)

### 📦 [WB Arbitrage Parser](https://github.com/Ruzik707/wb-parser)
> Парсер Wildberries с автоматическим поиском арбитражных связок  
> • 10 000+ товаров: цены, отзывы, кешбэк-условия  
> • Авто-алерты в Telegram: 100+ релевантных офферов/день  
> **Стек:** Python, BeautifulSoup, Pandas, Telegram Bot API, APScheduler

<details>
<summary>🔧 Дополнительные проекты</summary>

### 🤖 [Cheese Shop Telegram Bot](https://github.com/Ruzik707/telegram_bot_kamil)
> Бот для автоматизации заказов малого бизнеса (сыры, ИП)  
> • Каталог, поиск, оформление заказов; 100+ взаимодействий/мес  
> • Работал в production 6+ месяцев  
> **Стек:** python-telegram-bot, requests

</details>

---

## 📫 Контакты
✉️ [R89061187131@gmail.com](mailto:R89061187131@gmail.com)  
💬 [@ruzel_sali](https://t.me/ruzel_sali)  
📄 [Резюме (PDF)](https://drive.google.com/file/d/1jDJ78CMHgsnXtyz8VC1WZK0K43eo97Yu/view?usp=sharing)  

> ✨ **Открыт к предложениям**: стажировка / Junior ML Engineer / Data Scientist  
> 📍 Москва | 🔄 Готов к тестовым заданиям и собеседованиям

---

## 📊 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Ruzik707&show_icons=true&theme=github_dark&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Ruzik707&layout=compact&theme=github_dark&hide_border=true)

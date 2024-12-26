# Проект "FaceOFF"
---
## Введение

Проект **"FaceOFF"** был создан с целью упрощения процесса заблюривания объектов на изображениях и видео, что позволяет пользователям легко скрывать конфиденциальную информацию или личные данные, а также маскировать нежелательные объекты в реальном времени. Это приложение ориентировано на пользователей, которым важно защищать свою конфиденциальность и безопасности данных.

## Команда

### Наставник:
- Владимир Семенов

### Члены команды:
- **Батычков Вячеслав Геннадьевич** — КТбо1-7, Backend Developer
- **Долбин Матвей Сергеевич** — КТ6о1-7, Business Analyst
- **Лавров Даниил Эдуардович** — КТбо1-7, Frontend Developer
- **Одинцов Дмитрий Максимович** — КТбо1-7, ML-Engineer
- **Скубриев Роман Владимирович** — КТсo1-4, DevOps Engineer
- **Ягольник Даниил Сергеевич** — КТбо1-7, Fullstack Web Developer, UX/UI Designer

## О проекте

Проект **"FaceOFF"** — это веб-приложение, предназначенное для заблюривания объектов на фото/видео. Приложение позволяет пользователям выбирать объекты для блюра, а также настраивать степень и тип блюра, заменять блюр на маску и многое другое. Пользователи могут отправлять свои фотографии или видео для обработки и просматривать историю отправок.

### Основные функции:
- **Заблюривание объектов**: Пользователи могут заблюрить различные объекты на изображениях и видео.
- **Режим реального времени**: Поддержка обработки в реальном времени с использованием камеры.
- **Типы объектов**: Возможность выбора типа объекта для блюра.
- **Настройка блюра**: Выбор степени и типа блюра (размытие, пикселизация и т.д.).
- **Маска вместо блюра**: Опция замены блюра на маску.
- **Регистрация пользователей**: Пользователи могут зарегистрироваться для просмотра истории отправок и дополнительных возможностей.

### Коммерциализация:
Для использования приложения предусмотрена система токенов:
- Незарегистрированные пользователи имеют ограничения по выбору типа объектов, количеству обработок и качеству.
- Для зарегистрированных пользователей планируется расширение функционала (в том числе возможность дополнительных настроек обработки).

## Стек технологий

### Frontend:
- **React** — для создания пользовательского интерфейса.
- **JavaScript** — основной язык программирования.
- **HTML, CSS** — для оформления и разметки страниц.

### Backend:
- **Golang** — для серверной логики, обработки запросов и взаимодействия с базой данных.
- **MySQL** — база данных для хранения информации о пользователях, объектах и истории отправок.

### Искусственный интеллект:
- **Python** — основной язык для разработки AI-моделей.
- **YOLO (You Only Look Once)** — модель для детекции объектов на изображениях и видео.

## Разработка

Проект состоит из нескольких компонентов, взаимодействующих друг с другом:

1. **Frontend** отвечает за отображение интерфейса и взаимодействие с пользователем.
2. **Backend** обрабатывает запросы, работает с базой данных и управляет логикой приложения.
3. **Искусственный интеллект** используется для детекции объектов на изображениях и видео с целью их последующего блюра.
4. **DevOps** отвечает за развертывание и поддержание приложения в рабочем состоянии.

## Планируемые улучшения

- Добавление новых типов блюра и масок.
- Оптимизация AI-алгоритмов для повышения точности детекции.
- Улучшение пользовательского опыта через адаптивный интерфейс и дополнительные настройки.
- Разработка и внедрение платных подписок для пользователей с расширенным функционалом.

## Лицензия

Этот проект лицензирован под лицензией MIT. См. файл [LICENSE](LICENSE) для подробностей.

## Контрибьюции

Мы приветствуем контрибьюции! Для того чтобы предложить улучшения или исправления:

1. Форкните репозиторий.
2. Создайте новую ветку для вашего улучшения.
3. Напишите тесты и убедитесь, что они проходят.
4. Сделайте pull request.

Пожалуйста, следуйте [стилю кодирования](CONTRIBUTING.md) и убедитесь, что ваш код соответствует стандартам проекта.

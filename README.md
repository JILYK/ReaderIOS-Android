# Reader App for iOS and Android

A comprehensive eBook reader app for iOS and Android, designed for smooth performance, intuitive navigation, and multilingual support. This project includes powerful search and filter features, favorites management, and automatic language detection, making it an ideal tool for users who enjoy reading on their mobile devices.

##
![Home Screen](home_screenshot.png)

## Features

- **Instant Search with Filters**: Real-time search functionality updates results with each character typed, allowing users to find relevant content instantly. The search includes filtering options by year and issue, making it easy to narrow down results for specific editions.

  ![Search and Filter Functionality](search_filter_screenshot.png)

- **Book Reading Experience**: Books are organized as `ScriptableObject` assets, each containing images of pages, title, and cover. Pages are displayed as images, offering a unique and visually immersive reading experience.

  ![Book View](book_view_screenshot.png)

- **Favorites**: Users can add books to their favorites list, creating a personalized library for easy access to frequently read or preferred issues.

  ![Favorites Screen](favorites_screenshot.png)

- **Automatic Language Detection**: Detects the device's language on the first launch and automatically applies it. This ensures the app is accessible to a global audience without requiring manual language settings.

## How It Works

The app organizes book content and user interactions with a focus on efficiency and a smooth user experience:

1. **Real-Time Search with Year and Issue Filters**: As the user types, results are filtered instantly. Users can further refine their search by selecting specific years and issue numbers, making it easy to locate specific content.

2. **Reading Books as Images**: Each book is stored as a `ScriptableObject`, managing data like page images, titles, and covers. Pages are displayed as images, offering a visually rich reading experience.

3. **Favorites Management**: Users can mark books as favorites, saving them in a personal list for easy access to preferred issues.

4. **Multilingual Support with Auto-Detection**: Upon the first launch, the app checks the device's language settings and adjusts automatically, making the app versatile and accessible for readers worldwide without any manual language configuration.

### Example Book Data Structure

The app uses `ScriptableObject` to store book data, including page images and metadata:

- **Title**: The title of the book or magazine.
- **Cover Image**: The cover image displayed in the book list.
- **Pages**: A collection of images representing each page of the book.

## Getting Started

1. Clone the repository and open the project in Unity.
2. Customize book content by adding images and metadata to `ScriptableObject` assets.
3. Build and deploy the app for iOS and Android.

## Usage

In the app, users can:

- Search for books in real time by typing keywords and applying filters for year and issue.
- Read books with a unique page-based image display.
- Add books to their favorites list.
- Enjoy automatic language detection based on device settings for a seamless experience.

---

# Приложение для Чтения Книг на iOS и Android

Полнофункциональное приложение для чтения книг, разработанное для iOS и Android, с акцентом на производительность, удобство использования и поддержку нескольких языков. Проект включает расширенные возможности поиска, автоматическое определение языка и гибкие опции для чтения, что делает его идеальным для пользователей, которые любят читать на мобильных устройствах.

##
![Home Screen](home_screenshot.png)

## Особенности

- **Мгновенный Поиск с Фильтрами**: Обеспечивает обновление результатов поиска в реальном времени с каждым введённым символом. В поиске также доступны фильтры по году и номеру выпуска, что позволяет сужать результаты до нужных изданий.

  ![Search and Filter Functionality](search_filter_screenshot.png)

- **Чтение Книг**: Поддерживает чтение книг, представленных в виде изображений страниц, создавая уникальный опыт чтения. Использует `ScriptableObject` для управления данными книг, включая изображения страниц, названия и обложки, обеспечивая эффективное управление ресурсами и простое редактирование данных.

  ![Book View](book_view_screenshot.png)

- **Избранное**: Позволяет пользователям добавлять книги в избранное, создавая персонализированную библиотеку для быстрого доступа к любимым книгам.

  ![Favorites Screen](favorites_screenshot.png)

- **Автоопределение Языка**: Определяет язык устройства при первом запуске и автоматически применяет его. Это делает приложение удобным и доступным для глобальной аудитории без необходимости вручную настраивать язык.

## Как Это Работает

Приложение управляет контентом книг и взаимодействием с пользователем, делая акцент на простоте и эффективности:

1. **Поиск в Реальном Времени с Фильтрами по Году и Выпуску**: По мере ввода запроса результаты поиска мгновенно обновляются. Пользователи могут дополнительно уточнить результаты, выбрав конкретные годы и номера выпусков, что делает поиск удобным и точным.

2. **Чтение Книг как Изображений**: Книги организованы с помощью `ScriptableObject`, который хранит данные о страницах, названиях и обложках. Это позволяет отображать каждую страницу как изображение, создавая визуально насыщенный и увлекательный опыт чтения.

3. **Управление Избранным**: В приложении есть функция избранного, которая позволяет пользователям легко сохранять книги в список избранного для быстрого доступа в будущем.

4. **Многоязычная Поддержка с Автоопределением**: При запуске приложение проверяет настройки языка на устройстве и автоматически подстраивается, что делает приложение удобным для читателей по всему миру без необходимости настройки языка вручную.

### Пример Структуры Данных Книги

Приложение использует `ScriptableObject` для хранения данных каждой книги, включая изображения страниц и метаданные:

- **Название**: Название книги или журнала.
- **Обложка**: Изображение обложки, отображаемое в списке книг.
- **Страницы**: Коллекция изображений, представляющих каждую страницу книги.

## Начало Работы

1. Склонируйте репозиторий и откройте проект в Unity.
2. Настройте контент книг, добавив изображения и метаданные в `ScriptableObject`.
3. Соберите и разверните приложение для iOS и Android.

## Использование

В приложении пользователи могут:

- Искать книги в реальном времени, вводя ключевые слова и применяя фильтры по году и выпуску.
- Читать книги, представленные в виде изображений страниц.
- Добавлять книги в избранное.
- Наслаждаться автоматическим определением языка на основе настроек устройства для удобного опыта.

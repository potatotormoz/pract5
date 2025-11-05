# Программа для встраивания водяных знаков

Программа для скрытого встраивания произвольных файлов в качестве водяных знаков в другие файлы.

## Назначение модулей

### 1. Модуль работы с файловым диалогом (OpenFileDialog)
**Функции:**
- `string OpenFileDialog(const char* filter)`
- Отвечает за открытие системного диалога выбора файлов
- Поддерживает фильтры для типов файлов
- Возвращает полный путь к выбранному файлу

### 2. Модуль работы с файлами (File Operations)
**Функции:**
- `bool copyFile(const string& from, const string& to)`
- `void embedWatermarkToFile(const string& hostFile, const string& watermarkFile, const string& outputFile)`
- Выполняет бинарное копирование файлов
- Обеспечивает встраивание водяных знаков в конец файлов
- Добавляет маркер для последующего извлечения

### 3. Модуль пользовательского интерфейса (UI)
**Функции:**
- Основная функция `main()`
- Управляет потоком выполнения программы
- Выводит информацию о файлах и процессе работы
- Обрабатывает пользовательский ввод

<img width="884" height="945" alt="Image" src="https://github.com/user-attachments/assets/f66f18ed-c7c7-441c-8c42-5874935ff915" />

<img width="1004" height="758" alt="Image" src="https://github.com/user-attachments/assets/f3f2fd51-4879-45c4-a9e9-b962eb1b79e7" />
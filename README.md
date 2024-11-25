# Динамическое ценообразование для интернет-магазина 

Программа предназначена для автоматизации процессов мониторинга цен конкурентов, расчета оптимальных цен, а также их выгрузки в систему 1С. Она помогает интернет-магазинам бытовой техники эффективно конкурировать, снижая затраты времени и минимизируя ошибки при ценообразовании.

## Основные функции программы:

1. **Получение данных из 1С:**
   - Загружаются данные о наличии товаров на складах поставщиков и собственных складах.

2. **Сопоставление товаров:**
   - Производится автоматическое сопоставление данных о товарах из 1С с товарами, представленными на Яндекс.Маркете.

3. **Фильтрация запрещенных товаров:**
   - Исключаются товары с минимальной розничной ценой (МРЦ), для которых изменение цены невозможно.

4. **Получение данных о конкурентах:**
   - Собираются данные о товарах и ценах конкурентов двумя способами:
     - Через API Яндекс.Маркета.
     - С использованием парсинга прайс-листов (Price Labs).

5. **Анализ цен конкурентов:**
   - Определяются минимальные и максимальные цены на каждый товар среди конкурентов.

6. **Изменение цен:**
   - Рассчитывается новая цена для товаров, учитывая минимальный разрешенный порог рентабельности.

7. **Формирование аналитики:**
   - Генерируется аналитическая информация по ценам конкурентов и товарным категориям.

8. **Выгрузка данных в 1С:**
   - Обновленные цены загружаются обратно в систему 1С.

## Используемые технологии:
- **Язык программирования:** Python.
- **Библиотеки:**
  - `pandas` и `numpy` для работы с таблицами и анализа данных.
  - `requests` для работы с API Яндекс.Маркета.
- **Методы обработки данных:**
  - Чтение и парсинг CSV-файлов.
  - Обработка данных из API и прайс-листов.
  - Генерация отчетов в текстовом формате.

## Преимущества использования программы:
- Автоматизация сложных процессов ценообразования.
- Повышение конкурентоспособности интернет-магазина.
- Сокращение времени на ручной расчет цен.
- Возможность гибкого управления ценами и анализа конкурентов.



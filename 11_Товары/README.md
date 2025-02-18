# Папка 11_Товары

В этой папке содержится информация, описывающая **потребительские товары** и иные предметы массового использования. Для создания подробных описаний товаров рекомендуется использовать шаблон `TEMPLATE.md`.

## Содержание информации о товарах

Здесь размещаются подробные описания различных товаров, включая:

- **Продукты питания:** Описание донк-покетов, напитков, сигарет, алкоголя и прочих продуктов потребления.
- **Бытовые товары:** Описание гаджетов, одежды, инструментов и других предметов повседневного использования.
- **Медицинские препараты, фармацевтика:** Описание лекарственных средств и препаратов (если они не описаны в разделе "Технологии").

Для описания каждого товара рекомендуется использовать файл `TEMPLATE.md`, скопировав его содержимое и заполнив соответствующие разделы.

## Рекомендации по структурированию информации

Использование строгой структуры категорий внутри Markdown файлов (с заголовками и подзаголовками, как показано в `TEMPLATE.md`) является лишь **рекомендацией** для обеспечения единообразия и удобства чтения.

## Обязательная структура хранения

Для лучшей организации информации **каждый товар** **должен** иметь **свою собственную папку**.

Внутри каждой папки **обязательно** должен лежать `.md`-файл с основным содержанием описания товара, а также файл `design_document.md`, описывающий концепцию данного товара. Дополнительно может присутствовать папка `images/`, где хранятся все связанные изображения. Если товар выпускается конкретной корпорацией, рекомендуется делать ссылки на соответствующую папку в разделе `04_Корпорации`. Для дополнительных статей, углубляющих описание отдельных аспектов товара (например, варианты рецептов или модификации), не требуется следование `TEMPLATE.md` и создание `design_document.md`.

## Обязательное дополнение - design_document.md

Для каждой основной статьи о товаре **обязательно** создание файла `design_document.md` в корневой папке соответствующего товара. Этот документ служит для описания концепции, истории и основных принципов данного товара, а также вариантов его возможного отражения в игре.

## 📁 Структура хранения материалов

```
[Категория_товаров]/
├── images/
│   ├── [изображение_1].png
│   └── [изображение_2].jpg
├── design_document.md
├── [Название_товара]
│   ├── images/
│   │   ├── [изображение_1].png
│   │   └── [изображение_2].jpg
│   ├── [Название_подстатьи].md
└── [Название_товара].md
```

- `[Категория_товаров]/` - корневая папка с информацией о конкретной категории товаров.
- `[Название_товара]/` - внутренняя папка для дополнительных статей о конкретном товаре.
- `images/` - подпапка для изображений, относящихся к данным товарам (необязательно).
- `design_document.md` - документ, описывающий концепцию и принципы, лежащие в основе данно категории товаров (обязательно).
- `[Категория_товаров].md` - основной файл с подробным описанием категории товаров, созданный на основе `TEMPLATE.md`.
- `[Название_товара].md` - дополнительный файл с подробным описанием второстепенной информации, не относящейся к основной статье. Может не придерживаться `TEMPLATE.md`.

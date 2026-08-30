# Данные: Online Retail II

Реальные транзакционные данные британского онлайн-ритейлера подарочных товаров
за 2009-2011 гг. (~1 млн транзакций). Есть повторные покупки, что позволяет строить
полноценный когортный анализ Retention.

Колонки: `Invoice`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `Price`,
`Customer ID`, `Country`.

## Откуда скачать

UCI Machine Learning Repository — **"Online Retail II"**:
https://archive.ics.uci.edu/dataset/502/online+retail+ii

## Как разместить

Скачайте датасет и положите его в эту папку под именем **`online_retail_II.csv`**
(`Project_2/data/online_retail_II.csv`).

> Оригинал распространяется в формате `.xlsx` с двумя листами (2009-2010 и 2010-2011).
> Объедините листы и сохраните в единый CSV `online_retail_II.csv`.

> Сам CSV не хранится в git (см. `.gitignore` в корне репозитория).

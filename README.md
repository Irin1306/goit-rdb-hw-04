# Brazilian E-Commerce Dataset

## Dataset

- **Назва:** Brazilian E-Commerce Public Dataset by Olist
- **Формат:** CSV
- **Джерело:** Kaggle
- **Kaggle dataset:** `olistbr/brazilian-ecommerce`
- **Спосіб отримання:** Dataset was downloaded using KaggleHub
- **Кількість файлів:** 6 CSV files

| Файл | Кількість рядків |
|---|---:|
| `olist_customers_dataset.csv` | 99,441 |
| `olist_orders_dataset.csv` | 99,441 |
| `olist_order_items_dataset.csv` | 112,650 |
| `olist_products_dataset.csv` | 32,951 |
| `olist_sellers_dataset.csv` | 3,095 |
| `olist_order_reviews_dataset.csv` | 99,224 |
| **Разом** | **446,802** |

## Dataset Files

CSV-файли не зберігаються в GitHub-репозиторії через обмеження розміру файлів.

Датасет доступний на Kaggle:

https://www.kaggle.com/olistbr/brazilian-ecommerce

Для отримання файлів через Python використовується `KaggleHub`:

```python
import kagglehub

dataset_dir = kagglehub.dataset_download(
    "olistbr/brazilian-ecommerce"
)

print(dataset_dir)
```  

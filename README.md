# SIB-Project3

#### Project ETL sederhana melakukan migrasi Tabel dari Database Marketplace ke Data Warehouse

### Background Project 

Tim data analyst membutuhkan tabel untuk membuat dashboard terkait detail order dari data source yang ada di database production `marketplace`, Anda sebagai data engineer di minta untuk membuat script data migrasi dari tabel source tersebut ke data warehouse, sehingga tim data analyst bisa menggunakan table dari data warehouse tanpa membebankan database production marketplace.

### Goal Project

Membuat tabel di data warehouse dengan schema yang sudah ditentukan oleh user (tim data analyst).

### Requirement Kolom

Berikut adalah schema yang dibutuhkan oleh tim data analyst:
- `order_id` (INT): Not Null
- `order_date` (DATE): Not Null
- `user_id` (INT): Not Null
- `payment_name` (VARCHAR(255))
- `shipper_name` (VARCHAR(255))
- `order_price` (INT)
- `order_discount` (INT)
- `voucher_name` (VARCHAR(255))
- `voucher_price` (INT)
- `order_total` (INT)
- `rating_status` (VARCHAR(255))
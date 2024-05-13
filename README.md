# Kimia Farma Business Performance Analysis 2020-2023

### Introduction
Project ini bertujuan untuk membuat Dashboard berdasarkan data mentah penjualan produk Kimia Farma pada periode tertentu. 
Data mentah tersebut terdiri dari empat dataset yakni, kf_final_transaction.csv, kf_inventory.csv, kf_kantor_cabang.csv, dan kf_product.csv.
Data mentah tersebut diolah mulai dari awal hingga akhir untuk mencari hubungan dan memanipulasi antar data, hingga termuat hasil sesuai dengan yang diinginkan. 

### Data Overview and Description
| Mandatory Column        | Description                                                            |
|-------------------------|------------------------------------------------------------------------|
| `transaction_id`        | kode id transaksi.                                                     |
| `branch_id`             | Kode id cabang Kimia Farma.                                            |
| `branch_name`           | Nama cabang Kimia Farma.                                               |
| `kota`                  | Kota cabang Kimia Farma.                                               |
| `provinsi`              | Provinsi cabang Kimia Farma.                                           |
| `rating_cabang`         | penilaian konsumen terhadap cabang Kimia Farma.                        |
| `customer_name`         | Nama customer yang melakukan transaksi.                                |
| `product_id`            | Kode product obat.                                                     |
| `product_name`          | Nama produk.                                                           |
| `actual_price`          | Harga obat.                                                            |
| `discount_percentage`   | Persentase diskon yang diberikan pada obat.                            |
| `persentase_gross_laba` | Persentase laba yang seharusnya diterima dari obat.                    |
| `nett_sales`            | Harga setelah diskon.                                                  |
| `nett_profit`           | Keuntungan yang diperoleh Kimia Farma.                                 |
| `rating_transaksi`      | penilaian konsumen terhadap transaksi yang dilakukan.                  |

Variable `persentase_gross_laba` ditentukan berdasarkan :
| Harga                  | Persentase Laba |
|------------------------|-----------------|
| <= Rp50.0000           | 10%             |
| Rp50.0000 - Rp100.000  | 15%             |
| Rp100.0000 - Rp300.000 | 20%             |
| Rp300.0000 - Rp500.000 | 25%             |
| > Rp500.000            | 30%             |

### Processing

#### Data Understanding, Data Exploration and Data Preprocessing
- **Load the Data**: Read the CSV file containing the customer behavior data.
- **Data Cleaning**: Handle missing values, duplicate data, outliers, and feature encoding.
- **Data Transformation**: Transform the data into a suitable format for analysis.

#### Overview Datasets
<img width="1512" alt="Screenshot 2024-05-13 at 07 19 09" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/41256b66-f1b9-41a0-aca6-8e3c856cc7eb">
<img width="1512" alt="Screenshot 2024-05-13 at 07 19 18" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/65489ff4-22cb-4ae5-91b9-de56a5348bdd">
<img width="1510" alt="Screenshot 2024-05-13 at 07 22 30" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/9909b239-3917-4f5a-9542-a9f0e8e86ad8">
<img width="1512" alt="Screenshot 2024-05-13 at 07 22 41" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/7b85e6a3-5ce8-481a-9f88-06fb70b3cde2">

#### Adding Analysis Performance Dataset
<img width="1512" alt="Screenshot 2024-05-13 at 07 17 02" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/d55e287f-09df-4a35-8384-856f19cb6695">

#### Make an Analysis Table
- **Analysis Table**: Based on the aggregation results of the four tables.
- **Data Visualization**: Make table contains mandatory columns.

### Overview Tables
<img width="1512" alt="Screenshot 2024-05-13 at 07 17 46" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/6c44a73e-12a6-4e15-8ec0-b2209400fcf6">
<img width="1512" alt="Screenshot 2024-05-13 at 07 18 01" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/5050f55e-e2b0-462e-b83e-144a5fa52635">
<img width="1512" alt="Screenshot 2024-05-13 at 07 18 18" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/96090156-0437-4016-a1c7-6f1d0467597b">
<img width="1512" alt="Screenshot 2024-05-13 at 07 18 32" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/1cf243a5-66c9-4899-b982-bdfe92bbbc4c">

#### Create Dashboard (Contains)
- **Determine Dashboard Title**
- **Summary of Dashboard**
- **Filter Dashboard**
- **Snapshot Data**
- **Income Comparison of Kimia Farma year to year**
- **Top 10 Total transaction provincial branch**
- **Top 10 Nett Sales Provincial Branch**
- **Top 5 Branches with the Highest Ratings, but Ratings Lowest Transactions**
- **Indonesia's Geo Map for Total Profit for Each Province**

#### Overview Dashboard
<img width="1058" alt="Screenshot 2024-05-13 at 22 06 45" src="https://github.com/nijmafyd/Performance_Analytics_Kimia_Farma/assets/146143788/2701514b-27e3-4223-a393-c92c955e8560">

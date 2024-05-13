# Kimia Farma Business Performance Analysis 2020-2023

### Introduction
Project ini bertujuan untuk membuat Dashboard berdasarkan data mentah penjualan produk Kimia Farma pada periode tertentu. 
Data mentah tersebut terdiri dari empat dataset yakni, kf_final_transaction.csv, kf_inventory.csv, kf_kantor_cabang.csv, dan kf_product.csv.
Data mentah tersebut diolah mulai dari awal hingga akhir untuk mencari hubungan dan memanipulasi antar data, hingga termuat hasil sesuai dengan yang diinginkan. 

### Data Overview and Description
| Mandatory Column        | Description                                                            |
|-------------------------|------------------------------------------------------------------------|
| `transaction_id'        | kode id transaksi.                                                     |
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

#### Make an Analysis Table
- **Analysis Table**: Based on the aggregation results of the four tables.
- **Data Visualization**: Make table contains mandatory columns.

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

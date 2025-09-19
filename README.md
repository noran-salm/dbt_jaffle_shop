# dbt Jaffle Shop Project

This project is a **dbt (data build tool)** demo based on the [Jaffle Shop tutorial](https://docs.getdbt.com/guides).  
It shows how to transform raw data from a simple e-commerce business (Jaffle Shop) into analytics-ready tables in **Snowflake** (or any supported warehouse).

---

## 📂 Project Structure
jaffle_shop_project/
├── models/
│ ├── staging/ # Staging models: clean and prepare raw source data
│ ├── marts/ # Business logic models (customers, orders, payments)
│ └── schema.yml # Model tests & documentation
├── seeds/ # Example CSV files (raw data)
├── dbt_project.yml # Main dbt project config
└── README.md # Project documentation

---

## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/jaffle_shop_project.git
   cd jaffle_shop_project
##   Run dbt commands   
dbt debug        # Test connection
dbt seed         # Load seed CSVs
dbt run          # Build models
dbt test         # Run tests
dbt docs generate && dbt docs serve

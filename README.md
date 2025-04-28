# Terraform Azure Resources

## 📌 Available Terraform Resource Codes

The following Terraform resource configurations are included in this repository:

- **Resource Group (`RG`)**
- **Storage Account (`Storage AC`)**
- **Remote Backend Configuration**
- **Virtual Network (`VNET`)**
- **Subnet (`SUBNET`)** (Uses `dynamic` blocks)
- **Meta-arguments** (`for_each`, `depends_on`)
- **Virtual Machine

## 🛠 Features Implemented

✅ **Used `for_each` for Resource Iteration:**  
   - Allows creation of multiple resources dynamically.  
   - Example: Creating multiple Virtual Networks or Resource Groups dynamically.  

✅ **Utilized `dynamic` Blocks for Subnet Configuration:**  
   - Helps in defining multiple subnets without manually writing each block.  
   - Improves scalability and maintainability of the code.  

✅ **Implemented Remote Backend Storage:**  
   - Ensures Terraform state is stored securely in **Azure Storage**.  
   - Supports **state locking and collaboration**.  

---

## 📌 Usage Instructions

1️⃣ **Clone the Repository:**  
   ```bash
   git clone <repository-url>
   cd <repository-folder>

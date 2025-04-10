# Products--Database

A **Tkinter-based GUI application** for managing product sales records. Stores product details (name, price, quantity, category, and sale date) and supports basic CRUD operations via a user-friendly interface.  

**Key Features:**  
- 📋 **Treeview Table**: Displays product records with columns: *ID, Name, Sale Date, Price, Quantity, Category*.  
- ➕ **Add/Edit Entries**:  
  - Input fields for product name, price, quantity.  
  - Dropdown (`Combobox`) for categories.  
  - Date picker (`DateEntry`) for sale dates.  
- 🗑️ **Delete Records**: Remove selected entries.  
- 📅 **Date Handling**: Automatically sets today’s date for new entries.  

**Tech Stack:**  
- Python (`tkinter`, `ttk`)  
- `tkcalendar` for date selection  
- SQLite/PostgreSQL (implied by `db_products.models.Product`, though not visible in the snippet)  

**Use Cases:**  
- Small business sales tracking  
- Inventory management with date-based filtering  
- Learning GUI development with Python  

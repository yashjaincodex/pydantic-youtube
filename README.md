# **Pydantic Series**

Welcome to the **Pydantic Series** repository!  
This playlist is designed to take you from the **basics of Python data validation** to building **production-ready models** using Pydantic.

You’ll learn everything from simple model creation to advanced features like validators, computed fields, nested models, and environment-based settings.

Each video includes hands-on examples to help you use Pydantic in real-world applications.

---

## 🐍 **Install Python Using Miniconda / Miniforge**

To ensure your Pydantic projects stay clean and maintainable, it is recommended to use **conda environments**.

Follow the steps below to install Miniforge and set up your environment.

---

### 🔗 **Download Miniforge for macOS (ARM64)**

Download from the official repository:  
https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh

---

### 💻 **Install Miniforge**

Run:

```bash
chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh
sh ~/Downloads/Miniforge3-MacOSX-arm64.sh
source ~/miniforge3/bin/activate
```

---

### 🧱 **Create a project-specific conda environment**

```bash
conda create --prefix ./env python=3.13
conda activate ./env
```

---

### 📦 **Install packages from requirements.txt**

```bash
pip install -r requirements.txt
```

Your Pydantic environment is ready! ⚡
Start validating and structuring your Python data like a pro.

---

# **📺 Playlist Breakdown**

### **1. Basics of Pydantic — Write Your First Pydantic Models**

-   Creating your first `BaseModel`
-   Type-driven validation
-   Serialization & deserialization basics

---

### **2. Mixing Typing Module with Pydantic**

-   Using `List`, `Dict`, `Optional`, `Union`, etc.
-   Benefits of Python type hints in data validation

---

### **3. How to Use `Field()` for Validation**

-   Adding constraints: `min_length`, `gt`, `lt`, `pattern`, etc.
-   Adding metadata: titles, descriptions, examples

---

### **4. Using `@field_validator` & `@model_validator`**

-   Field-level custom validation
-   Model-level pre/post validation
-   Cleaner, reusable validation logic

---

### **5. Using `@computed_field` in Pydantic**

-   Creating dynamic fields from existing data
-   Practical examples: full names, totals, formatting

---

### **6. Handling `ValidationError`**

-   Understanding error structures
-   Returning readable error messages
-   Debugging invalid payloads effectively

---

### **7. Working with Nested Models**

-   Embedding models inside each other
-   Validating complex JSON structures
-   Best practices for hierarchical data

---

### **8. Using `model_dump()` & `model_dump_json()`**

-   Converting models to dicts & JSON
-   Including/excluding fields
-   Handling field aliases

---

### **9. Using `default_factory`**

-   Creating dynamic default values
-   Avoiding mutable default issues

---

### **10. Using `Annotated` in Pydantic**

-   Cleaner constraints using `Annotated`
-   Combining typing + validation metadata

---

### **11. Using Pydantic-Settings**

-   Managing application settings
-   Loading environment variables & `.env`
-   Structuring configs for real applications

---

# **📄 requirements.txt**

```
pydantic
pydantic-settings
python-dotenv
notebook
```

---

# **🤝 Contributing**

Got ideas, suggestions, or improvements?
Feel free to open an issue or submit a pull request.

---

# **📜 License**

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

# **📬 Stay Connected**

-   [YouTube Channel](https://www.youtube.com/@yashjaincodex)
-   [LinkedIn](https://www.linkedin.com/in/yashjaincodex)

---

Thank you for checking out the **Pydantic Series**!
Happy validating and modeling your data with Pydantic 🚀

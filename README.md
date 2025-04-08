# 🧠 Pydantic Crash Course

Welcome to my crash course on [Pydantic](https://docs.pydantic.dev/)!  
If you're working with **FastAPI**, **data validation**, or **clean Python code**, this guide is for you.  
This repo breaks down the most important concepts with **code examples** you can run.

---

## 📦 What You'll Learn

- ✅ Creating Models
- 🧠 Data Validation
- 🧬 Type Hints & Field Types
- ⚠️ Custom Validators
- 🔗 Root Validators
- 🧃 JSON Serialization / Deserialization
- 🧱 Nested Models
- 🧩 Enum Fields
- 🪝 Field Aliases
- 🔥 Real-life challenges

---

## 🧑‍💻 Start Learning

| Lesson | Description |
|--------|-------------|
| [01_basic_model.py](01_basic_model.py) | Creating your first model |
| [02_field_types.py](02_field_types.py) | Exploring common field types |
| [03_validators.py](03_validators.py) | Custom field validation |
| [04_root_validator.py](04_root_validator.py) | Cross-field validation |
| [05_enums.py](05_enums.py) | Using enums with Pydantic |
| [06_aliases.py](06_aliases.py) | Field aliasing and renaming |
| [07_serialization.py](07_serialization.py) | JSON, dict, and parsing |
| [08_custom_errors.py](08_custom_errors.py) | Better error messages |
| [09_nested_models.py](09_nested_models.py) | Models inside models |
| [10_final_challenges.py](10_final_challenges.py) | Practice problems |

---

## 💡 Tip

Clone this repo and try running the files yourself.  
If you're stuck, check the comments in the `.py` files or raise an issue!

---

## 📚 Resources

- [Pydantic Docs](https://docs.pydantic.dev/latest/)
- [FastAPI (uses Pydantic)](https://fastapi.tiangolo.com/)
- [Python Type Hints](https://peps.python.org/pep-0484/)

---

## 🙌 Author

**Md Abdullah Al Mamun**  
Backend Developer • Scraper • Competetive Programmer  
Let's connect on [GitHub](https://github.com/mamun700263) or Follow me on [Medium](https://medium.com/@mamun700263)

---

## 📘 Tutorial

### 1. What is Pydantic?

Pydantic is a Python library for **data validation and settings management** using Python type annotations.  
It helps you write clean, readable, and safe code by turning Python classes into powerful data validators.

So that no naughty data type can play with your object's emotions 😤💔

Whether you’re building APIs, working with user input, or just hate unexpected bugs — Pydantic’s got your back.




---

### 2. Installing Pydantic

Just like other Python packages, you can easily install Pydantic using `pip`.  
But before that, you *must* have a virtual environment. I hope you already know how to create one —  
but if you don’t, your brother’s got you 👇

```bash
# Create a virtual environment
python3 -m venv your_env_name

# Activate it
source your_env_name/bin/activate       # for Linux/macOS
your_env_name\Scripts\activate          # for Windows
```

Now it’s time to say the **three magical words** to your terminal and summon the Pydantic powers:

```bash
pip install pydantic
```

If you want the latest version (Pydantic v2+), just make it explicit:

```bash
pip install "pydantic>=2.0"
```


---
### Let's write the first *pydentic* model

Creating a model is just the same as you do in other cases , Just inherit a premade model from pydentic, and write you logic to finish your job.



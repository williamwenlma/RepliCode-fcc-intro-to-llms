# RepliCode-fcc-intro-llms 🚀  
**Replicate + Project: Create a LLM from Scratch with Python - Tutorial**  

---

## 📜 Project Source 复现项目来源  
- YouTube Tutorial: [How to Build a Large Language Model from Scratch (freecodecamp.org)](https://www.youtube.com/watch?v=UU1WVnMk4E8)  

---

## 🎯 Project Description 项目描述  
Learn how to build your own large language model (LLM) from scratch. This course dives into:  
**数据预处理** | ​**数学原理** | ​**Transformer架构** | ​**Python实战**  
你将使用Python实现一个完整的LLM，涵盖数据处理、模型训练和推理全流程。  

---

## 🐍 Python Version 版本要求  
- ​**Use Python 3.10.9** (Recommended)  
  ⚠️ ​**Why not 3.11/3.12?**  
  - Compatibility issues with `pylzma` (常见错误: `ModuleNotFoundError: No module named 'distutils.msvccompiler'`)

---

## ⚙️ Setup Guide 环境配置  

### Step 1: Create Virtual Environment 创建虚拟环境  
```bash
# Open Anaconda Prompt
cd Desktop
cd "Python Testing"
mkdir fcc-gpt-course
python -m venv cuda
cuda\Scripts\activate
pip3 install matplotlib numpy pylzma ipykernel jupyter

⚠️ ​If pylzma installation fails:

Download ​Visual Studio Build Tools: https://visualstudio.microsoft.com/visual-cpp-build-tools/
During installation:
Select ​**"Desktop development with C++"**
Add ​**".NET desktop build tools"**
Retry pip install pylzma.

### Step 2: Install PyTorch 安装PyTorch
pip3 install torch --index-url https://download.pytorch.org/whl/cu118
🔗 Get the latest PyTorch command:https://pytorch.org/get-started/locally/


<h1 align="center">Disk Scheduling Algorithms Simulator</h1>
<p align="center"><em>🚀 Explore Disk Scheduling in Action — A Powerful Visualization Platform to Understand, Compare, and Experiment with Algorithms like FCFS, SSTF, SCAN, C-SCAN, and LOOK for Enhanced Learning and Research</em></p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/GUI-CustomTkinter-FF6B35?style=for-the-badge&logo=tkinter&logoColor=white" alt="CustomTkinter">
  <img src="https://img.shields.io/badge/Visualization-Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib">
</p>

---

## 📋 Overview

<div align="center">
  <img src="https://img.shields.io/badge/Educational-Research Tool-FF9800?style=for-the-badge&logo=microscope&logoColor=white" alt="Research Tool">
  <img src="https://img.shields.io/badge/Operating-Systems-2196F3?style=for-the-badge&logo=linux&logoColor=white" alt="Operating Systems">
  <img src="https://img.shields.io/badge/Performance-Analysis-9C27B0?style=for-the-badge&logo=analytics&logoColor=white" alt="Performance Analysis">
</div>

**Disk Scheduling Algorithms Simulator** is a comprehensive educational and analytical tool designed to **demonstrate, 
compare, and visualize various disk scheduling algorithms used in modern operating systems**. 
This interactive suite provides both terminal-based and graphical interfaces for understanding how different 
scheduling strategies optimize disk I/O performance.

---

## ✨ Features

<div align="center">

| 🔧 Interactive Simulation                                    | 🎨 Advanced UI/UX                                              |
| ------------------------------------------------------------ | -------------------------------------------------------------- |
| ✅ Multi-Algorithm Support: 6 scheduling algorithms           | ✅ Rich Terminal Interface: Colorized output with progress bars |
| ✅ Dynamic Parameter Input: Customizable track configurations | ✅ Graphical GUI: Modern CustomTkinter interface                |
| ✅ Real-time Visualization: Animated disk head movement       | ✅ Data Visualization: Professional matplotlib charts           |
| ✅ Performance Metrics: Seek time and distance analysis       | ✅ Error Handling: Comprehensive input validation               |

</div>

---

## 🧮 Algorithms Implemented

<div align="center">
  
| Algorithm     | Full Name                | Strategy                | Time Complexity | Best Use Case               |
| ------------- | ------------------------ | ----------------------- | --------------- | --------------------------- |
| 🎯 **FCFS**   | First-Come, First-Served | Sequential processing   | O(n)            | Simple, fair scheduling     |
| ⚡ **SSTF**    | Shortest Seek Time First | Greedy nearest-first    | O(n²)           | Minimize seek time          |
| 🛗 **SCAN**   | Elevator Algorithm       | Bidirectional sweep     | O(n)            | Heavy load systems          |
| 👀 **LOOK**   | Look Algorithm           | Optimized SCAN          | O(n)            | Efficient boundary handling |
| 🔄 **C-SCAN** | Circular SCAN            | Unidirectional circular | O(n)            | Uniform response time       |
| 🎯 **C-LOOK** | Circular LOOK            | Optimized C-SCAN        | O(n)            | Best overall performance    |

</div>

---

## 💻 System Requirements

<div align="center">

🛠️ Development Environment

<table align="center">
<tr>
<td align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python" alt="Python 3.8+"><br>
  <strong>Python 3.8+</strong><br>
  <em>Core runtime environment</em>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/OS-Cross Platform-success?style=for-the-badge&logo=windows" alt="Cross Platform"><br>
  <strong>Cross-Platform</strong><br>
  <em>Windows, macOS, Linux</em>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/GUI-Desktop Environment-orange?style=for-the-badge&logo=desktop" alt="Desktop"><br>
  <strong>Desktop Environment</strong><br>
  <em>For GUI components</em>
</td>
</tr>
</table>

</div>

---

## 📦 Dependencies

<div align="center">

🔧 Required Libraries

| 📊 Visualization & UI                         | 🎨 Enhancement Libraries              |
| --------------------------------------------- | ------------------------------------- |
| `matplotlib>=3.5.0` – Data visualization      | `tqdm>=4.64.0` – Progress bars        |
| `rich>=12.0.0` – Terminal formatting          | `colorama>=0.4.4` – Terminal colors   |
| `customtkinter>=5.0.0` – Modern GUI framework | `CTkMessagebox>=2.0.0` – GUI dialogs  |
| `Pillow>=9.0.0` – Image processing            | `numpy>=1.21.0` – Numerical computing |

</div>

--- 

## 🚀 Installation

<div align="center">
  <img src="https://img.shields.io/badge/Setup-Quick & Easy-brightgreen?style=for-the-badge&logo=rocket" alt="Quick Setup">
</div>

### Step 1: Clone the Repository
  ```bash
  git clone https://github.com/icodecedd/disk-scheduling.git
  cd disk-scheduling
  ```
### Step 2: Create Virtual Environment (Recommended)
  ```bash
  # Create virtual environment
  python -m venv disk_scheduler_env
  
  # Activate virtual environment
  # On Windows:
  disk_scheduler_env\Scripts\activate
  # On macOS/Linux:
  source disk_scheduler_env/bin/activate
  ```

### Step 3: Install Dependencies
  ```bash
  # Install all required packages
  pip install matplotlib rich tqdm colorama customtkinter pillow CTkMessagebox numpy
  
  # Or install from requirements file (if available)
  pip install -r requirements.txt
  ```

### Step 4: Verify Installation
  ```bash
  python -c "import matplotlib, rich, customtkinter; print('✅ All dependencies installed successfully!')"
  ```
---

## 🤝 Contributing

<div align="center">
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge&logo=git" alt="Contributions Welcome">
</div>

<div align="center">

We enthusiastically welcome contributions from the community! Here's how you can help improve this project:

| 🔧 Development Contributions                                  | 📚 Documentation & Education                           | 🐛 Quality Improvements                                   | 🎯 Feature Requests                                    |
| ------------------------------------------------------------- | ------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------ |
| 🆕 New Algorithms: Implement additional scheduling algorithms | 📖 Tutorials: Create step-by-step learning guides      | 🔍 Bug Reports: Identify and report issues                | 🔮 New Features: Suggest innovative functionality      |
| 🎨 UI Improvements: Enhance user interface and experience     | 🎥 Examples: Add practical use-case demonstrations     | ✨ Code Quality: Refactor and improve code structure       | 🎨 Visualization: Propose new chart types and displays |
| ⚡ Performance: Optimize existing algorithm implementations    | 🔍 Analysis: Provide performance comparison studies    | 🛡️ Security: Enhance input validation and error handling | ⚙️ Configuration: Add customization options            |
| 🧪 Testing: Expand test coverage and validation               | 🌐 Translations: Localize documentation and interfaces | 📊 Analytics: Improve performance metrics and reporting   | 🚀 Performance: Suggest optimization strategies        |

</div>

### Contribution Process

1. **Fork** the repository to your GitHub account
2. **Clone** your fork locally (`git clone https://github.com/icodecedd/disk-scheduling.git`)
3. **Create** a feature branch (`git checkout -b feature-name`)  
4. **Commit** your changes (`git commit -m "Add: Enhanced SSTF algorithm with batch processing"'`)  
5. **Push** to your branch (`git push origin feature-name`)  
6. **Open** a Pull Request  

---

<div align="center">
  <h3>🎓 Designed for Academic Learning & OS Concepts 🎓</h3>

  <p>
    <img src="https://img.shields.io/badge/Focus-Academic%20Learning-blue?style=for-the-badge" alt="Academic Learning">
    <img src="https://img.shields.io/badge/Focus-Operating%20Systems-yellow?style=for-the-badge" alt="Operating Systems">
  </p>

  <p>
    <strong>Track Project Engagement:</strong>
  </p>

  <p>
    <a href="https://github.com/icodecedd/disk-scheduling/stargazers">
      <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/icodecedd/disk-scheduling?style=social">
    </a>
    <a href="https://github.com/icodecedd/disk-scheduling/network/members">
      <img alt="GitHub forks" src="https://img.shields.io/github/forks/icodecedd/disk-scheduling?style=social">
    </a>
    <a href="https://github.com/icodecedd/disk-scheduling/watchers">
      <img src="https://img.shields.io/github/watchers/icodecedd/disk-scheduling?style=social&logo=eye&color=green" alt="GitHub Watchers">
    </a>
  </p>
  
  <p>
    <em>"Understanding disk scheduling algorithms is key to optimizing system performance"</em>
  </p>
</div>

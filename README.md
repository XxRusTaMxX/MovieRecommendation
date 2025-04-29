# 🎬 Movie Recommendation System / 电影推荐系统

## 📌 Project Overview / 项目概述

This project is a **content-based movie recommendation system** built using Python and Streamlit.  
The system recommends movies based on similarity of descriptions, genres, actors, and other metadata.

本项目是一个使用 Python 和 Streamlit 构建的 **基于内容的电影推荐系统**。  
系统基于电影描述、类型、演员等元数据的相似性推荐电影。

---

## 🚀 Quick Start / 快速开始

### 1. Clone the Repository / 克隆仓库


git clone https://github.com/XxRusTaMxX/MovieRecommendation.git
cd MovieRecommendation

2. Create and Activate a Virtual Environment / 创建并激活虚拟环境

# Create virtual environment / 创建虚拟环境
python -m venv venv

# Activate virtual environment / 激活虚拟环境
venv\Scripts\activate        # Windows系统
source venv/bin/activate     # Linux或Mac系统

3. Install Required Packages / 安装依赖库

pip install -r requirements.txt

4. Run the Application / 运行项目

streamlit run main.py

Then open your browser and go to http://localhost:8501.

之后打开浏览器，访问 http://localhost:8501。
🛠 Features / 功能特色

    Movie recommendations based on content similarity.
    基于内容相似度的电影推荐。

    Fetching movie posters using TMDB API.
    使用 TMDB API 获取电影海报。

    Interactive UI using Streamlit framework.
    通过 Streamlit 框架实现交互式界面。

    Lightweight and easy to deploy.
    轻量级，易于部署。

📂 Project Structure / 项目结构

MovieRecommendation/
├── main.py               # Main Streamlit application
├── requirements.txt      # Required packages
├── .gitignore             # Git ignore rules
├── README.md              # Project documentation
└── Files/                 # (Not uploaded) Pre-calculated similarity data

Note: .pkl files in the Files/ directory are not uploaded due to GitHub file size limitations.
注意： Files/ 文件夹下的 .pkl 文件由于 GitHub 限制（100MB）未上传。
📥 How to Get Pre-calculated Data / 如何获取预计算数据

The pre-calculated similarity .pkl files are available via cloud storage (e.g., Google Drive).
You need to download them manually and place them inside the Files/ directory.

预计算的相似度 .pkl 文件可以通过云存储（如 Google Drive）下载。
您需要手动下载并放置到项目根目录下的 Files/ 文件夹内。
👨‍💻 Developed By / 开发者

    Name: Rustam 卢斯塔姆

    GitHub: XxRusTaMxX

    Email: your_email@example.com

📜 License / 许可证

This project is licensed under the MIT License.
本项目使用 MIT 开源许可证。

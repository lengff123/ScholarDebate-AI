# AI学术辩论助手：小明 vs 小红

AI学术辩论助手是一个专为博士生和研究生设计的创新桌面应用程序。它利用人工智能技术模拟两个虚拟角色（小明和小红）之间的学术辩论，旨在帮助研究生提升论文质量，深化对研究主题的理解。

## 功能特点

- **智能学术辩论**：模拟两个AI角色（小明和小红）进行多轮学术讨论
- **论文质量提升**：通过多角度分析和辩论，帮助完善研究思路和论证
- **热键触发**：使用快捷键（Ctrl+B）快速启动辩论，方便在写作过程中随时使用
- **文本分析**：基于用户选中的论文片段和研究问题进行深入讨论
- **实时显示**：在图形界面中实时展示辩论过程，便于跟踪思路发展
- **个性化头像**：为小明和小红配备独特头像，增强视觉体验和辨识度

## 适用场景

- 论文写作过程中的思路梳理
- 研究方法的可行性分析
- 实验结果的多角度解读
- 文献综述的深度探讨
- 学术观点的辩证分析

## 安装说明

1. 确保你的系统已安装Python 3.7+
2. 克隆此仓库：
   ```bash
   git clone https://github.com/your-username/ai-academic-debate-assistant.git
   ```
3. 进入项目目录：
   ```bash
   cd ai-academic-debate-assistant
   ```
4. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```

## 配置

本程序使用 `settings.json` 文件来存储配置信息，包括 DashScope API 密钥。首次运行时，程序会自动创建此文件。请按照以下步骤进行配置：

1. 运行程序后，在项目根目录找到自动创建的 `settings.json` 文件
2. 编辑文件，将 `your_api_key_here` 替换为你的实际 DashScope API 密钥：
   ```json
   {
     "dashscope_api_key": "your_api_key_here"
   }
   ```
3. 保存文件

注意：确保 `settings.json` 文件不被提交到版本控制系统中，以保护你的 API 密钥。

## 使用方法

1. 确保已正确配置 `settings.json` 文件
2. 运行主程序：
   ```bash
   python main.py
   ```
3. 在你的论文或研究文档中选中需要讨论的文本
4. 按 `Ctrl+B` 触发辩论助手
5. 在弹出的窗口中输入具体的研究问题或讨论提示
6. 观看AI角色小明和小红展开学术辩论，获取多角度见解

## 自定义

- 你可以自定义小明和小红的头像，替换 `assets` 目录中的相应图片文件
- 调整 `main.py` 中的参数来修改辩论轮数或其他行为，以适应不同的研究需求

## 依赖库

- tkinter
- dashscope
- keyboard
- pyperclip
- Pillow

## 贡献

欢迎博士生、研究生和开发者提交问题和拉取请求。对于重大更改或新功能建议，请先开issue讨论您的想法。

## 许可证

[MIT](https://choosealicense.com/licenses/mit/)

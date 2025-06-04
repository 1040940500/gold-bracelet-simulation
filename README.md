# 🛍️ 黄金手镯销售模拟 - 角色扮演训练系统

该项目使用 LangChain + OpenAI GPT 模拟客户与销售的对话场景，严格限定“客户”角色回应方式，适用于销售话术训练。

## 🚀 功能简介

- 客户类型 + 销售阶段 组合配置
- 每轮输入销售语句，客户仅用一句自然语言回应
- 语言生成受 Prompt 严格控制，确保训练有效性
- 使用 Gradio 构建用户交互界面，支持状态记忆

## 🔧 技术栈

- Python
- LangChain
- OpenAI GPT API（通过 ChatAnywhere 接口）
- Gradio（界面搭建）

## 📦 安装与运行

```bash
pip install -r requirements.txt
python app.py
```

## 📁 .env 示例

请创建 `.env` 文件或使用如下 `.env.example` 格式：

```
OPENAI_API_KEY=sk-xxxxx
```

## 📸 截图

（可选上传项目截图）
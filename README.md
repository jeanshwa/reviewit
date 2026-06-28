# NSW Legal Analyzer Pro

专业 Streamlit 应用：上传 NSW Contract of Sale 或 Lease 文件，自动分析并生成**中英双语 Word 报告**。

## 功能亮点（Enhanced）
- PDF/TXT/DOCX 上传与文本提取（使用 pypdf）
- 智能分析：基于 NSW 2026 合同标准、Retail Leases Act、商业/住宅租赁专业技能
- **中英双语专业报告**：含执行摘要、风险表格、行动项
- 支持不同客户视角（买方/卖方、租户/房东）
- 可选 Grok API Key 集成真实 AI 分析
- 一键下载 Word 报告

## 本地运行
```bash
pip install -r requirements.txt
streamlit run app.py
```

## GitHub + Streamlit Cloud 部署
1. 将整个文件夹推送到 GitHub 仓库
2. 登录 [share.streamlit.io](https://share.streamlit.io)
3. Connect GitHub → 选择仓库 → Deploy
4. 应用立即上线，可分享链接

## 真实 API 集成（新增）
- 支持 **Grok (xAI)**、**Gemini (Google)**、**Claude (Anthropic)** 三个主流 LLM
- 在侧边栏输入对应 API Key 即可实时调用专业分析
- Grok 使用 OpenAI 兼容端点（https://api.x.ai/v1）
- 提示词已优化为 NSW 物业法专家角色（2026 合同 + Retail Leases Act）

## 本地运行
```bash
pip install -r requirements.txt
streamlit run app.py
```

## GitHub + Streamlit Cloud 部署
1. 将整个文件夹推送到 GitHub 仓库
2. 登录 [share.streamlit.io](https://share.streamlit.io)
3. Connect GitHub → 选择仓库 → Deploy
4. 在 Streamlit Secrets 中配置 API Key（推荐生产环境）

## 注意事项
- 始终结合最新 NSW 法规和您的专业判断使用 AI 输出
- API Key 请妥善保管
- 适合 Redd Law 日常合同/租赁审查工作流

Built for Alex Huang, Solicitor Director, Redd Law Pty Ltd

Built for Alex Huang, Solicitor Director, Redd Law Pty Ltd

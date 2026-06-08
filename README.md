# AI Chat Assistant

赛博朋克风格的 AI 聊天助手网页，基于 Dify + Ollama 本地部署。

## 技术栈

- **前端**: 纯 HTML/CSS/JS，Canvas 粒子动画
- **AI 引擎**: [Dify](https://dify.ai) 工作流编排
- **本地模型**: Ollama + qwen3.5:0.8b
- **GPU**: NVIDIA RTX 3060 Laptop (6GB)

## 效果

- Canvas 粒子背景 + 动态连线
- 霓虹光晕球体浮动
- 科技网格脉冲背景
- 玻璃态卡片 + 四角霓虹装饰
- 在线状态指示器
- 响应式布局（移动端适配）

## 部署

```bash
# 本地预览
python -m http.server 8080

# Vercel 部署
vercel
```

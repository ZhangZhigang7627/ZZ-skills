# OpenClaw 技能集 / OpenClaw Skills

[English](#english) | [中文](#中文)

---

## 中文

### 📖 简介

这是一个精心打造的 OpenClaw Skills 集合，专注于办公自动化和日常效率提升。每个 Skill 都经过测试，帮助你在文档处理、信息查询、媒体创作等方面更加高效。

### ✨ 包含的 Skills

#### 📄 [文档处理](./docx) (Docx)

**描述**: Word 文档的创建、编辑、转换和格式化

**适用场景**:

- 需要创建 Word 文档
- 文档格式调整
- PDF 转 Word
- 批量文档处理

**触发方式**:

```
生成Word文档
把这个内容转成Word
修改Word格式
/docx
```

---

#### 📊 [表格处理](./xlsx) (Xlsx)

**描述**: Excel 表格的创建、编辑、数据分析和可视化

**适用场景**:

- 需要创建 Excel 表格
- 数据清洗和分析
- 公式计算
- 表格格式调整

**触发方式**:

```
生成Excel表格
分析这个表格
做个统计表
/xlsx
```

---

#### 📽️ [PPT 制作](./pptx) (PPTX)

**描述**: PowerPoint 演示文稿的创建和编辑

**适用场景**:

- 需要制作演示文稿
- 幻灯片设计和排版
- 图表和可视化
- 模板应用

**触发方式**:

```
做一个PPT
生成演示文稿
制作slides
/pptx
```

---

#### 📑 [PDF 处理](./pdf) (PDF)

**描述**: PDF 文档的读取、转换、编辑和提取

**适用场景**:

- 需要读取 PDF 内容
- PDF 转换格式
- PDF 合并拆分
- 提取文本和图片

**触发方式**:

```
提取PDF内容
PDF转Word
合并PDF
/pdf
```

---

#### 🚄 [火车票查询](./12306) (12306)

**描述**: 中国铁路12306火车票查询

**适用场景**:

- 查询火车票
- 余票查询
- 时刻表查询

**触发方式**:

```
查火车票
北京到上海的高铁
12306
```

---

#### ✈️ [国际机票查询](./amadeus-flights) (Amadeus Flights)

**描述**: 国际航班搜索和价格查询

**适用场景**:

- 搜索国际航班
- 比较价格
- 查看航班时刻

**触发方式**:

```
查机票
上海到东京航班
国际机票
```

---

#### 📰 [AI 新闻聚合](./ai-news-collectors) (AI News)

**描述**: AI 领域最新动态和热点追踪

**适用场景**:

- 了解 AI 最新新闻
- 跟踪技术趋势
- 行业动态分析

**触发方式**:

```
今天AI有什么新闻
AI动态
AI热点
```

---

#### 🎬 [视频总结](./vsum) (Video Summary)

**描述**: YouTube/Bilibili 视频自动获取字幕并 AI 总结

**适用场景**:

- 视频内容提取
- 长视频要点总结
- 会议记录整理

**触发方式**:

```
总结这个视频
视频内容
/vsum
```

---

#### 🎥 [YouTube 摘要](./youtube-summarizer) (YouTube Summarizer)

**描述**: YouTube 视频字幕获取和结构化总结

**适用场景**:

- YouTube 内容分析
- 字幕提取
- 视频要点整理

**触发方式**:

```
YouTube总结
youtube
```

---

#### 🖼️ [图片生成](./nano-banana-pro) (Image Generation)

**描述**: 使用 Gemini 生成高质量图片

**适用场景**:

- AI 配图
- 概念图生成
- 插图创作

**触发方式**:

```
生成图片
画个图
```

---

#### 🔄 [格式转换](./markdown-converter) (Markdown Converter)

**描述**: 文档格式转换工具

**适用场景**:

- Markdown 转换
- 文档格式互转
- 电子书制作

**触发方式**:

```
转成PDF
MD转HTML
markdown
```

---

#### 🌐 [网页提取](./defuddle-obsidian) (Web Extractor)

**描述**: 干净的网页内容提取

**适用场景**:

- 文章提取
- 内容净化
- 去广告提取

**触发方式**:

```
提取这个网页
读取文章
```

---

### 🚀 快速开始

#### 安装方式

**手动安装**

将需要的 Skill 复制到你的 OpenClaw Skills 目录：

```bash
# 克隆本仓库
git clone https://github.com/ZhangZhigang7627/openclaw-skills.git

# 或者只复制需要的 Skill
cp -r docx ~/.openclaw/workspace/skills/
cp -r pptx ~/.openclaw/workspace/skills/
cp -r pdf ~/.openclaw/workspace/skills/
cp -r xlsx ~/.openclaw/workspace/skills/
```

#### 安装依赖

```bash
# Python 依赖
pip install python-docx python-pptx pypdf openpyxl markitdown

# Node.js 依赖
npm install docx pptxgenjs
```

#### 使用 Skills

直接告诉 OpenClaw 你想做什么：

```
帮我做个Word文档
生成一个PPT
提取这个PDF的内容
查一下北京到上海的火车票
```

---

### 📂 项目结构

```
.
├── README.md                    # 项目说明文档
├── docx/                       # Word文档处理
│   └── SKILL.md
├── xlsx/                       # Excel表格处理
│   └── SKILL.md
├── pptx/                       # PPT制作
│   └── SKILL.md
├── pdf/                        # PDF处理
│   └── SKILL.md
├── 12306/                     # 火车票查询
│   └── SKILL.md
├── amadeus-flights/           # 国际机票查询
│   └── SKILL.md
├── ai-news-collectors/       # AI新闻聚合
│   └── SKILL.md
├── vsum/                      # 视频总结
│   └── SKILL.md
├── youtube-summarizer/        # YouTube摘要
│   └── SKILL.md
├── nano-banana-pro/          # 图片生成
│   └── SKILL.md
├── markdown-converter/        # 格式转换
│   └── SKILL.md
└── defuddle-obsidian/        # 网页提取
    └── SKILL.md
```

---

### 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

### 📄 许可证

本项目采用 MIT 许可证开源。

---

### 📧 联系方式

如有问题，欢迎通过 GitHub Issues 联系。

---

## English

### 📖 Introduction

A carefully crafted collection of OpenClaw Skills focused on office automation and daily productivity. Each skill has been tested to help you work more efficiently in document processing, information lookup, and media creation.

### ✨ Included Skills

#### 📄 [Docx](./docx)

**Description**: Word document creation, editing, conversion and formatting

**Use Cases**:

- Creating Word documents
- Document formatting
- PDF to Word conversion
- Batch document processing

**Trigger**:

```
Generate Word document
Convert to Word
/docx
```

---

#### 📊 [Xlsx](./xlsx)

**Description**: Excel spreadsheet creation, editing, data analysis and visualization

**Use Cases**:

- Creating Excel spreadsheets
- Data cleaning and analysis
- Formula calculations
- Spreadsheet formatting

**Trigger**:

```
Generate Excel
Analyze this spreadsheet
/xlsx
```

---

#### 📽️ [PPTX](./pptx)

**Description**: PowerPoint presentation creation and editing

**Use Cases**:

- Creating presentations
- Slide design and layout
- Charts and visualization
- Template application

**Trigger**:

```
Make a PPT
Create presentation
/pptx
```

---

#### 📑 [PDF](./pdf)

**Description**: PDF document reading, conversion, editing and extraction

**Use Cases**:

- Reading PDF content
- PDF format conversion
- PDF merge and split
- Text and image extraction

**Trigger**:

```
Extract PDF content
PDF to Word
/pdf
```

---

### 🚀 Quick Start

#### Installation

```bash
# Clone the repository
git clone https://github.com/ZhangZhigang7627/openclaw-skills.git

# Copy needed skills
cp -r docx ~/.openclaw/workspace/skills/
cp -r pptx ~/.openclaw/workspace/skills/
```

#### Install Dependencies

```bash
# Python dependencies
pip install python-docx python-pptx pypdf openpyxl markitdown

# Node.js dependencies
npm install docx pptxgenjs
```

#### Usage

Simply tell OpenClaw what you want:

```
Help me make a Word document
Create a PPT
Extract this PDF content
```

---

### 📂 Project Structure

```
.
├── README.md
├── docx/                      # Word processing
├── xlsx/                      # Excel processing  
├── pptx/                      # PPT creation
├── pdf/                       # PDF processing
├── 12306/                     # Train ticket query
├── amadeus-flights/           # Flight search
├── ai-news-collectors/       # AI news
├── vsum/                      # Video summary
├── youtube-summarizer/        # YouTube summary
├── nano-banana-pro/           # Image generation
├── markdown-converter/        # Format conversion
└── defuddle-obsidian/        # Web extraction
```

---

### 🤝 Contributing

Issues and Pull Requests are welcome!

---

### 📄 License

MIT License

---

Made with ❤️ by ZhangZhigang

# 循证手记 · Evidence Workbench

[中文](#中文) · [English](#english) · [所有版本 / All releases](https://github.com/MalcolmLu/med-research-workbench-downloads/releases)

## 中文

循证手记是一款 macOS 医学科研工作台。可以从一个研究问题或一组论文建课题，在同一处管理文献、方案、实验数据、图表和稿件。研究者可以沿 PDF 页码、原始文件和分析版本核对结论。

- **查找和阅读文献。** 导入 PDF、Zotero 文库、PubMed 和 ClinicalKey 批量题录。阅读器支持高亮、批注及带页码的 AI 问答。可用独立的本机或云端向量模型建立课题知识库。
- **整理证据和研究空白。** 对照多篇论文，保留原句、支持与反证、未解决的问题，以及候选研究方向的依据。
- **管理实验与分析。** 登记采集批次、样本、表格、图片和原始文件。由 AI 建议适合研究设计的分析与图表，核对参数后运行，并保留复算所需版本。
- **写作和投稿。** 在文稿中管理引文、图表和修订，可导出 Word、对照学术写作风格，并在投稿前根据稿件和参考文献推荐期刊。
- **保存课题。** 本地和 WebDAV 加密备份支持版本历史与课题恢复。界面支持中文和英文。

### 下载与安装

**[下载 v0.12.1 公开预览版](https://github.com/MalcolmLu/med-research-workbench-downloads/releases/tag/v0.12.1)**。安装包面向 Apple 芯片 Mac（arm64），构建目标为 macOS 14.0 及以上。本次本机实测系统为 macOS 27.2.1。

1. 从版本页面下载 `EvidenceWorkbench-0.12.1-16.zip` 和 `SHA256SUMS.txt`。
2. 在两个文件所在目录运行 `shasum -a 256 -c SHA256SUMS.txt`，确认校验结果为 `OK`。
3. 解压后将「循证手记.app」拖到「应用程序」。已有课题可先在应用中备份，再替换旧版。

> 0.12.1 使用本机签名，Apple 公证待完成。带下载隔离标记的副本在本机 Gatekeeper 检查中被拒绝，首次打开取决于系统和设备管理策略。校验通过后，可参阅 [Apple 的 Mac 应用打开说明](https://support.apple.com/zh-cn/102445) 了解系统提供的选项。

在「系统 AI 设置」连接自己的服务账号，或按需配置本机模型。模型权重按需下载。使用问题可在 [Issues](https://github.com/MalcolmLu/med-research-workbench-downloads/issues) 反馈，并附应用版本、macOS 版本和可复现步骤。

## English

Evidence Workbench is a macOS app for medical research. Start a project with a research question or a set of papers, then keep its literature, protocol, experimental data, figures, and manuscript together. Trace conclusions back to PDF pages, source files, and analysis versions.

- **Find and read papers.** Import PDFs, Zotero libraries, and batch exports from PubMed and ClinicalKey. Highlight and annotate PDFs, and ask AI questions with page references. Build a project knowledge base with a separately configured local or cloud embedding model.
- **Compare evidence and identify research gaps.** Compare papers side by side, retaining original passages, supporting and conflicting findings, open questions, and the basis for proposed topics.
- **Manage experiments and run analyses.** Record batches, samples, tables, images, and source files. Review AI suggestions for statistical methods and figures before running an analysis, and retain the versions needed to reproduce it.
- **Write and prepare for submission.** Manage citations, figures, and revisions, export to Word, use writing style profiles, and get journal suggestions based on the manuscript and its references.
- **Preserve projects.** Encrypted local and WebDAV backups retain project history and support restoration. The interface is available in English and Chinese.

### Download and install

**[Download the v0.12.1 public preview](https://github.com/MalcolmLu/med-research-workbench-downloads/releases/tag/v0.12.1)** for Apple silicon Macs (arm64). The build targets macOS 14.0 or later and was tested locally on macOS 27.2.1.

1. Download `EvidenceWorkbench-0.12.1-16.zip` and `SHA256SUMS.txt` from the release page.
2. In the folder containing both files, run `shasum -a 256 -c SHA256SUMS.txt` and look for `OK`.
3. Unzip the archive and drag the app into Applications. Back up any existing projects in the app before replacing an earlier version.

> Version 0.12.1 uses an ad-hoc signature and is pending Apple notarization. The download-quarantined copy was rejected by Gatekeeper in local testing. First launch depends on macOS and device management policy. After verifying the download, see [Apple's guidance on opening Mac apps](https://support.apple.com/en-us/102445) for the options your Mac offers.

Connect your own AI service in system AI settings, or configure a local model. Model weights are downloaded on demand. Please include the app version, macOS version, and steps to reproduce when reporting a problem in [Issues](https://github.com/MalcolmLu/med-research-workbench-downloads/issues).

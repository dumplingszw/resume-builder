# ResumeForge - 在线简历编辑器

一个纯前端的在线简历编辑器，内置多种开源模板风格，支持 A4 纸预览、实时编辑、一键导出。

**在线体验**: [https://dumplingszw.github.io/resume-builder/](https://dumplingszw.github.io/resume-builder/)

## 功能特性

- **多岗位模板库**: 覆盖校招、社招、技术、产品运营、数据分析、设计、研究生等场景的岗位化模板
- **GitHub 开源模板风格**: 集成 Awesome-CV、Modern Resume、JSON Resume、Deedy、Jake's Resume、Reactive Resume、OpenResume 7 套经典风格
- **技术简历模板**: 接入 [geekcompany/ResumeSample](https://github.com/geekcompany/ResumeSample) 9 个技术岗位模板（Web 前端、Java、NodeJS、PHP、iOS、Android、C/C++、架构师、通用程序员）
- **A4 实时预览**: 右侧预览区按 A4 纸比例 (210mm x 297mm) 渲染，自动压缩字体和间距确保内容完整
- **在线编辑**: 左侧表单实时编辑个人信息、教育经历、工作经历、项目经历等
- **导出功能**: 支持导出为 PDF
- **响应式设计**: 白色简约 UI，渐变标签和玻璃感设计
- **纯静态部署**: 单 HTML 文件，无需后端服务，可部署到 GitHub Pages / 任意静态托管

## 技术实现

- **前端**: 纯 HTML + CSS + JavaScript，无框架依赖
- **模板渲染**: `renderGithubStylePreview()` 动态生成不同风格预览
- **模板切换**: `applyTemplateStyle()` 一键切换编辑器预览样式
- **自动排版**: 三级压缩模式（标准 → 紧凑 → 超紧凑），JS 检测 scrollHeight 自动适配
- **部署**: GitHub Pages 静态托管

## 项目结构

```
resume-builder/
└── resume-builder.html    # 单文件应用（HTML + CSS + JS 全部内联）
```

## 参考项目

- [geekcompany/ResumeSample](https://github.com/geekcompany/ResumeSample) - 程序员简历模板集合
- [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV) - LaTeX 简历模板
- [billryan/resume](https://github.com/billryan/resume) - 简历模板

## License

MIT

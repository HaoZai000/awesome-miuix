# Contributing

[English](#english) | [简体中文](#简体中文)

## English

### Inclusion criteria

- Resources must relate directly to Miuix: applications, extensions, themes, templates, or learning material.
- Applications must use Miuix to build their interfaces. A similar visual style is insufficient.
- Applications, examples, and reusable code must be open source under a license that permits reuse. Articles and demos must be accessible without login or payment.
- Links must work, and descriptions must reflect the project's current state. Disclose archived status and important limitations.
- Community source repositories must have **at least 50 GitHub Stars** at review time. This threshold does not replace quality review.
- Code and documentation must have no obvious AI-generation artifacts, such as leftover prompts, irrelevant boilerplate, or fabricated APIs. AI-assisted work must be reviewed, tested, and maintained.
- Applications and examples must handle padding and safe areas correctly. There must be no obvious overlap, clipping, duplicate padding, or excessive blank space.
- Unrelated Compose resources, duplicate entries, and promotional descriptions are not accepted.

### Categories

Top-level categories follow **resource type**:

- **Official Resources**: the library and official documentation.
- **Examples and Demos**: resources demonstrating Miuix usage.
- **Applications**: projects with interfaces built using Miuix, divided into:
  - **System Tools**: update, extraction, and installation utilities.
  - **Root / Xposed**: root-based system modifications and Xposed applications or modules, including customization and lyrics modules.

Use one category per entry. Optional root support alone does not place a tool in Root / Xposed. Do not classify complete applications by individual UI components.

Propose a new category when needed. Add sections for extensions, themes, templates, or tutorials only when suitable entries are available. Do not create empty sections.

### Pull request checklist

- Use `- [Name](https://github.com/) - Short, factual description.` End descriptions with a period.
- Use official project names and canonical links. For code projects, prefer source repositories.
- Alphabetize entries by project name within each category. In Root / Xposed, keep KernelSU first and GhostLock second; alphabetize the remaining entries.
- Keep both READMEs consistent in names, links, and categories. Update both tables of contents when changing sections. Note any translation assistance needed.
- Explain the resource's value and category. For applications, provide evidence of Miuix-based interfaces, such as a dependency declaration or UI source file.
- Confirm compliance with the inclusion criteria above.
- For applications and examples, include screenshots or a short recording. Specify the device or emulator, screen size, and system UI states tested.
- Test key screens across representative supported sizes and orientations, with the keyboard shown and hidden. On Android, also test display cutouts and supported navigation modes.
- Contributions use the repository's [CC0 license](LICENSE). Linked projects retain their own licenses.

## 简体中文

### 收录要求

- 资源须与 Miuix 直接相关，包括应用、扩展、主题、模板及学习资料。
- 应用须使用 Miuix 构建界面，仅有相似的视觉风格不足以收录。
- 应用、示例及可复用代码须开源，并采用允许复用的许可证。文章和演示须无需登录或付费即可访问。
- 链接须有效，描述须符合项目现状。已归档状态及重要限制须明确说明。
- 社区源码仓库在审核时须有 **至少 50 个 GitHub Stars**。该门槛不能替代质量审核。
- 代码和文档不得有提示词残留、无关模板或虚构 API 等明显 AI 生成痕迹。AI 辅助成果须经人工审阅、测试和维护。
- 应用和示例须正确处理 padding 及安全区域。不得有明显遮挡、裁切、重复 padding 或异常留白。
- 不收录无关的 Compose 资源、重复条目或广告式描述。

### 分类规则

一级分类按**资源类型**划分：

- **官方资源**：库本身及官方文档。
- **示例与演示**：展示 Miuix 用法的资源。
- **应用**：使用 Miuix 构建界面的项目，下分：
  - **系统工具**：更新、提取、安装类工具。
  - **Root / Xposed**：基于 Root 的系统修改及 Xposed 应用或模块，包括系统定制和歌词模块。

每个条目仅归入一个分类。工具仅支持可选 Root 功能时，不必归入 Root / Xposed。完整应用不按单个 UI 组件分类。

现有分类不适用时，可提出新分类。扩展、主题、模板或教程等分类须有实际条目，不预建空章节。

### Pull Request 检查清单

- 使用 `- [名称](https://github.com/) - 简短、客观的描述。` 格式，描述以句号结尾。
- 使用项目正式名称及规范链接。代码项目优先链接源码仓库。
- 同一分类内按项目名称的字母顺序排列。Root / Xposed 中，KernelSU 固定首位，GhostLock 固定第二位，其余条目按字母顺序排列。
- 两个 README 的名称、链接及分类须一致。修改章节时，同步更新目录；需要翻译协助时，请注明。
- 说明资源价值及分类理由。应用须附使用 Miuix 构建界面的证据，如依赖声明或界面源码。
- 确认符合上述收录要求。
- 应用和示例须附截图或简短录屏，注明测试设备或模拟器、屏幕尺寸及系统 UI 状态。
- 测试关键页面在代表性屏幕尺寸、受支持的横竖屏方向及键盘显示和隐藏时的表现。Android 还须测试屏幕缺口及支持的导航模式。
- 贡献遵循本仓库的 [CC0 许可证](LICENSE)。被链接的项目保留各自的许可证。

# 第三方声明

星词典的 `StarKeyboard` 组件和 `starPinyin.js` 由本项目独立编写，当前构建不再包含上一版 `NEORUAA/Vela_input_method` 的组件源码和图片。

项目仍使用以下开源数据或工具：

- **ECDICT**：英文词库补充数据，MIT License。来源：<https://github.com/skywind3000/ECDICT>。
- **pypinyin**：用于构建中文拼音资源，MIT License。来源：<https://github.com/mozillazg/python-pypinyin>。
- 项目中的基础英语词表按各自原始文件携带的许可和来源使用。

本文件只说明项目内实际使用的来源；运行时键盘代码不依赖上述项目的 JavaScript 实现。

## 教材拼写核验

24本人教版历史词表仅提取英文拼写事实用于覆盖核验，来源kajweb/dict（https://github.com/kajweb/dict），具体URL及来源文件SHA256记录于data/school-spelling-facts.json。没有导入其中文释义、例句、音频或应用代码。新增中文释义来自上述MIT ECDICT。教材版次与大学系列未确认，覆盖缺口在data/school-coverage-audit.md/JSON记录。

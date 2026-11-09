# Nomio V8.12.0

**从杂乱文件，到清晰规则。**

[直接下载 V8.12.0 完整源码包](https://raw.githubusercontent.com/Nepenthe396/Nomio/main/releases/NOMIO_V8.12_Source.zip)

[未导入 · 暗色](releases/NOMIO_V8.12_Intake_Dark.png) · [未导入 · 浅色](releases/NOMIO_V8.12_Intake_Light.png) · [核对中 · 暗色](releases/NOMIO_V8.12_Preview.png) · [核对中 · 浅色](releases/NOMIO_V8.12_Preview_Light.png) · [执行结果](releases/NOMIO_V8.12_Result.png) · [全部参数](releases/NOMIO_V8.12_All_Parameters.png)

完整解压到新目录，运行NOMIO_V8.12/run.bat，确认标题8.12.0。需要Python 3.10或更高版本；首次启动安装依赖。本包不含预编译Windows exe，旧exe不会自动更新。用户目录下的.nomio数据继续保留。

## 本版重点

- **阅读层级**：正文/按钮15px Regular，字段标签14px，辅助文字13px，主要标题18px Bold。实际字体样式已检查；缓和暗色白字与边线对比，减少嵌套描边，增加字段和列表文字空间。
- **未导入**：集中显示拖入、添加文件与导入文件夹；搜索筛选和核对工具稍后出现。
- **核对中**：保留一排状态、异常和变化数量；更多展开排序/详情/复制。没有对应项目时禁用跳转，只有名称变化时显示图例。双击/回车仍可直接看详情。
- **参数按需**：只显示规则引用或已填写字段，空白无关字段不重复提示；“全部命名参数”一次展开全部9项，自定义入口保留，不删除原值。单个相关字段占满宽度。
- **图片与结果**：选中实际图片才显示预览图，可关闭并记住；执行后保留精确结果与撤销范围。
- **千文件**：行高改用有界纯文本测量缓存，差异样式在绘制时生成；长原名与新名仍共同决定行高。

177项回归通过，含16项新增状态、字体、可达性和布局测试。真实临时文件重命名/撤销与深浅色1366/1920截图通过。[验证记录](releases/NOMIO_V8.12_Verification.md) · [千文件测量](releases/NOMIO_V8.12_Scale_Report.json) · [千文件末行](releases/NOMIO_V8.12_1000_Files.png)。本次导入含布局1.194秒，参数更新含布局0.683秒，原文件内容保持。

以上为Linux Qt临时文件验证。Windows实机字体观感、高DPI、网络盘和长期使用尚未验证。旧版本保留在releases目录。

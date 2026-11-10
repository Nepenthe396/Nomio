# Nomio V8.13.0

**从杂乱文件，到清晰规则。**

[直接下载 V8.13.0 完整源码包](https://raw.githubusercontent.com/Nepenthe396/Nomio/main/releases/NOMIO_V8.13_Source.zip)

[当前方案与规则摘要](releases/NOMIO_V8.13_Preview.png) · [活动模板](releases/NOMIO_V8.13_Active_Template.png) · [安全追加](releases/NOMIO_V8.13_Safe_Append.png) · [恢复提示](releases/NOMIO_V8.13_Recovery.png) · [恢复任务](releases/NOMIO_V8.13_Recovered_Task.png) · [执行结果](releases/NOMIO_V8.13_Result.png) · [空状态](releases/NOMIO_V8.13_Intake.png)

完整解压到新目录，运行NOMIO_V8.13/run.bat，确认标题8.13.0。需要Python 3.10或更高版本；首次启动安装依赖。本包不含预编译Windows exe，旧exe不会自动更新。用户目录下的.nomio数据继续保留。

## 本版优化

- **明确当前方案**：实际活动模板、我的预设、独立规则与最近使用的选择入口分开；任务名、未保存修改与自动草稿保存独立显示。
- **规则直接可读**：卡片显示具体替换、编号、格式等摘要；选中后显示这一阶段的真实文件变化。无选中时禁用编辑和删除。
- **安全继续追加**：统一三个导入入口，明确新增/重复/不可读/保护数量。第一批01/02执行后追加03，只处理新条目；已处理文件不重复添加前缀，未变化参与项也保护。完成项不再进入单文件测试或待执行导出计划。
- **恢复有上下文**：入口显示时间、任务名和数量；空界面不覆盖旧恢复草稿；提取方式、已处理状态与续号位置可恢复，外部文件状态变化给出完整路径提示。
- **保留简洁与键盘操作**：沿用Regular正文和轻量动效，空状态降低中右栏强调；F7下一处变化、F8下一处异常、Enter详情、Ctrl+C完整名称等入口附提示。

方案/参数改变后，新文件按当前起始值编号，已处理保护保留。要重处理旧文件请开始新批次再导入。旧任务缺少分组续号元数据时会提示核对；较早批次回滚可能留下编号空位。文件状态核验依据大小/修改时间，不是内容哈希；任务不备份文件内容，撤销只恢复名称。

201项回归通过，含24项新增实际执行、追加、取消、恢复、撤销、保护和身份测试。[验证记录](releases/NOMIO_V8.13_Verification.md) · [千文件测量](releases/NOMIO_V8.13_Scale_Report.json) · [千文件末行](releases/NOMIO_V8.13_1000_Files.png)。本次导入含布局0.817秒，参数更新含布局0.497秒，源文件内容保持。

以上为Linux Qt临时文件验证。Windows实机、高DPI、网络盘与长期使用尚未验证。旧版本保留在releases目录。

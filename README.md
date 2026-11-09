# Nomio V8.9.0

**从杂乱文件，到清晰规则。**

[直接下载 V8.9.0 源码包](https://raw.githubusercontent.com/Nepenthe396/Nomio/main/releases/NOMIO_V8.9_Source.zip)

[界面预览](releases/NOMIO_V8.9_Preview.png) · [自定义编辑器](releases/NOMIO_V8.9_Custom_Fields.png) · [千文件末行截图](releases/NOMIO_V8.9_1000_Files.png)

解压到新目录，运行 `NOMIO_V8.9/run.bat`，确认窗口和副标题为8.9.0。需要Python 3.10或更高版本；此包不包含预编译Windows exe，旧exe不会自动更新。

## 按优化顺序完成

- 千文件行高分批适配和像素滚动；检查详情独立滚动，小窗口不遮挡列表。
- 完成后无匹配筛选仍显示实际结果和数量，提供清除筛选；状态筛选和下一个异常入口。
- 自定义入口始终可见，默认表格编辑并保留JSON；全部命名字段可达。
- 后台预览仅接受最新结果，保留队列与查看位置，复用缩略图。F5可刷新外部文件状态。
- 自动工作草稿与启动恢复，保存状态可见；命名任务单独保留，完成状态随任务恢复。
- 局部名称提亮、规则归位和完成汇总淡入；没有冲击波或常驻鼠标装饰。

135项自动测试通过，包含1000个长名称、1000个冲突、实际执行/撤销、草稿恢复与保存失败。

[性能测量原始JSON](releases/NOMIO_V8.9_Scale_Report.json)。测量来自Linux Qt和临时TXT文件，Windows实机字体、高DPI、网络盘及真实大图首次导入尚需验证；不声称完成两周真实使用。

旧包继续保留于releases目录。

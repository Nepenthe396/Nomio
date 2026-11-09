# Nomio V8.11.0

**从杂乱文件，到清晰规则。**

[直接下载 V8.11.0 完整源码包](https://raw.githubusercontent.com/Nepenthe396/Nomio/main/releases/NOMIO_V8.11_Source.zip)

[界面预览](releases/NOMIO_V8.11_Preview.png) · [异常优先核对](releases/NOMIO_V8.11_Priority_Review.png) · [收藏与最近](releases/NOMIO_V8.11_Favorites.png) · [执行结果](releases/NOMIO_V8.11_Result.png) · [撤销范围](releases/NOMIO_V8.11_Undo_Scope.png) · [任务可继续状态](releases/NOMIO_V8.11_Task_Readiness.png)

完整解压到新目录，运行NOMIO_V8.11/run.bat，确认标题8.11.0。需要Python 3.10或更高版本；首次启动安装依赖。本包不含预编译Windows exe，旧exe不会自动更新。

## 六项日常优化

- 收藏与最近使用支持系统模板和我的预设，记住有效模板参数；新套用模板的起始编号回到模板默认值，日期遵循日期方式。
- 字段旁显示当前规则是否引用，自定义变量同步提示；JS动态读取明确说明无法静态确定。
- 仅变化与异常筛选、异常与变化优先、下一个异常/变化；显示排序不改变队列、编号和执行顺序，保留选中文件。
- 新增绿底、删除线、替换暖色底，双列共同适配长名称行高；一键复制完整新名。
- 已保存任务显示最后保存、待处理/可访问、已完成、已排除与失效路径；按保存状态估算，打开后仍需预览检查。
- 执行结果明确区分成功、失败、未变化、未处理和排除；事务失败区分已回滚与待确认，不捏造逐文件失败数。撤销范围检查文件缺失和原路径占用，仅恢复名称，不恢复内容。重启后的历史恢复通过操作记录核验。

沿用内置中文无衬线字体、后台预览、自动草稿和执行限定流光，不增加常驻动画。

161项自动测试通过，含实际临时文件执行/撤销及18项新增日常流程测试。[验证记录](releases/NOMIO_V8.11_Verification.md) · [千文件测量](releases/NOMIO_V8.11_Scale_Report.json) · [千文件末行](releases/NOMIO_V8.11_1000_Files.png)。千文件参数更新含布局0.877秒，原文件内容不变。

以上为Linux Qt临时文件验证。Windows实机、高DPI、网络盘与长期使用尚未验证。旧版本保留在releases目录。

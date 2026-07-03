# xivtoolssf


最终幻想14个人工具集
### 时间轴导出工具（timeline/）
解析 FFLogs 战报链接，按玩家和技能筛选后，导出：
- 分析用 CSV 表格
- 展示用 HTML 时间轴

### 谁是你的最佳搭档（partner/）
分析战报数据，统计团队中配合度最高的搭档，仅供娱乐参考。

### FFLogs API 配置
两个工具都需要在 FFLogs 官网申请个人 API 凭证（Client ID / Client Secret），首次使用时会引导填写。凭证只保存在浏览器本地的 localStorage 中，不会上传到除 FFLogs 官方以外的任何服务器。两个工具共用同一份凭证，在其中一个工具里配置过，另一个工具会自动读取，无需重复填写。

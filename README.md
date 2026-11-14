# 嘉立创地图 PCB Skill

根据地名调研道路、步道、水系等地图表达，按需预览；接收地图后先确认位置和大小，再自主完成嘉立创EDA落板、检查和保存。

## 文件

- `jlc-map-pcb-skill.zip`：当前 skill，解压后将 jlc-map-pcb 文件夹放到 ~/.codex/skills/，调用 $jlc-map-pcb。
- `all-files-backup-20261114.zip`：第一版、首轮全部文件、第二轮原始地图、工程、Gerber、截图、总结和技能快照。解压后查看 pcb_skill_selftest_round2/交付索引.md 与 07_review/方案总结.md。
- `WestLake-desktop-verified.epro2`：桌面 EDA 实际导出并完成重开验证的西湖试验工程。
- `original-backup.sha256`：完整备份原始文件名及SHA256；仓库中备份已改用英文名，内容不变。

## 验证与限制

已完成真实西湖地图抓取、桌面导入、保存、工程导出、关闭重开与实际截图。板框85.6×54mm，正面左侧顶层丝印0.2mm，27环。DRC141项0问题；Gerber几何核对通过。仍有29对近邻轮廓的笔画合并，尚非生产定稿；白板黑丝印仅为本次3D预览，未验证颜色持久化。没有下单。

原始地图 © OpenStreetMap contributors，ODbL 1.0，来源 https://www.openstreetmap.org/relation/2308774 ，许可 https://www.openstreetmap.org/copyright 。完整来源与处理记录在备份中。

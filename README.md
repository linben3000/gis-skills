# gis-skills
I have collected some GIS skills



A quick scan of popular agent skill catalogs reveals a gap: almost none are truly GIS-native. They assume tabular data, generic APIs, or frontend concerns. Few of them understand projections, spatial joins, topology, geometry validity, publishing constraints, or how GIS work turns into actual deliverables.
https://github.com/danmaps/gis-agent-skills


A skill package that teaches Claude how to write correct, production-quality PyQGIS code. Every skill uses deterministic ALWAYS/NEVER language, includes working code examples, and documents anti-patterns with fix patterns.
https://github.com/OpenAEC-Foundation/QGIS-Claude-Skill-Package

GIS Web Mapping Skills 
https://github.com/Fadhili5/gis-claude-skills

已支持的重点地图能力包括：
分级设色
热力图 / 密度图
流向图
胡焕庸线生成与对比
标签、图例、属性查询
地形剖面和简化地形表达
https://github.com/Sinfony8838/QGIS-OpenClaw-Bridge

[Land Acquisition Intelligence](
qgis-automation-skill 是一个面向 AI 编码 Agent（如 Claude Code）的技能包，让 Agent 通过 qgis_process CLI 完成 GIS 空间分析任务，而不是给出"打开 QGIS 点菜单"这类无法执行的指令。
核心能力：
缓冲区分析（native:buffer）
图层裁剪（native:clip）
坐标重投影（native:reprojectlayer）
批量处理 / 多步流水线（PyQGIS 脚本）
错误自动诊断（error-detector）
https://github.com/Zhangyi-cug/qgis-automation-skill


Real Agent — King County Property Intelligence
https://github.com/JayAI623/real-agent


通过自然语言语义路由，自动调度四大专业管道完成空间数据治理、用地优化、多源数据融合和商业智能分析。
https://github.com/iflow-mcp/zhouning-gisdataagent


GeoPipeAgent 是一个 AI 优先 的 GIS 数据分析流水线框架。 AI 通过 Skill 文件理解框架能力，生成 YAML 格式的分析流水线，框架解析并执行，返回 JSON 结构化报告。
https://github.com/znlgis/GeoPipeAgent

本 Skill 为 WorkBuddy/Claude 提供 SuperMap iDesktopX 自动化能力，涵盖数据管理、空间分析、地图制图、三维分析等核心 GIS 功能。
https://github.com/kruie/supermap-idesktop-skill

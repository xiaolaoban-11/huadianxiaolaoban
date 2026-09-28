# 线上花店 · 小红书运营 Skills

本仓库集中管理八个可独立调用的业务 Skill。它们是为线上花店定制的工作指令，不代表已部署爬虫、接通小红书 API 或开启自动发布。

## 流程
公开竞品研究 → 爆款拆解 → 产品策划 → 选题 → 原创文案 → 内容排期 → 人工审核发布与询单 → 数据复盘。

## 目录
- [xhs-research](skills/xhs-research/SKILL.md)：小红书竞品情报
- [xhs-benchmark](skills/xhs-benchmark/SKILL.md)：小红书爆款拆解
- [flower-product](skills/flower-product/SKILL.md)：花束产品策划
- [xhs-topic](skills/xhs-topic/SKILL.md)：小红书选题
- [xhs-copywriting](skills/xhs-copywriting/SKILL.md)：小红书花店文案
- [content-calendar](skills/content-calendar/SKILL.md)：花店内容日历
- [lead-conversion](skills/lead-conversion/SKILL.md)：私信询单转化
- [analytics](skills/analytics/SKILL.md)：运营数据复盘

## 外部项目（仅作为候选依赖，需独立安全评估和安装）
- https://github.com/xiaofuqing13/redbooks （Windows 小红书研究工具，注意平台条款、访问频率与登录信息）
- https://github.com/theone-ctrl/ai-content-automation-n8n （面向视频的 n8n 示例，需按花店业务改造）
- https://github.com/alphaparkinc/genpark-content-calendar-skill （内容日历参考）
- https://github.com/mithulix/Social-Media-Dashboard （社媒看板参考，非开箱即用小红书看板）
- https://github.com/feder-cr/invisible_playwright_mcp （第三方浏览器工具，需单独安全和合规评估，不以规避平台风控为目的）

## 使用与验收
每个 `skills/*/SKILL.md` 说明输入、流程、输出、验收条件。先用手工导出或授权数据打通一条真实业务链；实际发布与顾客沟通必须审核。禁止伪造订单、销量、互动或顾客评价，禁止绕过验证码及平台访问控制。任何客户联系方式仅存于授权的私有业务系统，不提交到本仓库。

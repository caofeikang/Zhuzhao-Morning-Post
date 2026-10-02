# Zhuzhao-Morning-Post
This is an information platform that integrates energy and AI, dedicated to serving practitioners across the entire energy industry.
六种信源：RSS、网页列表、JSON 接口、X 账号、微信公众号，以及你自己脚本推送进来的内容。信源分级（官方一手 / 媒体个人），抓取频率按产出自动调整
精选：预筛，同一份评分标准独立打两次分，再按信源分级的门槛决定入选。提示词和门槛全部公开，全部可以改；用你自己标注的样本在 SelectBench 里校准
写作：中文标题、答案先行的摘要、推荐理由、标签，外文全文翻译；防止模型把原文没提到的公司写进标题
聚簇：不同来源报道的同一件事聚成一个事件，后续进展挂在同一个事件下，事件页有综述；人工改过的归属不会被覆盖
热点：按事件算热度：独立来源越多越靠前，X 上的讨论也算进来；和 6 小时前比，涨得快的标上升，新出现的标“新”
日报、周报、月报：每天 07:00 出日报，每周一出周报，每月 1 日出月报，按分类分节，带导语
给 Agent 用：RSS（精选、全部、全文、日报）、公开 API、MCP、Agent Markdown、llms.txt，同一份内容给人看也给 Agent 用
后台：信源管理与试抓、内容诊断、精选评测、每一步单独换模型、付费服务的预算熔断、运行记录与告警
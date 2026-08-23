# 错题诊断与个性化复习助手（教育场景 AI 三件套）

仓库：[hopehou666/AI_zuoye](https://github.com/hopehou666/AI_zuoye)

## 统一场景

学生订正作业时往往只看正确答案，难以定位薄弱知识点；教师也难以及时给出个性化复习建议。本作业围绕同一痛点，用三条技术路线分别交付：

| 路径 | 目录 | 交付物 | 使用者 |
|------|------|--------|--------|
| 路径1 分数除法习题 学伴智能体 | [01-agent](./01-agent/) | 智能体页面 + 提示词 | 问知识点 / 输入题目批改 |
| 路径2 多维表 | [02-table](./02-table/) | 多维表（AI 字段）链接 | 教师班级学情管理 |
| 路径3 交互网页 | [03_web](./03_web/) | `index.html` | 课堂/课后即时练习 |
| 最大公因数 | [04_gcf](./04_gcf/) | `index.html` | 列举法 / 更相减损法演示 |

## 与评价指标对齐

- **教育场景适配度**：错题 → 知识点 → 错因 → 巩固题 → 复习计划，贴近真实教与学流程。
- **技术实现可靠性**：固定输出结构、缺信息先追问，便于反复测试稳定复现。
- **应用角度创新性**：按学段/学科/错因做个性化路径，而非通用闲聊问答。

## 在线链接（GitHub Pages 开启后可用）

先在仓库 **Settings → Pages**，Source 选 `Deploy from a branch`，Branch 选 `main` / `(root)` 并 Save。约 1～2 分钟后打开：

| 入口 | 链接 |
|------|------|
| 总导航 | https://hopehou666.github.io/AI_zuoye/ |
| 路径1 分数除法习题 学伴智能体 | https://hopehou666.github.io/AI_zuoye/01-agent/agent.html |
| 路径2 多维表 | https://hopehou666.github.io/AI_zuoye/02-table/table.html |
| 路径3 交互网页 | https://hopehou666.github.io/AI_zuoye/03_web/index.html |
| 最大公因数计算器 | https://hopehou666.github.io/AI_zuoye/04_gcf/index.html |

代码仓库：https://github.com/hopehou666/AI_zuoye

## 建议演示顺序

1. 打开交互网页做 5 题小测。
2. 打开分数除法习题 学伴智能体：先问知识点，再输入题目让它批改。
3. 打开多维表查看 AI 字段自动生成结果。

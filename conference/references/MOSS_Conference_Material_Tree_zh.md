# MOSS: Conference & Product Material Tree (产品级路演文档树)

为了确保 MOSS 作为一个极具潜力的明星内部产品能够成功“兜售”给各个层级的高管和利益相关方，我们需要建立一个结构清晰、无死角的“Conference & Product Material Tree”（产品路演与资料树）。

以下是完整的理论树结构，以及我们目前**已拥有（✅）**和**还缺失（🔲）**的文档大地图。

---

## 1. 核心愿景与价值层 (The "Why" - Vision & Value)
**受众**：Global 高管、Country Manager、商业化负责人。主要解决“为什么要做，能省多少钱，战略意义是什么”的问题。

*   ✅ **项目愿景与极简介绍书 (Vision Document)**
    *   *现有文件*：`conference/MOSS_Conference_Vision_Document.md` (英文一页纸摘要)
    *   *现有文件*：`ref/IKEA AI 智能图像工作台 - 商业价值白皮书.md` (中文白皮书)
*   ✅ **产品全景白皮书 (Product Whitepaper)**
    *   *现有文件*：`ref/MOSS_产品全景与汇报材料.md` (作为所有材料的母本库)
*   🔲 **竞品与投入产出比分析 (ROI & Build vs. Buy Model)** (缺失)
    *   *说明*：需要明确论证为什么我们要内部造轮子（Build MOSS），而不是买市面上现成的 SaaS 服务（Buy Adobe Firefly/Midjourney），量化自建模型对宜家自有版权和成本带来的长远保护。

## 2. 汇报演说与打榜演示层 (The "Show" - Pitch & Demo)
**受众**：各路决策会上的评审团。主要解决“如何生动地打动他们并拿到预算和支持”的问题。

*   ✅ **针对业务线高管的路演 PPT 与剧本**
    *   *现有文件*：`ref/MOSS_PPT汇报大纲与剧本.md`
*   ✅ **针对研发/技术线高管的答辩 PPT**
    *   *现有文件*：`slides/Engineer_Manager_Presentation.md`
*   🔲 **标准演示原型 / 视频 (Live Demo Script / Video)** (待深化)
    *   *说明*：仅仅有 PPT 剧本不够。在实际 Conference 上，你需要一个“万无一失”的录制版 Demo 视频文件，或者一个极简的 figma 点击交互原型，用来展示 Vibe coding 的丝滑。
*   ✅ **防弹衣：核心 QA 与痛点防守矩阵**
    *   *现有文件*：`ref/跨部门干系人沟通与防守矩阵 (Stakeholder Matrix).md`

## 3. 产品需求与架构说明层 (The "What" - Product & Design)
**受众**：产品经理、设计师、前端/后端主程。主要解决“MOSS到底长什么样，具体怎么交互”的问题。

*   ✅ **UI 与信息架构草图**
    *   *现有文件*：`moss.drawio` (三栏布局草图)
*   🔲 **核心产品需求文档 (PRD: Product Requirements Document)** (严重缺失)
    *   *说明*：虽然有宏观愿景，但研发团队需要能看到具体的 User Story（用户故事）。例如：“作为一个门店导购，我希望...” 还需要写明每个模块的功能边界。
*   🔲 **技术架构与系统交互流 (Technical Architecture Blueprint)** (缺失)
    *   *说明*：向技术线汇报时，虽然 PPT 讲了故事，但需要一份落地的架构图（如包含前端应用层、后端 API Gateway、大模型推理层、宜家 SKU 算力层的分布图），以证明项目的技术可行性。

## 4. 落地与推行运营层 (The "How" - Operations & GTM)
**受众**：项目组内部、种子用户（门店员工、运营人员）。主要解决“接下来我们要干什么，怎么教会大家用”的问题。

*   ✅ **产品演进路线图 (Roadmap)**
    *   *现有文件*：`ref/产品演进与落地路线图 (Roadmap).md`
*   🔲 **一页纸新手操作指南 (Cheatsheet / Onboarding Guide)** (缺失)
    *   *说明*：当产品 MVP 上线甚至在 Conference 当天让别人试玩时，需要一张给非技术人员的极为简单的图文说明或飞书/钉钉公告模版。

---

### 💡 总结与建议行动：

目前，您在 **宏观价值 (价值层)** 和 **向上汇报 (演示层)** 的“子弹”已经准备得比较充足了。我们现在拥有一个非常能够“卖得出去”的好故事。

如果要将这个“会议文档集”彻底补齐变成“随时可立项动工”的状态，**接下来我建议我们优先补充【第三层（The "What"）】的内容**：
1.  **产品层面**：我们可以把 `moss.drawio` 的思路写成一份轻量级的 **MVP PRD (敏捷核心需求文档)**。
2.  **技术层面**：为您设计并输出一份文字版的 **技术架构说明 (Technical Architecture Blueprint)**，这将彻底打消 Engineering Manager 对您系统落地可行性的最后疑虑。

您看是否认同这个树状结构？如果认同，我们可以从哪一个“缺失模块”开始动笔？

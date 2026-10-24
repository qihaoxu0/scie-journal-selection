# 来源与检索规范

以下是权威入口，不代表对任何具体期刊作出当前状态认证。每次执行时打开实际页面并验证，不能只引用搜索摘要或把入口链接当作逐刊证据。

## SCIE与期刊身份

- [Clarivate Master Journal List](https://mjl.clarivate.com/)：查精确刊名及ISSN，核实 Web of Science Core Collection 明确列出 Science Citation Index Expanded。记录查询结果链接或可复查检索条件。
- 出版社主页用于核对刊名、ISSN、转社、更名及文章类型。更名刊须确认索引承接，旧刊索引不能自动赋给新刊。
- 网站受限时，可采用当前、可追溯的Clarivate官方列表或用户授权取得的记录；无法确认当前状态则UNKNOWN。不得将影响因子、历史论文能检索到或第三方“SCI期刊”标签作为充分证据。

### 强制状态变化调查

当前收录核查不能停在历史分区、JCR或题名检索结果。对每一本候选刊同时执行以下调查：

1. 用完整刊名、常用简称、pISSN和eISSN分别查询Master Journal List，确认当前集合字段明确为 `Science Citation Index Expanded`。通用Clarivate题名表可能同时包含其他数据库，题名仍存在不等于仍在SCIE。
2. 跨时间公开检索以下组合，并查看结果发生日期，而不是只看页面更新时间：

```text
"Journal Title" ("On Hold" OR "re-evaluation" OR reevaluation)
"Journal Title" (removed OR delisted OR dropped OR "coverage discontinued")
"Journal Title" (cease OR ceased OR "stopped indexing")
"Journal Title" (reinstated OR restored OR resumed)
"ISSN" ("Web of Science" OR SCIE) (removed OR "On Hold" OR reinstated)
"期刊名称" (踢出SCIE OR 停止收录 OR 暂停收录 OR 恢复收录)
```

3. 优先核实Clarivate当前页面、Clarivate回复或可追溯移除清单；再用高校图书馆、科研机构和出版社信息交叉验证。可信报道若给出停止日期、停止覆盖卷期或“之后内容不再收录”，必须记录这些边界。
4. 检查所谓“恢复收录”是否有Clarivate当前SCIE记录支持。仍可在出版社投稿、仍有影响因子、Scopus继续收录、旧论文仍在WoS、旧馆藏条目仍标SCIE，都不等于恢复。

状态判定：

- 当前MJL明确列出SCIE，且未检出尚未解决的移除/暂停证据：`PASS`。
- Clarivate已停止覆盖、移出Core Collection或当前不列SCIE：`FAIL`。同时记录停止日期和最后覆盖卷期/年份（如可得）。
- `On Hold`、重新评估中、可信移除报告与当前页面冲突、MJL关键字段不可访问，或恢复状态缺乏官方确认：`UNKNOWN`，不得推荐。
- 历史JCR、2025中科院分区和旧SCIE记录只能证明历史状态。它们与当前收录结论分栏记录，不能相互替代。

## 2025中科院分区与预警

- [中科院期刊分区表](https://www.fenqubiao.com/)及有权访问的2025年存档：核对版本、刊名、ISSN、大类和全部相关小类。官方服务不可用时使用可追溯的机构馆藏或用户合法提供的2025年表，记录来源和页码/条目。第三方网站只能辅助定位，不能静默升级为已核实官方分区。
- [国际期刊预警入口](https://earlywarning.fenqubiao.com/)。可交叉核查[中科院机构发布的2025年预警公告](https://iae.cas.cn/jw/kycx/202504/t20250401_7585150.html)及[中科院机构托管的2025年名单PDF](https://ic.cas.cn/jyc/xwsq/xwwj/202209/P020251020610082955431.pdf)。打开并确认完整名单和年份后，按ISSN及刊名别名逐一匹配；搜索不到该刊不等于不在名单。
- 中科院分区表数据结构中的小类字段名可能含JCR字样，不能据此将其解释为JCR Q1–Q4。输出明确写“2025中科院大类/小类分区”。
- 不绕过登录、不使用网页公开粘贴的共享账号。来源不足时请求用户提供合法记录，继续其他可独立核查项。

## 非OA路径与转换报告

对每刊至少核查当前出版社的期刊主页、作者指南/发表模式和收费页面，以及出版社新闻/转换列表。若为学会刊或近期转社刊，补查学会及新旧出版社的相关公告。出版社宏观OA战略不能直接证明每一本旗下期刊已有转换计划。

跨时间公开搜索，不以“最近一年”等筛选漏掉早年发布的未来转换公告。使用完整刊名、简称及必要的ISSN，组合：

```text
"Journal Title" ("fully open access" OR "gold open access")
"Journal Title" (transition OR converting OR converted OR flipped OR "from January")
"Journal Title" ("subscription" OR "hybrid" OR "publishing options")
"期刊名称" (转全OA OR 转为开放获取 OR 全开放获取)
site:publisher-domain "Journal Title" "open access"
```

这些是查询模式示例；根据搜索引擎是否支持布尔语法拆分查询。不能只完成其中一条搜索就宣称充分覆盖。

判断规则：

- 明确的该刊全OA转换公告或可追溯的可信转换报告：FAIL，无论转换是否已生效。记录公告发布日和生效日，不把网页更新时间当公告日。
- 可信第三方出现具体转换消息而原公告暂无法核实：UNKNOWN并单列线索，不能仍推荐为无报告。
- 只有作者可选OA、机构转换协议、某篇OA文章、OA特刊或姊妹刊全OA：不是该刊整体转全OA的充分证据；继续核查该刊自身路径。
- 搜索结果串刊、机器生成摘要或未经证实的帖子不能直接定案。相互冲突的官方页面、未注明日期的转换信息、关键页面无法访问：UNKNOWN，记录冲突。
- 全部既定渠道已实际核查且未见相关报告：可在披露检索范围后将本项记为PASS，含义是“范围内未检出”，不是证明绝对不存在。

证据记录最小字段：`journal_title, pissn, eissn, publisher, checked_at, timezone, criterion, status, source_title, source_url, published_at, effective_at, query_or_locator, finding, uncertainty`。不适用日期留空，不猜测。

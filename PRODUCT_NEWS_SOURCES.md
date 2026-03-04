# Product News 信息源配置文档

## 项目定位
跨境电商产品情报系统 - 追踪海内外消费品趋势、爆品机会和市场动向

## 目标内容
1. 用户喜欢什么产品
2. 文化性活动和节日营销机会
3. 整体文化潮流和风向
4. 实体产品为主（硬件、消费品、时尚、生活方式）

---

## 📡 信息源列表

### 1. Reddit 频道（重点）

#### 产品发现类
- **r/ProductHunters** - 新产品发现和讨论
- **r/shutupandtakemymoney** - 用户想买的产品（高购买意愿）
- **r/DidntKnowIWantedThat** - 创意产品和新奇物品
- **r/ProductPorn** - 优秀产品设计
- **r/BuyItForLife** - 高质量耐用产品推荐

#### 电商和创业类
- **r/Entrepreneur** - 创业和商业机会
- **r/ecommerce** - 电商行业趋势
- **r/AmazonSeller** - 亚马逊卖家动态和爆品
- **r/dropship** - Dropshipping 产品和策略

#### 垂直品类
- **r/streetwear** - 街头时尚和潮流服饰
- **r/sneakers** - 球鞋文化和限量款
- **r/MakeupAddiction** - 美妆产品和趋势
- **r/gadgets** - 科技产品和电子设备
- **r/HomeImprovement** - 家居改善产品

---

### 2. 产品发现平台（RSS 订阅）

#### 综合产品平台
- **Product Hunt - Physical Products**
  - URL: https://www.producthunt.com/categories/physical-products
  - RSS: https://www.producthunt.com/feed
  - 特点：每天更新，有投票和评论，产品质量高

- **Gadget Flow**
  - URL: https://thegadgetflow.com/
  - RSS: https://thegadgetflow.com/feed/
  - 特点：科技产品、创意硬件、众筹项目

- **Trendy Gadget**
  - URL: https://www.trendygadget.com/
  - RSS: https://www.trendygadget.com/feed/
  - 特点：最新科技产品新闻和趋势

- **The Gadgeteer**
  - URL: https://the-gadgeteer.com/
  - RSS: https://the-gadgeteer.com/feed/
  - 特点：1997年至今，专注实用硬件评测

---

### 3. 众筹平台（爆品早期信号）

#### Kickstarter
- **Kickstarter 热门项目**
  - 可用 RSS: https://blog.feedspot.com/kickstarter_rss_feeds/
  - 特点：创新产品早期信号，众筹数据反映市场需求

#### Indiegogo
- **Indiegogo 热门项目**
  - URL: https://www.indiegogo.com/explore/all
  - 特点：硬件和消费品众筹

---

### 4. 科技媒体（RSS 订阅）

- **Engadget**
  - URL: https://www.engadget.com/
  - RSS: https://www.engadget.com/rss.xml
  - 特点：科技产品新闻和深度评测

- **The Verge - Products**
  - URL: https://www.theverge.com/products
  - RSS: https://www.theverge.com/rss/index.xml
  - 特点：科技产品深度报道

- **Gadgets 360**
  - URL: https://www.gadgets360.com/trends
  - RSS: https://gadgets.ndtv.com/rss/feeds
  - 特点：最新产品趋势和发布

- **TechCrunch - Hardware**
  - URL: https://techcrunch.com/category/hardware/
  - RSS: https://techcrunch.com/category/hardware/feed/
  - 特点：硬件创业公司和新产品

---

### 5. 时尚和潮流媒体

- **Hypebeast**
  - URL: https://hypebeast.com/
  - RSS: https://hypebeast.com/feed
  - 特点：街头文化、时尚、球鞋、潮流产品

- **Cool Hunting**
  - URL: https://coolhunting.com/
  - RSS: https://coolhunting.com/feed/
  - 特点：设计、文化、旅行、产品趋势

- **Trend Hunter**
  - URL: https://www.trendhunter.com/
  - 特点：消费趋势和创新产品

---

### 6. 电商数据平台（需要 API/爬虫）

#### Amazon
- **Amazon Best Sellers**
  - 各品类畅销榜
  - 可以通过爬虫或第三方工具获取

#### 产品研究工具
- **Thieve.co** - AliExpress 热门产品精选
- **AutoDS** - AI 驱动的产品研究
- **Ecomhunt** - Dropshipping 产品发现

---

### 7. Telegram 频道（可选）

- 跨境电商资讯频道
- 品牌动态频道
- 消费趋势频道
- 海外营销案例频道

---

### 8. GitHub（保留）

- **开源硬件项目**
  - Arduino、Raspberry Pi 相关项目
  - 智能家居、可穿戴设备

---

## 🎯 AI 打分标准

### 评分维度（0-10分）

1. **商业潜力** (30%)
   - 市场规模和需求
   - 可复制性和供应链可行性
   - 利润空间

2. **消费者兴趣** (30%)
   - 社交媒体热度
   - 用户讨论和评论
   - 搜索趋势

3. **文化相关性** (20%)
   - 是否符合当前潮流
   - 节日和文化活动相关
   - 地域文化适配性

4. **产品创新性** (20%)
   - 设计独特性
   - 功能差异化
   - 解决的痛点

### 过滤条件
- ✅ 必须是实体产品相关
- ❌ 排除纯软件、纯技术内容
- ✅ 优先海外市场，但不排除国内
- ✅ 关注消费品、硬件、时尚、生活方式

---

## 🏷️ 标签体系

### 商业机会类
- `#爆品潜力` - 有成为爆品的可能
- `#市场机会` - 新兴市场或细分市场
- `#供应链` - 供应链和采购相关

### 趋势类
- `#消费趋势` - 消费者行为和偏好变化
- `#文化潮流` - 文化和社会趋势
- `#时尚潮流` - 时尚和穿搭趋势

### 营销类
- `#节日营销` - 节日和季节性机会
- `#网红推荐` - KOL 和网红推荐的产品
- `#社交媒体` - 社交媒体热门产品

### 产品类
- `#产品设计` - 优秀的产品设计
- `#创意产品` - 创新和新奇产品
- `#品牌动态` - 品牌发布和更新

### 用户类
- `#用户需求` - 用户痛点和需求
- `#生活方式` - 生活方式和场景
- `#文化活动` - 文化活动和事件

---

## 📊 输出格式

保持现有结构：

```markdown
# Product News 每日速递 - 2026-03-04

> From XX items, XX important product trends were selected

---

1. [产品标题](#item-1) ⭐️ 9.0/10
2. [产品标题](#item-2) ⭐️ 8.5/10
...

---

<a id="item-1"></a>
## [产品标题](链接) ⭐️ 9.0/10

产品描述和市场机会分析...

来源 · 作者/品牌 · 时间

**标签**: `#爆品潜力`, `#消费趋势`, `#文化活动`
```

---

## 🔄 更新频率

- **每日运行一次**：抓取过去 24 小时的内容
- **建议运行时间**：每天早上 8-9 点
- **处理时间**：约 1 分钟

---

## 📝 使用说明

### 运行命令
```bash
cd /Users/admin/Horizon
export PATH="$HOME/.local/bin:$PATH"
uv run horizon --hours 24
```

### 查看结果
```bash
open data/summaries/horizon-$(date +%Y-%m-%d)-zh.md
```

---

## 🚀 未来扩展

### 短期（1-2周）
- [ ] 添加更多 Reddit 频道
- [ ] 配置所有 RSS 订阅源
- [ ] 优化 AI Prompt

### 中期（1个月）
- [ ] 集成 Kickstarter API
- [ ] 添加 Amazon Best Sellers 爬虫
- [ ] 配置 Telegram 频道

### 长期（3个月）
- [ ] 添加图片识别（识别产品图片）
- [ ] 价格追踪功能
- [ ] 竞品分析功能
- [ ] 自动生成产品报告

---

**文档创建时间**: 2026-03-04
**最后更新**: 2026-03-04

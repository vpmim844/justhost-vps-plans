# 搬瓦工替代怎么选：$49.99/年买不到 CN2 GIA，便宜的套餐是不是阉割版？换机房、换 IP、退款这些坑一次讲清（附 JustHost 全套餐价格表）

搬瓦工替代这个词，搜的人多半卡在同一个地方：预算和线路对不上。搬瓦工 $49.99/年 那一档走的是 CN2 GT 和普通线路，要 CN2 GIA 得掏 $169.99/年。如果预算只有每月二三十块，又希望机房能随便换、流量不设上限，JustHost 是这条路上起步价最低的一档：1 核 1GB、20GB NVMe、300Mbit 不限流量，月付 ¥24.65，年付折后月均 ¥19.72。

下面讲清三件事：搬瓦工那几档套餐的线路到底怎么分、同样挂着 CN2 GIA 名头的方案一年为什么能差出四倍价钱、换成 JustHost 这类便宜多机房商家之后会在哪些地方卡住。

> **选购速览**：要 CN2 GIA 三网优化，别看 JustHost，去看搬瓦工 GIA-E 或 DMIT Pro。只需要一台便宜、机房多、不限流量、能随时换 IP 的境外机器用来建站或做节点，直接上 Sirius 这档（1 核 / 1GB / 20GB NVMe / 300Mbit，年付折后月均 ¥19.72）。¥6.93 的 Promo 只有 10Mbit 带宽和 512MB 内存，装个 WordPress 都吃力。
> 👉 [查看 JustHost 全部套餐与当前价格](https://justhost.asia/?ref=196392)

## JustHost 当前在售套餐全表

下表是官网人民币口径的月付原价与年付折后月均，全部 KVM 虚拟化、NVMe SSD、不限月流量。

| 套餐 | CPU / 内存 / NVMe | 带宽 | 月付原价 | 年付折后月均 | 购买 |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1核 / 512MB / 5GB | 10Mbit | ¥6.93 | — | [ 看这档配置](https://justhost.asia/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1核 / 1GB / 10GB | 100Mbit | ¥19.40 | ¥15.52 | [ 选 New Star](https://justhost.asia/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1核 / 1GB / 20GB | 300Mbit | ¥24.65 | ¥19.72 | [ 选 Sirius](https://justhost.asia/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1核 / 2GB / 30GB | 300Mbit | ¥35.17 | ¥28.13 | [ 选 Arcturus](https://justhost.asia/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2核 / 2GB / 20GB | 200Mbit | ¥36.01 | ¥28.81 | [ 选 Double Star](https://justhost.asia/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2核 / 2GB / 40GB | 400Mbit | ¥45.68 | ¥36.55 | [ 选 Alpha Centauri](https://justhost.asia/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4核 / 4GB / 30GB | 300Mbit | ¥49.78 | ¥39.83 | [ 选 Bright Star](https://justhost.asia/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2核 / 4GB / 80GB | 500Mbit | ¥68.29 | ¥54.63 | [ 选 Vega](https://justhost.asia/services/vps/tariffs/vega?ref=196392) |
| Capella | 4核 / 4GB / 120GB | 750Mbit | ¥93.00 | ¥74.40 | [ 选 Capella](https://justhost.asia/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4核 / 8GB / 200GB | 750Mbit | ¥141.95 | ¥113.56 | [ 选 Rigel](https://justhost.asia/services/vps/tariffs/rigel?ref=196392) |
| Betelgeuse | 6核 / 12GB / 400GB | 750Mbit | ¥231.33 | ¥185.06 | [ 选 Betelgeuse](https://justhost.asia/services/vps/tariffs/betelgeuse?ref=196392) |
| Procyon | 12核 / 32GB / 1000GB | 1000Mbit | ¥835.95 | ¥668.76 | [ 选 Procyon](https://justhost.asia/services/vps/tariffs/procyon?ref=196392) |

两点说明。年付折后月均是按官网年付八折算的常规价，不是限时优惠码，续费同样按这个口径走，这点比“首年特价、续费翻倍”的商家好算账。Promo 那档 ¥6.93 属于引流款，10Mbit 换算下来约 1.25MB/s，放个静态页可以，跑动态站会明显卡。

套餐之间的差价主要花在三个地方：NVMe 容量、内存、带宽档位。Sirius 到 Arcturus 多花 ¥10.52 买到的是 1GB 内存和 10GB 硬盘，比从 New Star 升到 Sirius 划算；但 Arcturus 的带宽还是 300Mbit，没变。真正把带宽拉起来要从 Alpha Centauri 起。

## 你要替代的，是搬瓦工的哪一部分

搬瓦工被推荐的理由集中在三条：线路好、机房能免费一键切、有自研的 KiwiVM 面板。找替代品的人，实际需求分成三路，混在一起比价就会买错。

第一路要的是**同样的 CN2 GIA 精品线路，但价格低一点**。这一类该看 DMIT，不是 JustHost。

第二路要的是**便宜、机房多、能随时换 IP 换地区**，线路只要不难用就行。JustHost 属于这一路，机房列表里有香港、日本东京、新加坡、美国洛杉矶/西雅图/纽约/芝加哥/达拉斯/亚特兰大、加拿大多伦多、德国法兰克福，官方促销页的说法是覆盖四十多个国家、三十个以上机房，后台支持一键切换机房和 IP。

第三路只是**要一台能练手、能跑脚本的境外机器**，年付十几美元就够。这一路的选项包括 RackNerd 年付 $11.29 起，也包括 JustHost 的 Promo 档。

三路需求的预算差了一个数量级，先认清自己在哪一路，再看价格。

## $49.99/年买不到 CN2 GIA，这件事得先说清楚

搬瓦工在售套餐里，$49.99/年 和 $169.99/年 是两个世界：

| 套餐系列 | 入门配置 | 价格 | 线路 |
| --- | --- | --- | --- |
| KVM 入门 | 1核 / 1GB / 20GB SSD / 1TB | $49.99/年 | CN2 GT / 普通线路 |
| CN2 GIA-E | 1核 / 1GB / 20GB SSD / 1TB | $49.99/季，$169.99/年 | CN2 GIA |
| 香港 CN2 GIA | 1核 / 2GB / 40GB SSD / 500GB | $89.99/月，$899.99/年 | CN2 GIA + CMI + 9929 |
| 日本东京 CN2 GIA | 1核 / 2GB / 40GB SSD / 500GB | $89.99/月 | CN2 GIA + CMI |

KVM 入门和 GIA-E 的配置一字不差，价差 3.4 倍，全部差在线路上。前排不少文章把“$49.99/年”和“CN2 GIA”写在一起，读者照着买回去，晚高峰体感不对，才发现买的是普通线路那一档。

这条对选替代品同样成立。搬瓦工真正的门槛不是 $49.99，是 $169.99。拿这个数去比价，很多“便宜一半”的说法就站不住了。

另外，搬瓦工的限量版（$19/年、$49/年那一类）性价比确实高，但常年缺货，补货时间不定，不适合当成计划内的方案。

## 同样叫 CN2 GIA，$36.9/年 和 $169.99/年 差在哪

以 CN2 GIA 为共同基准，DMIT 的 LAX.Pro.WEE 是 $36.9/年，搬瓦工 GIA-E 是 $169.99/年，第一年差 $133.09，约 4.6 倍。

配置差也得一起看：DMIT 这档是 1 核 1GB、10GB SSD、1Gbps 带宽、每月 400GB 流量；搬瓦工 GIA-E 是 1 核 1GB、20GB SSD、每月 1TB 流量。硬盘少一半、流量少六成，价格差四倍多，这才是完整的对比。

这里有个容易踩的口径陷阱。DMIT 官网 $36.9 这个价位同时出现在 LAX.Pro.WEE 和 LAX.T1.WEE 两个套餐上，后者是国际线路、不含中国大陆优化。看到“$36.9 起”要先确认套餐代号，不能默认这就是 CN2 GIA。

香港方向的差距更直观。DMIT 的 HKG.Pro.TINY 是 $39.90/月，1 核 1GB、20GB SSD、400GB 流量、100Mbps 端口。一个月的起步价，差不多等于洛杉矶那档一整年的钱。洛杉矶到国内三网大约 150–180ms，香港通常在 50ms 以内，两者差 100ms 左右。这 100ms 值不值十二倍价钱，取决于你跑什么：实时对战、语音、对响应敏感的 API，值得；静态站、文件存储、定时任务，洛杉矶完全够用。

DMIT 的限制也得说：没有多机房切换，机房出问题只能等官方处理；热门档长期缺货；默认用 SSH 密钥登录，不熟悉的人第一次会卡住；Pro 以外的线路在网络攻击或成本上升时存在切路由的可能，对 CN2 GIA 有硬要求的必须选 Pro。

## JustHost 便宜在哪，哪里被砍了

JustHost 的产品描述里反复出现的是机房数量、300–750Mbit 带宽、不限流量、一键换机房换 IP、全系带 DDoS 防护，没有出现 CN2 GIA、9929、CMIN2 这些词。它的定位不是精品回国线路，是多地区、大带宽、低单价。

省下来的成本落在三处。线路是国际线路，国内访问质量取决于具体机房和时段，晚高峰不如 CN2 GIA 稳，这一点买之前要有预期。带宽标的是峰值，300Mbit 到 750Mbit 是上限，不是保底。Promo 档把配置压到 512MB 内存、5GB 硬盘、10Mbit 带宽，价格是 ¥6.93，但这个规格只能算能用，谈不上好用。

反过来，它给到的东西在同等价位不常见：三十个以上机房随便切、流量不设上限、后台自助换 IP、支付宝和银联都能付、全系 NVMe。对需要多地区节点做测试、或者业务本身要覆盖多个国家的人，这些比一条 CN2 GIA 实用。

支付方式上，信用卡、PayPal、支付宝、银联和多种加密货币都支持，国内用户不需要额外的海外账户。退款窗口是 15 天，下单页会再显示一次条款。

## 换过去之后容易卡住的几个地方

**Promo 档不要当主力机。** 512MB 内存跑 WordPress 加数据库会频繁吃满，5GB 硬盘装完系统加面板就剩不了多少。¥6.93 的意义是让你用最低成本验证机房和连通性，验证完再换 Sirius 或 Arcturus。

**不限流量不等于不限速度。** 套餐表里的 10Mbit、300Mbit、750Mbit 是端口上限，流量确实不计量，但速度卡在这个数上。买之前按业务的实际并发算一下带宽够不够，别只看“不限量”三个字。

**机房多，选错就白花钱。** 同一个套餐在不同机房的实际速度差得很远，官方给的带宽是端口规格，不是国内访问速度。下单后先用一周时间把候选机房测一遍，再决定长期挂在哪。

**换 IP 和换机房是两件事。** 后台都能自助操作，但换完 IP 之后域名解析、白名单、客户端配置都要跟着改，正在跑的业务最好挑低峰期做。

**年付折扣绑的是长周期。** 八折只在年付生效，但机器还没验证好就付一年，出了问题是自己扛。先用月付跑满一个月，确认机房和速度稳定，再转年付拿折扣，多花的这一个月钱是最便宜的保险。

👉 [先用月付开一台 Sirius 验证机房](https://justhost.asia/services/vps/tariffs/sirius?ref=196392)

## 谁不该换

要三网 CN2 GIA 优化的，别换。JustHost 不给这个，搬瓦工 GIA-E 和 DMIT Pro 才是这条路上的答案。

业务连续性强、不能接受线路波动的，别换。搬瓦工的 12 个机房免费一键切换和 30 天内可退款，是它最实在的两个功能，出问题时能立刻把业务挪走，这个能力在便宜商家那里基本找不到。

不想折腾、要随时有货的，也别换。DMIT 洛杉矶 Pro 多个规格长期无库存，JustHost 的热门档同样会缺货，搬瓦工随时能买这件事本身就是价值。

愿意为“机房多、流量不限、价格低”接受线路一般的，JustHost 值得试。这类需求本来就不该拿 CN2 GIA 的预算去衡量。

## 按场景给结论

- 预算 ¥20–30/月，要多地区机房、不限流量、能自助换 IP：JustHost 的 Sirius，年付折后月均 ¥19.72。
- 要跑 WordPress 或有数据库：至少 Arcturus（1核 2GB / 30GB），¥28.13/月（年付口径）。
- 要 CN2 GIA 三网优化、预算 $150 以上：搬瓦工 GIA-E，$169.99/年，20GB SSD + 1TB 流量。
- 要 CN2 GIA 但预算紧、能接受 10GB 硬盘和 400GB 月流量：DMIT LAX.Pro.WEE，$36.9/年，注意确认套餐代号不是 T1。
- 香港低延迟的实时业务：DMIT HKG.Pro.TINY，$39.90/月。
- 只想花十几美元练手：JustHost Promo 或 RackNerd 年付 $11.29 起，都够用。

下单前确认两件事：库存，热门档会缺货，页面显示的和实际下单时可能不一致，提交前刷新一遍；计费周期，新商家先月付，验证过再年付。

👉 [对比 JustHost 各档配置后选一台开始](https://justhost.asia/?ref=196392)

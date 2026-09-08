# Contributing / 贡献指南

Help keep this a concise, evidence-backed survey of desktop robots. English and Simplified Chinese contributions are welcome.

## Add or update a robot

1. Check both README files before adding an entry. Include robots intended for tabletop interaction, desktop companionship, education, or expressive robotics research. Explain borderline cases; floor-first pets and general industrial arms are outside the initial scope.
2. Prefer official product pages, stores, manuals, repositories, announcements, and papers. Record the date you actually checked each time-sensitive fact. Do not copy marketing prose or treat a demonstration as independently verified performance.
3. Update `README.md` and `README.zh-CN.md` together. Keep section order, robot order, explicit anchors, factual fields, and image paths identical. Each comparison row needs a complete detailed introduction and a return link.
4. Specify the exact model, bundle, currency, store region, and price date. Separate purchase availability from shipping promises. Distinguish locally running features, cloud features, optional subscriptions, and mandatory subscriptions.
5. Describe motion concretely. A swiveling head is different from walking. A public SDK is different from open robot firmware or hardware; record licenses and restrictions. Use **Unknown / 未知** for facts that cannot be confirmed.
6. Add one representative image under `assets/robots/<slug>.webp` or `.png`. Prefer reusable press assets, then official repository assets, then attributed official promotional assets. Link to the product page and place the owner and original image URL immediately below it. Preserve the complete image and existing watermarks; do not create an AI imitation. Identify research figures and pictures of a different version explicitly.
7. Keep introductions short: two to four short paragraphs, structured facts, official links, features, notes, and sources. Do not add product databases, generators, separate product pages, or a documentation tree.

## Before submitting

- Check both languages for matching anchors, ordering, prices, dates, and versions.
- Check local image paths and review the README rendering. Keep images around 800–1200 pixels wide; a padded 4:3 canvas may preserve the source without cropping.
- Follow external links and check that they lead to the intended product. A successful HTTP request does not establish stock, purchase eligibility, cloud uptime, or SDK compatibility.
- Explain corrected facts and cite the evidence in the pull request. An uncertain date or service state should remain unknown.
- Keep historically useful entries. Broken links or stopped services are reasons to annotate and investigate, not automatically remove a robot.

The link-check workflow reports potentially broken links in its job summary. It does not rewrite files, remove entries, create issues, or publish changes. HTTP 403/429 responses can require manual review; they are not proof that a product has disappeared.

## 图片和商标 / Image and trademark rights

The repository's MIT license covers original repository text and code. Third-party product images, research figures, logos, and trademarks remain the property of their respective owners and are **not relicensed under MIT**. A source link identifies provenance; it does not grant a blanket reuse license. Respect any source-specific license or media terms. Rights holders can use the error-report issue template to request corrections or removal.

## 中文说明

请同时维护中英文 README：比较表、详情顺序、锚点、事实和图片必须对应。优先引用官网、商店、说明书、官方代码仓库和论文，并记录实际核查日期。价格应注明型号、套餐、币种及地区；发售、预售、缺货、研究原型需明确区分。

不要仅凭“AI”宣传判断能力，也不要把公开 SDK 等同于整机开源。明确区分预设动画、身体摆动、桌面行走、本地处理及云端功能；无法确认的信息写“未知”。每个条目应有图片、官方链接、注意事项和来源。

图片优先使用允许转载的官方媒体素材或官方仓库资源，其次使用来源和权属明确的官方宣传图。图片应保留原有内容及水印，注明版权方和原始地址；研究配图、不同版本的产品图需明确说明。图片及商标不适用本仓库的 MIT 许可。

提交前请核对双语一致性、图片显示和链接目标。链接检查只提供待复核报告，不代表商品可购买、云服务可用或 SDK 已实测，也不会自动删除条目。

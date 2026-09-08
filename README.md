# Awesome Desktop Robots

A curated, source-linked survey of desktop robots: companion pets, developer platforms, and expressive robotics research. Compare the landscape here, then follow official links for current product details.

**English** · [简体中文](README.zh-CN.md)

<a id="scope"></a>

## Scope

This list includes physical robots designed for interaction on a desk or tabletop, including portable companions that can sit on a desk. They must have physical actuation or an embodied interaction function beyond a screen-only character. Stationary robots qualify; walking is not required.

Floor-first robot pets, cleaning robots, general industrial arms, and purely virtual pets are outside this initial scope. Research prototypes and historically relevant platforms are included with explicit status labels. This is a curated starting set, not an exhaustive market census or a ranking.

<a id="freshness"></a>

## Freshness and legend

**Last source check: 2026-09-08.** Prices, store status, languages, cloud dependencies, subscriptions, and SDK access below were checked against the linked sources on this date. An older announcement date is identified explicitly; **Unknown** means the current fact could not be confirmed. Check the official store for your region, shipping, tax, bundle contents, and checkout price.

- **AI:** A concrete perception, speech, model, or adaptive behavior capability. Claims are attributed to the developer; this repository has not tested the hardware or independently measured performance. Expressive animation alone is not evidence of AI.
- **Open source:** **Yes** identifies an openly licensed project; **Partial** may mean an open SDK or software with restricted hardware; **Unknown** means no adequate public licensing evidence was found. A public SDK does not make the entire robot open source.
- **Availability:** “On sale” means an orderable official listing, not verified delivery. A preorder, a kit with a lead time, and a research prototype are different purchase propositions.
- **Movement:** Describes actual mechanics, distinguishing body gestures from locomotion. Country/region describes the developer or project, not the factory or shipping destination.
- **Evidence limits:** Public documentation and page accessibility do not establish successful purchase, cloud uptime, SDK compatibility, or real-world reliability. No hands-on tests were performed.

<a id="comparison"></a>

## Comparison

All prices use the check date above unless a historical price is explicitly indicated. Each name opens its detailed entry below.

| Robot | Developer | Country/Region | Availability | Reference Price | AI | Movement | Open Source | SDK/API | Cloud/Subscription | Main Function |
|---|---|---|---|---|---|---|---|---|---|---|
| [EMO](#emo) | LivingAI | China | On sale; quoted ~2-week dispatch | USD 279; GO HOME USD 369 | Face/sound recognition, voice | Two-legged desktop walking | Unknown | Unknown | Online functions; subscription Unknown | Autonomous desk pet with games and reminders. |
| [AIBI Pocket](#aibi) | LivingAI | China | On sale; quoted ~2-week dispatch | USD 249 | Face recognition; offline commands, online Q&A | Turns in place; no desktop roaming documented | Unknown | Unknown | Online Q&A; subscription Unknown | Portable companion with camera and reminders. |
| [Eilik / 艾力克](#eilik) | Energize Lab | China | On sale | USD 139.99; AI Station +USD 99 | Base: AI unconfirmed; station adds vision/chat | Arm/body gestures; fixed base | Unknown | Unknown | Base offline; station cloud terms Unknown | Touch-reactive animated desk companion. |
| [Ropet KAMOMO](#ropet) | Ropet | China / USA teams | Pro on sale; Basic sold out | Pro USD 349; Basic USD 299 (sold out) | Local perception/adaptation claimed | Head/body gestures; fixed base | Unknown | Unknown | Daily interaction offline; optional cloud; fees Unknown | Plush companion with customizable fur and eyes. |
| [Moflin / モフリン](#moflin) | Casio | Japan | On sale in selected regions | USD 429 at 2025 US launch; current Unknown | Adaptive voice/touch responses claimed | Head rotation and tilt; no locomotion | Unknown | Unknown | Local interaction; app services; fees Unknown | Soft pet with nonverbal, adaptive responses. |
| [BOCCO emo](#bocco-emo) | Yukai Engineering | Japan | On sale; Wi-Fi model | JPY 52,800 incl. tax | Voice interaction; premium AI conversation | Head/body gestures; fixed base | Unknown | Public; noncommercial conditions | Cloud; basic free; premium JPY 1,700/month | Family messaging, reminders, and sensor alerts. |
| [Vector 2.0](#vector) | Anki / Digital Dream Labs | USA | On sale; store states in stock | USD 199.99 new black unit | Vision, voice, autonomous behaviors | Tracks, lift, head movement | Partial | Public legacy Python SDK | Cloud voice from USD 11.99/month | Roaming desk pet with voice services. |
| [Loona Deskmate](#loona-deskmate) | KEYi Tech / Loona | China | On sale listing; delivery Unknown | USD 299; iPhone extra | iPhone perception and cloud assistant claimed | Three-axis phone mount; fixed base | Unknown | Unknown | iPhone + cloud; subscription Unknown | Moving phone dock for AI work assistance. |
| [Reachy Mini](#reachy-mini) | Pollen Robotics / Hugging Face | France (Pollen) | Orderable DIY kits; up to 90-day lead time | Lite EUR 350; Wireless EUR 435 | Programmable vision/audio/model apps | 6-DoF head, body rotation, antennas | Partial | Public Python / JavaScript | Depends on app; model fees may apply | Expressive platform for building AI interactions. |
| [Stack-chan / ｽﾀｯｸﾁｬﾝ](#stack-chan) | Community / M5Stack | Japan / China | Open-source build; K151 on sale | K151 USD 99; DIY cost varies | Firmware-dependent; factory AI Agent | Two-axis head/body rotation; fixed base | Yes (community project) | Public | Firmware/model-dependent; fees Unknown | Small ESP32 robot for custom faces and behaviors. |
| [ELEGNT](#elegnt) | Apple research | USA | Research prototype; not offered for sale | Not applicable | Autonomous AI not established by the study | Six-axis lamp-like arm; fixed base | Unknown | Not publicly available | Unknown; research setup | Studies how motion conveys attention and intention. |
| [Cozmo](#cozmo) | Anki / Digital Dream Labs | USA | Legacy platform; 2.0 listed “coming soon” | 2.0 listed USD 399.99, sold out | Vision, cube recognition, programmed behavior | Tracks, lift, head movement | Partial | Public legacy Python SDK | App required; current service terms Unknown | Cube games and introductory robot programming. |

<a id="emo"></a>

## EMO

<p align="center">
  <a href="https://living.ai/emo/"><img src="assets/robots/emo.webp" width="760" alt="EMO two-legged AI desktop pet with headphones and skateboard charger"></a>
</p>
<p align="center"><sub>Official promotional image © LivingAI · <a href="https://living.ai/wp-content/uploads/2020/12/product2-1024x1024.jpg">Source</a></sub></p>

> An expressive desk pet that actually walks around its tabletop environment.

### Overview

LivingAI describes EMO as a camera-equipped companion that recognizes faces, locates sounds, and explores a desk. Its screen and body motions support games, reactions, and everyday reminders.

The standard package includes a skateboard charger and smart light. The separately priced GO HOME package adds the home-station proposition; check its contents before comparing prices. Recognition and navigation performance are manufacturer claims.

### Product information

| Item | Details |
|---|---|
| Product name | EMO; EMO GO HOME variant |
| Developer / Organization | LivingAI |
| Country / Region | China; manufacturer filing names Living Technology (Shenzhen) |
| Product type | Commercial desktop companion |
| Availability | On sale; official standard listing quotes dispatch in about 2 weeks |
| First released | Unknown; exact first shipment date not confirmed |
| Reference price | USD 279 standard; USD 369 GO HOME, checked 2026-09-08 |
| AI capabilities | Manufacturer claims face recognition, sound localization, and voice interaction |
| Movement | Two-legged desktop walking, turning, and dancing |
| Open source | Unknown; no full robot source release identified |
| SDK/API | Unknown; no current official SDK entry found in reviewed support pages |
| Main functions | Autonomous desk pet with games, reminders, photos, and smart-light interaction |
| Supported languages | English commands documented; complete current language list Unknown |
| Network requirement | App setup and network-dependent services; complete offline feature boundary Unknown |
| Cloud dependency | Online assistant/weather functions; complete local/cloud split Unknown |
| Subscription | Unknown; no current subscription terms confirmed |
| Power and charging | Rechargeable; standard skateboard wireless charger; home station is a different package/accessory |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [EMO](https://living.ai/emo/)
- **Official store:** [Standard EMO](https://living.ai/product/emo/) · [All packages](https://living.ai/store/)
- **Project repository:** Unknown
- **Documentation:** [Play with EMO](https://living.ai/play-with-emo/)
- **SDK/API:** Unknown
- **Support:** [LivingAI support](https://living.ai/support/)
- **Official videos:** [Usage videos](https://living.ai/play-with-emo/)
- **Press kit:** Unknown

### Main features

- Physical desk exploration with camera and microphone sensing.
- Expressive face animations, games, alarms, and photography.
- Charging and smart-light accessories with package-dependent contents.

### Notes

The older product presentation includes future-feature language. Do not assume its proposed integrations have shipped. The claimed edge detection is not a guarantee against falls; this repository has not tested it.

### Sources

- [Product presentation](https://living.ai/emo/) — capabilities and charging; [current store](https://living.ai/store/) — package prices.
- [Standard listing](https://living.ai/product/emo/) — contents and dispatch estimate; [support](https://living.ai/support/) — available help resources.
- [Manufacturer's FCC filing, mirrored by FCC.report](https://fcc.report/FCC-ID/2AZ6REMO1/5311794.pdf) — manufacturer identity/location; not a product review.

[↑ Back to comparison](#comparison)

<a id="aibi"></a>

## AIBI Pocket

<p align="center">
  <a href="https://living.ai/aibi/"><img src="assets/robots/aibi.webp" width="760" alt="AIBI Pocket portable AI companion robot with camera on its charging base"></a>
</p>
<p align="center"><sub>Official promotional image © LivingAI · <a href="https://living.ai/wp-content/uploads/2023/12/2023121521.png">Source</a></sub></p>

> A portable companion combining face recognition, local commands, and online questions.

### Overview

AIBI is LivingAI's smaller portable companion. Official examples include photos, animated weather reports, alarms, and reminders. Its turn-in-place motions differ from EMO's desk exploration.

The manufacturer explicitly distinguishes offline voice commands from online Q&A using ChatGPT. The product presentation still says preorder, while the actual store accepts orders with a dispatch estimate; the latter determines the listing status here.

### Product information

| Item | Details |
|---|---|
| Product name | AIBI Pocket |
| Developer / Organization | LivingAI |
| Country / Region | China; LivingAI manufacturer location, see EMO source |
| Product type | Commercial portable / desktop companion |
| Availability | On sale; store quotes dispatch in about 2 weeks |
| First released | Unknown; first shipment date not confirmed |
| Reference price | USD 249, checked 2026-09-08 |
| AI capabilities | Face recognition; offline voice commands and online Q&A, per manufacturer |
| Movement | Turns in place; independent desktop roaming not documented |
| Open source | Unknown |
| SDK/API | Unknown; no current official SDK identified |
| Main functions | Portable companion with camera, animated reactions, alarms, and reminders |
| Supported languages | English commands documented; complete current list Unknown |
| Network requirement | Some commands work offline; Q&A/weather require connectivity |
| Cloud dependency | Online Q&A uses ChatGPT; offline commands remain a separate mode |
| Subscription | Unknown; current paid-service terms not confirmed |
| Power and charging | Rechargeable with charging accessories; current capacity/runtime Unknown |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [AIBI](https://living.ai/aibi/)
- **Official store:** [AIBI Pocket](https://living.ai/product/aibi-pocket/)
- **Project repository:** Unknown
- **Documentation:** [Play with AIBI](https://living.ai/play-with-aibi/)
- **SDK/API:** Unknown
- **Support:** [LivingAI support](https://living.ai/support/)
- **Official videos:** [AIBI usage videos](https://living.ai/play-with-aibi/)
- **Press kit:** Unknown

### Main features

- Camera-based recognition and photography.
- Documented offline command subset.
- Portable form with expressive screen and turning motions.

### Notes

Do not read “offline commands” as an offline general-purpose language model. Current language coverage and cloud-service eligibility should be confirmed for the intended region.

### Sources

- [Product presentation](https://living.ai/aibi/) — perception and offline/online distinction.
- [Store listing](https://living.ai/product/aibi-pocket/) — price and dispatch; [support command list](https://living.ai/support/) — commands marked for offline use.
- [LivingAI manufacturer filing](https://fcc.report/FCC-ID/2AZ6REMO1/5311794.pdf) — company location, not an AIBI specification sheet.

[↑ Back to comparison](#comparison)

<a id="eilik"></a>

## Eilik / 艾力克

<p align="center">
  <a href="https://energizelab.com/consumerview/eilik"><img src="assets/robots/eilik.webp" width="760" alt="Eilik 艾力克 animated desktop companion with arms and fixed circular base"></a>
</p>
<p align="center"><sub>Official promotional image © Energize Lab · <a href="https://store.energizelab.com/cdn/shop/products/eilik-buy-overview-1.jpg?v=1660634933">Source</a></sub></p>

> A touch-reactive desk companion whose base behavior does not require internet access.

### Overview

Eilik responds to touch and vibration with screen expressions, sounds, and four-servo body animation. Connected units can perform shared interactions. The robot itself stays on its base.

The base product's “emotional intelligence” language does not establish general voice or vision AI. The separately sold AI Station adds camera-based and conversational features, so its capabilities and cost are listed separately.

### Product information

| Item | Details |
|---|---|
| Product name | Eilik; optional Eilik AI Station |
| Developer / Organization | Energize Lab / Shenzhen Zhuneng Technology |
| Country / Region | China |
| Product type | Commercial animated desktop companion |
| Availability | On sale; AI Station separately listed as in stock |
| First released | Unknown; exact first shipment date not confirmed |
| Reference price | Eilik USD 139.99; AI Station adds USD 99, checked 2026-09-08 |
| AI capabilities | Base: meaningful voice/vision AI unconfirmed; AI Station advertises vision and AI chat |
| Movement | Arm/body gestures through four servos; fixed base, no independent locomotion |
| Open source | Unknown |
| SDK/API | Unknown; firmware updater is not a public robot-control SDK |
| Main functions | Touch-reactive animated desk companion, mini-games, and multi-Eilik interactions |
| Supported languages | Base mainly uses animations/sounds; AI Station's complete language list Unknown |
| Network requirement | Base works without Wi-Fi or internet; updates use the official tool |
| Cloud dependency | Base interaction offline; AI Station's full processing/service boundary Unknown |
| Subscription | Base interaction needs no online service; AI Station fees Unknown |
| Power and charging | USB-C, 5 V / 1 A; 450 mAh; claimed 1.5-hour runtime and 1-hour charge |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Eilik](https://energizelab.com/consumerview/eilik)
- **Official store:** [Eilik](https://store.energizelab.com/products/eilik) · [AI Station](https://store.energizelab.com/products/ai-station)
- **Project repository:** Unknown
- **Documentation:** [Manual and update tools](https://www.energizelab.com/downloads)
- **SDK/API:** Unknown
- **Support:** [Energize Lab support](https://energizelab.com/support)
- **Official videos:** [Product demonstrations](https://energizelab.com/consumerview/eilik)
- **Press kit:** Unknown

### Main features

- Tactile reactions, mini-games, and animated body language.
- Interactions between multiple Eilik units.
- Optional AI Station expands the base robot's functions.

### Notes

AI Station is an additional purchase; the quoted base price does not include it. Panxer is another accessory and does not make the base Eilik a mobile robot. Review accessory-specific service terms separately.

### Sources

- [Base product and FAQ](https://store.energizelab.com/products/eilik) — price, offline operation, power.
- [Product overview](https://energizelab.com/consumerview/eilik) — motion and touch interaction.
- [AI Station](https://store.energizelab.com/products/ai-station) — separate hardware and claims; [company website](https://www.energizelab.com/) — organization/location.

[↑ Back to comparison](#comparison)

<a id="ropet"></a>

## Ropet KAMOMO

<p align="center">
  <a href="https://ropetai.com/"><img src="assets/robots/ropet.webp" width="760" alt="Ropet KAMOMO plush desktop AI pet, Pro bundle with charging base"></a>
</p>
<p align="center"><sub>Official promotional image © Ropet · Pro bundle pictured · <a href="https://ropetai.com/cdn/shop/files/ropet_Pro.png?v=1773906287">Source</a></sub></p>

> A plush desk pet built around local interactions and a replaceable appearance.

### Overview

Ropet presents KAMOMO as a companion whose reactions change through daily care. A camera, microphone, expressive eyes, and physical gestures support its pet-like behavior; the manufacturer describes ordinary interaction as local processing.

The FAQ describes an optional Dream Sketch feature using cloud image processing; its rollout status is Unknown. This exception matters when evaluating the otherwise offline positioning. Basic and Pro bundles differ, including whether a charging base is included.

### Product information

| Item | Details |
|---|---|
| Product name | Ropet KAMOMO; Basic and Pro bundles |
| Developer / Organization | Ropet |
| Country / Region | China / USA teams; company lists Beijing, Shenzhen, Hong Kong, and Washington |
| Product type | Commercial plush desktop companion |
| Availability | Pro on sale; Basic marked out of stock in the store's variant data; shipping estimates vary |
| First released | Unknown; company founding in 2022 is not a product release date |
| Reference price | Pro USD 349; Basic listed USD 299 but out of stock, checked 2026-09-08 |
| AI capabilities | Local image/audio processing and behavior adaptation claimed by developer |
| Movement | Head/body gestures on a fixed base; no locomotion documented |
| Open source | Unknown |
| SDK/API | Unknown |
| Main functions | Plush companion with customizable fur, masks, and screen eyes |
| Supported languages | Unknown; do not equate pet sounds with conversational language support |
| Network requirement | Daily interaction claimed to work offline; app/account functions need connectivity |
| Cloud dependency | Optional Dream Sketch uses cloud processing; ordinary interaction described as local |
| Subscription | Unknown; no complete current service fee schedule confirmed |
| Power and charging | Rechargeable; claimed 2.5–3.5 hours; Basic excludes the charging base |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Ropet](https://ropetai.com/)
- **Official store:** [KAMOMO bundles](https://ropetai.com/products/ropet%E2%84%A2-ai-comfort-companion-plush-robot)
- **Project repository:** Unknown
- **Documentation:** [Product FAQ](https://ropetai.com/products/ropet%E2%84%A2-ai-comfort-companion-plush-robot)
- **SDK/API:** Unknown
- **Support:** [Contact Ropet](https://ropetai.com/pages/contact)
- **Official videos:** [Official product demonstrations](https://ropetai.com/)
- **Press kit:** Unknown

### Main features

- Local perception and adaptive pet behavior, according to the developer.
- Replaceable fur, face masks, and eye styles.
- Optional cloud feature documented separately from ordinary interaction.

### Notes

Promotional banners and bundle selectors showed different bundle prices during this check. The values here are from the named Basic/Pro selector and variant data, not the headline promotion; Basic was marked out of stock. Confirm checkout. The pictured Pro bundle includes a base that Basic does not.

### Sources

- [KAMOMO listing and FAQ](https://ropetai.com/products/ropet%E2%84%A2-ai-comfort-companion-plush-robot) — named bundles, battery, and processing claims.
- [About Ropet](https://ropetai.com/pages/about-ropet) — organization and locations.
- [Privacy policy](https://ropetai.com/policies/privacy-policy) — app/account connectivity and data handling; [homepage](https://ropetai.com/) — positioning and promotions.

[↑ Back to comparison](#comparison)

<a id="moflin"></a>

## Moflin / モフリン

<p align="center">
  <a href="https://www.casio.com/us/moflin/"><img src="assets/robots/moflin.webp" width="760" alt="Casio Moflin モフリン silver and gold soft companion robots on a table"></a>
</p>
<p align="center"><sub>Official press image © Casio · <a href="https://www.casio.co.jp/content/casio/locales/jp/ja/corporate/release/2024/1010-moflin/_jcr_content/root/responsivegrid/container_489163755_/container/container/container_570173118_/image_copy.casiocoreimg.jpeg/1728535554672/img01.jpeg">Source</a></sub></p>

> A soft, nonverbal companion that reacts through small movements and pet-like sounds.

### Overview

Casio's Moflin uses voice, touch, and motion sensing to vary its responses. Its adaptive personality and owner recognition are manufacturer-described behaviors, expressed through head motion and sounds.

It can rest on a desk or be held. The MofLife app provides a view into its state and settings. It is not presented here as a general conversational assistant, and marketing about comfort is not evidence of medical effectiveness.

### Product information

| Item | Details |
|---|---|
| Product name | Moflin / モフリン; PE-M10 series |
| Developer / Organization | Casio |
| Country / Region | Japan |
| Product type | Commercial soft companion; handheld / tabletop |
| Availability | On sale in selected regions; official US and Japan listings exist |
| First released | Casio Japan launch: 2024-11-07; earlier development/crowdfunding is a separate milestone |
| Reference price | USD 429 at 2025 US launch; current checkout price Unknown, checked 2026-09-08 |
| AI capabilities | Adaptive voice/touch responses and owner recognition, per Casio |
| Movement | Two axes: head rotation and tilt; no independent locomotion |
| Open source | Unknown |
| SDK/API | Unknown |
| Main functions | Soft pet with nonverbal, adaptive responses and app-based state viewing |
| Supported languages | Nonverbal robot; complete regional app language coverage Unknown |
| Network requirement | Local robot interaction; smartphone/Bluetooth for app functions |
| Cloud dependency | Local behavior; connected app/data-service details depend on region |
| Subscription | Unknown; distinguish optional support plans from basic robot operation |
| Power and charging | Charging bed and AC adapter; 1,200 mAh; claimed ~5-hour use, ~3.5-hour charge |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [US](https://www.casio.com/us/moflin/) · [Japan](https://www.casio.com/jp/moflin/)
- **Official store:** [Moflin Silver, US](https://www.casio.com/us/moflin/product.PE-M10SR/)
- **Project repository:** Unknown
- **Documentation:** [PE-M10 online manual](https://support.casio.com/global/en/moflin/manual/PE-M10_en/)
- **SDK/API:** Unknown
- **Support:** [Casio Moflin support](https://www.casio.com/us/support/moflin/)
- **Official videos:** [Product page demonstrations](https://www.casio.com/us/moflin/)
- **Press kit:** [Official launch release and photos](https://www.casio.co.jp/release/2024/1010-moflin/)

### Main features

- Compact plush body with two-axis movement.
- Adaptive responses to repeated interaction, according to Casio.
- Charging bed and companion app.

### Notes

The USD price is explicitly historical: the current product page did not expose a verifiable checkout price in this check. Availability, app distribution, warranty, and optional care plans vary by region.

### Sources

- [Casio product overview](https://www.casio.com/us/moflin/) — behavior and current specifications.
- [Japan launch announcement](https://www.casio.co.jp/release/2024/1010-moflin/) — release date and press photo.
- [Casio's US launch press release](https://www.prnewswire.com/news-releases/casio-introduces-moflin-the-emotionally-responsive-smart-companion-that-learns-and-evolves-with-you-302558268.html) — historical USD 429 price.
- [Official manual](https://support.casio.com/global/en/moflin/manual/PE-M10_en/) — operation and app setup.

[↑ Back to comparison](#comparison)

<a id="bocco-emo"></a>

## BOCCO emo / ボッコ エモ

<p align="center">
  <a href="https://www.bocco.me/en/"><img src="assets/robots/bocco-emo.webp" width="760" alt="Yukai Engineering BOCCO emo ボッコ エモ tabletop family communication robot"></a>
</p>
<p align="center"><sub>Official promotional image © Yukai Engineering · <a href="https://store.ux-xu.com/cdn/shop/products/product_bocco_emo.jpg?v=1592317204">Source</a></sub></p>

> A tabletop family communication robot with messaging, reminders, and sensor connections.

### Overview

BOCCO emo relays app messages, supports voice interaction, and connects to household sensors. Physical gestures and colored cheeks make alerts and responses visible without a conventional display.

The current Premium plan adds generative conversation and remembered interactions. The Wi-Fi model's basic messaging and information features remain free under the published plan description; the LTE rental model has separate terms.

### Product information

| Item | Details |
|---|---|
| Product name | BOCCO emo Wi-Fi model; YE-RB010-GWNJP |
| Developer / Organization | Yukai Engineering |
| Country / Region | Japan |
| Product type | Commercial tabletop family communication robot |
| Availability | On sale through the official Japan store; Wi-Fi model |
| First released | Unknown; exact first retail date not confirmed in this check |
| Reference price | JPY 52,800 including Japanese tax, checked 2026-09-08 |
| AI capabilities | Voice interaction; Premium plan adds generative conversation and voice-linked memory |
| Movement | Head/body gestures on a fixed base |
| Open source | Unknown; public cloud API is not a full robot source release |
| SDK/API | Public Platform API; developer/noncommercial conditions apply |
| Main functions | Family messaging, reminders, sensor alerts, and optional AI conversation |
| Supported languages | Japanese service documented; equivalent support in other languages Unknown |
| Network requirement | Wi-Fi 2.4 GHz and smartphone for the listed model |
| Cloud dependency | Messaging, platform integration, and AI conversation depend on online services |
| Subscription | Wi-Fi basic functions free; optional Premium JPY 1,700/month incl. tax |
| Power and charging | 100–240 V AC adapter; mains-powered tabletop use |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [BOCCO emo](https://www.bocco.me/en/)
- **Official store:** [Wi-Fi model](https://store.ux-xu.com/products/bocco-emo)
- **Project repository:** Unknown; full robot firmware not identified
- **Documentation:** [User manual](https://www.bocco.me/wp-content/uploads/2021/01/emo_manual_2_20210115.pdf)
- **SDK/API:** [Platform API](https://platform-api.bocco.me/api-docs/)
- **Support:** [Official usage and service information](https://www.bocco.me/living/premium/)
- **Official videos:** [Product demonstrations](https://www.bocco.me/en/)
- **Press kit:** [Official media folder](https://drive.google.com/drive/folders/1-w-wBQUaqldAOIboJrrlws2fdXj6QtxP)

### Main features

- Voice/text messages between family members and the robot.
- Sensor-linked notifications and scheduled reminders.
- Public integration API and optional paid generative conversation.

### Notes

The Premium guide documents conversation quotas and states that real-time information is not supported. API availability does not imply unrestricted commercial use. The reference price is for outright purchase of the Wi-Fi model, not LTE rental.

### Sources

- [Official store](https://store.ux-xu.com/products/bocco-emo) — price, model, network and power.
- [English overview](https://www.bocco.me/en/) — messaging and sensor functions.
- [Premium guide](https://www.bocco.me/living/premium/) — fees, free basic functions, and limitations; [Premium terms](https://www.bocco.me/terms-premium/) — external AI services.
- [API announcement](https://www.bocco.me/appnews/20211012/) — developer/noncommercial access; [Platform API](https://platform-api.bocco.me/api-docs/) — documentation entry point.

[↑ Back to comparison](#comparison)

<a id="vector"></a>

## Vector 2.0

<p align="center">
  <a href="https://anki.bot/products/vector-robot"><img src="assets/robots/vector.webp" width="760" alt="Anki Digital Dream Labs Vector 2.0 tracked desktop robot with lifting arm"></a>
</p>
<p align="center"><sub>Official promotional image © Anki / Digital Dream Labs · <a href="https://anki.bot/cdn/shop/files/Vector_Product_ArmsUp_swap_1000px_d2c99795-151d-4095-8534-804920b159ed.jpg?v=1788848061">Source</a></sub></p>

> A tracked desktop companion with autonomous behaviors and subscription-based cloud voice services.

### Overview

Vector combines a camera, expressive screen, tracked drive, and small lift. The current official store lists Vector 2.0 alongside open-box and OSKR variants; those are distinct offers with different prices and intended users.

The original Anki Python SDK remains publicly accessible. Community-maintained wire-pod offers a self-hosted voice-service alternative, but requires a separate setup and is not the manufacturer's hosted subscription service.

### Product information

| Item | Details |
|---|---|
| Product name | Vector 2.0; legacy Vector 1.0 is a different hardware generation |
| Developer / Organization | Anki originally; Digital Dream Labs / current Anki-branded store |
| Country / Region | USA |
| Product type | Commercial autonomous desktop companion |
| Availability | On sale; official store states in stock with one-business-day dispatch |
| First released | Unknown for the exact 2.0 retail configuration listed here |
| Reference price | New black Vector 2.0 USD 199.99; open-box listing starts at USD 139.99, checked 2026-09-08 |
| AI capabilities | Vision, voice services, and autonomous pet behaviors; current model integrations are vendor claims |
| Movement | Tracks for desktop locomotion; movable head and lift |
| Open source | Partial: public SDK and selected server components; not a fully open robot |
| SDK/API | Public legacy Python SDK; compatibility with current firmware not tested |
| Main functions | Roaming desk pet with voice interaction and cube play |
| Supported languages | English documented; complete current backend-specific list Unknown |
| Network requirement | Wi-Fi/internet for official cloud voice; self-hosted alternative needs a local server |
| Cloud dependency | Official voice service uses vendor cloud; some autonomous behavior remains without a membership |
| Subscription | ChatGPT backend USD 11.99/month or 99.99/year; Claude backend USD 14.99/month or 139.99/year |
| Power and charging | Rechargeable with charging dock; verify included charger for each condition/bundle |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Vector](https://anki.bot/products/vector-robot)
- **Official store:** [Vector 2.0 and condition variants](https://anki.bot/products/vector-robot)
- **Project repository:** [Original Anki Vector SDK](https://github.com/anki/vector-python-sdk)
- **Documentation:** [SDK documentation source](https://github.com/anki/vector-python-sdk/tree/master/docs)
- **SDK/API:** [Python SDK](https://github.com/anki/vector-python-sdk)
- **Support:** [Anki / DDL support](https://support.anki.bot/)
- **Official videos:** [Product demonstrations](https://anki.bot/products/vector-robot)
- **Press kit:** Unknown

### Main features

- Autonomous tracked motion and expressive screen reactions.
- Official cloud voice service with backend-dependent membership prices.
- Legacy SDK and a separate community self-hosting route.

### Notes

The public SDK repository is historical evidence of developer access, not proof of a working current setup. [wire-pod](https://github.com/kercre123/wire-pod) is an **unofficial** alternative whose installation and optional external model services must be evaluated separately. Neither cloud path was tested here.

### Sources

- [Current store](https://anki.bot/products/vector-robot) — hardware prices, condition variants, stock statement, and subscription boundary.
- [Membership guide, updated 2026-08-10](https://support.anki.bot/article/344-all-about-memberships) — backend-specific fees and activation.
- [Original SDK](https://github.com/anki/vector-python-sdk) — public developer interface; [wire-pod project](https://github.com/kercre123/wire-pod) — community server scope.

[↑ Back to comparison](#comparison)

<a id="loona-deskmate"></a>

## Loona Deskmate

<p align="center">
  <a href="https://keyirobot.com/en-us/products/deskmate"><img src="assets/robots/loona-deskmate.webp" width="760" alt="KEYi Loona Deskmate three-axis desktop phone dock with iPhone character display"></a>
</p>
<p align="center"><sub>Official promotional image © KEYi Tech / Loona · Phone shown for demonstration · <a href="https://cdn.shopify.com/s/files/1/0750/4170/2077/files/gallery-deskmate-obsidian-1-v1.webp?v=1782099702">Source</a></sub></p>

> An actuated iPhone dock that gives an AI work assistant a physical desktop presence.

### Overview

Loona Deskmate uses a mounted iPhone for sensing and interaction, with a three-axis motorized base. The vendor advertises meeting preparation, draft replies, reminders, and connections to workplace tools.

Its product page describes on-iPhone processing of facial and attention signals, while task commands go to cloud services. These are vendor claims. This is a different product from the floor-moving Loona Petbot.

### Product information

| Item | Details |
|---|---|
| Product name | Loona Deskmate / DeskMate; Obsidian listing |
| Developer / Organization | KEYi Tech / Loona |
| Country / Region | China; company history identifies Beijing |
| Product type | Commercial motorized phone dock / AI desk assistant |
| Availability | Official US listing has Buy Now; delivery timing Unknown |
| First released | Introduced at CES in January 2026; first delivery date Unknown |
| Reference price | USD 299, excluding the required iPhone, checked 2026-09-08 |
| AI capabilities | Vendor claims iPhone-based perception, cloud conversation, memory, and connected work tasks |
| Movement | Three-axis yaw/pitch/roll phone mount; fixed base |
| Open source | Unknown |
| SDK/API | Unknown; advertised MCP integrations do not establish a public hardware SDK |
| Main functions | Moving phone dock for AI work assistance, draft preparation, and reminders |
| Supported languages | Unknown; webpage translations do not prove voice-language support |
| Network requirement | Compatible iPhone and online services; official page specifies iPhone 12+ |
| Cloud dependency | Explicit task commands use cloud; face/attention processing claimed to stay on iPhone |
| Subscription | Unknown; complete current pricing and entitlement terms not found |
| Power and charging | Mains-powered dock; Qi2 phone charging advertised; see power-specification discrepancy below |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Deskmate](https://keyirobot.com/en-us/products/deskmate)
- **Official store:** [US listing](https://keyirobot.com/en-us/products/deskmate)
- **Project repository:** Unknown
- **Documentation:** [Product specifications](https://keyirobot.com/en-us/products/deskmate)
- **SDK/API:** Unknown
- **Support:** [Loona support center](https://supportcenter.keyirobot.com/en/)
- **Official videos:** [Product demonstrations](https://keyirobot.com/en-us/products/deskmate)
- **Press kit:** Unknown

### Main features

- Physical orientation and phone-based animated interaction.
- Claimed integrations for calendars, email drafts, and meeting context.
- Phone charging alongside the motorized desk mount.

### Notes

An iPhone is required and is not included in the USD 299 reference price. The page lists 165 W power delivery but a 180 W charger in the box; these may describe different ratings and were not reconciled here. Assistant integrations, latency, and privacy claims have not been independently tested.

### Sources

- [US product listing](https://keyirobot.com/en-us/products/deskmate) — price, required phone, movement, cloud claims, and power labels.
- [Company history](https://keyirobot.com/about-us) — developer origin.
- [Official launch/news index](https://keyirobot.com/blogs/news) — January 2026 introduction; [Japan presentation](https://makuake.keyirobot.com/) — phone compatibility context.

[↑ Back to comparison](#comparison)

<a id="reachy-mini"></a>

## Reachy Mini

<p align="center">
  <a href="https://huggingface.co/blog/reachy-mini"><img src="assets/robots/reachy-mini.webp" width="760" alt="Pollen Robotics Hugging Face Reachy Mini Lite expressive desktop robot with antennas"></a>
</p>
<p align="center"><sub>Official promotional image © Pollen Robotics / Hugging Face · Lite pictured · <a href="https://store.pollen-robotics.com/cdn/shop/files/reachy-mini-lite.png?v=1776692700">Source</a></sub></p>

> A programmable desktop body for experimenting with vision, audio, and AI applications.

### Overview

Reachy Mini provides expressive head motion, rotating body, antennas, camera, microphones, and a speaker. The Lite version runs through a connected computer; Wireless adds onboard Raspberry Pi CM4 computing and a battery.

The project publishes SDKs, examples, and simulation resources. AI behavior depends on the installed application and model. Its hardware-design license includes a noncommercial restriction, so this list classifies openness as partial despite the product's open-source positioning.

### Product information

| Item | Details |
|---|---|
| Product name | Reachy Mini Lite / Reachy Mini Wireless |
| Developer / Organization | Pollen Robotics / Hugging Face |
| Country / Region | France for Pollen Robotics; store states design in Bordeaux and manufacture in China |
| Product type | Developer / education desktop robot kit |
| Availability | Both kits orderable; store quotes up to 90 days lead time |
| First released | Announced 2025-07-09; shipment dates depend on version/batch |
| Reference price | Lite EUR 350; Wireless EUR 435 in the observed EUR storefront, checked 2026-09-08 |
| AI capabilities | Programmable vision/audio/model applications; capabilities depend on app and compute |
| Movement | Six-degree-of-freedom head, body rotation, and two animated antennas; no locomotion |
| Open source | Partial: SDK Apache-2.0; hardware design files described as CC BY-SA-NC, a noncommercial restriction |
| SDK/API | Public Python and JavaScript interfaces |
| Main functions | Expressive platform for building AI interactions and robotics experiments |
| Supported languages | Application/model-dependent; no single robot-wide language guarantee |
| Network requirement | Lite uses USB-C with a computer; Wireless offers Wi-Fi/onboard compute |
| Cloud dependency | Application-dependent; local control and simulation are available |
| Subscription | No mandatory robot subscription identified; chosen cloud/model providers may charge |
| Power and charging | Lite includes mains supply; Wireless adds battery and power supply |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Project introduction](https://huggingface.co/blog/reachy-mini)
- **Official store:** [Lite](https://store.pollen-robotics.com/products/reachy-mini-lite-version) · [Wireless](https://store.pollen-robotics.com/products/reachy-mini-wireless-version)
- **Project repository:** [reachy_mini](https://github.com/pollen-robotics/reachy_mini)
- **Documentation:** [Official SDK and guides](https://github.com/pollen-robotics/reachy_mini#readme)
- **SDK/API:** [SDK source](https://github.com/pollen-robotics/reachy_mini)
- **Support:** [Project issue tracker](https://github.com/pollen-robotics/reachy_mini/issues)
- **Official videos:** [Introduction and demos](https://huggingface.co/blog/reachy-mini)
- **Press kit:** Unknown

### Main features

- Coordinated head/body/antenna expression with audio and camera access.
- Public programming interfaces and MuJoCo simulation resources.
- Computer-connected and onboard-compute variants.

### Notes

These are assembly kits, not guaranteed ready-to-use conversational companions. The old USD 299/449 announcement is not substituted for the current observed EUR listing. Review hardware licenses before commercial reuse and confirm destination-specific shipping/tax.

### Sources

- [Launch announcement](https://huggingface.co/blog/reachy-mini) — date and concept.
- [Lite store](https://store.pollen-robotics.com/products/reachy-mini-lite-version) · [Wireless store](https://store.pollen-robotics.com/products/reachy-mini-wireless-version) — current prices, hardware, origin, and lead time.
- [Project README and license description](https://github.com/pollen-robotics/reachy_mini) — SDKs, simulation, and hardware-license restriction.

[↑ Back to comparison](#comparison)

<a id="stack-chan"></a>

## Stack-chan / ｽﾀｯｸﾁｬﾝ / M5StackChan

<p align="center">
  <a href="https://github.com/stack-chan/stack-chan"><img src="assets/robots/stack-chan.webp" width="760" alt="Stack-chan ｽﾀｯｸﾁｬﾝ M5StackChan K151 ESP32-S3 desktop robot with two-axis base"></a>
</p>
<p align="center"><sub>Official promotional image © M5Stack · K151 pictured · <a href="https://shop.m5stack.com/cdn/shop/files/1_29c1c66c-6170-4270-ba77-7d3bf4793c7b_1200x1200.webp?v=1776925002">Source</a></sub></p>

> A small community robot with customizable faces, two-axis motion, and accessible firmware.

### Overview

Stack-chan is a community project around M5Stack hardware, with firmware, case files, schematics, and browser tools. The current community README recommends the preassembled M5StackChan K151 as a starting configuration.

M5Stack's factory firmware and the community JavaScript firmware are distinct software choices. Factory features include an AI Agent; community users can build their own behaviors and integrations. Installing community firmware replaces the factory version.

### Product information

| Item | Details |
|---|---|
| Product name | Stack-chan / ｽﾀｯｸﾁｬﾝ; M5StackChan K151 commercial configuration |
| Developer / Organization | Shinya Ishikawa and community; M5Stack hardware |
| Country / Region | Japan / China; community origin and M5Stack hardware organization |
| Product type | Open-source DIY project with a commercial hardware option |
| Availability | Open-source build; K151 official store lists stock |
| First released | Community project: 2021; K151 first shipment date Unknown |
| Reference price | M5StackChan K151 USD 99; DIY build cost varies, checked 2026-09-08 |
| AI capabilities | Firmware-dependent; K151 factory AI Agent and camera/audio integrations documented |
| Movement | Two-axis rotation/tilt; fixed base; K151 lists 360° horizontal and 90° vertical motion |
| Open source | Yes for the community project under Apache-2.0; do not extend this to every factory component/service |
| SDK/API | Public community firmware/API; M5Stack documents Arduino and UiFlow2 development |
| Main functions | Small ESP32 robot for custom faces, behaviors, and AI integration |
| Supported languages | Firmware/model-dependent; no uniform project-wide spoken-language guarantee |
| Network requirement | K151 supports 2.4 GHz Wi-Fi and BLE; cloud AI needs network access |
| Cloud dependency | Depends on firmware/application; local custom behaviors are possible |
| Subscription | Current factory/model-service fees Unknown; third-party integrations can have separate costs |
| Power and charging | K151 USB-C power/data and 550 mAh battery; DIY builds vary |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Community project](https://github.com/stack-chan/stack-chan)
- **Official store:** [M5StackChan K151](https://shop.m5stack.com/products/stackchan-kawaii-co-created-open-source-ai-desktop-robot)
- **Project repository:** [stack-chan](https://github.com/stack-chan/stack-chan)
- **Documentation:** [M5Stack hardware/factory guide](https://docs.m5stack.com/en/StackChan) · [Community guides](https://github.com/stack-chan/stack-chan/tree/develop/docs)
- **SDK/API:** [Community firmware API](https://github.com/stack-chan/stack-chan/blob/develop/firmware/docs/api.md)
- **Support:** [Community issues](https://github.com/stack-chan/stack-chan/issues)
- **Official videos:** [Creator introduction](https://youtu.be/fZb_mF08xV0)
- **Press kit:** Unknown

### Main features

- Open community firmware, printable cases, and schematics.
- Browser firmware installer, face tools, and behavior development.
- K151 integrates camera, microphones, touch sensing, and two servos.

### Notes

Use the documentation for the exact hardware and firmware combination. K151 specifications and price do not describe every community build. A firmware swap changes the feature set; the public project explains how to restore factory firmware.

### Sources

- [Community repository](https://github.com/stack-chan/stack-chan) — project history, license, supported boards, and firmware distinction.
- [K151 store](https://shop.m5stack.com/products/stackchan-kawaii-co-created-open-source-ai-desktop-robot) — configuration, price, and inventory statement.
- [K151 documentation](https://docs.m5stack.com/en/StackChan) — factory AI, network, motion, and power.

[↑ Back to comparison](#comparison)

<a id="elegnt"></a>

## ELEGNT — expressive lamp robot research

<p align="center">
  <a href="https://machinelearning.apple.com/research/elegnt-expressive-functional-movement"><img src="assets/robots/elegnt.webp" width="760" alt="Apple ELEGNT research figure showing a six-axis lamp-like robot and interaction modalities"></a>
</p>
<p align="center"><sub>Research figure © the ELEGNT authors / Apple · Figure 4 from the authors' paper, not a retail product photo · <a href="https://arxiv.org/html/2501.12493v1/figure/prototype2.png">Source</a></sub></p>

> A research example of conveying attention and intention through the movement of an everyday object.

### Overview

ELEGNT investigates expressive motion with a lamp-like robot. The authors compare functional movement with movements designed to convey internal states through posture, timing, and orientation.

The paper uses staged interaction scenarios and a video-based user study. It offers design evidence for desktop interaction, not a purchasable Apple robot or proof of a production autonomous assistant.

### Product information

| Item | Details |
|---|---|
| Product name | ELEGNT research framework and lamp-like prototype |
| Developer / Organization | Apple researchers: Yuhan Hu, Peide Huang, Mouli Sivapurapu, Jian Zhang |
| Country / Region | USA; paper lists Apple, Cupertino |
| Product type | Research prototype / human–robot interaction study |
| Availability | Not offered for sale in the cited research publication |
| First released | Research publication: January 2025; not a commercial release |
| Reference price | Not applicable |
| AI capabilities | Autonomous AI not established by this study; expressive motion and interaction research |
| Movement | Six-axis lamp-like arm on a fixed base |
| Open source | Unknown; publication does not establish an open implementation |
| SDK/API | Not publicly available in the cited research materials |
| Main functions | Studies how motion conveys attention and intention alongside practical tasks |
| Supported languages | Unknown; not a supported consumer language specification |
| Network requirement | Unknown; research setup, no consumer setup contract |
| Cloud dependency | Unknown |
| Subscription | Not applicable to this research prototype |
| Power and charging | Unknown; consumer power and charging specifications not published |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Apple research page](https://machinelearning.apple.com/research/elegnt-expressive-functional-movement)
- **Official store:** Not publicly available; research prototype
- **Project repository:** Unknown
- **Documentation:** [Authors' paper](https://arxiv.org/html/2501.12493v1)
- **SDK/API:** Not publicly available
- **Support:** Not publicly available; research publication only
- **Official videos:** [Apple-hosted demonstration](https://machinelearning.apple.com/research/elegnt-expressive-functional-movement)
- **Press kit:** Unknown; attributed research figure used above

### Main features

- A lamp form factor for expressive desktop movement.
- Functional and expressive movement objectives considered together.
- Published user-study methodology and interaction examples.

### Notes

The study involved 21 participants evaluating videos across six task scenarios. It does not demonstrate long-term real-world operation or establish a consumer release, cloud service, or purchase price. The image is a paper figure rather than a promotional retail asset.

### Sources

- [Apple research summary](https://machinelearning.apple.com/research/elegnt-expressive-functional-movement) — project scope and demonstration.
- [Authors' paper, sections 3–4](https://arxiv.org/html/2501.12493v1) — prototype, scripted study setup, evaluation, and figure provenance.

[↑ Back to comparison](#comparison)

<a id="cozmo"></a>

## Cozmo — legacy platform and announced 2.0

<p align="center">
  <a href="https://anki.bot/products/cozmo-robot"><img src="assets/robots/cozmo.webp" width="760" alt="Anki Digital Dream Labs Cozmo 2.0 promotional rendering of a tracked educational desk robot"></a>
</p>
<p align="center"><sub>Official promotional image © Anki / Digital Dream Labs · Announced Cozmo 2.0 pictured; not proof of shipment · <a href="https://anki.bot/cdn/shop/products/Cozmo2.0-500x405_5.jpg?v=1658947111">Source</a></sub></p>

> A historically important cube-playing robot with a public Python programming interface.

### Overview

The original Cozmo combines a tracked body, lift, camera, and phone/tablet application for cube games and programming. Its publicly available SDK makes it relevant to desktop robotics learning even as the surrounding software ecosystem ages.

The current store advertises Cozmo 2.0 improvements but labels the robot “coming soon” and sold out. This entry distinguishes the established legacy platform from those unverified next-generation delivery claims.

### Product information

| Item | Details |
|---|---|
| Product name | Cozmo legacy platform; announced Cozmo 2.0 |
| Developer / Organization | Anki originally; Digital Dream Labs / current Anki-branded store |
| Country / Region | USA |
| Product type | Historical educational tabletop robot; announced successor |
| Availability | Legacy platform; 2.0 store listing says coming soon / sold out |
| First released | Exact legacy release date not reverified; 2.0 first delivery Unknown |
| Reference price | Cozmo 2.0 listed at USD 399.99 but sold out, checked 2026-09-08; legacy resale price not tracked |
| AI capabilities | Vision/cube recognition and programmed behavior; 2.0 enhancements remain vendor claims |
| Movement | Tracked locomotion, head motion, and lifting arm |
| Open source | Partial: original Python SDK source public; not the complete robot |
| SDK/API | Public legacy Python SDK; current app/OS/firmware compatibility untested |
| Main functions | Cube games and introductory robot programming |
| Supported languages | Current app/region language support Unknown |
| Network requirement | Compatible smartphone/tablet and Cozmo app required; legacy robot/app connection |
| Cloud dependency | App-dependent operation; current setup/service availability Unknown |
| Subscription | Current service terms Unknown; do not apply Vector membership terms to Cozmo |
| Power and charging | Rechargeable robot with charger; verify charger, cube batteries, and battery condition when buying used |
| Last verified | 2026-09-08 |

### Official links

- **Official website:** [Cozmo](https://anki.bot/products/cozmo-robot)
- **Official store:** [Cozmo 2.0 listing and accessories](https://anki.bot/products/cozmo-robot)
- **Project repository:** [Original Cozmo Python SDK](https://github.com/anki/cozmo-python-sdk)
- **Documentation:** [SDK documentation source](https://github.com/anki/cozmo-python-sdk/tree/master/docs)
- **SDK/API:** [Python SDK](https://github.com/anki/cozmo-python-sdk)
- **Support:** [Anki / DDL support](https://support.anki.bot/)
- **Official videos:** [Official product presentation](https://anki.bot/products/cozmo-robot)
- **Press kit:** Unknown

### Main features

- Cube manipulation and expressive tracked motion.
- App-based coding activities and legacy Python examples.
- Useful historical reference for approachable robot interaction.

### Notes

A working SDK repository does not guarantee that current phones can install or run the required app. Verify a complete working setup before buying a used unit. Do not present a 2.0 promotional image or a displayed price as proof of an available shipment.

### Sources

- [Current Cozmo page](https://anki.bot/products/cozmo-robot) — app requirement, 2.0 positioning, price, and availability labels.
- [Original Anki SDK](https://github.com/anki/cozmo-python-sdk) — legacy public API and documentation source.

[↑ Back to comparison](#comparison)

<a id="contributing"></a>

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) to add robots or correct information. Update both languages together and include dated official sources. Use the repository's **Add a robot** or **Report an error** issue templates for suggestions and corrections.

Original repository text and code are covered by [MIT](LICENSE). Product images, research figures, logos, and trademarks belong to their respective owners and are **not relicensed under MIT**. Image citations record provenance, not blanket reuse permission. The initial image set uses attributed official promotional/press assets and one identified research figure; source-specific reuse terms still apply.

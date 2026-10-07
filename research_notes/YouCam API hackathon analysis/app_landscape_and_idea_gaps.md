# AI Skin Analysis & Virtual Try-On: App Landscape, Prior Hackathon Clone Map, and Under-served Niches (for a YouCam API hackathon entry, as of 2026-10-07)

> Scope note for the report writer: the single most decision-relevant finding is that Perfect Corp already ran a near-identical Devpost hackathon in Jul–Aug 2026 ("YouCam API Skin AI & Apparel VTO Hackathon", 238 public submissions). Many of the "non-obvious" ideas in the brief were already built there, and some of them won. The current target hackathon appears to be the follow-up "YouCam API Skin AI & eCommerce VTO Hackathon" (deadline Nov 2, 2026). The clone map in Key Question 6 should drive idea selection more than the consumer-app landscape does.

---

## Key Question 1: Existing consumer apps and features. What is common or commoditized?

### Takeaway
"Selfie → skin scores → product recommendations", "AR makeup/hair-color/eyewear try-on on a product page", and, since 2025–26, "conversational AI beauty advisor that runs a diagnostic and recommends products" are all commoditized. Large brands and retailers ship them, and Perfect Corp powers many of them, including Clinique, Madison Reed and its own YouCam AI Agent. Generative apparel try-on from a photo is now a Google feature (Search/Shopping and the Doppl app). A hackathon team should treat all of these as baseline plumbing, not as the idea.

### Cited Findings

**Brand / retailer skin analysis (commoditized):**
- L'Oréal Paris **Beauty Genius**: AI assistant with selfie skin and hair diagnostics, recommendations from 750+ L'Oréal Paris products, AR try-on and custom routines. Launched on the L'Oréal Paris USA website and WhatsApp; more than 1.2M consumer conversations in the US. It connects to major US retailers, and L'Oréal cites "70% of consumers feel overwhelmed by too many beauty choices." — [L'Oréal](https://www.loreal.com/en/articles/science-and-technology/loreal-paris-beauty-genius/)
- Beauty Genius was unveiled in Paris in July 2025. It was trained on 150,000+ dermatologist annotations and tested with 10,000+ products in 50 countries. A WhatsApp version via a Meta partnership was announced for 2026. — [RetailBoss](https://retailboss.co/loreal-launches-advanced-beauty-genius-ai-assistant-for-global-rollout/)
- **Clinique Clinical Reality**: a 30-second "skinalysis" that plots 80+ data points against models built on 1M+ face scans. It covers pores/texture, uneven tone, fatigue, irritation, redness, acne, wrinkles and sagging, plus a foundation shade match with VTO. — [Clinique](https://clinique.com/clinicalreality/landing). Developed with Perfect Corp, it reportedly raised conversions 2.5x with a 30% larger basket (vendor-reported figure, surfaced in search results for [Clinique NZ](https://www.clinique.co.nz/clinicalreality) and [Glossy](https://www.glossy.co/beauty/clinique-development-ai-skin-analysis); not independently verified).
- **Neutrogena Skin360**: first launched in 2018 with a hardware attachment, then relaunched as camera-only. The current version combines skin imaging, behavior coaching and an AI assistant ("NAIA") that starts text conversations. It is still active, not discontinued. — [Global Cosmetics News](https://www.globalcosmeticsnews.com/neutrogena-relaunches-skin360-app-with-ai-functionality/); [Drug Store News](https://drugstorenews.com/neutrogena-relaunches-its-skin360-app)
- **La Roche-Posay SpotScan+**: free, dermatologist co-developed AI acne analysis. It uses 3 selfies and scores against the Global Acne Severity Scale (GEA), trained on 6,000 images across phototypes. — [L'Oréal](https://www.loreal.com/en/articles/science-and-technology/la-roche-posay-spotscan); [La Roche-Posay CA](https://www.laroche-posay.ca/en_CA/spotscan.html)
- **Olay Skin Advisor**: a web selfie tool that estimates "skin age", billed as the first deep-learning application in beauty. — [El Diario NY / LatinoWire](https://eldiariony.com/latinowire/olay-unveils-global-skin-analysis-platform-olay-skin-advisor-the-first-of-its-kind-application-of-deep-learning-in-the-beauty-industry)
- **Sephora Skincare IQ**: an in-store tool that asks deductive questions (not a selfie scan) and cross-references 1,200+ SKUs from 60 brands for 10 concerns. — [Drug Store News](https://drugstorenews.com/news/new-sephora-skincare-iq-aims-revolutionize-retail-skin-care-consultations)
- **Ulta GlamLab** skin analysis: facial recognition plus a survey (skin type, age, up to 3 of 8 goals), with recommendations shoppable in-app. — [Yahoo/Allure](https://sports.yahoo.com/ulta-beautys-app-skin-care-163809512.html)
- **Nykaa Skin Scan** (India): a single selfie analyzes tone, texture, hydration, ageing, dark spots and pores. — [T2 Online](https://t2online.in/goodlife/fashion-beauty/looking-back-at-how-artificial-intelligence-redefined-fashion-and-beauty-in-2025/2002928). Orbo AI launched a plug-and-play skin analysis + VTO platform in Mumbai in April 2025. — [RetailBoss](https://retailboss.co/orbo-ai-introduces-unified-platform-for-ai-skin-analysis-and-virtual-try-ons-redefining-personalized-beauty/)
- **Haut.AI SkinGPT**: generative "skin simulation" (aging, UV, active ingredients, routine effects over time), commercially available to brands for product pages. Haut.AI works with Beiersdorf and Ulta. — [Haut.AI](https://haut.ai/skingpt); [Personal Care Insights](https://www.personalcareinsights.com/news/hautai-makes-skingpt-commercially-available-for-beauty-brands.html); [Cosmetics Design Europe](https://cosmeticsdesign-europe.com/Article/2025/01/16/skingpt-tackles-skin-cares-biggest-challenge-proving-product-claims-with-ai)

**Perfect Corp's own first-party offerings (things a hackathon entry should NOT re-build as-is):**
- **YouCam AI Agent** (CES 2026): conversational beauty assistant. From a single selfie plus real-time dialogue, it analyzes skin concerns, learns preferences, recommends products, routines and looks, and guides comparisons. — [Perfect Corp CES 2026](https://www.perfectcorp.com/business/news/ces-2026-perfect-corp); [BusinessWire](https://www.businesswire.com/news/home/20251219606970/en/Perfect-Corp.-Unveils-Next-Generation-AI-Beauty-Agent-and-API-Innovations-Transforming-Beauty-Skincare-and-Retail-at-CES-2026)
- The CES 2026 lineup includes:
  - AR makeup try-on and AI makeup transfer
  - Hair color and hairstyle try-on
  - AR ring, bracelet, watch, earring and necklace try-on
  - AI eyewear try-on
  - AI clothes, AR shoes, scarf and bag try-on
  - Nail color try-on
  - AI Skin Analysis "with Validator", AI Skin Simulation and a Face Analyzer/Reshape simulator
  - Fitzpatrick skin type analysis
  - Hair type, length, frizz and density analysis

  YouCam apps have 1.1B+ downloads. — [Perfect Corp CES 2026](https://www.perfectcorp.com/business/news/ces-2026-perfect-corp)
- All YouCam APIs support native MCP through 3 MCP servers (Beauty & Personal Care, Fashion & Retail, Creators) and 6 ready-made Agent Skills. Additional API categories include smile enhancement, teeth whitening, body reshape, fabric, hats, image/video generation and face swap. — [YouCam MCP page](https://yce.perfectcorp.com/ai-api/agent/mcp-skill)
- **Hair & Beard API suite** (June 15–16, 2026): 11 APIs covering color, style, extensions, bangs, texture, volume and beard try-on, plus hair diagnostics including frizz. It targets barbers, salons and retailers. — [Perfect Corp](https://www.perfectcorp.com/business/news/HairBeardAPI); [American Salon](https://www.americansalon.com/business/new-ai-hair-beard-try-tools-can-analyze-hair-health-too)

**Try-on for other categories (commoditized):**
- **Madison Reed** hair color VTO (40+ shades, live camera or selfie, split-screen slider) was built with Perfect Corp. It reports a 38% conversion improvement for quiz + VTO users. — [Perfect Corp success story](https://www.perfectcorp.com/business/successstory/Madison-Reed); [Marketing Dive](https://www.marketingdive.com/news/dtc-beauty-brand-madison-reed-brings-ar-try-ons-to-hair-coloring/540654/)
- **Warby Parker** AR glasses try-on (iPhone X+ face mapping, since 2019). — [Retail Dive](https://www.retaildive.com/news/warby-parker-launches-ar-tool-for-virtual-try-on/547673)
- **Amazon**: AR shoe try-on in the Amazon Shopping app (Adidas, New Balance, Puma, Reebok), and thousands of eyewear models as Snapchat Lenses via Amazon 3D assets. — [Retail Dive](https://www.retaildive.com/news/amazon-fashion-snapchat-augmented-reality-eyewear-lenses/635689/); [Marketing Dive](https://www.marketingdive.com/news/amazon-fashion-snapchat-ar-marketing-shopping-lenses/635690/)
- **Google Search/Shopping**: Gemini-based try-on of multiple makeup products at once (lipstick, mascara, eyeshadow, liner), with "See the looks on you" for trend searches. AR assets come from brands such as CoverGirl, Dior, Fenty, Laura Mercier, Makeup by Mario and Pat McGrath. Clothing try-on expanded to pants and skirts, and the features moved from Labs into Search/Shopping. — [CO/AI](https://getcoai.com/news/googles-ai-shopping-tools-let-you-create-and-virtually-try-on-clothing-and-makeup); [Retail TouchPoints](https://www.retailtouchpoints.com/topics/digital-commerce/google-brings-advanced-ai-capabilities-to-search-including-virtual-try-on-agentic-checkout)
- **Google Doppl** (Google Labs, June 26, 2025): upload a full-body photo, then "try on" any outfit photo or screenshot, with AI-generated motion video of you in the outfit. US only, iOS/Android, experimental. — [Google blog](https://blog.google/innovation-and-ai/models-and-research/google-labs/doppl/); [Gigazine](https://gigazine.net/gsc_news/en/20250627-google-launches-doppl-visualize-outfit/)
- **TikTok Shop** offers AR try-ons (glasses, hats, makeup). Live shopping grew sharply in 2025, and TikTok Shop became the UK's 4th-largest beauty retailer in 2025. — [EchoTik](https://www.echotik.live/blog/tiktok-shop-tiktok-seller-official-site-2025-features/); [Retail-News.de](https://retail-news.de/tiktok-shop-beauty-uk-2025/) (secondary/trade-blog sources; growth figures not verified against primary data)

**Ingredient apps (common):**
- **OnSkin**: ingredient checker and product scanner covering skincare, makeup, hair and household products. It claims 8M+ users and a 2M-product database, rates products Excellent/Good/Not Great/Bad, suggests safer alternatives and has an acne-safe "Skin Match". — [App Store](https://apps.apple.com/lb/app/id1630768985)

**Discontinued / changed:**
- **Sephora Virtual Artist** (in-app AR makeup try-on): customers were told in 2022 that the feature was discontinued, and community posts complain about its removal. — [Sephora Community](https://community.sephora.com/t5/Customer-Support/Virtual-Artist/m-p/6209161)

### Inferences
- **Commoditized:**
  - Single-selfie skin scoring with routine recommendations
  - AR lipstick, foundation and hair-color try-on
  - AR eyewear and shoe try-on
  - Generative "upload any outfit → see it on you" (Doppl, Google Shopping)
  - Brand-captive AI beauty chat assistants (Beauty Genius, NAIA, YouCam AI Agent)
- **Exists but niche or weak:**
  - Multi-brand, retailer-neutral skin advice (only retailer-scoped versions such as Sephora Skincare IQ and Ulta)
  - Generative "future skin" simulation (Haut.AI SkinGPT, YouCam Skin Simulation; B2B, not consumer-facing)
  - Messaging-channel advisors (Beauty Genius on WhatsApp; few others found)
- Brand tools recommend only their own catalog: Beauty Genius draws from 750+ L'Oréal Paris products, and Clinique's tool recommends Clinique. This supports the user complaint of "upsell bias", although no direct survey of that complaint was found.

### Gaps
- No primary sources were fetched for:
  - CeraVe, No7, Garnier and Schwarzkopf apps
  - Yuka (cosmetics mode), Think Dirty, TroveSkin, Skin Bliss
  - Glasses.com
  - Tiffany, Cartier and Mejuri ring try-on
  - Ulta GlamLab in 2025–26 (the cited source is from 2020)

  Their current (2025–26) status is unverified.
- Whether Olay Skin Advisor and Ulta GlamLab skin analysis are still live in 2026 was not confirmed.
- Snapchat/Amazon eyewear lens dates were not confirmed from the fetched snippets.

---

## Key Question 2: What do users complain these apps lack?

### Takeaway
Recurring complaints fall into five groups:
1. **Inaccuracy and instability:** scores jump between scans, and features are misidentified.
2. **Bias on darker skin tones and lighting sensitivity.**
3. **Untrustworthy shade matching.**
4. **Over-claiming:** VTO is "not a fit guarantee", and generative try-on silently alters the face.
5. **Inaccessibility** for blind or low-vision shoppers.

Winning entries in the prior YouCam hackathon turned several of these complaints into features: honesty labels, error bars, identity-preservation checks and accessibility.

### Cited Findings
- A tester found an AI skin app misidentified milia as blackheads, and her skin score jumped from "average" to "very good" between scans with no visible change. — [Bustle](https://www.bustle.com/p/do-ai-skin-apps-actually-work-i-tested-out-5-heres-what-i-found-19253267)
- Smartphone skin photos vary with lighting, focus, angle, shadow, skin tone and camera model. Models trained on images that under-represent darker skin perform worse on those skin tones. — [Forefront Dermatology](https://forefrontdermatology.com/ai-skin-apps-and-professional-diagnosis/)
- Dermatologist commentary on the limits of consumer face analyzers. — [LovelySkin](https://www.lovelyskin.com/blog/p/board-certified-dermatologists-weigh-in-on-ai-face-analyzers); [DermApproved](https://dermapproved.com/blog/ai-skin-analysis-apps-useful-or-gimmick/)
- Shade-match frustration:
  - Sephora community users report shade-match tools returning no match or a completely wrong shade family. — [Sephora Community](https://community.sephora.com/t5/Makeup-Is-Life/Foundation-Shade-Match/m-p/6450015)
  - A Product Hunt maker argues that a HEX swatch looks different on every screen and that labels like "light medium, neutral" are too broad. Users therefore crowd-source "shade twins" on Reddit, TikTok and YouTube. — [Product Hunt: ShadeTwin](https://www.producthunt.com/products/shadetwin-app)
- Users complained about losing Sephora Virtual Artist, which suggests demand for try-on persists when a retailer removes it. — [Sephora Community](https://community.sephora.com/t5/Customer-Support/Virtual-Artist/m-p/6209161)
- **Accessibility gap:**
  - Beauty e-commerce relies on visuals (swatches, ingredient panels) and is unusable with screen readers. Sephora (2017), Ulta (2019) and Fenty Beauty (2019) were sued over inaccessible e-commerce, and the European Accessibility Act became enforceable in June 2025.
  - The Aloud team states that Perfect Corp carried no accessibility statement before their project. (Claims made by the Aloud hackathon team; the litigation details were not independently verified.) — [Devpost: Aloud](https://devpost.com/software/aloud-lxqr70)
- **Generative VTO alters identity:** AI try-on can change glasses, face, hair or skin without the user noticing (KeepMe's problem statement). — [Devpost: KeepMe](https://devpost.com/software/keepme)
- **Over-claiming fit:** the ConfidFit team learned that "product language has to stay careful" and shipped an "Honest Label": "visual preview only. It is not a fit guarantee." — [Devpost: ConfidFit](https://devpost.com/software/confidfit)

### Inferences
- **Trust, not more features, is the main unmet need:** calibrated confidence, explaining why a score changed, disclosing accuracy bias, and keeping the face unaltered. Prior winners leaned into this hard. CASTING's "Methods" panel, ConfidFit's Honest Label and Aloud's accuracy-bias disclosure are all examples.
- Many entries in the previous hackathon (TOLERANCE, Assay, MirrorProof ×2, FitCheck Studio, DrapeProof, MirrorKey) attacked the same trust gap. The trust angle is now crowded, so a new entry needs a different user or context, not just another honesty layer.
- The brief's hypothesized complaints were not directly evidenced by sources found here: no progress tracking, no tie to affordable products, no social or group features, no explanation. They remain plausible but uncited.

### Gaps
- No systematic App Store or Google Play review mining was done (no review corpus was fetched). Complaint frequencies are unknown.
- A JAMA Dermatology study on the harm of AI dermatology apps and a "63% unwilling to rely on AI" survey were mentioned in a search summary, but the primary source was not identified. Do not cite them.

---

## Key Question 3: eCommerce integration landscape. What would a "drop-in" tool for small DTC beauty brands look like?

### Takeaway
Shopify already has several plug-and-play beauty VTO and shade-finder apps, including Perfect Corp's own YouCam Makeup plugin, Auglio (with a starter plan), Gleame and Match My Makeup. A prior YouCam hackathon winner, ConfidFit, shipped a Shopify apparel VTO app that is live on the Shopify App Store. A small-brand drop-in therefore needs more than a "try-on button". Its differentiation would be skin-analysis-driven matching within the merchant's own catalog, merchant cost controls and analytics, and content generation.

### Cited Findings
- Perfect Corp's **YouCam Makeup plugin for Shopify** targets small and medium brands. It needs no coding, and Perfect Corp claims up to 2.5x conversion. — [Perfect Corp blog](https://www.perfectcorp.com/business/blog/makeup/plug-play-virtual-try-on-for-shopify-beauty-merchants); [BusinessWire 2020](https://www.businesswire.com/news/home/20201005005392/en/Perfect-Corp.-Launches-New-YouCam-Makeup-App-for-Shopify-as-the-Digital-First-E-Commerce-Solution-to-Drive-Online-Beauty-Sales)
- **Match My Makeup Shade Finder** (Shopify): cross-brand shade lookup or a quiz of fewer than 5 questions, plus VTO for complexion, lip and cheek. — [Shopify App Store](https://apps.shopify.com/shade-finder-virtual-try-on)
- **Gleame** (Shopify): AI try-on showing how beauty, skincare, haircare or wellness products would "transform" the shopper. — [Shopify App Store](https://apps.shopify.com/gleame)
- **Auglio** cosmetics VTO for Shopify added a Starter Plan for emerging brands. — [Auglio](https://auglio.com/es/news/article/75-whats-new-in-auglios-shopify-try-on-app-for-cosmetics)
- **Revieve** offers skincare/makeup advisors, foundation matching and hair-color VTO to brands and retailers, and is a direct Perfect Corp competitor. — [CB Insights](https://www.cbinsights.com/compare/perfect-corp-vs-revieve)
- **ConfidFit** (prior YouCam hackathon, 3rd–5th place) is a Shopify app using YouCam cloth-v3. Its design:
  - Theme app block, with an App Proxy hiding the API key
  - Async task polling with a worker process
  - Consent before photo upload
  - Blocking of intimate apparel and swimwear
  - Merchant go-live checklist, tiered billing, cohort analytics and per-user budget "fairness controls"

  It is live on the Shopify App Store. — [Devpost: ConfidFit](https://devpost.com/software/confidfit)
- **TryOnReady** ("Virtual try-on that a small boutique can actually run") and **onpoint** ("AI try-on + real inventory + fit-aware checkout for African fashion storefronts") were also submitted to the prior hackathon. — [Devpost gallery p.8](https://youcam-api.devpost.com/project-gallery?page=8); [Devpost gallery p.7](https://youcam-api.devpost.com/project-gallery?page=7)
- Return-reduction claims for VTO range from a 25% to a 64% reduction, alongside a claimed 30% return drop for Sephora Virtual Artist. These come from vendor and aggregator stat pages, not primary studies, so treat them as low reliability. — [Morphed stats](https://morphed.app/stats/virtual-try-on-statistics); [FreeYourself](https://freeyourself.com/blogs/news/virtual-try-on-beauty-technology-statistics)

### Inferences
- **Likely shape of a credible small-brand drop-in (inference):**
  1. A Shopify theme app block or embeddable script, with a server-side proxy for the API key.
  2. Skin analysis plus Fitzpatrick and facial-color analysis that maps the shopper to the merchant's own SKUs, rather than a generic catalog.
  3. Honest labeling and consent.
  4. Unit-budget guards, because API units cost money.
  5. A merchant dashboard that turns aggregate (anonymized) skin-concern data into merchandising insight, such as "40% of your scanners have deeper skin tones but your best-selling shade is light".
  6. A GenAI content tab that renders the merchant's shades or garments on diverse panels.

  Item 6 overlaps with prior winners CASTING and ShadeSpan.
- No clear incumbent was found for a drop-in aimed specifically at **indie skincare** (not makeup) brands that ties a skin-analysis result to *which of the brand's 5–20 SKUs* fits. Gleame and Match My Makeup skew toward makeup and transformation previews. This should be verified on the Shopify App Store before building.

### Gaps
- The Shopify App Store was not fetched for skincare-quiz-specific apps (e.g., Octane AI, Revieve's Shopify presence) or for review counts.
- Prose and Function of Beauty quiz flows and WooCommerce plugins were not researched.
- Agentic checkout (e.g., ChatGPT shopping) integration with VTO was not researched beyond Google's agentic checkout mention. — [Retail TouchPoints](https://www.retailtouchpoints.com/topics/digital-commerce/google-brings-advanced-ai-capabilities-to-search-including-virtual-try-on-agentic-checkout)

---

## Key Question 4: B2B and professional tools (med-spa, esthetician, salon, barber, teledermatology, pharmacy)

### Takeaway
Clinics have an entrenched gold standard: Canfield VISIA hardware (now VISIA 3D) and practice-management suites such as Pabau that embed AI skin analysis and treatment simulation. Teledermatology lesion triage (SkinVision, Skin Analytics DERM) is a regulated medical space and outside YouCam's cosmetic positioning. The lower-cost, phone-based pro segment is far less served: freelance estheticians, brow and lash artists, makeup artists, barbers and pharmacy beauty counters. That is the more plausible hackathon whitespace.

### Cited Findings
- **Canfield VISIA** tracks 8 metrics (spots, wrinkles, texture, pores, UV spots, RBX brown, RBX red, UV porphyrins). It grades skin against same-age and same-type peers, and offers AI aging simulation and wrinkle algorithms. It is positioned as the med-spa consultation standard and now integrates VECTRA 3D in VISIA 3D. — [Canfield](https://www.canfieldsci.com/in-the-news/stories/harnessing-ai-in-consultations-revolutionizing-precision-and-efficiency/); [Canfield VISIA 3D](https://www.canfieldsci.com/in-the-news/stories/canfield-scientific-premieres-next-generation-visia-skin-analysis.-now-in-3d.)
- **Pabau AI Studio** sits inside the client card. From a client photo it returns a ranked list of treatable concerns (area, priority, confidence, matching treatments, next step) and generates a simulated treatment result. — [Pabau](https://pabau.com/features/ai-studio/)
- Perfect Corp markets apps to estheticians. — [Perfect Corp blog](https://www.perfectcorp.com/business/blog/ai-skincare/best-apps-for-estheticians)
- Perfect Corp's Hair & Beard suite explicitly targets barbers and salons for "digital consultation platforms". — [Perfect Corp](https://www.perfectcorp.com/business/news/HairBeardAPI)
- Teledermatology:
  - **SkinVision** offers mole and lesion risk assessment with dermatologist connection. — [Medical Futurist](https://medicalfuturist.com/digital-skin-care-top-8-dermatology-apps)
  - **Skin Analytics** received a NICE recommendation for early NHS use (May 2025) and introduced DERM Zero, a smartphone version (June 2026, per search summary; unverified). — [YesPress](https://yespress.io/skin-analytics.md)
  - **Google DermAssist** was announced for a 2021 pilot; its current status was not confirmed. — [HealthExec](https://healthexec.com/topics/healthcare-management/healthcare-economics/googleplex-comes-free-ai-tool-skin-diagnostics)
- **In-store retail:** Tata CLiQ Palette's Mumbai store has AR makeup trials and skin-analyser mirrors. — [Inc42](https://inc42.com/?p=409661)
- **Prior-hackathon B2B angles:**
  - **EloVHERA** ("Most marketplaces verify your bank details. We verify sellers can actually read skin") verifies beauty sellers' skill. — [Devpost gallery p.7](https://youcam-api.devpost.com/project-gallery?page=7)
  - **ShowVibe** gives real estate agents outfit staging. — [Devpost gallery p.8](https://youcam-api.devpost.com/project-gallery?page=8)
  - **NGABONZIMA WorkerCare** pairs skin AI with industrial safety in Africa. — [Devpost gallery p.9](https://youcam-api.devpost.com/project-gallery?page=9)
  - **GlamCode OS** turns YouCam hair color and beard try-on into a real salon appointment. — [Devpost gallery p.5](https://youcam-api.devpost.com/project-gallery?page=5)

### Inferences
- **Exists and is common:** clinic-grade imaging (VISIA) and clinic practice-management AI (Pabau).
- **Exists but niche:** salon or barber try-on-to-booking flows (GlamCode OS in the prior hackathon; Perfect Corp markets its Hair & Beard API for this).
- **No clear incumbent found:**
  - Phone-based intake for solo estheticians or mobile makeup artists: consent, standardized photo capture, YouCam scores, before/after comparison and rebooking reminders. It would be a "VISIA-lite for people who can't afford VISIA".
  - A barber "cut spec card" that turns a client's chosen beard or hairstyle try-on into a handoff for the barber.
  - A pharmacist counter mode.
- Medical triage (lesions, cancer) should be avoided. It conflicts with YouCam's cosmetic scope, and prior winner Aloud explicitly linted out medical language. — [Devpost: Aloud](https://devpost.com/software/aloud-lxqr70)

### Gaps
- No sources were retrieved on Observ, "Bella Skin AI", pharmacy beauty-counter software or barber-specific consultation apps (e.g., booking apps with try-on). Their existence and features are unverified.
- Esthetician software pricing, which would support the "VISIA too expensive" argument, was not retrieved.

---

## Key Question 5: Non-obvious and emerging application patterns. Status of each candidate, checked against incumbents AND prior YouCam hackathon submissions

### Takeaway
Most of the brief's candidate ideas were already built in the July–August 2026 YouCam hackathon, which had 238 public submissions, and several of them won:
- Conversational agents
- Progress trackers and product-efficacy proofs
- Ingredient matchers
- Wedding and group planners
- Salon booking
- Chrome extensions
- WhatsApp bots
- Accessibility for blind users
- Resale try-on
- Content generation for small brands
- Climate and cycle skin apps
- Returns dashboards

Whitespace remains in four areas:
- **Categories that hackathon was not about:** makeup, nail, jewelry/watch, eyewear and the June 2026 Hair & Beard APIs. The current hackathon's "eCommerce VTO" track explicitly covers beauty.
- **Specific under-served users:** teens with guardrails, solo pros, oncology/medical camouflage, live-stream hosts.
- **B2B "API as measuring instrument" for beauty (not apparel):** for example, foundation-range coverage audits.
- **Non-shopper roles in commerce:** customer service, merchandising, sales associates.

### Cited Findings: status of each brief candidate
(Legend: **COMMON** = exists and common; **NICHE** = exists but niche or poorly done; **PRIOR-HACK** = already built in a previous YouCam/Perfect Corp hackathon; **OPEN** = no clear incumbent found.)

| Candidate idea | Status | Evidence |
|---|---|---|
| LLM agent + YouCam (diagnose → recommend → VTO) | COMMON + PRIOR-HACK (heavily) | YouCam AI Agent ([Perfect Corp](https://www.perfectcorp.com/business/news/ces-2026-perfect-corp)); Beauty Genius ([L'Oréal](https://www.loreal.com/en/articles/science-and-technology/loreal-paris-beauty-genius/)); YouCam MCP ([YouCam](https://yce.perfectcorp.com/ai-api/agent/mcp-skill)); prior submissions SkinSense Agent, RetailMind AI, Holistic Mirror, LookGen AI, Last Look, CounterLook, naxora ([p.8](https://youcam-api.devpost.com/project-gallery?page=8), [p.9](https://youcam-api.devpost.com/project-gallery?page=9), [p.3](https://youcam-api.devpost.com/project-gallery?page=3), [p.7](https://youcam-api.devpost.com/project-gallery?page=7), [p.10](https://youcam-api.devpost.com/project-gallery?page=10)); MirraAI in the Pegasus hackathon ([gallery](https://perfectcorphackathon.devpost.com/project-gallery)) |
| Routine/progress tracker with timelapse scores | COMMON + PRIOR-HACK | Neutrogena Skin360 tracking ([GCN](https://www.globalcosmeticsnews.com/neutrogena-relaunches-skin360-app-with-ai-functionality/)); Glowdays, Derma Glow, PerfectSkinDiary, Grapht, My Skin Loop, DERMA, Skinova ([p.2](https://youcam-api.devpost.com/project-gallery?page=2), [p.3](https://youcam-api.devpost.com/project-gallery?page=3), [p.10](https://youcam-api.devpost.com/project-gallery?page=10), [p.6](https://youcam-api.devpost.com/project-gallery?page=6), [p.8](https://youcam-api.devpost.com/project-gallery?page=8), [p.9](https://youcam-api.devpost.com/project-gallery?page=9), [p.5](https://youcam-api.devpost.com/project-gallery?page=5)) |
| "Does this product actually work?" efficacy proof | PRIOR-HACK (crowded) | Face Value, Pruv, Assay, TOLERANCE, DERMA, Ritual Proof (supplements), Slept On (sleep) ([p.5](https://youcam-api.devpost.com/project-gallery?page=5), [p.4](https://youcam-api.devpost.com/project-gallery?page=4), [p.7](https://youcam-api.devpost.com/project-gallery?page=7), [p.9](https://youcam-api.devpost.com/project-gallery?page=9), [p.2](https://youcam-api.devpost.com/project-gallery?page=2)); B2B equivalent Haut.AI SkinGPT for claims ([CDE](https://cosmeticsdesign-europe.com/Article/2025/01/16/skingpt-tackles-skin-cares-biggest-challenge-proving-product-claims-with-ai)) |
| Ingredient-aware matcher (skin analysis + INCI) | COMMON (scanners) + PRIOR-HACK | OnSkin 8M users ([App Store](https://apps.apple.com/lb/app/id1630768985)); Skingredient, OurSkinOurFuture ([p.4](https://youcam-api.devpost.com/project-gallery?page=4), [p.10](https://youcam-api.devpost.com/project-gallery?page=10)); Spectra ([Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)); Aloud used EU CosIng (33,116 ingredients) + Open Beauty Facts ([Aloud](https://devpost.com/software/aloud-lxqr70)) |
| Budget/dupe finder with VTO | NICHE + PRIOR-HACK (light) | SkinBudget ([Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)); SkinCause "affordable guidance" ([p.7](https://youcam-api.devpost.com/project-gallery?page=7)); Match My Makeup cross-brand shade lookup ([Shopify](https://apps.shopify.com/shade-finder-virtual-try-on)). A makeup-dupe + VTO combo was not seen as a main focus |
| Wedding/event/group planner | PRIOR-HACK | OneDress ("Six bridesmaids, six skin tones, one dress color"), Dress Circle ("A whole friend group in one virtual fitting room"), VOWS&VIBE, Festive Ready AI (family), EventReady AI, LookLens ([p.9](https://youcam-api.devpost.com/project-gallery?page=9), [p.5](https://youcam-api.devpost.com/project-gallery?page=5), [p.3](https://youcam-api.devpost.com/project-gallery?page=3), [p.2](https://youcam-api.devpost.com/project-gallery?page=2), [p.8](https://youcam-api.devpost.com/project-gallery?page=8)). Bridal *makeup* (vs. dress) was not seen |
| Gifting assistant (try jewelry on recipient's photo) | OPEN (not seen) | No gifting project seen in the YouCam/Pegasus/DeveloperWeek galleries reviewed. Jewelry/watch VTO exists as API ([Perfect Corp](https://www.perfectcorp.com/business/news/ces-2026-perfect-corp)). Consent issue: uses another person's face |
| "Try before you dye" salon booking | PRIOR-HACK (one) | GlamCode OS ([p.5](https://youcam-api.devpost.com/project-gallery?page=5)); Madison Reed DTC hair VTO ([Perfect Corp](https://www.perfectcorp.com/business/successstory/Madison-Reed)) |
| Men's grooming onboarding | NICHE | Worn ("for men who dislike shopping") ([p.9](https://youcam-api.devpost.com/project-gallery?page=9)); new beard APIs (June 2026) ([Perfect Corp](https://www.perfectcorp.com/business/news/HairBeardAPI)). No beard/men's-skincare-focused submission seen |
| Accessibility (blind/low-vision voice guidance) | PRIOR-HACK, and it WON | Aloud (listed first among winners) ([Aloud](https://devpost.com/software/aloud-lxqr70)); POISE ("voice-first multilingual AI mirror for blind and low-vision people"), AccessWear ([p.4](https://youcam-api.devpost.com/project-gallery?page=4), [p.6](https://youcam-api.devpost.com/project-gallery?page=6)); InclusiFit (adaptive fashion, voice navigation) won the Pegasus hackathon ([gallery](https://perfectcorphackathon.devpost.com/project-gallery)). Direct clone risk |
| Clinical-trial / derm research data collection | NICHE (B2B incumbents) | Haut.AI positions SkinGPT for claims ([CDE](https://cosmeticsdesign-europe.com/Article/2025/01/16/skingpt-tackles-skin-cares-biggest-challenge-proving-product-claims-with-ai)). Consumer-side claim tests exist in the prior hackathon (Face Value, Pruv). A decentralized-trial *sponsor-side* tool was not seen |
| Teen skincare with safety guardrails | OPEN (not seen) | Regulatory hook: the Connecticut AG investigation (Nov 2024) led Sephora to add warnings for products unsuitable for under-13s, train staff and require brand disclosures ([Personal Care Insights](https://www.personalcareinsights.com/news/sephora-kids-skincare-rules.html); [News12](https://hudsonvalley.news12.com/sephora-now-required-to-have-warnings-on-skincare-products-not-suitable-for-children-under-13-following-investigation)). No dedicated app with guardrails found |
| Sustainability / returns / tester-waste dashboard | PRIOR-HACK (returns); OPEN (tester waste) | MirrorMargin, ReturnGuard, LoopLook ([p.9](https://youcam-api.devpost.com/project-gallery?page=9), [p.10](https://youcam-api.devpost.com/project-gallery?page=10)); EcoTry Bellini (sustainable alternatives) ([Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)). In-store tester replacement or hygiene was not seen |
| Social commerce / live shopping with VTO | NICHE | TikTok Shop has AR try-ons ([EchoTik](https://www.echotik.live/blog/tiktok-shop-tiktok-seller-official-site-2025-features/)); prior submissions fitcheck, onMe (social feed), Wear or Dare ([p.2](https://youcam-api.devpost.com/project-gallery?page=2), [Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)). A tool for *live-stream hosts* (render viewer requests on the fly) was not seen |
| Resale/secondhand try-on | PRIOR-HACK | SecondLook ("Virtual try-on built for physical resale") ([p.3](https://youcam-api.devpost.com/project-gallery?page=3)) |
| Dermatology clinic before/after | COMMON (pro) | VISIA, Pabau AI Studio ([Canfield](https://www.canfieldsci.com/in-the-news/stories/harnessing-ai-in-consultations-revolutionizing-precision-and-efficiency/), [Pabau](https://pabau.com/features/ai-studio/)) |
| Content creation for small brands (diverse model swatches) | PRIOR-HACK, and it WON | CASTING and ShadeSpan (winners); NoStudio, StyleTwin, Modelier, zero-sample-b2b, OutfitPost-AI ([CASTING](https://devpost.com/software/casting), [ShadeSpan](https://devpost.com/software/shadespan), [p.2](https://youcam-api.devpost.com/project-gallery?page=2), [p.4](https://youcam-api.devpost.com/project-gallery?page=4), [p.5](https://youcam-api.devpost.com/project-gallery?page=5), [p.8](https://youcam-api.devpost.com/project-gallery?page=8)). Done for apparel; a makeup/foundation-shade version was not seen |
| Chrome extension adding VTO to any product page | COMMON + PRIOR-HACK (crowded) | Doppl's screenshot-any-outfit ([Google](https://blog.google/innovation-and-ai/models-and-research/google-labs/doppl/)); WANT!, Zdress, DressUp Chrome Extension, Universal try on, Anywear ([p.2](https://youcam-api.devpost.com/project-gallery?page=2), [p.3](https://youcam-api.devpost.com/project-gallery?page=3), [p.8](https://youcam-api.devpost.com/project-gallery?page=8), [p.9](https://youcam-api.devpost.com/project-gallery?page=9)) |
| WhatsApp/Telegram bot (India/Africa) | COMMON (L'Oréal) + PRIOR-HACK | Beauty Genius on WhatsApp ([L'Oréal](https://www.loreal.com/en/articles/science-and-technology/loreal-paris-beauty-genius/)); Verxio FitCheck ("WhatsApp fashion AI stylist") ([p.8](https://youcam-api.devpost.com/project-gallery?page=8)) |
| Smart mirror / kiosk | NICHE + PRIOR-HACK | Tata CLiQ Palette skin mirrors ([Inc42](https://inc42.com/?p=409661)); Mirra in-store, Aina smart mirror, OG in-store ([p.6](https://youcam-api.devpost.com/project-gallery?page=6), [p.3](https://youcam-api.devpost.com/project-gallery?page=3), [Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)) |
| Personal color analysis + VTO | PRIOR-HACK (the most crowded category) | Drape (×3 variants), Palette, TrueTone, SeeOn, D'Fashion, WearProof, Undertone (×3), Palette Proof, TrueHue, Drapping, Hue.U, ToneGrid, MIROIR, AI Beauty Color Lab (Pegasus), and more across pages 2–10 |
| Skin × environment (climate, travel, cycle, food) | PRIOR-HACK, and it WON (food) | ClimaSkin, Climate Skin, TravelGlow, GlowCycle, GirlCode360, CHARME (Ayurveda/food) ([p.8](https://youcam-api.devpost.com/project-gallery?page=8), [p.5](https://youcam-api.devpost.com/project-gallery?page=5), [p.7](https://youcam-api.devpost.com/project-gallery?page=7), [p.2](https://youcam-api.devpost.com/project-gallery?page=2)); "Food for Beautiful Skin" won the Pegasus hackathon ([gallery](https://perfectcorphackathon.devpost.com/project-gallery)) |
| Aging / future-self simulation | COMMON (B2B) + PRIOR-HACK | Haut.AI SkinGPT ([Haut.AI](https://haut.ai/skingpt)); YouCam Skin Simulation ([Perfect Corp](https://www.perfectcorp.com/business/news/ces-2026-perfect-corp)); Time Mirror, Future You Mirror ([Pegasus](https://perfectcorphackathon.devpost.com/project-gallery)); FaceState ([p.8](https://youcam-api.devpost.com/project-gallery?page=8)) |

**Other notable prior submissions showing how far teams already stretched "non-obvious":**
- ConfidentSkin: styling for vitiligo, scars and post-surgical patients ([p.3](https://youcam-api.devpost.com/project-gallery?page=3))
- ReWeave: remaking sarees ([p.3](https://youcam-api.devpost.com/project-gallery?page=3))
- KnitTech: knitters ([p.6](https://youcam-api.devpost.com/project-gallery?page=6))
- Ginani Pattern Engine and PatternProof: sewing ([p.4](https://youcam-api.devpost.com/project-gallery?page=4), [p.5](https://youcam-api.devpost.com/project-gallery?page=5))
- SoleFit: foot profiles ([p.4](https://youcam-api.devpost.com/project-gallery?page=4))
- FaceForge: worst skin metric becomes an RPG class ([p.7](https://youcam-api.devpost.com/project-gallery?page=7))
- BACKDROPIQ: "Upload the room. Watch the ranking change." ([p.10](https://youcam-api.devpost.com/project-gallery?page=10))
- ME // STYLE AUDITION: blind fashion discovery ([p.10](https://youcam-api.devpost.com/project-gallery?page=10))
- DressRehearsal: try unreleased fashion before seeing the price ([p.4](https://youcam-api.devpost.com/project-gallery?page=4))
- Aequidrape: dressing with differing bodies or needs ([p.5](https://youcam-api.devpost.com/project-gallery?page=5))

### Inferences

These are candidate whitespace directions. They are my synthesis of the absence of incumbents in the sources reviewed plus absence from about 260 hackathon taglines. Verify before committing.
1. **Beauty-side "measuring instrument" for brands**, a makeup analogue of the winning ShadeSpan/CASTING pattern. Example: a foundation or concealer shade-range coverage audit. Use Skin Tone/Facial Color/Fitzpatrick analysis on a diverse panel plus makeup VTO to show which skin tones have no good match in an indie brand's range before launch. Prior winners did this only for apparel colorways.
2. **Hair & Beard API (June 2026)** is newer than the previous hackathon's scope. Candidate directions:
   - Barber/stylist "cut spec card" handoff
   - Hair-density or frizz progress tracker for hair-loss or treatment users
   - Wig and brow try-on for chemotherapy patients, which pairs with a medical-camouflage niche partly touched by ConfidentSkin
3. **Teen/tween skincare co-pilot with guardrails:** age-appropriate routines, blocking actives such as retinol and acids for under-13s, and a parent view. It has a fresh regulatory hook (Connecticut AG / Sephora), but minors' biometric data (COPPA-type issues) is a serious design constraint.
4. **Non-shopper commerce roles:**
   - Customer-service "wrong shade" return-to-exchange flow: before a refund on an opened foundation, run a shade match and VTO and offer the correct shade.
   - Sales associate or pharmacist counter mode.
   - Live-stream host console for rendering viewers' requested shades.
5. **Gifting with consent:** jewelry or watch try-on on a recipient's photo, with a consent/link-share step so the recipient opts in.
6. **Solo-pro intake:** a "VISIA-lite" mobile intake for estheticians, lash/brow artists and freelance makeup artists, including a bridal makeup trial pre-visualization.
- **Ideas to avoid as primary concepts** (clone risk relative to winners or crowded categories):
  - Blind/low-vision voice beauty (Aloud)
  - Diverse-skin-tone garment panels (CASTING, ShadeSpan)
  - VTO identity or trust receipts (KeepMe and around 10 others)
  - Shopify apparel VTO (ConfidFit)
  - Personal color analysis + VTO
  - Skin + outfit "occasion readiness"
  - Chrome extension VTO
  - Generic agentic advisor

### Gaps
- Gallery page 1 of the July–August 2026 hackathon was only partially captured (winners plus about 6 notable projects). About 14 non-winning projects from page 1 are unseen, so some "OPEN" items could have a page-1 clone.
- The current hackathon's (Skin AI & eCommerce VTO) gallery is unpublished, so ideas in progress there are unknown. — [Devpost](https://youcam-api-skin-ai-ecommerce.devpost.com/project-gallery)
- No market-size or demand evidence was gathered for the "OPEN" niches (teens, gifting, solo pros, live-stream hosts). Their demand is inferred, not sourced.

---

## Key Question 6: Prior hackathon winners. What won, what made it stand out, and general patterns

### Takeaway
Perfect Corp has run at least four developer hackathons in 2026: DeveloperWeek (February), Pegasus/Startup World Cup (May), the Devpost "Skin AI & Apparel VTO" hackathon (July–August, 238 submissions), and the current "Skin AI & eCommerce VTO" hackathon (deadline November 2, 2026). Across their known winners there are clear patterns:
- **Inclusion and accessibility for a specific under-served group:** Aloud, InclusiFit, CASTING, ShadeSpan.
- **Reframing the API for B2B merchandising as a measuring instrument:** ShadeSpan, CASTING.
- **Trust, consent and honesty as product features:** KeepMe, ConfidFit, CASTING, Aloud.
- **Production-readiness:** ConfidFit is live on the Shopify App Store. Several winners also built in cost controls and real-device validation.

### Cited Findings

**Current target hackathon: YouCam API Skin AI & eCommerce VTO** ([Devpost](https://youcam-api-skin-ai-ecommerce.devpost.com/))
- Deadline November 2, 2026, 11:45am EST. Online, 698 registered (at time of fetch).
- Prizes: 1st $2,500, 2nd $1,000, 3rd $500 (each with a feature blog and marketing meeting), plus a Women in Tech award ($1,000) and a Rising Star award for students ($1,000).
- Judging:
  - Technological Implementation: "How thoroughly and skillfully does the project integrate at least one YouCam API?"
  - Design: "Does the project deliver a complete, coherent product experience?"
  - Potential Impact: "Does the project make a credible case for solving a real problem?"
  - Quality of Idea: "Is this a creative, non-obvious use of at least one YouCam API?"
- Tracks:
  - Skin AI: skin analysis for purchase decisions and skincare guidance
  - eCommerce VTO: virtual try-on for beauty AND fashion shopping
- The page fetch listed "AI Skin Analysis" and "Generative Apparel Virtual Try-On" as the API features; whether makeup, hair and jewelry VTO count should be confirmed in the rules.
- 1,000 free API units per participant.
- Submissions need a repo, description, screenshots and a 1–3 minute demo video showing working functionality and the API integration, and must deliver "clear consumer or retail value", not a surface-level implementation.
- The gallery is not yet published. — [Devpost gallery](https://youcam-api-skin-ai-ecommerce.devpost.com/project-gallery)

**Previous: YouCam API Skin AI & Apparel VTO Hackathon** (July 6 – August 17, 2026; 1st $5,000, 2nd $1,000, 3rd–5th 5,000 API units; tracks Skin AI / Apparel VTO / combined; same 4 judging criteria) — [Devpost](https://youcam-api.devpost.com/). Winners, in gallery order — [Gallery](https://youcam-api.devpost.com/project-gallery):
1. **Aloud** ("Beauty, aloud. The first beauty AI a blind shopper can use alone, screen off")
   - Four voice-operable flows (Talk, Scan barcode, Know Your Skin, Verify Your Look).
   - Uses YouCam Skin Analysis (7 concerns) and Skin Tone Analysis, and discloses lowered confidence when accuracy drops: "the first consumer skin tool that discloses its own accuracy bias".
   - Stack: Next.js, Capacitor, OpenAI Realtime, Deepgram, ElevenLabs, MediaPipe, EU CosIng, Open Beauty Facts.
   - A CI "claim linter" blocks medical language, and the app stores nothing.
   - Validation: non-visual capture succeeded 10/10 on a real iPhone in under 30 seconds.
   - Its framing turned litigation and the EAA into market access.
   - Exact placement was not stated on the project page (listed first). — [Devpost: Aloud](https://devpost.com/software/aloud-lxqr70)
2. **ShadeSpan** (B2B)
   - Renders garments across six Fitzpatrick-representative tones using Apparel VTO and Skin AI, and grades each piece on its *worst* tone.
   - Scoring uses CIEDE2000/WCAG contrast plus a washout veto.
   - A 14-piece collection takes about 2 minutes and about 168 API units, versus a week of studio time.
   - Only 14.3% of demo garments passed on all tones.
   - It "repurposes virtual try-on technology as a measuring instrument". Python/FastAPI CLI plus dashboard. — [Devpost: ShadeSpan](https://devpost.com/software/shadespan)
3. **CASTING** (3rd–5th; B2B)
   - One product photo is rendered on 8 measured skin tones as a coverage board.
   - Uses Clothes VTO, Skin Analysis, Fitzpatrick and Facial Color Tones (ΔL*/ΔE2000).
   - Results stream as NDJSON with honest partial-failure reporting and a staggered tile reveal (about 28 seconds), behind a budget circuit-breaker.
   - A "Methods" provenance panel discloses the AI-generated reference panel. — [Devpost: CASTING](https://devpost.com/software/casting)
4. **KeepMe**
   - An "Identity Contract" for generative try-on: protected zones, drift detection and repair, JWS-signed receipts and verified deletion.
   - Uses AI Clothes v3 and Skin Analysis v2.1.
   - Tested with Playwright and axe-core. — [Devpost: KeepMe](https://devpost.com/software/keepme)
5. **ConfidFit** (3rd–5th): Shopify app live on the App Store, with consent, an honest label, billing, analytics and abuse controls. — [Devpost: ConfidFit](https://devpost.com/software/confidfit)

**Pegasus / Startup World Cup Silicon Valley Hackathon** (through May 7, 2026; $1,500 / $1,000) — [BusinessWire](https://www.businesswire.com/news/home/20260505489956/en/Perfect-Corp.-Partners-with-Pegasus-Startup-World-Cup-for-Silicon-Valley-Hackathon-Inviting-Innovators-to-Build-the-Future-of-Retail-using-AI-Powered-API-Suite). Winners — [Gallery](https://perfectcorphackathon.devpost.com/project-gallery):
- **InclusiFit**: "The first adaptive fashion platform for people with disabilities": VTO, smart filters and voice navigation.
- **Food for Beautiful Skin**: "See how food you already have at home can make your skin more beautiful."

Non-winners included many generic "skin analysis + recommendations + VTO" apps: Skinfo, Skin-Lab-Rx, Skindex, Lume, GlowFit, ToneMatch and Virtual Try.

**DeveloperWeek 2026** (February 2–20; Perfect Corp prize $1,500 / $1,000) — [Perfect Corp](https://www.perfectcorp.com/business/news/hackathon-2026-perfect-corp). Perfect Corp prize winners — [Gallery](https://developerweek-2026-hackathon.devpost.com/project-gallery):
- **CLOSET** ("What to wear today?"): 10-category AR try-on with outfit recommendations. It claims 95.2% alignment, 60fps and a B2B2C model. — [Devpost: CLOSET](https://devpost.com/software/closet-a-i)
- **FitCast**: weather-based outfits on your photo.

Perfect Corp also launched a "Global Hackathon" at WeAreDevelopers Berlin 2026 (July). — [BusinessWire](https://www.businesswire.com/news/home/20260708291593/en/Perfect-Corp.-Showcases-AI-Skin-Beauty-and-Fashion-APIs-and-Launches-Global-Hackathon-at-WeAreDevelopers-Berlin-2026)

**General Devpost/sponsor-hackathon advice:**
- Read the judging rubric before the problem statement, and tailor the submission to the criteria.
- Write the 90-second demo script before coding.
- Sponsor judges reward deep integration over hello-world calls.
- Keep the video to about 2 minutes: problem (15–20s), solution in action (60–75s), impact (15–20s). Show a live URL rather than localhost.
- Hardcode the demo path and cache API responses so the demo always reaches its punchline.

Sources: [DEV Community](https://dev.to/ajeetraina/top-5-tips-to-win-the-futurestack-genai-hackathon-2pgg); [DEV Community: Devpost submissions](https://dev.to/jacklyn/how-to-make-your-devpost-submissions-not-suck-37i0); [HackerEarth](https://www.hackerearth.com/blog/10-tips-win-hackathon)

### Inferences
- **Judges' revealed preferences across 9 known Perfect Corp prize winners:**
  - Four center on inclusion or diversity of a specific group: blind users, people with disabilities, and skin-tone coverage (twice).
  - Two are B2B merchandising instruments.
  - Two (or three) are productized trust layers.
  - Generic "selfie → scores → recommendations → try-on" apps appear many times among non-winners and not among winners.
- **The strongest pattern is a reframe:** use the API for a user or job the API wasn't marketed for, such as VTO as a QA instrument or skin analysis as an accessibility sense. Pair it with:
  - quantitative evidence (pass rates, unit costs, timing)
  - explicit limitation disclosure
  - real-device or real-merchant validation
- **The current hackathon's eCommerce VTO track covers beauty as well as fashion.** The previous hackathon was apparel-only on the VTO side. Makeup, hair/beard, nail, jewelry/watch and eyewear VTO used in a commerce workflow is therefore comparatively unclaimed territory, pending confirmation of which APIs are in scope.
- **The special awards favor certain teams:** Women in Tech and Rising Star (students) mean team composition can matter.

### Gaps
- Exact 1st and 2nd placement among Aloud, ShadeSpan and KeepMe was not confirmed. The gallery lists Aloud first, and CASTING and ConfidFit state 3rd–5th, so ShadeSpan and KeepMe were presumably among the top three, order unconfirmed.
- No Perfect Corp blog post announcing winners was found.
- The WeAreDevelopers Berlin hackathon's winners or status was not found; it may be the same Devpost event as the July–August hackathon.
- Pre-2026 Perfect Corp/YouCam hackathons, and non-Perfect-Corp beauty-tech hackathon winners (e.g., MLH or university events with AR try-on), were not researched.

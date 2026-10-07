# YouCam API Skin AI & eCommerce VTO Hackathon: Rules, Resources and YouCam API Technical Inventory

Research date: 2026-10-07 (hackathon live; deadline Nov 2, 2026 11:45 am ET).
Method notes: Devpost pages were read via WebFetch (Devpost blocks direct curl with HTTP 403). The YouCam developer docs (docs.perfectcorp.com) were crawled directly. The site's sitemap, the 12 developer-guide pages and the changelog were read, and the **official OpenAPI bundles for all 67 API reference pages** were downloaded from `https://docs.perfectcorp.com/_bundle/reference/{api_id}.yaml?download` and parsed. Unit costs, endpoints and input limits below come verbatim from those bundles. The reference page for any API is `https://docs.perfectcorp.com/reference/{api_id}`. The api_id values are given in the tables.

---

## Q1. Hackathon rules, requirements, deadlines, prizes and judging (verified and expanded)

### Takeaway
I checked the facts the coordinator had already extracted, and they are correct. New details: the Stage-2 tie-break goes by criterion order. Software built before the hackathon is allowed only if it was "significantly updated" during the submission period, and you must explain the update. The project must stay testable for free, with no restrictions, until judging ends on Nov 20. The two special awards have their own eligibility conditions. Two official pages disagree on small points: which form to use for the social bonus, and whether Youku is accepted as a video host.

### Cited Findings
**Identity and dates**
- The official name is "YouCam API Skin AI & eCommerce VTO Hackathon", with the tagline "Build with the YouCam API to Shape the Future of Skincare, Beauty, Fashion and eCommerce". It is online and hosted by Perfect Corp. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)
- The legal sponsor is "Perfect Mobile Corp., 14F., No. 98, Minquan Rd., Xindian Dist., New Taipei City 231, Taiwan". Devpost is the administrator (support@devpost.com). — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Registration runs Sep 24, 2026 (12:00 pm ET) to Nov 2, 2026 (11:45 am ET). Submissions run Sep 29, 2026 (12:00 pm ET) to Nov 2, 2026 (11:45 am ET). Judging runs Nov 3 (12:00 pm ET) to Nov 20, 2026 (11:45 am ET). Winners will be announced "on or around Nov 24, 2026 (12:00 pm Eastern Time)". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Devpost theme tags are AR/VR, E-commerce/Retail and Machine Learning/AI. On 2026-10-07 the page showed 698 registered participants. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/); [Resources](https://youcam-api-skin-ai-ecommerce.devpost.com/resources)

**What to build (two tracks)**
- Core requirement: "Create a working application that integrates at least one Perfect Corp. YouCam API and demonstrate clear consumer or eCommerce value". Allowed API categories are Skin, Beauty, Fashion, Jewelry & Watch, and Hair & Beard. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Skin AI track framing: "People don't wonder about their skin in the abstract; they wonder right before a purchase, right after a bad breakout, or right when they're standing in front of a mirror deciding whether a product is working". Entrants are encouraged to combine Skin AI with other YouCam APIs to help users understand their skin and decide what to do next. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)
- eCommerce VTO track framing: "Build something that brings Virtual Try-On together into one seamless, intuitive experience". The intent is to unify apparel and beauty try-on in a single shopping interface. The overview also mentions "Agentic AI workflows" as an option. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)
- The project "must be capable of being successfully installed and running consistently on the platform for which it is intended". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Pre-existing projects: "must have been significantly updated after the start of the Hackathon Submission Period. Entrants must explain how their Project was significantly updated during the Submission Period." — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- A project "must not have been developed, or derived from a Project developed, with financial or preferential support from the Sponsor or Administrator". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Multiple submissions are allowed, but each "must be unique and substantially different" from the entrant's other submissions. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)

**Submission requirements**
- Code repository: it "must contain all necessary source code, assets, and instructions required for the project to be functional". It can be public with relevant licensing, or private and shared with contact_event@PerfectCorp.com. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- A text description of features and functionality that shows consumer or eCommerce value, plus screenshots. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Demo video, 1–3 minutes. It "must explain the YouCam API used", "must include footage that shows the Project functioning on the device for which it was built", and must be public on "YouTube (highly preferred), or Vimeo". It must contain no third-party trademarks or copyrighted music without permission. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules). The overview page also lists Youku as acceptable, which conflicts with the rules page. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)
- Testing access: "The Entrant must make the Project available free of charge and without any restriction, for testing, evaluation and use by the Sponsor, Administrator and Judges until the Judging Period ends." — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Materials must be in English or come with an English translation. Winners must take part in an exit interview. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- The overview adds that entrants consent to being featured in a blog article. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)

**Eligibility**
- Entrants can be individuals at or above the age of majority where they live, teams of eligible individuals (with one Representative), or organizations. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Excluded countries and regions: Afghanistan, Antarctica, China, Djibouti, Iraq, Somalia, Venezuela, Western Sahara, Italy, Brazil, Quebec, Russia, Cuba, Iran, North Korea, Sudan, Belarus, Vietnam, and the Crimea, Donetsk and Luhansk regions of Ukraine. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules). Note: the official rules text excludes only the three Ukrainian regions, not all of Ukraine. The coordinator's pre-extracted list said "Ukraine".
- Also ineligible: employees and agents of the promotion entities and their immediate families, judges and their employers, and anyone with a "real or apparent conflict of interest". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)

**Judging**
- Stage One is pass/fail. It checks that the project "reasonably fits the theme and reasonably applies the required APIs/SDKs". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Stage Two uses four equally weighted criteria. (1) Technological Implementation: "How thoroughly and skillfully does the project integrate at least one Perfect Corp. YouCam API from the Skin, Beauty, Fashion, Jewelry & Watch, Hair & Beard category? Does the project demonstrate clear consumer or eCommerce value?" (2) Design: "complete, coherent product experience — not just a technical proof of concept". (3) Potential Impact: "credible, specific case for solving a real problem for a real audience". (4) Quality of the Idea: "creative, non-obvious use". — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules). The overview adds that technical work should show "genuine, non-trivial working code". — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)
- Tie-break: "the tied Submission with the highest score in the first applicable criterion listed above will be considered the higher scoring Submission". Technological Implementation is listed first, so it decides ties. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)

**Prizes ($6,000 total)**
- 1st place: $2,500. 2nd place: $1,000. 3rd place: $500. Each placement also gets a feature blog post and a meeting with the product/marketing team. Women in Tech: $1,000 cash. Rising Star (students): $1,000 cash. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Women in Tech eligibility (as summarized from the rules): teams with self-identified women. Rising Star eligibility: teams with currently enrolled students, verified by a .edu email. "A Project can only win one (1) prize"; "A team may win a maximum of one (1) Placement Prize (1st–3rd) or one (1) Special Award." — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Prize mechanics: winners must return affidavit and tax forms (W-9 for US residents, W-8BEN for others) within 10 business days. Prizes are delivered within 60 days of receiving the forms. Winners pay their own taxes and fees. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)

**Intellectual property and legal**
- Submissions remain the entrant's intellectual property. The sponsor gets a non-exclusive license to use them for judging. The sponsor and Devpost may promote submissions and use participants' name and likeness for 3 years. Open source is allowed if licenses are respected and the entrant builds on top of it. Disputes go to AAA arbitration under New York law. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)

**Free API units**
- "Entrants may request a YouCam API redeem code, which includes 1,000 free API units for use during the Hackathon." Codes are "issued on a per-registrant basis, and are non-transferable, and are valid for 90 days from the date of redemption." — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- Social Sharing Bonus: 500 units per qualifying shared demo video, at most one per platform and two in total (1,000 units maximum). The post must tag @YouCam API, briefly describe which YouCam API(s) the project uses, include the disclosure "Received API credits for sharing", stay public for at least 30 days, and come from an account created before the submission period started. The claim form must be submitted by Nov 2, 2026 11:45 am ET. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules)
- The rules give the bonus form as https://forms.gle/JwMFYMpaExckupEk7. The overview's "Share & Earn" link points to a different form, https://forms.gle/BJd5gPzF6YqPQR4R8. — [Rules](https://youcam-api-skin-ai-ecommerce.devpost.com/rules); [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/)

### Inferences
- Judging runs until Nov 20, 2026, and the deployed demo must work "without any restriction" until then. Teams therefore need enough units left over for judges' test calls. A code redeemed on or after Sep 29 stays valid for 90 days, until about late December, which covers judging.
- Ties are broken by Technological Implementation. Depth of YouCam API integration, for example several APIs chained or HD skin analysis plus try-on, is the most decisive single factor.
- The allowed categories exclude the "Image" and "Video" (Creators) API groups. A project built only on background removal, image generation or video generation would probably fail the Stage 1 pass/fail check, although those APIs can support a Skin, Beauty, Fashion, Jewelry & Watch, or Hair & Beard API.

### Gaps
- I could not get the exact rules wording for Women in Tech (all members or at least one?) and Rising Star (all members students?). The WebFetch summary gave only a paraphrase.
- Which of the two Google Forms is canonical for the social bonus is unresolved. Prefer the one in the official rules (JwMFYMpaExckupEk7) and confirm with wendy_yen@perfectcorp.com.

---

## Q2. Devpost subpages, judges, resources, discussions and how to claim free units

### Takeaway
There are no Updates posts yet, no FAQ page, and no office hours or webinars are listed. The resources page is a 3-step onboarding plus documentation links. The only judge listed is Wendy Yen, who is also the hackathon manager. Units are claimed by redeeming an emailed code in the YouCam API console. The forum shows a few redeem-code failures, which the organizer fixed by hand.

### Cited Findings
- The Updates page has no posts yet: "Stay tuned for important announcements. Organizers will post them here and also send an email to registered participants." — [Updates](https://youcam-api-skin-ai-ecommerce.devpost.com/updates)
- Resources, 3-step quick start: (1) "Register on Devpost. Get your exclusive redeem code by email (2 minutes)". (2) "Sign up for YouCam API". (3) "Claim Your Free 1,000 YouCam API Units" by redeeming the code. The estimated time from registration to first API call is about 30 minutes. — [Resources](https://youcam-api-skin-ai-ecommerce.devpost.com/resources)
- Resource links:
  - API overview: https://yce.perfectcorp.com/ai-api
  - Console and sign-up: https://yce.perfectcorp.com/api-console/en/account-settings/
  - API keys / first-call guide: https://yce.perfectcorp.com/api-console/en/api-keys/
  - API Playground: https://yce.perfectcorp.com/api-console/en/api-playground/
  - Docs: https://docs.perfectcorp.com/develop/introduction
  - India console: https://yce.makeupar.com/api-console/en/account-settings/
  - India docs: https://docs.makeupar.com/develop/introduction

  — [Resources](https://youcam-api-skin-ai-ecommerce.devpost.com/resources)
- India-region participants use makeupar.com instead of perfectcorp.com. — [Resources](https://youcam-api-skin-ai-ecommerce.devpost.com/resources)
- Judges: only "Wendy Yen" is listed, with no title. The overview names the hackathon manager as wendy_yen@perfectcorp.com, and the event contact is contact_event@PerfectCorp.com. — [Overview](https://youcam-api-skin-ai-ecommerce.devpost.com/). A web search found no public title for Wendy Yen. — [search result](https://en.wikipedia.org/wiki/Perfect_Corp)
- Discussions: there are two threads. "Error redeeming code": a user got "Invalid redeem code The redeem code you entered does not exist". The "YouCam API Team" (Manager) replied "Could you please try again for us? The code should be working properly now", and the user confirmed it worked. A second user reported the same error after signing up with Google. — [Forum thread](https://youcam-api-skin-ai-ecommerce.devpost.com/forum_topics/45356-error-redeeming-code)
- "Issue with YouCam credit": the 1,000 credits did not show in the account. Wendy Yen (Manager) asked the user to email their User ID to wendy_yen@perfectcorp.com. — [Forum thread](https://youcam-api-skin-ai-ecommerce.devpost.com/forum_topics/45425-issue-with-youcam-credit)
- Docs FAQ (not a Devpost FAQ): units are called "Credit" in the API. Auth is "Authorization: Bearer YOUR_API_KEY". The API works with Flutter, Wix (Velo backend fetch recommended) and WooCommerce through plain REST. — [Docs FAQ](https://docs.perfectcorp.com/develop/faq)

### Inferences
- There are no office hours or tutorials, so the docs, Playground and Agent Skills are the main support. Teams should redeem their code early and email wendy_yen@perfectcorp.com with their console User ID if the credits do not appear.
- Signing up with Google may be linked to redeem failures. One report is not enough to confirm this.

### Gaps
- No judges besides Wendy Yen, and no judge bios, were found.
- The /details/dates page and the project gallery could not be fetched separately: Devpost returns 403 to curl, and WebFetch returned only overview content. The gallery is presumably empty until submissions close.
- I found no published livestream, webinar or office-hours schedule.

---

## Q3. Full YouCam API catalog, with endpoints and unit cost

### Takeaway
The docs (version v1.16, released 2026-09-24) list about 61 AI APIs in 7 sidebar groups: Skin/Face & Body, Beauty, Hair & Beard, Fashion, Jewelry & Watches, Image, and Video. There are also utility APIs for units, files and tasks. The first five groups are eligible for the hackathon. Costs range from 1 unit (makeup VTO, jewelry, most hair VTO) up to 22 units (HD skin analysis, 13–16 concerns) and 30 units (face analyzer, 15–28 features).

### Cited Findings
**Docs sidebar grouping** — [docs sidebar](https://docs.perfectcorp.com/reference/ai_skin_analysis/section/overview/unit-consumption)
- **Skin, Face & Body:** AI Skin Analysis, AI Skin Simulation, AI Facial Color Tones Analyzer, AI Face Attributes & Ratio Analyzer, AI Aging Simulation, AI Face Reshape, AI Body Reshape, AI Breast Augmentation Simulator, AI Face Lift, AI Smile, AI Fitzpatrick Skin Type Analysis, AI Abs Filter.
- **Beauty:** AI Makeup Transfer, AI Makeup Virtual Try-On, AI Look Virtual Try-On, AI Nail Transfer, AI Nail Virtual Try-On, AI Eye Color Lens Virtual Try-On, AI Teeth Whitening.
- **Hair & Beard:** AI Hair Style, Hair Color, Hair Extension, Bangs Filter, Hair Volume and Wavy Hair Virtual Try-On; AI Beard Style Generator; AI Hair Type, Hair Length, Hair Frizziness and Hair Density Detection.
- **Fashion:** AI Clothes, Hat, Scarf, Bag, Shoes and Fabric Virtual Try-On.
- **Jewelry & Watches:** AI Ring, Bracelet, Watch, Earrings and Necklace Virtual Try-On.
- **Image:** Face Swap, Image Extender, Object Removal Pro, Photo Enhance, Background Removal, Colorize, Lighting, Color Correction, Background Change, Background Blur, AI Replace, Avatar Generator, Headshot Generator, Studio Generator, Image Generator, Watermark Removal.
- **Video:** Video Generator, Video Enhancer, Video Face Swap, Video Style Transfer, Video Object Removal, Video Background Replace.

**Base host:** `https://yce-api-01.makeupar.com`. All V2 endpoints are `/s2s/v2.0/task/...` except where noted. Every task has a matching `GET .../{task_id}` status endpoint. — [API Server](https://docs.perfectcorp.com/develop/api_server); OpenAPI bundles.

**Hackathon-eligible APIs**

| Category | API (api_id) | Endpoint(s) | Units | Key inputs / limits |
|---|---|---|---|---|
| Skin | AI Skin Analysis (`ai_skin_analysis`) | POST `/s2s/v2.0/task/skin-analysis` and `/s2s/v2.1/task/skin-analysis` | SD: 9 (1–4 concerns), 12 (5–8), 14 (9–12), 16 (13–16). HD: 12, 16, 20, 22 respectively | SD needs a short side of at least 480 px; HD needs at least 1080 px. Inputs above a 2560 px long side are auto-resized. File <10MB, jpg/png. Face width must be >60% of image width. HD and SD concerns cannot be mixed in one call. [ref](https://docs.perfectcorp.com/reference/ai_skin_analysis) |
| Skin | AI Skin Simulation (`ai_skin_simulation`) | `/task/skin-simulation` | 4 (1–4 concerns), 6 (5–10 concerns) | 10 concerns (wrinkle, radiance, oiliness, acne, eye_bags, dark_circle, spots, pores, texture, redness). Each takes an intensity from 0.0 to 1.0, and not all can be 0. [ref](https://docs.perfectcorp.com/reference/ai_skin_simulation) |
| Skin | AI Facial Color Tones Analyzer (`ai_skin_tone_analysis`) | `/task/skin-tone-analysis` | 20 | Long side ≤4096 (auto-resized to 1080). Single person, jpg. `face_angle_strictness_level` can be strict, high, medium, low or flexible. [ref](https://docs.perfectcorp.com/reference/ai_skin_tone_analysis) |
| Skin | AI Fitzpatrick Skin Type Analysis (`ai_fitzpatrick_skin_type`) | `/task/fitzpatrick-scale-analyzer/pre-process`, then `/task/fitzpatrick-scale-analyzer` | 10 | Long side ≤4096, short side ≥320, jpg. Returns `fitzpatrick_scale` I–VI. [ref](https://docs.perfectcorp.com/reference/ai_fitzpatrick_skin_type) |
| Skin/Face | AI Face Attributes & Ratio Analyzer (`ai_face_analyzer`) | `/task/face-attr-analysis` | 10 (1–5 features), 20 (6–14), 30 (15–28) | Long side ≤4096 (auto-resized to 1080). Single person, jpg. [ref](https://docs.perfectcorp.com/reference/ai_face_analyzer) |
| Skin/Face | AI Aging Simulation (`ai_aging_simulation`) | `/task/aging` | 2 | Long side ≤4096. Yaw within ±30°, roll and pitch within ±20°. jpg. [ref](https://docs.perfectcorp.com/reference/ai_aging_simulation) |
| Face | AI Face Reshape / Face Lift (`ai_face_reshape`, `ai_face_lift`) | `/task/face-reshape` (+ `/pre-process`), `/task/face-lift` (+ `/pre-process`) | 1 each | Face Lift features: eye_bag, cheek, forehead, shape, mouth. Mode is auto or custom. [ref](https://docs.perfectcorp.com/reference/ai_face_lift) |
| Face | AI Smile (`ai_smile`) | `/task/ai-smile` | 1 | expression_type is smile_with_teeth_visible or closed_mouth_smile. [ref](https://docs.perfectcorp.com/reference/ai_smile) |
| Body | AI Body Reshape, Breast Augmentation, Abs Filter | `/task/body-reshape` (+ pre-process), `/task/breast-shape`, `/task/abs-shape` | 1 each | Abs Filter: mode Six-pack or Vest-line, intensity 1–2. Long side ≤4096, yaw within ±45°. [ref](https://docs.perfectcorp.com/reference/ai_abs_filter) |
| Beauty | AI Makeup Virtual Try-On (`makeup_vto`) | `/task/makeup-vto` | 1 | Long side <1920, face width ≥100, jpg/png. Effects array covers 13 categories plus skin_smooth. [ref](https://docs.perfectcorp.com/reference/makeup_vto) |
| Beauty | AI Look Virtual Try-On (`ai_look_vto`) | GET `/task/template/look-vto`; POST `/task/look-vto` | 2 | Long side <1920, face width ≥100. Uses predefined look templates. [ref](https://docs.perfectcorp.com/reference/ai_look_vto) |
| Beauty | AI Makeup Transfer (`ai_makeup_transfer`) | `/task/mu-transfer` | 2 | src plus reference face, long side ≤1024, single face. [ref](https://docs.perfectcorp.com/reference/ai_makeup_transfer) |
| Beauty | AI Nail Virtual Try-On (`ai_nail_vto`) | `/task/nail-vto` | 1 | effect_type is nail_polish or press_on_nails. Hand photo: long side ≤2048, short side ≥256. Press-on design image 271–542 px wide. [ref](https://docs.perfectcorp.com/reference/ai_nail_vto) |
| Beauty | AI Nail Transfer (`ai_nail_transfer`) | `/task/ai-nail` | 1 | Hand photo plus reference nail photo, long side ≤4096. [ref](https://docs.perfectcorp.com/reference/ai_nail_transfer) |
| Beauty | AI Eye Color Lens VTO (`ai_eye_color_lens`) | `/task/eye-color-vto` | 1 | Selfie long side ≤1920, short side ≥320. Lens style image is a PNG of 200×200 to 600×600. [ref](https://docs.perfectcorp.com/reference/ai_eye_color_lens) |
| Beauty | AI Teeth Whitening (`ai_teeth_whitening`) | `/task/teeth-whiten` (+ `/pre-process`) | 1 | Long side ≤1920, short side ≥320. Takes whitening_intensity. [ref](https://docs.perfectcorp.com/reference/ai_teeth_whitening) |
| Hair | AI Hair Style VTO (`ai_hairstyle`) | v2.0: `/task/hair-style` (templates), `/task/hair-transfer` (reference). v2.1: `/s2s/v2.1/task/hair-transfer` | v2.0: 1 (preset) or 2 (custom). v2.1: 2 for either | Long side ≤1024, face width ≥128. Pitch within ±10°, yaw within ±45°, roll within ±15°. jpg. v2.1 adds `hair_color`=ref or src. [ref](https://docs.perfectcorp.com/reference/ai_hairstyle) |
| Hair | AI Hair Color VTO (`ai_hair_color`) | `/task/hair-color` | 1 (full or ombre) | 14 named presets (e.g. Jet Black, Honey Blonde, Rose Gold, Teal Blue) plus custom palettes. Ombre settings include blend_strength and line_offset. Long side <1920. [ref](https://docs.perfectcorp.com/reference/ai_hair_color) |
| Hair | Hair Extension / Bangs / Wavy (`ai_hair_extension`, `ai_bangs`, `ai_wavy_hair`) | `/task/hair-ext`, `/task/hair-bang`, `/task/hair-curl` (template-based) | 1 each | Bangs: long side ≤1024, face width ≥128. [ref](https://docs.perfectcorp.com/reference/ai_bangs) |
| Hair | Hair Volume (`ai_hair_volume`) | `/task/hair-vol` | 2 | Template-based. [ref](https://docs.perfectcorp.com/reference/ai_hair_volume) |
| Beard | AI Beard Style Generator (`ai_beard_style`) | `/task/beard-style` | 2 | Long side <1024, face width >256, yaw within ±30°, jpg. [ref](https://docs.perfectcorp.com/reference/ai_beard_style) |
| Hair analysis | Hair Type Detection (`ai_hair_type_detection`) | `/task/hair-type-detection` (3 images) | 2 | Front, left and right photos. Each 320–4096 px. [ref](https://docs.perfectcorp.com/reference/ai_hair_type_detection) |
| Hair analysis | Hair Length Detection | `/task/hair-length-detection` | 2 | One front selfie. [ref](https://docs.perfectcorp.com/reference/ai_hair_length_detection) |
| Hair analysis | Hair Frizziness Detection | `/task/hair-frizziness-detection` (3 images) | 2 | All three images must be the same size. [ref](https://docs.perfectcorp.com/reference/ai_hair_frizziness_detection) |
| Hair analysis | Hair Density Detection | `/task/hair-density-detection` | 1 | One selfie with the head tilted 45° downward. Minimum 100 px. [ref](https://docs.perfectcorp.com/reference/ai_hair_density_detection) |
| Fashion | AI Clothes VTO (`ai_clothes`) | `/task/cloth` (v2), `/task/cloth-v3`, `/task/cloth-v4`; templates at GET `/task/template/cloth` | 2 (V2.0 and V3.0 listed) | garment_category is full_body, upper_body, lower_body, shoes or auto; outerwear was added in v1.14.1. Also `change_shoes`. v4 adds `filter_multi_person`=off, normal or strict. Images 512×384 minimum, 1024×768 recommended, max 4096, <10MB. [ref](https://docs.perfectcorp.com/reference/ai_clothes) |
| Fashion | AI Shoes VTO (`ai_shoes`) | `/task/shoes` (v2, generative with style presets), `/task/shoes-transfer` (v3, reference image) | 2 each | gender is required. Product images at least 512×512; worn images at least 800×800. [ref](https://docs.perfectcorp.com/reference/ai_shoes) |
| Fashion | AI Hat / Scarf / Bag VTO | `/task/hat`, `/task/scarf`, `/task/bag` | 2 each | gender is required. Style presets, e.g. Bag: style_parisian_chic, style_urban_chic, style_mediterranean_chic, style_art_deco_style. Bag output is 1104×1472. Selfie at least 512×512 with face over 15% of height. [ref](https://docs.perfectcorp.com/reference/ai_bag) |
| Fashion | AI Fabric VTO (`ai_fabric`) | `/task/fabric` (templates) | 2 | Single person, upright, face, shoulders and abdomen visible. [ref](https://docs.perfectcorp.com/reference/ai_fabric) |
| Jewelry | AI Ring VTO (`ring_vto`) | `/task/2d-vto/ring` | 1 (single) or 2 (stacked) | Back of hand with all 5 fingers visible. Product image has automatic background removal; optional occlusion masks. `ring_wearing_finger` 0–4, `ring_shadow_intensity` 0–1. Long side ≤4096. [ref](https://docs.perfectcorp.com/reference/ring_vto) |
| Jewelry | AI Bracelet / Earrings VTO | `/task/2d-vto/bracelet`, `/task/2d-vto/earring` | 1 (single) or 2 (stacked) | Bracelet product shot at about 45° three-quarter view. Earrings support frontal and dual-ear since v1.10. Optional anchor points. [ref](https://docs.perfectcorp.com/reference/ai_earrings) |
| Jewelry/Watch | AI Watch / Necklace VTO | `/task/2d-vto/watch`, `/task/2d-vto/necklace` | 1 (single) | Watch must be upright and front-facing, with the clasp not visible; optional 4 anchor points. Necklace: neck width at least 15% of image width, head rotation within 20°. [ref](https://docs.perfectcorp.com/reference/ai_watch) |

**Not eligible on their own (Image/Video "Creators" group)**

| API | Endpoint | Units |
|---|---|---|
| Background Removal | `/task/sod` | 1 |
| Background Change | `/task/bg-replace` | 4 |
| Background Blur | `/task/bg-blur` | 1 |
| Photo Enhance (1x/2x/4x) | `/task/enhance` | 2 |
| Colorize | `/task/colorize` | 2 |
| Color Correction | `/task/colorize/color-correct` | 2 |
| Lighting | `/task/lighting` | 2 |
| Image Extender | `/task/out-paint` | 2 |
| Object Removal Pro | `/task/generative-fill` | 1 standard / 2 professional |
| AI Replace | `/task/obj-replace` | 1 |
| Face Swap | `/task/face-swap` | 1 |
| Watermark Removal | `/task/wmk-removal` | 1 |
| Avatar | — | 1 unit per 4 images |
| Headshot / Studio | — | 1 unit per 2 images |
| Image Generator | — | V1: 2; V2 (`/task/text-to-image/youcam`, `/task/image-to-image/youcam`): 1 |
| Video Generator | — | Std V1: 3/s; Pro V1: 6/s; I2V V2: 1/2/3 per second at 480p/720p/1080p; T2V V2: 2 (720p) or 3 (1080p) per second |
| Video Enhancer | — | 1 per 2 s |
| Video Face Swap | — | 1 per 5 s |
| Video Style Transfer | — | 4/s |
| Video Object Removal | — | 2/s |
| Video Background Replace | — | 2/s |

— [OpenAPI bundles](https://docs.perfectcorp.com/reference/ai_video_generator); [Background Change](https://docs.perfectcorp.com/reference/ai_photo_background_change)

**Recent additions (changelog)** — [Changelog](https://docs.perfectcorp.com/release/changelog)
- v1.16, 2026-09-24: Watermark Removal; Shoes VTO V3 (reference-image shoe generation with style, shape, color and material); a `hair_color` param on Hairstyle v2.1.
- v1.15.1, 2026-09-04: YouCam Skills, and multi-person filtering for AI Clothes.
- v1.15, 2026-08-26: Nail Transfer.
- v1.14.1, 2026-08-06: outerwear try-on.
- v1.14, 2026-07-28: Abs Filter, Background Blur, and a universal file upload for images and video.
- v1.13, 2026-06-29: feature-cost endpoint and task delete.
- v1.12.1, 2026-06-09: Skin Analysis v2.1 (new engines, output up to 2560 px).
- v1.12, 2026-05-28: Fitzpatrick.
- v1.11.1: whole-face plus T-zone and U-zone skin type, and tear trough.
- v1.10, 2026-03-30: Eye Color Lens, Teeth Whitening, Hair Density.
- v1.9, 2026-03-02: Skin Simulation, Breast Augmentation.
- v1.8, 2026-01-28: Nail VTO, Face Reshape, Body Reshape, Hairstyle; skin-analysis input raised to 4096 px.
- v1.7, 2025-12-29: Hat, Scarf, Bag, Shoes, Ring, Bracelet, Watch, Earrings and Necklace VTO; simplified V2 structure for all APIs.
- v1.6, 2025-11-25: Makeup VTO, Look VTO, webhooks.

### Inferences
- Cheapest eligible building blocks, 1 unit each: makeup VTO, hair color, nail VTO, eye lens, teeth whitening, single jewelry pieces, and face lift/reshape. With 1,000 units that is about 1,000 calls.
- Expensive calls: HD skin analysis with all 16 concerns (22 units, about 45 calls per 1,000 units), the skin tone analyzer (20 units, 50 calls), Fitzpatrick (10 units), and the face analyzer (10–30 units). Skin-heavy apps should cache results and use SD or fewer concerns during development.
- Shoes, Hat, Scarf and Bag need a `gender` parameter and use preset "styles" that generate a whole look. They are generative, not exact product overlays, which is worth checking against eCommerce fidelity needs.
- Whether body/face-editing APIs (Body Reshape, Breast Augmentation, Abs Filter, Face Reshape, Smile) count as the "Skin" category is unclear. They sit in the docs' "Skin, Face & Body" group, but the rules name only "Skin". Building on Skin Analysis or a clear VTO API is safer.

### Gaps
- No unit cost is published for Clothes `cloth-v4`; only V2.0 and V3.0 are listed at 2 units. Check with GET `/s2s/v2.0/credit/feature-cost`.
- I did not extract the full template counts for Look VTO, hairstyle presets or cloth templates. They are available at runtime via the GET `/task/template/...` endpoints.

---

## Q4. Integration model: auth, async task pattern, files, rate limits, retention, webhooks, SDKs, latency

### Takeaway
YouCam API is REST-only and asynchronous. You authenticate with a Bearer API key, register a file to get a pre-signed S3 PUT URL (or pass a public URL), create a task, then poll the task or receive a webhook. Units are charged only when a task succeeds. Rate limit is 250 requests per 300 s per IP and per token. There is no on-device AR or try-on SDK in the API product. The only SDKs are "Camera Kits" (a web JS kit and an Android/iOS kit) that guide and quality-check the photo capture.

### Cited Findings
- Auth: "Include your API key in the request header using Bearer Token: Authorization: Bearer YOUR_API_KEY". Keys are generated on the API Key tab of the console. — [Quick Start](https://docs.perfectcorp.com/develop/quick_start_guide)
- Common auth mistakes: missing the "Bearer " prefix, or wrapping the key in `<>`. An invalid key returns 401 `InvalidAccessToken`. — [Debugging Guide](https://docs.perfectcorp.com/develop/debugging_guide); [AI Clothes ref](https://docs.perfectcorp.com/reference/ai_clothes)
- The FAQ mentions a "secret key ... created only when you first generate it". The rate-limit page refers to "access token". These look like leftovers from the older V1 client-secret/access-token scheme. V2 is Bearer API key only. — [FAQ](https://docs.perfectcorp.com/develop/faq); [Rate Limit](https://docs.perfectcorp.com/develop/rate_limit)
- The API is described as "standard RESTful APIs to let you easily integrate to your website, e-commerce platforms, iOS/Android APP, applets, mini-programs". Docs version: v1.16. — [Introduction](https://docs.perfectcorp.com/develop/introduction)
- API server: `https://yce-api-01.makeupar.com`. — [API Server](https://docs.perfectcorp.com/develop/api_server). In my probe, both `yce-api-01.makeupar.com` and `yce-api-01.perfectcorp.com` answered HTTP 401 to an unauthenticated GET on `/s2s/v1.0/client/credit`, so both hosts are live. (Own probe, 2026-10-07.)
- **Workflow (5 steps)**
  1. POST `/s2s/v2.0/file` with `{files:[{content_type,file_name,file_size}]}`. This returns a `file_id` and `requests[].url`, a pre-signed PUT URL on `yce-us.s3-accelerate.amazonaws.com`, plus the headers to use.
  2. PUT the bytes to that URL.
  3. POST `/s2s/v2.0/task/<feature>` with `src_file_id` or `src_file_url` (any public image URL). This returns `task_id`.
  4. GET `/s2s/v2.0/task/<feature>/{task_id}` until `task_status` is `success` or `error`. While the task runs, the status stays 'running'.
  5. The result has download URLs, and a `dst_id` that lets you "chain another AI task without re-upload".

  — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis); [Quick Start](https://docs.perfectcorp.com/develop/quick_start_guide)
- "Simply calling the File API does not upload your file". Skipping the PUT causes 404 or 500 `unknown_internal_error`. — [Debugging Guide](https://docs.perfectcorp.com/develop/debugging_guide)
- Since v1.14 there is a universal File API for images and video. File size limits are "10 MB for image files and 100 MB for video files". — [File API spec](https://docs.perfectcorp.com/reference/file); [Changelog](https://docs.perfectcorp.com/release/changelog)
- Billing: "Your units will only be consumed in this case [success]. If the engine fails ... no unit will be consumed." Units nearest expiry are deducted first. — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- Rate limits: each IP address and each access token is limited to "250 requests per 300 seconds". Exceeding the limit returns 429. Recommended pacing is "~5 requests per second (5 QPS)". Back off and retry. — [Rate Limit](https://docs.perfectcorp.com/develop/rate_limit)
- Retention: uploaded files and `file_id` last 30 days. A `task_id` stays valid for 30 days. A result download URL is "valid for 2 hours", and you can get a new one with the task_id. All files are auto-removed after 30 days. — [File Retention](https://docs.perfectcorp.com/develop/file_retention_period). Conflict: the Skin Analysis reference says "Processed results are retained for 24 hours after completion". — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis). The Fitzpatrick spec also says the task result is queryable "for 24 hours". — [Fitzpatrick ref](https://docs.perfectcorp.com/reference/ai_fitzpatrick_skin_type)
- Polling an expired task returns `InvalidTaskId`. — [FAQ](https://docs.perfectcorp.com/develop/faq)
- Task delete: POST `/s2s/v2.0/task/delete` "Delete a task and its files", added in v1.13. — [Task Management spec](https://docs.perfectcorp.com/reference/task_management); [Changelog](https://docs.perfectcorp.com/release/changelog)
- Unit system endpoints:
  - GET `/s2s/v1.0/client/credit`: balance to two decimals, plus each unit lot's expiry timestamp.
  - GET `/s2s/v1.0/client/credit/history`: usage history, including the skin-analysis dst_actions used.
  - GET `/s2s/v2.0/credit/feature-cost`: per-feature unit cost, "consistent with those listed at https://yce.perfectcorp.com/ai-api/api-pricing".

  — [Unit System spec](https://docs.perfectcorp.com/reference/unit_system)
- Webhooks (since v1.6): they follow the Standard Webhooks spec with HMAC-SHA256 and a `whsec_`-prefixed base64 secret. Headers are `webhook-id`, `webhook-timestamp` and `webhook-signature` (v1). The body is `{created_at, data:{task_id, task_status}}`. Endpoints are configured in the console at `/api-console/en/webhook/`, up to 10 of them, and must be HTTPS. — [Webhook](https://docs.perfectcorp.com/develop/webhook)
- Large IDs exceed JavaScript's 2^53 limit. Postman's "Pretty" view rounds them, so use json-bigint or treat IDs as strings. — [Debugging Guide](https://docs.perfectcorp.com/develop/debugging_guide)
- Common error codes:
  - `error_no_face`, `error_large_face_angle`, `error_multiple_people`, `error_no_shoulder`, `error_hair_too_short`, `error_bald_image`, `error_nsfw_content_detected`, `error_unsupport_ratio`
  - Skin analysis: `error_src_face_too_small`, `error_lighting_dark`, `error_src_face_out_of_bound`

  — [Error Codes](https://docs.perfectcorp.com/develop/error_codes); [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- **JS Camera Kit v2.5** (web SDK, capture only)
  - Load it from `https://plugins-media.makeupar.com/v2.5-camera-kit/sdk.js`. It installs a global `YMK` object with `YMK.init({faceDetectionMode, imageFormat:'base64'|'blob', language, qualityLevel:'relaxed'|'moderate'|'strict', videoQuality:'720p'|'1080p'|'1920p'})`, `openCameraKit()`, and events such as `faceQualityChanged` and `faceDetectionCaptured`.
  - It needs getUserMedia, HTTPS, and a `<div id="YMK-module">` mount point.
  - Detection modes: makeup, skincare, hdskincare (2560 px webcams), shadefinder, facereshape, hairlength, hairfrizziness, hairtype (3-phase capture), hairdensity, ring, wrist, necklace, earring, teethwhiten, nail, and comprehensive. Comprehensive mode takes one photo for Makeup, Skin Analysis and Face Attributes.

  — [JS Camera Kit](https://docs.perfectcorp.com/reference/ai_skin_analysis/section/overview/js-camera-kit)
- **Mobile Camera Kit v2.5.0** (Apr 16, 2026): "real-time camera frame quality checking for AI Skin Analysis API". It checks lighting, face area and head pose. On Android (6.0+) it ships as `PerfectLibCameraKit.aar` plus model files; on iOS (12+) as a static `PerfectLibCameraKit.framework`. It is a public zip download at `https://us-consultation-cdn.perfectcorp.com/ttlx/8296658a-d9dd-45ce-ad4d-7cee3d03de45.zip`. — [Mobile Camera Kit](https://docs.perfectcorp.com/reference/ai_skin_analysis/section/overview/mobile-camera-kit)
- The Skin Analysis v2.1 request body has a `pf_camera_kit` field. — [Skin Analysis OpenAPI bundle](https://docs.perfectcorp.com/_bundle/reference/ai_skin_analysis.yaml?download)
- Sample code in the docs is provided for cURL, Node.js ≥18, browser JS, PHP ≥7.4, Python ≥3.10 and Java 11+. — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- Latency: task responses include `timed` ("Engine processing time, in seconds"). The docs say "execution time is not guaranteed", so polling is still required. — [Fitzpatrick spec](https://docs.perfectcorp.com/reference/ai_fitzpatrick_skin_type); [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)

### Inferences
- Every try-on is photo-in, image-out: an async round trip of seconds, not a live AR video overlay. A "live mirror" experience would need the JS Camera Kit for guided capture, followed by async processing. The camera kits are freely downloadable, so hackathon teams can use them. Nothing in the docs suggests that Perfect's real-time AR makeup/jewelry SDK (sold to enterprises) is available through this API program.
- The pre-signed upload flow plus the Bearer key means production apps should proxy calls through a backend to keep the key secret. A third-party hackathon repo ("VirtuFit ... powered by YouCam cloth-v3 browser-direct", [GitHub](https://github.com/yashwanth07-debug/virtufit)) suggests that calling the API directly from a browser works, but that would expose the key.
- The `dst_id` chaining feature (no re-upload) enables cheap pipelines, for example face analyzer → makeup VTO → look VTO, or clothes VTO → background change.

### Gaps
- No documented latency figures or SLAs. Expect several seconds per task; this is unverified.
- The retention conflict (30 days / 2 h URL vs "24 hours") is unresolved. Design for the stricter case: download results right away.
- CORS behavior is not documented.
- No official Postman collection was found. The OpenAPI YAML/JSON bundles can be imported into Postman (`/_bundle/reference/{api}.json?download`).

---

## Q5. What the key analysis APIs return (outputs useful for product logic)

### Takeaway
Skin Analysis returns per-concern `raw_score` and `ui_score` (1–100), detection masks, an overall score and `skin_age`. Several analyzers return structured labels or hex colors that can feed recommendation logic: face shape and features, color tones, Fitzpatrick type, and hair type, length, frizz and density.

### Cited Findings
- **Skin Analysis outputs**
  - Per concern, `raw_score` (float 1–100) and `ui_score` (integer 1–100). `ui_score` is adjusted upward: "consumers generally prefer positive evaluations". Higher always means healthier.
  - Also returned: `mask_urls` or PNG masks with alpha for overlay, `all.score` (overall), and `skin_age`.
  - Output as `format=json` (scores plus mask URLs in the response; since v1.7) or `zip` (score_info.json plus PNGs).
  - Masks can be separate per concern, or one blended image via `enable_mask_overlay`. HD pore and wrinkle masks also support dark-background options.

  — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis); [Changelog](https://docs.perfectcorp.com/release/changelog)
- **Skin Analysis concerns**
  - SD (16): wrinkle, droopy_upper_eyelid, droopy_lower_eyelid, firmness, acne, moisture, eye_bag, dark_circle_v2, age_spot, radiance, redness, oiliness, pore, texture, tear_trough, skin_type.
  - HD (16): hd_redness, hd_oiliness, hd_age_spot, hd_radiance, hd_moisture, hd_dark_circle, hd_eye_bag, hd_droopy_upper_eyelid, hd_droopy_lower_eyelid, hd_firmness, hd_texture, hd_acne, hd_pore, hd_wrinkle, hd_tear_trough, hd_skin_type.
  - hd_pore has sub-regions forehead, nose, cheek and whole. hd_wrinkle has forehead, glabellar, crowfeet, periocular, nasolabial, marionette and whole.
  - skin_type has whole, t_zone and u_zone, classified as Normal, Oily, Dry, Combination, Redness, Dry & Redness, Oily & Redness, or Combination & Redness.

  — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- **Skin Analysis capture guidance**
  - Face should be 60–80% of the image width.
  - Even, bright lighting; front-facing, mouth closed, eyes open.
  - Forehead revealed, glasses off (recommended), makeup removed.
  - Portrait orientation recommended.

  — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- Agent Skills docs describe Skin Analysis as "16 skin concerns plus skin type". This differs slightly from the spec, which counts skin_type within the 16. — [Skills](https://docs.perfectcorp.com/develop/agent_skills)
- **Facial Color Tones Analyzer outputs**
  - `skin_color`, `eye_color`, `lip_color`, `eyebrow_color` and `hair_color`, all as hex values.
  - `eye_color_name`: Amber, Brown, Green, Blue, Gray or Other.
  - `hair_color_name`: Auburn, Black, Blonde, Brown, Grey/White or Red.

  — [Color Tones ref](https://docs.perfectcorp.com/reference/ai_skin_tone_analysis)
- **Face Attributes & Ratio Analyzer**
  - Face shape: Triangle, Diamond, Heart, InvTriangle, Oblong, Oval, Round or Square.
  - Eyes: shape (Narrow/Round/Almond), size, angle, distance, and eyelid (Hooded, Single, Double, Deep-Set).
  - Brows: shape, thickness, distance, shortness.
  - Lips: 10 lip shapes.
  - Nose: width and length.
  - Cheekbones: Flat, High, Low or Round.
  - Ratios against "golden ratio" targets: horizontal thirds, vertical fifths, face aspect 1:1.46, eye aspect, eyebrow arch, nose aspect, nose-to-mouth width, nose-lip-chin, and upper-to-lower lip.
  - Up to 28 features in total.

  — [Face Analyzer ref](https://docs.perfectcorp.com/reference/ai_face_analyzer)
- **Fitzpatrick** returns `fitzpatrick_scale` with values I, II, III, IV, V or VI, after a pre-process detection step that returns face boxes and an index. — [Fitzpatrick ref](https://docs.perfectcorp.com/reference/ai_fitzpatrick_skin_type)
- **Hair analyses**
  - Hair type: categories include 2A Slight Wavy, 2B Medium Wavy, 2C Thick Wavy, 4A Kinky Soft, 4B Coily and 4C Extremely Coily, returned as `mapping` and `term` values. The MCP docs describe "9 clear types".
  - Hair length terms: "above the ears", "ear length", "ear length or longer", "short hair", "short hair or longer", "above chest", "above chest or longer", "long hair".
  - Frizz: mapping 0–3 (Not Frizzy, Slightly Frizzy, Frizzy, Extreme Frizzy).
  - Density: Level 1–4 (Extremely Low to High).

  — [Hair Type ref](https://docs.perfectcorp.com/reference/ai_hair_type_detection); [Hair Length ref](https://docs.perfectcorp.com/reference/ai_hair_length_detection); [Frizziness ref](https://docs.perfectcorp.com/reference/ai_hair_frizziness_detection); [Density ref](https://docs.perfectcorp.com/reference/ai_hair_density_detection); [MCP](https://docs.perfectcorp.com/develop/mcp)
- **Skin Simulation** gives a before/after visualization. Intensity guide: 0.1–0.3 "Subtle refinement", 0.4–0.6 "Balanced enhancement", 0.7–1.0 "Full correction". — [Skin Simulation ref](https://docs.perfectcorp.com/reference/ai_skin_simulation)
- **Makeup VTO effect categories**
  - skin_smooth, foundation, concealer, blush, bronzer, contour, highlighter, eye_shadow, eye_liner, eyelashes, eyebrows, lip_color, lip_liner.
  - Each takes a hex color and intensity (0–100). Some take textures: blush uses matte, satin or shimmer.
  - Pattern catalogs are public JSON files, e.g. https://plugins-media.makeupar.com/wcm-saas/patterns/blush.json.
  - A default skin smoothing of 50 is applied unless overridden.

  — [Makeup VTO ref](https://docs.perfectcorp.com/reference/makeup_vto)
- Disclaimer from the Skills docs: "All outputs are AI-generated and intended for reference only. They are not medical, dermatological, cosmetic, or professional styling advice." — [Skills](https://docs.perfectcorp.com/develop/agent_skills)

### Inferences
- Hex color outputs from the Color Tones Analyzer, combined with makeup VTO hex inputs, allow a closed loop: detect skin, lip and eye color, choose product shades, then render them.
- Skin_type with T-zone and U-zone, plus per-concern scores, give enough structure for routine and product-matching logic without a separate ML model.
- The `ui_score` is deliberately inflated. An honest-feedback app should base its logic on `raw_score`.
- The docs make no dermatology-grade or medical claim. Projects should avoid diagnostic language. Skin-health ideas must be framed as cosmetic and informational.

### Gaps
- I did not extract the full list of 9 hair types; types 1 and 3A–3C were not captured.
- No published accuracy or validation figures for skin analysis were found in the docs.

---

## Q6. Pricing beyond the free tier

### Takeaway
The pricing page (https://yce.perfectcorp.com/ai-api/api-pricing) renders prices client-side, so I could not extract exact plan prices. Confirmed facts: pay-as-you-go units are valid for 1 year, and a "30% off on Pay-as-you-go credits" offer appears in the page's text strings. Two different dollar values for units appear in official Perfect Corp materials.

### Cited Findings
- The pricing page's front-end text includes "Pay-as-you-go units are valid for 1 year after being received." and "30% off on Pay-as-you-go credits". The page also links to a "Unit Calculator" at /ai-api/unit-calculator. — [Pricing page](https://yce.perfectcorp.com/ai-api/api-pricing) (strings found in the page's JS bundles)
- The Quick Start says you can "purchase or subscribe to get your units", and subscription plans, pay-as-you-go units and usage records are shown in the console. — [Quick Start](https://docs.perfectcorp.com/develop/quick_start_guide)
- Perfect Corp's DeveloperWeek 2026 announcement valued "1,000 free API units" at "$179". — [Perfect Corp news](https://www.perfectcorp.com/business/news/hackathon-2026-perfect-corp)
- The previous YouCam hackathon valued "5,000 YouCam API Units" at "≈$275". — [youcam-api.devpost.com](https://youcam-api.devpost.com/)
- Per-feature unit costs can be fetched for free via GET `/s2s/v2.0/credit/feature-cost`. With the Skills tooling, `python scripts/youcam_core.py cost --feature skin-analysis` and `credits` are free preflight checks. — [Unit System spec](https://docs.perfectcorp.com/reference/unit_system); [Skills](https://docs.perfectcorp.com/develop/agent_skills)

### Inferences
- The two valuations imply about $0.179 per unit (small pay-as-you-go) versus about $0.055 per unit (larger pack or subscription). These are probably different tiers, so per-unit price drops sharply with volume. Treat this as an estimate.

### Gaps
- Exact plan names, prices, included units and enterprise terms could not be read because the page is JS-rendered and its pricing API was not found. Check manually in a browser or the console.

---

## Q7. Official sample code, GitHub repos, Postman, MCP servers and agent integrations

### Takeaway
Perfect Corp offers an official **remote MCP server** split into Beauty, Fashion and Creators endpoints, which works with Claude Desktop, Cursor and VS Code Copilot. There are also official **Agent Skills** (GitHub `YouCam-API/skills`, a Python CLI) and an **API Playground** that generates sample code. No official sample app repo or Postman collection was found.

### Cited Findings
- MCP servers:
  - `https://mcp-api-01.makeupar.com/mcp/beauty`
  - `https://mcp-api-01.makeupar.com/mcp/fashion`
  - `https://mcp-api-01.makeupar.com/mcp/creators`

  Auth uses an `Authorization: Bearer YOUR_API_KEY` header. Config examples are given for Claude Desktop (via `npx mcp-remote`), Cursor and VS Code Copilot. — [MCP](https://docs.perfectcorp.com/develop/mcp)
- MCP tools, Beauty server: AI_Skin_Analysis, AI_Skin_simulation, AI_Facial_Color_Tones_Analyzer, AI_Aging_Simulation, AI_Face_Attributes_and_Ratio_Analyzer, AI_Face_Lift, AI_Face_Reshape, AI_Fitzpatrick_Skin_Type_Analysis, AI_Smile, AI_Teeth_Whitening, all hair VTO and detection tools, body tools, makeup/nail/eye/look/beard tools, plus utilities: File_Upload (drag-and-drop widget), Get_Running_Task_Status, Get_Upload_API_Info and Get_Feature_Cost. — [MCP](https://docs.perfectcorp.com/develop/mcp)
- MCP tools, Fashion server: AI_Clothes_Virtual_Try_On, AI_Fabric_Virtual_Try_On (+Templates), AI_Shoes, AI_Hat, AI_Scarf, AI_Bag, AI_Bracelet, AI_Earrings, AI_Necklace, AI_Ring and AI_Watch Virtual Try-On. — [MCP](https://docs.perfectcorp.com/develop/mcp)
- MCP history: v1.7 supported 18 APIs, v1.8 26 APIs, and v1.14 "access all APIs". In v1.14.2 (2026-08-11) it was split into three solution categories. — [Changelog](https://docs.perfectcorp.com/release/changelog)
- Official GitHub org `YouCam-API` has 4 repos: `skills` (Python, created 2026-08-31), `beauty-skin-care-MCP`, `fashion-retail-MCP` and `creators-MCP`. — [GitHub YouCam-API/skills](https://github.com/YouCam-API/skills); [GitHub YouCam-API/fashion-retail-MCP](https://github.com/YouCam-API/fashion-retail-MCP)
- **YouCam Skills**
  - Install with `npx skills add YouCam-API/skills` (or `--skill skin-analysis-expert -a claude-code`, or `--all`).
  - Six skills: Skin Analysis Expert, Facial Consultant, Beauty Advisor, Hair Color & Style Advisor, Hair Diagnostics, and Clothes Try-on Studio. The last includes "optional background replacement and short motion videos".
  - CLI: `python scripts/youcam_core.py run --feature skin-analysis --src_file selfie.jpg --param dst_actions='["hd_pore","hd_skin_type"]'`. It handles upload, task and polling, and includes free `cost` and `credits` preflights. The key comes from the `YOUCAM_API_KEY` env var or credentials.json.

  — [Skills](https://docs.perfectcorp.com/develop/agent_skills)
- API Playground: the user picks a feature, selects a key, chooses a source (local file, URL or samples), configures parameters, reviews the payload and "Sample Code", and runs it. — [API Playground](https://docs.perfectcorp.com/develop/api_playground)
- OpenAPI 3.0 bundles for each API can be downloaded (`/_bundle/reference/{api}.yaml?download` or `.json?download`). — [Skin Analysis ref](https://docs.perfectcorp.com/reference/ai_skin_analysis)
- Community repos:
  - `nakamura196/zenn-youcam`: "20 タスク全網羅検証 + 公式ドキュメントに無いスキーマ集", i.e. a test of all 20 tasks plus schemas not in the official docs.
  - `pft-AJChou/Youcam`: "OpenAPI for Perfect YouCam API".
  - Many repos from the previous hackathon, e.g. `uiharu-kazari/anywear` and `yashwanth07-debug/glow-skin`.

  — [GitHub search](https://github.com/nakamura196/zenn-youcam); [GitHub](https://github.com/pft-AJChou/Youcam); [GitHub](https://github.com/uiharu-kazari/anywear)
- Repos already tagged for this hackathon: `Bowen1314/unstack` ("Check your skincare shelf before you layer it", Skin Analysis), `aposalik/TheLook` ("FitRoom"), and `oritercompany-ui/tryora-ai` (makeup try-on). — [GitHub](https://github.com/Bowen1314/unstack); [GitHub](https://github.com/aposalik/TheLook); [GitHub](https://github.com/oritercompany-ui/tryora-ai)

### Inferences
- The MCP and Skills tooling makes "agentic" beauty and styling assistants cheap to prototype. The 1st-place winner of the previous hackathon used the YouCam MCP server (see Q9). Because of that precedent, MCP alone is unlikely to count as a "non-obvious" idea this round.

### Gaps
- No official end-to-end sample web or mobile app and no Postman collection were found.
- I did not inspect the contents of the YouCam-API GitHub repos beyond their descriptions.

---

## Q8. Data privacy terms (images, biometrics, retention)

### Takeaway
Perfect's API privacy policy says face scans may be collected but facial recognition is not used, and data is not used for model training. It says data is generally kept 30 days and stored in the USA. API customers are the data controller and must get end-user consent.

### Cited Findings
- "Perfect and/or any such third parties do not and will not use facial recognition or identification technology in providing the Services." — [API Privacy Policy](https://www.perfectcorp.com/perfectbeauty/youcam/privacy-policy-api)
- Personal information and user content "will not be used for any other purposes beyond those stated in this Privacy Policy (including, for example, model training)." — [API Privacy Policy](https://www.perfectcorp.com/perfectbeauty/youcam/privacy-policy-api)
- "We generally retain your Data for 30 days after you complete each session of the Service." Data may be kept longer when needed for the policy's purposes or required by law. "We store your Data on our servers located in the USA." — [API Privacy Policy](https://www.perfectcorp.com/perfectbeauty/youcam/privacy-policy-api)
- "you remain the data controller responsible for establishing a lawful basis for the collection and processing of API Data, including obtaining any necessary consents from your end users." The policy cites Illinois BIPA definitions of biometric identifiers and lists GDPR rights. — [API Privacy Policy](https://www.perfectcorp.com/perfectbeauty/youcam/privacy-policy-api)
- Technical retention: uploads and results are auto-deleted after 30 days, and a task's files can be deleted early with POST `/s2s/v2.0/task/delete`. — [File Retention](https://docs.perfectcorp.com/develop/file_retention_period); [Task Management](https://docs.perfectcorp.com/reference/task_management)
- The OpenAPI specs link the API ToS and privacy policy on makeupar.com: https://www.makeupar.com/perfectbeauty/youcam/terms-of-service-api and https://www.makeupar.com/perfectbeauty/youcam/privacy-policy-api. — [Skin Analysis OpenAPI bundle](https://docs.perfectcorp.com/_bundle/reference/ai_skin_analysis.yaml?download)

### Inferences
- A consent screen plus a "delete my photos" action that calls task/delete would show privacy awareness to judges, and costs little to build. A previous winner, KeepMe, won partly on consent and integrity (see Q9).

### Gaps
- I did not read the API Terms of Service in full, e.g. for restrictions on medical use or on storing results.

---

## Q9. Previous Perfect Corp hackathons and winners

### Takeaway
This is at least Perfect Corp's third Devpost hackathon in 2026. Before it came DeveloperWeek 2026 (Feb, sponsor prize) and the "YouCam API Skin AI & Apparel VTO Hackathon" (Jul 6 – Aug 17, 2026, 1,278 participants, $5,000 first prize). In the Apparel VTO hackathon, winners favored accessibility, inclusive skin-tone representation, trust and consent, and merchant/B2B tools over generic try-on apps.

### Cited Findings
- **YouCam API Skin AI & Apparel VTO Hackathon** (https://youcam-api.devpost.com/):
  - Dates: Jul 6 – Aug 17, 2026. 1,278 participants. Judges listed as "YouCam API Team".
  - Prizes: 1st $5,000; 2nd $1,000; 3rd–5th "5,000 YouCam API Units (≈$275)". All places also got a blog feature and marketing meeting.
  - Same four judging criteria as this hackathon.

  — [youcam-api.devpost.com](https://youcam-api.devpost.com/)
- Its three categories were Skin AI, Apparel VTO, and a combined Skin AI + Apparel VTO "unified experience". — [Devpost search result](https://youcam-api.devpost.com/)
- It launched at WeAreDevelopers Berlin (July 9–10, 2026), where an on-site booth offered 500 extra free units. The press release gave the deadline as August 16, 2026; the Devpost page says Aug 17. — [Perfect Corp news](https://www.perfectcorp.com/business/news/WeAreDevelopers)
- **1st place: Aloud.** "Beauty, aloud. The first beauty AI a blind shopper can use alone, screen off." By Stephen Sookra. Uses YouCam Skin Analysis API, Skin Tone Analysis and the YouCam MCP Server. Features: voice-guided barcode scanning, an ingredient/allergen Q&A over a realtime voice API, skin analysis "with bias disclosure for deeper skin tones", and post-makeup verification. Web plus Capacitor mobile. — [Aloud](https://devpost.com/software/aloud-lxqr70)
- **2nd place: ShadeSpan.** "The same t-shirt is obvious on one customer and nearly invisible on another." By Kumar Abhinav. A catalog audit tool that renders garments across skin tones with Apparel VTO and Skin AI, then grades visibility and color distinction (CIEDE2000, WCAG contrast). Python/FastAPI dashboard. — [ShadeSpan](https://devpost.com/software/shadespan)
- **3rd–5th place: CASTING.** "Show your customers someone who looks like them. One product photo, eight measured skin tones." By Lutfiya Miller and Chris Müller. Uses AI Clothes VTO, Skin Analysis, Fitzpatrick and Facial Color Tones; produces a coverage board with ΔL* and ΔE2000. Next.js. — [CASTING](https://devpost.com/software/casting)
- **3rd–5th place: KeepMe.** "makes AI virtual try-on trustworthy". Users set what may change, detect unwanted changes, repair drift, and get signed proof. By Ankit Hemant Lade and Sai Krishna Jasti. Uses Clothes v3 and Skin Analysis v2.1. — [KeepMe](https://devpost.com/software/keepme)
- **3rd–5th place: ConfidFit.** A Shopify app adding YouCam generative apparel try-on (cloth-v3), with merchant analytics and billing. By João Nunes. — [ConfidFit](https://devpost.com/software/confidfit)
- Other submissions in that gallery, to show crowded idea space: Atelier (selfie → skincare + makeup + outfit), Wabi-Sabi, MirrorMind, BreakoutGate, Slip (Chrome extension for fit), ClosetIQ, Wearwise, Skin Journey (progress tracking), Drape (skin-tone styling), Parallax (3D fitting), GlowCycle (cycle- and climate-adaptive skin guidance), MirrorFit, Muse, CosplayAI, Before You Cut, BaddieGuide, Labelle, Wearwheather. — [Project gallery](https://youcam-api.devpost.com/project-gallery)
- **DeveloperWeek 2026 Hackathon:** online Feb 2–20, 2026, plus in person Feb 18–20 in San Jose. The Perfect Corp prize paid $1,500 for 1st and $1,000 for 2nd, and entrants got 1,000 free units ("$179 value"). — [Perfect Corp news](https://www.perfectcorp.com/business/news/hackathon-2026-perfect-corp)
- DeveloperWeek Perfect Corp prize winners: "CLOSET 'What to wear today?'", an AI outfit recommender with "AR try-on across 10 fashion categories", and "FitCast", which shows weather-based outfits on the user's photo. — [DeveloperWeek gallery](https://developerweek-2026-hackathon.devpost.com/project-gallery)

### Inferences
- What the winners had in common:
  - They serve a specific, underserved audience: blind shoppers, or darker skin tones in catalogs.
  - They often target merchants or B2B users (catalog audit, Shopify app).
  - They add trust layers on top of try-on (consent, integrity, bias disclosure).
  - They combine several APIs in measurable ways (color science, ΔE).
- Generic ideas were common and did not place: "selfie → skin report → routine → outfit try-on", closet stylists, weather outfit apps, and progress trackers. This round adds eCommerce VTO (beauty plus fashion plus jewelry). Under-explored areas include jewelry and watch VTO, hair diagnostics, nail VTO, and Fitzpatrick or color-tone-driven shade matching.

### Gaps
- For the Apparel VTO hackathon, which of CASTING, KeepMe and ConfidFit placed 3rd, 4th or 5th is not distinguished on Devpost ("3rd–5th Place Winner").
- For DeveloperWeek, which of CLOSET and FitCast got 1st versus 2nd in the Perfect Corp prize was not confirmed.
- I found no Perfect Corp hackathons before 2026.

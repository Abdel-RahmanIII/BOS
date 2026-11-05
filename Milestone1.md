# Milestone 1: Project Idea & Business Model Canvas

## Founders' Contribution Table (1 Page)
| Founder Name | Role | Deliverables & Sections Owned | % Contribution |
| :--- | :--- | :--- | :--- |
| Nooreldeen | CEO / Product owner | 1.1 Section 1 (Vision and Mission), Section 3 (Customer Discovery), Section 9 (Company Type and Founding Structure); Appendix A (Interview Log); Appendix B (Cap Table); Deliverable 1.2 (Business Model Canvas and Pricing Hypothesis) | |
| Abdelrahman | CTO | Technical deliverables | |
| Ahmed | COO | Operations deliverables | |

---

## Deliverable 1.1: Founding Memo (Max. 12 Pages, Excluding Appendices)

### 1. Vision and Mission
* **10-Year Vision:** To become the operating system for barbershops and salons across MENA, where every chair is visible, every wait is predictable, and no customer is lost.
* **Daily Mission:** Every day, we show customers the live wait for their own barber, or let them book him for a slot sized to their service (about 30 minutes for hair, 20 for a beard), so they arrive just in time. Shops keep their queue fair and replace their paper logs.

#### How the Mission Leads to the Vision
* **Today (Cairo barbershops):** Live per-barber wait, plus the automatic service log that replaces the front desk's paper.
* **Next:** Service-based booking with a specific barber, introduced shop by shop once owners see that visible bookings stay fair to walk-ins.
* **In 10 years:** Salons and grooming businesses across MENA, running their queues, bookings and records on one platform.

#### Why It Fits Our Evidence
* **"Their own barber":** Customers are loyal to one barber, and walk-outs happen while other barbers are free.
* **"Live wait" first:** Both shops we interviewed refuse reservations, because it is unfair to customers who arrived first. We intend to change that policy, not work around it. Our answer to the fairness objection:
  - Every booked slot is shown on the shop screen, so walk-ins see why someone goes ahead;
  - Bookings only fill a barber's free time; and
  - A small deposit discourages no-shows.
  *(Changing this policy is our riskiest assumption, so we test it with owners before building booking).*
* **"Slot sized to their service":** A haircut and a beard take different times, so slots and wait estimates are calculated per service instead of a flat appointment length.
* **"Replace their paper logs":** Shops record every service per barber by hand and pay for no software today.

### 2. Problem and Customer

* **Problem Description:**
  * **Who Has the Problem:**
    * **The Primary Buyer (Barbershop Owner-Operator):** Owners of multi-chair, upper-mid barbershops suffer from severe queue imbalances and blind operations. Demand clusters around 1–2 popular barbers while other chairs sit empty, causing shops to lose revenue from untracked walk-outs while relying on manual paper notebooks and constant phone interruptions.
    * **The End-User (The Loyal or High-Intent Client):** Young men and professionals who demand a haircut from *their specific barber*—either through personal loyalty or after discovering a barber via social media (e.g., viral TikTok/Instagram hair transformation clips). They face complete "wait blindness" with no way to check queue length before arriving.
  * **Frequency:**
    * **Daily & Peak-Bunched:** The problem occurs daily, concentrating during evenings (6:00 PM – 11:00 PM), Thursdays, Fridays, and weekends.
    * **Frequent Communication Friction:** Receptionists handle 5–10 calls per busy day solely answering *"Is [Barber X] free?"*, while individual barbers receive ~5 direct calls and messages daily.
  * **Current Solutions & Workarounds:**
    * *Guesswork & Blind Walk-Ins:* Clients show up unannounced; encountering 2–4 waiting customers, they either endure a 30–60 minute wait or walk away.
    * *Phone Calls & WhatsApp DMs:* Regulars call or message barbers and front desks directly to check availability, causing constant interruptions during operating hours.
    * *Strict "First-Come, First-Served" Policy:* Shops actively reject traditional booking apps because allowing customers to skip the physical queue violates shop floor fairness and upsets waiting walk-ins.
    * *Physical Paper Ledgers:* Staff manually log each service on paper notebooks, leaving owners with no retention tracking or customer data.
  * **Cost of the Problem:**
    * **Direct Revenue Loss for Owners:** Field interviews confirm walk-outs happen daily. At Shop 1's baseline (120 EGP/cut), losing just 3 walk-away clients per day costs **360 EGP per day, or ~10,800 EGP per month** in unrecovered top-line revenue.
    * **Uncaptured Social Discoverability:** High-intent prospective clients who discover a barber on TikTok/Instagram hit a dead end without a direct link to check live availability or queue status, failing to convert viral interest into visits.
    * **Client Time & Friction Cost:** Loyal clients lose 30–60 minutes in waiting chairs or incur wasted round-trip commutes when forced to walk away.

* **Ideal Customer Profile (ICP):**
  * **Economic Buyer ICP (Barbershop Owner-Operator):**
    * *Geography & Setting:* High-density urban commercial districts in Greater Cairo, starting in **New Cairo and Nasr City**.
    * *Shop Capacity & Tier:* Multi-chair establishments (**3 to 8 chairs**) charging **100 to 250 EGP per haircut**, where individual barber craftsmanship drives customer loyalty.
    * *Operational Profile:* Relies on manual paper logging, adheres strictly to first-come, first-served walk-ins, and wants to prevent walk-outs without disrupting shop floor fairness.
  * **End-User ICP (The Loyal / High-Intent Client):**
    * *Demographics:* Men aged **18 to 35** (students and working professionals) in urban Cairo.
    * *Behavior:* Strongly loyal to one specific barber, or actively seeking skilled barbers seen on TikTok/Instagram.
    * *Tech Profile:* App-literate smartphone user who prefers checking a live queue online over calling or waiting blindly in a shop.

* **Job-to-be-Done (JTBD) Statement:**
  * **Buyer JTBD (Shop Owner):**
    > *"When customer demand bunches on popular barbers or rushes in from social media, I want to make our live queue transparent and automate daily service logs, so I can eliminate walk-away losses and run an orderly, fair shop without hiring extra staff."*
  * **End-User JTBD (Loyal / High-Intent Client):**
    > *"When I need a haircut from my designated barber (or see his work on TikTok), I want to see his real-time queue length before heading out, so I can arrive just in time, skip the 45-minute wait, and never have to settle for another barber."* 

### 3. Customer Discovery

To validate the core problem and test our initial hypothesis, we conducted **6 customer discovery interviews** across both sides of the market: 4 on the supply side across two barbershops (2 barbers, 1 front-desk receptionist, and 1 owner) and 2 on the demand side with customers.

Following ***The Mom Test*** principles, we strictly avoided pitching our idea upfront and asked about specific, recent past behavior (*"the last busy day"*, *"the last time someone left"*), not hypothetical opinions. Where answers were vague (*"a lot"*), we asked for concrete numbers and recent examples. Statements about future intentions were flagged as weak evidence. Interviews were conducted in Egyptian Arabic, framed neutrally as a GUC academic research project: *"I'm a GUC student doing a project on barbershops. I'm not selling anything."*

| Segment | Interviews | Setting / Profile |
|---|:---:|---|
| **Barber** | 2 | Shop 1 (multi-chair, front desk), Shop 2 (peer-managed, no front desk) |
| **Front-desk receptionist** | 1 | Shop 1 |
| **Shop owner** | 1 | Shop 1 |
| **Customer** | 2 | Customer 1 (loyal to a specific barber), Customer 2 (no preferred barber) |

* **Interview Guide:** (*The Mom Test* principles — past behavior, not opinions)

  **Barbers (Shop 1 & Shop 2)**
  1. Tell me about the last busy day. How did you know whose turn it was?
  2. Are there barbers people ask for by name? When was the last time people waited for one barber while others were free?
  3. When was the last time someone left because the wait was too long? Do they come back, or go elsewhere?
  4. Do customers call or WhatsApp you before coming? Roughly how many times a day?
  5. Do you ever book someone an appointment? What happens if someone asks you to?
  6. When customers call while you're working, how do you answer?
  7. Has the shop ever used an app for bookings or the queue? What happened?

  **Front Desk (Shop 1)**
  1. Tell me about the last really busy day. How did you track the order? How many people called asking about a wait?
  2. When someone calls about a specific barber, what do you tell them?
  3. Have you ever taken reservations by phone? Why do you work first come, first served?
  4. When you tell a caller the barber is busy, what does he do next?

  **Shop Owner (Shop 1)**
  1. When did someone last leave because the barber they wanted was busy? How many do you lose like that per week?
  2. How much is a haircut? A beard?
  3. Why did you choose no reservations?
  4. Do you pay monthly for any software or app for the shop?
  5. *(Tested only at the very end)* If we built a screen showing the wait for each barber, with no reservations and no line-skipping, would you try it?

  **Customers (Demand Side)**
  1. Tell me about your last haircut. When did you go, how did you choose that time, and how long did you wait?
  2. Before going, did you call the barber or the shop? Why or why not?
  3. When did you last leave without a haircut because of the wait? What did you do after?
  4. Have you ever used an app to book anything? What happened?

* **Summary of Findings:**

  > **Core Insight:** The core problem is **customer loyalty, not shop capacity**: regulars wait for or leave one popular barber while other barbers sit idle.

  | # | Finding | Field Evidence | Heard From |
  |---|---|---|---|
  | **1** | **Demand bunches on 1–2 popular barbers while others are idle** | Popular barbers have 2–4 people waiting. *"Just now I was giving someone a haircut and another was waiting for me while the whole shop was free."* | Barber 1, Barber 2, Owner |
  | **2** | **Customers walk out daily, and nobody counts it** | Owner: walk-outs happen *"always"*, number unknown. Some return later or the next day; some never return. | Barber 1, Barber 2, Owner, Customer 1 |
  | **3** | **Customers already use a manual workaround: calling to ask "are you free?"** | 5–10 calls per busy day to the front desk; about 5 a day to one popular barber; regulars have barbers' phone numbers. | Front desk, Barber 1, Barber 2 |
  | **4** | **Customers who don't call just guess, and guess wrong** | Customer 1 went in the morning *"thinking he'd be free"* and waited ~30 minutes. | Customer 1 |
  | **5** | **Both shops refuse reservations as strict policy** | The owner's rationale is fairness: a customer who arrived first should not see a later arrival skip ahead. | Front desk, Owner, Barber 2 |
  | **6** | **Shops keep records by hand and pay for no software** | Front desk logs every service per barber on paper; at Shop 2 another barber takes payment and logs the service (shop policy). | Front desk, Owner, Barber 2 |
  | **7** | **The wait-time pain belongs exclusively to loyal customers** | Customer 2 has no preferred barber and waited 0 minutes. | Customer 2 |
  | **8** | **Phone and app habits already exist** | Barbers answer phones during cuts. Both customers book padel or football courts by app; one also books doctors. | Barber 1, Barber 2, Customers 1–2 |

  * **Prices & Illustrative Loss:** Shop 1 charges 120 EGP for a haircut, 70 EGP for a beard, 170 EGP for both. Losing 3 haircut customers a day to walk-outs equals **360 EGP a day, about 10,800 EGP a month** in lost revenue.
  * **Willingness to Pay Reality Check:** The owner stated, *"Of course I'd even pay for a service like that,"* and was open to a free trial. We treat this as stated opinion rather than committed budget, since the shop currently spends nothing on software.

* **Invalidated Assumptions & Surprises:**

  Our primary assumption—that shops want customers to book a specific barber in advance—was **invalidated**. We pivoted our MVP from advance time-slot booking to **live wait visibility**.

  | Assumption Before Interviews | What We Learned (Field Evidence) | What We Changed (Strategic Pivot) |
  |---|---|---|
  | **Shops want customers to book a barber in advance** | Both shops refuse reservations as policy. The owner says it is unfair to customers who arrived first. | **MVP shows a live per-barber wait** (*"2 waiting for [barber], about 40 minutes"*) and never changes arrival order. Booking with a specific barber comes later, introduced shop by shop once owners see that visible bookings stay fair to walk-ins (see [Section 1](#1-vision-and-mission)). |
  | **Long waits come from too few barbers** | Waits come from loyalty: regulars wait for one barber while others are free. | **Wait is shown per barber**, not aggregated per shop. |
  | **All young male customers feel the pain** | Customers with no preferred barber barely wait; they take whoever is free. | **ICP narrowed to loyal customers** who wait for one specific barber. |
  | **Customers who leave are lost for good** | At Shop 2 most leavers ask *"when will you be free?"* and return then. At Shop 1 some never return. | **Add queue alerts:** The cost is wasted trips and delay as much as lost revenue. Added a *"your barber's queue is short"* alert. |
  | **Barbers would manage the app themselves** | Shop 1 already has a front desk that logs every service on paper; Shop 2 delegates payment to a peer barber. | **Dual staff logging:** The front desk, or the designated cashier barber, marks services done. Auto-calculated totals per barber replace paper ledgers. |
  | **Barbers want customers to see their queue at all times** | Barber 2 decides whether to take another customer based on how much energy he has left. | **Queue control:** Each barber gets an individual *"open / close my queue"* toggle control. |

  **Other Surprises & Limitations:**
  * *Operational Surprises:* The owner has no idea how many customers he loses, and the front desk cannot tell whether a telephone caller later came in. At Shop 2, a peer barber takes payment and logs services to ensure internal control.
  * *Methodological Limitations:* Small sample (2 shops, 2 customers; 3 shop interviews from Shop 1). Customer 1 is the interviewer's brother (potential confirmation bias). Future willingness to pay is stated, not demonstrated. Revenue totals were withheld as confidential by Shop 1.
  * *Next Discovery Cycle:* Expand to at least 2 additional shops in other neighborhoods and arms-length customers to verify if the strict no-reservation policy and loyalty clustering hold universally.

*(Full anonymized raw interview logs with verbatim translated quotes and surprises are provided in [Appendix A: Full Customer Discovery Interview Log](#appendix-a-full-customer-discovery-interview-log).)*

### 4. Market Sizing
**Price used in both methods:** EGP 6,000 per shop per year (EGP 500/month).

---

## Top-Down

### TAM = EGP 36M 
**Calculation:** EGP 12bn × 3% × 10% = EGP 36M
- **EGP 12bn:** Annual income of Egypt's barber sector, estimated at no less than EGP 12bn by the head of the hairdressing division at the Cairo Chamber of Commerce [1].
- **× 3%:** Share of revenue a barbershop spends on software (POS, scheduling, payments) [2].
- **× 10%:** Only licensed shops can subscribe; about 200,000 of at least 2 million salons are licensed [1].

### SAM = EGP 8.6M 
**Calculation:** EGP 36M × 23.8% = EGP 8.6M
- **× 23.8%:** launches in Cairo (10.5M), Giza (9.9M) and Alexandria (5.7M), 26.1M of Egypt's 109.5M people [3].

### SOM = EGP 924k
**Calculation:** EGP 8.6M × 10.8% = EGP 924k
- **× 10.8%:** The share of SAM expected to be captured by Year 3, from the capture plan below.

---

## Bottom-Up

### TAM = EGP 41.1M (6,853 shops)
**Calculation:** 6,853 shops × EGP 6,000 = EGP 41.1M
- **6,853:** Men's barbershops listed with an address and phone in Egypt's Yellow Pages, summed across governorates: Cairo 3,037, Giza 2,519, Qalyubia 540, Alexandria 283, Menoufia 198, Sharqia 74, Kafr El-Sheikh 61, Dakahlia 59, Damietta 42, Fayoum 40 [4].

### SAM = EGP 8.0M (1,330 shops)
**Calculation:** 1,330 shops × EGP 6,000 = EGP 8.0M
- **Step 1:** Yellow Pages lists 5,839 men's barbershops in the 3 launch cities: Cairo 3,037, Giza 2,519, Alexandria 283 [4].
- **Step 2:** Of these, 1,330 have a Google Maps business profile, meaning they already use technology: Cairo 632, Giza 475, Alexandria 223 [5].

### SOM = EGP 924k (154 shops)
**Calculation:** 154 shops × EGP 6,000 = EGP 924k (11.6% of SAM)
- **154 shops:** From the same capture plan.

---

## SOM Capture Plan (used by both)

| Year | Sales effort | New shops | Lost (15% churn) | Active shops |
|---|---|---|---|---|
| 1 | 2 founders, Nasr City and New Cairo | 2/month = 24 | — | 24 |
| 2 | + 1 sales rep, add Giza | 4/month = 48 | 4 | 68 |
| 3 | + 2nd sales rep, add Alexandria | 8/month = 96 | 10 | **154** |

- **How each year is calculated:** Active shops = last year's shops − 15% churn + new shops.
- **Why 8 a month is realistic:** 2 sales reps each sign 1 shop per week.

---

## Reconciliation

| | Top-down | Bottom-up | Gap |
|---|---|---|---|
| TAM | EGP 36M | EGP 41.1M | 14% |
| SAM | EGP 8.6M | EGP 8.0M | 7% |
| SOM | EGP 924k | EGP 924k | — |

Two independent starting points, sector money and named shops, land within 7–14% of each other.

---

## Assumptions
1. **Shop counts come from Yellow Pages Egypt.** Yellow Pages is the national business directory [4], used because no official count of barbershops exists. These counts are a minimum: they miss shops that never listed themselves and may include some that have closed.
2. **EGP 12bn is a minimum.** The Chamber said the sector earns "no less than" EGP 12bn, so the real figure could be higher. The hairdressing division also covers women's salons, so part of that money may not come from barbers [1].
3. **3% is a U.S. figure.** No Egyptian data exists on how much barbershops spend on software. Egyptian shops probably spend less, which partly offsets the 12bn being a minimum [2].
4. **10% licensed is for all salons.** The Chamber's 200,000 licensed out of 2 million mixes men's and women's salons. We assume men's barbershops have a similar licensing rate [1].
5. **The Google Maps data is unofficial.** It comes from a private company that collects Google Maps listings, and it doesn't explain exactly how it collected them. So it shows the right order of magnitude but isn't an exact count [5].
6. **EGP 6,000 a year is our own price.** Real willingness to pay still has to be tested with shops [6].
7. **The sales pace and churn are targets.** Signing 2, then 4, then 8 shops a month, and losing 15% of shops each year, are goals rather than proven numbers. They need to be checked during pilot launches.
---


* **"Why Now?":**
  Egypt has a huge, recurring market for men’s grooming, yet barbershops still run on walk-ins, phone calls and WhatsApp, so customers waste time waiting and shops lose income from no-shows and idle chairs. Meanwhile, Egyptians have already adopted booking and paying through their phones for rides, food and doctor visits. Existing booking platforms are generic or foreign and not built for local barbershops, which leaves a clear gap. A simple, barber-focused booking and POS app that brings organized, predictable visits fills this gap in a market where still has no dominant business in this area.

## References
1. Masrawy, "شعبة الكوافير: قطاع الحلاقة يحقق دخلًا سنويًا لا يقل عن 12 مليار جنيه," Aug 18, 2026. [Link](https://www.masrawy.com/news/news_economy/details/2026/8/18/3034825/)
2. BizMetricsHQ, "Barbershop Business Benchmarks: cost structure." [Link](https://www.bizmetricshq.com/industries/beauty/barbershop/)
3. Egypt Today, "Egypt's domestic population reaches 109.5 Million: CAPMAS," Sep 19, 2026. [Link](https://www.egypttoday.com/Article/1/149579/Egypt’s-domestic-population-reaches-109-5-Million-CAPMAS)
4. Yellow Pages Egypt, "حلاق رجالي" (men's barber) category. [Link](https://yellowpages.com.eg/ar/category/%D8%AD%D9%84%D8%A7%D9%82-%D8%B1%D8%AC%D8%A7%D9%84%D9%8A)
5. Rentech SmartScraper, "List of Barber shops in Egypt," data as of Apr 1, 2026. [Link](https://rentechdigital.com/smartscraper/business-report-details/list-of-barber-shops-in-egypt)
6. Codeiks, "برنامج محل حلاقة رجالي في مصر." [Link](https://www.codeiks.com/blog/barber-shop-software-egypt)
7. El Watan News, SAR/EGP exchange rate, Apr 27, 2026. [Link](https://www.elwatannews.com/news/details/8273856)
8. A. Wahsh, "Understand the Market," guest lecture, CSEN1096 Business of Software, GUC, 2026: 02 · Market Size, clinic worked example.
9. CAPMAS, Egyptian Economic Census 2022/2023 (metadata). [Link](https://metadata.capmas.gov.eg/ar/index.php/catalog/1948)
### 5. Market Structure and Competition
*
  ## Competition List by Tier

| Tier | Competitor | What it does | Why this tier |
|---|---|---|---|
| Direct | Ehgezly [1][2][3] | Egyptian app where customers browse shops and book beauty services, including a barber category. Shops get a dashboard for bookings, calendar, team and revenue. | Customers can choose any listed barbershop and book. |
| Direct | Fresha [9][10] | Global salon marketplace and shop software. 28 barbers listed in Egypt. Customers pick a barber and a time slot online. | Customers can choose any listed barbershop and book. |
| Indirect | QR Barbers [15] | Cairo-built barber booking app where each shop gets its own booking service. | Booking for one shop at a time. Customers cannot compare shops. |
| Indirect | Dahem Salon [16] | B2B system with a men's barbershop edition: appointments, waitlist, chair status, commissions, customer records. | The shop gets its own booking link. No cross-shop marketplace. |
| Indirect | Dexef [17] | Accounting, ERP and POS vendor with salon software: scheduling, commissions, customers, POS, inventory. | B2B accounting and POS. No customer platform. |
| Substitute | Walk-in queue [18] | Customer arrives and waits for a turn. | Barber does no online booking. |
| Substitute | Call or WhatsApp [19] | Customer and barber agree a time by message or call, and the barber confirms manually. | Barber does no online booking. |

*
  ## Competition Matrix: Direct Competitors

| | Ehgezly | Fresha |
|---|---|---|
| **Summary** | Egyptian app where customers book beauty and wellness services: barbers, hair and nails, laser, makeup, massage, pet services [1]. The barber category lists 9 shops, all in New Cairo (7 brands; La Casa and Luka each have 2 branches) [2]. Shop owners get a dashboard for bookings, calendar, team and revenue [3]. | London-based global booking marketplace plus shop software [12]. Egypt barber page: 28 barbers and 10 professionals in Cairo, Giza, Ismailia and Damietta, with an average rating of 4.0 from 9,892 reviews [9]. Customers pick a specific barber or any professional and book in 5-minute slots [10]. |
| **Target customers** | Customers: people in Cairo booking beauty services [2]. Shops: barbershops, salons and clinics [3]; its FAQ says any small business [4]. | Customers: people searching for local services [9]. Shops: salons, spas, barbershops, solo barbers and small teams [14]. Direct sales for large multi-branch businesses [12]. |
| **Product or service pricing** | Customers pay the shop's listed price in EGP. Haircuts range from 150 to 290 EGP, and 6 of 9 shops charge 250 [2]. Shop-side fees, commission and subscription are not published [3][8]. Refunds take 5 to 7 business days under the shop's policy [4]. | Customers pay the shop's listed price in EGP. Haircuts range from 80 (Gedo Salon) [9] to 320 (Shad's Men's Salon) [10]. Shops pay (USD list prices) [11]: Independent USD 19.95 a month; Team USD 14.95 per barber a month; online card payments 2.79% + USD 0.20; in-person 2.29% + USD 0.20; a 20% one-time fee (minimum USD 6) on each new customer found through the marketplace. Booking through the shop's own link, Instagram or Facebook is free [11]. Whether Egypt shops are billed in EGP is not stated [11]. |
| **General marketing strategy** | Almost no public marketing so far. Shop-side pitch: "Goodbye WhatsApp chaos", "fill empty hours" with 24/7 booking, "get paid automatically" [3]. Free onboarding in Arabic and English, Cairo phone support (Sat to Thu, 10:00 to 20:00), WhatsApp chat, AI assistant [3][5]. Positions itself as built in Egypt [3]. | Free-to-start pitch, with paid plans added in 2025 [12]. The marketplace brings new customers and Fresha charges a fee on the first booking only [11][12]. Creator posts with working stylists and barbers. Claims shops get 26% more customers and a 392% return (third-party study, not independently checked) [12]. Self-serve sign-up with a 7-day trial for small shops [11][12]. |
| **Online marketing strategy** | Instagram: 11 followers [6]. Facebook: 1 follower, one post, 0 reviews [7]. A blog page exists; posts not read [1]. Website and apps are the main channel [1]. | Heavy Google advertising: about 2,000 Search ads, with automated per-shop ads in several languages [12]. Instagram about 80,000 followers; TikTok and LinkedIn active; no active Meta or TikTok ads [12]. Arabic platform live since 2025 [13]. Middle East push targets the Gulf (Dubai and Saudi teams; Qatar, Oman and Kuwait next), and Egypt is not mentioned [13]. |
| **Strengths** | Egyptian company with local support in Arabic and English [3][5]. Prices in EGP [2]. Online payment at booking and refunds [3][4]. Reminders and reviews [3]. Dashboard for bookings, team and revenue [3]. | Large review base in Egypt: Rashed's Studio 3,205 reviews, Shad's Men's Salon 1,691, Gedo Salon branches 356 to 1,392 [9][10]. Customers choose barber and slot online [10]. Full toolset: waitlist, deposits, POS, memberships, reports [14]. Strong global brand [12]. |
| **Weaknesses** | Few barbers: 9 in one area [2], though its partner form says "thousands of shops" [8]. Not barber-focused: pet clinics and women's salons sit on the same app [2]. Almost no social following [6][7]. Deposit and no-show rules not stated [3][4]. | The 20% fee on new customers plus processing fees add up [11][14]. No Egypt-specific marketing found [13]. Phone support is a paid add-on on the Independent plan [14].  Not barber-specific [9]. |
| **Competitive advantage** | Local: Egyptian team, EGP, Arabic and Cairo-hours support [3][5]. | Already has shops and thousands of reviews in Egypt, plus a complete product [9][10][14]. |
* ## Positioning Map

![Positioning map: barbershop booking in Egypt](positioning-map.png)

## References
- [1] Ehgezly, home page. <https://ehgezly.app/>
- [2] Ehgezly, barber listings. <https://ehgezly.app/service/barber>
- [3] Ehgezly, for salons and clinics. <https://ehgezly.app/for-business>
- [4] Ehgezly, FAQ. <https://ehgezly.app/faq>
- [5] Ehgezly, contact. <https://ehgezly.app/contact>
- [6] Ehgezly, Instagram (@bookwithehgezly). <https://www.instagram.com/bookwithehgezly/>
- [7] Ehgezly, Facebook page. <https://www.facebook.com/share/184zUxhmEW/?mibextid=wwXIfr>
- [8] Ehgezly, list your business form. <https://ehgezly.app/ListUrBussiness>
- [9] Fresha, Egypt barber page. <https://www.fresha.com/lp/en/bt/barbers/in/egypt>
- [10] Fresha, Shad's Men's Salon page and booking flow. <https://www.fresha.com/a/shads-mens-salon-cairo-governorate-shads-mens-salon-el-montaza-el-fath-fsxsilpl>
- [11] Fresha, pricing. <https://www.fresha.com/pricing>
- [12] Milk and Cookies, "Marketing Spotlight: Mapping Fresha's Marketing and Sales Tactics" (third-party study). <https://milkandcookies.studio/market-intelligence/marketing-spotlight-fresha-marketing-sales-tactics/>
- [13] Fresha, "Fresha continues to expand across the GCC", 1 July 2025. <https://www.fresha.com/blog/expanding-in-the-GCC>
- [14] Pabau, Fresha review (written by a competitor). <https://pabau.com/blog/fresha-review/>
- [15] QR Barbers, Google Play listing. <https://play.google.com/store/apps/details?id=com.qrbarbers.app&hl=en_US>
- [16] Dahem, salon system. <https://dahem.cloud/salon>
- [17] Dexef, beauty center management software. <https://dexef.com/apps/beauty-center-management-software>
- [18] Codeiks, barber shop software page (vendor description, not independent data). <https://www.codeiks.com/blog/barber-shop-software-egypt>
- [19] The Barber, New Cairo, online booking page. <https://thebarber-eg.com/en/blog/online-booking-grooming-lounges-egypt>
### 6. Differentiation and Moat
*## Differentiators

Current options fall into three groups: general beauty platforms (Fresha, Ehgezly), single-shop booking tools (Dahem Salon, QR Barbers, Dexef), and the status quo (walk-ins, calls and WhatsApp). None of them combines the four points below.

### 1. A marketplace for barbershops only
Every listing is a men's barbershop. Fresha and Ehgezly list barbers next to salons, spas and other categories, and single-shop tools only show one shop. Here, customers looking for a barber compare barbershops only, and a shop is seen by people who are looking for exactly what it offers.Since it is focusing on barbershops only it can bring more barbershops than general beauty platforms ,which will increase the network of barbershops acquired and cause a network effect non replaceable.

### 2. Ratings for each barber, not just each shop
Customers rate both the shop and the barber who cut their hair. In a barbershop, people choose the barber, so a skilled barber builds his own reputation and attracts customers by name. On general platforms, reviews sit on the business profile, and single-shop tools have no public reviews. Shops with good barbers will be exposed and rewarded on a larger scale than just word of mouth.

### 3. Barber profiles that move with the barber
In Egypt, barbers often move between shops, and loyal customers follow the barber, not the shop. Each barber has his own profile with his ratings, photos of his work and his customers. If he moves to another shop on the platform, his reputation moves with him and his customers can find him. General platforms tie everything to the business, and single-shop tools lose the barber's history when he leaves.

**Why it matters for barbershops:**
- **Scouting proven talent.** A shop owner can find skilled barbers on the platform by their real ratings and work, instead of hiring on word of mouth.
- **Hiring brings customers.** A barber who joins a shop brings his reputation and his loyal customers with him, so the shop gains revenue from day one.
- **Lower hiring risk.** The owner sees a barber's track record before hiring him, not after.

### Why this is hard to copy as a whole
Since there is no platform for barbers only, this can be something completely new for barbershops and customers. It helps them with online booking, which is the basic feature we provide to facilitate daily operations and reduce lost profits from clients who leave because of traffic. In addition, the platform offers monetization and exposure to barbershops, helps with talent acquisition, and rewards shops that have high-quality barbers, helping in marketing and human resources operations for barbershops. This combination is not offered anywhere in Egypt which is exactly why our product standout.
* ## Moat

### 1. Switching costs

Once a barbershop runs on the platform, leaving means losing what it has built:

- **Its reputation.** The ratings and reviews of the shop and each of its barbers stay on the platform. On a competitor's app, the shop starts again from zero next to shops with hundreds of reviews.
- **Its booking customers.** The shop would have to convince every regular who books online to download a new app and book there instead. Many won't, and some will book another shop that is still on the platform.
- **Its history.** Months of data on revenue, barber performance and customer visits stay behind, so the owner loses the record he uses to manage his team.

**Why it protects us:** a competitor would have to offer a shop enough to make up for losing its reputation, its booking customers and its history, which is very hard to do.

### 2. Network effects

The platform gathers both sides of the market in one place: many barbershops (supply) and a large customer base (demand).

- **Each side keeps the other.** Customers come because the shops are here, and shops stay because the customers are here.
- **It becomes the standard.** The more shops and customers join, the more the platform becomes the default place to find and book a barber, so even more people join.
- **Reviews build up with use.** Every visit adds ratings that a new platform cannot copy or buy.

**Why it cannot be copied:** a competitor can copy the features, but not the network. A new platform starts with no shops, no customers and no reviews, and has to compete with a platform that already has supply and demand. No shop wants to move first and lose its customers, and no customer wants to move first and find few shops. Gathering both sides from scratch takes years and a large budget.

### 7. Product-Market Fit (PMF) Plan

Following the three-part framework from market analysis (Survey predicts, Process improves, Behaviour proves):

* **PMF Verification Method:**
  * **1. Survey (Predicts) — The Sean Ellis Test:**
    * Survey active users after 30 days (clients who checked queue $\ge 2$ times; shop owners/cashiers running the queue screen daily):
      > *"How would you feel if you could no longer use this platform tomorrow?"*  
      > *(A) Very disappointed &nbsp;&nbsp;|&nbsp;&nbsp; (B) Somewhat disappointed &nbsp;&nbsp;|&nbsp;&nbsp; (C) Not disappointed*
  * **2. Process (Improves) — The Superhuman PMF Engine (Rahul Vohra):**
    * **Segment:** Profile users who answer "Very disappointed" to isolate our core ICP (loyal clients who visit a specific barber every 2–4 weeks; multi-chair shops with 3–8 chairs).
    * **Analyze:** Identify what fans love (e.g., real-time barber queue visibility, zero walk-outs) vs. what holds back the "somewhat disappointed" group.
    * **50/50 Roadmap:** Allocate 50% of development to doubling down on what fans love and 50% to resolving core friction for "somewhat disappointed" users.
    * **Repeat:** Re-survey cohorts monthly to track score progression.
  * **3. Behaviour (Proves) — Flattening Retention Curves:**
    * Measure cohort retention over time to confirm a loyal core stays without push notifications:
      * **Client Cohorts:** 30, 60, and 90-day repeat queue check-in rates (tracking the natural 2–4 week haircut cycle).
      * **Shop B2B Cohorts:** Monthly active shop usage and subscription renewals.
  * **4. Pull Signals:**
    * Measure organic word-of-mouth (clients sharing live queue links with friends) and inbound requests from neighboring barbershops.

* **Target Thresholds:**
  * **Sean Ellis Score:** $\ge 40\%$ "Very disappointed" among surveyed active clients; $\ge 50\%$ among shop owners/cashiers.
  * **Client Cohort Retention:** 60-day cohort curve flattens at $\ge 35–40\%$ repeat active users.
  * **Shop B2B Retention:** Monthly shop churn $< 1.3\%$ (maintaining our SOM assumption of $< 15\%$ annual churn).
  * **Workflow Stickiness:** $\ge 85\%$ of all daily cuts logged digitally on the screen rather than paper ledgers.
  * **Operational Pull:** $\ge 60\%$ of queue views occur during peak hours (6:00 PM – 11:00 PM) before in-person arrival. 

### 8. Product Strategy and MVP
* **MVP Scope:** (Designed to test the riskiest assumption)
* **Feature Prioritization (Top 15–20 Features):**
  * **MoSCoW Classification:** (Must-haves, Should-haves, Could-haves, Won’t-haves)
  * **Kano Classification:** (Basics, one-dimensionals, delighters, indifferent)
* **Roadmap (Now / Next / Later for 6–12 Months):** 

### 9. Company Type and Founding Structure

* **Company Type Justification:** (Venture-scale vs. SME/lifestyle)
  * **Company Type:** Venture-scale startup.
  * We are a venture-scale startup. Three founders split equity 35 / 30 / 25 by role, with 10% reserved for future employees. All shares vest over 4 years with a 1-year cliff, and all IP belongs to the company.
  * **Why venture-scale, not an SME or lifestyle business:**
    * **Software scales cheaply:** Adding a new barbershop costs almost nothing; there is no new staff or location per customer.
    * **Revenue that grows with every haircut:** We earn a commission on each haircut served through the platform, so revenue grows with every shop we add and every customer each shop serves. Shops pay nothing upfront and only pay when they earn.
    * **A large, expandable market:** We start with Cairo barbershops, then move to salons and grooming businesses across MENA (see [Section 1: Vision and Mission](#1-vision-and-mission)).
    * **A data advantage:** Every shop adds data on walk-outs, wait times and barber demand that no shop records today. That data improves wait estimates and is hard for a competitor to copy.
    * **The honest counter-argument:** The commission on a single haircut is small, and shops pay for no software today. Venture scale therefore depends on high volume: many shops, each serving many haircuts through the platform, rather than a few shops paying a high price. Shops may also resist a fee on every cut, or log cuts outside the platform to avoid it. If volume stays low, this would become an SME, and we will test that before raising money.
    * **Revenue math (to complete):** A commission of [__] EGP per haircut × [__] haircuts per shop per month × [__] shops = [__] EGP per month. (Commission rate to be confirmed.)

* **Founding Roles:** (Including Product Owner)
  | Founder | Role | Owns |
  | :--- | :--- | :--- |
  | **Nooreldeen** | CEO / Product owner | Vision, product decisions and the MVP scope, customer discovery, fundraising. Owns product. |
  | **Abdelrahman** | CTO | The customer app, the shop screen and the barber app; technical architecture; data |
  | **Ahmed** | COO | Shop partnerships, onboarding barbershops, operations and support, the next rounds of interviews |

  * **Product Owner Designation:** Nooreldeen owns product because Nooreldeen ran the customer discovery and turned it into product decisions: the move from booking to a live per-barber wait, and the narrower ICP of loyal customers.

* **Founder–Market Fit:**
  We are three GUC students building a software company, and our roles cover the three things it must do well: understand barbershops, build the product, and win shops. Nooreldeen (CEO) has already done the field work: he ran all six discovery interviews across two barbershops, on both the shop and customer side, and turned them into the product's direction. Abdelrahman (CTO) led this milestone's technical deliverables and will build the customer app, the shop screen and the barber app. Ahmed (COO) led this milestone's operations deliverables and will run shop partnerships, onboarding and support. Our gap: we are full-time students, so our time is limited, especially during exams, and none of us knows yet how to register a company in Egypt or collect a commission from shops legally. We close the first by keeping the pilot small (2–3 shops) and planning the heavy work around the semester, and the second by getting advice from a lawyer and from GUC’s startup support before we register, and by using a licensed local payment provider to collect the commission.

* **Equity Split & Vesting Schedule:** (e.g., 4 years with 1-year cliff)
  * The split is weighted by role, based on responsibility, how hard each role is to replace, and early work done.

  | Holder | Shares | Ownership | Vesting |
  | :--- | :---: | :---: | :--- |
  | **Nooreldeen (CEO / Product owner)** | 3,500,000 | 35% | 4 years, 1-year cliff |
  | **Abdelrahman (CTO)** | 3,000,000 | 30% | 4 years, 1-year cliff |
  | **Ahmed (COO)** | 2,500,000 | 25% | 4 years, 1-year cliff |
  | **Employee option pool** | 1,000,000 | 10% | Set per hire |
  | **Total** | **10,000,000** | **100%** | |

  * **Role Weighting Rationale:**
    * **CEO (35%):** Makes the final product and company decisions, and leads fundraising.
    * **CTO (30%):** Builds the core product; the hardest role to replace.
    * **COO (25%):** Brings in and keeps the shops.
    * **Option pool (10%):** Set aside to hire early employees, at the low end of the usual 10–20% range.
  * **Vesting Schedule:** 4 years, 1-year cliff, monthly after that. No founder owns any shares until 12 months after the company starts. At the cliff, 25% vest at once; the rest vest in equal monthly amounts over the next 36 months.
  * **Founder Departure:** If a founder leaves, they keep only what has vested. Unvested shares return to the company, so the remaining founders are not carrying someone who left.
  * **Current Status:** Today: 0% vested, because the cliff has not been reached.
  * *(See [Appendix B: Cap Table & Founders' Agreement](#appendix-b-cap-table--founders-agreement) for detailed monthly vesting calculations, pre-seed dilution modeling, and cap table template references).*

* **IP Assignment:**
  Every founder signs an IP assignment agreement that transfers to the company everything they create for it:
  * The app code, the shop screen and the barber app
  * Designs, the brand name and the logo
  * The customer-discovery data: interview notes, the interview log and findings
  * Any work done before the company is incorporated

  This means no founder can leave and take the product with them, and investors can see that the company owns what it sells.

---

## Deliverable 1.2: Business Model Canvas and Pricing Hypothesis

*(The one-page canvas is in `Business Model Canvas and Pricing Hypothesis.docx`. Every block is based on our 6 discovery interviews.)*

### 1. Business Model Canvas (9 Blocks)
* **Key Partners:** Pilot barbershops in New Cairo and Nasr City (first shops, free trial); barbers with a social following, who share their live queue link; a local payment provider (cards and wallets) to collect the commission and booking deposits; cloud hosting and SMS / push notification providers; a tablet supplier for the in-shop queue screen.
* **Key Activities:** Build and run the customer app, shop screen and barber app; sign and onboard shops in person and train the front desk; keep per-barber wait estimates accurate; keep interviewing shops and customers and run pilots.
* **Key Resources:** The platform (live queue, service log, alerts); live data on walk-outs, waits and barber demand that no shop records today; the network of shops, barbers and their ratings; the founding team (product, tech, operations).
* **Value Propositions:**
  * *For shops:* win back walk-outs (about 10,800 EGP a month at 3 lost cuts a day, our estimate); fewer "is he free?" calls (5–10 a day at the front desk); an automatic service log per barber replaces the paper notebook; keeps first come, first served, so walk-ins stay treated fairly; nothing to pay upfront, pay only per haircut.
  * *For customers:* see the live wait for your own barber and arrive just in time; a "your barber's queue is short" alert.
  * *For barbers:* an open / close queue control and fewer calls during cuts.
* **Customer Relationships:** In-person onboarding and support for every shop (COO); a free first month for pilot shops; a WhatsApp support line for shop staff; a self-service app for customers.
* **Channels:** Direct visits to shops by the founders, later sales reps; a queue screen and QR code at the shop entrance; barbers' Instagram, TikTok and WhatsApp, with a link to their live queue; the customer app and web page.
* **Customer Segments:**
  * *Paying customer:* owners of multi-chair barbershops (3–8 chairs, 100–250 EGP per cut) in Greater Cairo that work first come, first served and log on paper.
  * *Users:* men aged 18–35 loyal to one specific barber, and high-intent clients who found a barber on social media.
  * *Not targeted:* customers with no preferred barber (they barely wait).
* **Cost Structure:** Product development (founders' time now, engineers later); cloud hosting, SMS and push notifications; queue-screen tablets for shops; field sales and onboarding (sales reps from Year 2); payment processing fees on collected commission; marketing with barbers on social media.
* **Revenue Streams:** A commission on each haircut served through the platform: **[__] EGP per haircut** (rate to be confirmed). No subscription and no setup fee; customers use the app for free. Revenue grows with shops × haircuts per shop.

### 2. Pricing Hypothesis
We charge shops a commission on each haircut served through the platform. Shops pay nothing upfront, customers use the app for free, and the initial price is [__] EGP per haircut, to be confirmed by the team and tested in Milestone 2.

* **Monetization Model:** Marketplace take rate / usage-based: a fee per haircut served through the platform, not a monthly subscription. The barbershop pays; customers and barbers do not. No setup fee and no subscription, so a shop's bill rises and falls with the haircuts it actually serves.
* **Initial Price Point:** **[__] EGP per haircut** (or [__]% of the haircut price). At Shop 1's price of 120 EGP, that is [__]% of each cut.
* **Pricing Logic:**
  * *Fits a customer who pays for no software today.* The owner we interviewed pays for no software and runs everything on paper. A per-haircut fee removes the upfront cost that would stop him from trying.
  * *Value-based.* Losing 3 haircut customers a day at 120 EGP costs a shop about 10,800 EGP a month (our estimate). The commission must stay a small share of the value we recover: if the platform wins back even one walk-out a day (about 3,600 EGP a month), the shop should keep most of that gain.
  * *Anchoring against competitors.* Fresha charges a 20% one-time fee on each new customer it brings through its marketplace, plus card fees of 2.79% + USD 0.20. Ehgezly does not publish its shop fees (see [Section 5](#5-market-structure-and-competition)). Our per-haircut fee is set to look small next to Fresha's 20%.
  * *Willingness to pay from interviews.* The owner said, *"Of course I'd even pay for a service like that,"* and was open to a free trial. This is stated, not committed, so we treat it as a signal to test, not as proof.
* **Risks and How We Test Them:**
  * *Leakage:* shops may serve haircuts without logging them, to avoid the fee.
  * *Resistance to a fee on every cut:* owners may prefer a fixed monthly price.
  * *Milestone 2 test:* offer pilot shops the commission after the free month and record how many accept, at what rate, and how many cuts they log.

---

## Deliverable 1.3: Riskiest Assumptions
*(Top 5 assumptions that would kill the company if wrong, ranked by risk, each with the cheapest test. Note which will be tested in Milestone 2.)*

1. **Assumption 1:** 
   * **Risk Rank:** 1
   * **Cheapest Test:** 
2. **Assumption 2:** 
   * **Risk Rank:** 2
   * **Cheapest Test:** 
3. **Assumption 3:** 
   * **Risk Rank:** 3
   * **Cheapest Test:** 
4. **Assumption 4:** 
   * **Risk Rank:** 4
   * **Cheapest Test:** 
5. **Assumption 5:** 
   * **Risk Rank:** 5
   * **Cheapest Test:** 

* **Selected Validation Experiment for Milestone 2:** 

---

## Deliverable 1.4: Investor One-Pager
* **Problem:** 
* **Solution:** 
* **Customer:** 
* **Market:** 
* **Business Model:** 
* **Evidence So Far:** 
* **Team:** 

---

## Appendices

### Appendix A: Full Customer Discovery Interview Log

All interviews were conducted on **October 31, 2026** by Nooreldeen (CEO). Names, shop names, and phone numbers are withheld for privacy. Contact details for interviewees who agreed to verification are held privately by the interviewer.

| # | Date | Role / Segment | Interviewer | Key Past Behaviour | Numbers | Key Quote (Translated) | Surprise |
|---|---|---|---|---|---|---|---|
| **1** | 31 Oct 2026 | Barber, Shop 1 (has front desk) | Nooreldeen (CEO) | First come, first served, with a separate wait for specific barbers. Front desk logs every service per barber. Regulars call or message barbers directly. Answers phone during cuts. | Walk-outs daily. Popular barbers have 2–4 waiting while others are free. | Regulars wait for their barber *"while the rest of the barbers are free"* | Demand bunches on 1–2 barbers. Shop has never used a booking app. |
| **2** | 31 Oct 2026 | Front-desk receptionist, Shop 1 | Nooreldeen (CEO) | Strict first come, first served. Customer queue plus a barber rotation. Logs every service on paper. Regulars call barbers directly. | 5–10 calls per busy day asking whether a specific barber is free. | *"If someone called me and came later, I don't know if it's who called me"* | Reservations are against shop policy and were never tried. |
| **3** | 31 Oct 2026 | Owner, Shop 1 | Nooreldeen (CEO) | No reservations, for fairness. Pays for no software. All calculations done by the front desk on paper. | Haircut 120 EGP, beard 70 EGP, both 170 EGP. Walk-outs *"always"*, uncounted. | *"Of course I'd even pay for a service like that"* | Does not measure his own losses. Open to a free trial (stated, not committed). |
| **4** | 31 Oct 2026 | Barber, Shop 2 (no front desk) | Nooreldeen (CEO) | Barbers manage the order. Another barber takes payment and logs the service (policy). No reservations (policy). Leavers ask when he'll be free and return then. | About 5 calls or messages a day to him. Walk-outs *"a lot"*. | *"Just now I was giving someone a haircut and another was waiting for me while the whole shop was free"* | Decides whether to take another customer based on his remaining physical energy. |
| **5** | 31 Oct 2026 | Customer, 18–35, loyal to one barber (family member) | Nooreldeen (CEO) | Went in the morning guessing his barber would be free. Sometimes calls ahead, sometimes not, though he has the number. Books padel and football courts by app. | Waited about 30 minutes 2 days earlier. Walked out about a month ago with 2 ahead; returned the next day. | *"I went thinking he'd be free"* | Has the barber's phone number but doesn't reliably call ahead. |
| **6** | 31 Oct 2026 | Customer, 30, working professional, no preferred barber | Nooreldeen (CEO) | Went after work last week (his only free time) before a conference the next day. Didn't call. Takes whoever is free. Books padel courts and doctor appointments by app. | Waited 0 minutes. | *"I don't have a specific barber, whoever's free"* | Had a preferred barber when younger and stopped caring. Says he'd find another barber rather than wait (hypothetical). |

### Appendix B: Cap Table & Founders' Agreement

#### 1. Cap Table & Model Documentation
The filled cap table is in `Cap Table - Founding Structure.xlsx`, built on the course template. It has the Cap Table, Founders and vesting, Funding Rounds (none raised yet), a hypothetical 10% pre-seed dilution scenario, and a Summary. Reference: [Cap table template, The Startup Project](https://startupproject.org/templates/cap-table/).

| Holder | Shares | Ownership | Vesting Schedule | Role Rationale |
| :--- | :---: | :---: | :--- | :--- |
| **Nooreldeen (CEO / Product owner)** | 3,500,000 | 35% | 4 years, 1-year cliff | Makes the final product and company decisions, and leads fundraising. |
| **Abdelrahman (CTO)** | 3,000,000 | 30% | 4 years, 1-year cliff | Builds the core product; the hardest role to replace. |
| **Ahmed (COO)** | 2,500,000 | 25% | 4 years, 1-year cliff | Brings in and keeps the shops. |
| **Employee option pool** | 1,000,000 | 10% | Set per hire | Set aside to hire early employees, at the low end of the usual 10–20% range. |
| **Total** | **10,000,000** | **100%** | | |

#### 2. Dilution Scenario (Hypothetical Pre-Seed Round)
No investors yet. If we later sell 10% in a pre-seed round, every holder is diluted by the same proportion, and founders go from 90% to 81% together (Dilution Scenarios sheet).

#### 3. Detailed Vesting Mechanics & Example
* **Terms:** 4 years, 1-year cliff, monthly after that. No founder owns any shares until 12 months after the company starts. At the cliff, 25% vest at once; the rest vest in equal monthly amounts over the next 36 months.
* **Example:** Nooreldeen holds 3,500,000 shares. At 12 months, 875,000 vest. After that, about 72,917 vest each month until all 3,500,000 have vested at 48 months.
* **Departure Provision:** If a founder leaves, they keep only what has vested. Unvested shares return to the company, so the remaining founders are not carrying someone who left.
* **Current Status:** Today: 0% vested, because the cliff has not been reached.

#### 4. IP Assignment Terms
Every founder signs an IP assignment agreement that transfers to the company everything they create for it:
* The app code, the shop screen and the barber app
* Designs, the brand name and the logo
* The customer-discovery data: interview notes, the interview log and findings
* Any work done before the company is incorporated

This means no founder can leave and take the product with them, and investors can see that the company owns what it sells.

### Appendix C: Generative AI Disclosure
*(Tools used and for what purpose)*

### Appendix D: Market Sizing Sources & Citations

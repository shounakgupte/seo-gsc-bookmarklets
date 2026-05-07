# 🔍 SEO Google Search Console Bookmarklets

Elevate your organic search analysis with these **SEO Google Search Console Bookmarklets**. Instantly filter your GSC Performance reports by search intent, word count, and advanced regex patterns with a single click—no more manual copying and pasting of complex regex.

## 🚀 Why Use SEO Google Search Console Bookmarklets?

Google Search Console (GSC) is powerful, but manually entering regex filters for search intent every time you perform an audit is tedious. This tool provides a curated collection of 15+ "Drag & Drop" bookmarklets designed specifically for SEO professionals to:

*   🎯 **Analyze Search Intent:** Categorize queries into Commercial, Informational, Transactional, and Navigational.
*   📏 **Find Long-Tail Opportunities:** Instantly filter for queries with 5+ or even 10+ words.
*   ❓ **Extract Question Queries:** Identify "How-to" and "What is" queries for content gap analysis.
*   🏢 **Filter Branded vs. Non-Branded:** Quickly isolate your brand traffic to see pure organic performance.
*   🛠️ **Troubleshoot Issues:** Find "not working" or "error" queries to improve user experience.

---

## 🛠️ Features

*   **15+ Built-in Regex Patterns:** Optimized for GSC's RE2 regex engine.
*   **Drag & Drop Installation:** Simple browser-based setup.
*   **Master Prompt Tool:** A flexible bookmarklet that prompts you for *any* custom regex on the fly.
*   **Offline Support:** Includes a downloadable "Clean HTML" version for your own local toolkit.
*   **Mobile Friendly:** Manual "Copy Code" fallbacks for mobile browsers.

---

## 🖱️ Installation

1.  Open the [GSC SEO Regex Bookmarklets Tool](seo-bookmarklets.html) in your browser.
2.  Ensure your **Bookmarks Bar** is visible (`Ctrl+Shift+B` or `Cmd+Shift+B`).
3.  **Drag** any purple bookmarklet button directly onto your bookmarks bar.
4.  Navigate to your **Google Search Console Performance Report**.
5.  **Click** the bookmarklet to apply the filter!

---

## 🧪 Included Patterns

| Filter Type | Description |
| :--- | :--- |
| **Commercial Intent** | Catch "best", "review", "vs", "price" |
| **Transactional** | High intent: "buy", "order", "signup" |
| **Informational** | Guide-seeking: "how to", "tutorial", "tips" |
| **Long-Tail** | Specific queries with 5+ or 10+ words |
| **Local Intent** | "Near me", "nearby", and city-specific terms |
| **Branded Exclude** | See only non-branded organic discovery |

---

## 🧪 Deep Dive: Understanding the Filters (Newbie Friendly)

Here is a breakdown of all the regex filters included in this project, why they are useful, and how they work.

### 1️⃣ Commercial Intent
**Regex:** `\b(buy|price|cost|cheap|deal|discount|sale|best|top|review|vs|comparison)\b`  
**Use Case:** These are "investigation" queries. Users are likely looking to spend money but are still researching the best option. Filtering for these helps you identify pages that should be optimized for conversions.

### 2️⃣ Comparison & Alternatives
**Regex:** `\b(vs|versus|alternative|or|better|difference|compared)\b`  
**Use Case:** Useful for finding "Product A vs Product B" queries. This is a goldmine for creating comparison pages or "Top 10 Alternatives" content to capture users who are deciding between you and a competitor.

### 3️⃣ Troubleshooting & Pain Points
**Regex:** `\b(how to fix|problem|issue|error|not working|failed|broken|slow|help|support)\b`  
**Use Case:** Find out where your users are struggling. If people are searching for "how to fix [your product]", you can create help desk articles or FAQ sections to improve user satisfaction and reduce support tickets.

### 4️⃣ Question Queries
**Regex:** `^(who|what|where|why|how|can|is)`  
**Use Case:** These queries usually trigger "People Also Ask" (PAA) boxes. Identifying these allows you to structure your content with H2/H3 headers that directly answer these questions, increasing your chances of winning a featured snippet.

### 5️⃣ Long-Tail (5+ Words)
**Regex:** `^(\S+\s+){5,}\S+$`  
**Use Case:** Long-tail keywords are often easier to rank for because they are very specific. If you see high impressions but low clicks for these, it's a sign you need to make your page content more specific to the user's detailed query.

### 6️⃣ Branded Queries
**Regex:** `\b(yourbrand|your-brand|your_brand)\b`  
**Use Case:** Use this to see how people find you when they already know your name. (Note: You'll need to edit the bookmarklet with your actual brand name).

### 7️⃣ Non-Branded (Exclude Brand)
**Regex:** `^(?!.*(yourbrand|your-brand)).+$`  
**Use Case:** This is the "True SEO" filter. It shows you how users discover your site without searching for your brand name. This is the best way to measure the success of your top-of-funnel content marketing.

### 8️⃣ Local Intent
**Regex:** `\b(near me|nearby|in [a-z]+|local|[a-z]+\s+(australia|uk|usa|canada))\b`  
**Use Case:** Essential for local businesses. This finds users looking for services in specific locations or "near them," helping you optimize your Local SEO strategy and Google Business Profile.

### 9️⃣ Transactional Intent
**Regex:** `\b(buy now|order|purchase|checkout|add to cart|sign up|subscribe|get started|free trial)\b`  
**Use Case:** These users are ready to pull the trigger. They aren't researching; they want to buy or sign up *now*. Monitoring these queries helps you ensure your "Buy" buttons and landing pages are working perfectly.

### 🔟 Informational Intent
**Regex:** `\b(guide|tutorial|how to|what is|learn|tips|steps|example|ideas|list|vs|vs\.)\b`  
**Use Case:** Great for content ideation. These users want to learn something. Use this to find topics for new blog posts or educational resources.

### 1️⃣1️⃣ Short Queries (1-2 Words)
**Regex:** `^\S+(\s+\S+){0,1}$`  
**Use Case:** These are "Head Terms." They have massive volume but are very competitive. Use this to see if you are ranking for major industry keywords.

### 1️⃣2️⃣ Very Long Queries (10+ Words)
**Regex:** `^(\S+\s+){10,}\S+$`  
**Use Case:** These are ultra-specific searches, often from voice search or people pasting entire error messages. They represent very specific user needs that you can address with hyper-targeted content.

### 1️⃣3️⃣ Expanded Questions (Voice Search)
**Regex:** `(?i)^(who|what|where|when|why|how|can|could|should|would|is|are|does|do|did|will)\b`  
**Use Case:** A more comprehensive version of the Questions filter. It includes words like "could" and "should," which are common in voice searches (Siri/Alexa/Google Assistant).

### 1️⃣4️⃣ Competitor Comparisons
**Regex:** `\b(vs|versus|vs\.|compared to|alternative to|instead of)\s+(competitor1|competitor2)\b`  
**Use Case:** Directly see queries where you are being compared to specific competitors. (Note: You'll need to customize the competitor names in the regex).

### 1️⃣5️⃣ Price-Sensitive Queries
**Regex:** `\b(cheap|affordable|budget|low cost|discount|deal|coupon|promo|free|pricing|cost of)\b`  
**Use Case:** Target the bargain hunters. If you have a "Pricing" page or run sales, this filter shows you if users are finding those pages when looking for deals.

---

## ⚙️ Technical Details

These bookmarklets use the `URLSearchParams` API to manipulate the GSC URL directly. They target the `query` parameter with a regex prefix (`~` for match, `!~` for exclude).

**Regex Engine:** Google Search Console uses the [RE2 syntax](https://github.com/google/re2/wiki/Syntax).

## 📄 License & Attribution

This project is licensed under the MIT License.

Created by **Shounak Gupte** • [hello@shounakgupte.com](mailto:hello@shounakgupte.com)

---
*Keywords: SEO Google Search Console Bookmarklets, GSC Regex Filters, Search Intent Regex, SEO Automation Tools, Google Search Console Performance.*


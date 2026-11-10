# Awesome-Business-Card-Scanning-OCR

## Top Business Card Scanning & OCR Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Contact Digitization, OCR Extraction & CRM-Ready Lead Capture*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Card Scanning & OCR**. These tools help professionals and sales teams convert physical business cards into structured digital contacts—covering mobile scanning apps, AI-powered field mapping, CRM synchronization, and self-hosted OCR pipelines.

**Examples** include Zoho Card Scanner, CamCard, ABBYY Business Card Reader, ScanBizCards, HubSpot Business Card Scanner, Haystack, Covve, Sansan, Popl, and Evernote Scannable (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted business card OCR, LLM-assisted extraction, and privacy-first contact scanning—ideal for developers, privacy-conscious users, and teams seeking transparent alternatives to proprietary scanning apps.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global business card scanning & OCR market is estimated at ~$3.9B (projected to reach ~$19.9B by the mid-2030s at ~17–20% CAGR), while the pure-play digital business card market represents an adjacent ~$240M–$440M sector. The industry is **moderately fragmented**: while foundational CRM giants (HubSpot, Zoho) and established regional platforms (Sansan in Japan, INTSIG/CamCard in Asia-Pacific) capture heavy enterprise market share, the broader market remains fragmented across agile mobile-first startups, NFC hardware vendors, and self-hosted open-source OCR pipelines catering to distinct privacy, trade-show, and CRM integration niches.

## SaaS/Hosted Platforms

| Product | Description | Starting Pricing | Free Tier / Trial Limits | Company Scale (Revenue / Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[HubSpot Business Card Scanner](https://www.hubspot.com/)** | Free AI card scanner inside the HubSpot mobile CRM app mapping card text directly into CRM contacts. | Free (Scanner feature); CRM Starter starts at $15/user/month | Free forever: Unlimited card scans; capped by free CRM limits (up to 2 free users, 1M contacts) | ~$21.0B market cap (NYSE: HUBS) / ~$2.2B annual revenue |
| **[Evernote Scannable](https://evernote.com/)** | iOS scanning app for capturing receipts and business cards directly into Evernote notebooks. | App is free; Evernote Personal starts at $14.99/month ($129.99/year) | Free forever: Unlimited scans, but Evernote free storage caps at 50 total notes, 1 notebook, 1 device | ~$18.4B–$25.0B parent valuation (Bending Spoons) / ~$1.3B parent revenue |
| **[CamCard](https://www.camcard.com/)** | Enterprise & individual AI business card scanner with OCR recognition, CRM auto-sync, and QR exchange. | CamCard Premium starts at $8.50/month ($46.99/year) | Free forever: Capped at 100 lifetime scans and max 20 cards stored in active digital cardholder | ~$2.8B market cap (INTSIG, SSE: 688615) / ~CN¥1.8B (~$250M) revenue |
| **[Sansan](https://jp.sansan.com/)** | Enterprise corporate card management platform combining AI OCR with human-verified data correction. | Custom enterprise quote; consumer tier Eight starts at ¥600/month (~$4/month) | Eight app has free forever plan (scan & basic exchange); Sansan enterprise requires sales consultation/demo (no self-serve free trial) | ~$1.6B market cap (TSE: 4443) / ~¥43.2B (~$285M) annual revenue |
| **[Zoho Card Scanner](https://www.zoho.com/crm/mobile/card-scanner.html)** | Mobile OCR card scanner supporting 10+ languages with direct export to Zoho CRM, Google Contacts, and Salesforce. | Standalone scanner app is free; Zoho CRM Standard starts at $14/user/month (annual) | Free forever: Standalone card scanning is free; Zoho CRM Free Edition caps at 3 users, 5,000 records, 1 GB storage | ~$1.4B+ annual revenue (Zoho Corporation, bootstrapped/profitable) |
| **[ABBYY Business Card Reader](https://pdf.abbyy.com/products/mobile/business-card-reader/)** | High-precision mobile OCR card reader supporting 25 languages, smart cropping, and multi-format exports. | BCR Premium starts at $7.99/month ($29.99/year or $59.99 lifetime) | 7-day free trial on monthly subscription; Free tier strictly limited to 10 total card recognitions lifetime | ~$45M+ ARR (Marlin Equity Partners private equity portfolio) |
| **[Popl](https://popl.co/)** | Digital business card & NFC networking ecosystem with AI business card and event badge OCR scanning. | Popl Pro starts at $7.99/month ($6.49/month billed annually) | Free forever: Digital profile creation & sharing; OCR card scanner allows viewing first 5 scanned leads before paywall | ~$12M–$34M estimated annual revenue / YC-backed (~$2.5M funding) |
| **[ScanBizCards](https://www.scanbizcards.com/)** | Badge and card scanner with OCR and optional human verification fallback for complex layouts. | Sales Ninja plan starts at $100/user/year ($8.33/user/month); Enterprise at $100/user/year | 14-day free trial for Enterprise; Lite/Trail-Blazer free tier allows basic card scans without automated CRM export or team sync | ~$5M estimated revenue / Acquired by CircleBack / Evernote ecosystem |
| **[Haystack](https://thehaystackapp.com/)** | Digital business card and paper card scanner with unlimited mobile AI OCR extraction. | Haystack Pro starts at $7.95/user/month ($4.50/user/month billed annually) | Free forever: Unlimited digital cards, unlimited shares, and unlimited AI card scans on individual tier (exports & CRM locked) | Seed stage (~$1.7M total venture funding, ~$2M–$3M estimated revenue) |
| **[Covve](https://covve.com/)** | AI business card scanner and relationship assistant with 60+ language OCR and offline capture. | Covve Essential starts at $12/month ($119/year); Pro at $20/month ($199/year) | 14-day free trial on annual Pro/Essential plans; Free forever tier capped at 20 active relationship contacts | Seed/Growth stage (~$5M total funding, ~$1.6M estimated annual revenue) |

## Open-Source GitHub Projects

Curated list of open-source business card scanning repositories, native mobile OCR applications, and developer toolkits—sorted by GitHub stars:

- **[Business Card Reader (BCR)](https://github.com/adityamehra/Business-Card-Reader-BCR-)** [![GitHub stars](https://img.shields.io/github/stars/adityamehra/Business-Card-Reader-BCR-?style=social&color=white)](https://github.com/adityamehra/Business-Card-Reader-BCR-/stargazers)  
  Android native application to extract contact names, emails, and phone numbers from business cards using `tess-two` (Android Tesseract OCR engine) and camera capture.

- **[CardScan](https://github.com/danauclair/CardScan)** [![GitHub stars](https://img.shields.io/github/stars/danauclair/CardScan?style=social&color=white)](https://github.com/danauclair/CardScan/stargazers)  
  iOS OCR demonstration application using Tesseract OCR to scan business cards and automatically create iOS contacts.

- **[Javascript-BCR-Library](https://github.com/syneo-tools-gmbh/Javascript-BCR-Library)** [![GitHub stars](https://img.shields.io/github/stars/syneo-tools-gmbh/Javascript-BCR-Library?style=social&color=white)](https://github.com/syneo-tools-gmbh/Javascript-BCR-Library/stargazers)  
  Client-side JavaScript and web-based offline business card reader library with structured contact field extraction.

- **[card-reader](https://github.com/gpadmaku1/card-reader)** [![GitHub stars](https://img.shields.io/github/stars/gpadmaku1/card-reader?style=social&color=white)](https://github.com/gpadmaku1/card-reader/stargazers)  
  Card reader Android application that scans business cards with OCR and directly syncs and saves details into Google Contacts.

- **[Business-Card-Scanner](https://github.com/dhruv2601/Business-Card-Scanner)** [![GitHub stars](https://img.shields.io/github/stars/dhruv2601/Business-Card-Scanner?style=social&color=white)](https://github.com/dhruv2601/Business-Card-Scanner/stargazers)  
  Optical Character Recognition engine to scan business cards locally and offline on Android devices.

- **[business-card-scanner](https://github.com/stpabhi/business-card-scanner)** [![GitHub stars](https://img.shields.io/github/stars/stpabhi/business-card-scanner?style=social&color=white)](https://github.com/stpabhi/business-card-scanner/stargazers)  
  Native iOS business card reader app leveraging Tesseract OCR for automated contact detail extraction.

- **[Business-Card-Reader-App](https://github.com/ierolsen/Business-Card-Reader-App)** [![GitHub stars](https://img.shields.io/github/stars/ierolsen/Business-Card-Reader-App?style=social&color=white)](https://github.com/ierolsen/Business-Card-Reader-App/stargazers)  
  End-to-end OCR and entity extraction project parsing contact entities from scanned business card images.

- **[Text-Extraction-From-Business-Card-Using-OCR](https://github.com/tulasinnd/Text-Extraction-From-Business-Card-Using-OCR)** [![GitHub stars](https://img.shields.io/github/stars/tulasinnd/Text-Extraction-From-Business-Card-Using-OCR?style=social&color=white)](https://github.com/tulasinnd/Text-Extraction-From-Business-Card-Using-OCR/stargazers)  
  Python and Streamlit web application using EasyOCR to extract names, emails, phones, pin codes, addresses, and URLs from business cards.

- **[BizCardX](https://github.com/IamJafar/BizCardX-Extracting_Business_Card_Data_with_OCR)** [![GitHub stars](https://img.shields.io/github/stars/IamJafar/BizCardX-Extracting_Business_Card_Data_with_OCR?style=social&color=white)](https://github.com/IamJafar/BizCardX-Extracting_Business_Card_Data_with_OCR/stargazers)  
  Interactive Streamlit application using EasyOCR and SQL database integration for structured business card digitization and CRUD contact management.

- **[BusinessCard-DataExtraction-OCR-NER](https://github.com/shaadclt/BusinessCard-DataExtraction-OCR-NER)** [![GitHub stars](https://img.shields.io/github/stars/shaadclt/BusinessCard-DataExtraction-OCR-NER?style=social&color=white)](https://github.com/shaadclt/BusinessCard-DataExtraction-OCR-NER/stargazers)  
  Structured entity extraction pipeline combining OpenCV image preprocessing, PyTesseract OCR, and spaCy Named Entity Recognition (NER).

- **[Meishi](https://github.com/mundanelunacy/meishi)** [![GitHub stars](https://img.shields.io/github/stars/mundanelunacy/meishi?style=social&color=white)](https://github.com/mundanelunacy/meishi/stargazers)  
  TypeScript/React PWA for business card scanning using bring-your-own LLM API key (OpenAI, Anthropic, Google Gemini); captures card images, extracts structured contacts via LLM, provides editable review UI, exports `.vcf`, and syncs to Google Contacts.

- **[bizscan](https://github.com/pratikpaudel/bizscan)** [![GitHub stars](https://img.shields.io/github/stars/pratikpaudel/bizscan?style=social&color=white)](https://github.com/pratikpaudel/bizscan/stargazers)  
  Python/Streamlit business card scanner using EasyOCR for text extraction and OpenCV for image bounding box visualization with Supabase backend storage.

### Mobile SDKs & Core OCR Engines

- **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)** [![GitHub stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract?style=social&color=white)](https://github.com/tesseract-ocr/tesseract/stargazers) — The foundational open-source neural net OCR engine supporting 100+ languages.
- **[EasyOCR](https://github.com/JaidedAI/EasyOCR)** [![GitHub stars](https://img.shields.io/github/stars/JaidedAI/EasyOCR?style=social&color=white)](https://github.com/JaidedAI/EasyOCR/stargazers) — Ready-to-use Python OCR library supporting 80+ languages with deep learning detection & recognition.
- **[business_card_scanner (Flutter Plugin)](https://pub.dev/packages/business_card_scanner)** — Flutter package for offline business card scanning using Google ML Kit on-device text recognition.
- **[advanced_business_card_reader (Flutter Plugin)](https://pub.dev/packages/advanced_business_card_reader)** — Flutter plugin with native OCR (Google ML Kit on Android, Apple Vision on iOS), entity extraction, and double-sided card support.
- **[Google ML Kit Text Recognition](https://developers.google.com/ml-kit/vision/text-recognition)** — On-device OCR SDK for Android/iOS with zero cloud latency and privacy guarantees.
- **[Apple Vision Framework](https://developer.apple.com/documentation/vision)** — Native high-performance iOS/macOS text and document recognition.

**Frameworks for building custom systems**: Combine **Tesseract** or **EasyOCR** for text extraction, **Meishi** or **bizcard-ai-scanner** for LLM-assisted field mapping and review UI, and **Google Contacts API** or **Supabase** for contact storage—or wrap **ML Kit** in a Flutter app for fully on-device, privacy-first scanning.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Business card scanning apps process personal contact data; ensure compliance with applicable privacy regulations (GDPR, CCPA) and your organization's data handling policies.
- Open-source OCR and LLM-based extraction tools require careful validation of accuracy before relying on them for CRM data entry; always review extracted fields.

---

**Made for sales professionals, networkers, privacy-conscious users, and developers building contact automation.**  
Let's make business card scanning more open, accurate, and privacy-respecting.

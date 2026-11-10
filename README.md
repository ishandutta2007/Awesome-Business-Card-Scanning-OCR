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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Zoho Card Scanner](https://www.zoho.com/crm/mobile/card-scanner.html)**  
  Mobile app that scans business cards in 10+ languages and saves contacts to Zoho CRM, Salesforce, Google Cloud, and other Zoho apps; features augmented reality overlays showing CRM status and smart field filling [citation:1].

- **[CamCard](https://www.camcard.com/)**  
  AI-powered business card recognition app with 99.99% claimed accuracy, CRM sync (Salesforce, Google, Outlook), voice transcription, and digital business card sharing via QR code and link [citation:2][citation:13].

- **[ABBYY Business Card Reader](https://pdf.abbyy.com/products/mobile/business-card-reader/)**  
  OCR specialist's card scanner supporting 25 languages, auto-crop and edge detection, Apple Watch companion app, and export to Salesforce, Excel, and vCard; free tier limited to 10 recognitions [citation:3][citation:14].

- **[ScanBizCards](https://www.scanbizcards.com/)**  
  Versatile card and conference badge scanner with batch scanning, human transcription fallback for difficult cards, email signature capture, and unlimited Salesforce export on Premium plans [citation:4][citation:15].

- **[HubSpot Business Card Scanner](https://www.hubspot.com/)**  
  Free scanner built into the HubSpot mobile app; AI maps card text to CRM properties with ~98% accuracy using a neural network trained on ~500,000 business cards, directly creating HubSpot contacts .

- **[Haystack](https://thehaystackapp.com/)**  
  Digital business card platform with unlimited AI card scanning on free plans; Pro tiers add CRM integrations, smart email signatures, and team management for sales organizations [citation:6].

- **[Covve](https://covve.com/)**  
  Business card and event badge scanner supporting 60+ languages with offline scanning; Pro adds custom fields with CRM mapping and team analytics, Enterprise adds SSO and audit logs [citation:7].

- **[Sansan](https://jp.sansan.com/)**  
  Japan-market leader in corporate business card management with 99.9% data accuracy through AI + human verification; dedicated scanner processes 100 cards in 5 minutes, with company-wide contact sharing and 11-language support [citation:8].

- **[Popl](https://popl.co/)**  
  Digital-first networking platform with AI-powered OCR card scanner, NFC tap sharing, customizable lead capture forms, and CRM sync; offline scanning supported with automatic sync when reconnected [citation:10].

- **[Evernote Scannable](https://evernote.com/)**  
  iOS-only scanning app for documents, receipts, and business cards; auto-crops and enhances images, saves to Evernote or device, though lacks dedicated contact field parsing [citation:9].

## Open-Source GitHub Projects

- **[Meishi](https://github.com/mundanelunacy/meishi)**  
  TypeScript/React PWA for business card scanning using bring-your-own LLM API key (OpenAI, Anthropic, Google Gemini); captures or imports card images, extracts structured contacts via LLM, provides editable review UI, exports `.vcf`, and optionally syncs to Google Contacts via Firebase token brokering [citation:11][citation:20].

- **[BizScan](https://github.com/pratikpaudel/bizscan)**  
  Python/Streamlit business card scanner using EasyOCR for text extraction and OpenCV for image processing; stores contacts in Supabase, provides search/edit/delete management UI, and visualizes detected text regions on scanned cards [citation:21].

- **[bizcard-ai-scanner](https://github.com/vassiliylakhonin/bizcard-ai-scanner)**  
  Privacy-first TypeScript business card scanner with configurable AI providers or on-device OCR; supports photo/video input, review/edit workflow, and Excel/CSV/vCard export under MIT license [citation:26].

- **[business_card_scanner (Flutter)](https://pub.dev/packages/business_card_scanner)**  
  Flutter package for offline business card scanning using Google ML Kit on-device text recognition; extracts emails, phone numbers, and URLs with smart parsing, works on Android and iOS [citation:19][citation:29].

- **[advanced_business_card_reader (Flutter)](https://pub.dev/packages/advanced_business_card_reader)**  
  Flutter plugin with native OCR (Google ML Kit on Android, Apple Vision on iOS), entity extraction for phones/emails/URLs, Dart-side fallback parsing, and double-sided card support; requires Android SDK 26+ and iOS 15.5+ [citation:24][citation:27].

- **[Android OCR Card Reader (tess-two)](https://github.com/topics/business-card?o=desc&s=stars)**  
  Community Android app using Tesseract OCR (tess-two) and device camera to extract name, email, and phone from business cards; a simpler, older reference implementation [citation:17].

### Additional Strong Open-Source Options

- **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)** — The foundational open-source OCR engine underlying many card scanning projects; supports 100+ languages and can be embedded in custom pipelines.
- **[EasyOCR](https://github.com/JaidedAI/EasyOCR)** — Python OCR library used by BizScan; supports 80+ languages with a simple API for custom extraction workflows.
- **[Google ML Kit Text Recognition](https://developers.google.com/ml-kit/vision/text-recognition)** — On-device OCR for Android/iOS; privacy-preserving since images never leave the device.
- **[Apple Vision Framework](https://developer.apple.com/documentation/vision)** — Native iOS OCR with high accuracy; used by advanced_business_card_reader for iOS extraction.
- **Community Flutter/React Native card scanner packages** — Various implementations bridging native OCR to cross-platform apps.

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

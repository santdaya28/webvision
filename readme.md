webvision 
UMANG 
rebuilding umang website - by creating multiple  section 
# 🇮🇳 UMANG Smart Assistant – उमंग स्मार्ट सहायक

#AI-Assisted Smart Discovery & Navigation for Indian Government Services

UMANG Smart Assistant is an independent GovTech prototype designed to make Indian government digital services easier to discover, understand, and access.

It helps citizens describe their problems in natural Hindi or English and guides them towards relevant government services, required documents, eligibility information, and official portals.

> **Note:** This is an independent concept prototype. It is not affiliated with, endorsed by, or officially integrated with UMANG, MeitY, or any government department.

---

# Key Features

# 1. Smart Problem-to-Service Navigator
- Describe everyday problems in natural Hindi or English.
- Intelligent, rule-based intent classification.
- Matches citizen needs with relevant government services.
- Explains why a particular service is recommended.
- Provides relevant document checklists and official portal links.

# 2. UMANG Sahayak – Conversational Assistant
- Interactive citizen assistance interface.
- Step-by-step government service guidance.
- Scheme eligibility guidance for selected schemes.
- Text-to-Speech support for assistant responses.
- Clearly labelled demo responses.

# 3. Accessibility Suite
- Adjustable font sizes (A, A+, A++).
- High-contrast display mode.
- Text-to-Speech functionality.
- Keyboard navigation with visible focus indicators.
- Designed with senior citizens and Divyangjan users in mind.

# 4. Bilingual Interface
- English and Hindi language support.
- Language switching across major application sections.
- Localized service information and navigation.

# 5. Government Services Directory
Includes a catalogue of 12+ public digital services, such as:

- EPFO – Provident Fund Services
- UIDAI – Aadhaar Services
- DigiLocker
- PM-Kisan
- Ayushman Bharat PM-JAY
- Parivahan – Driving Licence Services
- Income Tax e-Filing
- Passport Seva
- National Scholarship Portal
- Bharat BillPay
- Pradhan Mantri Awas Yojana
- Atal Pension Yojana

# 6. Application Tracker
- Interactive application status tracking interface.
- Multi-stage progress timeline.
- Sample application reference numbers.
- Simulated application progress clearly labelled as DEMO.

# 7. Grievance Redressal Guide
- Guidance for submitting public grievances through CPGRAMS.
- Step-by-step instructions.
- Official government portal references.

---

##  The Problem We Address

Citizens often face difficulties when navigating government digital services:

- Finding the correct service for their specific problem.
- Understanding complicated government terminology.
- Knowing which documents are required.
- Understanding eligibility requirements.
- Navigating services across different government departments.
- Accessing digital platforms with accessibility barriers.

## Our Solution

UMANG Smart Assistant introduces a citizen-first approach:

**Describe Your Problem → Identify the Right Service → Understand Requirements → Follow Guided Steps → Visit Official Portal**

The goal is to simplify service discovery rather than replace existing government platforms.

---

##  Technology Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend application |
| Vite | Development and build tool |
| JavaScript | Application logic |
| Tailwind CSS | Responsive UI styling |
| Lucide React | Icons |
| Web Speech API | Text-to-Speech |

# Architecture
- Frontend-based prototype.
- Local sample datasets and rule-based intent classification.
- React Context for language and accessibility preferences.
- Reusable component-based architecture.
- No paid API key required for the current prototype.

---

#  Installation & Setup

# Prerequisites
- Node.js (LTS recommended)
- npm
- Git

# 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

# 2. Navigate to the Project

```bash
cd umang-smart-assistant
```

# 3. Install Dependencies

```bash
npm install
```

# 4. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

# 5. Create Production Build

```bash
npm run build
```

---

#  Project Structure

```text
src/
├── context/
│   ├── LanguageContext.jsx
│   └── AccessibilityContext.jsx
│
├── data/
│   ├── servicesData.js
│   ├── aiKnowledgeBase.js
│   └── translations.js
│
├── components/
│   ├── layout/
│   ├── dashboard/
│   ├── assistant/
│   └── tracker/
│
├── App.jsx
├── main.jsx
└── index.css

index.html
package.json
vite.config.js
tailwind.config.js
```

---

# Important Disclaimer

- This project is an independent educational and hackathon prototype.
- It does not have direct integration with government databases or official UMANG APIs.
- AI assistant responses and application tracking information are simulated.
- Eligibility, fees, processing times and document requirements should be checked against the relevant official government sources.
- Never enter sensitive personal information such as Aadhaar numbers, PAN details, passwords or OTPs into this prototype.

---

#  Future Enhancements

- Secure integration with authorized government APIs.
- More advanced multilingual natural-language understanding.
- Real-time service availability information from authorized sources.
- Personalized citizen dashboards.
- Improved screen-reader and assistive technology support.
- Verified, regularly updated government service information.

---

# Project Information

**Project:** UMANG Smart Assistant  
**Category:** GovTech / Digital Governance / AI-Assisted Public Services  
**Purpose:** Simplifying access to Indian government digital services.

---

# Made with  for Digital India

*Making government services easier to discover, understand, and access.*
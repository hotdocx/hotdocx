<p align="center">
  <img src="https://raw.githubusercontent.com/hotdocx/researchersx.hotdocx.com/gh-pages/hotdocx_mascot.png" width="150" alt="hotdocX Mascot">
  <h1 align="center">hotdocX</h1>
  <p align="center">
    <strong>Publish Your Daily Experiences Apps, Get Paid. <br/> <em>hotdocX is the Hottest Fastest Calendared-Marketplace Publisher</em></strong>
  </p>
  <p align="center">
    hotdocX is an AI-powered social events marketplace that turns your Images, PDFs, LaTeX, Markdown text, and data into live, shareable applications.
  </p>
  <p align="center">
    <a href="https://hotdocx.kit.com" target="_blank">
      <img src="https://img.shields.io/badge/Join%20The%20Waitlist-2.4K%2B%20Researchers-orange?style=for-the-badge&logo=rocket" alt="Join the Waitlist">
    </a>
  </p>
  <p align="center">
    <a href="https://github.com/hotdocx" target="_blank"><img src="https://img.shields.io/github/followers/hotdocx?style=social" alt="GitHub followers"></a>
    <a href="https://x.com/workschool365" target="_blank"><img src="https://img.shields.io/twitter/follow/workschool365?style=social" alt="Twitter Follow"></a>
  </p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/hotdocx/researchersx.hotdocx.com/gh-pages/hotdocx_capture.png" alt="A screenshot of the hotdocx application, showing an interactive UI generated from a document." width="100%">
</p>

---

## ✨ From Static Paper to Interactive Playground

Watch as complex research documents are instantly transformed into live, interactive applications. Our AI reads your files and automatically generates UIs, visualizations, and formatted content, turning a static paper into a live demo.

## 🚀 Core Features

| Icon | Feature | Description |
| :--: | --- | --- |
| 🧠 | **Intelligent Document Transformation** | Go beyond static text. Our AI reads your PDFs, LaTeX, and text files, then automatically generates interactive UIs, visualizations, and formatted content. |
| 👥 | **Build Communities Around Places** | Create 'Places'—virtual hubs for your lab or area of interest. Each Place is a community center with its own document libraries, member roles, and event feed. |
| 📚 | **Centralized Document Libraries** | Connect your Place to where your work already lives. Source documents directly from SharePoint, GitHub repositories, arXiv categories, or any URL. |
| 🍴 | **Remix, Fork, and Evolve Ideas** | Every event is a starting point. Remix an existing creation to add your own data, fork a visualization to test a new hypothesis, or build upon a shared codebase. |
| 💰 | **A New Creator Economy** | Monetize your expertise. Set a price in 'Coins' for others to remix your work, view your source code, or access premium content. |
| 📡 | **Amplify Your Reach** | Automate your outreach. Configure Social Relays to automatically share new events to X (Twitter), Reddit, and Instagram. |

---

## 🎯 Built For...

-   **Researchers & Academics**: Publish interactive papers, host virtual poster sessions, and collaborate on experimental code.
-   **Creators & Authors**: Transform your long-form content into bite-sized, interactive experiences.
-   **Learners & Educators**: Make learning active. Generate quizzes, summaries, and interactive tutorials from course materials.
-   **Conference Organizers**: Streamline your call for papers and peer-review process with a central, interactive hub.
-   **In-App Developers**: Build and sell in-app power-ups, features, or mini-games using our secure host-guest communication bridge.

---

## ⭐ Become a Founding Member (Customer Advisory Board)

We're inviting a select group of researchers, creators, and developers to join our exclusive **Customer Advisory Board**. This is more than a waitlist—it's a chance to shape the future of collaborative science and content creation.

**As a Founding Member, you'll get:**
-   **First Access**: Get priority access to the developer preview.
-   **Shape the Roadmap**: Influence features with direct feedback calls with our team.
-   **Lifetime Discount**: Lock in a permanent, exclusive discount on premium features.
-   **No Obligations**: Just share your insights and help us build the best platform for you.

<p align="center">
  <a href="https://hotdocx.kit.com" target="_blank">
    <img src="https://img.shields.io/badge/Join%20the%20Advisory%20Board-%23FF4500.svg?&style=for-the-badge&logo=rocket&logoColor=white" alt="Join the Waitlist"/>
  </a>
</p>

*Can't wait? The most determined researchers might just find the developer preview by exploring our GitHub organization...*

---

## ❤️ Support Our Work

hotdocX is an ambitious open-source project. You can support our development and get premium features in the app by becoming a sponsor!

**[➡️ Become a GitHub Sponsor](https://github.com/sponsors/hotdocx)**

Sponsorship tiers map directly to our in-app subscription plans, giving you an alternative way to power up your account while supporting the open-source community.

---

## 🛠️ Tech Stack

-   **Backend**: [Convex](https://convex.dev) (Serverless Database, Functions, Auth)
-   **Frontend**: [React](https://reactjs.org/), [Vite](https://vitejs.dev/), [Tailwind CSS](https://tailwindcss.com/)
-   **UI**: [Shadcn UI](https://ui.shadcn.com/) + [Radix UI](https://www.radix-ui.com/)
-   **In-Browser IDE**: `@codesandbox/sandpack-react`
-   **AI**: Google Gemini & Mistral

## hotdocX Feature List

### **Access & User Experience**

*   **Anonymous Guest Access:** Users can browse and interact with the application without signing in, with an option to create an account later.
*   **User Authentication:** Supports email/OTP (One-Time Password) and GitHub OAuth for user sign-up and sign-in.
*   **Geolocation Services:** Utilizes the user's current location to filter event listings and provide localized search results for events and places.
*   **Map Provider Selection:** Allows users to switch between Google Maps and MapLibre for displaying event and place locations on maps.
*   **Theme Toggle:** Provides a user-toggleable dark and light theme for the application interface.

### **Event & Content Creation**

*   **AI-Powered Document Transformation:** Converts user-uploaded documents (PDFs, LaTeX, text, images) into interactive UIs, visualizations, or runnable code artifacts using Google Gemini AI models. Generated code is rendered in an in-browser Sandpack environment.
*   **Event Creation:** Users can create events specifying a title, associated place, selected AI template, and an initial AI prompt.
*   **Online Meeting Integration:** Offers the option to create Microsoft Teams meetings for events, which are configured to allow all attendees to join and present directly. Requires a configured SharePoint relay for the associated place.
*   **Event Remixing:** Enables users to create new events based on existing ones, inheriting documents and AI prompt history. Remixing may be subject to a "remix\_access" entitlement purchase.
*   **Document Attachment & Sourcing:** Supports native file uploads and integration with external document sources including SharePoint, GitHub repositories, arXiv categories, and URLs. Includes OCR processing for PDF documents.
*   **Thumbnail Generation:** Automatically generates PDF thumbnails, can use AI-generated images, or generates an AI summary thumbnail if no other visual thumbnail is available.
*   **In-Editor Content Editing:** Event creators with appropriate permissions (creator, manager, or purchased "view\_source" access) can directly edit generated code artifacts within the Sandpack editor.
*   **AI Conversation Continuation:** Allows event creators to provide additional prompts to the AI model to refine existing artifacts, maintaining a conversation history.

### **Platform Interaction & Discovery**

*   **Event Browsing Views:** Events can be displayed in grid, swipeable deck, map, or calendar formats.
*   **Event Filtering:** Events can be filtered by proximity to user's location, tags, and date ranges (start/end times).
*   **Place Management:** Users can create and manage "Places" which act as community hubs. Places can be linked to Google Places or Baidu Maps IDs.
*   **Place Search:** Provides search functionality for places by name, supporting both Google Places and Baidu Places APIs for location linking.
*   **Event Calendar Views:** Dedicated calendar views are available for all public events on the home page, and a personalized calendar view within the user's profile showing their created, saved, and attending events.
*   **User Profiles:** Displays user information, created events, created and owned places, and events marked as saved, upcoming attending, or past attending.
*   **Commenting System:** Supports adding comments to events, replying to specific comments, and mentioning other users (`@mention`).
*   **User Actions Tracking:** Records user interactions with events, such as saving, attending, or hiding events.
*   **In-App Notifications:** Notifies users about new comments, event attendance, remixes, and direct mentions.

### **Monetization & API**

*   **Creator Economy:** Event creators can define a `purchaseMenu` for their events, specifying items (e.g., `remix_access`, `view_source`) and their prices in a virtual currency ("Coins"). Items can be entitlements (one-time purchase) or consumables (repeatable purchases).
*   **Virtual Coin System:** An in-app virtual currency ("Coins") is used for purchases. Users can acquire Coins via Stripe. User Coin balances are managed atomically.
*   **Subscription Tiers:** Supports "Free," "Premium," and "VIP" subscription tiers. Users can upgrade their tier via Stripe or by sponsoring the hotdocX project on GitHub.
*   **Social Media Relays:** Automates the cross-posting of new events to configured social media platforms (X/Twitter, Reddit, Instagram) and SharePoint sites.
*   **Permanent Event Identifiers (CAT-Refs):** Each event receives a unique, immutable 14-character identifier (e.g., `YYDDD-UUUU-QQSSS`). Events can be retrieved using the full ID or an 11-character shorthand.
*   **Programmatic Event Creation API:** Provides an HTTP API endpoint for external applications to programmatically create events, upload associated files (including base64 encoded content), and integrate with AI content generation. API access is secured using personal access tokens with defined scopes.
    *   **API Token Management:** Users can generate and manage personal access tokens with specific scopes (e.g., `events:create`) from their settings page. Rate limiting is applied to API usage.

---
<p align="center">
  <a href="https://hotdocx.github.io">Website</a> • 
  <a href="https://x.com/workschool365">Twitter</a> • 
  <a href="https://github.com/hotdocx">GitHub</a>
</p> 
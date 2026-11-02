# Awesome-Event-Management-Registration-Software

# Awesome Event Management & Registration Software

> A curated list of top Event Management and Registration platforms — both SaaS/Hosted commercial solutions and open-source alternatives for self-hosted event organization, ticketing, and attendee management.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [HubSpot Events Management](#hubspot-events-management)
  - [Cvent](#cvent)
  - [Eventbrite](#eventbrite)
  - [Bizzabo](#bizzabo)
  - [Hopin](#hopin)
  - [Splash](#splash)
  - [Whova](#whova)
  - [Goldcast](#goldcast)
  - [Airmeet](#airmeet)
  - [Socio (Webex Events)](#socio-webex-events)
- [Open-Source Software](#-open-source-software)
  - [Indico](#indico)
  - [Hi.Events](#hievents)
  - [Open Event Orchestrator](#open-event-orchestrator)
  - [OpenPass](#openpass)
  - [pretalx](#pretalx)
  - [TALL Events](#tall-events)
  - [LibreRegistration](#libreregistration)
  - [Virtual Event Starter Kit](#virtual-event-starter-kit)
  - [Eventyay](#eventyay)
  - [osem](#osem)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Event Management and Registration platforms. These are not open-source but are included as reference points for feature comparison.

### HubSpot Events Management
**Type:** Marketing-integrated event management  
Extends HubSpot's CRM and marketing suite with event registration pages, attendee tracking, and post-event follow-up automation. Events are treated as campaign assets, with registrants automatically synced to contact records. Best suited for organizations already using HubSpot for inbound marketing and sales.

### Cvent
**Type:** Enterprise event management suite  
A comprehensive platform covering venue sourcing, event registration, mobile apps, attendee management, and post-event analytics. Widely used for large-scale conferences, tradeshows, and corporate events. Pricing is quote-based and typically targets mid-to-large enterprises.

### Eventbrite
**Type:** Self-service ticketing and discovery  
The most recognized name in event ticketing for public events. Offers event creation, ticketing (free and paid), attendee management, and a discovery marketplace. Fees are charged per paid ticket. Best for public events, workshops, and community gatherings rather than complex enterprise conferences.

### Bizzabo
**Type:** Event experience operating system  
Combines registration, agenda management, networking, and attendee engagement into a unified platform. Strong focus on hybrid and in-person event experiences. Pricing is quote-based.

### Hopin
**Type:** Virtual and hybrid event platform  
Specializes in online events with multi-stage streaming, networking sessions, and expo booths. Acquired by RingCentral in 2023, with the events platform subsequently wound down. Included here as a historical reference point for the virtual event category.

### Splash
**Type:** Event marketing and registration  
Focused on branded event registration pages, guest management, and event marketing automation. Popular for corporate events, product launches, and brand experiences. Pricing is quote-based.

### Whova
**Type:** Event app and attendee engagement  
Provides mobile event apps with agendas, networking, messaging, and community features. Often used alongside other registration systems for attendee engagement. Pricing is quote-based.

### Goldcast
**Type:** B2B video events platform  
Designed for virtual and hybrid B2B events with video-first experiences, attendee analytics, and integrations with marketing automation platforms. Pricing is quote-based.

### Airmeet
**Type:** Virtual and hybrid event platform  
Offers virtual conferences, webinars, and meetups with networking lounges, breakout sessions, and audience engagement tools. Pricing tiers available with a free option for smaller events.

### Socio (Webex Events)
**Type:** Event experience platform (Cisco)  
Acquired by Cisco and rebranded as Webex Events. Provides event apps, registration, live streaming, and attendee engagement for in-person, virtual, and hybrid events. Integrated into the broader Webex ecosystem.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Event Management and Registration platforms. All listed projects offer source code you can deploy on your own infrastructure.

### Indico
**Stack:** Python / PostgreSQL | **License:** MIT  
A full-featured conference lifecycle management and meeting/lecture scheduling tool, originally developed at CERN. Handles the complete event lifecycle: call for papers, abstract review, registration, timetable creation, and post-event materials. Includes a room booking system, badge printing, and a plugin architecture. With 2,000+ GitHub stars and active development, it is one of the most mature open-source event management systems available [citation:6][citation:15].  
**Best for:** Academic conferences, research institutions, and organizations needing comprehensive lifecycle management beyond simple ticketing.

### Hi.Events
**Stack:** PHP / Laravel / React | **License:** Open Source (per GitHub)  
An open-source event management and ticket selling platform positioned as a self-hosted alternative to Eventbrite, Tito, and Ticket Tailor. Supports ticket sales, door management, event check-in, and attendee tracking. Actively maintained with ~4,000 GitHub stars and frequent releases [citation:10][citation:12].  
**Best for:** Organizations wanting a direct open-source replacement for Eventbrite with self-hosted ticketing and sales.

### Open Event Orchestrator
**Stack:** SvelteKit / TypeScript / PocketBase | **License:** Open Source (per GitHub)  
A comprehensive control plane for events covering the full organizer workflow. Features include Call for Papers (CFP) with speaker submission and review, planning and scheduling with room/track management, Stripe-integrated ticketing with QR check-in, CRM with contact segmentation and email campaigns, budget and finance management, sponsor management, and a public REST API with webhooks and embeddable widgets [citation:1].  
**Best for:** Conference organizers who want an all-in-one open-source platform covering CFP through finance, sponsorship, and post-event CRM.

### OpenPass
**Stack:** Go / Fiber / SvelteKit / PostgreSQL | **License:** Open Source (per GitHub)  
A fully free and self-hostable event platform with two modes: list-only discovery (directing users to external registration) and full platform mode covering registration, ticketing, check-in, and feedback. Includes location-based discovery, interactive maps, custom registration forms with drag-and-drop builder, QR-code tickets with offline-capable scanning, live analytics, and bulk email/SMS [citation:3].  
**Best for:** Community-focused event discovery and management where attendee privacy and self-hosting are priorities.

### pretalx
**Stack:** Python / Django | **License:** Apache-2.0  
A web-based conference planning tool focused on the Call for Papers and scheduling workflow. Features include CFP submission, review and scoring, speaker management, talk scheduling, and exports to various formats. Actively maintained with 650+ GitHub stars [citation:13][citation:15].  
**Best for:** Academic and technical conferences needing a focused CFP and scheduling workflow.

### TALL Events
**Stack:** PHP / Laravel / Livewire / Alpine.js | **License:** Open Source (per GitHub)  
An open-source event management platform built with the TALL stack, positioned as a simpler Eventbrite alternative. Features include multi-ticket-type events, promo codes, QR-code tickets, waitlist management, custom registration fields, team collaboration, and check-in with QR scanning [citation:5].  
**Best for:** Small to mid-sized organizers wanting a Laravel-based, feature-rich ticketing platform with a modern UI.

### LibreRegistration
**Stack:** Go / SQLite or PostgreSQL | **License:** Open Source (per GitHub)  
A lightweight, privacy-friendly, self-hosted event registration platform. Attendees only need a name (email optional), with no account creation required. Supports self-service cancellation links, optional public attendee lists, CSV export, and email notifications. Deploys in minutes via Docker [citation:7].  
**Best for:** Meetups, workshops, and community gatherings where simple, privacy-respecting registration is the priority.

### Virtual Event Starter Kit
**Stack:** Next.js / TypeScript / Vercel | **License:** Open Source (per GitHub)  
A starter kit for building custom virtual event platforms, originally used for Next.js Conf 2020 with nearly 40,000 live attendees. Features multi-stage streaming (YouTube or 100ms live video), sponsor expo, career fair, ticket registration, speaker pages, and schedule. Built on the principle of delegating specialized components while owning the platform [citation:2].  
**Best for:** Developers and technical teams who want to build a custom virtual event experience rather than use a SaaS platform.

### Eventyay
**Stack:** Python / Django / WebRTC | **License:** Open Source (per GitHub)  
An online event management and video conferencing platform combining ticketing, CFP, scheduling, and live video into a unified system. Uses WebRTC for browser-to-browser media and includes live streaming, interactive video calls, and group chat [citation:8][citation:11].  
**Best for:** Organizations wanting an integrated open-source platform for both event management and virtual conferencing.

### osem
**Stack:** Ruby on Rails | **License:** Open Source (per GitHub)  
Event management tailored specifically for free and open-source software conferences. Handles CFP, scheduling, speaker management, and registration for community-driven technical events [citation:15].  
**Best for:** Open-source community conferences and FOSS events needing a purpose-built management platform.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Ticketing | Virtual Events | Best For |
|----------|---------|-------|-----------|----------------|----------|
| **HubSpot Events** | Proprietary | Cloud | ✅ | ❌ | HubSpot marketing users |
| **Cvent** | Proprietary | Cloud | ✅ | Limited | Enterprise conferences |
| **Eventbrite** | Proprietary | Cloud | ✅ | ❌ | Public ticketed events |
| **Bizzabo** | Proprietary | Cloud | ✅ | ✅ | Hybrid event experiences |
| **Whova** | Proprietary | Cloud | ❌ (app only) | ✅ | Attendee engagement apps |
| **Indico** | MIT | Python | ✅ | ❌ | Academic lifecycle management |
| **Hi.Events** | Open Source | PHP/Laravel | ✅ | ❌ | Eventbrite self-hosted replacement |
| **Open Event Orchestrator** | Open Source | SvelteKit/PocketBase | ✅ (Stripe) | ❌ | Full organizer workflow + finance |
| **OpenPass** | Open Source | Go/SvelteKit | ✅ | ❌ | Community discovery + privacy |
| **pretalx** | Apache-2.0 | Python/Django | ❌ | ❌ | CFP + scheduling focus |
| **TALL Events** | Open Source | PHP/Laravel | ✅ | ❌ | Laravel-based ticketing |
| **LibreRegistration** | Open Source | Go | ❌ (free) | ❌ | Privacy-first simple registration |
| **Virtual Event Starter Kit** | Open Source | Next.js | ✅ | ✅ | Custom virtual event builds |
| **Eventyay** | Open Source | Python/WebRTC | ✅ | ✅ | Integrated management + video |
| **osem** | Open Source | Ruby/Rails | ✅ | ❌ | FOSS community conferences |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Event Management or Registration platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐

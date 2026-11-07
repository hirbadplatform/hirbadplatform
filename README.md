<div align="center">

# Hirbad Platform

### Learn together. Grow with the right teacher.

A Persian-first online tutoring marketplace that brings students and teachers together — from discovery and booking to live sessions and secure payments.

[![GitHub](https://img.shields.io/badge/GitHub-hirbadplatform-1553A0?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hirbadplatform)
[![Platform](https://img.shields.io/badge/Focus-Online%20Education-2D7FB8?style=for-the-badge)](#what-were-building)
[![Language](https://img.shields.io/badge/Experience-Persian%20%7C%20RTL-10B981?style=for-the-badge)](#built-for-persian)

</div>

---

## What we're building

**Hirbad** is an online tutoring platform designed to make finding, booking, and attending lessons simpler. Students can discover teachers and request private lessons or join group sessions. Teachers can manage their profiles, availability, verification, and payouts — while staff oversee the platform through an administration panel.

Our goal is to create a dependable learning experience where every step, from the first search to the completed session, feels connected.

## The platform

| For students | For teachers | For the platform team |
|---|---|---|
| Discover teachers and explore skills | Build a teaching profile | Review and verify teachers |
| Request one-to-one lessons | Set weekly availability | Manage users and content |
| Join group sessions | Host group sessions | Review disputes and payouts |
| Pay and track bookings | Track earnings and payouts | Moderate reviews and messages |
| Review completed sessions | Manage upcoming sessions | Monitor activity with audit logs |

### Core capabilities

- **Teacher discovery & verification** — skills, availability, verification documents, and staff approval.
- **Flexible learning** — private bookings and group sessions.
- **Payments & payouts** — checkout, gateway callbacks, escrow-style payment flow, commissions, refunds, disputes, and payout ledger.
- **Online meetings** — session join links with configurable meeting providers.
- **Notifications & email** — in-app notifications and Persian transactional email templates.
- **Content & support** — managed articles, static pages, reviews, and a public contact form.
- **Administration** — dedicated staff tools for users, teachers, payments, reviews, content, and audit logs.

## Built with

The project uses a modern full-stack architecture:

<div align="center">

![Python](https://img.shields.io/badge/Python-3.12-1553A0?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-5.2-0C4B33?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7-B02B2C?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-5.6-37814A?style=flat-square)
![React](https://img.shields.io/badge/React-19-149ECA?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-6-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

| Layer | Technologies |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS, TanStack Query |
| Backend | Python, Django, Django REST Framework |
| Data & background work | PostgreSQL, Redis, Celery |
| Authentication | JWT |
| API documentation | OpenAPI / Swagger via drf-spectacular |
| Infrastructure | Docker, Docker Compose, nginx |
| Quality | pytest, Vitest, Testing Library, GitHub Actions |

## Built for Persian

Hirbad's interface is Persian-first and right-to-left (RTL). The frontend includes Persian translations, Jalali date support, and the self-hosted **Vazirmatn** typeface.

The design system follows a calm, trustworthy blue identity with teal accents:

<div align="center">

| Brand blue | Blue accent | Teal accent | Soft background | Dark surface |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://placehold.co/72x36/1553A0/FFFFFF?text=%20" alt="Brand blue" /> | <img src="https://placehold.co/72x36/4A8FC5/FFFFFF?text=%20" alt="Blue accent" /> | <img src="https://placehold.co/72x36/10B981/FFFFFF?text=%20" alt="Teal accent" /> | <img src="https://placehold.co/72x36/EAF2FA/1553A0?text=%20" alt="Soft background" /> | <img src="https://placehold.co/72x36/050D1A/FFFFFF?text=%20" alt="Dark surface" /> |
| `#1553A0` | `#4A8FC5` | `#10B981` | `#EAF2FA` | `#050D1A` |

</div>

The interface supports light and dark themes, with reusable design tokens rather than scattered hard-coded colors.

## Project structure

```text
hirbad-platform/
├── hirbad-backend/       # Django REST API, domain apps, Celery tasks
├── hirbad-frontend/      # React + TypeScript application
├── docs/                 # Deployment and product documentation
├── scripts/              # Maintenance and deployment helpers
├── docker-compose.yml     # Local development stack
└── docker-compose.prod.yml
```

## Engineering principles

- **Trust and clarity:** clear booking states, verified teachers, payment records, and review moderation.
- **Reliable workflows:** background jobs for reminders, booking expiry, reconciliation, and payment processing.
- **Maintainable design:** feature-oriented frontend structure and modular Django apps.
- **Accessible localization:** RTL-aware layout, Persian copy, and Jalali date handling.
- **Operational readiness:** containerized services, CI workflows, deployment documentation, and audit trails.

## Explore the code

The main project repository contains the application source, setup instructions, architecture notes, and deployment guides.

- [Browse Hirbad repositories](https://github.com/hirbadplatform?tab=repositories)
- [Open the main project repository](https://github.com/hirbadplatform/hirbad-platform)
- [Read the project documentation](https://github.com/hirbadplatform/hirbad-platform/tree/main/docs)

## Get involved

Have an idea, found an issue, or want to help improve the learning experience? Explore the repositories and join the conversation through GitHub issues and pull requests.

---

<div align="center">

**Hirbad Platform**  
*Making quality learning easier to find, book, and experience.*

<sub>Built with care for students, teachers, and lifelong learners.</sub>

</div>

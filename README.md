# Xi02 Developer Compliance Documentation

## Overview

Xi02 is a creator workflow assistant designed to help users organize and manage their own Pinterest content through the official Pinterest API.

The application focuses on:

* Content organization
* Board management
* Pin management
* Inspiration workflow support
* Creator productivity

Xi02 is not a platform analytics service, benchmarking tool, competitor intelligence system, or market research product.

---

## Pinterest API Usage

Xi02 accesses Pinterest content exclusively through the official Pinterest API.

The application does not:

* Scrape Pinterest
* Collect Pinterest passwords
* Circumvent Pinterest authorization systems
* Access private content without authorization

All Pinterest access requires explicit OAuth authorization from the user.

---

## Requested Initial Scopes

The initial application requests only:

* user_accounts:read
* boards:read
* pins:read

These permissions are used solely to support user-authorized workflow features.

---

## Data Handling Principles

Xi02 follows a data minimization approach.

We:

* Access Pinterest data only when needed
* Use Pinterest data only for the authenticated user's workflow
* Do not sell or share Pinterest-derived information
* Do not provide competitor benchmarking or platform-wide analytics

---

## OAuth Flow

1. User clicks Connect Pinterest
2. User is redirected to Pinterest OAuth
3. User grants authorization
4. Pinterest returns authorization code
5. Xi02 exchanges code for access token
6. Xi02 accesses authorized Pinterest content
7. Content is displayed for the user's workflow

---

## Privacy Policy

See:

privacy-policy.md

---

## Contact

Project: Xi02

Website:
https://www.xi02.com

# Pinterest Developer Policy Checklist – Xi02

## 1. App Purpose

Xi02 is a Pinterest creator workflow assistant.

It helps users organize and manage their own authorized Pinterest boards and pins for personal creative planning.

## 2. Allowed Use Positioning

Xi02 is positioned as:

* Creator workflow tool
* Inspiration organization tool
* Pinterest content management assistant
* User-authorized board and pin organizer

Xi02 is not positioned as:

* Pinterest trend intelligence platform
* Market research database
* Competitor benchmarking product
* Platform-wide analytics tool

## 3. Data Access

Pinterest data is accessed only through:

* Official Pinterest API
* OAuth user authorization
* Minimal requested scopes

Xi02 does not scrape Pinterest or access data outside approved API permissions.

## 4. Data Storage

Xi02 does not permanently store raw Pinterest API content.

Any temporary cache is limited to operational processing and is not used to build a long-term Pinterest dataset.

## 5. User Control

Users explicitly connect their Pinterest account through OAuth.

Users can revoke access at any time from Pinterest account settings.

Xi02 does not perform automated posting, saving, following, commenting, or engagement actions without user confirmation.

## 6. Data Sharing

Xi02 does not sell, rent, license, or share Pinterest-derived data with third parties.

Xi02 does not provide Pinterest-derived benchmarking, competitor comparison, or platform-level insights.

## 7. Security

Access tokens are stored securely.

Client secrets and tokens are never committed to public repositories.

Environment variables or encrypted storage are used for sensitive credentials.

## 8. Initial API Request

Initial API access will request only:

* `user_accounts:read`
* `boards:read`
* `pins:read`

Write permissions and advanced scopes will not be requested in the first application.

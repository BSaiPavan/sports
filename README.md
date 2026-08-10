# Nandigiri SportsSphere 2K26

A web-based platform for managing the **SSSIHL Nandigiri Campus Annual Sports Events**.

SportsSphere brings student registration, event management, notices, published results, and the winners' gallery into one simple portal.

## Features

### Students

* Registration-number based login
* Register / unregister for events
* Filter events by Track, Field, Marathon, or Other
* View personal registrations
* Receive event notices
* View published results and event galleries

### Admin

* Add and manage events
* Manage students and registrations
* Export registrations as CSV
* Create event notices
* Publish and edit results
* Upload event photographs

### Leaderboard

Track and Field results contribute to the overall leaderboard:

| Position | Points |
| -------- | -----: |
| 🥇 1st   |      5 |
| 🥈 2nd   |      3 |
| 🥉 3rd   |      1 |

Marathon and Other events are excluded from leaderboard scoring.

### Teacher Mode

Teacher accounts have **view-only access** and cannot modify registrations, events, results, notices, or photos.

## Tech Stack

* HTML
* CSS
* JavaScript
* Google Apps Script
* Google Sheets / backend data
* Cloudflare Worker *(optional proxy)*

The frontend communicates with the backend through a configured API endpoint, with retry handling for temporary network/API failures.

## Running Locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Make sure the backend URL is configured in `index.html`.

## Project Structure

```text
sports-sphere/
├── index.html
├── logo.png
├── README.md
└── ...
```

## About

**Nandigiri SportsSphere 2K26**
Digital platform for the SSSIHL Annual Sports & Cultural Meet.

> Life is a Game - Play it.

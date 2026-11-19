# Trade Diary India — Cloud Attachments Storage

Private storage repository for **Trade Diary India** chart screenshots, contract notes, and bond documents.

## Purpose
This repository acts as a private, encrypted-in-transit file store accessed exclusively via the GitHub REST API using a Personal Access Token configured inside the Trade Diary India app.

## Directory Structure
- `attachments/` — Automatically managed folder storing compressed chart images (`.jpg`) and PDF documents (`.pdf`) uploaded from the app's trade entry form.
- `README.md` — Initial repository file required to keep the default `main` branch active for API uploads.

## Usage Notes
- Do not delete or rename files inside `attachments/` manually, as trade records in your GitHub Gist backup reference these exact filenames.
- Keep this repository set to **Private** so your trade charts and documents remain accessible only to your GitHub account.

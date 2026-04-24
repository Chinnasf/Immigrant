# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About This Repository

This is a Spanish-language documentation repository (`Immigrant`) containing practical immigration resources for people relocating from Latin America to Europe. Content is based on first-hand experiences and accounts from friends. There is no build system, no tests, and no code — only Markdown files.

## Structure

Each top-level directory represents a European country:

- `BELGICA/` — Most developed section; contains sub-directories: `ASISTENCIA_MEDICA/`, `PROTECCION_INTERNACIONAL/`, `ABOGADOS/`, `SOCIAL/`
- `ALEMANIA/`, `ESPANA/`, `FRANCIA/`, `HOLANDA/`, `PORTUGAL/`, `REINO_UNIDO/` — Stubs with empty README.md files

## Content Conventions

- License: CC BY 4.0 — anyone may share, adapt, and republish with attribution
- Language: bilingual (Spanish + English); Spanish files are `README.md`, English files are `README.en.md`
- Each country and sub-topic has its own `README.md`
- Resources list: organization name, address, phone(s), hours, email, and relevant URLs
- Headings use `###` for subsections within a topic file
- Contact blocks use bold `**Name**` followed by bullet-list details

## How to Contribute

To add a new country or topic: create a directory and add a `README.md` following the existing format in `BELGICA/ASISTENCIA_MEDICA/README.md` or `BELGICA/ABOGADOS/README.md` as reference.

When editing, verify that phone numbers, addresses, and URLs are accurate — this information directly affects vulnerable people. Update the `last_verified` frontmatter field (format: `"YYYY-MM"`) whenever you confirm that information is current. Aim to re-verify each file at least once a year.

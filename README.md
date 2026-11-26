
# fitsip-studio

Fit & Sip Studio — user-facing website for the Digital Services course project.

- Repository: https://github.com/LIee-zh/fitsip-studio
- Published site (GitHub Pages): https://liee-zh.github.io/fitsip-studio/

## What is in here

`index.html` is the whole site in one self-contained file:

- 6 views driven by hash routing: Home, Classes & Café, Membership, About, Contact, plus item detail pages
- 5 languages: EN / 中文 / Suomi / 한국어 / 日本語, switchable in the header and in the language dialog
- Fixed side rail that shows the current section (n/5)
- Prices in RMB (¥), sized for the Chengdu market
- Classes, menu, membership plans and the lead form talk to a live Supabase demo backend (Postgres + RLS + SECURITY DEFINER functions)
- Photos are inlined as data URIs, so the file runs from a local disk, a web server or GitHub Pages with nothing else next to it

## Companion admin suite

A separate single-file suite (Overview / Member area / Staff console / Café till / Owner dashboard / Partner portal) is kept in its own project and is not part of this repository.

## Course

Digital Services — Haaga-Helia University of Applied Sciences.
Team: Ziheng Zhou, Ruizhao Zhang, Jin Lan, Tianyi Lin.

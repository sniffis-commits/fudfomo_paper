# FUD/FOMO — Academic Paper

This repository contains the academic paper for the **FUD/FOMO** project: a transparent, reproducible meter for headline language that scores articles on six factors (clickbait, FUD, FOMO, violence, attack, profanity) and publishes the phrases that produced every score.

## Paper

Read the full draft: [docs/paper.md](docs/paper.md)

## Live site

The FUD/FOMO scanner runs live at **https://fudfomo.eu.org**:

- Site: https://fudfomo.eu.org/
- Admin: https://fudfomo.eu.org/index.php?p=admin-login
- API health: https://fudfomo.eu.org/api/health

## About

The project measures *language pressure* in headlines — not truth, not intent, not quality. Every score resolves to a matched phrase and a published ruler, and empty titles are logged as errors rather than silently zero-scored.

## Code

The full source (scorer, service, frontend, extension, tools) lives in the companion repository: https://github.com/sniffis-commits/fudfomo

This paper repository is public; the code repository is not.

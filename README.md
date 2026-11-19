# Prabodh Shivaji Ghule · Portfolio

**Live site:** https://prabodhghule.github.io/PSG

Senior Technical Engineer at Altisec Technologies, Mumbai. I deploy Palo Alto Cortex XSIAM and XDR, migrate legacy SIEMs to XSIAM, and build XQL detections and SOC automation.

## What's on the site
- **whoami** – summary and key numbers
- **focus** – XSIAM architecture, SIEM migration, detection engineering, endpoint security and SOC automation
- **experience** – roles and engagements at Altisec (Jul 2023 – present)
- **work** and **projects** – anonymized case studies and things I've built
- **skills** and **education**
- **learning** – what I'm studying now, updated weekly (see [LEARNING-LOG.md](LEARNING-LOG.md))
- **certs** – flip cards with each certificate and a link to verify it with the issuer
- **contact** – a form that emails me directly, plus email and LinkedIn
- **resume** – downloadable PDF

## Files
All files sit in the repo root, which GitHub Pages serves from the `main` branch.

| File | What it is |
| --- | --- |
| `index.html` | The whole site: layout, styles and scripts |
| `Prabodh-Shivaji-Ghule-Resume.pdf` | Resume behind the download buttons |
| `*.webp` | Certificate images shown on the backs of the flip cards |
| `LEARNING-LOG.md` | Weekly record of what I'm learning |

## Updating the site
The editable content lives in the `<script>` block of `index.html`:
- `LEARNING`, `LEARN_TOOLS`, `LEARN_INTERESTS` – the Currently learning section. Set `progress` to a number from 0 to 100, or `null` for an "in progress" bar.
- `CERTS` – certification cards. `img` is an image file name in the root, and `verify` is the issuer's link.
- `EXPERIENCE` – roles and engagements.

Edit `index.html` on GitHub (pencil icon), commit to `main`, and the site updates in about a minute.

## Contact form
The form sends messages to my Gmail through [FormSubmit](https://formsubmit.co). The first message triggers a one-time activation email that has to be confirmed before messages start arriving.

## Connect
- LinkedIn: https://www.linkedin.com/in/prabodhghule
- Email: prabodhghule21391@gmail.com

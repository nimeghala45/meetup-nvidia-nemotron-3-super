# Project Name: ContribLens
**Track:** Track 2 - Open-Source Maintainer Copilot

**Team:** Nimeghala Krishna Muppavaram

## Description
ContribLens is a contributor intelligence platform that turns intimidating 
GitHub repositories into beginner-friendly contribution journeys.

Contributor Mode: friendliness score grounded in real files, Nemotron AI mentor, 
issue difficulty with label evidence, PR comment draft, Contributor Journey 
Simulation with friction score.

Maintainer Mode: honest health report, missing labels, draft CONTRIBUTING.md.

Compare Mode: paste two repos, Nemotron picks which to contribute to first.

## Project Links
- **YouTube Demo:** https://www.youtube.com/watch?v=OCgRuW_LBfg
- **Blog Post:** https://medium.com/@nimeghalakrishnaofc/building-contriblens-reducing-open-source-onboarding-friction-with-nvidia-nemotron-891e14b3716f?postPublishedType=repub
- **LinkedIn Post:** https://www.linkedin.com/feed/update/urn:li:activity:7464769845113405440/
- **Github:** https://github.com/nimeghala45/ContribLens

## Architecture
<img width="800" height="1200" alt="image" src="https://github.com/user-attachments/assets/81e0b16a-e676-479c-bb02-e8d628d5727b" />

## How it uses Nemotron-3-Super
Nemotron 3 Super's long-context reasoning allows ContribLens to pass the full 
repository context in a single prompt and get grounded recommendations back.
All outputs show exactly what data Nemotron received.

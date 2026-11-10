# Safety Incident Analyst (by Frontline)

Your AI safety advisor. Upload your incident logs, SafetyCulture exports or any safety data and find out exactly where to focus next, backed by your own numbers. Works in Claude Cowork, Claude Code and the Claude apps.

## What it does

- **Tells you where to focus**: the top 3 issues, the evidence, why they matter and the next action for each
- **Finds the patterns**: hotspots by site, area, shift, task and equipment, repeat events and root cause themes
- **Weights severity, not just count**: high-potential near misses outrank piles of first aids
- **Spots early warning signs**: rising near misses, quiet reporting, clustering overdue actions
- **Gives you a plan**: a 30-60-90 day plan with owners and lead indicators to prove it worked
- **Industry briefings**: ask "what are the most common safety issues in manufacturing?" and get the frequent and the serious risks, critical controls and lead indicators

Supports model WHS laws (AU), WorkSafe Victoria, WorkSafe NZ, US OSHA and UK HSE.

## What you get in v2

- **Real deliverables, not just chat**: a live Excel workbook (formulas, dropdowns, traffic lights), clean charts, and for executives or boards a document you can circulate
- **Numbers you can defend**: every rate calculated in code with the right convention for your jurisdiction (AU/NZ per 1,000,000 hours, US per 200,000 hours)
- **Legal checks built in**: notifiable incident tests and terminology for Australian WHS laws, Victoria, New Zealand, US OSHA and UK RIDDOR
- **Expert reference packs**: fatal risks, critical controls and lead indicators for 12 industries, plus risk and investigation methods

## Try it

Install the plugin, then say "Analyse my incident data and tell me where to focus" and upload your log or SafetyCulture export. Or ask "What are the most common safety issues in warehousing?"

## Make it live

Connect Frontline to watch your data continuously, flag hotspots early and chase overdue actions: https://getfrontline.io

## Privacy

This plugin runs entirely inside your own Claude session. It does not send, store or retain your data anywhere. Privacy policy: https://getfrontline.io/privacy

## Disclaimer

Outputs are advice based on the data provided, not legal advice. Check against your own records and current legislation, and use competent judgement before acting.

## What this plugin runs

The skill includes three readable Python helper scripts in `skills/safety-agent/scripts/`: `incident_tools.py` (cleans and summarises the data you upload, using pandas), `charts.py` (draws charts with matplotlib) and `xlsx_builder.py` (builds the Excel output with openpyxl, and if LibreOffice is installed, runs it locally in headless mode to recalculate formulas). They work only on files in your session. They make no network calls and fetch nothing from the internet.

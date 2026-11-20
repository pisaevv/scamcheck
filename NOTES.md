# Scam check — project notes

## What it is
A tool that helps people renting a flat in Germany find out whether a listing or a "landlord" is a scam. The user gives it a listing and/or the messages with the "landlord" (screenshot or text), and the tool tells them what looks suspicious and why.

## Who it's for
Flat-seekers in Germany, especially newcomers, international students and people who don't speak German well.

## Why
Rental scams are a big problem in Berlin. A common one is advance payment: the "landlord" is abroad, there is no viewing, and they ask for the deposit or rent up front.

The key idea: platforms like ImmoScout24 already filter listings and verify landlords. But the scam often lives in the conversation with the "landlord", which happens after the listing and sometimes outside the platform, where the platform can't see it. This tool looks at the conversation.

## What's decided
- I'm building this tool.
- It's a one-day build: about 4–5 hours of building, and by the evening a working prototype that I can show in a live demo.
- I build it with Claude Code: I make the decisions, the agents write the code. I'm a beginner coder.

## What I have
- No real scam examples yet; I'll write test examples based on known scam patterns.
- No access to ImmoScout24 data or API.
- No Nebius account or API key yet.
- Anthropic API credits (about $47). No OpenAI key.

## What's open
- What exactly the tool checks and how.
- Which AI model provider to use (Nebius Token Factory is one option).
- Interface: web page, Telegram bot, or something else.
- Whether to use outside services (e.g. reverse image search).

# 100Hires Portfolio Project

## Tools Installed

- **Cursor IDE** — AI-powered code editor (https://cursor.com/)
- **Claude (Sonnet 4.6)** — AI model by Anthropic, available built-in in Cursor
- **Codex 5.3** — AI model by OpenAI, available built-in in Cursor
- **Git** — for version control and pushing to GitHub

## Steps Completed

1. Installed Cursor IDE and logged in to my account
2. Activated Claude (Sonnet 4.6) and Codex (5.3) models in Cursor's Settings → Models menu
3. Created a GitHub account and a public repository named `hundredhires-portfolio`
4. Cloned the repository to my local machine using Git
5. Opened the project folder in Cursor Editor
6. Created and edited this README.md file
7. Committed and pushed to GitHub

## Issues Encountered & How I Solved Them

- **Instructions asked to install "Claude Code" and "Codex" as Extensions** — After checking, the latest version of Cursor no longer uses an extension system like VS Code. Claude and Codex are now available directly as built-in models under Settings → Models. Solution: activated both models from the Models menu instead.
- **Running `cursor .` in CMD** — Initially opened the Agent Window instead of the Editor Window. Solution: clicked "Editor Window" in the top right corner to switch to the correct editor view.

---

## Task 2: Research Project — AI-Powered SEO Content Production

### What I Collected

For this task, I selected **AI-Powered SEO Content Production** as my research topic. I identified and validated 10 practitioners who actively build and ship AI-driven content systems (not just commentators), documented in `research/sources.md`.

From this pool, I collected:
- **5 YouTube video transcripts** from the most technically credible voices (Mike King / iPullRank, Authority Hacker), saved in `research/youtube-transcripts/`
- **9 LinkedIn posts** (3 each) from Mike King, Ross Hudgens, and Ryan Law, manually copied and organized in `research/linkedin-posts/`, focusing on posts backed by real data and case studies rather than generic advice

### Why I Chose These Experts

I prioritized practitioners who:
1. **Publish original data and case studies**, not recycled SEO tips (e.g. Ross Hudgens' GEO studies analyzing hundreds of real sites; Ryan Law's schema markup A/B test on 1,885 pages)
2. **Build and ship real systems**, not just write about theory (e.g. Mike King's Relevance Engineering framework and open-source agentic RAG audit tool; Ryan Law's Claude Code content automation pipeline used to publish real articles on the Ahrefs blog)
3. **Have a clear track record** in the AI search / SEO space, verified through their role, published work, and industry recognition

I intentionally avoided generic "Top 10 AI SEO Tips" creators in favor of voices that show their actual methodology, data, and results — per Alex's note that 10 high-signal sources beat 50 generic ones.

### Note on Data Collection Method

YouTube transcripts were collected using the `youtube-transcript-api` Python library via Claude/Composer in Cursor, a legal, publicly available method.

LinkedIn posts were collected **manually** (copy-pasted from publicly visible posts on each expert's profile) rather than scraped, in line with LinkedIn's Terms of Service which prohibit automated scraping.

# AI search skills

Free Claude skills for getting found and recommended by AI search.

## LinkedIn profile audit

Your profile has two readers now: the person who clicked from your post, and the AI engine
answering "who's a good X in my city?". This skill scores your profile for both (out of 50),
gives the top 3 fixes ready to paste, five headlines, and a full About rewrite.

**Claude Code**
```
/plugin marketplace add SagelynAI/ai-search-skills
/plugin install linkedin-profile-audit@ai-search-skills
```
Then: "Audit my LinkedIn profile" and attach the PDF (Profile → More → Save to PDF).

**Claude.ai (no code)**
Create a Project, paste [prompt-for-claude-projects.md](prompt-for-claude-projects.md) into its
instructions, then upload your profile PDF.

Built by [Sourav Pati](https://www.linkedin.com/in/sourav-pati-a2909228/), founder of
[Sagelyn](https://sagelyn.ai). MIT licensed.

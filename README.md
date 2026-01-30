# Claude Skills for Product Managers - Complete Library

A comprehensive collection of 12 production-ready Claude Skills designed specifically for product managers. Save 6-10 hours weekly on documentation, research synthesis, stakeholder communication, and strategic planning.

## 📦 What's Included

This library contains 12 specialized skills:

1. **PRD Writer** - Feature documentation → Save 2-3hrs per PRD
2. **User Research Synthesizer** - Interview/feedback analysis → Save 4-6hrs per synthesis
3. **Competitive Analysis** - Market intelligence → Save 2-3hrs weekly  
4. **Stakeholder Update Generator** - Executive communications → Save 90min weekly
5. **Technical Spec Writer** - Engineering documentation → Save 2-3hrs per spec
6. **A/B Test Analyzer** - Experiment evaluation → Save 1-2hrs per test
7. **OKR Planning Assistant** - Goal setting → Save 3-4hrs quarterly
8. **Product Roadmap Builder** - Strategic planning → Save 2-3hrs per roadmap
9. **Interview Question Generator** - Research design → Save 1-2hrs per guide
10. **Feature Prioritization** - Backlog management → Save 2-3hrs per session
11. **Go-to-Market Planner** - Launch strategy → Save 3-5hrs per launch
12. **Sprint Planning Assistant** - Agile workflows → Save 1-2hrs per sprint

**Total time savings: 6-10 hours weekly**

## 🚀 Quick Start

### Prerequisites

- Claude Pro, Max, Team, or Enterprise subscription
- Claude desktop application (skills don't work in web-only version)
- Basic file management comfort

### Installation (5 minutes)

1. **Download this repository**
   ```bash
   # Clone or download ZIP
   git clone https://github.com/YOUR-USERNAME/claude-skills-pm-library.git
   cd claude-skills-pm-library
   ```

2. **Locate your Claude skills directory**

   - **macOS/Linux:** `~/.claude/skills/user/`
   - **Windows:** `C:\Users\YOUR-USERNAME\.claude\skills\user\`

   If these folders don't exist, create them.

3. **Copy skills to Claude**
   ```bash
   # Copy all skills folders
   cp -r prd-writer ~/.claude/skills/user/
   cp -r user-research-synthesizer ~/.claude/skills/user/
   # ... repeat for all skills, or copy the entire directory
   ```

   Or manually copy each skill folder into the `skills/user/` directory.

4. **Restart Claude**

   Completely close and reopen Claude.

5. **Test a skill**

   Try: "Help me write a PRD for a new dashboard feature"

   If the skill is working, Claude will automatically invoke the PRD Writer and follow its methodology.

## 📖 How to Use Each Skill

### PRD Writer

**Triggers:** "write a PRD", "create product requirements", "document this feature"

**Usage example:**
```
"I need to write a PRD for a new in-app messaging feature that lets users chat with customer support."
```

The skill will ask clarifying questions, then generate a comprehensive PRD following best practices.

### User Research Synthesizer  

**Triggers:** "synthesize research", "analyze user feedback", "identify themes"

**Usage example:**
```
"Here are 10 user interview transcripts. Please synthesize the key themes and pain points."
```

[Include transcripts as attachments or paste]

### Stakeholder Update Generator

**Triggers:** "stakeholder update", "executive update", "status report"

**Usage example:**
```
"Create a weekly stakeholder update. Here's what shipped: [list]. 
Here are our metrics: [data]. We're blocked on: [issue]."
```

(Continue with examples for each skill...)

## 🎛️ Customizing Skills

All skills are designed to be customized for your specific workflow:

### Edit Instructions

Each skill has a `SKILL.md` file containing its instructions. Open in any text editor.

**Example customization:**

Original:
```markdown
Format PRDs using standard sections: Overview, User Stories, Success Metrics...
```

Your version:
```markdown
Format PRDs using OUR template: Problem Statement, Customer Impact, 
Technical Requirements, Launch Plan. Always include our standard 
disclaimer about backward compatibility.
```

### Add Your Templates

Drop your company templates into each skill folder. The skill will reference them.

### Create Variants

Copy a skill folder, rename it, and modify for different use cases:
- `stakeholder-update-executive/` for C-level
- `stakeholder-update-engineering/` for technical teams  
- `stakeholder-update-customers/` for external communications

## 🐛 Troubleshooting

**Skills not appearing?**
- Ensure you're using Claude desktop app (not just web)
- Check file permissions (skills folder needs read access)
- Verify folder structure matches exactly
- Check Claude Settings → Skills to see if they're enabled

**Skills not activating automatically?**
- Try explicitly: "Use the PRD Writer skill to..."
- Check Code Execution is enabled in Claude settings
- Review the skill's `SKILL.md` for trigger keywords

**Skill gives unexpected results?**
- Skills improve with specific context
- Provide more detail about your product/market
- Edit the SKILL.md to include your context
- Share examples of good outputs you want

**Still stuck?**
- Open an issue on GitHub
- Comment on the original Medium article
- Check for updates to this README

## 💡 Pro Tips

1. **Start with context:** Give Claude background about your product before using skills
2. **Use examples:** Upload examples of good outputs you want to match
3. **Combine skills:** Use multiple skills in sequence for complex workflows
4. **Iterate:** First outputs won't be perfect - refine the skill based on usage
5. **Share feedback:** Help improve these skills by reporting issues or suggestions

## 🤝 Contributing

Found a bug? Have an improvement? Want to add a skill?

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/amazing-skill`)
3. Commit your changes (`git commit -m 'Add amazing skill'`)
4. Push to the branch (`git push origin feature/amazing-skill`)
5. Open a Pull Request

## 📝 Version History

- **v1.0.0** (Jan 2026) - Initial release with 12 core PM skills

## 📄 License

MIT License - Use freely, modify as needed, share with your team.

## 🙏 Acknowledgments

Built by the Product AI community. Special thanks to all the PMs who shared feedback on what skills would be most valuable.

## 💬 Community & Support

- **Questions:** Open a GitHub issue
- **Updates:** Star this repo to get notified of new skills
- **Discussion:** Comment on the [Medium article](YOUR-MEDIUM-ARTICLE-LINK)
- **Newsletter:** [Subscribe for weekly AI tools for PMs](YOUR-CONVERTKIT-LINK)

## ☕ Support This Work

If these skills save you time:
- ⭐ Star this repository
- 🔗 Share on Twitter/LinkedIn
- ☕ [Buy me a coffee](https://buymeacoffee.com/your-handle)
- 💬 Share how you're using them

---

**Made with ❤️ by PMs, for PMs**

*Last updated: January 2026*

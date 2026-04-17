# Contributing to Pitch Deck Builder

Thanks for your interest in improving Pitch Deck Builder! This document provides guidelines and instructions for contributing.

## 📋 Types of Contributions

### Documentation Improvements
- Clarifying or expanding existing guides
- Adding examples to reference materials
- Fixing typos or grammatical issues
- Improving organization and structure

### New Narrative Frameworks
- New storytelling structures for different pitch types
- Novel narrative opening or closing strategies
- Additional persuasion techniques
- Industry-specific narrative patterns

### Design Enhancements
- New color strategies or palettes
- Additional chart type examples
- Design patterns for specific industries
- Accessibility improvements

### Technical Improvements
- Better workflow documentation
- New tools or library integrations
- Context management optimizations
- Testing frameworks

## 🛠️ How to Contribute

### 1. Fork and Clone
```bash
git clone https://github.com/yourusername/pitch-deck-builder.git
cd pitch-deck-builder
```

### 2. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
# or for bug fixes:
git checkout -b fix/issue-description
```

### 3. Make Your Changes

**For documentation changes:**
- Keep tone professional but conversational
- Use concrete examples throughout
- Cross-reference related sections
- Include before/after examples when applicable

**For new frameworks:**
- Include the complete framework structure
- Provide 2-3 real-world pitch examples
- Explain when to use and when to avoid
- Add to the narrative frameworks reference file

**For design changes:**
- Include visual examples or screenshots
- Explain the design reasoning
- Test for accessibility (colorblind-friendly)
- Update any related guidelines

### 4. Update References
- Update relevant reference files
- Add cross-references in SKILL.md if applicable
- Update README if adding major new features
- Include yourself in contributors list if making substantial changes

### 5. Write Clear Commit Messages
```
[Type] Brief description (50 chars max)

Longer explanation of what and why (72 chars per line)
- Bullet points work well
- Explain the problem being solved
- Reference any related issues
```

**Commit types:**
- `docs:` Documentation changes
- `feat:` New feature or narrative framework
- `fix:` Bug fix
- `refactor:` Code/documentation reorganization
- `style:` Formatting or style changes

### 6. Submit a Pull Request

**PR Title Format:**
```
[Type] Brief description
```

**PR Description:**
```markdown
## What does this change?
Brief explanation of what you're improving.

## Why?
Why this change is important or valuable.

## Example or Testing
Show how this works with an example or test case.

## Related Issues
Fixes #123
Related to #456
```

## 📖 Documentation Standards

### Voice and Tone
- Professional but approachable
- Direct and clear
- Action-oriented
- Use second person ("you," "your")

### Structure
- Start with a clear purpose statement
- Use headings to organize
- Provide examples for complex concepts
- End with checklist or summary when applicable

### Examples
All guidance should include concrete examples:
- ✅ Good: "Use assertive slide titles like 'We're Growing 40% Monthly' not generic labels like 'Traction'"
- ❌ Bad: "Use better slide titles"

### Code Blocks
```markdown
Use triple backticks with language specification
```
Choose monospace for technical terms: `SKILL.md`

## 🎨 Design Guidelines

### Visual Examples
- Include before/after comparisons
- Use realistic pitch deck examples
- Show both good and poor examples
- Explain the visual reasoning

### Color Examples
- Always test with colorblind simulation
- Include hex codes: `#FF6B6B`
- Test WCAG contrast ratios
- Provide colorblind-friendly alternatives

### Charts
- Include both the chart image and description
- Explain when to use each chart type
- Show common mistakes and fixes
- Provide data-to-visualization guidance

## ✅ Quality Checklist

Before submitting, ensure:

### Content
- [ ] No spelling or grammar errors
- [ ] Consistent terminology throughout
- [ ] Examples are realistic and relevant
- [ ] Links work (if included)
- [ ] Code examples are tested

### Structure
- [ ] Headings are logical and hierarchical
- [ ] Related content is cross-referenced
- [ ] New sections are added to table of contents
- [ ] Formatting is consistent with existing docs

### Accessibility
- [ ] Color examples work for colorblind users
- [ ] Images have descriptive alt text
- [ ] Charts have clear labels and legends
- [ ] Text has sufficient contrast

### Integration
- [ ] Changes don't conflict with existing material
- [ ] Updates related documentation
- [ ] Follows existing style and voice
- [ ] Aligns with project goals

## 🚫 What NOT to Contribute

We cannot accept:
- Contributions promoting specific commercial products (unless educational)
- Unverified or unsourced claims about market data
- Copyrighted pitch deck examples without permission
- Generic business advice without context to pitch decks
- Self-promotional content

## 📅 Review Process

1. **Initial Review** (1-3 days)
   - Maintainers review for alignment with project goals
   - Feedback on structure and content

2. **Revision** (as needed)
   - Address feedback
   - Iterate on examples
   - Ensure quality standards

3. **Final Approval** (1-2 days)
   - Final quality check
   - Merge to main branch
   - Include in next release notes

## 🏆 Recognition

We recognize contributors in:
- CONTRIBUTORS.md file
- Release notes for substantial changes
- Special acknowledgment for major frameworks or guides

## 📞 Questions?

- Open an issue for discussion
- Include `[QUESTION]` in the title
- Ask before starting major work
- We're here to help!

## 📄 License

By contributing, you agree that your contributions are licensed under the MIT License (same as the project).

---

Thank you for helping make Pitch Deck Builder better! 🎉

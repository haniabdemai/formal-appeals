# formal-appeals

**A complete working method for appeals, reconsiderations and formal
complaints to institutions (customer service departments, insurers,
banks, councils, tax authorities, employers, benefits agencies),
packaged as a skill an AI assistant can
follow end to end.**

Template letters are everywhere and lose. This is different: a method
distilled from real appeals where every rule was earned through a
rejected draft. It covers the parts the templates skip:

- **Evidence verification before a single sentence**: read original
  sources, verify every number against its source document, check that
  "sent" emails were actually sent.
- **Conclusion-first structure**: the ask up front, numbered grounds, a
  dated timeline with verbatim quotes, then the ask again.
- **A rejected-vs-shipped wording table**: real before/after pairs with
  the reason each "before" failed (combative, apologetic, AI-sounding,
  vague).
- **Register and tone rules**: legal-document subheadings, connector
  words, the one-candid-line principle.
- **Print-ready document packs**: contents page with dot leaders,
  whole-bundle page numbering, emails in print style, built with
  reportlab/pypdf/img2pdf.
- **Iteration discipline**: versioned filenames, adversarial review by
  two independent reviewer lenses before anything is declared done.

## Use it

Drop the skill into Claude Code (or hand SKILL.md to any capable
assistant) and ask for help with your appeal:

```bash
git clone https://github.com/haniabdemai/formal-appeals
cp -r formal-appeals ~/.claude/skills/formal-appeals
```

(Skills are folders of instructions Claude Code loads on demand; see
[Anthropic's Agent Skills docs](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview).
The folder name must stay `formal-appeals` to match the skill's name.)

The assistant should follow the file's order strictly: the sequencing
(verify evidence → agree the point → structure → wording → pack → review)
is the method.

*This is a writing method, not legal advice. For high-stakes matters,
involve a qualified adviser.*

## Licence

[MIT](LICENSE)

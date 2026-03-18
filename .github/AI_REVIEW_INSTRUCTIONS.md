# AI Review Instructions for Pull Requests

Use these prompts with GitHub Copilot (or another AI) to review .md files in pull requests for content suitability and Arabic language quality.

## General Guidelines
- Focus on .md and .mdx files in the `docs/` folder
- Ensure content is educational and appropriate for programming learners
- Check for proper Arabic grammar, spelling, and terminology
- Flag any English technical terms that should be translated to Arabic

## Specific Prompts

### Content Suitability Check
```
Review this Arabic markdown content for a programming education site. Check if:
- The content is suitable for learners (clear, educational, not offensive)
- Technical concepts are explained properly
- Code examples are correct and relevant
- Links and references are valid
- Content aligns with teaching programming in Arabic

Content to review:
[PASTE THE .MD CONTENT HERE]
```

### Arabic Language Quality Check
```
Analyze this Arabic text for language quality in an educational context:
- Check grammar, spelling, and punctuation
- Ensure technical terms use proper Arabic translations (e.g., "endpoint" → "نقطة نهاية", "VPN" → "شبكة خاصة افتراضية")
- Verify readability and clarity for Arabic-speaking learners
- Suggest improvements for better Arabic expression

Text to analyze:
[PASTE THE .MD CONTENT HERE]
```

### English Terms Detection
```
Scan this Arabic markdown for English technical terms that should be translated:
- Common terms to flag: endpoint, VPN, API, database, server, client, etc.
- Suggest Arabic equivalents
- Ensure the translation fits the context

Content:
[PASTE THE .MD CONTENT HERE]
```

## Usage in PRs
- When reviewing a PR, copy the changed .md content
- Paste into the prompts above
- Use Copilot's chat or inline suggestions to get feedback
- Add review comments based on the AI's suggestions

## Note
This is for manual review since automated AI integration in CI requires API access (e.g., OpenAI), which Copilot doesn't provide publicly.
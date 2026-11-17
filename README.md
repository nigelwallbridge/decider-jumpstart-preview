# The Decider — Jumpstart design preview

A standalone, interactive presentation of Design Brief 3: From Calculator to Conversation.

**This is a design demonstration, not a working Decider calculator.** No engine, MCP service, authentication or production website is connected. The emotional mappings are illustrative, not validated psychological measurements or the approved spreadsheet conversion scheme.

## Explore

Open the GitHub Pages address for this repository. Choose the dress example, select an answer, and open the four possible outcomes. Change wearing frequency, regret or liking. Suggested numerical interpretations can be inspected and edited. The house-sale example uses numerical financial assumptions instead. Phone and Desktop views are available through the presentation selector.

The presentation works without a ChatGPT account or connector. Browser scripting is needed for the interactive screens. AI assistants that only fetch page text may not render the interactions; ask them to open the page in a browser, or supply screenshots for visual feedback.

## What the demonstration does

- Opens with “What do you want to decide?” and a question box.
- Provides two predefined examples; it does not generate models for arbitrary questions.
- Shows Buy/Leave against Love wearing it/Hardly wear it.
- Updates descriptions and visual emphasis when answers change, without claiming a calculated recommendation.
- Makes all six illustrative emotional inputs inspectable and editable.
- Shows Accept/Wait against Strong/Weak market, including offer revisions.

Example mappings: liking → enjoyment 2 / 7 / 13 / 20; wearing frequency → illustrative scenario likelihood 5 / 30 / 65 / 90%; regret → 0 / −5 / −12. Fixed starting suggestions: disappointment −6, relief +3, emotional reserves 15. Frequency is only a provisional proxy for probability. These mappings are for interface exploration only.

## Files and updates

- `index.html`: self-contained standalone export, including presentation navigation and browser-local state support.
- `presentation-source.html`: editable original presentation fragment.
- `.nojekyll`: serves the files without a site generator.

Ask Codex to update **this preview repository only**, preserving existing Decider deployments. Edit `presentation-source.html`, regenerate `index.html` with the visualization standalone exporter, test both examples and screen layouts, and commit the updated files to `main`. GitHub Pages republishes automatically; the URL stays the same.

Publishing source: `main`, repository root. No custom domain, build dependencies, paid hosting or server-side service is required. Existing production repositories and deployments are separate.

To undo a design update, revert its commit in this repository and allow Pages to republish.


# How to Use CCBL in Your Project

This guide walks you through adding CCBL to your own software project.

## Step 1: Copy the License Text

Copy the CCBL 1.7 license text from one of these sources:

- **This repository**: The `LICENSE` file in the root directory (pure text)
- **[ccbl.cc](https://ccbl.cc)**: Formatted version with better readability

## Step 2: Add the License to Your Project

Create a file named `LICENSE` (no extension) in your project's root directory. Paste the license text.

### Replace the placeholders:

Copyright (c) [year] [copyright holder name]
**Example**:
Copyright (c) 2026 Zhang San


## Step 3: (Recommended) Add the AI Policy File

Create a file named `AI_POLICY.md` in your project's root directory. Copy the content from [AI_POLICY.md](./AI_POLICY.md) in this repository.

This file clarifies your stance on AI training and scraping, and is incorporated into the license by reference.

## Step 4: Add a License Summary to Your README

Add a clear, scannable summary to your project's `README.md`. Users need to understand their rights at a glance.

**Recommended template**:

## License

This project is licensed under [CCBL 1.7](./LICENSE) (Contribution-Commercial-Benevolent License).

| Your Use Case | Do You Need to Pay? |
| :--- | :--- |
| Personal learning, research, hobby | ✅ Free |
| Company use (employees) | ❌ Need commercial license (QC status is personal and does NOT cover your company) OR become a contributor for your own use |
| Integrating into commercial product | ❌ Need commercial license OR become a contributor for your own use |
| Submitted a PR/Issue that was accepted | ✅ Free commercial use for you personally (permanent) |

**To get free commercial use**: Submit a Pull Request or valid Issue. Once a maintainer **explicitly accepts or merges** it, you become a Qualified Contributor with perpetual free commercial use. Note: this right is **personal** and does not extend to your employer or organization.

📄 [Full License Text](./LICENSE) | 🤖 [AI Policy](./AI_POLICY.md)

## Step 5: Set Up Contribution Guidelines

Create a CONTRIBUTING.md file in your project root to explain how contributions work under CCBL.

**Recommended template**:

```markdown
# Contributing to [Your Project Name]

## Contribution Reward

By submitting a Pull Request or Issue that a maintainer explicitly accepts or merges, you will receive **perpetual free commercial use** of this software. This applies to **you personally** and does **not** extend to your employer or organization.

## Contribution Terms

Submitting any contribution means you have read and agree to the CCBL Contribution Terms (Section 0.7 of the [LICENSE](./LICENSE)), which includes a copyright license, a patent grant, and a warranty that you have the right to make the contribution (including any required employer consent).

## How to Contribute

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Open a Pull Request
5. Wait for review — a maintainer must **explicitly accept or merge** your submission for it to count as a Valid Contribution (silence or inaction does not automatically count as acceptance)

## Questions?

Open an Issue or contact the maintainers.
```

## Step 6: (Optional) Create a PR Template

Create `.github/pull_request_template.md` to remind contributors of the terms:

```markdown
## Contributor Confirmation

- [ ] I have read and agree to the [CCBL License](./LICENSE) Contribution Terms (Section 0.7), including the copyright and patent grants.
- [ ] If my contribution relates to my employer's business, I confirm I have the right to make this contribution (e.g., employer consent or it is outside the employer's claim).

## Change Description

...

## Related Issues

...
```

## Step 7: Decide on Commercial Licensing

If you plan to sell commercial licenses, add information to your project's website or README:

```markdown
## Commercial Licensing

If you need to use this software commercially but have not made a contribution, please purchase a commercial license.

**Contact**: commercial@yourproject.com
```

## Step 8: Set Up Donation Reporting (CCBL Section 6)

If you sell commercial licenses, the copyright holder pledges to publish an annual donation report by March 31 each year. Note that this pledge is a **non-enforceable good-faith statement** — it does not create enforceable obligations.

**Recommended approach**: Add a section to your README or website:

```markdown
## Donation Report (CCBL Section 6)

[year] Net Commercial License Revenue: $XX,XXX
Donated (1%): $XXX to [Foundation Name]
Transaction proof: [link]

If you have not sold any commercial licenses, you can state: "No commercial license revenue this year."
```

## Example Project Structure

```markdown
your-project/
├── LICENSE                 # CCBL 1.7 (pure text)
├── AI_POLICY.md            # AI policy (optional but recommended)
├── README.md               # Contains license summary
├── CONTRIBUTING.md         # Contribution guidelines
└── .github/
    └── pull_request_template.md
```

## Common Mistakes to Avoid

| ❌ Don't Do This	| ✅ Do This Instead |
| :--- | :--- |
|Modify the CCBL license text	| Use the exact text, only change placeholders |
|Remove the copyright notice	| Keep all notices intact |
|Forget to add AI_POLICY.md	| Include it if you want AI protection |
|Assume all users read the full license	| Add a summary table to README |
|Assume silence = acceptance of contributions	| Explicitly accept or merge submissions; silence does not automatically make them Valid Contributions |
|Let QC status cover a whole company	| Remember QC status is personal and does not extend to organizations |

## Getting Help

License questions: Open an issue in ccbl-license/ccbl-license

Using CCBL in your project: The FAQ (FAQ.md) covers most common questions

Legal advice: CCBL is not legal advice. Consult an attorney for specific legal concerns.

Official website: [ccbl.cc](https://ccbl.cc)

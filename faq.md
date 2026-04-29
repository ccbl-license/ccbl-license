# CCBL Frequently Asked Questions

## General Questions

### Q1: What is CCBL?

CCBL (Contribution-Commercial-Benevolent License) is a source-available license designed for independent developers and commercial open source projects. Its core principle: **personal use is free, commercial use requires payment or contribution, and contributors get perpetual free commercial use.**

### Q2: How is CCBL different from MIT, GPL, or BSL?

| License | Core Principle | Best For |
| :--- | :--- | :--- |
| MIT | Do whatever you want, keep the notice | Libraries, tools, maximum adoption |
| GPL | Use freely, but modifications must be open source | Free software, preventing proprietary forks |
| BSL | Source available, production use requires payment | Commercial software, preventing cloud SaaS |
| **CCBL** | **Personal free, company pays or contributes, contributors get free** | **Independent devs who want both community and revenue** |

### Q3: Is CCBL an open source license?

CCBL is **source-available**, not OSI-approved open source. It restricts commercial use without contribution or payment, which does not meet the Open Source Definition. However, it offers more freedom than closed source and more protection than traditional open source licenses.

## Using CCBL

### Q4: How do I use CCBL in my project?

1. Copy the `LICENSE` file from this repository (or [ccbl.cc](https://ccbl.cc)) into your project root
2. Replace `[year]` and `[copyright holder name]` with your information
3. (Optional) Add `AI_POLICY.md` to your project root
4. Add a license summary to your `README.md` (see [guide.md](./guide.md))

### Q5: Do I need to register or pay to use CCBL?

No. CCBL is free to use for licensing your own software. You only need to charge others for commercial use of **your software** if that's your business model.

## For Users of CCBL-Licensed Software

### Q6: Can I use CCBL software for personal learning?

Yes. Non-commercial use (personal study, research, hobby projects) is always free.

### Q7: Can I use CCBL software at work (company use)?

It depends:

- If you or your company has submitted a Valid Contribution (PR/Issue that was accepted), you get **free commercial use**.
- Otherwise, you need to **purchase a commercial license** from the copyright holder.

### Q8: How do I become a Qualified Contributor?

Submit a Pull Request or Issue that gets accepted. If it's not marked as "invalid", "spam", or "malicious" within 30 days, you automatically become a Qualified Contributor. This status is **perpetual** and applies to you (and your company, if you contributed as an employee).

### Q9: What counts as a "Valid Contribution"?

- A merged Pull Request (any code size)
- An Issue labeled as "accepted", "confirmed", "bug", or "enhancement"
- An adopted suggestion or documentation improvement

Trivial fixes (typos, formatting, auto-generated code) may be marked as "invalid" at the maintainer's discretion.

### Q10: Once I'm a Qualified Contributor, do I need to keep contributing?

No. The status is **perpetual**. One accepted contribution gives you lifetime free commercial use.

## Commercial Use

### Q11: How much does a commercial license cost?

Pricing is determined by each project's copyright holder. Check the project's website or contact them directly.

### Q12: Can I modify and distribute CCBL software?

Yes, but with restrictions:

- Modifications must be distributed in **source code form**
- You must retain all license and copyright notices
- You cannot use the original project's name/trademark in commercial activities without permission
- You cannot provide it as a public SaaS without a commercial license

### Q13: Can I use CCBL software as a SaaS?

Not without a commercial license. Public SaaS distribution is prohibited unless you have purchased a commercial license.

## AI Policy

### Q14: Can AI companies train models on CCBL code?

Not for commercial purposes without permission. CCBL explicitly prohibits commercial AI training and scraping. Personal research and academic use are allowed.

### Q15: How can you prove my AI was trained on CCBL code?

The copyright holder may embed unique, non-functional watermarks in the source code. If those watermarks appear in AI-generated output, they can be used as evidence.

## Donation

### Q16: What is the 1% donation pledge?

The copyright holder of CCBL-licensed software pledges to donate at least 1% of their annual net commercial license revenue to a designated open source foundation. This is a good-faith commitment, not a legally enforceable obligation.

### Q17: Where can I see donation reports?

Donation reports are published annually by March 31 on the project's official website or repository.

## Legal

### Q18: What law governs CCBL?

The laws of the jurisdiction where the copyright holder primarily resides or has their principal place of business.

### Q19: Can I use a past version of CCBL?

Yes. Projects may continue to use any past version. There is no requirement to upgrade.

### Q20: Who maintains CCBL?

CCBL is maintained by the CCBL community. The authoritative source is [github.com/ccbl-license/ccbl-license](https://github.com/ccbl-license/ccbl-license). For specific projects using CCBL, contact that project's copyright holder.

---

*Still have questions? Open an issue on [GitHub](https://github.com/ccbl-license/ccbl-license/issues) or visit [ccbl.cc](https://ccbl.cc)*

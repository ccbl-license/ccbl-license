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

- If **you personally** have submitted a Valid Contribution (a PR/Issue that a maintainer explicitly accepted or merged), you qualify for **free commercial use** — but this right is **personal** and does **not** extend to your company or employer. Your organization must obtain its own commercial license.
- Otherwise, you or your company needs to **purchase a commercial license** from the copyright holder.

### Q8: How do I become a Qualified Contributor?

Submit a Pull Request or Issue that a maintainer **explicitly accepts or merges**. Qualified Contributor status is **perpetual** and **personal** — it applies to you as an individual and does **not** extend to your employer or organization.

### Q9: What counts as a "Valid Contribution"?

- A merged Pull Request (any code size)
- An Issue explicitly labeled as "accepted", "confirmed", "bug", or "enhancement" by a maintainer
- An optimization suggestion or documentation improvement that a maintainer explicitly confirms as adopted in writing

Trivial fixes (typos, formatting, auto-generated code) may be marked as "invalid" at the maintainer's discretion. Note: silence or inaction by maintainers does **not** automatically count as acceptance — submissions must be explicitly accepted or merged.

### Q10: Once I'm a Qualified Contributor, do I need to keep contributing?

No. The status is **perpetual**. One accepted contribution gives you lifetime free commercial use (for your own use).

## Commercial Use

### Q11: How much does a commercial license cost?

Pricing is determined by each project's copyright holder. The scope, term, and pricing are set forth in a separate agreement between the copyright holder and the licensee, and are not governed by the CCBL License itself. Check the project's website or contact them directly.

### Q12: Can I modify and distribute CCBL software?

Yes, but with restrictions:

- Modifications may be distributed in **source code and/or binary form** (binary-only distributions must make the corresponding source available to recipients)
- You must retain all license and copyright notices
- You cannot use the original project's name/trademark in commercial activities without permission
- You cannot provide it as a hosted SaaS service to any third party without a commercial license

### Q13: Can I use CCBL software as a SaaS?

Not without a commercial license. Providing the Software as a hosted service to **any third party** — whether publicly over the internet or internally to specific customers — is prohibited unless you have purchased a commercial license.

## AI Policy

### Q14: Can AI companies train models on CCBL code?

Not for commercial purposes without permission. CCBL explicitly prohibits commercial AI training and scraping. Personal research and academic use are allowed. However, if a model produced through non-commercial AI training is later used commercially, that commercial use still requires satisfying Section 3.

### Q15: How can you prove my AI was trained on CCBL code?

The copyright holder may embed unique, non-functional watermarks in the source code. If those watermarks appear in AI-generated output, they can be used as evidence.

## Donation

### Q16: What is the 1% donation pledge?

The copyright holder of CCBL-licensed software pledges to donate at least 1% of their annual net revenue from commercial licenses to a designated open source foundation. This is a good-faith commitment and is **not** a legally enforceable obligation — no party may bring a claim for non-performance.

### Q17: Which open source foundations are eligible?

The copyright holder designates the recipient foundation. Eligible foundations should be legally registered non-profit organizations whose mission includes supporting open source software development, and that are not controlled by or affiliated with the copyright holder. Examples of qualifying foundations include (non-exhaustive):

- Apache Software Foundation
- Cloud Native Computing Foundation (CNCF)
- Eclipse Foundation
- Free Software Foundation (FSF)
- OpenAtom Foundation (开放原子开源基金会)
- Kaiyuanshe (开源社)

The copyright holder may update the designated list periodically. The current list is published in the project's official repository or website.

### Q18: Where can I see donation reports?

Donation reports are published annually by March 31 on the project's official website or repository.

## Legal

### Q19: What law governs CCBL?

The laws of the jurisdiction where the copyright holder primarily resides or has their principal place of business. Disputes are first resolved via written notice and good-faith negotiation; if unresolved after 60 days, they go to the courts of that jurisdiction.

### Q20: What happens if I violate the license?

Your rights terminate automatically upon violation. However, if the violation is curable, you have **60 days** after receiving written notice to cure it, after which your rights are reinstated.

### Q21: Does CCBL include a patent grant?

Yes. Section 11 grants users a patent license for the unmodified Software. Section 0.6(b) also requires contributors to grant a patent license for their contributions. Initiating patent litigation against the copyright holder or a contributor terminates your patent license.

### Q22: Can I use a past version of CCBL?

Yes. Projects may continue to use any past version. There is no requirement to upgrade. Later versions of CCBL may not diminish the substantive rights already granted under the version you received.

### Q23: What happens if a license provision is invalid?

Section 12 (Severability) provides that if any provision is held invalid or unenforceable, it will be modified to the minimum extent necessary to make it valid, and the remaining provisions stay in full effect. The License also constitutes the entire agreement regarding use of the Software.

### Q24: Who maintains CCBL?

CCBL is developed & maintained by [Ignotus Labs](https://github.com/ignotuslabs). The authoritative source is [github.com/ccbl-license/ccbl-license](https://github.com/ccbl-license/ccbl-license). For specific projects using CCBL, contact that project's copyright holder.

---

*Still have questions? Open an issue on [GitHub](https://github.com/ccbl-license/ccbl-license/issues) or visit [ccbl.cc](https://ccbl.cc)*

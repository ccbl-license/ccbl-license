# Contributing to CCBL

Thank you for your interest in contributing to the Contribution-Commercial-Benevolent License (CCBL). This document provides guidelines for contributing to this repository, which contains the license text, policies, and official documentation.

**Affiliation**: CCBL is an official license developed & maintained by [Ignotus Labs](https://github.com/ignotuslabs). This repository (`ccbl-license/ccbl-license`) is hosted under the independent `ccbl-license` GitHub organization for neutrality and focus of concerns, but contributions are governed by Ignotus Labs.

## Scope of This Repository

This repository hosts:
- The canonical CCBL license text (`LICENSE`)
- The AI Policy (`AI_POLICY.md`)
- Official documentation (`README.md`, `FAQ.md`, `guide.md`, `adopters.md`)
- Version archives (`/versions/`)

**Important**: This repository does NOT host any software projects that use CCBL. For contributions to a project that uses CCBL, please refer to that project's own contribution guidelines.

## Ways to Contribute

### 1. Report Issues

If you find:
- Typos, grammatical errors, or formatting problems in the license or documentation
- Ambiguities or contradictions in the license text
- Missing content or outdated information

Please open a [GitHub Issue](https://github.com/ccbl-license/ccbl-license/issues) with clear description and, if possible, a suggested fix.

### 2. Suggest Improvements

For proposed changes to the license text, documentation, or policies:

- **Minor changes** (typos, clarifications, formatting): Open a Pull Request directly.
- **Major changes** (rewording definitions, adding new clauses, changing policy direction): Open an Issue first to discuss the change. This ensures alignment before significant work is done.

### 3. Add Your Project to Adopters

If your project uses CCBL, add it to [`adopters.md`](./adopters.md). See instructions in that file.

### 4. Translate the License

CCBL is available in English (authoritative) and Chinese. To contribute translations to other languages, please open an Issue to coordinate.

## Contribution Process

### Opening an Issue

1. Go to [Issues](https://github.com/ccbl-license/ccbl-license/issues)
2. Click "New Issue"
3. Choose a template (if available) or write a clear title and description
4. Label appropriately (e.g., `bug`, `enhancement`, `question`, `translation`)
5. Submit

### Submitting a Pull Request

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/your-username/ccbl-license.git`
3. **Create a branch**: `git checkout -b fix/typo-readme`
4. **Make your changes** (follow the guidelines below)
5. **Commit** with clear message: `git commit -m "Fix typo in README"`
6. **Push** to your fork: `git push origin fix/typo-readme`
7. Open a Pull Request against the `main` branch of `ccbl-license/ccbl-license`
8. Wait for review and address feedback

## Guidelines for Changes

### License Text (`LICENSE`)

- **Never change the legal meaning** without extensive discussion.
- Keep the file as **pure text** (no Markdown formatting).
- Maintain consistent indentation and line breaks.
- If you update the version number, also update:
  - The header in `LICENSE`
  - `README.md` (version badge)
  - `versions/` directory (archive previous version)
  - `guide.md` (references to CCBL 1.x)

### Documentation (`*.md`)

- Use **Markdown** with clear headings.
- Wrap lines at **80-100 characters** for readability (unless in code blocks).
- For code blocks, specify the language (e.g., ```markdown, ```bash).
- Ensure all links are valid.

### AI Policy (`AI_POLICY.md`)

- Changes must be discussed in an Issue first (due to legal implications).
- Maintain backward compatibility with existing versions (or clearly version).

### Version Archive (`/versions/`)

- When releasing a new version (e.g., 1.8):
  - Move current `LICENSE` to `/versions/CCBL-1.7.txt` (if not already)
  - Create `CCBL-1.7.md` (Markdown version) in `/versions/`
  - Update `/versions/README.md` with the new version
  - Update root `LICENSE` with new version text

## Conduct

- Be respectful and constructive.
- Assume good faith.
- This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## Getting Help

- Open an Issue for questions.
- Email the maintainers (if listed in `README.md` or on the website).

---

Thank you for helping make CCBL better!

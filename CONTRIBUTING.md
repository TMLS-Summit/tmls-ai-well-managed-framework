# Contributing to TMLS AI Well-Managed Framework

Thank you for your interest in contributing to the TMLS AI Well-Managed Framework! This framework is designed to be a vendor-neutral, community-driven standard for evaluating modern digital and AI systems.

## How to Contribute

### Types of Contributions

We welcome the following types of contributions:

1. **Pillar Content Enhancement**
   - Add principles and best practices
   - Document common failure patterns
   - Provide real-world examples and case studies
   - Add executive checklists and evaluation criteria

2. **Framework Improvements**
   - Suggest new evaluation criteria
   - Improve clarity and accessibility
   - Add cross-references between pillars
   - Propose new sections or subsections

3. **Documentation**
   - Fix typos and improve readability
   - Add diagrams and visual aids
   - Translate content to other languages
   - Create guides and tutorials

4. **Reviews and Feedback**
   - Review pull requests from other contributors
   - Provide feedback on proposed changes
   - Validate technical accuracy
   - Test evaluation criteria in real scenarios

## Contribution Process

### 1. Request Access
- Share your GitHub ID with the TMLS team to be added as a contributor.

### 2. Pick Your Pillar
- Each pillar has a dedicated folder in the repository.

### 3. Branch
- Create a branch named `pillar/[pillar-name]/[your-handle]`
```bash
git checkout -b pillar/[pillar-name]/[your-handle]
```

### 4. Make Your Contribution
- Guidance, best practice, case study, or assessment criterion.
- Follow the template in each pillar's `CONTRIBUTING.md` (if applicable) and the existing structure.
- Ensure your content is vendor-neutral and accessible to non-technical executives.

### 5. Submit a Pull Request
- Open a pull request against `master` with a clear description of what you're adding and why.
- Keep PRs focused — one idea per PR is better than one large PR.
- Your PR is your public record of contribution.

### 6. Review Cycle
- The Pillar Lead will review and may request changes. 
- PRs don't need to be perfect initially. The goal is to get expertise into the repo and iterate.

## Content Guidelines

### Vendor Neutrality
✅ **DO**: Focus on principles, patterns, and trade-offs  
✅ **DO**: Use generic examples applicable across platforms  
❌ **DON'T**: Promote specific vendors, tools, or products  
❌ **DON'T**: Include marketing language or commercial claims

### Audience Awareness
This framework serves both technical and non-technical audiences:
- **Executive Level**: Board members, C-suite, compliance officers
- **Technical Level**: Architects, engineers, security professionals

Structure content to be understood by executives while providing actionable guidance for technical teams.

### Writing Style
- **Clear**: Use plain language; avoid unnecessary jargon
- **Concise**: Be direct; every word should add value
- **Comprehensive**: Cover all aspects without being exhaustive
- **Actionable**: Provide practical guidance, not just theory

## Pillar Structure

Each pillar follows this structure:

```
pillars/XX-pillar-name/
├── README.md                  # Pillar overview
├── principles.md              # Core principles
├── evaluation-criteria.md     # Assessment checklist
├── common-failures.md         # Anti-patterns and pitfalls
└── examples/                  # Real-world case studies
    ├── example-1.md
    └── example-2.md
```

### Template Format

When adding content to a pillar, use the provided templates:

**Principle Template**:
```markdown
## [Principle Name]

**Description**: Brief explanation of the principle

**Why It Matters**: Executive-level justification

**Implementation Guidance**: Practical steps for technical teams

**Common Pitfalls**: What to avoid

**Related Pillars**: Links to related content in other pillars
```

## Review Process

1. **Automated Checks**: PRs must pass format and link validation
2. **Community Review**: At least one community member review required
3. **Maintainer Review**: Final approval from framework maintainers
4. **Merge**: Once approved, changes are merged into main

## Code of Conduct

### Our Standards
- **Respectful**: Treat all contributors with respect
- **Collaborative**: Work together constructively
- **Professional**: Maintain professional discourse
- **Inclusive**: Welcome diverse perspectives and backgrounds

### Unacceptable Behavior
- Harassment or discrimination of any kind
- Trolling, insulting, or derogatory comments
- Publishing others' private information
- Other conduct inappropriate for a professional setting

## Questions?

- **General Questions**: Open a [discussion](../../discussions)
- **Issues**: Report bugs or suggest features via [issues](../../issues)
- **Security**: Report security concerns to [security email TBD]

## Recognition

Contributors will be acknowledged in:
- CONTRIBUTORS.md file
- Release notes for significant contributions
- Community highlights (with permission)

---

**Thank you for helping build the future of technology governance!**

By contributing, you agree that your contributions will be licensed under the same license as the project.

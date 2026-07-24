# Contributing

Thank you for improving the roadmap.

## Before opening a pull request

1. Search existing issues and pull requests.
2. Keep one coherent change per pull request.
3. For a resource, follow [the curation policy](resources/curation-policy.md).
4. For an exercise/project, state prerequisites, outcome, deliverable, and evaluation.
5. Check internal links and manually open every external link you add.
6. Use clear international English and inclusive examples.

## Local checks

```bash
git diff --check
npx --yes markdownlint-cli2 "**/*.md"
npx --yes markdown-link-check README.md
```

Network link checks can produce false failures due to rate limits or bot protection.
Manually verify those links in a browser before changing/removing them.

## Pull request description

Explain what changed, why it improves a learner outcome, how it was verified, and
any resource affiliation. By contributing, you agree that your contribution is
licensed under this repository's license.

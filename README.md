# WAQueen QA Checklist

Static do-or-die QA testing page for WAQueen.

This public form is intentionally short: 16 critical tests designed for a
45-60 minute manual smoke pass. AI testing is part of the critical path.
Deep integrations/regression testing should use a separate full checklist.

## GitHub Pages

1. Create a separate repository named `waqueen-qa`.
2. Put `index.html` from this folder at the root of that repository.
3. Enable GitHub Pages from the repository settings.
4. Share this URL with QA:

```text
https://aamirmursleen.github.io/waqueen-qa/
```

## Rules

- Do not add passwords, API keys, license keys, webhook secrets, or real customer data to the public page.
- Share test credentials privately.
- Fail means the expected result did not match.
- Skip means the feature is unavailable or test data is missing.
- Every Fail needs screenshot or Loom/video evidence.
- The PDF button downloads a simple daily QA report from the current browser state.

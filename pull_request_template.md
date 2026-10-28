# Pull Request Template

## Summary
Provide a clear, concise description of the change.  
Explain what the PR does and why it is needed.

## Related Issues
List any related issues or discussions:

- Fixes #
- Closes #
- References #

## Type of Change
Select all that apply:

- [ ] Bug fix  
- [ ] New feature  
- [ ] Documentation update  
- [ ] Refactor  
- [ ] Performance improvement  
- [ ] Build / tooling change  
- [ ] Other (explain below)

## Description of Changes
Describe the technical changes you made.  
Include relevant details such as:

- New functions or modules  
- Changes to existing APIs  
- Updates to solar geometry logic  
- Formatting or parsing changes  
- Website or demo updates  

If applicable, include code snippets:

```ts
// Example snippet
const t = UmiTime.fromDate(new Date());
console.log(t.format());
```

## Breaking Changes
Does this PR introduce any breaking changes?

- [ ] Yes  
- [ ] No  

If yes, describe them clearly.

## Tests
Describe test coverage:

- What tests were added or updated  
- How to run them  
- Any edge cases covered  

Run tests:

```bash
npm test --workspace=packages/umi-time-js
```

## Documentation
If your change affects public behavior, note any documentation updates:

- [ ] Updated existing docs  
- [ ] Added new docs  
- [ ] Not applicable  

## Screenshots / Visuals (Optional)
If your change affects the website or demos, include screenshots or GIFs.

## Checklist
Before submitting, confirm:

- [ ] Code builds without errors  
- [ ] Tests pass  
- [ ] Linting passes  
- [ ] Documentation updated (if needed)  
- [ ] PR title is clear and descriptive  

## Additional Notes
Add any extra context, discussion points, or follow‑up tasks here.


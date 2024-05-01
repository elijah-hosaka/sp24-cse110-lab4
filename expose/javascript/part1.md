1. Line 9 prints `values added: 20`
2. Line 13 prints `final results: 20`
3. Line 9 prints `values added: 20`
4. Line 13 returns an error because `result` is a `let` variable which is block-scoped so it's only accessible in the if block
5. Line 9 returns an error because `result` is a `const` variable and the attempt to reassign `result` in line 7 will not be allowed
6. Line 13 returns an error for the same reason as answer 5, because we are attemptint to reassign the `const` variable `result`
## Decide whether a queued request can afford to wait

Returns [charge now, balance after immediate decision, feasible by deadline, wait]. Deferred work consumes no tokens until resubmitted. Invalid arguments and nonfinite results return an empty vector.

1. Open an empty file named `petrel-demo.blyx`.
2. Type `blyx-petrel-demo` and select **Petrel — runnable example**. You can also use **Snippets: Fill File with Snippet**.
3. Choose **Blyx: Run File** from the command palette. Change an argument near the end of `fn main()` to try another input.

Expected output

```text
0
4
1
2
```

[Work through the example in the browser](https://www.blyx-lang.space/play?example=package-petrel)

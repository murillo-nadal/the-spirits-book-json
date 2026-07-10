# The Spirits' Book — JSON Dataset

The questions and answers of *The Spirits' Book* (*O Livro dos Espíritos*) by Allan Kardec, organized as structured JSON. Public domain — use it for anything: apps, search tools, chatbots, analysis, whatever you like.

## Files

- `pt.json` — Portuguese (uses `P` / `R` for question / answer)
- `en.json` — English (uses `Q` / `A` for question / answer)

Each file is a JSON array of objects. `Id` is the original question number from the book, so entries line up across languages.

```json
{ "Id": "1", "Q": "What is God?", "A": "God is the Supreme Intelligence, the First Cause of all things." }
```

## Contributing

Contributions are welcome — **translations into other languages are especially appreciated.** Add a new file named with its language code (`fr.json`, `es.json`, ...), keep the same array-of-objects structure, and match the `Id` to the original question number so entries stay aligned.

## License

Public domain.

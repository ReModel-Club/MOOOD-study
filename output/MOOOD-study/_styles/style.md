# Style block

## Audience: `intermediate`

- **max_code_block_lines**: 100
- **max_diagram_participants**: 10
- **Reader**: an intermediate coder who understands the key concepts of the language but has never used this particular codebase.
- **Tone**: readable but not patronising. Written in British English, so it reads as if a British person wrote it.
- **Code**: simplify where it helps, but longer real excerpts are fine. Every code block is followed by an explanation.
- **Analogies**: use some for the more complex concepts, but not too many. It must not feel patronising to intermediate or advanced coders.
- **Depth**: in the internals section, explain in more depth what is happening and *why*, remembering that the reader is fairly competent but new to this repository.
- **Quarto features**: tabsets open on **Real code** first, and prefer verbatim excerpts in general. Use collapsed callouts the other way round from `beginner`: for optional *background* the reader probably already knows (e.g. "Refresher: Python descriptors"). Use code annotations for the non-obvious lines only. Give margin definitions only for project-specific terms.
- **Line highlighting** (if `code-line-style` is enabled): `hi:` for the lines the next paragraph explains, and `dim:` on boilerplate (imports, setup) so a longer real excerpt stays complete while the reader's eye goes to the point. Keep `dim` to a few blocks per chapter. No diff styles.

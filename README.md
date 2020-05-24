# Simon Cousineau's personal portfolio website.

Can be found at [simoncousineau.com](https://simoncousineau.com).

## Development

To recompile source files (includes index and 404), run:

```
pug -P _src/[!_]*.pug -o . && sass _src/main.scss ./main.css
```

To watch and recompile files on change, use:

- Pug files:
  `pug -P -w _src/[!_]*.pug -o .`
- Sass files:
  `sass --watch _src/main.scss:./main.css`

To view changes locally, use the VS Code Live Server extension. Start live server with `⌘L ⌘O`.

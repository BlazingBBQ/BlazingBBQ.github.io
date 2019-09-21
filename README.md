### Description

This is Simon Cousineau's personal portfolio website. Can be found at simoncousineau.com or at blazingbbq.github.io.

### Development

To recompile source files (includes index and 404), run:
`pug -P _src/[!_]*.pug -o . && sass _src/main.scss ./main.css`

To view changes locally, use Live Server extension. Start live server with `⌘L ⌘O`.

- Watching pug files:
  `pug -P -w _src/[!_]*.pug -o .`
- Watching sass files:
  `sass --watch _src/main.scss:./main.css`

# edge-github-dark
Edge plugin to give GitHub a dark theme. It's only been briefly tested but you should be able to side load this with Chrome as well if you don't want to use Stylish (ref: [GitHub-Dark#455](https://github.com/StylishThemes/GitHub-Dark/issues/455)).

Uses [GitHub-Dark](https://github.com/StylishThemes/GitHub-Dark) and the Monokai theme.

The three files loaded are
- [styles.css](styles.css) - the contents of GitHub-Dark with `@-moz-document regexp()` removed since it's not supported in Edge and we're specifying the urls in `manifest.json`
- [theme.css](theme.css) - the Monokai theme
- [edge.css](edge.css) - rules specific to rendering differences in Edge

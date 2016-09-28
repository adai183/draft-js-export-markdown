# This is a fork to adapt draft-js-export-markdown to megadraft

# DraftJS: Export ContentState to Markdown

This is a module for [DraftJS](https://github.com/facebook/draft-js) that will export your editor content to Markdown.

It was extracted from [React-RTE](https://react-rte.org) and placed into a separate module for more general use. Hopefully it can be helpful in your projects.

## Installation

    npm install --save megadraft-js-export-markdown

This project is still under development. If you want to help out, please open an issue to discuss or join us on [Slack](https://draftjs.slack.com/).

## How to Use

```javascript
import { stateToMarkdown } from 'megadraft-js-export-markdown'
let html = stateToMarkdown(contentState);
```

## License

This software is [ISC Licensed](/LICENSE).

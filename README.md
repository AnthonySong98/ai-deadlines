## AI Deadlines [![Build Status](https://travis-ci.com/anthonysong98/graph-ai-deadlines.svg?branch=gh-pages)](https://travis-ci.com/anthonysong98/graph-ai-deadlines)

Countdown timers to keep track of a bunch of CV/NLP/ML/RO conference deadlines.

## Contributing

Contributions are very welcome!

To keep things minimal, I'm only looking to list top-tier conferences in AI, focusing on graph-related topics. Feel free to maintain a separate fork if you don't see your sub-field or conference of interest listed.

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request

## Acknowledgement
This repository is based on [ai-deadlines](https://aideadlin.es/) website developed by @[Abhishek Das](http://abhishekdas.com/).

## License

[MIT][1]
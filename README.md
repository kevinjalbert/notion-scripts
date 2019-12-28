# This repository is ⚰️ ARCHIVED ⚰️

`notion-scripts` as an individual project has been sunsetted and merged into [`notion-toolbox`](https://github.com/kevinjalbert/notion-toolbox). In `notion-toolbox` is where this project lives on. The merge happened on December 27, 2019.

---

## Install

This package is using Python 3.

```sh
pip install git+https://github.com/kevinjalbert/notion-scripts
```

## Usage

Some quick usage is shown here:

```python
from notionscripts.notion_api import NotionApi

notion_api = NotionApi()
notion_api.current_day()
notion_api.append_to_current_day_notes("title of a note")
```

For more detailed usage I would recommend taking a look at [`alfred-notion`](https://github.com/kevinjalbert/alfred-notion) and [`notion-heroku`](https://github.com/kevinjalbert/notion-heroku).

A more completed set of features and instructions will be provided soon.

## Author

👤 **Kevin Jalbert**

* Twitter: [@KevinJalbert](https://twitter.com/KevinJalbert)
* Github: [@kevinjalbert](https://github.com/kevinjalbert)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/kevinjalbert/notion-scripts/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Kevin Jalbert](https://github.com/kevinjalbert).<br />
This project is [MIT](https://github.com/kevinjalbert/notion-scripts/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_

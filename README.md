# Sudoers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Sudoers** is bash script that helps editing **/etc/sudoers** file.

## Content

- [Content](#content)
- [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Installation

```
git clone "https://github.com/DeBos99/sudoers.git"
sudo mv sudoers /usr/bin
```

## Usage

Show help:

`sudoers --help`

Add **USER1** and **USER2** to **/etc/sudoers** file:

`sudoers --add USER1 USER2`

Delete **USER1** and **USER2** from **/etc/sudoers** file:

`sudoers --delete USER1 USER2`

Set **KEY** option to **VALUE**:

`sudoers --set-default KEY VALUE`

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## Contact

Discord: DeBos#3292

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

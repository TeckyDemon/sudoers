# Sudoers

**Sudoers** is bash script that helps editing **/etc/sudoers** file.

## Content

- [Content](#content)
- [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)
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

Set timestamp_timeout option to **TIMESTAMP**:

`sudoers --timestamp_timeout TIMESTAMP`

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

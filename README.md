# Sudoers

![Made with Bash](https://img.shields.io/badge/made%20with-bash-0.svg?color=cc2020&labelColor=ff3030&style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB2ZXJzaW9uPSIxIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIj48cGF0aCBkPSJNNTEyIDI1NmEyNTUgMjU1IDAgMCAxLTI4IDExNyAyNDkgMjQ5IDAgMCAxLTczIDg3IDI1NiAyNTYgMCAwIDEtODkgNDMgMjQ4IDI0OCAwIDAgMS0xMDYgNkEyNTMgMjUzIDAgMCAxIDI1IDM2N2EyNTYgMjU2IDAgMSAxIDQ4Ny0xMTF6IiBmaWxsPSIjZjJmMmYyIi8%2BPGcgZmlsbD0iIzJkM2EzZSI%2BPHBhdGggZD0iTTQ0NSA0MjVsLTE0NCA4MyAyMS01YzEyLTMgMjItNiAzMy0xMWw1Ni0zMmEyNTggMjU4IDAgMCAwIDQyLTQxbC04IDZ6bTctMzAyTDI5NiAzM2E3NyA3NyAwIDAgMC03NiAwTDY0IDEyM2E3NyA3NyAwIDAgMC0zOSA2N3YxNzdjMTYgMzMgMzkgNjIgNjcgODVsNzcgNDVjMTUgNSAzMSA5IDQ3IDEyTDcwIDQyNWE2NCA2NCAwIDAgMS0zMS01NVYxOTBjMC0yMyAxMi00NCAzMS01NWwxNTYtOTBhNjMgNjMgMCAwIDEgNjQgMGwxNTUgOTBhNjQgNjQgMCAwIDEgMzIgNTV2MTgwYzAgNy0xIDE1LTQgMjJsMTEtMTkgNi0xNFYxOTBjMC0yNy0xNC01My0zOC02N3oiLz48cGF0aCBkPSJNNDg0IDE5MHYxODNhMjQ5IDI0OSAwIDAgMS00NyA2NGwtMTE1IDY2YTI0OCAyNDggMCAwIDEtNzEgOWwtMi0xMVYzMjFjMC0yNSAxMy00OCAzNS02MWwxNTYtOTAgOC00YTI2IDI2IDAgMCAxIDM2IDI0eiIvPjwvZz48cGF0aCBkPSJNMzQ4IDM4NWMwLTE4LTE2LTE4LTI0LTE4cy0xMy0zLTEzLTExIDEwLTIwIDI4LTE3bDctMThzLTgtMS0xOCAxdi0xN2wtMTUgOXYxNWMtOSA2LTE3IDE5LTE3IDQxIDAgMTAgNSAyMCAyMiAyMCAxNiAwIDE3IDE1IDggMjMtOSA5LTI5IDktMjkgOWwtMiAyMHM4IDAgMTgtM3YxN2wxNS05di0xNWMxMS04IDIxLTIyIDIwLTQ3eiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGZpbGw9IiMzMWI2NDQiIGQ9Ik00MTMgNDA5bC00MyAyOXYtMTZsNDMtMjh6Ii8%2BPC9zdmc%2B)

![GitHub](https://img.shields.io/github/license/DeBos99/sudoers.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/DeBos99.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/DeBos99/sudoers.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/DeBos99/sudoers.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/DeBos99/sudoers.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/DeBos99/sudoers.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/DeBos99/sudoers.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/DeBos99/sudoers.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/DeBos99/sudoers.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/DeBos99/sudoers.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)

![GitHub issues](https://img.shields.io/github/issues-raw/DeBos99/sudoers.svg?color=cc2020&labelColor=ff3030&style=for-the-badge)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/DeBos99/sudoers.svg?color=10aa10&labelColor=30ff30&style=for-the-badge)

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

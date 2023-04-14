# Bitwarden Export Viewer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

I always have an exported bitwarden_vault.json on an encrypted USB. To view the data i made a simple HTTP-Site which list it in a nice way.
Everythinng works offline.

## Installation

To use Bitwarden Export Viewer, you'll need to clone this repository to your local machine:
```bash
git clone https://github.com/eliasthecactus/bitwarden-export-viewer.git
```

Copy the index.html now to you USB or if you want to use it localy, just copy it there.
Copy the json-vault to the same location as the index.html as data.json.



## Usage

Serve it somehow (as an example, i use python):
```bash
cd <path-to-the-files>
python -m http.server 1234
```

To start using Bitwarden Export Viewer, simply visit:
[127.0.0.1:1234](http://127.0.0.1:1234)


## Contributing

If you'd like to contribute to Bitwarden Export Viewer, please follow these steps:

1. Fork this repository to your own GitHub account
2. Create a new branch with your proposed changes: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push the branch to your fork: `git push origin my-new-feature`
5. Submit a pull request to this repository

We welcome all contributions, big or small!

## License

Bitwarden Export Viewer is licensed under the [MIT License](https://opensource.org/licenses/MIT). See [LICENSE](LICENSE) for more information.


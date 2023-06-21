# completion

[![License](https://img.shields.io/badge/license-MIT-007EC7)](/LICENSE)
[![built for](https://img.shields.io/badge/built%20for-%20%F0%9F%A6%93%20zshzoo-black)][zshzoo]

> Initialize Zsh completions

## Installation

### Install with a Zsh plugin manager

Follow the instructions for your preferred Zsh plugin manager to install as a plugin.

### Install manually, without a plugin manager

To install manually, first clone the repo:

```zsh
git clone https://github.com/zshzoo/completion ${ZDOTDIR:-~}/.zplugins/completion
```

Then, in your .zshrc, add the following line:

```zsh
source ${ZDOTDIR:-~}/.zplugins/completion/completion.zsh
```

[zshzoo]: https://github.com/zshzoo/zshzoo

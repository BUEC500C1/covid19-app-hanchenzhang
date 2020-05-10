covid19 app by hanchen zhang

Originally, the Environment Setup should follow the instruction on [link:](https://reactnative.dev/docs/environment-setup)
But for Chinese software developer, some instructions are different from what the previous link has. All details are shown [here:](https://reactnative.cn/docs/getting-started), with several noticement below.

1. The react-Native is a cross-platform developing framework based on node.js, Therefore the node version should at least be v12.

2. Homebrew can install the latest version of node.js, but the command brew install could not be directly work in China. There are necessary mirrors to update the Homebrew. Mirrors are sources from the [University of Science and Technology of China](http://mirrors.ustc.edu.cn/)

```
$ cd "$(brew --repo)"
$ git remote set-url origin https://mirrors.ustc.edu.cn/brew.git
$ cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
$ git remote set-url origin https://mirrors.ustc.edu.cn/homebrew-core.git
$ brew update
```
3. For installing the yarn that could substitute, add the sudo prefix for access approvement.
4. For further access blocked by the system, type ``sudo spctl --master-disable ``



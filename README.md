- [Karabiner](https://pqrs.org/osx/karabiner/)

  - 해피해킹 방향키 설정
    - Complex Modifications에서 Vi Style Arrows -> Control + h/j/k/l to Arrow

- [Homebrew](https://brew.sh/)

- Zsh

  - `$ brew install zsh`
  - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

- Vim

  - Copy `.vimrc` at `~/.vimrc`
  - Set up [Vundle](https://github.com/VundleVim/Vundle.vim) and install plugins

- Node and Yarn

  ```bash
  brew install n
  sudo n 20
  sudo npm install -g yarn
  ```

- .zshrc

  ```bash
  export GIT_CEILING_DIRECTORIES=$HOME
  source $HOME/.aliases
  source $HOME/.confidentials
  ```

#Template for `~/.aws/credentials`

```
[default]
aws_access_key_id =
aws_secret_access_key =
[profile_name]
aws_access_key_id =
aws_secret_access_key =
```


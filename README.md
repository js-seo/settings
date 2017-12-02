- [Karabiner](https://pqrs.org/osx/karabiner/)

  - 해피해킹 방향키 설정
    - Complex Modifications에서 Vi Style Arrows -> Control + h/j/k/l to Arrow

- [Homebrew](https://brew.sh/)

- Zsh

  - `$ brew install zsh`
  - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

- [janus](https://github.com/carlhuda/janus)

- Node and Yarn

  ```bash
  brew install nvm
  nvm install stable
  brew install yarn --without-node
  ```

- .zshrc

  ```bash
  export GIT_CEILING_DIRECTORIES=$HOME
  source $HOME/.aliases
  source $HOME/.confidentials
  ```

- Input source switcher

  - INSERT 모드에서 나갈 때 자동으로 영문모드로 바꿔줌
    ```bash
    git clone git@github.com:vovkasm/input-source-switcher.git
    cd input-source-switcher
    mkdir build
    cd build
    cmake ..
    make
    make install
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


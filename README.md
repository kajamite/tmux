Prerequisites
------------

You need to have tmux installed.
On MacOs you can use Homebrew to install tmux:

```bash
  brew install tmux
```

Installation
------------

  Download:

  ```bash
  git clone https://github.com/kajamite/tmux.git ~/.tmux
  ```

  Copy tmux config to home:

  ```bash
  ln -s ~/.tmux/tmux.conf ~/.tmux.conf
  ```

  Update config:

  ```bash
  tmux source-file ~/.tmux.conf
  ```

  Copy binary files to your bin folder (destination folder can be different on your machine) 

  ```bash
  sudo cp ~/.tmux/bin/* /bin/ 
  ```

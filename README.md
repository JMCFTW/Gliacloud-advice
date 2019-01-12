# Gliacloud-tmux-workflow

Open any project, and upgrade all requirement automatically.

## 1. Install Tmux

### Mac OS


```
brew update
brew install tmux
```

### Debian / Ubuntu

```
sudo apt-get install tmux
```

* [Tmux Tutorial](https://www.youtube.com/watch?v=nD6g-rM5Bh0&list=PLbkWnfz63JbWlZSq964DCMW64dM06_qht)
* [Tmux cheat sheet](https://gist.github.com/henrik/1967800/)
常用指令:
(a) Ctrl + F 後, 按鍵盤上下左右 (在不同的Pane中移動)
(b) Ctrl + F 後, 按d (暫時離開這個window)
(c) Ctrl + F 後, 按z (將當前Panel縮放)

## 2. Install tmuxinator

```
gem install tmuxinator
```

## 3. create a new tmuxinator project
```
tmuxinator new project_name
```

And then copy and paste [this](https://github.com/JMCFTW/Gliacloud-tmux-workflow/blob/master/tmuxinator_project_studio.txt)

tmuxinator start project_name






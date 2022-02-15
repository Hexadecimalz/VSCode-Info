# VSCode Info 
VSCode is quickly becoming one of my favorite code editors. It's flexbile and allows for lots of tools to get things done. At the same time, there are often lots of little features to learn, which are easy to forget from project to project. 

This is my collection of resource for working in VSCode and setting things up. 

## VSCode Shortcuts 
- [Toggle Zen Mode](https://techstacker.com/vscode-toggle-zen-mode/) 
  - `Control + Shift + P` 

  **👟  VSCode Shortcuts**
- Run Code: `Control + Alt + N` 
- Comment out a selection of code with `Control + /` 
- Collapse file bar `Control + B`
- Indent section `Control + ]`


## Setting up Git 
Until seeing a recent Youtube tutorial I hadn't even thought of incorporating Git and VSCode, but it makes a lot of sense. It simplified having to run a lot of commands manually. Pretty easy setup as well. 
- [Red Gate: VSCode Git Config](https://www.red-gate.com/blog/my-git-and-vscode-setup-global-git-config-extensions-and-more-video)

```
# setup in the git-bash terminal 
git config --global user.name "Username"
git config --global user.email "not-my-email@users.noreply.github.com"     
git config --global core.editor "code --wait"
git config --global merge.tool vscode
git config --globa mergetool.vscode.cmd "code --wait $MERGED"
```

## Extensions 
**Useful and worth reinstalling**
- Code Runner 
- Markdown Preview Enhanced
- Powershell
- Pylance 
- Python 
- Remote - WSL
- Ruby 

**Maybe Installations**
- erlang
- Go
- Jupyter
- Jupyter Kemap
- Jupyter Notebook Renderers
- VSCode ruby 

## Themes 
So many themes to pick from! 

- Night Owl v2.0.1 by sarah.drasner
- Abyss 

## Fonts 
Located in: File > Preferences > Settings > Commonly Used
- Default Font Faces: `Consolas, 'Courier New', Monospace` 
- What I use: `Roboto Mono, Roboto Mono, Monospace`

## Links 
- [VSCode Crash Course by Free Code Camp](https://www.youtube.com/watch?v=WPqXP_kLzpo)
- [25 VSCode Productivity Tips and Speed Hacks](https://www.youtube.com/watch?v=ifTF3ags0XI)
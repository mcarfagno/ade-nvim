# ade-nvim

Use neovim inside a Autoware's [ADE](https://ade-cli.readthedocs.io/en/latest/intro.html) Container.

Build:
```
docker build -t ade-nvim .  
```

Add to your `.aderc`:
```
export ADE_IMAGES="
  ade-nvim:latest
"
```

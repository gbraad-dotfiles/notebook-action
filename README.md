gbraad's Dotfiles `notebook` action
===================================


Use dotfiles' `notebook`-command for Jupyter notebook execution

### Usage

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Excute example notebook
        uses: gbraad-dotfiles/app-action@main
        with:
          notebook: examples/notebook.ipynb   # or .md
          command: execute
```

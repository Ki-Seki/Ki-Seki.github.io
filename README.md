# ki-seki.github.io

## Usage

### Deploy by GitHub Pages

* Settings -> Actions -> General -> Workflow permissions -> Read and write permissions
* Settings -> Pages -> Source -> Deploy from a branch
* Settings -> Pages -> Branch -> gh-pages -> (root)

### Deploy by yourself

```bash
sudo apt install pandoc
pandoc index.md -o index.html --template template/template.html --css template/template.css --self-contained --toc --toc-depth 2
```

## Copyright

The [template](https://github.com/tonyblundell/pandoc-bootstrap-template) copyright is owned by [Tony Blundell](https://github.com/tonyblundell); the other content copyright is owned by myself.

All works are licensed under Apache License 2.0.

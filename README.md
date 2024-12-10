## *Processing Place: How Computers and Cartographers Redrew Our World*

This is the repository for the digital exhibition of the Leventhal Map & Education Center's 2024 exhibition *Processing Place: How Computers and Cartographers Redrew Our World*. It is built with [Quire v1.0](https://github.com/thegetty/quire) and customized by LMEC staff.

## Build chain

[See the Quire Docs](https://quire.getty.edu/docs-v1/quire-commands/) for detailed information on all Quire commands.

### Develop locally

1. clone or copy this repository
2. from inside the `processing-place` directory:

```
npm install
```

3. then, `quire preview` to view locally (should serve at `http://localhost:8080`)

### To deploy

1. from inside `processing-place` directory:

```
quire build
```

2. hand-copy the contents of `_site` into `/var/www/lmec-main-site/public/digital-exhibitions/processing-place`
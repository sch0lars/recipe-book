# recipes-book
This is an EPUB-formatted eBook of recipe collections.

## Compilation
To compile the EPUB, navigate to the `recipe-book` directory and use the following command:

```bash
zip -0Xq recipes.epub mimetype; zip -Xr9Dq recipes.epub META-INF/ && zip -Xr9Dq recipes.epub OEBPS/
```

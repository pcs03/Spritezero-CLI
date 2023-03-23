# Steps to create sprite from SVG images:

1. Put svg images in data/sprites/\_svg directory.

2. Run docker, mount data to docker container.

```
docker run -it -v C:/Work/Code/test/data:/data dolomate/spritezero
```

In this case the directory where data lives is `C:/Work/Code/Spritezero-CLI/`, change accordingly.

3. The SVG images should now be converted to a sprites.json and sprites.png and placed within the working directory.

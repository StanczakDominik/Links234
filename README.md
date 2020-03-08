Use Chrome; firefox has issues with dark notes background on my config

```
reveal-md Prezentacja.md -w
```

To convert movies downloaded via `youtube-dl`:

```
ffmpeg -i d3d.n16.2x_0.6_fly.mpg -vf "fps=20,scale=900:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" -loop 0 d3d.n16.2x_0.6_fly.gif
```

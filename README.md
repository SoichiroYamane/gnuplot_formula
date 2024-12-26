# Custom formula for gnuplot install via Homebrew

```bash
brew install gnuplot.rb
```

Ensure that you have `DISPLAY` environment variable set to `:0` or `localhost:0` before running gnuplot.

```bash
export DISPLAY=:0
```

or

```fish
set -x DISPLAY :0
```

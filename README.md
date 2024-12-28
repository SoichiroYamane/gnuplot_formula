# Custom formula for gnuplot install via Homebrew

## Commands

```bash
brew install --build-from-source gnuplot.rb
```

Ensure that you have `DISPLAY` environment variable set to `:0` or `localhost:0` before running gnuplot.

```bash
export DISPLAY=:0
```

or

```fish
set -x DISPLAY :0
```

## References

- <https://kanekou.hatenablog.com/entry/2019/02/04/155633>

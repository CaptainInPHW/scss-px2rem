# scss-px2rem

Convert `px` to `rem` by using Scss.

### Usage

Import the `px2rem` file into your project and set the `root font-size`(html font-size) via the `$baseFontSize` variable.

```
$baseFontSize: 10;

// Inputs:
div {
  @include rem(font-size, 16px);
  @include rem(margin, 0 24px 0 12px);
}

// Outputs:
div {
  font-size: 16px;
  font-size: 1.6rem;
  margin: 0 24px 0 12px;
  margin: 0 2.4rem 0 1.2rem;
}
```

> Reference: [The ultimate SASS - PX to REM mixin](https://gist.github.com/gregrickaby/6544558)

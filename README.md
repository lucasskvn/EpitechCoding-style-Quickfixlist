# EpitechCoding-style-Quickfixlist

A way to put epitech coding-style-reports.log in nvim quickfix.

## Installation

```lua
{
  "lucasskvn/EpitechCoding-style-Quickfixlist",
  config = function()
    require("epi-quickfix").setup()
  end,
}
```

### Usage : <kbd>:CSquickfix</kbd>, it will execute <kbd>coding-style .</kbd> and parse all the output in the quickfix list.

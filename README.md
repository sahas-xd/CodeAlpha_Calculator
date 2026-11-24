# CalcBasix

CalcBasix is a responsive scientific calculator built for CodeAlpha Frontend Development Task 2. It works offline in a web browser and opens with a three-second glowing intro.

## Run locally

1. Download [CalcBasix.html](CalcBasix.html) from this repository.
2. Double-click the downloaded file to open it in your browser.
3. Use the on-screen keypad or your keyboard. The result updates as you enter an expression. Press **Enter** or **=** to confirm it.

HTML, CSS, and vanilla JavaScript are bundled in `index.html`. No installation or internet connection is required.

## Features

- Basic arithmetic with decimals, parentheses, and standard operator precedence
- Scientific functions including powers, squares, square roots, absolute values, factorials, and logarithms
- Sine, cosine, and tangent with **DEG** and **RAD** modes
- The constants **π** and **e**, plus **Ans** to reuse the last confirmed result
- Error messages for invalid operations such as dividing by zero

## Keyboard shortcuts

| Keys | Action |
| --- | --- |
| `0`–`9`, `.` | Enter a number |
| `+`, `-`, `*`, `/`, `^` | Add, subtract, multiply, divide, or raise to a power |
| `(`, `)` | Group an expression |
| `%`, `!` | Divide by 100 or calculate a factorial |
| `p`, `e`, `a` | Insert π, e, or the last confirmed answer |
| `Enter` or `=` | Confirm the calculation |
| `Backspace` or `Delete` | Delete the last input |
| `Esc` | Clear the expression |

## Try it

| Input | Result |
| --- | --- |
| Type `(2+3)^2` | `25` |
| Select **DEG**, click **sin**, then enter `90)` | `1` |
| Click **√**, then enter `81)` | `9` |
| Type `200*15%` | `30` |


## Project

Created as a Calculator project for CodeAlpha Task 2.

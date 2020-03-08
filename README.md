# A really helpful mathematics search tool

A simple script that uses [ddgr](https://github.com/jarun/ddgr) in combination with [bangs](https://duckduckgo.com/bang) to help you query any type of math question your heart can imagine

## Usage

```
math-search q					// Searches for query in all places
math-search -eq q				// Parses Equation to WolframAlpha
math-search -mw	q				// Searches Wolfram Mathworld
math-search -q q				// Searches Maths Stack Exchange

```

## Examples

`math-search -mw hyperbola`

![hyperbola](https://raw.githubusercontent.com/muffledMitosis/math-search/master/exampleImages/mw_hyperbola.png)

`math-search -mw "Differential Equations"`

![DiffEq](https://raw.githubusercontent.com/muffledMitosis/math-search/master/exampleImages/mw_diffEq.png)

`math-search -eq "Solve x^2 + 24x + 5 = 0"`

![eqSolve](https://raw.githubusercontent.com/muffledMitosis/math-search/master/exampleImages/eq_solveQuad.png)

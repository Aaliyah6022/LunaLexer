# LunaLexer
A simple lexer i use for Luna language

## Run the project

You must have Python 3+ installed in your machine.

### Optimized version

If you want to run the main script in optimized mode (python -o), you must change the lexer construction line to:

```python
  lexer = lex(module=lexer_rules, optimized=1)
```

## Program example
An implementation of the Fibonacci sequence.
```
var iteration, i, x, y, z;
input iteration;
x = 0;
y = 1;
i = 0;
while iteration > i do {
  output x;
  z = x + y;
  # Modify values
  x = y;
  y = z;
  i = i + 1
}.
```


# GitHub math bugs

### Two brackets

```markdown
$[a+b](c+d)$
```

$[a+b](c+d)$

### Backslashes in `$`-math

- https://github.com/community/community/discussions/16993
- https://github.com/community/community/discussions/17143
- https://github.com/community/community/discussions/31812

```markdown
$\{a\}$
```

$\{a\}$

### Math vs. HTML mix-up

- https://github.com/community/community/discussions/17022

```markdown
$$
a <b > c
$$
```

$$
a <b > c
$$

<!--Terminate the bold tag-->

</b>

### Sum/product signs in inline mode

- https://github.com/community/community/discussions/17051

```markdown
$f(x) = \sum_{i=0}^{n} \prod_{j=0}^{n} a_{i,j}$
```

$f(x) = \sum_{i=0}^{n} \prod_{j=0}^{n} a_{i,j}$

### Spacing around dollar sign in math mode

- https://github.com/community/community/discussions/17116

```markdown
$x = \$$
```

$x = \$$

### Math in italic text

- https://github.com/community/community/discussions/17264

```markdown
_Equation $\Omega(69)$ in italic text_
```

_Equation $\Omega(69)$ in italic text_

### Inline math and display math in same list item doesn't render

- https://github.com/community/community/discussions/17325
- https://github.com/community/community/discussions/18817
- https://github.com/community/community/discussions/39545
- https://github.com/community/community/discussions/40775

````markdown
- $a$

  ```math
  a
  ```

- ```math
  b
  ```
````

- $a$

  ```math
  a
  ```

- ```math
  b
  ```

### Inline math can't be surrounded by brackets, quotation marks etc.

- https://github.com/community/community/discussions/28115
- https://github.com/community/community/discussions/30157

```markdown
$\pi$, "$\pi$", ($\pi$)
```

$\pi$, "$\pi$", ($\pi$)

### Dollar-math with spaces

- https://github.com/community/community/discussions/30747

This is the example from [GitHub's announcement blog
post](https://github.blog/2022-05-19-math-support-in-markdown/).

```markdown
A
$$ x = 1 $$
```

A
$$ x = 1 $$

### Oversized sqrt symbol around fractions

- https://github.com/community/community/discussions/39251

```math
\sqrt{\frac{1}{2}}
```

### Sum in fraction

- https://github.com/community/community/discussions/39432

```math
\frac{\sum_{i=1}^n}{2}
```

#### Dollar in `\text`

- https://github.com/community/community/discussions/39655

```math
a
```

- ```math
  \text{$b$}
  ```

### Issues with underscores

- https://github.com/community/community/discussions/36915
- https://github.com/community/community/discussions/41087

  ```markdown
  ${a}_b c_{d}$
  ```

  ${a}_b c_{d}$

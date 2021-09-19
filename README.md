# ProgProving

ProgProving is a LaTeX package that aims to help people prove their codes.

## Requirements

ProgProving requires:

-   [amsmath](https://ctan.org/pkg/amsmath)

## Download

You can find the downloads for each version with their release notes in the [releases page](https://github.com/BergLucas/ProgProving/releases).

## Installation

You can install ProgProving by downloading the package to your folder and importing it into your LaTeX files using :

```latex
\usepackage{progproving}
```

## Documentation

### ProgProving State

This command allows you to easily display the state of a program.

**Requires Math mode**

Usage :

```latex
\state{<state>}
```

Example :

```latex
\state{x = 1}
```

Example output :

```
{x = 1}
```

### ProgProving sp

This command allows you to easily display a sp.

**Requires Math mode**

Usage :

```latex
\ppsp{<instructions>, <state>}
```

Example :

```latex
\ppsp{x := 2, \state{x = 1}}
```

Example output :

```
sp(x := 2,{x = 1})
```

### ProgProving wp

This command allows you to easily display a wp.

**Requires Math mode**

Usage :

```latex
\ppwp{<instructions>, <state>}
```

Example :

```latex
\ppwp{x := 2, \state{x = 1}}
```

Example output :

```
wp(x := 2,{x = 1})
```

### ProgProving Precondition (P)

This command allows you to easily display the precondition letter.

Usage :

```latex
\pre
```

### ProgProving Postcondition (Q)

This command allows you to easily display the postcondition letter.

Usage :

```latex
\post
```

### ProgProving Invariant (I)

This command allows you to easily display the invariant letter.

Usage :

```latex
\inv
```

### ProgProving Loop Condition (B)

This command allows you to easily display the loop condition letter.

Usage :

```latex
\cond
```

### ProgProving Loop Precondition (R)

This command allows you to easily display the loop precondition letter.

Usage :

```latex
\lpre
```

### ProgProving Loop Postcondition (T)

This command allows you to easily display the loop postcondition letter.

Usage :

```latex
\lpost
```

### ProgProving Loop Initialisation (INIT)

This command allows you to easily display the loop initialisation letters.

Usage :

```latex
\init
```

### ProgProving Loop Iteration (ITER)

This command allows you to easily display the loop iteration letters.

Usage :

```latex
\iter
```

### ProgProving Loop Termination (TERM)

This command allows you to easily display the loop termination letters.

Usage :

```latex
\term
```

## Developers

### Contributors

You can find all contributors [here](https://github.com/BergLucas/ProgProving/graphs/contributors).

### License

All code is licensed for others under MIT (see LICENSE).

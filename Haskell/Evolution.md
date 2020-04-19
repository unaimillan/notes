# Yet another Evolution of Haskell developer
Inspired by [Fritz Ruehr](https://willamette.edu/~fruehr/haskell/evolution.html)

## Evolution through addition

### Beginer level
`add x y = x + y`

### Foldr way
`add x y = foldr ($) x (replicate y (+1))`

### Monoid way
`add x = appEndo $ foldMap Endo (replicate a (+1))`

### Primrec way
```Haskell
add x 0 = x
add x n = (+ 1) $ add x (n-1)
```


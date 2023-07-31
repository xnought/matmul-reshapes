# matmul-reshapes

Matrix matrx multiplication is like series of Matrix vector multiplications which is like a series of scaled vectors summed.

Anyway, you can totally just reshape/view the matrix differently, then only do multiplies and sums to get a matmul. I suppose this is the sauce that [tinygrad](https://github.com/tinygrad/tinygrad), but I haven't checked.

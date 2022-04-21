# PGNs

### Checkmate (black wins)

```
[Result "0-1"]

1. f3 e5 2. g4 Qh4# 0-1
```

### Checkmate (white wins)

```
[Result "1-0"]

1. e4 g5 2. Nc3 f5 3. Qh5# 1-0
```

### Draw (agreement)

```
[Result "1/2-1/2"]

1. e4 e5 1/2-1/2
```

### Draw (insufficient material)

```
[Result "1/2-1/2"]

1. a4 b5 2. b4 c5 3. c4 d5 4. d4 e5 5. e4 f5 6. f4 g5 7. g4 h5 8. axb5 cxb4 9.
cxd5 exd4 10. exf5 gxf4 11. gxh5 Bxf5 12. Bxf4 Qxd5 13. Qxd4 Rxh5 14. Rxa7 Rxa7
15. Qxa7 Qxb5 16. Qxb8+ Qxb8 17. Bxb8 Bd3 18. Bxd3 Rxh2 19. Rxh2 Bd6 20. Nf3
Bxh2 21. Bxh2 Nf6 22. Nc3 bxc3 23. Be4 Nxe4 24. Bd6 Nxd6 25. Kd1 c2+ 26. Kxc2
Ne4 27. Ng5 Nxg5 1/2-1/2
```

### Draw (repetition)

```
[Result "1/2-1/2"]

1. Nf3 Nf6 2. Ng1 Ng8 3. Nf3 Nf6 4. Ng1 Ng8 1/2-1/2
```

### Draw (stalemate)

```
[Result "1/2-1/2"]

1. e3 a5 2. Qh5 Ra6 3. Qxa5 h5 4. h4 Rah6 5. Qxc7 f6 6. Qxd7+ Kf7 7. Qxb7 Qd3 8.
Qxb8 Qh7 9. Qxc8 Kg6 10. Qe6 1/2-1/2
```

### Draw (50 move rule)

```
[Result "1/2-1/2"]

1. Nc3 Nc6 2. Nf3 Nf6 3. Na4 Na5 4. Nh4 Nh5 5. Nc5 Nc4 6. Nf5 Nf4 7. Nh6 Nh3 8.
Na6 Na3 9. Ng4 Ng5 10. Nb4 Nb5 11. Ne5 Ne4 12. Nd5 Nd4 13. Ng4 Ng5 14. Nb4 Nb5
15. Na6 Na3 16. Nh6 Nh3 17. Nc5 Nf4 18. Nf5 Nc4 19. Nd3 Nd6 20. Ne3 Ne6 21. Nf5
Nf4 22. Nc5 Nh5 23. Nh4 Ne4 24. Ng6 Nhg3 25. Ne6 Nd6 26. Ne5 Ngf5 27. Nd4 Nb5
28. Ng4 Nh6 29. Ne3 Na3 30. Nb5 Nc4 31. Nd4 Ng4 32. Nef5 Nh6 33. Nh4 Nf5 34.
Ndf3 Ne5 35. Ng5 Nd4 36. Nhf3 Ng4 37. Ne6 Nf5 38. Ne5 Nge3 39. Nc4 Nd5 40. Na5
Nb6 41. Nb3 Nh6 42. Nec5 Nd5 43. Na5 Nf5 44. Ne4 Nh4 45. Nc6 Nf6 46. Ng5 Ng6 47.
Ne5 Ng4 48. Ne6 Nh4 49. Nc4 Ne5 50. Ne3 Nf5 1/2-1/2
```

### Resignation (black wins)


```
[White "Jack"]
[Black "Jill"]
[Result "0-1"]
[Termination "Jill won by resignation"]

1. e4 e5 0-1
```


### Resignation (white wins)

```
[White "Jack"]
[Black "Jill"]
[Result "1-0"]
[Termination "Jack won by resignation"]

1. e4 e5 1-0
```

### Timeout (black wins)

```
[Round "?"]
[White "Jack"]
[Black "Jill"]
[Result "0-1"]
[TimeControl "30"]
[Termination "Jill won on time"]

1. e4 {[%clk 0:00:23.2][%timestamp 68]} 1... e5 {[%clk 0:00:28][%timestamp 20]}
2. f4 {[%clk 0:00:16.3][%timestamp 69]} 2... f5 {[%clk 0:00:26.1][%timestamp
19]} 3. g4 {[%clk 0:00:09.2][%timestamp 71]} 3... g5 {[%clk
0:00:24.5][%timestamp 16]} 0-1
```

### Timeout (white wins)

```
[White "Jack"]
[Black "Jill"]
[Result "1-0"]
[TimeControl "30"]
[Termination "Jack won on time"]

1. e4 {[%clk 0:00:26.7][%timestamp 33]} 1... e5 {[%clk 0:00:20.9][%timestamp
91]} 2. d4 {[%clk 0:00:24.3][%timestamp 24]} 2... d5 {[%clk 0:00:14][%timestamp
69]} 3. c4 {[%clk 0:00:22.9][%timestamp 14]} 3... c5 {[%clk
0:00:07.5][%timestamp 65]} 4. b4 {[%clk 0:00:21.3][%timestamp 16]} 1-0
```

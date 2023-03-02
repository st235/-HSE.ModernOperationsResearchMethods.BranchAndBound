# HSE.ModernOperationsResearchMethods.BranchAndBound

## Build


[`branch_and_bound.cpp`](./branch_and_bound.cpp) is the main file and contains the implementation. To build a CLI application you need to run the command below:

```bash
g++ -std=c++17 -O3 branch_and_bound.cpp
```

Please, pay attention that app requires **C++ 17**. You should use one of the [compilers that support](https://en.cppreference.com/w/cpp/compiler_support/17) the standard.

## Report

The output of one program run can be found **below** or in [`clique_bnb.csv`](./clique_bnb.csv).

```text
            Instance    Clique          Heuristic + BnB time, sec
      brock200_1.clq        21                             59.123
      brock200_2.clq        12                              5.088
      brock200_3.clq        15                              7.101
      brock200_4.clq        17                              9.669
          C125.9.clq        34                              6.926
  gen200_p0.9_44.clq        44                              36.68
  gen200_p0.9_55.clq        55                              7.983
      hamming8-4.clq        16                             10.876
   johnson16-2-4.clq         8                              8.895
    johnson8-2-4.clq         4                              0.175
         keller4.clq        11                               4.57
        MANN_a27.clq       126                            154.294
         MANN_a9.clq        16                              0.727
     p_hat1000-1.clq        10                            145.272
     p_hat1500-1.clq        12                            702.589
      p_hat300-3.clq        36                            108.195
         san1000.clq        15                            627.314
     sanr200_0.9.clq        42                            2138.17
```

P.S.: Thank you for reading!

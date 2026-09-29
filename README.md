# Magma supplementary package

Supplementary material for the paper

> **Constructions of binary linear codes with prescribed hull dimensions from Boolean functions**

This package contains the Magma programs that reproduce the computational
results of the paper. It addresses the referee's request for reproducible
computational material (Reviewer 2, *"Provide reproducible computational
material"*) and also records the consistency checks of the Walsh-spectrum
tables and the three identities $\sum_\beta 1=2^n$,
$\sum_\beta W_f(\beta)=2^n(-1)^{f(0)}$ and $\sum_\beta W_f(\beta)^2=2^{2n}$
requested in the same report.

- **Repository:** https://github.com/Zhl3721/hull-dimensions-boolean-functions-magma
- **Environment:** tested with Magma V2.28-x *(replace with the exact version used)*
- **Contact:** *(to be added)*

## Index (paper item -> program)

| Paper item | Program |
| --- | --- |
| Example 4.1 | `Example4.1_Magma.txt` |
| Example 4.2 | `Example4.2_Magma.txt` |
| Remark 5, search for hull dim n | `Remark5_search_Magma.txt` |
| Remark 5, parity of wt(f) | `Remark5_parity_Magma.txt` |
| Example 5.1 | `Example5.1_Magma.txt` |
| Example 5.2 | `Example5.2_Magma.txt` |
| Example 5.3 | `Example5.3_Magma.txt` |
| Example 5.4 | `Example5.4_Magma.txt` |
| Example 5.5 | `Example5.5_Magma.txt` |
| Example 6.1 | `Example6.1_Magma.txt` |
| Example 6.2 | `Example6.2_Magma.txt` |
| Lemma 12 and Appendix A tables | `Lemma12_AppendixA_Magma.txt` |
| Lemma 12, direct checks m = 5, 6 | `Lemma12_m5m6_Magma.txt` |
| Proposition 2 (existence, m >= 9) | `Proposition2_existence_Magma.txt` |

## Output files

- `Example4.2_Magma_output.txt`
- `Remark5_parity_Magma_output.txt`

(For the remaining programs the output is printed on screen and can be saved
with a redirection, e.g. `magma -b <file> > <file>_output.txt`.)

## Usage

- **Magma GUI:** load/paste a program as is; the final `quit;` is commented
  out, so the session stays open.
- **Command line:** `magma -b <file>`; if Magma waits at the end, add a final
  `quit;` line.

Every program carries a header identifying the statement it verifies
(section, theorem/lemma/example/remark number and label in the manuscript) and
its expected output.

## License and citation

- **License:** see `LICENSE` *(to be added)*.
- If you use this package, please cite the paper above.

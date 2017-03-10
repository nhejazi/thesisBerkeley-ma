# Biostatistics M.A. Thesis

> "Targeted Learning methods with empirical Bayes moderation for biomarker
> discovery," a thesis submitted in partial satisfaction of the requirements for
> the Master of Arts (M.A.) in Biostatistics, at U.C. Berkeley, by [Nima
> Hejazi](http://nimahejazi.org).

---
## Summary

This thesis presents a generalized approach for employing empirical Bayes
shrinkage to improve the stability of estimates of variable importance measures
(VIMs) computed using Targeted Minimum Loss-Based Estimation (TMLE), in the
context of problems of biomarker discovery.

__The compiled thesis document (in PDF) is available for browsing
[here](http://www.stat.berkeley.edu/~nhejazi/publications/thesis-ma-biostat.pdf).__

---

## Compilation

* `make all` - compile the thesis document, generating two subdirectories: `pdf`
    (containing the thesis and approval page in PDF) and `output` (containing
    auxiliary documents created in the compilation process).

* `make clean` - removes the subdirectories generated by the use of `make all`.

_N.B._, a functional installation of a LaTeX distribution (_e.g._,
[MacTeX](http://www.tug.org/mactex/)) is required to compile this thesis
document.

---

## Related

* [`biotmle`](http://nimahejazi.org/biotmle/) - R package that facilitates
  biomarker discovery by generalizing the moderated t-statistic of Smyth for use
  with asymptotically linear target parameters using Targeted Minimum Loss-Based
  Estimation.

---

## License

&copy; 2017 [Nima S. Hejazi](http://nimahejazi.org)

The contents of this repository are released under a <a rel="license"
href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img
alt="Creative Commons License"
style="border-width:0"
src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a>

A human-readable version of the CC BY-NC-SA 4.0 license is available
[here](https://creativecommons.org/licenses/by-nc-sa/4.0/); the full license may
be examined [here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

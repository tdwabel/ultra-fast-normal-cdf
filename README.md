A verified, high-performance implementation of the Normal Distribution Cumulative
Distribution Function (CDF).

## Highlights

- **Precision**: Full IEEE 754 double-precision accuracy
  - Max absolute error: 3.33×10⁻¹⁶ (verified against SciPy 1.15.0)
  - Mean absolute error: 1.35×10⁻¹⁷
- **Speed**: 200× faster than `scipy.stats.norm.cdf` in scalar benchmarks
- **Zero dependencies**: A single, self-contained binary module
- **Drop-in replacement**: `import normcdf; normcdf.normcdf(x)` replaces
  existing SciPy calls with a single-line change

## Verification Report

The full performance and accuracy verification report is included in this
repository:
- `report_cn.pdf` — Full verification report (Chinese)

All tests were conducted on Windows 10/11 64-bit, Python 3.14, SciPy 1.15.0.

## Getting Started (Evaluation)

An evaluation version (30-day trial, compiled `.pyd` module) is available for
qualified teams. Please contact the author directly for access.

## License

This implementation is **proprietary and commercially licensed**.
No source code is distributed in this public repository.

For commercial licensing inquiries, please contact:

- **Author**: 汤大伟
- **Phone**: 13025178270

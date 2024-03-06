4.5.5 [2024.01.28]
Numeric.AD.Mode.Reverse.Double now handles IEEE floating-point special values (e.g., NaN and Inf) correctly when ad is compiled with +ffi. Note that this increase in floating-point accuracy may come at a slight performance penalty in certain applications. If this negatively impacts your application, please mention this at #106.

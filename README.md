% Generated by roxygen2: do not edit by hand
% Please edit documentation in R/HOSVDSig.R
\name{HOSVDSig}
\alias{HOSVDSig}
\title{HOSVDSig}
\usage{
HOSVDSig(
  obj,
  prefix,
  featureName = "To_inf",
  SampleID = "Sample_ID",
  flevel = c("control", "non", "adjacent", "inf"),
  pthres = 0.05,
  zthres = 2,
  recompute_glasso = TRUE,
  recompute_HOSVD = TRUE
)
}
\description{
This function constructs co-expression network for highly vairable and expressed genes split by samples and
It decomposes the co-expression network into 3 matrices with k TCs, k = min(#Gene, #Sample)
and extract variable network signatures
}

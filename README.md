#HOSVDSig
This function constructs co-expression network for highly vairable and expressed genes split by samples and
It decomposes the co-expression network into 3 matrices with k TCs, k = min(#Gene, #Sample)
and extract variable network signatures

#Example: 
if you have a seurat obj, a feature column Inf, a feature column Sample_ID, and four levels in the Inf column:

HOSVDSig(obj,prefix,featureName="Inf",SampleID="Sample_ID",flevel=c("control","non","adjacent","inf")

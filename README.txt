EXTENDED DATA SUMMARY
from Finotello et al. (Sci.Rep., 2012)
https://doi.org/10.1038/s41598-019-56992-w

FILE "PCA_ALL.xlsx"
Column order
1     Channel type (F=fluvial, T=Tidal)
2     Channel name
3     Number of bends (i.e., number of half meanders)
4     Total channel length (normalized with the mean channel half width)
5-9   Statistics of the width-normalized half meander intrinsic length (mean, var, st dev, skew, flat)
10-15 Statistics of the half meander asymmetry index (mean, var, st dev, skew, flat)
16-20 Statistics of the half meander sinuosity (mean, var, st dev, skew, flat)
21-25 Statistics of the width-normalized full meander intrinsic length (mean, var, st dev, skew, flat)
26-31 Statistics of the full meander asymmetry index (mean, var, st dev, skew, flat)
32-36 Statistics of the full meander sinuosity (mean, var, st dev, skew, flat)
37    Reach sinuosity (not used in the analyses)
38-42 Statistics of the normalized channel curvature (mean, var, st dev, skew, flat)

FILES BSC
Each individual file refers to a specific channel reach.
Column order
1 local channel width B(s)=B*/B_0
2 along-channel position (cumulative distance) s=s*/B_0
3 local channel curvature C=C*B_0

FILES HALF(*.hm)/FULL(*.fm) MEANDERS 
Each individual file refers to a specific channel reach, and it contains the morphometric characteristics of all the half/full meanders.
Column order
1 half/full meander intrinsic length (normalized with the mean meander half width)
2 half/full meander asymmetry index
3 half/full meander sinuosity
4 (only for rivers) half/full meander specific energy (not used in the analyses, see Bogoni et al., (WRR) 2017)

FILES KMZ
This folder contains the channel centerlines used in the analysis, in KMZ format. 

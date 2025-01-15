READ ME

A Spatio-Temporal Dirichlet Process Mixture Model on Linear Networks for Crime Data

Download data and code here:
https://www.dropbox.com/scl/fo/me61bfufrte00d8y5cat4/AB13ZtLzeoPZ39KDjt0xpfE?rlkey=md6bzl588fjr7rs0n745qg8xl&st=pm0ulx4x&dl=0

1. data
1) robbery.csv, theft.csv: crime location
2) amenity_loc.csv: amenity location
3) road_linnet_bf.Rdata: buffer from linear network
4) road_linnet.Rdata: linear network used for analysis
5) road_linnet_r.Rdata: road before cutting a large network

6) robbery_results.Rdata: mcmc results of robbery
7) robbery_postprocessing.Rdata: post processing results of robbery
8) theft_results.Rdata: mcmc results of theft
9) theft_postprocessing.Rdata: post processing results of theft

1),3),4) used for MCMC using mcmc.R in Section 4
2) for Section 4.2

6),7),8),9) used for draw table and figures


2. code
1) mcmc.R: run spatiotemporal dirichlet process on linear network mcmc
2) table and figure.R: draw table and figure based on 2-1),2),3),4)



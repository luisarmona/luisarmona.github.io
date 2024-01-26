This README explains the structure of the value-added estimates available for download at https://luisarmona.github.io/ (VA_ests.csv). 
For details on the methodology used to construct the estimates, please consult the paper, "Redesigning Federal Student Aid in Sub-baccalaureate Higher Education" by Luis Armona and Shengmao Cao. If you use these estimates to conduct your own research, please cite the paper accordingly. The estimates in the data correspond to the final estimates we use in our paper (e.g. the empirical bayes adjusted estimates)

The file contains for each school chain, an estimate of value-added on four outcomes. The file is organized at the OPEID level, where each observation corresponds to one six-digit OPEID (ommitting the final two digits which indicate branches within a school chain). These IDs may be used to merge these estimates into other datasets, such as IPEDS. We describe each column below.

opeid6: six-digit OPEID
name: Name associated with the primary campus of the school chain.
VA_earnings: Estimated effect of attending the college on earnings, 10 years after entering college.
VA_condearnings: Estimated effect of attending the college on earnings conditional on employment, 10 years after entering college.
VA_emp: Estimated effect of attending the college on the probability of being employed, 10 years after entering college.
VA_gainful: Estimated effect of attending the college on the probability of being gainfully employed (earnings >$25,000/year), 10 years after entering college.



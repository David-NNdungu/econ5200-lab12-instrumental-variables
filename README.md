# Instrumental Variables: Weak Instruments, Compliers and the Exclusion Restriction

## Objective

I used simulations and Card’s schooling data to see how instrument strength, exclusion, and the people whose treatment changes affect an IV estimate.

## Methodology

- I varied the strength of the first stage in a simulation and compared OLS and 2SLS across repeated samples.
- I compared OLS and 2SLS in Card’s college-proximity example and checked the 2SLS coefficient using two OLS regressions.
- I varied the instrument’s direct effect on the outcome to see how sensitive 2SLS was to a violation of exclusion.
- I simulated two valid instruments that changed treatment for different groups and compared their estimates.

## Key Findings

When the median first-stage F was 0.5, the median 2SLS estimate was 2.038, close to the median OLS estimate of 1.998 and far above the true effect of 1.0. A significant second stage could still give a poor estimate of the effect.

In Card’s data, the first-stage F was 16.7. The schooling coefficient was 0.0740 by OLS and 0.1323 by 2SLS. In the sensitivity check, allowing college proximity a direct effect on wages lowered the estimated return to schooling. The two-instrument simulation showed why valid instruments can give different answers when they move treatment for different groups.

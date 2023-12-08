#Main branch process updates

In order to get a new version brought into the main branch, we need to understand how the changes manifest in the outputs, and be able to explain the differences to ourselves and 

We need to rerun a set of scenarios that we identify as **core**, and run them through our main output generation, so that we can compare the outputs from the old version and the new version in charts.

Our current core scenarios are:
- Sectoral CBs
- Sectoral CBs (HL)
- Sectoral CBs (TO)
- Whole System CB

As part of a pull request, a link to a netlify page showing these comparisons should be given.

The CODEOWNERS file shows who will be responsible for approving a pull request.

A code owner should only approve a pull request once they have reviewed those comparisons, and understands what has changed, and why.

# safeinsights.r-universe.dev

Registry for the SafeInsights [r-universe](https://safeinsights.r-universe.dev) repository.
`packages.json` lists the R packages r-universe builds and serves as a CRAN-like repo.

Install a package from it:

```r
install.packages("safeinsights.fusion",
  repos = c("https://safeinsights.r-universe.dev", "https://cloud.r-project.org"))
```

Each entry tracks the default branch of its source repo. Set `"branch": "*release"` on an
entry to follow GitHub releases instead.

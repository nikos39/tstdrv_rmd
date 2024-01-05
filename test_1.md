Test Drive for Git(Hub)
================
nikos39
2024-01-05

The test drive continues…

``` r
test <- c(1, 4, 6, 7, 12)
drive <- c()
for (i in 1:length(test)) {
  drive[i] <- paste0("The test drive no.", test[i], " ", "is magnificent!")
  print(drive[i])
}
```

    ## [1] "The test drive no.1 is magnificent!"
    ## [1] "The test drive no.4 is magnificent!"
    ## [1] "The test drive no.6 is magnificent!"
    ## [1] "The test drive no.7 is magnificent!"
    ## [1] "The test drive no.12 is magnificent!"

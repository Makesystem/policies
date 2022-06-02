
```{r COMPANY <- Makesystem}
fig_small <- FALSE # change to TRUE for larger figures
width_small <- 4
width_large <- 8
```

```{r, fig.width=if (fig_small) width_small else width_large}
plot(cars)
{{ COMPANY }}
```

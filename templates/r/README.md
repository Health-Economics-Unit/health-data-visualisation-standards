# R templates (ggplot2)

This folder provides R examples for applying the Health Economics Unit visualisation standards using **ggplot2**.

Where possible, the Unit standard is implemented via the **`heutools`** R package (maintained separately in the organisation GitHub).  
This repository provides usage guidance and example plots for common analytical outputs.

---

## Quick start

### 1) Install `heutools`

```r
install.packages("remotes")
remotes::install_github("HealthEconomicsUnit/heutools")
```

### 2) Use the theme and palettes in plots
```r
library(ggplot2)
library(heutools)

ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point() +
  labs(
    title = "Fuel efficiency decreases as vehicle weight increases",
    x = "Weight (1000 lbs)",
    y = "Miles per gallon"
  ) +
  theme_heu()
```

## What `heutools` provides

Typically:

- `theme_heu()` — standard ggplot theme  
- HEU colour palette helpers (e.g. `get_heu_palette()`)  
- HEU colour scales (e.g. `scale_colour_heu()`, `scale_fill_heu()`)

Refer to the `heutools` repository for the definitive API and documentation.

---

## Example gallery

See:

- `example_gallery.Rmd` — runnable examples that generate standard plots  
- `outputs/` (optional) — rendered example images for quick reference  

The gallery focuses on chart types used commonly in health economics and NHS analytics:

- Time series (with annotations)  
- Group comparisons (dot plots)  
- Distributions (histograms/boxplots)  
- Funnel plots / variation charts (where relevant)  
- Survival curves (Kaplan–Meier)  
- Cost-effectiveness plane and CEAC (if applicable)  

---

## Contributing examples

If you add a new example:

- Keep it reproducible using built-in or simulated data.  
- Include a short description of when to use the chart.  
- Ensure titles, units and labels follow the Unit standards.

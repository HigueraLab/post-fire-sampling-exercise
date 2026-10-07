# Post-fire Sampling Exercise

An interactive exercise for **FORS 333: Fire Ecology** at the University of Montana. Students use field data  collected in the footprint of the 2017 Lolo Peak Fire to see how to summarize a site, how sample size affects the mean and its standard error, and whether fewer transects can still detect change between years.

**Open the exercise:** https://higueralab.github.io/post-fire-sampling-exercise/

## What the exercise covers

The exercise has three tabs:

1. **Summarize 16 plots.** Live seedling density in the 16 plots sampled at the high-severity site (LP_H) in 2026. Toggle the mean, median, range, mean ± 1 SD, and mean ± 2 SE to compare ways of describing central tendency and variability.
2. **Fewer plots?** Draw repeated random samples of *n* plots from the 16 and watch the sample means build into a bell-shaped distribution (the central limit theorem). Compare the spread of sample means with the prediction SD/√n.
3. **Detect a change?** Compare fine litter cover at LP_H between two years. Choose how many transects were sampled per year, and see how often the ±2 SE error bars separate across 1,000 random subsets.

**Terms.** A site (LP_H, LP_M) is characterized by a sample of sampling units: belt transects from 2018 to 2025, and 1-m-radius plots in 2026. The sample size, *n*, is the number of transects or plots.

**Course rule for significance.** Two means are called significantly different when their ±2 SE error bars do not overlap. This rule is conservative: it rarely flags a difference that is not there, but it misses some real differences that a formal test would detect.

## Data

All values are embedded in `index.html`. No data are loaded from the web.

- **Tabs 1 and 2:** live tree seedlings (all species combined) per plot, LP_H, 2026, n = 16 plots. Species absent from a plot count as zero.
- **Tab 3:** fine litter cover (<7.6 cm diameter) per belt transect, LP_H. Each value is the mean of a transect's two cover circles. Years: 2018, 2019, 2022 to 2025 (2020 and 2021 were not sampled).

The data were collected by FORS 333 students between 2018 and 2026. Tab 2 draws plots with replacement (a bootstrap). Tab 3 draws transects without replacement from each year.

## Using the exercise

- **Online:** open the link above in any current browser.
- **Offline:** download `index.html` and open it in a browser. It needs no internet connection or installation.

## License

- **Code** (HTML, CSS, and JavaScript): [MIT License](LICENSE).
- **Text, figures, and embedded class data:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## How to cite

Higuera, P. E. (2026). *Lolo Peak Sampling Exercise* [Interactive teaching tool]. FORS 333: Fire Ecology, University of Montana. https://github.com/HigueraLab/post-fire-sampling-exercise

## Development note

The exercise was developed by P. Higuera with AI assistance (Claude, Anthropic), and reviewed by the author.

## Contact

Philip Higuera, Department of Ecosystem and Conservation Sciences, W.A. Franke College of Forestry and Conservation, University of Montana. philip.higuera@umontana.edu

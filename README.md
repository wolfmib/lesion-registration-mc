# lesion-registration-mc

Monte Carlo simulation guide for the paper

> **Predicting Registration Error at Lesion Pixels from Fiducial Leverage and Residuals**
> Wei-Che Hung, Stefania Cristina, Kenneth P. Camilleri, Alexandra Bonnici
> Department of Systems and Control Engineering, University of Malta
> IEEE ISBI 2027 (under review)

## What is here

- [`Predicting_Registration_Error_at_Lesion_Pixels_Simulation_Guide.pdf`](Predicting_Registration_Error_at_Lesion_Pixels_Simulation_Guide.pdf) — two pages: what the simulation tests, the protocol of Sec. 3.4 of the paper, the script that produces each figure and table (Figs. 2–4, Table 1), and the run commands.

## What the simulation reproduces

| Paper object | Content |
|---|---|
| Fig. 2 | four-marker configuration, leverage map, worked frame |
| Fig. 3 | predicted vs simulated RMS registration error, 65 POIs, two configurations, four noise levels |
| Fig. 4 | ray sweep with the 95 % simultaneous band; six lesion polygons with 95 % confidence intervals |
| Table 1 | relative deviations of the predictions; lesion-boundary area disagreement for six polygons |

## Code availability

The simulation scripts are released in this repository after the review round. Until then, requests by e-mail are welcome.

## Citation

Hung, W.-C., Cristina, S., Camilleri, K. P., Bonnici, A. *Predicting Registration Error at Lesion Pixels from Fiducial Leverage and Residuals.* IEEE ISBI 2027, under review.

## Contact

Wei-Che Hung — wei-che.hung@um.edu.mt · wolfmib@gmail.com

## Licence

MIT, see [LICENSE](LICENSE).

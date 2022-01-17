# pandemic-flu-spread

The project is about modeling of pandemic spread in a classroom of 21 elementary school kids with one carrier named Tommy. The probability of any classmate being infected by carrier is 0.02 and once infected, the carrier is infectious for 3 days. We have a base assumption that all kids and days are independent to get an i.i.d. Bern(p) trial. To model the infection spread, we surveyed our problem using binomial and chain binomial models like SIR (Susceptible, Infected and Recovered) model to predict how long this epidemic will last. Later, we made more realistic assumptions on exposure, immunity, and initial vaccinated populations to model the spread in varied settings. For our simulation, we used the SIR model without any other parameters. 

Through our simulations (1000 simulations), we found that the average infection lasts in the class lasts between 4-19 days with an average of 9 days.

The Code.Rmd file contains the entire code. You can simply open the file in R studio and run the file.
It has been commented for clarity.

Required libraries in R
- deSolve
- ggplot2
- reshape2

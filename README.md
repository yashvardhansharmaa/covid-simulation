# Covid Vaccine Distribution Optimization & Simulation

This project was for my CS51 class at my university and it comprises of two parts.

## Part 1: Optimization

### Problem
To prevent the spread of an infectious disease, a vaccine needs to be distributed as quickly and efficiently as possible to **15 cities** that have experienced major outbreaks. The objective was to optimize the route between these cities.

### Approach
I employed a genetic algorithm to find the most efficient route by minimizing the total distance traveled. The algorithm involved generating an initial population, calculating fitness based on route distance, and iterating through generations with selection and mutation operations.

### Results
The code showcased the minimum distance achieved by the algorithm and the optimal order of cities in the route. While the genetic algorithm efficiently explored the problem space, it did not guarantee the global optimum.

## Part 2: Simulation

### Problem
In Part 2 of my project, I delved into the **SIR (Susceptible-Infectious-Recovered) model** to gain insights into the spread of infectious diseases, with a focus on the COVID-19 outbreak in my hometown, Lucknow, India.

### Approach
I utilized **Euler's method**, a widely used numerical simulation algorithm, to approximate the dynamics of the disease. By considering the **SIRD** (Susceptible-Infectious-Recovered-Deceased) model, I extended the original SIR model to include the variable of deaths.

### Results
The simulation provided visualizations that showcased the trajectory of the COVID-19 outbreak in Lucknow. By adjusting parameters such as the infection rate, recovery rate, and death rate, I observed how these factors influenced the course of the disease and its impact on the population. The simulations proved to be surprisingly accurate, providing realistic representations of the spread of COVID-19.

**Limitations**: The accuracy of the model relied on the availability and accuracy of reported COVID-19 cases, and the SIR model is a simplification of the complex reality.

Nonetheless, by employing the SIR model and Euler's method, I gained a deeper understanding of infectious disease dynamics and explored various scenarios. This project contributes to our knowledge of managing and controlling infectious diseases.

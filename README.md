# Wave_Spectral_Analysis
This assignment focused on analyzing wave behavior in a specified Global Wave Statistics (GWS) area using various seakeeping and marine engineering techniques. The goal was to understand and quantify wave characteristics, which are crucial for ship design, offshore platform stability, and overall safety in maritime operations.

### The key tasks were as follows:

#### Histogram of Significant Wave Heights:

The first part of the assignment involved drawing a histogram of significant wave heights for the selected GWS area. This graphical representation provided a clear visual of the distribution and frequency of wave heights, helping to identify the most common wave sizes encountered in the region.

**1. Sea Spectra and Ideal Conditions:**

Next, I calculated the most probable wave height and zero crossing period for the GWS area. Using these values, I determined the ideal sea spectra, which was then represented graphically. This helped in visualizing the energy distribution of waves at different frequencies, which is essential for understanding the impact of waves on ship dynamics.

**2. Numerical Calculation of Spectral Moments (m₀, m₁, m₂):**

Spectral moments are key statistical properties used to describe wave spectra. In this part, I numerically computed the spectral moments m₀, m₁, and m₂, which provided important insights into wave energy distribution, the average period of waves, and other sea state characteristics.

**3. Importance of Correct Frequency Intervals in Numerical Integration:**

I discussed the significance of choosing the correct frequency intervals during numerical integration. This is vital because the accuracy of spectral moments and wave predictions depends on the precision of the integration process. Incorrect intervals can lead to errors in estimating wave heights and periods, which can affect seakeeping assessments and design calculations.

**4. 100-Year Wave Height Prediction:**

Finally, I calculated the 100-year wave height for the selected GWS area. This was done by cutting the tail of the data after the cumulative distribution function (CDF) exceeded FX > 0.995. Additionally, I performed the same calculation using the full scatter table, which provided a long-term prediction of extreme wave heights. The results were then analyzed and compared to assess the variability and safety implications in long-term marine design and operations.

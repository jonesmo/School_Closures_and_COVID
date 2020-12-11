<br />
<p align="center">
  <h3 align="center">School Closures and COVID-19, from April 2020</h3>

  <p align="center">
    As countries successively shut down for the pandemic in spring of 2020, public conversation focused on <a href="https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf">the original Imperial College study</a> of measures to mitigate the virus' spread.  Before revisions, the study's models indicated that the lowest death rates would result from shutting down workplaces and businesses while keeping schools open, a detail often ignored in news articles.  I grew interested in how different countries' policies toward school closures might affect death rates from the disease.  Using data from the Blavatnik School of Government at the University of Oxford, I designed a study to measure the impact of school closure policies on COVID deaths.
    <br />
    <br />
    <a href="https://docs.google.com/document/d/1GCg7KxJ0ykM-ZQAFoYYqEIT3WGHLrKYY_jMCU_BQrGw/edit?usp=sharing">View Design</a>
    <br />
    <a href="https://covidtracker.bsg.ox.ac.uk/">Oxford Government Response Tracker, Data, and Studies</a>
  </p>
</p>

## Updates in Fall 2020 and Future Approach

After some time has passed, and after learning new techniques, I would approach this problem differently.  Rather than measuring school stringency index as a discrete number settled into by a country over time, I would take the average of school stringency for each country over the last 9 months and make school stringency index a continuous variable.  I would also start my measurement for each country from the date of first confirmed case in that country.  An additional feature to add to the analysis would be date from first case or death to date of implementation of new closure policy.  I would use clustering algorithms to group countries by school stringency index and by death rates.  I'd also use time series analysis to see whether changes in death rate can be predicted by changes in school closure policies.

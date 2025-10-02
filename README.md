# The Virus of Variation: Making Sense of Death and Data using Process Behavior Charts
Welcome to the official GitHub repository for **The Virus of Variation: Making Sense of Death and Data using Process Behavior Charts**. Here, you will find the Python code, Excel workbooks, and datasets used to generated the figures in  the *The Virus of Variation*. The Python code and Excel workbooks are organized by chapter. The datasets are organized by title as they pertain to application. For instance, Chapter 18, *A Framework for comparison* outlines how to perform *temporal* and *physical* comparisons using process behavior charts. The dataset used in the temporal comparison is called *temporal-comparison-death-to-birth-rates* while the dataset used in the physical comparison is called *physical-comparison-death-to-birth-rates*. The intent of the repository is to serve as a practical resource for those reading *The Virus of Variation* that are interested in furthering their practical understanding of the topics that it explores. 

If you've somehow found yourself here without having purchased the book, visit [brokenquality.com/book](https://www.brokenquality.com/book) to purchase a copy. 

For additional resources outside of *The Virus of Variation*, visit [BrokenQuality.com](https://www.BrokenQuality.com). If you have questions or would like to collaborate, contact **James.Lehner@gmail.com** or email **QualityIsBroken@gmail.com**. 

## Table of Contents
- [Python Code](#python-code)
- [Excel Workbooks](#excel-workbooks) 
- [Datasets](#data)
- [Process Improvement library](#process-improvement-library)
- [Contributing](#contributing) 
- [Contact](#contact) 
- [License](#license)
- [Additional Information](#additional-information)

## Python Code
Python code is organized by chapter title. Specific figures in the code are labeled in accordance with the numbering scheme in **The Virus of Variation**. In instances where a chapter does not contain figures or calculations using Python, no code is provided.

1. chapter-1-the-case-of-ignaz-semmelweis
2. chapter-2-the-impact-of-handwashing-at-vienna-general
3. chapter-3-measures-of-location
4. chapter-4-measures-of-dispersion
5. chapter-5-visual-syntax
6. chapter-6-the-basics-of-bar-charts
7. chapter-7-how-to-build-a-helpful-histogram
8. chapter-8-trustworthy-times-series
9. NA
10. chapter-10-variation-and-the-process-principle
11. chapter-11-the-process-behavior-chart-landscape
12. chapter-12-how-to-build-a-process-behavior-chart
13. chapter-13-characterization
14. chapter-14-other-types-of-signals
15. chapter-15-are-shewharts-limits-different
16. chapter-16-the-path-of-improvement
17. chapter-17-communicating-insights-with-written-reports
18. chp-18-a-framework-for-comparison
19. chp-19-improvement-and-its-principles
20. chp-20-insights-into-actions
21. NA (appendix A)
22. appendix-B-calculating-the-pareto-chart-cumulative-percentage-curve
23. appendix-C-shewharts-resistance-measurements
24. appendix-D-the-impact-of-handwashing-at-vienna-general
25. appendix-E-the-impact-of-pathological-anatomy-at-vienna-general
26. appendix-F-temporal-comparison
27. appendix-G-physical-comparison
28. appendix-H-improvement-at-vienna-general

## Excel Workbooks
Excel workbooks are sequentially organized by chapter using the same structure as the Python code.

## Datasets
The 11 different datasets that are used in **The Virus of Variation** include:
1. obstetrics-annual-salaries-in-1845.csv
2. sales-by-regions.csv
3. death-to-birth-rates-by-hospital-1784-to-1849.csv
4. death-to-birth-rates-for-software-verification.csv
5. causes-of-death-in-1864-dublin.csv
6. shewharts-resistance-measurements.csv
7. impact-of-handwashing-death-to-birth-rates.csv
8. impact-of-pathological-anatomy-death-to-birth-rates.csv
9. temporal-comparison-death-to-birth-rates.csv
10. physical-comparison-death-to-birth-rates.csv
11. improvement-death-to-birth-rates.csv

## Process Improvement Library
The `process_improvement.py` library simplifies the task of building process behavior charts using Python. The library is available on PyPi.org and can be installed with pip using the following command:

```pip install process_improvement```

Alternatively, `process_improvement.py` can be installed from GitHub by entering the following command using the `command prompt`:

```pip install git+https://github.com/jimlehner/process_improvement```

For additional details regarding the `process_improvement.py` library [click here](https://github.com/jimlehner/process_improvement).

## Contributing
To contribute to the Python code base, follow these steps:
1. Fork the repository.
2. Clone your fork locally:
```
git clone https://github.com/<your-username>/thevirusofvariation.git
cd thevirusofvariation/pythoncode
```
3. Create a branch: ```git checkout -b <branch_name>```. 
4. Make your changes and commit them:  ```git commit -m '<describe your changes>'```
5. Push to the original branch: ```git push origin <branch_name>/<location>```.
6. Open a pull request to the main repository.

Alternatively see the GitHub documentation on [creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Contact
If you want to contact me you can reach me at [James.Lehner@gmail.com](James.Lehner@gmail.com) or [qualityisbroken@gmail.com](QualityIsBroken@gmail.com).

## License
This project uses the following license: MIT License.
## Additional Information
- **Parts of a Process Behavior Chart**: Invented by Dr. Walter Shewhart in the mid-1920s at Bell Laboratories, PBCs are composed of two charts: the `X-chart` and the `mR-chart`. Where the `X-chart` bounds the variation associated with individual values the `mR-chart` bounds the value-to-value variation. This is made possible through the calculation of a trio of limits known as process limits. The `upper process limit (UPL)` and `lower process limit (LPL)` are used on the `X-chart`. The `upper range limit (URL)` is used on the `mR-chart`. 
- **Two types of variation**: Inherent in the characterizations of `predictable` and `unpredictable` is the tyoe of variation action a process. A predictable process is influenced by only `routine` causes of variation. An `unpredictable` process is influenced by both `routine causes of variation` and `assignable` causes of variation.  
- **Improvement**: 
	- **Predictable**: To improve a predictable process `routine` causes of variation must be `identified`, `understood`, and `mitigated`.  This requires fundamental changes to the process must be made. These include, but are not limited to, changes to raw materials, adjustment to system settings, redesign of stations, redesign of software, calibration of measurement systems. 
	- **Unpredictable**: To improve an unpredictable process  `assignable` causes of variation must be `identifed`, `understood`, and `eliminated`. To begin this process, an investigation into values that fall outside the process limits on the `PBC` must be performed. 
- For those unfamiliar with process behavior charts (control charts) that are interested in learning more visit [BrokenQuality.com](https://www.brokenquality.com).

## Additional Information
If you are unfamiliar with process behavior charts (control charts) and want to learn more, visit  [BrokenQuality.com](https://www.brokenquality.com/).

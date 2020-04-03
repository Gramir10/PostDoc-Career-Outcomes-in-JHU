# PostDoc-Career-Outcomes-in-JHU
Studying PostDoc Career Outcomes in JHU using cluster analysis to identify departments with different aspects.

Once the Postdoctoral Career Outcomes was imported from Tabula, the data was cleaned through text-to-columns.
1. Using percentage of populations, mean and st.dev were calculated for each sector category.
2. Using STANDARDIZE function, Z-scores were created for each department for each sector.
3. Cluster arrays set up with VLOOKUP, with each department given a DEPTID.
4. Using SUMXMY2 function, Distance Squared was calculated for each array of Z-score per department with each cluster array.
5. Using SOLVER Add-in, Clusters were formed by minimizing sum of distance squared.

In all, 4 clusters were created, they are summarized below.
Internship oppurtunities for the specific sectors should be offered. The Life Design Lab at JHU can use these clusters to categorize which oppurtunities should be highlighted for which departments. Further efforts should be extended to reach out to departments of Cluster #4, as they have less data on their outcomes.


![alt text](https://github.com/Gramir10/PostDoc-Career-Outcomes-in-JHU/blob/master/C1.png)
![alt text](https://github.com/Gramir10/PostDoc-Career-Outcomes-in-JHU/blob/master/C2.png)
![alt text](https://github.com/Gramir10/PostDoc-Career-Outcomes-in-JHU/blob/master/C3.png)
![alt text](https://github.com/Gramir10/PostDoc-Career-Outcomes-in-JHU/blob/master/C4.png)


Data Sources:
Coalition for Next Generation Life Science, JHU Provost Office. Postdoctoral Career Outcomes: https://provost.jhu.edu/education/graduate-and-professional-education/cngls/

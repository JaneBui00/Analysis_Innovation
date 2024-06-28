# Analysis and segmentation of innovative development of the Russian Federation 👩‍💻💡
Nowadays, the ability to create and use innovative products in the economy is considered a key factor in ensuring national economic security and increasing the country's competitiveness in the global space. This is because the use of these products can ensure economic development through increasing productivity and more efficient use of available resources. Therefore, the purpose of the work is to analyze innovative development in Russia and identify the features of regional groups of the Russian Federation according to innovation factors.
The dataset is collected by me from Rosstat (Federal State Statistics Service) and Rospatent (Federal Service for Intellectual Property) for 2022. It includes name of Russian region and 12 relative variables:

| Variable | Meaning |
| --- | --- |
| name | name of 85 regions in Russia |
| ind1 | percentage of costs for innovation activities of goods shipped, work performed, services |
| ind2 | average salary of an employee working in R&D |
| ind3 | percentage of innovative goods, works, services in the total volume of goods shipped, works performed, services |
| ind4 | level of innovative activity of organizations |
| ind5 | percentage of organizations carrying out technological innovations in the total number of organizations surveyed |
| ind6 | percentage of employees of organizations performing R&D in the total number of employees in the region |
| ind7 | percentage of researchers with an academic degree in the total number of employed in the region |
| ind8 | inventive activity coefficient |
| ind9 | profitability of production (volume of innovative production/costs for innovation activities) |
| ind10 | share of higher education students in the total population |
| ind11 | labor productivity in R&D (volume of innovative production/Number of employees of organizations performing R&D) |
| ind12 | share of R&D costs in GPD |

**Methods** using in the analysis are: KNN-imputation, EDA, factor analysis, and cluster analysis.

**Analysis result**
- Group 0 is characterized by high human innovation potential, especially in the city of Moscow (outlier point on the left graph). The coefficient of variation of factor 1 in this group is 0.33, which indicates the homogeneity of the factor of human innovative potential. All factors F2, F3, F4 have large coefficients of variation, which proves the presence of large differences between regions in cluster 1 for these factors.
- Group 2 is characterized by a high factor F2 – costs of innovation. Its coefficient of variation is 0.31, which indicates the homogeneity of the cluster data for this factor. In addition, it is interesting that although the cost of innovation is high, the level of investment in innovation and human innovation potential is almost the lowest compared to other groups (except for group 3). This proves that policies to encourage innovation in this group have not been used effectively;
- Group 4 is characterized by a high factor F4 – production efficiency. he coefficient of variation of factor F4 of this regional group is 0.65, which means that there is heterogeneity in this factor. This is explained by the fact that in the cluster there are two regions with high production efficiency, superior to other regions, these are: the Murmansk region and the Republic of Mordovia;
- Groups 1 and 3 do not have typical factors like the other groups, however, when comparing these two groups with each other, it is clear that group 1 has a higher level of investment in innovation than the level of group 3, and its human potential also tends to be somewhat higher, than in group 3.

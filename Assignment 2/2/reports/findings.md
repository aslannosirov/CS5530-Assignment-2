# Part A
I took a random sample of 25 people from the dataset and compared their Glucose values to the whole population. The sample mean and maximum Glucose were close to the population values, but not exactly the same. This makes sense because a small sample can differ from the full dataset. The bar charts clearly show how the sample and population Glucose values compare.

# Part B
I calculated the 98th percentile of BMI for both the sample of 25 and the full population. The sample percentile was different from the population percentile. This happens because extreme values (like the 98th percentile) are sensitive to small sample sizes. The bar chart shows this difference clearly.

# Part C
For BloodPressure, I created 500 bootstrap samples of size 150 each. For every sample, I calculated the mean, standard deviation, and 98th percentile. The average bootstrap results were very close to the population values, especially for the mean and standard deviation. The 98th percentile showed more variation but was still reasonably close. The histograms show that the bootstrap distributions are centered near the population statistics, meaning the bootstrap method works well for estimating these values.

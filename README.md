# Master-Thesis - Analysis of Job Traces in HPC Systems
The usage of HPC systems is increasing as the number of users and
jobs getting submitted surges. Because of the diverse workload, understanding or
characterizing jobs has become difficult. This causes jobs to fail or be canceled
more frequently. Most HPC users are from various disciplines; they overestimate or
underestimate the resources required while submitting the jobs, such as time limit and
the number of nodes. The overestimation leads to more unused resource allocations
or node failures due to the underestimation of job resources. Overall, these problems
are affecting the performance and efficiency of the HPC systems.

In this thesis, job characteristics such as job size, length, partitions, wait time, etc.,
are analyzed in detail to understand the jobs and further characterize them. Then
the jobs are categorized according to their properties to identify the jobs’ groups,
using unsupervised machine learning called clustering. To mitigate the high resource
usage, the prediction of resources required, such as time-limit, number of nodes
needed, and Maximum RSS (resident set size) necessary for the job, using supervised
learning called regression. The canceled and failed jobs are analyzed to determine
the properties responsible for the job that failed or was canceled. The cluster usage
is analyzed to find the minimum and maximum cluster usage periods to avoid an
overload of jobs or scheduler being idle.

The analysis visualization showed many insights into the job characteristics and helped
to understand the users, jobs, and workload manager to optimize the workload manager
and HPC systems further. The clusters or groups created using unsupervised learning
models have been evaluated using the silhouette score method to find out how many
types of jobs are submitted to the cluster. The resource prediction using the machine
learning regression algorithm is evaluated using mean squared error, mean absolute
error, and r2 score. According to the metrics, the models worked well for the job
resource prediction. The analyzed failed and canceled jobs are plotted to find the
factors affecting the jobs. Also, the cluster usage analysis is visualized to see the
individual project active periods.

**Goals**

Task 1: Data pre-processing and basic statists.

Task 2: Deep understanding of job characteristics using data analytics.

Task 3: Analysis of the cluster utilization (Job’s arrival pattern and resource utilization) to strategize the submission of jobs.

Task 4: Unsupervised learning to create the clusters containing jobs of similar properties for further analysis.

Task 5: Supervised learning to predict the resources required for the jobs such as time limit, nodes, and MaxRSS to avoid jobs getting failed or canceled, and make efficient utilization of the resources.

Task 6: Analysis of failed and canceled jobs to determine the factors affecting it.

** The whole code for the above mentioned goals are in the repo Jupyter files. The Data should not be shared according to University of Paderborn Privacy rule. Hence, the data is not uploaded. The results and discussions are in the power point presentastion in Results folder -  **




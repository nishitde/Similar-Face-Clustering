# Similar Face Clustering

Using the command ```fetch_lfw_people```, we download a load a dataset of **3023** faces (62 different people).

Next, we standardize the data and convert it into a 100 dimensional data using ***Principal Component Analysis***.

## Cluster Centers

Following are the different cluster centers that I get upon executing the **K-Means Algortihm**:

![CC1](https://user-images.githubusercontent.com/60853516/83341678-29f5a980-a2b4-11ea-9521-ccb4d076ea47.png)
![CC2](https://user-images.githubusercontent.com/60853516/83341688-44c81e00-a2b4-11ea-8343-cb2f47ce424d.png)
![CC3](https://user-images.githubusercontent.com/60853516/83341696-55789400-a2b4-11ea-920b-0082052b4d9b.png)
![CC4](https://user-images.githubusercontent.com/60853516/83341697-5ad5de80-a2b4-11ea-895c-5d3ff0c7f17c.png)
![CC5](https://user-images.githubusercontent.com/60853516/83341701-5f9a9280-a2b4-11ea-9e7e-2469441d1c03.png)
![CC6](https://user-images.githubusercontent.com/60853516/83341705-645f4680-a2b4-11ea-80a5-8c564cb7d14e.png)
![CC7](https://user-images.githubusercontent.com/60853516/83341707-67f2cd80-a2b4-11ea-9516-3d2079263e0c.png)
![CC8](https://user-images.githubusercontent.com/60853516/83341708-6aedbe00-a2b4-11ea-9ad4-f7454c1307ea.png)
![CC9](https://user-images.githubusercontent.com/60853516/83341709-6d501800-a2b4-11ea-8606-26812ef502ba.png)
![CC10](https://user-images.githubusercontent.com/60853516/83341711-70e39f00-a2b4-11ea-809a-7b216f538092.png)

## Closest and Farthest Cluster Images

After finding the cluster centers, we calculate the Euclidean distance for each cluster, to find the min and max values for the clusters. Where, min would be the value for the closest and max would be the value for the farthest image in the cluster.

Following are the closest and Farthest cluster images for each respective cluster:

![CC1](https://user-images.githubusercontent.com/60853516/83341852-1cd9ba00-a2b6-11ea-91c3-9d0ca3660652.png)
![FC1](https://user-images.githubusercontent.com/60853516/83341854-22370480-a2b6-11ea-9def-92039c3e49d1.png)

![CC2](https://user-images.githubusercontent.com/60853516/83341857-2531f500-a2b6-11ea-8183-7790c79764e1.png)
![FC2](https://user-images.githubusercontent.com/60853516/83341859-27944f00-a2b6-11ea-97bc-58bd80655935.png)

![CC3](https://user-images.githubusercontent.com/60853516/83341860-2a8f3f80-a2b6-11ea-9883-dee86b0cd886.png)
![FC3](https://user-images.githubusercontent.com/60853516/83341862-2cf19980-a2b6-11ea-870e-14eba4e5275c.png)

![CC4](https://user-images.githubusercontent.com/60853516/83341865-30852080-a2b6-11ea-89c8-ef982ceac6a2.png)
![FC4](https://user-images.githubusercontent.com/60853516/83341868-3549d480-a2b6-11ea-83b0-3f7320b1458d.png)

![CC5](https://user-images.githubusercontent.com/60853516/83341870-3844c500-a2b6-11ea-989d-5d217fec2dd6.png)
![FC5](https://user-images.githubusercontent.com/60853516/83341871-3aa71f00-a2b6-11ea-826a-6cf94ea89e91.png)

![CC6](https://user-images.githubusercontent.com/60853516/83341874-3da20f80-a2b6-11ea-9d52-c79f71ca1183.png)
![FC6](https://user-images.githubusercontent.com/60853516/83341876-409d0000-a2b6-11ea-87ac-e7d1a2e35e97.png)

![CC7](https://user-images.githubusercontent.com/60853516/83341877-4397f080-a2b6-11ea-9921-de80c3f61933.png)
![FC7](https://user-images.githubusercontent.com/60853516/83341883-4692e100-a2b6-11ea-8ed7-8623428e6b91.png)

![CC8](https://user-images.githubusercontent.com/60853516/83341885-498dd180-a2b6-11ea-9942-416ffe4868e1.png)
![FC8](https://user-images.githubusercontent.com/60853516/83341887-4bf02b80-a2b6-11ea-84bd-88b4a3084ba6.png)

![CC9](https://user-images.githubusercontent.com/60853516/83341889-4f83b280-a2b6-11ea-9f3d-d2bdb5b72e6b.png)
![FC9](https://user-images.githubusercontent.com/60853516/83341891-527ea300-a2b6-11ea-9ebf-5f2e7bf01231.png)

![CC10](https://user-images.githubusercontent.com/60853516/83341894-54e0fd00-a2b6-11ea-943b-a538163a4006.png)
![FC10](https://user-images.githubusercontent.com/60853516/83341896-57435700-a2b6-11ea-89b1-9653d18072de.png)

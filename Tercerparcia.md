### Describe the different data analysis architectures

The most common architectures are mainly two: Lambda Architecture and Kappa Architecture. The main difference between the two is the 
data processing flows involved, but it is necessary to know concepts about batch processing and streaming processing.
* Lambda:
  - Oriented to traditional data analytics.
  - Large volumes of static data are collected and processed periodically while dynamic data is processed “on the fly”, thus combining 
  volume and speed.
* Kappa:
  - Oriented to real-time analytics (soft strict).
  - Data storage is avoided and is processed as soon as it is received, minimizing the time the data is in the pipeline.
  - The idea here is not to recompute all the data in the batch layer, but to do it in the streaming layer and only to recompute if
  there is a change in business logic.

### Describes the characteristics of a data center

* Security: The security and privacy of the data is essential. Access control measures are mandatory so that only authorized personnel 
can contact the data center. Protection tools such as data encryption must also be used, as well as security solutions against the loss 
of information.
* Storage capacity: Increasing amounts of data are being generated, but now companies can get storage units that have increasingly 
higher capacities or hire cloud services.
* Data transfer: When accessed they must be fast and effective, this refers to writing or reading. The network is essential here because 
it is generally used for access to information.
* Maintenance and prevention: You must have air conditioners to keep the place cool because the teams work 24/7. In addition, they must 
be equipped with specialized fire detection and protection systems for servers.

### Identify the characteristics of Cloud and Fog data analysis

* Cloud
  - They are in fixed monthly payments for use, without additional costs, since there is no need to invest in large infrastructure or 
licenses.
  - The data is always safe.
  - There is no need to have a large storage capacity.
  - Faster work when being based on the web.
  - Information in real time.
  - Strong investment in innovation.
  - Access to all information.
  - Access when you want and where you want, only with an Internet connection.

* Fog:
  - Proposes a solution to problems related to the implementation of the Internet of Things.
  - Reduces traffic between smart devices and cloud storage while saving costs.
  - Gives the user more visible control over the information that it generates.
  - Possibility of offline operation.
  
 ### Understand the concept of Data Engineering.

Use advanced programming as well as system building skills to create software solutions. The engineer understands not only how to build 
a data stream, but how to combine a variety of technologies and frameworks to create the best solution for the business.His tools of a 
data engineer can include systems like Oracle, Hadoop, MySQL, as well as languages. which include Java, Linux, SQL and JavaScript. They 
understand the operation or process of data analysis while the analyst is only responsible for analyzing the behavior of such data.

### Define the concepts of data acquisition, management, process and administration

* Acquisition: It is the process that is carried out to collect data from a population or sample of it. Many techniques are applied to 
collect them, such as surveys or questionnaires, but there are other ways where the computer is responsible for doing so, since we all 
generate data at any time and time.
* Management: When the data is acquired, they are generally raw and do not establish a clear order, so it is required to order them for 
easy analysis. It is important to do so since poor management could not provide true results. There are useful techniques such as tidy 
data.
* Process: When the data is already ordered, it can already be processed to become valuable information. Generally, tools are used to 
carry it out and graphs are created to show results. Python and R Studio are good tools for this part.
* Administration: The information and data generated are stored on a server. In this part, solutions are implemented to keep the 
information secure and stable. Backups are made for recovery, security, user authentication.

### Describe the Lambda and Kappa architectures

* In a lambda architecture it implements the information systems: batch and stream. The batch mode gives us a complete and reliable 
reach while the stream mode gives us the online data for instant decisions.
* In the kappa architecture, it focuses only on processing data as a sequence. For this architecture, incoming data is transmitted 
through a real-time layer and the results are placed in the service layer for queries.

### Describe the layers of each architecture

* Lambda:
  - The new information collected by the system is sent to both the batch layer and the streaming layer.
  - Batch layer manages the raw information, that is, without modifying it.
  - Serving Layer, indexes the Batch Views generated in the previous step so that they can be consulted with low latency.
  - Speed Layer, compensates for the high write latency that occurs in the serving layer and only takes into account new data.
  - The response to the queries made is built by combining the results of the Batch Views and the views in real time.

* Kappa:
  - Your proposal is to remove the batch layer leaving only the streaming layer. It has no beginning or end from a time point of view 
  and is continually processing new data as it arrives.
  
### Contrast the advantages and disadvantages of each big data architecture with respect to incremental architectures.

* Lambda
  - Advantages:
    - Keep the input data unchanged.
    - This allows data to be reprocessed when criteria changes occur.
  - Disadvantages:
    - Maintain different code to produce the same result from two cumbersome complex distributed systems
    - Very different code for MapReduce and Storm / Apache Spark
    - Plus, it's not just about different code, it's also about debugging and interacting with other products.
    - In the end it is a problem about divergent and different programming paradigms.
* Kappa
  - Advantages:
    - It is only recomputed when there is a change in the code.
    - Only one code is maintained.
    - Kafka data can be dumped to HDFS (disk), if any memory limitations.



  

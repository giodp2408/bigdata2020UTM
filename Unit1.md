# Big Data Class

## *Syllabus contents*

### The importance of data.

**Explain the impact of data in nowadays.**
* We can access to information from Internet, so we can know anything of way more digital and closer.
* In Sciencie and Medicine,  when collecting data about this fields, they permit to improve reatments and diagnoses.
* In education, there are training tools to customize the contents and adapt them to the abilities of each person.
* Social networks allow us to permanently connect to a worldwide network.
* In business, they help companies to make decisions to improve the way that they work.

**Explain the causes what increase data collection.**

The answer is simple, because we can generate a lot of data about us. This is possible thanks new tools or techniques and they can
obteined data that we could not do by ourself before. For example, the ability to connect several devices and sensors to the
Internet, who generates a lot of new data at exponential speeds.

### Fundamentals of Big Data.

**Define the concept of Big Data.**

The basic concept responds to data that is varied enough, large and generated very quickly and from different sources, but it 
cannot be processed or managed by conventional methods easily, although there are tools. There are 10 characteristics, but the most 
prominent are the volume because they process large volumes of unstructured data. The speed that data is received and used. 
Finally, the variety refers to the various types of data available, usually unstructured.

**Differentiate between open data and private data.**
* Open Data are public and accessible for anyone, companies and organizations.
* Closed Data frequently restricts its use, through licenses or through privacy or security.

**Differentiate between structured and unstructured data.**
* **Structured data:** It is information that is usually found in most databases. They can be easily sorted and processed by all 
data mining tools.
* **Unstructured data:** They have an internal structure, but they are not structured through predefined data schemas or models.

**Differentiate between stored data and moving data.**
* The stored data are those that are structured and that are used for their analysis and for the generation of information.
* Moving data is data that is being transmitted on a network. In addition, they are stored in different sources.

### Fundamentals of Data Analysis

**Define the meaning of data analysis.**

The data analysis is responsible for examining a set of data in order to obtain conclusions to make decisions, or simply expand 
knowledge on various topics.

### Explain the impact of data analysis in organizations.

Many industries use data analysis to draw conclusions and decide actions to implement. Its impact is shown in these three areas:
* **Marketing:** To predict consumer behavior.
* **Human Resources:** To maintain a good working environment and qualify potential employees.
* **Academics:** To select new students and to measure student performance.

### Explain the different types of data analysis.
* **Descriptive analysis:** Shows summary numerical data.
* **Inferential analysis:** Find different conclusions from the same data but different samples.
* **Diagnostic analysis:** Find the cause of an event found in the statistical analysis.
* **Predictive analysis:** Shows what can happen with previously used data.
* **Prescriptive analysis:** Combines all the previous analyzes to determine what action to take on a situation.

## *Other topics*

### MapReduce
It is a suitable programming model to process large data. Its extraction process consists of two processes:
**Map:** extract and assign values to certain keys for a single document.
**Reduce:** Accumulation and combination of document keys to create a unique reduced value for each key.

### Haddop 
It is a distributed computer library for large data and is based on MapReduce. Its file system is HDFS. It is also capable of 
making copies as a security method.

### Apache Spark
Programming environment for libraries with the purpose of massive data processing. Make calculations without using a hard disk, 
only with RAM. Designed to improve the speed and performance of BigData applications.

### LAMBDA and KAPPA architecture
* In a lambda architecture it implements the information systems: batch and stream. The batch mode gives us a complete and 
reliable reach while the stream mode gives us the online data for instant decisions.
* In the kappa architecture, it focuses only on processing data as a sequence. For this architecture, incoming data is 
transmitted through a real-time layer and the results are placed in the service layer for queries.

### Docker container
Docker is one of the containerization platforms that can be used to create and run containers. Virtual machines are slow and 
require a lot of time to boot, so containers are used that are fast and start quickly, since it uses the host operating system 
and shares the relevant libraries.

## *Git Commands*
* Git Init: Start / Create a new repository.
* Git Clone: Get a copy of an existing repository.
* Git Status: Current repository listing on files.
* Git Add: Add files to the commit.
* Git Log: Shows commit records.
* Git rm: Deletes a file from the repository.
* Git mv: Move or rename a file.
* Git diff -staged: Shows the difference between the staging area and the commit.
* Git checkout: Used to return or switch between commits.
* Git checkout master: Return to the main branch (Last commit).
* Git commit --amend: Allows you to combine the current changes with the previous commit. Add "-m" for comment.
* Git reset: Remove commits, it has 3 types:
  - Soft: Preserves the changes of the stage area and working area.
  - Mixed: Undo changes between the atage area but retain the working area.
  - Hard: Undo changes of the stage area and working area.


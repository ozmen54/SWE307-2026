# SWE307-2026 BIG DATA

## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Data visualization.</b></td>
      <td>
        <b>a)</b> Every person in the group must install GraalVM and MongoDB. <br> 
        <b>b)</b> Groups will use the attached CSV file as data source. Use only one column in this study, such as first group will use only <i>Col-1</i> data.  This file must manually be imported to MongoDB in the beginning.<br>
        <b>c)</b> There are 100 rows, your Java program will read one consequtive row every second from the MongoDB in cyclic fashion, and the double number read will be sent to the R function for plot as shown in the class.<br>
        <b>d)</b> Preferebly use <i>xyplot()</i> from lattice library. In your plot, x axis will be integer from [0-99] and y axis will plot the double value sent from your Java program.<br>
        <b>e)</b> Your plot should be <i>line</i> type and the line color should be <i>dark brown</i>. Use <i>grid</i> in your graph.<br>
        <b>f)</b> Block diagram: <a href = "https://github.com/ozmen54/SWE307-2025/blob/main/pro1block.png">Figure 1</a>. Example output: <a href = "https://github.com/ozmen54/SWE307-2026/blob/main/pro1.png">Figure 2</a> .
      </td>
      <td>8 Oct 2026 <br></td>
      <td><a href="pro1_2026.pdf">Project1</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>Redis Cache, Hadoop-HDFS.</b></td>
      <td>
        <b>a)</b> Employee and department data will be read from the database via Redis (see <a href="https://github.com/ozmen54/SWE307-2025/blob/main/pro2.png">Figure 1</a>). Implement CRUD operations on emp table of scott database. <br>
        <b>b)</b> Employee images will be fetched from HDFS (use these <a href="images.zip">example image files</a>).<br>
        <b>c)</b> There will be a single web page, on this page the information will be displayed in a table using the JOIN operation. Information to display: employee name, manager name, salary, commission, department (see <a href="https://github.com/ozmen54/SWE307-2025/blob/main/Screenshot.png">Figure 2</a>). <br>
        <b>d)</b> Show that the user image file uploading and displaying them on the web page work. <br>
        <b>e)</b> Show that your application runs as expected.
      </td>
      <td>5 Nov 2026<br></td>
      <td><a href="pro2_2026.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Kafka-Spark-Cassandra Data Path</b></td>
      <td>
        <b>a)</b> You are going to implement a big data system shown in <a href="https://github.com/ozmen54/SWE307-2026/blob/main/pro-3.pdf">Figure 1</a>. <br>
        <b>b)</b> You need to create a console application that genarates random data as described in the project document (<a href="https://github.com/ozmen54/SWE307-2026/blob/main/pro3-26.pdf">Project 3</a>). You can implement this server using any language as you wish. <br>
        <b>c)</b> You need to install Kafka, Spark and Cassandra along with Hodoop-HDFS. <br>
        <b>d)</b> You need to start up Kafka with the topics assigned to each user. Kafka will start queuing incoming expense records.<br>
        <b>e)</b> You will write some Spark scripts using Scala or Python that will fetch records on Kafka topics periodically in a loop. Every new record must be stored on Cassandra. <br>
        <b>f)</b> When a web request comes to controller endpoint, the Spark routine must answer this as described in the Project documentation. <br>
        <b>g)</b> There will be a single web page on your sytem that shows the similar output as you did on Project 2, however in this time there will be another column that shows instantaneous total expens amount. <br> 
      </td>
      <td>3 Dec 2026<br></td>
      <td><a href="pro3-26.pdf">Project3</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td><b>ETL with NiFi</b></td>
      <td>
        <b>a)</b> You are going to implement ETL system shown in <a href="https://github.com/ozmen54/SWE307-2026/blob/main/pro-4.pdf">Figure 1</a>. <br>
        <b>b)</b> Data sources will be two different EC2 instances on AWS or VMs on Azure: One will host MongoDB, and theother will host MySQL. The data will be provided here as cvs files: <a href="expense.csv">expense.csv</a>, <a href="emp.csv">emp.csv</a>, <a href="dept.csv">dept.csv</a>. <br>
        <b>c)</b> You need to install Apache-NiFi, Apache-Hive and Apache-Hodoop-HDFS. <br>
        <b>d)</b> Transfer and load the data to the databases using NiFi or other methods.<br>
        <b>e)</b> Design a NiFi pipeline, so data from two different sources will be collected to locally installed Hive with the same name database name (big25) and table names (or collection name).<br>
        <b>f)</b> Create the pipeline and fetch the data from different sources to your local computer and store them into Hive DB in JSON format.<br>
        <b>g)</b> Do some anaylitacal work using HiveQL queries with joins and show: "1) who (with name) spends how much for food or appliences?", "2) Which department made the most purchases?", "3) How spent the most?"<br>
      </td>
      <td>24 Dec 2026<br></td>
      <td><a href="pro4-26.pdf">Project4</a></td>
    </tr>
</body>
</table>



4.4 A Holistic counter in Servlet
---------------------------------
![2016-02-17 18](https://cloud.githubusercontent.com/assets/16971890/13106134/aa2be41a-d58c-11e5-9a0d-62bab9c5627a.png)

In this program we are going to make a such a servlet which will count the number of times it has been accessed and the number of threads created by the server.
In this example firstly we are going to create one class named as HolisticCounterInServlet. Now declare a variable counter of int with initial value 0, the value of this counter will be different for each servlet and create a Hashtable object. This object will be shared by all the threads in the container. Inside the doGet() method use the method getWriter() method of the response object which will return the PrintWriter object. 



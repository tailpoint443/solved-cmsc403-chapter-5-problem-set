Download Link: https://assignmentchef.com/product/solved-cmsc403-chapter-5-problem-set
<br>
Develop a class named Graph that extends Canvas, a built in class in the Python package tkinter.  You will use this class Graph as the parent class to GraphBar and GraphPie.  Calling these two classes will build and display in a graphical window either a bar chart or pie chart from the information provided.  Each graph has the following information:

<ul>

 <li>data, which consists of a 2-dimensional list containing a value, a title for the value, and a color for the graph. Here is an example: data = [[6, “A’s”, “blue”], [7, “B’s”, “yellow”],[4, “C’s”, “green”], [2, “F’s”, “red”]]</li>

 <li>width of the window</li>

 <li>height of the window</li>

</ul>

The parameter list for Graph is: Graph(parent, data, width = x, height = y), where Graph is a subclass of Canvas and parent would be window and x and y are window dimensions, and data is a list as described above.

The only difference between GraphBar and GraphPie is the graph that is created.  Please make sure that when constructing the graphs you only use the methods available through Canvas.  Utilizing other packages/tools is not allowed.

Your program will read in a text file containing the following information on each line separated by tabs: graphType, data (2-dimensional list), width, and height.  From this input your program will construct the appropriate object and display the graph of that object.  See the sample displays below.

Please let me know what questions you might have.  I have attached some sample Python files for your reference.












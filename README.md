Download Link: https://assignmentchef.com/product/solved-csci3005-homework1-dpknapsack
<br>
Your assignment consists of implementing a dynamic programming solution to the 0-1

knapsack problem.  Your solution must be stored in the DPKnapsack class.  Your class is required to have the following methods:

<ul>

 <li><em>DPKnapsack(int capacity, String itemFile):</em> a constructor to accept the default capacity and the name of a data file as arguments. The data file will have several lines of the form below (the first entry in each line is a string, the other two are integer values):</li>

</ul>

itemName itemWeight itemValue

<ul>

 <li><em>int optimalWeight( ):</em> returns the overall weight of the items in the optimal solution subset</li>

 <li><em>int optimalNumber ( ):</em> returns the number of items in the optimal solution subset</li>

 <li><em>boolean contains(String item):</em> returns true if <em>item</em> is in the optimal solution subset, false otherwise</li>

 <li><em>String solution( ):</em> returns a string representing the optimal solution subset. The precise format of the string is left to you.  Output which is appropriately labeled and formatted will obviously receive a better grade.  Obviously, the solution string must contain each item in the knapsack exactly once.</li>

</ul>

In addition, the methods below, which overload the ones already presented, require that your program solve the problem using the same items, but with a different knapsack capacity.

<ul>

 <li><em>int optimalWeight(int maxWeight): returns the overall weight of the items in the optimal solution subset for a knapsack with maxWeight. </em></li>

 <li><em>int optimalNumber(int maxWeight): returns the number of items in the optimal solution subset for a knapsack with maxWeight. </em></li>

 <li><em>boolean contains(String item, int maxWeight): returns true if item is in the optimal solution subset for a knapsack with maxWeight, false otherwise. </em></li>

 <li><em>String solution(int maxWeight): returns a string representing the optimal solution subset for a knapsack with maxWeight. </em></li>

</ul>

Naturally, you may develop additional private methods in the process of implementing your solution, but the methods above are required. Your solution should be stored in the <strong>DPKnapsack.java</strong> source file.  Comments for your class and its methods should follow javadoc guidelines.  The source file <strong>DPKTest.java</strong> is provided to test some of the functionality of your class.  However, you probably want to design additional testing cases before submitting your program for grading.

When done, submit your DPKnapsack.java solution (as well as any other .java files you write) to Mimir for testing.  Your submission should contain neither DPKTest.java nor any .txt files.
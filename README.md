Download Link: https://assignmentchef.com/product/solved-cse111-lab-6
<br>
Complete the <strong>Student </strong>class so that the <strong>main </strong>method prints the following:

<strong>Name of the Student: Bob </strong>

<strong>ID of the Student: 1 </strong>

<strong>Name of the Student: Tom </strong>

<strong>ID of the Student: 2 </strong>

<strong>Name of the Student: Jack </strong>

<strong>ID of the Student: 3 </strong>

<strong>Name of the Student: Jill </strong>

<strong>ID of the Student: 4 </strong>

<strong> </strong>

<strong>public class Student{ </strong>

<strong>//Your code here </strong>

<strong>} </strong>

<strong>public class Printer{ </strong>

<strong>public void printDetail(Student s){ </strong>

<strong>System.out.println(“Name of the Student: “+s.name); </strong>

<strong>System.out.println(“ID of the Student: “+s.id); </strong>

<strong>} </strong>

<strong>} </strong>

<strong> </strong>

<strong>public class Test{ public static void main(String [] args){ Student s1 = new Student(“Bob”, 1); </strong>

<strong>Student s2 = new Student(“Tom”, 2); </strong>

<strong>Student s3 = new Student(“Jack”, 3); </strong>

<strong>Student s4 = new Student(“Jill”, 4); Printer pr = new Printer(); pr.printDetail(s1); pr.printDetail(s2); pr.printDetail(s3); pr.printDetail(s4); </strong>

<strong>} </strong>

<strong>} </strong>




Task 2

<strong>public class Cat{ </strong> public String color = “White”;  public String action = “sitting”;

//your code here

<strong>} </strong> <strong>public class Test{ </strong> public static void main(String []

args){  Cat c1 = new Cat();

Cat c2 = new Cat(“Black”);

Cat c3 = new Cat(“Brown”,

“jumping”);

Cat c4 = new Cat(“Red”, “purring”);  c1.printCat();  c2.printCat();  c3.printCat();  c4.printCat();  c1.changeColor(“Blue”);  c3.changeColor(“Purple”);  c1.printCat();  c3.printCat();

}

<strong>} </strong>







Complete the <strong>Cat </strong>class so the <strong>main </strong>method above produces the following output:




<strong>White cat is sitting </strong>

<strong>Black cat is sitting </strong>

<strong>Brown cat is jumping </strong>

<strong>Red cat is purring </strong>

<strong>Blue cat is sitting </strong>

<strong>Purple cat is jumping </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Task 3 </strong>

<strong> </strong>

<strong>Using the StudentDriver class and it’s outputs given below, write the Student class:  </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="623"><strong>public class StudentDriver </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>{ </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>  public static void main(String[] args) </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>  { </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    Student s1; </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1= new Student(); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.nameDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.boloToAmiKe()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.addressDao()); </strong></td>

  </tr>

 </tbody>

</table>




<table width="0">

 <tbody>

  <tr>

   <td width="623"><strong>    System.out.println(s1.cgpaDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.nameBoshao(“Tonmoy Dewanjee”); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.addressBoshao(“Mirpur”); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.idBoshao(“16301157”); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.cgpaBoshao(4.0); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.nameDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.boloToAmiKe()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.addressDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.cgpaDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    Student s2 =  new Student(“Azibun Nuder”,”16301045″,”Uttara”,4.0); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2.nameDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2.boloToAmiKe()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2.addressDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2.cgpaDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    Student s3 = new Student(); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s3); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s3.nameDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s3.boloToAmiKe()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s3.addressDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s3.cgpaDao()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.standUp(); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s2.standUp(); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.tellMeYourName()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s2.tellMeYourName()); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s1.call(“Sumit Dutta”); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    s2.call(“Ananya Ritu”); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>    System.out.println(s1.add2Numbers(2,3)); </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

<strong>Output:  </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="623"><strong><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="fba88f8e9f9e958fbbcacbc29f9d9f9d9f">[email protected]</a> </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Ei name e kono student nai </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Student ei nai, abar id &#x1f61b; </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Naam nai .. thikana ashbe koi theke? </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>-4.0 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Tonmoy Dewanjee </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>16301157 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Mirpur </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>4.0 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="2c7f5859484942586c191b4814491f1a1e">[email protected]</a> </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Azibun Nuder </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>16301045 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Uttara </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>4.0 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e7b4939283828993a7d28382d28585d484">[email protected]</a> </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Ei name e kono student nai </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Student ei nai, abar id &#x1f61b; </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Naam nai .. thikana ashbe koi theke? </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>-4.0 </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Tonmoy Dewanjee is now standing up!! </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Azibun Nuder is now standing up!! </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Sir, my name is Tonmoy Dewanjee </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Sir, my name is Azibun Nuder </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Tonmoy Dewanjee: Hey, Sumit Dutta, Sir is calling you!! </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>Azibun Nuder: Hey, Ananya Ritu, Sir is calling you!! </strong></td>

  </tr>

  <tr>

   <td width="623"><strong>5 </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h1>Task 4</h1>

Write a function <strong>trim()</strong> that will take an array of characters as an input and remove multiple consecutive spaces from the array (<strong>You cannot use the String class in java</strong>). Following example code generates the output below:




<strong>public class Trim{ </strong>

<strong>  public static char [] trim(char [] input){ </strong>

<strong>      //Your code here </strong>

<strong>  } </strong>

<strong>  public static void main(String [] args){ </strong>

<strong>    char [] input = {‘T’,’h’,’i’,’s’,’ ‘,’ ‘,’ ‘,’ ‘,’ ‘,’i’,’s’,’ ‘,’ ‘,’ </strong>

<strong>‘,’ ‘,’a’,’ ‘,’ ‘,’ ‘,’ ‘,’t’,’e’,’s’,’t’,’.’};     for (int i = 0; i&lt; input.length; i++){ </strong>

<strong>      System.out.print(input[i]); </strong>

<strong>    } </strong>

<strong>    System.out.println(“”);     char []  output = trim(input);     for (int i = 0; i&lt; output.length; i++){ </strong>

<strong>      System.out.print(output[i]); </strong>

<strong>    } </strong>

<strong>    System.out.println(“”);     </strong>

<strong>  } }</strong>

<strong>This     is    a    test. This is a test. </strong>

<strong> </strong>

<h1>Task 5</h1>

Write a <strong><u>Java Code</u></strong> of a program that reads in a string (UPPER-case letters only) from the <strong><u>user</u></strong> and prints the letter that occurs <strong><u>second</u></strong> most often.<strong>  </strong>

<strong> </strong>

For example, if the user enters the word “REFERENCES”, your program should print the character R because the word has 4 E, 2 R, and all other character only once.

<strong> </strong>

<strong><u>Notes:</u></strong><strong>  </strong>

<strong>s.length()</strong>  returns the length of a string <strong>s</strong>.

<strong>s.charAt(int index) </strong>returns the character at the specified index of string <strong>s</strong>. An index ranges from 0 to length() – 1.

<strong><em> </em></strong><strong> </strong>

<h1>Task 6</h1>

Write a <strong><u>Java Code</u></strong> of a function that takes an array of integers (of positive and negative numbers) and the length or size of the array as parameters, then modifies the array by getting rid of the negative elements (the numbers after the removed one will have to shift forward to fill the gap of course). If there are multiple negative elements, remove all of those. The function returns the new size of the array.

<em> </em>

<h1>Task7</h1>

Write the <strong>removeOdd</strong> function below which takes in an array of numbers that has even and odd numbers mixed. This function <strong>removes</strong> the odd numbers and returns a <strong>compact</strong> array which only has the even numbers. For example output of the following code is:




<strong>Sample Input </strong>

21 33 44 66 11 1 88 45 10 9

<strong> </strong>

<strong>Sample Output </strong>

44 66 88 10

<strong>  </strong>

<strong>public class Test{ </strong>

<strong>  public static int [] removeOdd (int [] input){ </strong>

<strong>      </strong><strong>//Your code here </strong>

<strong>  } </strong>

<strong>  public static void main(String [] args){ </strong>

<strong>    int [] mixedArray = {21, 33, 44, 66, 11, 1, 88, 45, 10, 9};     for (int i = 0; i &lt; mixedArray.length; i++) { </strong>

<strong>      System.out.print(mixedArray[i] + ” “); </strong>

<strong>    } </strong>

<strong>    System.out.println(); </strong>

<strong>    int [] noOdd = removeOdd(mixedArray);     for (int i = 0; i &lt; noOdd.length; i++) { </strong>

<strong>      System.out.print(noOdd[i] + ” “); </strong>

<strong>    }     </strong>

<strong>  } </strong>

<strong>} </strong>




<strong> </strong>

<strong> </strong>




<h2>Task 8</h2>

<table width="0">

 <tbody>

  <tr>

   <td width="591"><strong>public class FinalT6A{ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public int temp = 4; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  private int sum; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  private int y = 1; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    temp+=1; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = temp – p; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = temp + x; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public void methodA(){     </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    int x=0, y =0; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = y + this.y;  </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = y + (++temp); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    x = x + 3 +  n; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

What is the output of the following code sequence?




<table width="0">

 <tbody>

  <tr>

   <td rowspan="8" width="307"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); q1.methodA();   </strong></td>

   <td width="96"><strong>x </strong></td>

   <td width="96"><strong>y </strong></td>

   <td width="91"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

 </tbody>

</table>




<h2>Task 9</h2>

<table width="0">

 <tbody>

  <tr>

   <td width="43"><strong>1.</strong></td>

   <td width="547"><strong>class msgClass{ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>2.</strong></td>

   <td width="547"><strong>  public int content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>3.</strong></td>

   <td width="547"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

<strong>       </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="43"><strong>1.</strong></td>

   <td width="547"><strong>public class Q5{ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>2.</strong></td>

   <td width="547"><strong>  private int sum; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>3.</strong></td>

   <td width="547"><strong>  private int y; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>4.</strong></td>

   <td width="547"><strong>  public int x; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>5.</strong></td>

   <td width="547"><strong>  public Q5(){ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>6.</strong></td>

   <td width="547"><strong>    sum = 3; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>7.</strong></td>

   <td width="547"><strong>    x = 1; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>8.</strong></td>

   <td width="547"><strong>    y = 6; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>9.</strong></td>

   <td width="547"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>10.</strong></td>

   <td width="547"><strong>  public void methodA(){ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>11.</strong></td>

   <td width="547"><strong>    int x=1, y=1; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>12.</strong></td>

   <td width="547"><strong>    msgClass [] msg = new msgClass[1]; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>13.</strong></td>

   <td width="547"><strong>    msgClass myMsg = new msgClass(); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>14.</strong></td>

   <td width="547"><strong>    myMsg.content = this.x; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>15.</strong></td>

   <td width="547"><strong>    msg[0] = myMsg; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>16.</strong></td>

   <td width="547"><strong>    msg[0].content = this.y + myMsg.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>17.</strong></td>

   <td width="547"><strong>    this.y = this.y + methodB(msg[0]); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>18.</strong></td>

   <td width="547"><strong>    y = methodB(msg[0]) + this.y; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>19.</strong></td>

   <td width="547"><strong>    x = y + methodB(msg, msg[0]); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>20.</strong></td>

   <td width="547"><strong>    sum = x + y + msg[0].content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>21.</strong></td>

   <td width="547"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>22.</strong></td>

   <td width="547"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>23.</strong></td>

   <td width="547"><strong>  private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>24.</strong></td>

   <td width="547"><strong>    int x = 1; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>25.</strong></td>

   <td width="547"><strong>    y = y + mg2[0].content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>26.</strong></td>

   <td width="547"><strong>    mg2[0].content = y + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>27.</strong></td>

   <td width="547"><strong>    x = x + 3 + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>28.</strong></td>

   <td width="547"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>29.</strong></td>

   <td width="547"><strong>    mg1.content = sum – mg2[0].content ; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>30.</strong></td>

   <td width="547"><strong>    System.out.println(this.x + ” ” + this.y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>31.</strong></td>

   <td width="547"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>32.</strong></td>

   <td width="547"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>33.</strong></td>

   <td width="547"><strong>  private int methodB(msgClass mg1){ </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>34.</strong></td>

   <td width="547"><strong>    int x = 1, y = 1; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>35.</strong></td>

   <td width="547"><strong>    y = sum + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>36.</strong></td>

   <td width="547"><strong>    this.y = y + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>37.</strong></td>

   <td width="547"><strong>    x = this.x + 3 + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>38.</strong></td>

   <td width="547"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>39.</strong></td>

   <td width="547"><strong>    this.x = mg1.content + x + 2; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>40.</strong></td>

   <td width="547"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>41.</strong></td>

   <td width="547"><strong>    return y; </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>42.</strong></td>

   <td width="547"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="43"><strong>43.</strong></td>

   <td width="547"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

<strong>Write the output of the following code: </strong><strong>[Answer on the question paper] </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="384"><strong>Q5 q = new Q5(); </strong><strong>q.methodA(); </strong><strong> </strong><strong> </strong></td>

   <td width="67"><strong>x </strong></td>

   <td width="67"><strong>y </strong></td>

   <td width="67"><strong>sum </strong></td>

  </tr>

 </tbody>

</table>




<h1>Task 10</h1>

<table width="0">

 <tbody>

  <tr>

   <td width="523"><strong>public class Quiz3A{ </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public int temp = 4; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public int sum; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public int y; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public Quiz3A(){ </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    y = temp – 1; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    sum = temp + 1; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    temp+=2; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public Quiz3A(int k){ </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    temp = temp++; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    sum = ++temp + k; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    y = sum – 1; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  public int methodB(int m, int n){ </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    y = y + m + (++temp); </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    x = x + 2 +  n; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="523"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Consider the following code: </strong>

<table width="0">

 <tbody>

  <tr>

   <td rowspan="10" width="295"><strong>    Quiz3A a1 = new Quiz3A();     a1.methodB(1,2); </strong><strong>    Quiz3A a2 = new Quiz3A(3);     a2.methodB(2,4);     a1.methodB(2,1);     a2.methodB(1,3); </strong></td>

   <td width="96"><strong>x</strong></td>

   <td width="84"><strong>y</strong></td>

   <td width="96"><strong>sum</strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<h1>Task 11</h1>




<table width="0">

 <tbody>

  <tr>

   <td width="591"><strong>public class FinalT6A{ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public int temp = 3; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  private int sum; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  private int y = 2; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    temp+=3; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = temp – p; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = temp + x; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public void methodA(){     </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    int x=0, y =0; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = y + this.y;  </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    y = y + (++temp); </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    x = x + 2 +  n; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="591"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

What is the output of the following code sequence?




<table width="0">

 <tbody>

  <tr>

   <td rowspan="8" width="307"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); </strong><strong>FinalT6A q2 = new FinalT6A(4,5); q2.methodA(); </strong></td>

   <td width="96"><strong>x</strong></td>

   <td width="96"><strong>y</strong></td>

   <td width="91"><strong>sum</strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

   <td width="91"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Task 12</strong>

<table width="0">

 <tbody>

  <tr>

   <td width="37">1</td>

   <td width="552"><strong>public class Scope{  </strong></td>

  </tr>

  <tr>

   <td width="37">2</td>

   <td width="552"><strong>public int x = 1; </strong></td>

  </tr>

  <tr>

   <td width="37">3</td>

   <td width="552"><strong>public int y = 100; </strong></td>

  </tr>

  <tr>

   <td width="37">4</td>

   <td width="552"><strong>public void met1(){ </strong></td>

  </tr>

  <tr>

   <td width="37">5</td>

   <td width="552"><strong>    int x = 3; </strong></td>

  </tr>

  <tr>

   <td width="37">6</td>

   <td width="552"><strong>    x = this.x + 1; </strong></td>

  </tr>

  <tr>

   <td width="37">7</td>

   <td width="552"><strong>    y = y + this.x + 1; </strong></td>

  </tr>

  <tr>

   <td width="37">8</td>

   <td width="552"><strong>    x = y + met2(x+y) + y; </strong></td>

  </tr>

  <tr>

   <td width="37">9</td>

   <td width="552"><strong>    System.out.println(x); </strong></td>

  </tr>

  <tr>

   <td width="37">10</td>

   <td width="552"><strong>    System.out.println(y); </strong></td>

  </tr>

  <tr>

   <td width="37">11</td>

   <td width="552"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="37">12</td>

   <td width="552"><strong>  public int met2(int y){     </strong></td>

  </tr>

  <tr>

   <td width="37">13</td>

   <td width="552"><strong>    System.out.println(x); </strong></td>

  </tr>

  <tr>

   <td width="37">14</td>

   <td width="552"><strong>    System.out.println(y); </strong></td>

  </tr>

  <tr>

   <td width="37">15</td>

   <td width="552"><strong>    this.x = x + y;     </strong></td>

  </tr>

  <tr>

   <td width="37">16</td>

   <td width="552"><strong>    this.y = this.y + 200;     </strong></td>

  </tr>

  <tr>

   <td width="37">17</td>

   <td width="552"><strong>    return x + y; </strong></td>

  </tr>

  <tr>

   <td width="37">18</td>

   <td width="552"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="37">19</td>

   <td width="552"><strong>} </strong></td>

  </tr>

  <tr>

   <td colspan="2" width="589"> What is the output of the following code sequence?<strong>Scope q2 = new Scope(); </strong><strong>q2.met1(); q2.met2(); q2.met1(); q2.met2(); </strong> <h2>Task 13</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class FinalT6A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 4; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int y = 1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp+=1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – p; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 3 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table>What is the output of the following code sequence?


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="2" width="307"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="96"><strong>y </strong></td>

       <td width="91"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td rowspan="6" width="307"><strong>q1.methodA();   </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

     </tbody>

    </table>  <h2>Task 14</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>4.</strong></td>

       <td width="547"><strong>class msgClass{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>5.</strong></td>

       <td width="547"><strong>  public int content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>6.</strong></td>

       <td width="547"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>      </strong>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>44.</strong></td>

       <td width="547"><strong>public class Q5{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>45.</strong></td>

       <td width="547"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>46.</strong></td>

       <td width="547"><strong>  private int y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>47.</strong></td>

       <td width="547"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>48.</strong></td>

       <td width="547"><strong>  public Q5(){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>49.</strong></td>

       <td width="547"><strong>    sum = 3; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>50.</strong></td>

       <td width="547"><strong>    x = 1; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>51.</strong></td>

       <td width="547"><strong>    y = 6; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>52.</strong></td>

       <td width="547"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>53.</strong></td>

       <td width="547"><strong>  public void methodA(){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>54.</strong></td>

       <td width="547"><strong>    int x=1, y=1; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>55.</strong></td>

       <td width="547"><strong>    msgClass [] msg = new msgClass[1]; </strong></td>

      </tr>

     </tbody>

    </table>


    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>56.</strong></td>

       <td width="547"><strong>    msgClass myMsg = new msgClass(); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>57.</strong></td>

       <td width="547"><strong>    myMsg.content = this.x; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>58.</strong></td>

       <td width="547"><strong>    msg[0] = myMsg; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>59.</strong></td>

       <td width="547"><strong>    msg[0].content = this.y + myMsg.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>60.</strong></td>

       <td width="547"><strong>    this.y = this.y + methodB(msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>61.</strong></td>

       <td width="547"><strong>    y = methodB(msg[0]) + this.y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>62.</strong></td>

       <td width="547"><strong>    x = y + methodB(msg, msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>63.</strong></td>

       <td width="547"><strong>    sum = x + y + msg[0].content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>64.</strong></td>

       <td width="547"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>65.</strong></td>

       <td width="547"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>66.</strong></td>

       <td width="547"><strong>  private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>67.</strong></td>

       <td width="547"><strong>    int x = 1; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>68.</strong></td>

       <td width="547"><strong>    y = y + mg2[0].content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>69.</strong></td>

       <td width="547"><strong>    mg2[0].content = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>70.</strong></td>

       <td width="547"><strong>    x = x + 3 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>71.</strong></td>

       <td width="547"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>72.</strong></td>

       <td width="547"><strong>    mg1.content = sum – mg2[0].content ; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>73.</strong></td>

       <td width="547"><strong>    System.out.println(this.x + ” ” + this.y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>74.</strong></td>

       <td width="547"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>75.</strong></td>

       <td width="547"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>76.</strong></td>

       <td width="547"><strong>  private int methodB(msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>77.</strong></td>

       <td width="547"><strong>    int x = 1, y = 1; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>78.</strong></td>

       <td width="547"><strong>    y = sum + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>79.</strong></td>

       <td width="547"><strong>    this.y = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>80.</strong></td>

       <td width="547"><strong>    x = this.x + 3 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>81.</strong></td>

       <td width="547"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>82.</strong></td>

       <td width="547"><strong>    this.x = mg1.content + x + 2; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>83.</strong></td>

       <td width="547"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>84.</strong></td>

       <td width="547"><strong>    return y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>85.</strong></td>

       <td width="547"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>86.</strong></td>

       <td width="547"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong>Write the output of the following code: </strong><strong>[Answer on the question paper] </strong>


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="6" width="384"><strong>Q5 q = new Q5(); </strong><strong>q.methodA(); </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong></td>

       <td width="67"><strong>x </strong></td>

       <td width="67"><strong>y </strong></td>

       <td width="67"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong> </strong> <h2>Task 15</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class FinalT6A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int y = 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp+=3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – p; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 2 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table>What is the output of the following code sequence?


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="4" width="307"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); q1.methodA();   </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="96"><strong>y </strong></td>

       <td width="91"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td rowspan="4" width="307"></td>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

     </tbody>

    </table>   <h2>Task 16</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>7.</strong></td>

       <td width="547"><strong>class msgClass{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>8.</strong></td>

       <td width="547"><strong>  public int content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>9.</strong></td>

       <td width="547"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>      </strong>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>87.</strong></td>

       <td width="547"><strong>public class Q5{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>88.</strong></td>

       <td width="547"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>89.</strong></td>

       <td width="547"><strong>  private int y; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>90.</strong></td>

       <td width="547"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>91.</strong></td>

       <td width="547"><strong>  public Q5(){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>92.</strong></td>

       <td width="547"><strong>    sum = 8; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>93.</strong></td>

       <td width="547"><strong>    x = 2; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>94.</strong></td>

       <td width="547"><strong>    y = 4; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>95.</strong></td>

       <td width="547"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>96.</strong></td>

       <td width="547"><strong>  public void methodA(){ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>97.</strong></td>

       <td width="547"><strong>    int x=0, y=0; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>98.</strong></td>

       <td width="547"><strong>    msgClass [] msg = new msgClass[1]; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>99.</strong></td>

       <td width="547"><strong>    msgClass myMsg = new msgClass(); </strong></td>

      </tr>

     </tbody>

    </table>


    <table width="0">

     <tbody>

      <tr>

       <td width="44"><strong>100</strong></td>

       <td width="546"><strong>.    myMsg.content = this.x; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>101</strong></td>

       <td width="546"><strong>.    msg[0] = myMsg; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>102</strong></td>

       <td width="546"><strong>.    msg[0].content = this.y + myMsg.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>103</strong></td>

       <td width="546"><strong>.    this.y = this.y + methodB(msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>104</strong></td>

       <td width="546"><strong>.    y = methodB(msg[0]) + this.y; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>105</strong></td>

       <td width="546"><strong>.    x = y + methodB(msg, msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>106</strong></td>

       <td width="546"><strong>.    sum = x + y + msg[0].content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>107</strong></td>

       <td width="546"><strong>.    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>108</strong></td>

       <td width="546"><strong>.  } </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>109</strong></td>

       <td width="546"><strong>.  private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>110</strong></td>

       <td width="546"><strong>.    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>111</strong></td>

       <td width="546"><strong>.    y = y + mg2[0].content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>112</strong></td>

       <td width="546"><strong>.    mg2[0].content = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>113</strong></td>

       <td width="546"><strong>.    x = x + 30 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>114</strong></td>

       <td width="546"><strong>.    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>115</strong></td>

       <td width="546"><strong>.    mg1.content = sum – mg2[0].content ; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>116</strong></td>

       <td width="546"><strong>.    System.out.println(this.x + ” ” + this.y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>117</strong></td>

       <td width="546"><strong>.    return sum; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>118</strong></td>

       <td width="546"><strong>.  } </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>119</strong></td>

       <td width="546"><strong>.  private int methodB(msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>120</strong></td>

       <td width="546"><strong>.    int x = 0, y = 0; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>121</strong></td>

       <td width="546"><strong>.    y = sum + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>122</strong></td>

       <td width="546"><strong>.    this.y = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>123</strong></td>

       <td width="546"><strong>.    x = this.x + 30 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>124</strong></td>

       <td width="546"><strong>.    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>125</strong></td>

       <td width="546"><strong>.    this.x = mg1.content + x + 2; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>126</strong></td>

       <td width="546"><strong>.    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>127</strong></td>

       <td width="546"><strong>.    return y; </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>128</strong></td>

       <td width="546"><strong>.  } </strong></td>

      </tr>

      <tr>

       <td width="44"><strong>129</strong></td>

       <td width="546"><strong>.} </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong>Write the output of the following code: </strong><strong>[Answer on the question paper] </strong>


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="6" width="384"><strong>Q5 q = new Q5(); </strong><strong>q.methodA(); </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong></td>

       <td width="67"><strong>x </strong></td>

       <td width="67"><strong>y </strong></td>

       <td width="67"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

     </tbody>

    </table><strong> </strong>  <h2>Task 17</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class FinalT6A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int y = 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp+=1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – p; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 3 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 4 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table> What is the output of the following code sequence?  <strong>[Answer on question paper]</strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="5" width="307"><strong>FinalT6A q1 = new FinalT6A(5,6); q1.methodA(); q1.methodA();   </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="96"><strong>y </strong></td>

       <td width="91"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td rowspan="3" width="307"></td>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><h2>Task 18</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>10.</strong></td>

       <td width="547"><strong>class msgClass{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>11.</strong></td>

       <td width="547"><strong>  public int content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>12.</strong></td>

       <td width="547"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>       </strong>

    <table width="0">

     <tbody>

      <tr>

       <td width="47"><strong>130.</strong></td>

       <td width="543"><strong>public class Q5{ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>131.</strong></td>

       <td width="543"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>132.</strong></td>

       <td width="543"><strong>  private int y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>133.</strong></td>

       <td width="543"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>134.</strong></td>

       <td width="543"><strong>  public Q5(){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>135.</strong></td>

       <td width="543"><strong>    sum = 1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>136.</strong></td>

       <td width="543"><strong>    x = 2; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>137.</strong></td>

       <td width="543"><strong>    y = 3; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>138.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>139.</strong></td>

       <td width="543"><strong>  public void methodA(){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>140.</strong></td>

       <td width="543"><strong>    int x=1, y=1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>141.</strong></td>

       <td width="543"><strong>    msgClass [] msg = new msgClass[1]; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>142.</strong></td>

       <td width="543"><strong>    msgClass myMsg = new msgClass(); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>143.</strong></td>

       <td width="543"><strong>    myMsg.content = this.x; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>144.</strong></td>

       <td width="543"><strong>    msg[0] = myMsg; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>145.</strong></td>

       <td width="543"><strong>    msg[0].content = this.y + myMsg.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>146.</strong></td>

       <td width="543"><strong>    this.y = this.y + methodB(msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>147.</strong></td>

       <td width="543"><strong>    y = methodB(msg[0]) + this.y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>148.</strong></td>

       <td width="543"><strong>    x = y + methodB(msg, msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>149.</strong></td>

       <td width="543"><strong>    sum = x + y + msg[0].content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>150.</strong></td>

       <td width="543"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>151.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>152.</strong></td>

       <td width="543"><strong>  private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>153.</strong></td>

       <td width="543"><strong>    int x = 1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>154.</strong></td>

       <td width="543"><strong>    y = y + mg2[0].content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>155.</strong></td>

       <td width="543"><strong>    mg2[0].content = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>156.</strong></td>

       <td width="543"><strong>    x = x + 4 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>157.</strong></td>

       <td width="543"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>158.</strong></td>

       <td width="543"><strong>    mg1.content = sum – mg2[0].content ; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>159.</strong></td>

       <td width="543"><strong>    System.out.println(this.x + ” ” + this.y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>160.</strong></td>

       <td width="543"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>161.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>162.</strong></td>

       <td width="543"><strong>  private int methodB(msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>163.</strong></td>

       <td width="543"><strong>    int x = 5, y = 6; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>164.</strong></td>

       <td width="543"><strong>    y = sum + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>165.</strong></td>

       <td width="543"><strong>    this.y = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>166.</strong></td>

       <td width="543"><strong>    x = this.x + 7 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>167.</strong></td>

       <td width="543"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>168.</strong></td>

       <td width="543"><strong>    this.x = mg1.content + x + 8; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>169.</strong></td>

       <td width="543"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>170.</strong></td>

       <td width="543"><strong>    return y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>171.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>172.</strong></td>

       <td width="543"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>Write the output of the following code: </strong><strong>[Answer on the question paper] </strong>

    <table width="0">

     <tbody>

      <tr>

       <td width="387"><strong>Q5 q = new Q5(); </strong></td>

       <td width="68"><strong>x </strong></td>

       <td width="68"><strong>y </strong></td>

       <td width="68"><strong>sum </strong></td>

      </tr>

      <tr>

       <td rowspan="5" width="387"><strong>q.methodA(); </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong></td>

       <td width="68"></td>

       <td width="68"></td>

       <td width="68"></td>

      </tr>

      <tr>

       <td width="68"></td>

       <td width="68"></td>

       <td width="68"></td>

      </tr>

      <tr>

       <td width="68"></td>

       <td width="68"></td>

       <td width="68"></td>

      </tr>

      <tr>

       <td width="68"></td>

       <td width="68"></td>

       <td width="68"></td>

      </tr>

      <tr>

       <td width="68"></td>

       <td width="68"></td>

       <td width="68"></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong> </strong><h2>Task 19</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class FinalT6A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int y = 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp+=3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – p; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 2 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table>What is the output of the following code sequence?


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="3" width="307"><strong>FinalT6A q1 = new FinalT6A(3,2); FinalT6A q2 = new FinalT6A(2,3); q1.methodA(); q2.methodA();  </strong></td>

       <td width="96"><strong>X </strong></td>

       <td width="96"><strong>y </strong></td>

       <td width="91"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td rowspan="5" width="307"></td>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

     </tbody>

    </table> <h2>Task 20</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class MidQ3A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0, k = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int [] msg = new int[1]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    msg[0] = 5;     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    while (k &lt; 2){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      y = y + msg[0];        </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      x = y + methodB(msg, k);; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      sum = x + y + msg[0]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      k++; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int methodB(int [] mg2, int mg1){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + mg2[0]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 3 + mg1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    mg2[0] = y + mg1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    mg1 = mg1 + x + 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return mg1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>}</strong></td>

      </tr>

     </tbody>

    </table>In the above program show the values that are going to be printed as output if you run the methodA() on an instance of  Class <strong>MidQ3A</strong>.


    <table width="0">

     <tbody>

      <tr>

       <td width="197"><strong>x </strong></td>

       <td width="197"><strong>y </strong></td>

       <td width="197"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

     </tbody>

    </table> <h2>Task 21</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class MidQ3B{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0, k = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int [] msg = new int[1]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    msg[0] = 5;     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    while (k &lt; 2){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      y = y + msg[0] + 1;        </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      x = y + methodB(msg, k); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      sum = x + y + msg[0]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>      k++; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int methodB(int [] mg2, int mg1){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + mg2[0]; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 2 + mg1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    mg2[0] = y + mg1 -2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    mg1 = mg1 + x + 1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return mg1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>}</strong></td>

      </tr>

     </tbody>

    </table>In the above program show the values that are going to be printed as output if you run the methodA() on an instance of  Class <strong>MidQ3B</strong>.


    <table width="0">

     <tbody>

      <tr>

       <td width="197"><strong>x </strong></td>

       <td width="197"><strong>y </strong></td>

       <td width="197"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

      <tr>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

       <td width="197"><strong> </strong></td>

      </tr>

     </tbody>

    </table> <h2>Task: 22</h2>


    <table width="0">

     <tbody>

      <tr>

       <td width="582"><strong>class A{ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int temp = 4; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int sum; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int y; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public A(){ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    y = temp – 2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = temp + 1; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    x = x + 1 +  n; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>}    </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>class B{ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int y = 5; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int temp = -5; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public int sum = 2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public B(){ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    y = temp + 3 ; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = 3 + temp + 2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  }   </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public B(B b){ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = b.sum; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    x = b.x; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    b.methodB(2,3); </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>   public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    int x = 2; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    x = x + 5 +  n; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  public void methodB(int m, int n){     </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    int  y = 0; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    methodA(x, y); </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    sum = x + y + sum; </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="582"><strong>} </strong></td>

      </tr>

     </tbody>

    </table> <strong>Consider the following code: </strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="6" width="173"><strong>A        </strong><strong>a1 = new A(); </strong><strong>B        </strong><strong>b1 = new B(); B b2 = new B(b1); b1.methodA(1, 2); b2.methodB(3, 2); </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="84"><strong>y </strong></td>

       <td width="96"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

     </tbody>

    </table>   <h2>Task 23</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>class A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 4; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public A(){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + 3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 2 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>class B{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = -5; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int y = 3; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int sum = 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public B(){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp + 3 ; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = 3 + temp + 2; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp-=1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  }   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public B(B b){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = b.sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = b.x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodB(int m, int n){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int  y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    methodA(x, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 2 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong>Consider the following code: </strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="4" width="295"><strong>A        </strong><strong>a1 = new A(); </strong><strong>B        </strong><strong>b1 = new B(); B b2 = new B(b1); a1.methodA(1, 1); b1.methodA(1, 2); b2.methodB(3, 2); </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="84"><strong>y </strong></td>

       <td width="96"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><h2>Task 24</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="37">1</td>

       <td width="535"><strong>class A{ </strong></td>

      </tr>

      <tr>

       <td width="37">2</td>

       <td width="535"><strong>  public int temp = 4; </strong></td>

      </tr>

      <tr>

       <td width="37">3</td>

       <td width="535"><strong>  public int sum = 1; </strong></td>

      </tr>

      <tr>

       <td width="37">4</td>

       <td width="535"><strong>  public int y = 2; </strong></td>

      </tr>

      <tr>

       <td width="37">5</td>

       <td width="535"><strong>  public A(){ </strong></td>

      </tr>

      <tr>

       <td width="37">6</td>

       <td width="535"><strong>    y = temp – 2; </strong></td>

      </tr>

      <tr>

       <td width="37">7</td>

       <td width="535"><strong>    sum = temp + 3; </strong></td>

      </tr>

      <tr>

       <td width="37">8</td>

       <td width="535"><strong>    temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="37">9</td>

       <td width="535"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="37">10</td>

       <td width="535"><strong>  public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="37">11</td>

       <td width="535"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="37">12</td>

       <td width="535"><strong>    y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="37">13</td>

       <td width="535"><strong>    x = x + 2 +  n; </strong></td>

      </tr>

      <tr>

       <td width="37">14</td>

       <td width="535"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="37">15</td>

       <td width="535"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="37">16</td>

       <td width="535"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="37">17</td>

       <td width="535"><strong>} </strong></td>

      </tr>

      <tr>

       <td width="37">18</td>

       <td width="535"><strong>class B{ </strong></td>

      </tr>

      <tr>

       <td width="37">19</td>

       <td width="535"><strong>  public int x = 1; </strong></td>

      </tr>

      <tr>

       <td width="37">21</td>

       <td width="535"><strong>  public int y = 33; </strong></td>

      </tr>

      <tr>

       <td width="37">22</td>

       <td width="535"><strong>  public int temp = 7; </strong></td>

      </tr>

      <tr>

       <td width="37">23</td>

       <td width="535"><strong>  public int sum = 6; </strong></td>

      </tr>

      <tr>

       <td width="37">24</td>

       <td width="535"><strong>  public B(){ </strong></td>

      </tr>

      <tr>

       <td width="37">25</td>

       <td width="535"><strong>    y = temp + 3 ; </strong></td>

      </tr>

      <tr>

       <td width="37">26</td>

       <td width="535"><strong>    sum = 3 + temp + 2; </strong></td>

      </tr>

      <tr>

       <td width="37">27</td>

       <td width="535"><strong>    temp-=1; </strong></td>

      </tr>

      <tr>

       <td width="37">28</td>

       <td width="535"><strong>  }   </strong></td>

      </tr>

      <tr>

       <td width="37">29</td>

       <td width="535"><strong>  public B(B b){ </strong></td>

      </tr>

      <tr>

       <td width="37">30</td>

       <td width="535"><strong>    sum = b.sum; </strong></td>

      </tr>

      <tr>

       <td width="37">31</td>

       <td width="535"><strong>    x = b.x; </strong></td>

      </tr>

      <tr>

       <td width="37">32</td>

       <td width="535"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="37">33</td>

       <td width="535"><strong>  public void methodA(int m, int n){ </strong></td>

      </tr>

      <tr>

       <td width="37">34</td>

       <td width="535"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="37">35</td>

       <td width="535"><strong>    y = y + m + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="37">36</td>

       <td width="535"><strong>    x = x + 7 +  n; </strong></td>

      </tr>

      <tr>

       <td width="37">37</td>

       <td width="535"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="37">38</td>

       <td width="535"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>  public void methodB(int m, int n){     </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    int  y =0; </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    methodA(x, y); </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    sum = x + y + this.sum; </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="37"></td>

       <td width="535"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>Consider the following code: </strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="4" width="295"><strong>A        </strong><strong>a1 = new A(); </strong><strong>B        </strong><strong>b1 = new B(); B b2 = new B(b1); a1.methodA(1, 1); b1.methodA(1, 2); b2.methodB(3, 2); </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="84"><strong>Y </strong></td>

       <td width="96"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

     </tbody>

    </table><h2>Task 25</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="454"><strong>public class A{ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int temp = 3; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int sum; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int y; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public A(){ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        y = temp – 1; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        sum = temp + 2; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public void methodA(int m, int [] n){ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        x = x + 2 +  (++n[0]); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        n[0] = sum + 2; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>} </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>public class B { </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int x = 1; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int sum = 2; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int temp = 3; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public int y = 5; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public B(){ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        y = temp + 1 ; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        x = 3 + temp + x; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        temp-=2; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    }   </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public B(B b){ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        sum = b.sum + sum; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        x = b.x + x; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public void methodA(int m, int [] n){ </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        y = y + m + (temp++); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        x = x + 5 +  (++n[0]); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        n[0] = sum + 7; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    public void methodB(int m, int n){     </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        int [] y = {0}; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        this.y = y[0] + this.y + m;  </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        x = this.y + 2 + temp – n; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        methodA(x, y); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        sum = x + y[0] + this.sum; </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>        System.out.println(x + ” ” + y[0]+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>    } </strong></td>

      </tr>

      <tr>

       <td width="454"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong>Consider the following code: </strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="5" width="295"><strong>int x[] = {23}; A a1 = new A(); </strong><strong>B b1 = new B(); B b2 = new B(b1); a1.methodA(1, x); b2.methodB(3, 2); a1.methodA(1, x); </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="84"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

      <tr>

       <td width="96"></td>

       <td width="84"></td>

       <td width="96"></td>

      </tr>

     </tbody>

    </table><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><h2>Task 26</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="591"><strong>public class FinalT6A{ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int temp = 4; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  private int y = 1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public FinalT6A(int x, int p){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    temp+=1; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = temp – p; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = temp + x; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public void methodA(){     </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x=0, y =0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + this.y;  </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = this.y + 2 + temp; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = x + y + methodB(temp, y); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  public int methodB(int temp, int n){ </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    int x = 0; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    y = y + (++temp); </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    x = x + 3 +  n; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="591"><strong>} </strong></td>

      </tr>

     </tbody>

    </table>What is the output of the following code sequence?


    <table width="0">

     <tbody>

      <tr>

       <td rowspan="8" width="307"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); q1.methodA();   </strong></td>

       <td width="96"><strong>x </strong></td>

       <td width="96"><strong>y </strong></td>

       <td width="91"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

      <tr>

       <td width="96"><strong> </strong></td>

       <td width="96"><strong> </strong></td>

       <td width="91"><strong> </strong></td>

      </tr>

     </tbody>

    </table>     <h2>Task 27</h2>

    <table width="0">

     <tbody>

      <tr>

       <td width="43"><strong>13.</strong></td>

       <td width="547"><strong>class msgClass{ </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>14.</strong></td>

       <td width="547"><strong>  public int content; </strong></td>

      </tr>

      <tr>

       <td width="43"><strong>15.</strong></td>

       <td width="547"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>       </strong>

    <table width="0">

     <tbody>

      <tr>

       <td width="47"><strong>173.</strong></td>

       <td width="543"><strong>public class Q5{ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>174.</strong></td>

       <td width="543"><strong>  private int sum; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>175.</strong></td>

       <td width="543"><strong>  private int y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>176.</strong></td>

       <td width="543"><strong>  public int x; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>177.</strong></td>

       <td width="543"><strong>  public Q5(){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>178.</strong></td>

       <td width="543"><strong>    sum = 3; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>179.</strong></td>

       <td width="543"><strong>    x = 1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>180.</strong></td>

       <td width="543"><strong>    y = 6; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>181.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>182.</strong></td>

       <td width="543"><strong>  public void methodA(){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>183.</strong></td>

       <td width="543"><strong>    int x=1, y=1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>184.</strong></td>

       <td width="543"><strong>    msgClass [] msg = new msgClass[1]; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>185.</strong></td>

       <td width="543"><strong>    msgClass myMsg = new msgClass(); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>186.</strong></td>

       <td width="543"><strong>    myMsg.content = this.x; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>187.</strong></td>

       <td width="543"><strong>    msg[0] = myMsg; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>188.</strong></td>

       <td width="543"><strong>    msg[0].content = this.y + myMsg.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>189.</strong></td>

       <td width="543"><strong>    this.y = this.y + methodB(msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>190.</strong></td>

       <td width="543"><strong>    y = methodB(msg[0]) + this.y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>191.</strong></td>

       <td width="543"><strong>    x = y + methodB(msg, msg[0]); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>192.</strong></td>

       <td width="543"><strong>    sum = x + y + msg[0].content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>193.</strong></td>

       <td width="543"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>194.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>195.</strong></td>

       <td width="543"><strong>  private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>196.</strong></td>

       <td width="543"><strong>    int x = 1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>197.</strong></td>

       <td width="543"><strong>    y = y + mg2[0].content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>198.</strong></td>

       <td width="543"><strong>    mg2[0].content = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>199.</strong></td>

       <td width="543"><strong>    x = x + 3 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>200.</strong></td>

       <td width="543"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>201.</strong></td>

       <td width="543"><strong>    mg1.content = sum – mg2[0].content ; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>202.</strong></td>

       <td width="543"><strong>    System.out.println(this.x + ” ” + this.y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>203.</strong></td>

       <td width="543"><strong>    return sum; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>204.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>205.</strong></td>

       <td width="543"><strong>  private int methodB(msgClass mg1){ </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>206.</strong></td>

       <td width="543"><strong>    int x = 1, y = 1; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>207.</strong></td>

       <td width="543"><strong>    y = sum + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>208.</strong></td>

       <td width="543"><strong>    this.y = y + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>209.</strong></td>

       <td width="543"><strong>    x = this.x + 3 + mg1.content; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>210.</strong></td>

       <td width="543"><strong>    sum = sum + x + y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>211.</strong></td>

       <td width="543"><strong>    this.x = mg1.content + x + 2; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>212.</strong></td>

       <td width="543"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>213.</strong></td>

       <td width="543"><strong>    return y; </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>214.</strong></td>

       <td width="543"><strong>  } </strong></td>

      </tr>

      <tr>

       <td width="47"><strong>215.</strong></td>

       <td width="543"><strong>} </strong></td>

      </tr>

     </tbody>

    </table><strong>Write the output of the following code: </strong><strong>[Answer on the question paper] </strong>

    <table width="0">

     <tbody>

      <tr>

       <td rowspan="2" width="384"><strong>Q5 q = new Q5(); </strong><strong>q.methodA(); </strong><strong> </strong><strong> </strong></td>

       <td width="67"><strong>x </strong></td>

       <td width="67"><strong>y </strong></td>

       <td width="67"><strong>sum </strong></td>

      </tr>

      <tr>

       <td width="67"></td>

       <td width="67"></td>

       <td width="67"></td>

      </tr>

     </tbody>

    </table> </td>

  </tr>

 </tbody>

</table>
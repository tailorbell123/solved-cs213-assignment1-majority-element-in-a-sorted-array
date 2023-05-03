Download Link: https://assignmentchef.com/product/solved-cs213-assignment1-majority-element-in-a-sorted-array
<br>



<ul>

 <li>For each problem, test cases (p&lt;x&gt;_t&lt;y&gt;.txt) will be provided in the test folder. Note that your code will be tested on hidden test cases on submission.</li>

 <li>Use the following command to compile p1.cpp: ​g++ p1.cpp​. An executable a.out is created. To run the executable, use the command ./a.out​</li>

 <li>USE ‘cin’ and ‘cout’ for taking input and printing respectively. To take input from a file abc.txt, use ​./a.out &lt; abc.txt</li>

 <li>Try to solve the problems with any solution you think of, and try to improve the solution to make it as efficient as possible. As we will be testing on huge test cases, try to make ‘intelligent’ solutions. Timing your code, as explained in class, might help.</li>

 <li>Students are expected to adhere to the highest standards of integrity and academic honesty. Acts such as copying in the examinations and sharing code for the programming assignments will be dealt with strictly, in accordance with the institute’s <a href="http://www.iitb.ac.in/newacadhome/procedures201521July.pdf">procedures</a>​ and ​<a href="http://www.iitb.ac.in/newacadhome/punishments201521July.pdf">disciplinary actions</a><u>​</u> for academic malpractice.</li>

</ul>

<strong><u>Definition(For P1 and P2)</u></strong>​: A ​<strong><em>majority element</em></strong>​ in an array A of size n is an element that appears ​<strong>strictly more</strong>​ than n/2 times (and hence there is at most one such element).

<strong>P1: Majority element in a Sorted array </strong>

Write a C++ program which checks whether an input element x is the majority element in a sorted array. It should print 1 if the element x is the majority element else prints 0

<u>Input format</u><u>​</u>: The first line contains n and x; the size of the sorted array and the element to be checked respectively.

The second line of input contains n integers

<u>Example</u><u>​</u>:

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Input</strong></td>

   <td width="312"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="312">7 31 2 3 3 3 3 10</td>

   <td width="312">1</td>

  </tr>

  <tr>

   <td width="312">8 41 4 2 4 4 4 6 6</td>

   <td width="312">0</td>

  </tr>

  <tr>

   <td width="312">5 31 1 1 2 2</td>

   <td width="312">0</td>

  </tr>

 </tbody>

</table>

<strong>         </strong>

<strong>P2: Majority Element </strong>

Write a C++ program which prints the majority element if it exists, else prints -1

<u>Input format</u><u>​</u>: The first line of the input contains n, the size of the array. The second line of input contains n integers.

<u>Example</u>:<u>​</u>

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Input</strong></td>

   <td width="312"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="312">93 3 4 2 4 4 2 4 4</td>

   <td width="312">4</td>

  </tr>

  <tr>

   <td width="312">83 3 4 2 4 2 4 4</td>

   <td width="312">-1</td>

  </tr>

 </tbody>

</table>




<strong>P3 : How many survive from the Claws?</strong>

There are <em><sup>n</sup></em>​ ​ guilty people in a line, the <em><sup>i</sup></em>​​-th of them holds a claw with length <em><sup>L</sup></em>​ ​<em>i</em>​. The bell rings and every person kills some of people in front of him. The people are allowed to kill from left to right, i.e. the first person gets to kill first and then the second and so on. Namely, the <em><sup>i</sup></em>​​-th person kills the <em><sup>j</sup></em>​​-th person if and only if <em>j</em>​​ &lt; ​<em>i</em>​ and <em>j</em>​​ ≥ ​<em>i</em>​ - ​<em>L</em>​<em>i</em>​.

You are given lengths of the claws. You need to find the total number of alive people after the bell rings.




<u>Input format</u><u>​</u>:

The first line contains one integer <em><sup>n</sup></em>​ ​ (<sup>1</sup>​  ≤ ​<em><sup>n</sup></em>​ ≤ <sup>10</sup>​<sup>6</sup>​) — the number of guilty people.

Second line contains <em><sup>n</sup></em>​ ​ space-separated integers <em><sup>L</sup></em>​ ​1<sup>,</sup>​  ​<em><sup>L</sup></em>​2​<sup>,</sup>  …, <em><sup>L</sup></em>​​<em>n</em>​ (<sup>0</sup>​  ≤ ​<em><sup>L</sup></em>​<em>i</em>​ ≤ 10<sup>9</sup>​ ​), where <em><sup>L</sup></em>​ ​<em>i</em>​ is the length of the <em><sup>i</sup></em>​​-th person’s claw. <u>Output format</u><u>​</u>:

Print one integer — the total number of alive people after the bell rings.

<u>Example:</u>

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Input  </strong></td>

   <td width="312"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="312">40 1 0 10</td>

   <td width="312">1 </td>

  </tr>

  <tr>

   <td width="312">20 0</td>

   <td width="312">2</td>

  </tr>

  <tr>

   <td width="312">101 1 3 0 0 0 2 1 0 3</td>

   <td width="312">3 </td>

  </tr>

 </tbody>

</table>




<strong>P4: Do you sleep during lectures? </strong>

Your friend Divya and you attend a calculus lecture. Lecture lasts <em><sup>n</sup></em>​ ​ minutes. Lecturer tells <em><sup>a</sup></em>​ ​<em>i</em> theorems during the <em><sup>i</sup></em>​​-th minute.

Divya is really interested in calculus, though it is so hard to stay awake for all the time of lecture. You are given an array <em><sup>t</sup></em>​​ of Divya’s behavior. If Divya is asleep during the <em><sup>i</sup></em>​​-th minute of the lecture then <em><sup>t</sup></em>​​<em>i</em> will be equal to <sup>0</sup>​ ​, otherwise it will be equal to <sup>1</sup>​ ​. When Divya is awake she writes down all the theorems she is being told — <em><sup>a</sup></em>​ ​<em>i</em>​ during the <em><sup>i</sup></em>​​-th minute. Otherwise she writes nothing.

You know some secret technique to keep Divya awake for <em><sup>k</sup></em>​ ​ minutes straight. However you can use it ​<strong>only once</strong>​. You can start using it at the beginning of any minute between <sup>1</sup>​ ​ and <em><sup>n</sup></em>​ ​ - ​<em><sup>k</sup></em>​ + <sup>1</sup>​. If you use it on some minute <em><sup>i</sup></em>​​ then Divya will be awake during minutes <em><sup>j</sup></em>​​ such that  and will write down all the theorems lecturer tells.

You task is to calculate the maximum number of theorems Divya will be able to write down if you use your technique ​<strong>only once</strong>​ to wake her up. <u>Input format</u><u>​</u>:

The first line of the input contains two integer numbers <em><sup>n</sup></em>​ ​ and <em><sup>k</sup></em>​ ​ (<sup>1</sup>​  ≤ ​<em><sup>k</sup></em>​ ≤ ​<em><sup>n</sup></em>​ ≤ <sup>10</sup>​5)​ — the duration of the lecture in minutes and the number of minutes you can keep Divya awake.

The second line of the input contains <em><sup>n</sup></em>​ ​ integer numbers <em><sup>a</sup></em>​ ​1<sup>,</sup>​  ​<em><sup>a</sup></em>​2<sup>,</sup>​  <sup>… </sup>​<em><sup>a</sup></em>​<em>n</em>​ ( <sup>1</sup>​ ≤ ​<em><sup>a</sup></em>​<em>i</em>​ ≤ <sup>10</sup>​4)​ — the number of theorems lecturer tells during the <em><sup>i</sup></em>​​-th minute.

The third line of the input contains <em><sup>n</sup></em>​ ​ integer numbers <em><sup>t</sup></em>​​1<sup>,</sup>​  ​<em><sup>t</sup></em>​2<sup>,</sup>​  <sup>… </sup>​<em><sup>t</sup></em>​<em>n</em>​ ( <sup>0</sup>​ ≤ ​<em><sup>t</sup></em>​<em>i</em>​ ≤ <sup>1</sup>​) — type of Divya’s behavior at the <em><sup>i</sup></em>​​-th minute of the lecture. <u>Output format</u><u>​</u>:

Print only one integer — the maximum number of theorems Divya will be able to write down if you use your technique ​<strong>only once</strong>​ to wake her up.




<u>Example</u>​:

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Input </strong></td>

   <td width="312"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="312">6 31 3 5 2 5 41 1 0 1 0 0</td>

   <td width="312">16 </td>

  </tr>

  <tr>

   <td width="312">5 22 3 8 9 80 1 0 0 0</td>

   <td width="312">20</td>

  </tr>

  <tr>

   <td width="312">3 18 1 70 0 0</td>

   <td width="312">8</td>

  </tr>

 </tbody>

</table>

In the first case the better way is to use the secret technique at the beginning of the third minute. Then the number of theorems Divya will be able to write down will be equal to <sup>16</sup>​              ​.

(Hint: Try to relate this question with the problem discussed in class related to maximum contiguous sum)

<strong>P5: Be Patient, it’s a long <em>queue</em></strong>​ ​<strong>!</strong>

Amit wants to enter a football stadium that has <sup>n</sup>​ entrances. But he is the last person to enter the​      stadium entrance.

There already is a queue of <sup>a</sup>​ i​ ​ people in front of the ​  <sup>i</sup>​ th ​ entrance. Each entrance allows one person​             from its queue to enter the stadium in one minute.

Allen uses the following strategy to enter the fan zone:

<ul>

 <li>Initially he stands in the end of the queue in front of the first entrance.</li>

 <li>Each minute, if he is not allowed into the fan zone during the minute (meaning he is not the first in the queue), he leaves the current queue and stands in the end of the queue of the next entrance (or the first entrance if he leaves the last entrance).</li>

</ul>

Determine the entrance through which Amit will finally enter the fan zone. <u>Input format</u><u>​</u>:

The first line contains a single integer <sup>n</sup>​ the number of entrances.​

The second line contains do not include Allen. There are no new people entering and joining the queue.<sup>n</sup>​ integers ​                                                         <sup>a</sup><sup>​ </sup>​1<sup>,a</sup><sub>​ </sub>​2<sup>,…,a</sup><sub>​ </sub>n​ : the number of people in queues. These numbers​ <sub>            </sub>

<u>Output format</u><u>​</u>:

Print a single integer — the number of entrance that Allen will use.

<u>Example</u>​ :

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Input </strong></td>

   <td width="312"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="312">42 3 2 0</td>

   <td width="312">3 </td>

  </tr>

  <tr>

   <td width="312">210 10</td>

   <td width="312">1 </td>

  </tr>

  <tr>

   <td width="312">65 2 6 5 7 4</td>

   <td width="312">6</td>

  </tr>

 </tbody>

</table>

In the first example the number of people (not including Amit) changes as follows:

[​<strong>2</strong>​,3,2,0]→[1,​<strong>2</strong>​,1,0]→[0,1,​<strong>0</strong>​,0]. The number in bold is the queue Amit stands in. We see that​     he will enter the fan zone through the third entrance.

In the second example the number of people (not including Amit) changes as follows: [​<strong>10</strong>​,10]→[9,​<strong>9</strong>​]→[​<strong>8</strong>​,8]→[7,​<strong>7</strong>​]→[​<strong>6</strong>​,6]→[5,​<strong>5</strong>​]→[​<strong>4</strong>​,4]→[3,​<strong>3</strong>​]→[​<strong>2</strong>​,2]→[1,​<strong>1</strong>​]→[​<strong>0</strong>​,0]

In the third example the number of people (not including Amit) changes as follows :

[​<strong>5</strong>​,2,6,5,7,4]→[4,​<strong>1</strong>​,5,4,6,3]→[3,0,​<strong>4</strong>​,3,5,2]→[2,0,3,​<strong>2</strong>​,4,1]→[1,0,2,1,​<strong>3</strong>​,0]→[0,0,1,0,2,

<strong>0</strong>​]

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>       </strong>
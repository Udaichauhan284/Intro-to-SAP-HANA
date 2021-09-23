# OpenSAP, An Introduction to SAP HANA
<b>.</b> In August 2006 Dr. Vishal Sikka Name new Database which is in developing phase from 1999 SAP HANA.
<b>.</b> In october 2009, product of SAP HANA is in development.
<b>.</b> In december 1st, SAP HANA launch
<b>.</b> In June 2011 SAP HANA, offically launch and generally avaiable.
<b>.</b> HANA stand for Hasso's New Architecture.

<b>-></b> SAP HANA Technology: Parallelism
-> HANA Technologies
<ul>
  <li>Multi Core Parallelism</li>
  <li>Data locality in memeory</li>
  <li>Column Structure</li>
  <li>rethought everything</li>
</ul>

-> First Customer of HANA is Collgate.
-> HANA all operators are operates in Parrllel.
-> HANA does on Ivy bridge processor 3.5 Billion scans/sec/core. and 12.5 Million aggregation/sec/core.
-> Intra-operator parrellel. it is 6 and half faster then parrellelism
<b>-> Inta-Operator Parrellelism: The ability to run part of a job of an operator in parallel.</b>

<b>->SAP HANA Technology: Row and Column Stores.</b>
<ul>
  <li>Benefits of ROW is that you can transaction very fastly.</li>
  <li>Benefits of Column is that you can analytical read very fast.</li>
  <li>BSEG set have 320 fields.</li>
</ul>
<b>Ques. What does optimistic latch-free index traversal enable you to do? </b>
<b><i>Ans. Store a transaction in-memory without locking the index.</i></b>
  
<b>Ques. What are row structures used for? </b>
<b><i>Ans.For keeping extremely high volume transactions in buffer before data is merged into columnar main store</i></b>

<b>-> SAP HANA Technologies: Projections, Dynamic Aggregation, Integrated Compression </b>
<ul>
  <li>Keep minimal projection as we know BSEG have 320 fields </li>
</ul>

<b>Ques. How often should you perform a dynamic projection?</b>
<b><i>Ans.As often as you need to</i></b>

<b> Ques. When you organize data in columns, what does integrated compression enable you to do? </b>
<b><i>Ans. 1.Use a dictionary to store bits instead of real data values.</i></b>
<b><i>2. Reduce the size of a column.</i></b>

<b>->SAP HANA Technology: Insert Only, Partitioning and Scale-Out, Active and Passive Storage</b>
<b>Ques.Which of the following capabilities were included in the SAP HANA database from the beginning?</b>
<b>Ans.Insert-only
Partitioning and scale-out
"Hot and Cold" storage </b>

<b>Ques.What does partitioning and scale-out enable you to do?</b>
<b>Ans.Create divisions between columns and store them on different machines.
Split large columns into several parts across different machines.</b>

<b>Ques.What are some of the benefits of "hot and cold"?</b>
<b>Ans.Additional compression in memory
Improved performance</b>

<b>->SAP HANA Technology: SQL, Libraries, and Summary</b>
<b>.</b>Supporting: SQL, MDX(language same like SQL started in Microsoft), text-function, map-reduce(introduce in DKOM in 2006),
 SQl Script, L(low level language), R, IMSL, AFL.</b>
 
 <b>Ques. In the context of the SAP HANA database, what is AFL? </b>
 <b>Ans.A way to integrate custom function libraries safely.</b>
 
<b>->SAP HANA Performance Bookmark</b>
<b>5 dimension of performance by Dr. Vishal Sikka</b>
<ul>
  <li>Data Science </li>
  <li>Querry Complexity</li>
  <li>Rate of Change</li>
  <li>data prepared</li>
  <li>response time</li>
</ul>

<b>Ques. What distinguishes customers who belong to the 10,000 club?</b>
<b>Ans.They have deployed the SAP HANA database to improve performance by 10,000 times.</b>

<b>Ques.According to Dr. Sikka, what do we need to re-think in the age of SAP HANA?</b>
<b>Ans:The notion of benchmarks for information processing systems and The concept of performance itself </b>

<b>-> SAP HANA Roadmap and Re-thinking software development </b>
-> Every Product
. business suite, EPR, CRM, Cloud application
.Application services also known as Native application services.

<b>Ques. Which products does SAP plan to run on SAP HANA? </b>
<b>Ans. Every product </b>

<b>Ques. Which application development options exist with SAP HANA? </b>
<b>Ans. Open, Integrated, Native </b>


<b>-> SAP HANA Practice and Summary </b>
<b>Ques. How many start-up companies are building products on SAP HANA? </b>
<b>Ans. >800 </b>

<b>Ques. What does Dr. Sikka believe is the cornerstone of SAP's future? </b>
<b>Ans. SAP HANA Enterprise Cloud </b>

<b>Ques. For the journey ahead with SAP HANA, what is the only limitation? </b>
<b>Ans. Your Imagination </b>
 



































 

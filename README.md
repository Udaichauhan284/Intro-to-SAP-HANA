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
<b><i>For keeping extremely high volume transactions in buffer before data is merged into columnar main store</i></b>
 

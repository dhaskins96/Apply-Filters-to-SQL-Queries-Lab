<h1>Apply Filters to SQL Queries Lab</h1>

 


<h2>Description</h2>
In this lab, I’m responsible for filtering specific employee and machine information from the database to investigate security issues and update computers. I'll start by retrieving failed login attempts after hours, logins on certain dates, and those from outside of Mexico. Then, I'll pull data on employees from the Marketing, Finance, and Sales departments, and exclude those in IT.
<br />


<h2>Languages and Utilities Used</h2>

- SQL

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/H3pLRir.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve after hours failed login attempts:  <br/>
<img src="https://i.imgur.com/vhONaO0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve login attempts on specific dates: <br/>
<img src="https://i.imgur.com/iXWJkkf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve login attempts outside of Mexico:  <br/>
<img src="https://i.imgur.com/AkJeLE7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve employees in Marketing:  <br/>
<img src="https://i.imgur.com/3Xg8Wwl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve employees in Finance or Sales:  <br/>
<img src="https://i.imgur.com/9HrxZA8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retrieve all employees not in IT:  <br/>
<img src="https://i.imgur.com/9zXOrtO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h1>Summary</h1>

In this lab, I retrieved after-hours failed login attempts by filtering unsuccessful logins made after 18:00 from the log_in_attempts table. Next, I retrieved all login attempts from the suspicious dates of 2022-05-08 and 2022-05-09. I also extracted logins that didn't originate in Mexico by filtering out entries with 'MEX' or 'MEXICO' using the NOT and LIKE operators. Additionally, I gathered information about employees in the Marketing department, those in Finance or Sales, and employees not in the Information Technology department by querying the employees table for specific department data.
</p>

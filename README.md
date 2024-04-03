# Ex03 Time Table
## Date:
03/04/24
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<title>Ragavn E time table</title>
<body>
<center>
  <img src="/static/logo.png"height="150" width="600" >
      <table border="1" cellspacing=4" cellpadding="15" bgcolor="black">
<caption> <h2>Slot ragav time table(23013327)</h2></caption>
<tr>
<th bgcolor="red">days/timings</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th bgcolor="yellow">12-1</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>     

  </tr>
<tr>
<th bgcolor="yellow">MON</th>
<th bgcolor="cyan">C</th>
<th bgcolor="cyan">chemistry</th>
<th bgcolor="cyan">   </th>
<th bgcolor="cyan">BEEE</th>
<th bgcolor="cyan">  </th>
 </tr>
   <tr>
<th bgcolor="yellow">TUES</th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">C</th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">chemistry</th>
<th bgcolor="cyan">  </th>
</tr>
<tr>
<th bgcolor="yellow">WED</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">BEEE</th>
<th bgcolor="cyan">  </th>
</tr>
<tr>
<th bgcolor="yellow">THURS</th>
<th bgcolor="cyan">Softskills</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">Maths</th>
</tr>
<tr>
<th bgcolor="yellow">FRI</th>
<th bgcolor="cyan">Maths</th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">  </th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">  </th>
</tr>

<table border="1" cellspacing=4" cellpadding="10" bgcolor="cyan" >
  <tr>
  <th bgcolor="browm">S.no</th>
  <h2><th bgcolor="browm">COURSE CODE</th></h2>
  <h2><th bgcolor="browm">COURSE TITTLE</th></h2>
  </tr>
  
  <tr>
  <th bgcolor="browm">1.</th>.
  <th>19AI304</th>
  <th>Fundamentals of C Programming(</th>
  </tr>
  
  
  <tr>
  <th bgcolor="browm">2.</th>
  <th>19AI414</th>
  <th>Fundamentals of Web Applications(FWAD)</th>
  </tr>
  
  
  <tr>
  <th bgcolor="browm">3.</th>
  <th>19CY205</th>
  <th>Principles of Chemistry in Engineering</th>
  </tr>
  <tr>
    <th bgcolor="browm">4.</th>
    <th>19EE305</th>
    <th>Basic Electrical,Electrical and Measurement Engineering(BEEE)</th>
    </tr>
    
    
    <tr>
    <th bgcolor="browm">5.</th>
    <th>19EY701</th>
    <th>Soft Skills(SS)</th>
    </tr>
    
    
    <tr>
    <th bgcolor="browm">6.</th>
    <th>19MA201</th>
    <th>Calculus and Matrix Algebra</th>
    </tr>
    
    </center>
    </body>
    </html>  
```

## OUTPUT
![output](https://github.com/lakshman1206/slot/assets/129931784/54566b0a-323e-4184-8bcf-bf09b87784e4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

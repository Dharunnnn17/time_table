# Ex03 Time Table
# Date:1.4.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<HTML>
    <HEAD>
    <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
    <center>
    <img src="/static/logo.png"height="100"width="540">    
    </center>
    <TABLE border = "1" align = "center" cellpadding = "5" bgcolor = "cyan">
    <CAPTION>SLOT TIME TABLE - DHARUN ARULSELVAN(212224220024)</CAPTION>
    <TR bgcolor = "yellow">
    <TH>DAY/TIME</TH>
    <TH>8 - 10</TH>
    <TH>10 - 12</TH>
    <TH rowspan = "7">Lunch</TH>
    <TH>1 - 3</TH>
    <TH>3 - 5</TH>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Monday</TH>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    
    </TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Tuesday</TH>
    <TD>FREE SLOT</TD>
    <TD>DIGITAL ELECTRONICS</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    <TD>FREE SLOT</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Wednesday</TH>
    <TD>DIGITAL ELECTRONICS</TD>
    <TD>PYTHON PROGRAMMING</TD>
    <TD>Mentor Meet</TD>
    <TD>HUMAN VALUES AND PROFESSIONAL ETHICS</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Thursday</TH>
    <TD>FREE SLOT</TD>
    <TD>REASONING ABILITY</TD>
    <TD>STATISTICS AND NUMBERICAL METHODS</TD>
    <TD>STOCK MARKET AND COMPANY OPERATIONS</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Friday</TH>
    <TD>FREE SLOT</TD>
    <TD>STOCK MARKET AND COMPANY OPERATIONS</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT</TD>
    <TD>ENVIRONMENTAL SCIENCE</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Saturday</TH>
    <TD>FREE SLOT</TD>
    <TD>PYTHON PROGRAMMING</TD>
    <TD>FREE SLOT</TD>
    <TD>STATISTICS AND NUMERICAL METHODS</TD>
    </TR>
    </TABLE>
    <BR>
    <TABLE border = "1" align = "center" cellpadding = "5">
    <CAPTION>Courses</CAPTION>
    <TR>
    <TH>S.No</TH>
    <TH>Course Code</TH>
    <TH>Course Name</TH>
    </TR>
    <TD>1.</TD>
    <TD>19EE404</TD>
    <TD>DIGITAL ELECTRONICS</TD>
    </TR>
    <TR>
    <TD>2.</TD>
    <TD>19AI414</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT</TD>
    </TR>
    <TR>
    <TD>3.</TD>
    <TD>19AI301</TD>
    <TD>PYTHON PROGRAMMING</TD>
    </TR>
    <TR>
    <TD>4.</TD>
    <TD>19HS801</TD>
    <TD>HUMAN VALUES AND PROFESSIONAL ETHICS</TD>
    </TR>
    <TR>
    <TD>5.</TD>
    <TD>19EY709</TD>
    <TD>REASONING ABILITY</TD>
    </TR>
    <TR>                
    <TD>6.</TD>
    <TD>19MS155</TD>
    <TD>STOCK MARKET AND COMPANY OPERATIONS</TD>
    </TR>
    <TR>                
    <TD>7.</TD>
    <TD>19MA211</TD>
    <TD>STATISTICS AND NUMERICAL METHODS</TD>
    </TR>
    <TR>                
    <TD>8.</TD>
    <TD>19CY801</TD>
    <TD>ENVIRONMENTAL SCIENCE</TD>
    </TR>

    </TABLE>
    </BODY>
    </HTML>
```
# OUTPUT
![Screenshot 2025-04-01 204732](https://github.com/user-attachments/assets/3273a0e9-d957-429b-9741-91437ab19fbd)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

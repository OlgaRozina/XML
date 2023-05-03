# This is a part of GIT homework - XML
## 1. Create an external repository called XML.: 
```
GitHub > New repository > Create repository 
```
***
## 2.Clone the XML repository to a local machine": 
```
$ git clone HTTPS
```
***
## 3. Inside the local XML create a “new.xml” file: 
```
$ cd XML
$ touch new.xml
```
***
## 4. Add changes to indexed files section
```
$ git add .
```
***
## 5. Commit the file
```
$ git commit -m "First commit"
```
***
## 6. Push the file to the external GitHub repository
```
$ git push
```
***
## 7. Edit the content of the file “new.xml” - write information about yourself. Everything is written in xml format
```
$ vim new.xml
press i

<?xml version="1.0" encoding="UTF-8"?>
<information>
	<name>Olga</name>
	<surname>Rozina</surmane>
	<age>24</age>
	<hobby>hiling</hobby>
	<country>Lithuania</country>
	<city>Vilnus</city>

</information>

press Esc > :wq
```
***
## 8. Push changes the an external repository
```
$ git add .
$ git commit -m "XML"
$ git push
```
***
## 9. Create a file "preferences.xml"
## 10. In the file "preferences.xml", add information about your preferences in xml format.
```
$ cat > preferences.xml
<?xml version="1.0" encoding="UTF-8"?>
<preferences>
    <eat>pizza</eat>
    <film>Interstellar</film>
    <series>Force_majeure</series>
    <time_of_year>summer</time_of_year>
</preferences>
```
***
## 11.Create a file "skills.xml" and add information about the skills that will be studied in the course in xml format
```
$ cat > skills.xml
<?xml version="1.0" encoding="UTF-8"?>
<skills>
    <skill_1>GIT</skill_1>
    <skill_2>SQL</skill_2>
    <skill_3>Postman</skill_3>
    <skill_4>Fiddler</skill_4
    <skill_5>Android_Studio</skill_5>
    <skill_6>Charles</skill_6>
    <skill_7>HTTP</skill_7>
    <skill_8>JSON</skill_8>
    <skill_9>XML</skill_9>
</skills>
```
***
## 11.Send two files at once to the external repository
```
$ git add .
$ git commit preferences.xml skills.xml -m "First commit"
$ git push
```
***
## 12. On the web interface, modify the file "bug_report.xml" and add a bug report in xml format.
```
<?xml version="1.0" encoding="UTF-8"?>
<bug_report_1>
    <ID>1</ID>
    <Enviroment>
         <OS>Win_10</OS>
         <Browser>Chrome_112</Browser>
     </Enviriment>
     <Summary>404 error when user is accessined the purchase order report page as a sales manager</Summary>
     <Actual_result>The report isn't showed as per the criteria selected</Actual_result>
     <Expected_result>The report should show as per the criteria selected</Expected_result>
     <Step_to_reproduce>
         <STR_1>Login as Sales Manager</STR_1>
         <STR_2>Go to the Reports page and choose Purchase Order Report</STR_2>
         <STR_3>Select any filter criteria</STR_3>
         <STR_4>Click the Show Report button</STR_4>
     </Step_to_reproduce>
     <Severity>Medium</Severity>
     <Priirity>Normal</Priirity>
     <Repruducibility>Always</Repruducibility>
     <Symptom>Missing_feature</Symptom>
     <Workaround>No</Workaround>
     <Attachment>Link</Attachment>
     <Status>Open</Status>
     <Author>Olga_Rozina<Author>
     <Sign_to>Olga_Fefilova</Sign_to>
</bug_repost_1> 
```
***
## 13. Press "Commit changes" and save changes on the web interface
```
>Commit changes
```
***
## 14. Synchronize the external and the local XML repository
```
$ git pull
```
***

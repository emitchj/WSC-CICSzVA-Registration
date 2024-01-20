<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this CICS Lab at Barcelona TechXchange. 

## 1) Information about IBM's virtual z environment

Click [here](IBM_TechXchange2024_Barcelona_Lab_Guide_CICS_4140.pdf){:target="_blank"} for detailed  information regarding available labs, User IDs, and keyboard mapping for the 3270 emulator.

## 2) Lab Exercise

Open the lab document associated with the excercise that you want to run and save it to your desktop.  The lab document provides detailed steps for the exercise.  

**Implementing Web Services in CICS**
- [L20: SOAP based web services](L20-V61.02-SOAP-WebServices-.pdf){:target="_blank"} 
- [L90: JSON based web services](L90-V61.03-JSON-Web-Service.pdf){:target="_blank"}

**Java Applications in CICS**
- [L34 - How to deploy a CICS application program coded in Java using the OSGI JVM](L34-V61.01-Java-OSGi-Program.pdf){:target="_blank"}
- [L72 - Java Servlet with Link to COBOL program](L72-V61.03-Java-Liberty-Program.pdf){:target="_blank"}
- [L93 - RESTful JSON with LINK to COBOL program using JAX-RS, JSON4j, JZOS](L93-V61.02-Java-Liberty-REST.pdf){:target="_blank"}

**z/OS Connect and CICS**
- [zOS Connect EE calling a CICS COBOL application (OpenAPI 3 Provider)](Developing RESTful  APIs  for accessing a CICS Program%20.pdf).
- [zOS Connect EE calling an API from a COBOL application (OpenAPI 2 Requster)](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/APIRequesters/Developing%20CICS%20API%20Requester%20Applications.pdf).


## 3) Lab Environment Access 

**Please enter your student ID email address (ex. student1@ibm.com) to retrieve your unique access details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

**Use the generated URL to open a new tab in your browser and then enter the generated ID and password to launch the virtual lab environment.**
## Help 
Click [here](Lab Environment Connection Instructions.pdf){:target="_blank"} for more details on how to access the IBM environment from your workstation.
Or notify your lab instructors:   [Any Armstrong](mailto: andy.armstrong@uk.ibm.com)   [Anthony Papageorgiou](mailto: a.papageorgiou@uk.ibm.com).

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Barcelona TechXchange CICS workshop. 

## Accessing the hands-on lab

Click [here](Lab Environment Connection Instructions.pdf){:target="_blank"} to read instructions for accessing the IBM systems from your workstation.

Click [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/OpenAPI2/Important-Read%20Me.pdf) for important information regarding credentials for accessing z/OS. This document also contains information on 3270 Emulator (IBM Personal Communications) keyboard mappings for the **Enter** and **Clear** keys as well as direction on how to customize the 3270 Personal Communications keyboard for use with Mac keyboards.

## Lab Exercise

Open the lab document associated with the excercise that you are interested in running.  

**Implementing Web Services in CICS**
- [L20: SOAP based CICS web services](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L20-V61.02-SOAP-WebServices-.pdf).
- [L90: CICS JSON based web services](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L90-V61.02-JSON-Web-Service.pdf).

**Java Applications in CICS**
- [L34 - How to deploy a CICS application program coded in Java using the OSGI JVM](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L34-V61.01-Java-OSGi-Program.pdf) 
- [L72 - Java Servlet with Link to CICS COBOL program](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L72-V61.03-Java-Liberty-Program.pdf).
- [L93 - RESTful JSON with LINK to COBOL program using JAX-RS, JSON4j, JZOS](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L93-V61.02-Java-Liberty-REST.pdf).

**z/OS Connect and CICS**
- [zOS Connect EE calling a CICS COBOL application (OpenAPI 3 Provider)](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/OpenAPI3/Developing%20Native%20Server%20RESTful%20APIs%20for%20accessing%20a%20CICS%20Program%20.pdf).
- [zOS Connect EE calling an API from a COBOL application (OpenAPI 2 Requster)](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/APIRequesters/Developing%20CICS%20API%20Requester%20Applications.pdf).

## Lab Environment Access 

**Please enter your student ID email address retrieve your unique log in details.**

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
Having trouble with labs? Notify your lab instructor:   [Any Armstrong](mailto: andy.armstrong@uk.ibm.com) or [Anthony Papageorgiou](mailto: a.papageorgiou@uk.ibm.com).

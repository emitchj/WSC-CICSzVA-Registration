<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending the IBM CICS Lab at SHARE Kansas City. 

## 1) Information about IBM's virtual z environment

Click [here](SHARE_KC2024_CICS_Labs_Guide_CICS.pdf){:target="_blank"} for detailed  information regarding available labs, User IDs, and keyboard mapping for the 3270 emulator.

## 2) Lab Exercise

Hardcopy lab documents are available for today's session.  The lab documents provide detailed steps for each exercise.

If you prefer a softcopy of the lab document, click the link below that corresponds with the exercise that you want to run, and then save the pdf file to your desktop.   
- [L20: SOAP based web services](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Integration%20Lab%20Exercises/L20-V61.02-SOAP-WebServices-.pdf){:target="_blank"} 
- [L34: How to deploy a CICS application program coded in Java using the OSGI JVM](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L34-V61.02.zVA-SimpleOSGiProgramWithCICSExplorer.pdf){:target="_blank"}
- [L72: Java Servlet with Link to COBOL program](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L34-V61.01.zVA-SimpleOSGiProgramWithCICSExplorer.pdf){:target="_blank"}
- [L90: JSON based web services](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Integration%20Lab%20Exercises/L90-V61.02-JSON-Web-Service.pdf){:target="_blank"}
- [L93: RESTful JSON with LINK to COBOL program using JAX-RS, JSON4j, JZOS](https://github.com/ibm-wsc/CICS-Wildfire-Workshops/blob/main/CICS-Java%20Lab%20Exercises/L93-V61.04.zVA-CICS-JSON-JAXRS.pdf){:target="_blank"}
- [L97: zOS Connect EE Developing RESTFull APIs for a CICS Channel program](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/OpenAPI2/Developing%20RESTful%20APIs%20for%20a%20CICS%20Channel%20program.pdf){:target="_blank"}


## 3) Lab Environment Access 

**Please enter your assigned student ID email address (ex. student1@ibm.com) to retrieve your unique access details.**

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
Or notify your lab instructors:   [Eric Higgins](mailto: erichiggins@us.ibm.com)   [Steve Fowlkes](mailto: fowlkes@us.ibm.com)   [Leigh Compton](mailto: lcompton@us.ibm.com).
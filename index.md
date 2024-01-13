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

## Lab Exercises and Presentations

All of the Lab Exercise have been posted at [https://github.com/ibm-wsc/CICS-Conference-Labs](https://github.com/ibm-wsc/CICS-Conference-Labs).

Here are links to the individual Lab Exercises.  Open the lab document that you are interested in running on your native windows machine.  Then follow the instructions below to access the virtual lab environment. 

- [CICS Web Services](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L20-V61.02-SOAP-WebServices-.pdf).
- [CICS A simple OGSi Program](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L34-V61.01-Java-OSGi-Program.pdf) 
- [Servlet with Link to CICS COBOL](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L72-V61.03-Java-Liberty-Program.pdf).
- [Using CICS JSON assistant](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L90-V61.02-JSON-Web-Service.pdf).
- [Java Rest services using JAX-RS(non-OSGI)](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L93-V61.02-Java-Liberty-REST.pdf).
- [z/OS Connect - CICS Provider API, open API 2](https://github.com/ibm-wsc/CICS-Conference-Labs/blob/main/L97-V30.05-zOSConnect-Provider.pdf).





**Please enter your email address used for registration to retrieve your unique log in details.**

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

## Help 
Having trouble with labs? Send an email to [Steve Fowlkes](mailto: fowlkes@us.ibm.com) or [Leigh Compton](mailto: lcompton@us.ibm.com) for help.

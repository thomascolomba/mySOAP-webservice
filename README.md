SOAP webservice


url of wsdl : http://localhost:8080/myJaxWs/helloService?wsdl <br/>
<br/>
request :<br/>
---<br/>
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ws="http://ws.test.org/"> <br/>
  &lt;soapenv:Header/> <br/>
    &lt;soapenv:Body> <br/>
      &lt;ws:sayHello> <br/>
        &lt;guestname>Thomas&lt;/guestname> <br/>
      &lt;/ws:sayHello> <br/>
    &lt;/soapenv:Body> <br/>
&lt;/soapenv:Envelope> <br/>
---<br/>
<br/>
Here is a screenshot of the webservice being addressed through the software SOAPUI<br/>
![Request executed through SOAPUI](./request_in_SOAPUI.png)
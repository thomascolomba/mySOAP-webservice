SOAP webservice


url of wsdl : http://localhost:8080/myJaxWs/helloService?wsdl <br/>
<br/>
request :<br/>
---<br/>
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ws="http://ws.test.org/"><br/>
  <soapenv:Header/><br/>
    <soapenv:Body><br/>
      <ws:sayHello><br/>
        <guestname>Thomas</guestname><br/>
      </ws:sayHello><br/>
    </soapenv:Body><br/>
</soapenv:Envelope><br/>
---<br/>
<br/>
Here is a screenshot of the webservice being addressed through the software SOAPUI<br/>
![Request executed through SOAPUI](./request_in_SOAPUI.png)
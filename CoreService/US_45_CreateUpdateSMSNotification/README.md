Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SMS</systemId>
            <content xsi:type="bo:CreateUpdateSMSNotificationReq">
               <action>A</action>
               <cifNumber>9144782363</cifNumber>
               <accountNumber>115471119</accountNumber>
               <phoneNumber>9</phoneNumber>
               <debitTreshold>200000</debitTreshold>
               <checkDebit>ON</checkDebit>
               <creditTreshold>200000</creditTreshold>
               <checkCredit>ON</checkCredit>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>238264</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0185                    **            003099200100001031931000000     0  I  0 000000  A        00000009144782363000000001154711199                   00000000200000000+ON00000000200000000+ON]

[ 0162    0078            0000    000000003099200100001031931238264000040320200 000000  080000 O.K.                                                                     ]
```
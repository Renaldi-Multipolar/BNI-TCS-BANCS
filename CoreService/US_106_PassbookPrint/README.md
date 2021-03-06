Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>ECHANNEL</systemId>
            <content xsi:type="bo:PassbookPrintReq">
               <accountNum>114479721</accountNum>
               <printedBalance>5500011032</printedBalance>
               <purgingFlag>N</purgingFlag>
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
               <coreJournal>325264</coreJournal>
            </header>
            <content xsi:type="bo:CompiledPassbookPrintRes">
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount>00000000800000000+</depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026036000+</balance>
                  <balanceEur>81011092038702000+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>92</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>COR WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1514</penDays>
                  <penType>1</penType>
                  <fillerM2>2</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-KOR TRF</fcaCurrCodeNo>
                  <narative></narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount>00000000800000000-</wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005484226036000+</balance>
                  <balanceEur>80999276438702000+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>42</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1514</penDays>
                  <penType>2</penType>
                  <fillerM2>7</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-BILL PAYMENT (SK</fcaCurrCodeNo>
                  <narative>YNINDO TV ) NO :123123456781111333</narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount>00000000800000000+</depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026036000+</balance>
                  <balanceEur>81011092038702000+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>92</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>COR WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1514</penDays>
                  <penType>2</penType>
                  <fillerM2>8</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-KOR TRF</fcaCurrCodeNo>
                  <narative></narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>986</branchNo1>
                  <tellerNo1>00001</tellerNo1>
                  <wdlAmount>00000000000001000-</wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026035000+</balance>
                  <balanceEur>81011092023932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>4</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1218</penDays>
                  <penType>1</penType>
                  <fillerM2>8</fillerM2>
                  <penMne>8</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>986-TRF KE/116913895</fcaCurrCodeNo>
                  <narative>/Bpk MUHAMA/9870011447972101 NYOPEDIA</narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount>00000000800000000-</wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005484226035000+</balance>
                  <balanceEur>80999276423932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>42</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1354</penDays>
                  <penType>3</penType>
                  <fillerM2>3</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-BILL PAYMENT (SK</fcaCurrCodeNo>
                  <narative>YNINDO TV ) NO :123123456781111333</narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount>00000000800000000+</depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026035000+</balance>
                  <balanceEur>81011092023932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>92</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>COR WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1354</penDays>
                  <penType>3</penType>
                  <fillerM2>3</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-KOR TRF</fcaCurrCodeNo>
                  <narative></narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount>00000000800000000-</wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005484226035000+</balance>
                  <balanceEur>80999276423932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>42</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1357</penDays>
                  <penType>1</penType>
                  <fillerM2>0</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-BILL PAYMENT (SK</fcaCurrCodeNo>
                  <narative>YNINDO TV ) NO :123123456781111333</narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount>00000000800000000+</depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026035000+</balance>
                  <balanceEur>81011092023932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>92</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>COR WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1357</penDays>
                  <penType>2</penType>
                  <fillerM2>6</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-KOR TRF</fcaCurrCodeNo>
                  <narative></narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount>00000000800000000-</wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005484226035000+</balance>
                  <balanceEur>80999276423932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>42</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1357</penDays>
                  <penType>4</penType>
                  <fillerM2>4</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-BILL PAYMENT (SK</fcaCurrCodeNo>
                  <narative>YNINDO TV ) NO :123123456781111333</narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
               <passbookItem>
                  <date>31/05/10</date>
                  <formatIndicator>0</formatIndicator>
                  <branchNo1>997</branchNo1>
                  <tellerNo1>00004</tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount>00000000800000000+</depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance>00005485026035000+</balance>
                  <balanceEur>81011092023932500+</balanceEur>
                  <currCodeEur>EUR</currCodeEur>
                  <mnemonic>92</mnemonic>
                  <fcaCurrCode>IDR</fcaCurrCode>
                  <fcaCurrCodeNo></fcaCurrCodeNo>
                  <narative>COR WDL TFR</narative>
                  <txnAmount></txnAmount>
                  <recType></recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays>1357</penDays>
                  <penType>4</penType>
                  <fillerM2>4</fillerM2>
                  <penMne>0</penMne>
               </passbookItem>
               <passbookItem>
                  <date/>
                  <formatIndicator>2</formatIndicator>
                  <branchNo1></branchNo1>
                  <tellerNo1></tellerNo1>
                  <wdlAmount></wdlAmount>
                  <depAmount></depAmount>
                  <cheqCredAmount></cheqCredAmount>
                  <cheqDebAmount></cheqDebAmount>
                  <balance></balance>
                  <balanceEur></balanceEur>
                  <currCodeEur></currCodeEur>
                  <mnemonic>11</mnemonic>
                  <fcaCurrCode></fcaCurrCode>
                  <fcaCurrCodeNo>SMS-KOR TRF</fcaCurrCodeNo>
                  <narative></narative>
                  <txnAmount></txnAmount>
                  <recType>N</recType>
                  <fillerM1></fillerM1>
                  <penRate></penRate>
                  <typeRate></typeRate>
                  <rateMne></rateMne>
                  <penDays></penDays>
                  <penType></penType>
                  <fillerM2></fillerM2>
                  <penMne></penMne>
               </passbookItem>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0118                    **            003076899900001000600000000     0  I  0 000000  0000000011447972100005500011032000+N]

[ 0335    0251            0000    000000003076899900001000600325264000040320000 000000  0631052010099700004                  00000000800000000+                                    00005485026036000+81011092038702000+EUR92    IDR                    COR WDL TFR                                                                          15141201         2                                                                                                                       11       SMS-KOR TRF                                                                   N                                   3105201009970000400000000800000000-                                                      00005484226036000+80999276438702000+EUR42    IDR                    WDL TFR                                                                              15142701         2                                                                                                                       11       SMS-BILL PAYMENT (SKYNINDO TV ) NO :123123456781111333                        N                                   31052010099700004                  00000000800000000+                                    00005485026036000+81011092038702000+EUR92    IDR                    COR WDL TFR                                                                          15142801         2                                                                                                                       11       SMS-KOR TRF                                                                   N                                   3105201009860000100000000000001000-                                                      00005485026035000+81011092023932500+EUR4     IDR                    WDL TFR                                                                              12181880         2                                                                                                                       11       986-TRF KE/116913895/Bpk MUHAMA/9870011447972101 NYOPEDIA                     N                                   3105201009970000400000000800000000-                                                      00005484226035000+80999276423932500+EUR42    IDR                    WDL TFR                                                                              13543301         2                                                                                                                       11       SMS-BILL PAYMENT (SKYNINDO TV ) NO :123123456781111333                        N                                   31052010099700004                  00000000800000000+                                    00005485026035000+81011092023932500+EUR92    IDR                    COR WDL TFR                                                                          13543301         2                                                                                                                       11       SMS-KOR TRF                                                                   N                                   3105201009970000400000000800000000-                                                      00005484226035000+80999276423932500+EUR42    IDR                    WDL TFR                                                                              13571001         2                                                                                                                       11       SMS-BILL PAYMENT (SKYNINDO TV ) NO :123123456781111333                        N                                   31052010099700004                  00000000800000000+                                    00005485026035000+81011092023932500+EUR92    IDR                    COR WDL TFR                                                                          13572601         2                                                                                                                       11       SMS-KOR TRF                                                                   N                                   3105201009970000400000000800000000-                                                      00005484226035000+80999276423932500+EUR42    IDR                    WDL TFR                                                                              13574401         2                                                                                                                       11       SMS-BILL PAYMENT (SKYNINDO TV ) NO :123123456781111333                        N                                   31052010099700004                  00000000800000000+                                    00005485026035000+81011092023932500+EUR92    IDR                    COR WDL TFR                                                                          13574401         2                                                                                                                       11       SMS-KOR TRF                                                                   N                                   MSG 0900 69         0000                                                                               ]
```
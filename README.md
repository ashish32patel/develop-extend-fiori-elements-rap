# develop-extend-fiori-elements-rap
RAP based OData Service for developing and extending Fiori Elements app

[OpenSAP github](https://github.com/SAP-samples/fiori-elements-opensap)
<br/>
[SAP Fiori Elements Feature Map](https://sapui5.hana.ondemand.com/sdk/#/topic/62d3f7c2a9424864921184fd6c7002eb.html)
<br/>
[Extending SAP Fiori Elements based Apps](https://sapui5.netweaver.ondemand.com/#/topic/358cf2598d71462b8ac2bd8c944efbfd)
<br/>
[Adding Filterable Field to the Smart Filter Bar](https://sapui5.netweaver.ondemand.com/#/topic/3a515829ffd74239878ebc0d453d001d)
<br/><br/>
[Go to BAS Project Repository](https://github.com/ashish32patel/develop-extend-fiori-elements-bas-project)
<br/>

## Helper artifacts
Travel exercise generator: /dmo/cl_fe_travel_generator

Package generated: ZFE_TRAVEL_001632




## Useful Annotations
#### Airline pictures in Bookings table:  
  //make sure the field AirlinePicURL is given:  **@Semantics.imageUrl: true**
  
  @UI.lineItem: [ { position: 05, label: ' ', value: '_Carrier.AirlinePicURL' } ]<br/>_Carrier;


# SampleAppServer
Sample Application server to avoid CORS issues with BlockChain API 

### Due to the CORS issues with calling the BlockChain API directly you can use this server and expand by adding simpler routes to it 
### Get History of a particular product is added as an example 
#### /GetHistory/:gtin/:serialNumber/:lotNumber/:expiryDate
### Please feel free to expand and add more routes or let us know we will add them 

### Install 

git clone <this repo>
cd cd SampleAppServer/
npm install 


### Run the server 
npm start 

### Verify 
http://localhost:3000/GetHistory/08806555018611/180914579188/r036191/2021-07-07T00:00:00.000Z

### Added Single product retreive example 
http://localhost:3000/GetSingle/08806555018611/180914579188/r036191/2021-07-07T00:00:00.000Z

#### Sample code added for  AJAX request
 http://localhost:3000/

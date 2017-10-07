<img src="https://farm5.staticflickr.com/4451/37534898671_329fe37e6e.jpg" width="446" height="156" alt="Bluemix Logo">

# BlueMix Hackathon cheat-sheet  http://bit.ly/2fRWd6n

alf@us.ibm.com Developer Advocate with IBM.

Sign up to the IBM Cloud, bluemix.net http://bit.ly/2xYo0Ko  (We have promocodes)

## Navigate the Catalog

https://console.bluemix.net/catalog/

<img src="https://farm5.staticflickr.com/4496/37532679161_1a61013568_c.jpg" width="800" height="53" alt="BlueMix1">

## Find a Buildpack

<img src="https://farm5.staticflickr.com/4461/37274490530_557edf373c_z.jpg" width="587" height="328" alt="BluemixCatalog">

## Select a Buildpack
<img src="https://farm5.staticflickr.com/4445/23680630568_f9a8ebbe7b_z.jpg" width="640" height="271" alt="BluemixCatalogFlask">

## Fill in the Parameters and create the Buildpack
<img src="https://farm5.staticflickr.com/4456/37485097406_282f686f8c_z.jpg" width="640" height="342" alt="BluemixCatalogFlask2">

## The Flask Console
<img src="https://farm5.staticflickr.com/4464/36864516803_a3b79d2d81_z.jpg" width="640" height="350" alt="Flask Console">

## The navigation Menu
<img src="https://farm5.staticflickr.com/4465/23681963188_76b1891222.jpg" width="165" height="350" alt="Getting Started">

## Connecting to a services
<img src="https://farm5.staticflickr.com/4474/37487059056_4afe372406_z.jpg" width="640" height="227" alt="Connecting Services">

## Connecting to Cloudant
<img src="https://farm5.staticflickr.com/4447/37504015812_b868bb493b_z.jpg" width="640" height="571" alt="Cloudant">

## (Getting Started) Download to your laptop
<img src="https://farm5.staticflickr.com/4503/37533000711_e4901daaf0_z.jpg" width="640" height="306" alt="BluemixCatalogFlask3">

## Work on your laptop
<img src="https://farm5.staticflickr.com/4455/36865358803_debcabb822.jpg" width="418" height="242" alt="Files">

## The manifest.yml file 

```
applications:
- path: .
  memory: 128M
  instances: 1
  domain: mybluemix.net
  name: LennartFlask
  host: LennartFlask
  disk_quota: 1024M
  services:
  - availability-monitoring-auto
  buildpack: python_buildpack
```

## Push the app to Bluemix
<img src="https://farm5.staticflickr.com/4466/37275143510_bed56c8df8_z.jpg" width="640" height="282" alt="Bluemix 6">

## Running your app on Bluemix
<img src="https://farm5.staticflickr.com/4467/37502815812_e7079fb1df_z.jpg" width="640" height="296" alt="Hi There">

## Tip for hackathons
Run the app on your laptop and connect to services in the cloud.

# Watson Services https://www.ibm.com/watson/products-services/

# Watson Developer Journeys
* [All Developer Journeys](https://developer.ibm.com/code/journey/)
* [Watson Developer Journeys](https://developer.ibm.com/code/journey/category/artificial-intelligence/)
* [Create an investment management chatbot](https://github.com/IBM/personal-wealth-portfolio-mgt-bot?cm_sp=IBMCode-_-create-an-investment-management-chatbot-_-Get-the-Code)

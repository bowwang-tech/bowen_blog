---
layout: grid

title: Travel
slug: travel

description: >
  Travel posts during my free times. 🌍

# (Optional) You can disable grouping posts by date.
no_groups: true

# Exclude this example category from the sitemap.
# DON'T USE THIS SETTING IN YOUR CATEGORIES!
sitemap: false
permalink: /travel/
---

__Places I have been visited.__ (Interact to see more.😋)

{% leaflet_map {"zoom" : 3,
                "center" : [51.08656593806813, 15.218897702268658],
                "providerBasemap": "OpenStreetMap.HOT"} %}
                <!-- Spain -->
    {% leaflet_marker { "latitude" : 36.71297258493744,
                       "longitude" : -4.406209331746406,
                       "popupContent" : "Malaga, Spain"} %}
    {% leaflet_marker { "latitude" : 37.89114260862969, 
                       "longitude" : -4.7880963425690855,
                       "popupContent" : "Córdoba, Spain"} %}
    {% leaflet_marker { "latitude" : 41.42539369359404,  
                       "longitude" : 2.15709074059243,
                       "popupContent" : "Barcelona, Spain"} %}
                <!-- Iceland -->
    {% leaflet_marker { "latitude" : 64.14617094551173, 
                       "longitude" : -21.944336496326695, 
                       "popupContent" : "Reykjavík, Iceland"} %}
    {% leaflet_marker { "latitude" : 64.0043473256979,  
                       "longitude" : -16.66562813612896, 
                       "popupContent" : "Hvannadalshnúkur, Iceland"} %}
                <!-- Italy -->
    {% leaflet_marker { "latitude" : 45.463629574266875, 
                       "longitude" : 9.215181007440176,  
                       "popupContent" : "Milan, Italy"} %}
    {% leaflet_marker { "latitude" : 45.70237358962578, 
                       "longitude" : 9.672432863048014,  
                       "popupContent" : "Bergamo, Italy"} %}
                <!-- UK -->
    {% leaflet_marker { "latitude" : 51.571297336802125,  
                       "longitude" : -0.27434466539506563,  
                       "popupContent" : "London, UK"} %}
                <!-- Liech -->
    {% leaflet_marker { "latitude" : 47.181671307900885,   
                       "longitude" : 9.605995890015883,  
                       "popupContent" : "Vaduz, Liechtenstein"} %}
                <!-- Norway -->
    {% leaflet_marker { "latitude" : 59.98162612500349,  
                       "longitude" : 10.91368682130646,  
                       "popupContent" : "Oslo, Norway"} %}
    {% leaflet_marker { "latitude" : 60.47015436142154,  
                       "longitude" : 5.53416747352708,  
                       "popupContent" : "Bergen, Norway"} %}
                <!-- Sweden -->
    {% leaflet_marker { "latitude" : 59.3243149357553, 
                       "longitude" : 18.06170000420837,  
                       "popupContent" : "Stockholm, Sweden"} %}
    {% leaflet_marker { "latitude" : 55.596048225583175,   
                       "longitude" : 12.985424219082834,  
                       "popupContent" : "Malmö, Sweden"} %}
                <!-- Frence -->
    {% leaflet_marker { "latitude" : 48.85518324236633,    
                       "longitude" : 2.3449200659915244,  
                       "popupContent" : "Paris, Frence"} %}
    {% leaflet_marker { "latitude" : 48.579790604899735,     
                       "longitude" : 7.753458085932671,  
                       "popupContent" : "Strasburg, Frence"} %}
                <!-- The Neitherland -->
    {% leaflet_marker { "latitude" : 52.36904830957784,     
                       "longitude" : 4.899766278125317,  
                       "popupContent" : "Amsterdam, NL"} %}
    {% leaflet_marker { "latitude" : 51.921903071533926,      
                       "longitude" : 4.478961001426133,  
                       "popupContent" : "Rotterdam, NL"} %}
    {% leaflet_marker { "latitude" : 52.081347404722095,      
                       "longitude" : 4.311282109427798,  
                       "popupContent" : "The Hague, NL"} %}
                <!-- Germany -->
    {% leaflet_marker { "latitude" : 51.23299313287232,      
                       "longitude" : 6.783626404918842,  
                       "popupContent" : "Düsseldorf, Germany"} %}
    {% leaflet_marker { "latitude" : 50.111562539176134,       
                       "longitude" : 8.682936129146178,  
                       "popupContent" : "Frankfurt, Germany"} %}
    {% leaflet_marker { "latitude" : 48.139375267432335,       
                       "longitude" : 11.561080008402403,  
                       "popupContent" : "Münich, Germany"} %}
                <!-- Denmark -->
    {% leaflet_marker { "latitude" : 55.68927059762494,       
                       "longitude" : 12.563754958650316,  
                       "popupContent" : "Copenhagen, Denmark"} %}
    {% leaflet_marker { "latitude" : 56.164411818081796,        
                       "longitude" : 10.225947759476703,  
                       "popupContent" : "Aarhus, Denmark"} %}
    {% leaflet_marker { "latitude" : 57.595620598715996,        
                       "longitude" : 9.975632429705128,  
                       "popupContent" : "Hirtshals, Denmark"} %}
               <!-- CH -->
    {% leaflet_marker { "latitude" : 47.37395959610547,        
                       "longitude" : 8.545073950926032,  
                       "popupContent" : "Zurich, CH"} %}
    {% leaflet_marker { "latitude" : 46.947041153066216,         
                       "longitude" : 7.447864083163301,  
                       "popupContent" : "Bern, CH"} %}
    {% leaflet_marker { "latitude" : 46.20908114514355,         
                       "longitude" : 6.1413998147199615,  
                       "popupContent" : "Genève, CH"} %}
    {% leaflet_marker { "latitude" : 47.55543018947141,          
                       "longitude" : 7.584274386752053,  
                       "popupContent" : "Basel, CH"} %}
    {% leaflet_marker { "latitude" : 46.68666922541388,          
                       "longitude" : 7.8542593636741564,  
                       "popupContent" : "Interlaken, CH"} %}
    {% leaflet_marker { "latitude" : 46.0118313097857,           
                       "longitude" : 8.947505024084984,  
                       "popupContent" : "Lugano, CH"} %}
                <!-- US -->
    {% leaflet_marker { "latitude" : 41.88419752107815,         
                       "longitude" : -87.632042968453,  
                       "popupContent" : "Chicago, IL"} %}
    {% leaflet_marker { "latitude" : 40.425426288325944,         
                       "longitude" : -86.92406163366971,  
                       "popupContent" : "West Lafayette, IN"} %}
                <!-- Japan -->
    {% leaflet_marker { "latitude" : 35.68494728652097,          
                       "longitude" : 139.75175993226213,  
                       "popupContent" : "Tokyo, Japan"} %}
                <!-- China -->
    {% leaflet_marker { "latitude" : 47.71530130038627,           
                       "longitude" : 128.87088481815422,   
                       "popupContent" : "Yichun, CN"} %}
    {% leaflet_marker { "latitude" : 45.733657712810434,          
                       "longitude" : 126.64954840057852,   
                       "popupContent" : "Harbin, CN"} %}
    {% leaflet_marker { "latitude" : 43.8341832625904,         
                       "longitude" : 125.34215190402097,  
                       "popupContent" : "Changchun, CN"} %}
    {% leaflet_marker { "latitude" : 41.79003084686643,          
                       "longitude" : 123.43255048628635,  
                       "popupContent" : "Shenyang, CN"} %}
    {% leaflet_marker { "latitude" : 38.96883039273784,          
                       "longitude" : 121.55756066005871,  
                       "popupContent" : "Dalian, CN"} %}
    {% leaflet_marker { "latitude" : 39.916763326576614,         
                       "longitude" : 116.3989876065851,  
                       "popupContent" : "Beijing, CN"} %}
    {% leaflet_marker { "latitude" : 39.14175899904361,           
                       "longitude" : 117.197791710124,  
                       "popupContent" : "Tianjin, CN"} %}
    {% leaflet_marker { "latitude" : 39.70186939333221,           
                       "longitude" : 119.16788735469486,  
                       "popupContent" : "Qinhuangdao, CN"} %}
    <!-- pause -->
    {% leaflet_marker { "latitude" : 36.847445489403064,          
                       "longitude" : 119.39455334209491,   
                       "popupContent" : "Weifang, CN"} %}
    {% leaflet_marker { "latitude" : 36.091124102879405,         
                       "longitude" : 120.3752462052757,     
                       "popupContent" : "Qingdao, CN"} %}
    {% leaflet_marker { "latitude" : 37.51433475213019,          
                       "longitude" : 122.11286100185676,  
                       "popupContent" : "Weihai, CN"} %}
    {% leaflet_marker { "latitude" : 34.67026297579672,           
                       "longitude" : 112.42249490724552,  
                       "popupContent" : "Luoyang, CN"} %}
    {% leaflet_marker { "latitude" : 34.21297475988435,           
                       "longitude" : 117.28836930472973, 
                       "popupContent" : "Xuzhou, CN"} %}
    {% leaflet_marker { "latitude" : 32.04667621917724,          
                       "longitude" : 118.77610306658636, 
                       "popupContent" : "Nanjing, CN"} %}
    {% leaflet_marker { "latitude" : 31.544180484074964,          
                       "longitude" : 120.3175582864454,   
                       "popupContent" : "Wuxi, CN"} %}
    {% leaflet_marker { "latitude" : 31.237753870382974,        
                       "longitude" : 121.4791840824499,  
                       "popupContent" : "Shanghai, CN"} %}
    {% leaflet_marker { "latitude" : 31.30573823823205,           
                       "longitude" : 120.58196347148278,   
                       "popupContent" : "Suzhou, CN"} %}
    {% leaflet_marker { "latitude" : 30.2843783946442,           
                       "longitude" : 120.14722779445982,   
                       "popupContent" : "Hangzhou, CN"} %}
    {% leaflet_marker { "latitude" : 29.08959966400396,          
                       "longitude" : 119.64394855991755,  
                       "popupContent" : "Jinhua, CN"} %}
    {% leaflet_marker { "latitude" : 28.669457333265733,          
                       "longitude" : 121.42784416191706,  
                       "popupContent" : "Taizhou, CN"} %}
    {% leaflet_marker { "latitude" : 24.483761569533367,          
                       "longitude" : 118.09877302726422,  
                       "popupContent" : "Xiamen, CN"} %}
    {% leaflet_marker { "latitude" : 23.1277247759502,          
                       "longitude" : 113.25113673430778,  
                       "popupContent" : "Guangzhou, CN"} %}
    {% leaflet_marker { "latitude" : 22.54125665206624,           
                       "longitude" : 114.02578116550049,   
                       "popupContent" : "Shenzhen, CN"} %}
    {% leaflet_marker { "latitude" : 22.302660426041058,          
                       "longitude" : 114.18639577442285,   
                       "popupContent" : "Hongkong, CN"} %}
    <!-- pause -->
    {% leaflet_marker { "latitude" : 18.263533161828768,       
                       "longitude" : 109.49961599801351,       
                       "popupContent" : "Sanya, CN"} %}
    {% leaflet_marker { "latitude" : 28.205012205602046,       
                       "longitude" : 112.93905311392739,        
                       "popupContent" : "Changsha, CN"} %}
    {% leaflet_marker { "latitude" : 30.589259020359954,         
                       "longitude" : 114.29610103038235,    
                       "popupContent" : "Wuhan, CN"} %}
    {% leaflet_marker { "latitude" : 29.55652168748425,         
                       "longitude" : 106.5303297690822,     
                       "popupContent" : "Chongqing, CN"} %}
    {% leaflet_marker { "latitude" : 30.660548631419726,          
                       "longitude" : 104.06682677553121,   
                       "popupContent" : "Chengdu, CN"} %}
    {% leaflet_marker { "latitude" : 31.477938403719296,      
                       "longitude" : 104.68939171290924,  
                       "popupContent" : "Mianyang, CN"} %}
    {% leaflet_marker { "latitude" : 34.287380725006244,    
                       "longitude" : 108.94184312781442,    
                       "popupContent" : "Xi'An, CN"} %}
    {% leaflet_marker { "latitude" : 34.370036435591864,    
                       "longitude" : 107.18605797998094,       
                       "popupContent" : "Baoji, CN"} %}
    {% leaflet_marker { "latitude" : 36.06191893738231,           
                       "longitude" : 103.81843993026985,    
                       "popupContent" : "Lanzhou, CN"} %}
    {% leaflet_marker { "latitude" : 36.62072625371708,        
                       "longitude" : 101.77547886501796,       
                       "popupContent" : "Xining, CN"} %}
    {% leaflet_marker { "latitude" : 38.93524081871948,       
                       "longitude" : 100.44776679745355,  
                       "popupContent" : "Zhangye, CN"} %}
    {% leaflet_marker { "latitude" : 39.73296284307284,          
                       "longitude" : 98.47522426053825,
                       "popupContent" : "Jiuquan, CN"} %}
    {% leaflet_marker { "latitude" : 35.5916637583217,          
                       "longitude" : 103.22185003991613,   
                       "popupContent" : "Linxia, CN"} %}
    {% leaflet_marker { "latitude" : 35.19195440474807,          
                       "longitude" : 102.50576934764699,   
                       "popupContent" : "Xiahe, CN"} %}
    {% leaflet_marker { "latitude" : 34.594273491563236,          
                       "longitude" : 102.49721239535454,   
                       "popupContent" : "Luqu, CN"} %}
    {% leaflet_marker { "latitude" : 33.575821236559236,          
                       "longitude" : 102.96016494093888,    
                       "popupContent" : "ZOIGE, CN"} %}
    {% leaflet_marker { "latitude" : 32.78204353770239,          
                       "longitude" : 103.62269426179556,   
                       "popupContent" : "Chuanzhusi, CN"} %}
    {% leaflet_marker { "latitude" : 36.73686724304141,           
                       "longitude" : 99.78024374364516,   
                       "popupContent" : "Heimahe, CN"} %}
{% endleaflet_map %}

---
> __Country Flags with the time I first visit...__

## 2023
* [Spain 🇪🇸]{:.heading.flip-title} 
Feb 5 2023 - Feb 12 2023
{:.text.post-date}

## 2022
* [Iceland 🇮🇸]{:.heading.flip-title} 
Nov 21 2022 - Nov 27 2022
{:.text.post-date}
* [Italy 🇮🇹]{:.heading.flip-title} 
Nov 12 2022 - Nov 13 2022
{:.text.post-date}
* [UK 🇬🇧]{:.heading.flip-title} 
Sept 6 2022 - Sept 8 2022
{:.text.post-date}
* [Liechtenstein 🇱🇮]{:.heading.flip-title} 
Aug 30 2022
{:.text.post-date}
* [Norway 🇳🇴]{:.heading.flip-title} 
Aug 5 2022 - Aug 7 2022
{:.text.post-date}
* [Sweden 🇸🇪]{:.heading.flip-title} 
Aug 1 2022
{:.text.post-date}
* [France 🇫🇷]{:.heading.flip-title} 
July 13 2022 - July 16 2022
{:.text.post-date}
* [The Neitherland 🇳🇱]{:.heading.flip-title} 
Apr 16 2022 - Apr 21 2022
{:.text.post-date}
* [Germany 🇩🇪]{:.heading.flip-title} 
Apr 8 2022 - Apr 10 2022
{:.text.post-date}
## ～2021
* [Denmark 🇩🇰]{:.heading.flip-title} 
Oct 21 2021 - Oct 30 2021
{:.text.post-date}
* [Switzerland 🇨🇭]{:.heading.flip-title} 
Aug 29 2021 - Now
{:.text.post-date}
* [US 🇺🇸]{:.heading.flip-title} 
Aug 15 2019
{:.text.post-date}
* [Japan 🇯🇵]{:.heading.flip-title} 
Aug 30 2016
{:.text.post-date}
* [China 🇨🇳]{:.heading.flip-title} 
Home Country :)
{:.text.post-date}

<!-- 2023 -->
[Spain 🇪🇸]: /travel/spain.md
<!-- 2022 -->
[Iceland 🇮🇸]: /travel/
[Italy 🇮🇹]:   /travel/
[UK 🇬🇧]:      /travel/
[Liechtenstein 🇱🇮]: /travel/
[Norway 🇳🇴]:  /travel/
[Sweden 🇸🇪]:  /travel/
[France 🇫🇷]:  /travel/
[The Neitherland 🇳🇱]: /travel/
[Germany 🇩🇪]: /travel/
<!-- 2021 -->
[Denmark 🇩🇰]: /travel/
[Switzerland 🇨🇭]: /travel/switzerland.md
[US 🇺🇸]:    /travel/us.md
[Japan 🇯🇵]: /travel/japan.md
[China 🇨🇳]: /travel/china.md


## Highlights
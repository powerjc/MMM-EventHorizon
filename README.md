## MMM-EventHorizon

Simple countdown timer for events.

## Examples

* Small, medium and large options

![](images/1.png) ![](images/2.png)

![](images/3.png) ![](images/4.png)

## Installation

* `git clone https://github.com/mykle1/MMM-EventHorizon` into the `~/MagicMirror/modules` directory.

## Config.js entry and options

```
{
disabled: false,
module: 'MMM-EventHorizon',
position: 'bottom_center',
config: {
    timezone: "n179",                     // See Timezone chart at bottom
    units: "1",          // 1=no units, 2=units initial only, 3=units abbr singular, 4= units abbr plural, 5= units full name
    size: "large",                        // small, medium or large
    countUp: "yes",                       // Count up after timer ends
    date: "2019-07-04",                   // YYYY-MM-DD format ONLY
    time: "00:00:01",                     // (HH:MM:SS)    Exact time you want timer to end
    text1: "Describe event",         // 2 lines of text during timer
    text2: "And here too!",               // 2 lines of text during timer
    text1Color: "FFFFFF",                 // Hex color codes
    text2Color: "62FF00",                 // Hex color codes
    timerColor: "FFFFFF",                 // Hex color codes
    endText1: "When timer ends",          // 2 lines of text when timer ends
    endText2: "Say something here",       // 2 lines of text when timer ends
    endText1Color: "FFFFFF",              // Hex color codes
    endText2Color: "62FF00",              // Hex color codes
    timerUpColor: "FFFFFF",               // Hex color codes
    colorpc: "000",                       // color of the background 000 = black, t = transparent
  }
},
```

Go to this page and obtain your timezone code 
https://forum.magicmirror.builders/topic/9514/contribute-to-a-module-volunteers-wanted-easy

Or choose from the list below!

Or choose from the text file "Timezone codes" included with this module.

## Timezone codes - Added as needed. Please ask at the MagicMirror forum

* France, Paris = n195

* Germany, Berlin = n37

* Norway, Oslo = n187

* Sweden, Stockholm = n239

* Switzerland, Geneva = n87

* UK, London = n136

* USA, CA = n137
* USA, NY = n179
* USA, IL = n64
* USA TX = n70

@vinp - Contributor
* Central Time zone USA (Chicago) = n64

@sdetweil - Contributor
* n64 - Austin, Texas
* n70 - Dallas, Texas
* n104 - Houston, Texas
* n394 - Albuquerque, Nm
* N197 - Phoenix, Az

@rts58 - Contributor
* n43 Boston, MA

@dazza120 - Contributor
* n2483 UK 🇬🇧 England

@CyruS1337 - Contributor
* n268 Zuerich, Switzerland

@Sandy2503 - Contributor
* n959 Wuppertal - Germany - CET - Central European Time

@Sean - Contributor
* n83 - Frankfurt A.M, Germany

@Nilnik - Contributor
* n291, Gothenburg, Sweden

@THeStigh - Contributor
* n290 Tromso - Norway
* n187 Oslo - Norway
* n5267 Finnsnes - Norway
* n287 Bergen - Norway
* n288 Trondheim - Norway
* n289 Stavanger - Norway
* n2513 Alta - Norway

@zdenek - Contributor
* Czech Republic - Liberec - n3673
* Czech Republic - Brno - n1960
* Czech Republic - Praha - n204
* Czech Republic - Plzeň - n2172
* Czech Republic - Hradec Králové - n4344
* Czech Republic - Teplice - n5513
* Czech Republic - Karlovy Vary- n4726
* Czech Republic - Ostrava - n2202
* Czech Republic - Olomouc - n4343
* Czech Republic - Tábor - n2201
* Czech Republic - Ústí nad Labem - n4345

@MWel197 - Contributor
* Netherlands - Arnhem - n1296
* Netherlands - Amsterdam - n16

@qu1que - Contributor
* n681 - A Coruña - Spain
* n3334 - Lugo - Spain
* n4529 - Vigo - Spain
* n141- Madrid - Spain
* n327 - Bilbao - Spain
* n31 - Barcelona - Spain
* n326 - Zaragoza - Spain
* n321- Sevilla - Spain
* n325 - Valencia - Spain
* n683 - Santa Cruz de Tenerife - Spain
* n3751 - Valladolid - Spain

@yawns = Contributor
* n987 Solingen - Germany - CET - Central European Time

@robiv8 = Contributor
* n317 Stuttgart DE Germany CET
* n2390 Split HR Croatia CET
* n281 Zagreb HR Croatia CET

@MyMirror = Contributor
* n307 Hamburg DE Germany

@justjim = Contributor
* Maryville, Missouri – n5345
* Kansas City, Missouri – n405
* Saint Joseph, Missouri – n5688
* Independence, Missouri – n838
* Des Moines, Iowa – n76
* Kansas City, Kansas – n5080
* Overland Park, Kansas – n868

@swvalenti = Contributor
* n2268 Freehold, NJ, USA

@aidandon = Contributor
* n4391 - Northern Ireland

@MoreLinux = Contributor
* n48 - Walldorf (Baden-Württemberg)

@lavolp3 = Contributor
* n1016 - Moers, Germany
* n957 - Duisburg, Germany
* n973 - Krefeld, Germany
* n2011 - Mülheim/Ruhr, Germany

@Anthony = Contributor
* n26 - Greece - Athens

@rmonteroc = Contributor
* n94 - Central America

@mumblebaj = Contributor
* n111 - South Africa/Johannesburg

@TipsyNurse = Contributor
* n113 Afghanistan - Kabul  
n284 Albania - Tirana  
n14 Algeria - Algiers  
n686 Andorra - Andorra La Vella  
n138 Angola - Luanda  
n688 Antigua and Barbuda - Saint John's  
n51 Argentina - Buenos Aires  
n485 Argentina - Córdoba - Córdoba  
n370 Armenia - Yerevan  
n57 Australia - Australian Capital Territory - Canberra  
n240 Australia - New South Wales - Sydney  
n929 Australia - Northern Territory - Alice Springs  
n72 Australia - Northern Territory - Darwin  
n47 Australia - Queensland - Brisbane  
n927 Australia - Queensland - Cairns  
n5 Australia - South Australia - Adelaide  
n396 Australia - Tasmania - Hobart  
n152 Australia - Victoria - Melbourne  
n1980 Australia - Western Australia - Eucla  
n196 Australia - Western Australia - Perth  
n259 Austria - Vienna - Vienna  
n369 Azerbaijan - Baku  
n173 Bahamas - Nassau  
n15 Bahrain - Manama  
n73 Bangladesh - Dhaka  
n46 Barbados - Bridgetown  
n285 Belarus - Minsk  
n48 Belgium - Brussels - Brussels  
n36 Belize - Belmopan  
n203 Benin - Porto Novo  
n38 Bermuda - Hamilton  
n690 Bhutan - Thimphu  
n124 Bolivia - La Paz  
n1888 Bolivia - Sucre  
n691 Bosnia-Herzegovina - Sarajevo  
n86 Botswana - Gaborone  
n752 Brazil - Acre - Rio Branco  
n144 Brazil - Amazonas - Manaus  
n222 Brazil - Bahia - Salvador  
n491 Brazil - Ceará - Fortaleza  
n45 Brazil - Distrito Federal - Brasilia  
n446 Brazil - Pará - Belém  
n209 Brazil - Pernambuco - Recife  
n213 Brazil - Rio de Janeiro - Rio de Janeiro  
n233 Brazil - São Paulo - São Paulo  
n932 British Indian Ocean Territory - Diego Garcia  
n693 Brunei - Bandar Seri Begawan  
n238 Bulgaria - Sofia  
n186 Burkina Faso - Ouagadougou  
n52 Burundi - Bujumbura  
n3446 Burundi - Gitega  
n685 Cabo Verde - Praia  
n199 Cambodia - Phnom Penh  
n267 Cameroon - Yaoundé  
n55 Canada - Alberta - Calgary  
n80 Canada - Alberta - Edmonton  
n256 Canada - British Columbia - Vancouver  
n265 Canada - Manitoba - Winnipeg  
n749 Canada - New Brunswick - Saint John  
n1137 Canada - Newfoundland and Labrador - Happy Valley-Goose Bay  
n4880 Canada - Newfoundland and Labrador - Mary's Harbour  
n175 Canada - Newfoundland and Labrador - St. John's  
n1145 Canada - Northwest Territories - Inuvik  
n678 Canada - Northwest Territories - Yellowknife  
n286 Canada - Nova Scotia - Halifax  
n3368 Canada - Nunavut - Alert  
n1157 Canada - Nunavut - Baker Lake  
n1160 Canada - Nunavut - Coral Harbour  
n3764 Canada - Nunavut - Eureka  
n3801 Canada - Nunavut - Grise Fiord  
n1164 Canada - Nunavut - Pond Inlet  
n2380 Canada - Nunavut - Resolute Bay  
n188 Canada - Ontario - Ottawa  
n250 Canada - Ontario - Toronto  
n1922 Canada - Quebec - Blanc-Sablon  
n2438 Canada - Quebec - Chibougamau  
n3768 Canada - Quebec - Kuujjuaq  
n165 Canada - Quebec - Montréal  
n189 Canada - Quebec - Québec  
n210 Canada - Saskatchewan - Regina  
n679 Canada - Yukon - Whitehorse  
n377 Cayman Islands - George Town  
n694 Central African Republic - Bangui  
n174 Chad - N'Djamena  
n914 Chile - Easter Island  
n574 Chile - Punta Arenas  
n232 Chile - Santiago  
n33 China - Beijing Municipality - Beijing  
n470 China - Chongqing Municipality - Chongqing  
n1232 China - Guangdong - Shenzhen  
n2148 China - Jiangsu - Suzhou  
n237 China - Shanghai Municipality - Shanghai  
n918 China - Tibet - Lhasa  
n655 China - Xinjiang - Ürümqi  
n41 Colombia - Bogota  
n696 Comoros - Moroni  
n926 Congo - Brazzaville  
n121 Congo Dem. Rep. - Kinshasa  
n139 Congo Dem. Rep. - Lubumbashi  
n279 Cook Islands - Rarotonga  
n225 Costa Rica - San Jose  
n1 Cote d'Ivoire (Ivory Coast) - Abidjan  
n935 Cote d'Ivoire (Ivory Coast) - Yamoussoukro  
n281 Croatia - Zagreb  
n99 Cuba - Havana  
n680 Cyprus - Nicosia  
n204 Czech Republic - Prague  
n69 Denmark - Copenhagen  
n697 Djibouti - Djibouti  
n698 Dominica - Roseau  
n230 Dominican Republic - Santo Domingo  
n915 Ecuador - Galapagos Islands  
n93 Ecuador - Guayaquil  
n190 Ecuador - Quito  
n53 Egypt - Cairo  
n228 El Salvador - San Salvador  
n699 Equatorial Guinea - Malabo  
n700 Eritrea - Asmara  
n242 Estonia - Tallinn  
n149 eSwatini - Mbabane  
n7 Ethiopia - Addis Ababa  
n630 Falkland Islands - Stanley  
n701 Faroe Islands - Tórshavn  
n82 Fiji - Suva  
n101 Finland - Helsinki  
n3718 Finland - Kemi  
n1401 Finland - Rovaniemi  
n195 France - Île-de-France - Paris  
n61 French Guiana - Cayenne  
n278 French Polynesia - Tahiti - Papeete  
n3658 French Southern Territories - Amsterdam Island  
n397 French Southern Territories - Port-aux-Francais  
n129 Gabon - Libreville  
n30 Gambia - Banjul  
n371 Georgia - Tbilisi  
n37 Germany - Berlin - Berlin  
n83 Germany - Hesse - Frankfurt  
n4 Ghana - Accra  
n89 Gibraltar - Gibraltar  
n26 Greece - Athens  
n2114 Greenland - Danmarkshavn  
n705 Greenland - Ittoqqortoormiit  
n4217 Greenland - Kangerlussuaq  
n703 Greenland - Nuuk  
n3724 Greenland - Qaanaaq  
n704 Greenland - Thule Air Base  
n706 Grenada - Saint George's  
n707 Guadeloupe - Basse-Terre  
n91 Guam - Hagåtña  
n94 Guatemala - Guatemala City  
n67 Guinea - Conakry  
n40 Guinea-Bissau - Bissau  
n88 Guyana - Georgetown  
n709 Haiti - Port-au-Prince  
n245 Honduras - Tegucigalpa  
n102 Hong Kong - Hong Kong  
n50 Hungary - Budapest  
n211 Iceland - Reykjavik  
n1040 India - Bihar - Patna  
n771 India - Delhi - Delhi  
n176 India - Delhi - New Delhi  
n1039 India - Gujarat - Surat  
n438 India - Karnataka - Bangalore  
n1892 India - Kerala - Thiruvananthapuram  
n1041 India - Madhya Pradesh - Indore  
n44 India - Maharashtra - Mumbai  
n1038 India - Maharashtra - Pune  
n1042 India - Odisha - Bhubaneshwar  
n4498 India - Punjab - Ahmedgarh  
n1043 India - Punjab - Ludhiana  
n553 India - Tamil Nadu - Chennai  
n1047 India - Tamil Nadu - Madurai  
n1046 India - Uttar Pradesh - Agra  
n1045 India - Uttar Pradesh - Varanasi  
n54 India - West Bengal - Kolkata  
n761 Indonesia - Bali - Denpasar  
n631 Indonesia - East Java - Surabaya  
n434 Indonesia - East Kalimantan - Balikpapan  
n108 Indonesia - Jakarta Special Capital Region - Jakarta  
n555 Indonesia - North Sulawesi - Manado  
n759 Indonesia - Papua - Jayapura  
n653 Indonesia - South Sulawesi - Makassar  
n437 Indonesia - West Java - Bandung  
n2120 Indonesia - West Kalimantan - Pontianak  
n2436 Indonesia - West Papua - Manokwari  
n246 Iran - Tehran  
n27 Iraq - Baghdad  
n78 Ireland - Dublin  
n716 Isle of Man - Douglas  
n110 Israel - Jerusalem  
n676 Israel - Tel Aviv  
n157 Italy - Milan  
n215 Italy - Rome  
n120 Jamaica - Kingston  
n540 Japan - Kobe  
n538 Japan - Kyoto  
n565 Japan - Nagoya  
n671 Japan - Osaka  
n622 Japan - Sapporo  
n248 Japan - Tokyo  
n667 Japan - Yokohama  
n11 Jordan - Amman  
n382 Kazakhstan - Almaty  
n916 Kazakhstan - Aqtobe  
n921 Kazakhstan - Nursultan  
n2352 Kazakhstan - Oral  
n170 Kenya - Nairobi  
n274 Kiribati - Christmas Island - Kiritimati  
n675 Kiribati - Tarawa  
n743 Kosovo - Pristina  
n123 Kuwait - Kuwait City  
n384 Kyrgyzstan - Bishkek  
n260 Laos - Vientiane  
n602 Latvia - Riga  
n34 Lebanon - Beirut  
n147 Lesotho - Maseru  
n161 Liberia - Monrovia  
n252 Libya - Tripoli  
n714 Liechtenstein - Vaduz  
n660 Lithuania - Vilnius  
n534 Luxembourg - Luxembourg  
n20 Madagascar - Antananarivo  
n130 Malawi - Lilongwe  
n122 Malaysia - Kuala Lumpur - Kuala Lumpur  
n715 Maldives - Male  
n29 Mali - Bamako  
n2328 Mali - Timbuktu  
n255 Malta - Valletta  
n717 Marshall Islands - Majuro  
n718 Martinique - Fort-de-France  
n183 Mauritania - Nouakchott  
n201 Mauritius - Port Louis  
n9 Mexico - Aguascalientes - Aguascalientes  
n154 Mexico - Baja California - Mexicali  
n247 Mexico - Baja California - Tijuana  
n155 Mexico - Ciudad de México - Mexico City  
n3 Mexico - Guerrero - Acapulco  
n92 Mexico - Jalisco - Guadalajara  
n923 Mexico - Quintana Roo - Cancún  
n148 Mexico - Sinaloa - Mazatlan  
n503 Mexico - Sonora - Hermosillo  
n258 Mexico - Veracruz - Veracruz  
n1072 Micronesia - Pohnpei - Palikir  
n177 Moldova - Chișinău  
n674 Monaco - Monaco  
n950 Mongolia - Hovd  
n720 Mongolia - Ulaanbaatar  
n744 Montenegro - Podgorica  
n60 Morocco - Casablanca  
n206 Morocco - Rabat  
n146 Mozambique - Maputo  
n1981 Myanmar - Naypyidaw  
n208 Myanmar - Yangon  
n266 Namibia - Windhoek  
n276 Nauru - Yaren  
n117 Nepal - Kathmandu  
n16 Netherlands - Amsterdam  
n22 New Zealand - Auckland - Auckland  
n63 New Zealand - Chatham Islands - Chatham Islands  
n264 New Zealand - Wellington - Wellington  
n143 Nicaragua - Managua  
n180 Niger - Niamey  
n742 Nigeria - Abuja  
n125 Nigeria - Lagos  
n724 Niue - Alofi  
n205 North Korea - Pyongyang  
n673 North Macedonia - Skopje  
n737 Norway - Svalbard - Longyearbyen  
n187 Norway - Oslo  
n290 Norway - Tromsø  
n169 Oman - Muscat  
n106 Pakistan - Islamabad  
n757 Pakistan - Sindh - Karachi  
n756 Pakistan - Lahore  
n5606 Palau - Ngerulmud  
n192 Panama - Panama  
n193 Papua New Guinea - Port Moresby  
n21 Paraguay - Asuncion  
n131 Peru - Lima - Lima  
n145 Philippines - Manila  
n755 Pitcairn Islands - Adamstown  
n262 Poland - Warsaw  
n133 Portugal - Lisbon  
n271 Portugal - Azores - Ponta Delgada  
n226 Puerto Rico - San Juan  
n8 Qatar - Doha  
n216 Réunion (French) - Saint-Denis  
n49 Romania - Bucharest  
n2437 Russia - Arkhangelsk - Belushya Guba  
n356 Russia - Bashkortostan - Ufa  
n373 Russia - Chelyabinsk - Chelyabinsk  
n17 Russia - Chukotka - Anadyr  
n3795 Russia - Chukotka - Pevek  
n378 Russia - Irkutsk - Irkutsk  
n528 Russia - Kaliningrad - Kaliningrad  
n114 Russia - Kamchatka - Petropavlovsk-Kamchatsky  
n2439 Russia - Khabarovsk - Komsomolsk-on-Amur  
n3735 Russia - Krasnoyarsk - Khatanga  
n372 Russia - Krasnoyarsk - Krasnoyarsk  
n381 Russia - Krasnoyarsk - Norilsk  
n380 Russia - Magadan - Magadan  
n166 Russia - Moscow - Moscow  
n167 Russia - Murmansk - Murmansk  
n353 Russia - Novgorod - Novgorod  
n375 Russia - Novosibirsk - Novosibirsk  
n374 Russia - Omsk - Omsk  
n357 Russia - Perm - Perm  
n261 Russia - Primorsky - Vladivostok  
n352 Russia - Saint Petersburg - Saint-Petersburg  
n4211 Russia - Sakha (Yakutia) - Srednekolymsk  
n3769 Russia - Sakha (Yakutia) - Tiksi  
n3767 Russia - Sakha (Yakutia) - Verkhoyansk  
n1907 Russia - Sakha (Yakutia) - Yakutsk  
n1245 Russia - Sakhalin - Yuzhno-Sakhalinsk  
n355 Russia - Samara - Samara  
n358 Russia - Sverdlovsk - Yekaterinburg  
n354 Russia - Tatarstan - Kazan  
n364 Russia - Udmurtia - Izhevsk  
n4096 Russia - Zabaykalsky - Chita  
n119 Rwanda - Kigali  
n727 Saint Helena - Jamestown  
n728 Saint Kitts and Nevis - Basseterre  
n729 Saint Lucia - Castries  
n731 Saint Vincent and Grenadines - Kingstown  
n282 Samoa - Apia  
n732 San Marino - San Marino  
n733 Sao Tome and Principe - São Tomé  
n151 Saudi Arabia - Makkah  
n1942 Saudi Arabia - Medina  
n214 Saudi Arabia - Riyadh  
n74 Senegal - Dakar  
n35 Serbia - Belgrade  
n734 Seychelles - Victoria  
n85 Sierra Leone - Freetown  
n236 Singapore - Singapore  
n735 Slovakia - Bratislava  
n736 Slovenia - Ljubljana  
n273 Solomon Islands - Honiara  
n160 Somalia - Mogadishu  
n56 South Africa - Cape Town  
n111 South Africa - Johannesburg  
n3401 South Africa - Marion Island (Prince Edward Islands)  
n269 South Africa - Pretoria  
n1985 South Georgia/Sandwich Is. - King Edward Point  
n235 South Korea - Seoul  
n2171 South Sudan - Juba  
n31 Spain - Barcelona - Barcelona  
n141 Spain - Madrid  
n191 Spain - Majorca - Palma  
n389 Sri Lanka - Colombo  
n1925 Sri Lanka - Sri Jayawardenepura Kotte  
n118 Sudan - Khartoum  
n194 Suriname - Paramaribo  
n239 Sweden - Stockholm  
n270 Switzerland - Bern - Bern  
n87 Switzerland - Geneva - Geneva  
n268 Switzerland - Zurich - Zürich  
n487 Syria - Damascus  
n241 Taiwan - Taipei  
n385 Tajikistan - Dushanbe  
n71 Tanzania - Dar es Salaam  
n1030 Tanzania - Dodoma  
n28 Thailand - Bangkok  
n768 Timor-Leste - Dili  
n135 Togo - Lomé  
n738 Tokelau - Fakaofo  
n277 Tonga - Nukualofa  
n588 Trinidad and Tobago - Port of Spain  
n253 Tunisia - Tunis  
n19 Turkey - Ankara  
n107 Turkey - Istanbul  
n387 Turkmenistan - Ashgabat  
n272 Tuvalu - Funafuti  
n115 Uganda - Kampala  
n4060 Ukraine - Dnipropetrovsk - Dnipro  
n367 Ukraine - Kyiv - Kyiv  
n366 Ukraine - Odessa - Odesa  
n2 United Arab Emirates - Abu Dhabi - Abu Dhabi  
n776 United Arab Emirates - Dubai - Dubai  
n136 United Kingdom - England - London  
n919 United Kingdom - Northern Ireland - Belfast  
n304 United Kingdom - Scotland - Edinburgh  
n90 United Kingdom - Scotland - Glasgow  
n298 United Kingdom - Wales - Cardiff  
n769 United Kingdom - England - Greenwich Borough  
n5264 United Kingdom - England - Croydon  
n4744 United Kingdom - England - Bromley  
n4733 United Kingdom - England - Enfield  
n2125 United Kingdom - England - Loughton  
n4793 United Kingdom - England - Epsom 
n163 Uruguay - Montevideo  
n3399 US Minor Outlying Islands - Baker Island  
n1890 US Minor Outlying Islands - Midway  
n2131 US Minor Outlying Islands - Wake Island  
n407 USA - Alabama - Montgomery  
n13 USA - Alaska - Adak  
n18 USA - Alaska - Anchorage  
n81 USA - Alaska - Fairbanks  
n112 USA - Alaska - Juneau  
n931 USA - Alaska - Unalaska  
n197 USA - Arizona - Phoenix  
n134 USA - Arkansas - Little Rock  
n137 USA - California - Los Angeles  
n217 USA - California - Sacramento  
n770 USA - California - San Diego  
n224 USA - California - San Francisco  
n283 USA - California - San Jose  
n75 USA - Colorado - Denver  
n98 USA - Connecticut - Hartford  
n1029 USA - Delaware - Dover  
n263 USA - District of Columbia - Washington DC  
n156 USA - Florida - Miami  
n867 USA - Florida - Orlando  
n944 USA - Florida - Pensacola  
n25 USA - Georgia - Atlanta  
n103 USA - Hawaii - Honolulu  
n42 USA - Idaho - Boise  
n64 USA - Illinois - Chicago  
n105 USA - Indiana - Indianapolis  
n76 USA - Iowa - Des Moines  
n249 USA - Kansas - Topeka  
n413 USA - Kentucky - Louisville  
n178 USA - Louisiana - New Orleans  
n23 USA - Maine - Augusta  
n419 USA - Maryland - Baltimore  
n43 USA - Massachusetts - Boston  
n77 USA - Michigan - Detroit  
n159 USA - Minnesota - Minneapolis  
n219 USA - Minnesota - St. Paul  
n515 USA - Mississippi - Jackson  
n405 USA - Missouri - Kansas City  
n605 USA - Missouri - St. Louis  
n448 USA - Montana - Billings  
n132 USA - Nebraska - Lincoln  
n127 USA - Nevada - Las Vegas  
n68 USA - New Hampshire - Concord  
n861 USA - New Jersey - Newark  
n394 USA - New Mexico - Albuquerque  
n179 USA - New York - New York  
n207 USA - North Carolina - Raleigh  
n39 USA - North Dakota - Bismarck  
n805 USA - Ohio - Columbus  
n184 USA - Oklahoma - Oklahoma City  
n202 USA - Oregon - Portland  
n221 USA - Oregon - Salem  
n198 USA - Pennsylvania - Philadelphia  
n878 USA - Rhode Island - Providence  
n66 USA - South Carolina - Columbia  
n1920 USA - South Dakota - Rapid City  
n627 USA - South Dakota - Sioux Falls  
n843 USA - Tennessee - Knoxville  
n171 USA - Tennessee - Nashville  
n24 USA - Texas - Austin  
n70 USA - Texas - Dallas  
n104 USA - Texas - Houston  
n1921 USA - Texas - Midland  
n220 USA - Utah - Salt Lake City  
n164 USA - Vermont - Montpelier  
n212 USA - Virginia - Richmond  
n234 USA - Washington - Seattle  
n62 USA - West Virginia - Charleston  
n142 USA - Wisconsin - Madison  
n158 USA - Wisconsin - Milwaukee  
n778 USA - Wyoming - Cheyenne  
n244 Uzbekistan - Tashkent  
n280 Vanuatu - Port Vila  
n710 Vatican City State - Vatican City  
n58 Venezuela - Caracas  
n95 Vietnam - Hanoi  
n218 Vietnam - Ho Chi Minh  
n741 Western Sahara - El Aaiún  
n6 Yemen - Aden  
n672 Yemen - Sana  
n140 Zambia - Lusaka  
n96 Zimbabwe - Harare 

## Special thanks to @spitzlbergerj

For going out of his way and making some nice additions to the module,

Even if he made it work ONLY for Berlin Germany! I kid you not! :-)

## Comment by @spitzlberger on this "special thanks"
That's not correct. I inserted a parameter for the time zone that did not exist before. This allowed the users of the module to set the time zones (and much more about other parameters) without adjusting the code.

However it is correct, that I then set the time zone parameter to Berlin by default. 

But the "inventor of the time zone parameter" is also entitled to that, right? :-)

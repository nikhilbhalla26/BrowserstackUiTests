


# Task Overview
Technical Assignment: Run Selenium Test on BrowserStack
Steps:

1.Visit the website El País, a Spanish news outlet.
  -Ensure that the website's text is displayed in Spanish.

2.Scrape Articles from the Opinion Section:
  -Navigate to the Opinion section of the website.
  -Fetch the first five articles in this section.
  -Print the title and content of each article in Spanish.
  -If available, download and save the cover image of each article to your local machine.

3.Translate Article Headers:
  -Use a translation API of your choice, such as:
  -Rapid Translate Multi Traduction API
  -Translate the title of each article to English.
  -Print the translated headers.

4.Analyze Translated Headers:
  -From the translated headers, identify any words that are repeated more than twice across all headers combined.
  -Print each repeated word along with the count of its occurrences.

5.Cross-Browser Testing:
  -Run the solution locally to verify functionality.
  -Once validated, execute the solution on BrowserStack across 5 parallel threads, testing across a combination of  desktop and mobile browsers.


The script efficiently executes test cases simultaneously on multiple browser and device configurations.
This output is for one of the device test- 
user@users-MacBook-Air To_Run_Selenium_Test_on_BrowserStack % node index.js                          
Navigated to El Pais homepage.
======================================
No cookies popup found or already accepted.
======================================
Found Opinion section link: https://elpais.com/opinion/
======================================
Navigated to the Opinion section.
======================================
Located the main section with class 'z z-hi'.
======================================
Found 13 articles.
======================================
Title 1: Transparencia contra la pederastia
--------------------------------------
API Response: [ 'Transparency against pedophilia' ]
Translated Title 1: Transparency against pedophilia
--------------------------------------
Content: Algo falla en la Conferencia Episcopal cuando una víctima española tiene que acudir al Vaticano para denunciar su caso
======================================
No image found for Article 1
======================================
Title 2: Odio racista en las redes y en los estadios
--------------------------------------
API Response: [ 'Racist hatred on the networks and in the stadiums' ]
Translated Title 2: Racist hatred on the networks and in the stadiums
--------------------------------------
Content: Las plataformas y los clubes deben extremar el celo para erradicar los mensajes supremacistas y xenófobos
======================================
No image found for Article 2
======================================
Title 3: PSOE y Junts: tejer y destejer
--------------------------------------
API Response: [ 'PSOE and Junts: weaving and unweaving' ]
Translated Title 3: PSOE and Junts: weaving and unweaving
--------------------------------------
Content: En una relación desigual, la parte mayor tiene más responsabilidad. Los socialistas harían bien en reconstruir su relación con los independentistas catalanes
======================================
No image found for Article 3
======================================
Title 4: El vaciamiento de la democracia
--------------------------------------
API Response: [ 'The hollowing out of democracy' ]
Translated Title 4: The hollowing out of democracy
--------------------------------------
Content: Ahora que se habla tanto de blindar derechos no hay nada más urgente que garantizar algunos de los que componen el Estado de bienestar
======================================
Title 5: EE UU va ganando, de momento
--------------------------------------
API Response: [ 'The US is winning, for now' ]
Translated Title 5: The US is winning, for now
--------------------------------------
Content not found for Article 5
======================================
No image found for Article 5
======================================
the: 4
and: 3
Test executed successfully!
======================================
Image 4 saved to /Users/user/Documents/Automations/BrowserstackUiTests/To_Run_Selenium_Test_on_BrowserStack/opinion_image_4.jpg
======================================
Navigated to El Pais homepage.
======================================
Navigated to El Pais homepage.
======================================
Navigated to El Pais homepage.
======================================
Cookies accepted.
======================================
Found Opinion section link: https://elpais.com/opinion/
======================================
Navigated to the Opinion section.
======================================
Located the main section with class 'z z-hi'.
======================================
Found 13 articles.
======================================
Cookies accepted.
======================================
Found Opinion section link: https://elpais.com/opinion/
======================================
Cookies accepted.
======================================
Found Opinion section link: https://elpais.com/opinion/
======================================
Navigated to the Opinion section.
======================================
Located the main section with class 'z z-hi'.
======================================
Found 13 articles.
======================================
Title 1: Transparencia contra la pederastia
--------------------------------------
API Response: [ 'Transparency against pedophilia' ]
Translated Title 1: Transparency against pedophilia
--------------------------------------
Navigated to El Pais homepage.
======================================
Navigated to the Opinion section.
======================================
Located the main section with class 'z z-hi'.
======================================
Found 13 articles.
======================================
Title 1: Transparencia contra la pederastia
--------------------------------------
API Response: [ 'Transparency against pedophilia' ]
Translated Title 1: Transparency against pedophilia
--------------------------------------
Content: Algo falla en la Conferencia Episcopal cuando una víctima española tiene que acudir al Vaticano para denunciar su caso
======================================
No image found for Article 1
======================================
Title 2: Odio racista en las redes y en los estadios
--------------------------------------
API Response: [ 'Racist hatred on the networks and in the stadiums' ]
Translated Title 2: Racist hatred on the networks and in the stadiums
--------------------------------------
Content: Las plataformas y los clubes deben extremar el celo para erradicar los mensajes supremacistas y xenófobos
======================================
No image found for Article 2
======================================
Title 3: PSOE y Junts: tejer y destejer
--------------------------------------
API Response: [ 'PSOE and Junts: weaving and unweaving' ]
Translated Title 3: PSOE and Junts: weaving and unweaving
--------------------------------------
Content: En una relación desigual, la parte mayor tiene más responsabilidad. Los socialistas harían bien en reconstruir su relación con los independentistas catalanes
======================================
No image found for Article 3
======================================
Title 4: El vaciamiento de la democracia
--------------------------------------
API Response: [ 'The hollowing out of democracy' ]
Translated Title 4: The hollowing out of democracy
--------------------------------------
Content: Ahora que se habla tanto de blindar derechos no hay nada más urgente que garantizar algunos de los que componen el Estado de bienestar
======================================
Image 4 saved to /Users/user/Documents/Automations/BrowserstackUiTests/To_Run_Selenium_Test_on_BrowserStack/opinion_image_4.jpg
======================================
Title 5: EE UU va ganando, de momento
--------------------------------------
API Response: [ 'The US is winning, for now' ]
Translated Title 5: The US is winning, for now
--------------------------------------
Content not found for Article 5
======================================
No image found for Article 5
======================================
transparency: 3
against: 3
pedophilia: 3
the: 8
and: 6
Test executed successfully!
======================================
Title 1: Transparencia contra la pederastia
--------------------------------------
API Response: [ 'Transparency against pedophilia' ]
Translated Title 1: Transparency against pedophilia
--------------------------------------
Content: Algo falla en la Conferencia Episcopal cuando una víctima española tiene que acudir al Vaticano para denunciar su caso
======================================
No image found for Article 1
======================================
Title 2: Odio racista en las redes y en los estadios
--------------------------------------
API Response: [ 'Racist hatred on the networks and in the stadiums' ]
Translated Title 2: Racist hatred on the networks and in the stadiums
--------------------------------------
Content: Las plataformas y los clubes deben extremar el celo para erradicar los mensajes supremacistas y xenófobos
======================================
No image found for Article 2
======================================
Title 3: PSOE y Junts: tejer y destejer
--------------------------------------
API Response: [ 'PSOE and Junts: weaving and unweaving' ]
Translated Title 3: PSOE and Junts: weaving and unweaving
--------------------------------------
Content: En una relación desigual, la parte mayor tiene más responsabilidad. Los socialistas harían bien en reconstruir su relación con los independentistas catalanes
======================================
No image found for Article 3
======================================
Title 4: El vaciamiento de la democracia
--------------------------------------
API Response: [ 'The hollowing out of democracy' ]
Translated Title 4: The hollowing out of democracy
--------------------------------------
Content: Ahora que se habla tanto de blindar derechos no hay nada más urgente que garantizar algunos de los que componen el Estado de bienestar
======================================
Image 4 saved to /Users/user/Documents/Automations/BrowserstackUiTests/To_Run_Selenium_Test_on_BrowserStack/opinion_image_4.jpg
======================================
Title 5: EE UU va ganando, de momento
--------------------------------------
API Response: [ 'The US is winning, for now' ]
Translated Title 5: The US is winning, for now
--------------------------------------
Content not found for Article 5
======================================
No image found for Article 5
======================================
transparency: 4
against: 4
pedophilia: 4
racist: 3
hatred: 3
on: 3
the: 12
networks: 3
and: 9
in: 3
stadiums: 3
psoe: 3
junts:: 3
weaving: 3
unweaving: 3
hollowing: 3
out: 3
of: 3
democracy: 3
us: 3
is: 3
winning,: 3
for: 3
now: 3
Test executed successfully!
======================================
Content: Algo falla en la Conferencia Episcopal cuando una víctima española tiene que acudir al Vaticano para denunciar su caso
======================================
No image found for Article 1
======================================
Title 2: Odio racista en las redes y en los estadios
--------------------------------------
API Response: [ 'Racist hatred on the networks and in the stadiums' ]
Translated Title 2: Racist hatred on the networks and in the stadiums
--------------------------------------
Content: Las plataformas y los clubes deben extremar el celo para erradicar los mensajes supremacistas y xenófobos
======================================
No image found for Article 2
======================================
Title 3: PSOE y Junts: tejer y destejer
--------------------------------------
API Response: [ 'PSOE and Junts: weaving and unweaving' ]
Translated Title 3: PSOE and Junts: weaving and unweaving
--------------------------------------
Content: En una relación desigual, la parte mayor tiene más responsabilidad. Los socialistas harían bien en reconstruir su relación con los independentistas catalanes
======================================
No image found for Article 3
======================================
Title 4: El vaciamiento de la democracia
--------------------------------------
API Response: [ 'The hollowing out of democracy' ]
Translated Title 4: The hollowing out of democracy
--------------------------------------
Content: Ahora que se habla tanto de blindar derechos no hay nada más urgente que garantizar algunos de los que componen el Estado de bienestar
======================================
Image 4 saved to /Users/user/Documents/Automations/BrowserstackUiTests/To_Run_Selenium_Test_on_BrowserStack/opinion_image_4.jpg
======================================
Title 5: EE UU va ganando, de momento
--------------------------------------
API Response: [ 'The US is winning, for now' ]
Translated Title 5: The US is winning, for now
--------------------------------------
No cookies popup found or already accepted.
======================================
Found Opinion section link: https://elpais.com/opinion/
======================================
Navigated to the Opinion section.
======================================
Located the main section with class 'z z-hi'.
======================================
Found 13 articles.
======================================
Title 1: Transparencia contra la pederastia
--------------------------------------
API Response: [ 'Transparency against pedophilia' ]
Translated Title 1: Transparency against pedophilia
--------------------------------------
Content: Algo falla en la Conferencia Episcopal cuando una víctima española tiene que acudir al Vaticano para denunciar su caso
======================================
No image found for Article 1
======================================
Title 2: Odio racista en las redes y en los estadios
--------------------------------------
API Response: [ 'Racist hatred on the networks and in the stadiums' ]
Translated Title 2: Racist hatred on the networks and in the stadiums
--------------------------------------
Content: Las plataformas y los clubes deben extremar el celo para erradicar los mensajes supremacistas y xenófobos
======================================
No image found for Article 2
======================================
Title 3: 
--------------------------------------
API Response: [ '' ]
Translated Title 3: 
--------------------------------------
Content: 
======================================
No image found for Article 3
======================================
Title 4: 
--------------------------------------
API Response: [ '' ]
Translated Title 4: 
--------------------------------------
Content: 
======================================
Image 4 saved to /Users/user/Documents/Automations/BrowserstackUiTests/To_Run_Selenium_Test_on_BrowserStack/opinion_image_4.jpg
======================================
Title 5: 
--------------------------------------
API Response: [ '' ]
Translated Title 5: 
--------------------------------------
Content not found for Article 5
======================================
No image found for Article 5
======================================
transparency: 5
against: 5
pedophilia: 5
racist: 5
hatred: 5
on: 5
the: 18
networks: 5
and: 13
in: 5
stadiums: 5
psoe: 4
junts:: 4
weaving: 4
unweaving: 4
hollowing: 4
out: 4
of: 4
democracy: 4
us: 4
is: 4
winning,: 4
for: 4
now: 4
: 3
Test executed successfully!
======================================
Content not found for Article 5
======================================
No image found for Article 5
======================================
transparency: 5
against: 5
pedophilia: 5
racist: 5
hatred: 5
on: 5
the: 18
networks: 5
and: 13
in: 5
stadiums: 5
psoe: 4
junts:: 4
weaving: 4
unweaving: 4
hollowing: 4
out: 4
of: 4
democracy: 4
us: 4
is: 4
winning,: 4
for: 4
now: 4
: 3
Test executed successfully!
======================================
All tests executed successfully!

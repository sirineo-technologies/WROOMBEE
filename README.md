## Sobre a WROOMBEE ESP32

Pioneira no mundo, construída com base no form factor do Xbee, a WROOMBEE utiliza o poderoso ESP32-WROOM-32,  possui dois Microprocessadores  Xtensa® 32-bit LX6  com até 600 DMIPS (velocidade de processamento). A frequência do clock pode ser de até 240 MHz, dependendo do modelo. A frequência mais comum é 160 MHz ( 10 vezes o clock do Arduino Uno). Possue conectividade híbrida com WiFi ou  Bluetooth Low Energy v4.2 (BLE), integrados ao ESP32 WROOM produzido pela [ESPRESSIF](https://www.espressif.com/). Com nosso módulo  você poderá trabalhar com diversos shields ou hardwares do mercado mundial com o soquete  Xbee. 

<p align="center">
<img width="226" height="313" src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/wroombee-top-png.png">
</p align="center">

Através também da IDE do Arduino ou ESP IDF, você terá também um grande aliado para suas soluções em IoT com aplicações que utilizam o Wi-FI e BLE.

A SiriNEO Technologies desenvolveu esse módulo com toda a pinagem e recursos com  referência ao Xbee, bastando conectá-la a TiBEE para programação do firmware ou até mesmo na BEESP MF para programação selecionando o modo de Programação através da chave nela integrada.

<p align="center">
  <img src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/wroombee-blinkled-gif.gif" alt="gif wroombee" />
</p>


Acoplada a BEESP MF e SAMBA BLACK da SiriNEO Technologies, você terá uma ampla gama de aplicações a possibilidades de realizar pequenas automações ou aplicações que envolva entrada de dados analógicas de acordo com sua necessidade.

<p align="center">
<img width="800" height="476" src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/BMF-%20wroombee%20enodemcu32.jpg">
</p align="center">

## História da WROOMBEE ESP32

A alguns anos eu teria sido procurado por colega par projetar um módulo que utilizasse o ESP8266, naquela época a gente vivia um conflito entre o ESP8266-01 e o Xbee que eu tinha uma grande paixão.
Para eu projetar um módulo nos padrões do formato do xbee eu precisaria de GPIOs analógicos, fato que o módulo ESP8266-12, utilizado na placa de desenvolvimento chamada NodeMCU, trazia apenas
uma entrada analógica, eu precisava pelo menos de 4 portas analógicas para desenvolver a WROOMBEE.

Sabiamente eu esperei e algum tempo depois fora lançado o ESP32, que trazia mais recursos e principalmente as portas analógicas que eu tanto precisava, o que me fez naquele momento decidir pelo retorno ao projeto do nosso módulo WROOMBEE Xbee form factor. 

<p align="center">
<img width="885" height="383" src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/pinagem%20wroombee.png">
</p align="center">

De fato foi um grande desafio, pois eu teria que projetar o módulo considerando algumas particularidades do ESP32-WROOM-32 que eu utilizei no projeto, o fato era que alguns GPIOs, eram utilizados na reinicialização do módulo, além de que quando ele era utilizado com o módulo nas funções WiFi ou BLE, alguns GPIOs eram necessários para essas funcionalidades, principalmente os GPOIs analógicos.

Para a programação do firmware eu optei por fazer da forma manual através de um slide switch, o que nos gerou alguma economia com alguns componentes, bem como eliminou alguns problemas que tinha na gravação do firmware nas  
versões do ESP32 NodeMcu - DevKit V1, que possui um botão de PROG e outro de RESET para caso de falhas na gravação do código.

<p align="center">
<img width="776" height="474" src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/wroombee-tibee-d.PNG">
</p align="center">

## DIAGRAMA DE VICENTE

Abaixo nosso diagrama com o resumo das funcionalidades da WROOMBEE ESP32.

<p align="center">
<img width="594" height="544" src="https://github.com/sirineo-technologies/WROOMBEE/blob/main/Figura/Diagrama%20de%20Vicente%20-%20WROOMBEE%20-%20PNG.png">
</p align="center">

## Nosso e-mail

<a target="_blank" href="mailto:sirineotechnologies.adm@gmail.com">
  <img align="left" alt="Gmail" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />
</a> commercialbusiness@sirineotechnologies.com

## Nossas Redes Sociais

Ajude o desenvolvimento de hardware no Brasil ! Nos ajude compartilhando, curtindo e comentando nossas publicações em nossas Redes Sociais.

<br>
<a target="_blank" href="http://sirineotechnologies.com/">
  <img align="left" alt="LinkdeIN" width="22px" src="https://visualpharm.com/assets/378/Website-595b40b65ba036ed117d1098.svg" />
</a>
<a target="_blank" href="https://t.me/+JRUYf0m6IjE0ZGMx">
  <img align="left" alt="LinkdeIN" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
</a>
<a target="_blank" href="https://www.linkedin.com/company/sirineo-technologies">
  <img align="left" alt="LinkdeIN" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a target="_blank" href="https://www.instagram.com/sirineotechnologies">
  <img align="left" alt="Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a target="_blank" href="https://web.facebook.com/Sirineotechnologies/">
  <img align="left" alt="Facebook" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />
</a>
<a target="_blank" href="https://twitter.com/sirineotech">
  <img align="left" alt="LinkdeIN" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a target="_blank" href="https://www.youtube.com/channel/UCXL7DX-jfyiIgiR7kq9hfNw">
  <img align="left" alt="LinkdeIN" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<a target="_blank" href="https://www.tiktok.com/@sirineotechnologies">
  <img align="left" alt="LinkdeIN" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/tiktok.svg" />
</a>

<br>

## Conheça nosso Laboratório BabaçuLAB VICENTE

Temos um laboratório onde desenvolvemos nossas pesquisas de hardware, venha e faça uma visita !

<a target="_blank" href="https://www.instagram.com/babaculab.sirineo/reels/">
  <img align="left" alt="Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<br>

## Autor

Cirineu - engereggae 

<a target="_blank" href="https://www.linkedin.com/in/cirineu-carvalho-fernandes-20490a37/">
  <img align="left" alt="linkedin" width="100px" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a> 
<a target="_blank" href="https://twitter.com/engereggae">
  <img align="left" alt="twitter" width="98px" src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>
 
:construction:  Página Github em construção  :construction:

## In memorian

Essa comunidade é inteiramente dedicada ao meu filho <b>VICENTE FERNANDES</b><br> que nos deixou dia 08/03/2022.
                                                          Obrigado meu filho
														  
## Home

:derelict_house:  [Pagina inicial SiriNEO Technologies](https://github.com/sirineo-technologies)
# MFe

Repositório para o Módulo Fiscal Eletrônico Elgin

## Sobre o Smart MFe Elgin:
Desenvolvido para atender à legislação fiscal na emissão de cupons fiscais eletrônicos do estado do Ceará, possui processador de última geração e fonte de alimentação externa, oferecendo ainda mais agilidade e confiabilidade. Características: Tecnologia GPRS. Receptor GPS. Conexão 3G. 2 portas Ethernet. 1 porta USB.
<br></br>
### Por onde começar?
=================  

Antes de mais nada, realize a liberação das seguintes portas na rede, tanto no protocolo UDP quanto no TCP:

* Portas 123 e 9035, para configuração.
* Portas 443 e 9012, para comunicação com a SEFAZ. 
* Portas 11118 e 11119, para comunicação interna (caso haja mais de um PDV por MFe)

E também dos seguintes endereços:
* ntp.cais.rnp.br
* cfews.sefaz.ce.gov.br
* pg-gateway-client.azurewebsites.net
* http://www.sefaz.ce.gov.br
* http://cfe.sefaz.ce.gov.br
* https://wsmfenacional.fazenda.sp.gov.br/
* https://wsmfesp.fazenda.sp.gov.br/
* https://wsmfehomolog.fazenda.sp.gov.br/

Caso esteja usando o Integrador:
* http://apiintegrador.azurewebsites.net
* http://integrador.blob.core.windows.net/integrador/

Em sequida, baixe os pacotes abaixo e os instale nesta **exata sequência**:

1. Driver USB V1.4: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Elgin/SMART%20MFe/Drivers)
2. Driver MFE V01.05.14: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Elgin/SMART%20MFe/Drivers)
3. SW Ativação V03.1.1.12: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Elgin/SMART%20MFe/Ativador)

Após a instalação, realize o teste no aplicativo comercial.
<br></br>

### Documentação
=================  
A maior parte destes artefatos foi retirado do site da SEFAZ-CE. Consulte [este](https://cfe.sefaz.ce.gov.br/mfe/informacoes/downloads#/) endereço para a lista completa de aplicativos, documentações, manuais, exemplos, etc.

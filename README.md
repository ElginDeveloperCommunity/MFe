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


Em sequida, baixe os pacotes abaixo e os instale nesta **exata sequência:

1. Driver USB V1.4: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Drivers)
2. Driver MFE V01.05.14: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Drivers)
3. SW Ativação V03.1.1.33: [Aqui](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Ativador)

Após a instalação, realize o teste no aplicativo comercial.
<br></br>

### Documentação
=================  
[Documentação](https://github.com/ElginDeveloperCommunity/MFe/tree/master/Documentacao)

**IMPORTANTE**: A maior parte destes artefatos foi retirado do site da SEFAZ-CE. Consulte este endereço para a lista completa de aplicativos, documentações, manuais, exemplos, etc.

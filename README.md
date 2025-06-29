# Mergulhando nas Redes como um Tubarão

Nessa instrução vamos nos aprofundar sobre o que acontece quando uma requisição-resposta entre cliente e servidor é processada. Faremos atividades práticas para simular esses processos, e compreenderemos ainda mais sobre Redes de Computadores.

# Galera, dá uma olhada nessa imagens. Com elas, vocês vão aprender o que é a Internet e seus Protocolos.

## Pontes

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/pontes.png">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/pontes.png)">
</picture>

## Mapas

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/mapas.jpg">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/mapas.jpg)">
</picture>

## Transportes

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/modais-de-transporte.jpg">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/modais-de-transporte.jpg)">
</picture>

## Compartilhamento de informações

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/compartilhamento.jpg">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/compartilhamento.jpg)">
</picture>

# Tipos de Redes

## 1) PAN

**Personal Area Network (PAN)** é uma rede de computadores usada para comunicação entre dispositivos próximos a uma pessoa. Normalmente, essas redes cobrem um raio de poucos metros. Na rede PAN têm-se os dispositivos:

* Smartphones;
* Computadores;
* Fones de ouvido;
* Mouse e teclado;
* Relógios;
* Impressoras e outros dispositivos pessoais.



### 1.1) Tecnologias de Conexão

As tecnologias mais comuns usadas em PANs são Bluetooth, ZigBee (conexão usada em ambientes com ruído eletromagnético) e NFC (Near Field Communication, usado no cartão de crédito) e, em alguns casos, o Wi-Fi.

### 1.2) Como Funciona uma Rede PAN?

As PANs funcionam através da comunicação direta entre dispositivos ou via um ponto de acesso central. A seguir, vamos explorar algumas das tecnologias mais comuns utilizadas em PANs.

### 1.3) Vantagens da PAN

* Mobilidade: permite a comunicação entre dispositivos pessoais em movimento;
* Fácil Configuração: geralmente, a configuração é simples e rápida;
* Conectividade sem fio: elimina a necessidade de cabos, proporcionando conveniência.

### 1.4) Desvantagens da PAN

* Alcance Limitado: o alcance é restrito a poucos metros;
* Interferência: pode haver interferência de outros dispositivos sem fio na mesma faixa de frequência;
* Segurança: a segurança pode ser uma preocupação, especialmente em tecnologias como Bluetooth.

### 1.5) Aplicações Práticas de Redes PAN

* Automação residencial: conectar e controlar dispositivos domésticos como lâmpadas inteligentes, termostatos e fechaduras;
* Acessórios pessoais: conectar fones de ouvido Bluetooth a smartphones;
* Saúde e fitness: Sincronização de dados entre smartwatches e aplicativos de saúde em smartphones.

## 2) LAN

**Local Area Network (LAN)** é uma rede de computadores que abrange uma área geográfica limitada, como uma residência, escola, laboratório, universidade ou prédio comercial. A principal característica das LANs é que elas são redes de alta velocidade que conectam computadores e dispositivos em uma área relativamente pequena.)

Na rede LAN têm-se os dispositivos:
 
* Computadores;
* Servidores;
* Impressoras;
* Switches (conectam dispositivos dentro da LAN);
* Roteadores (conectam a LAN à Internet);
* Cabos e Conectores;
* Pontos de Acesso (AP).


### 2.1) Tecnologias de Conexão

As tecnologias de conexão das LANs são de fio ou sem fio (rádio). No fio, a tecnologia de conexão chama-se **Ethernet** com as versões CAT5e, CAT6, CAT6a, CAT7 e no sem fio, **Wi-Fi** (Wireless Fidelity) têm-se as versões de tecnologias 802.11n, 802.11ac e o mais recente 802.11ax (Wi-Fi 6). Existe ainda o PLC (Power Line Communication) e a fibra óptica.

### 2.2) Como Funciona uma Rede LAN?

As LANs funcionam através da interconexão de dispositivos usando cabos Ethernet ou conexões sem fio. A seguir, vamos explorar algumas das tecnologias mais comuns utilizadas em LANs. As redes cabeadas são sempre mais velozes.

### 2.3) Vantagens da LAN

* Alta velocidade: oferece altas taxas de transferência de dados;
* Confiabilidade: conexões por cabo são muito estáveis e confiáveis;
* Compartilhamento de Recursos: facilita o compartilhamento de recursos como impressoras e arquivos.

### 2.4) Desvantagens da LAN

* Alcance limitado: cobertura restrita a uma área geográfica pequena;
* Custo de instalação: configurar uma LAN com cabeamento pode ser caro;
* Manutenção: requer manutenção regular para garantir o bom funcionamento.

### 2.5) Aplicações Práticas de Redes LAN

* Ambientes empresariais: conectar computadores e servidores em um escritório;
* Instituições de ensino: interconectar laboratórios de informática e dispositivos educacionais;
* Residências: conectar dispositivos domésticos como computadores, consoles de jogos e smart TVs.


## 3) MAN

**Metropolitan Area Network (MAN)** é uma rede de computadores que abrange uma área geográfica maior do que uma LAN, mas menor do que uma **WAN (Wide Area Network)**. Normalmente, uma MAN conecta várias LANs dentro de uma cidade ou região metropolitana para compartilhar recursos e serviços. Os dispositivos da MAN são:

* Roteadores, switches e servidores;
* Cabos de Fibra Óptica: Utilizados para conexões de alta velocidade entre diferentes LANs;
* Provedores de Serviço de Internet (ISP): são as empresas de telecom que fornecem a infraestrutura necessária para conectar as redes em uma área metropolitana;
* Equipamentos de Comunicação Com e Sem Fio: utilizados para conexões ponto-a-ponto ou multiponto entre LANs.

### 3.1) Tecnologias de Conexão

Fibra óptica ou links sem fio, que são rádios de micro-ondas que parecem antenas parabólicas ou antenas quadradas.


### 3.2) Como Funciona uma Rede MAN?

As MANs funcionam conectando várias LANs através de enlaces de alta velocidade.

### 3.3) Vantagens da MAN

* Alta velocidade: oferece altas taxas de transferência de dados entre diferentes LANs;
* Ampla cobertura: conecta redes em uma grande área geográfica;
* Eficiência de custo: compartilhamento de recursos e serviços reduz custos.

### 3.4) Desvantagens da MAN

* Complexidade de instalação: requer infraestrutura sofisticada e planejamento;
* Custo inicial: alto custo de instalação de fibra óptica e outros equipamentos;
* Manutenção: necessita de manutenção regular e suporte técnico especializado.

### 3.5) Aplicações Práticas de Redes MAN

* Governo e administração pública: Conectar diferentes departamentos e agências dentro de uma cidade;
* Instituições educacionais: Interconectar campus universitários e bibliotecas;
* Empresas grandes: Conectar escritórios e filiais espalhados por uma área metropolitana.

## 4) WAN

Uma **Wide Area Network (WAN)** é uma rede de computadores que abrange uma grande área geográfica, permitindo a comunicação e compartilhamento de recursos entre dispositivos e redes distantes. As WANs são essenciais para conectar escritórios corporativos, instituições governamentais, universidades e outros usuários que precisam de comunicação de longa distância.

Componentes:

* Roteadores e switches: dispositivos que direcionam o tráfego de rede e conectam diferentes redes;
* Linhas de comunicação: incluem cabos de fibra óptica, cabos submarinos, satélites e enlaces de rádio;
* Provedores de serviços de telecomunicações e Internet: empresas que fornecem infraestrutura de comunicação para conectar diferentes partes da WAN e à Internet.

### 4.1) Tecnologias de Conexão

As tecnologias de transmissão mais comuns: 

* Fibra óptica marítma;
* Satélites;
* MPLS (Multiprotocol Label Switching) que é um protocolo moderno que integra várias redes de telecomunicações, como celular e links de banda larga.

### 4.2) Como Funciona uma Rede WAN?

As WANs funcionam conectando várias LANs e MANs através de longas distâncias usando diversas tecnologias de transmissão.

### 4.3) Vantagens da WAN

* Conectividade global: permite a comunicação entre redes em diferentes locais geográficos;
* Compartilhamento de recursos: facilita o compartilhamento de recursos e informações entre escritórios e usuários dispersos;
* Escalabilidade: pode ser expandida para incluir novas regiões ou usuários conforme necessário.

### 4.4) Desvantagens da WAN

* Custo Elevado: implementação e manutenção podem ser caras;
* Complexidade: requer infraestrutura sofisticada e gerenciamento especializado;
* Latência: pode haver atrasos na comunicação devido à distância e à tecnologia utilizada.

### 4.5) Aplicações Práticas de Redes WAN

* Empresas multinacionais: conectar escritórios em diferentes países;
* Instituições governamentais: compartilhamento de informações e recursos entre departamentos em diferentes locais.
* Provedores de Serviços de Internet (ISP - Internet Service Provider): fornecer conectividade à internet em grande escala.

# Modelo TCP/IP

## Definição do Modelo TCP/IP

O modelo TCP/IP, também conhecido como **Modelo de Internet**, é um conjunto de protocolos de comunicação que forma a base da Internet. 


<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/modeloTCP-IP.png">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/modeloTCP-IP.png)">
</picture>



## Onde os protocolos vão?


<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/camadas_v2.png">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/camadas_v2.png)">
</picture>


## De que forma?

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/m02-semana10/blob/main/imgs/TCP-IPfig1.png">
   <img alt="Tipo de Modelagens" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/m02-semana10/blob/main/imgs/TCP-IPfig1.png)">
</picture>



## Vantagens do Modelo TCP/IP

1. **Interoperabilidade Universal**:
    - **Explicação**: o modelo TCP/IP é amplamente adotado e suportado por praticamente todos os sistemas operacionais e dispositivos de rede, o que facilita a comunicação e integração entre diferentes tecnologias e plataformas.
    - **Exemplo**: Um smartphone rodando iOS pode se comunicar sem problemas com um servidor rodando Linux, graças ao uso comum do TCP/IP.

2. **Escalabilidade**:
    - **Explicação**: o TCP/IP foi projetado para escalar eficientemente, suportando desde pequenas redes locais até a vasta rede global da Internet.
    - **Exemplo**: uma empresa pode começar com uma pequena rede interna e expandir para uma rede global sem a necessidade de substituir a infraestrutura ou os protocolos de comunicação.

3. **Robustez e Flexibilidade**:
    - **Explicação**: o modelo é robusto e flexível, capaz de se adaptar a diferentes tecnologias de rede e resistir a falhas parciais na rede.
    - **Exemplo**: se uma rota de dados na Internet falhar, o TCP/IP pode redirecionar o tráfego por outras rotas, garantindo que a comunicação não seja interrompida.

## Desvantagens do Modelo TCP/IP

1. **Complexidade na Configuração**:
    - **Explicação**: a configuração de redes TCP/IP pode ser complexa, exigindo conhecimentos técnicos avançados para ajustar parâmetros como endereçamento IP, sub-redes e roteamento.
    - **Exemplo**: configurar uma rede corporativa com múltiplos roteadores e sub-redes requer uma compreensão detalhada de conceitos como máscara de sub-rede e tabelas de roteamento.

2. **Sobrecarga de Protocolo**:
    - **Explicação**: o protocolo TCP, em particular, adiciona uma sobrecarga significativa devido à necessidade de estabelecer e manter conexões, o que pode impactar a performance em redes com recursos limitados.
    - **Exemplo**: em redes de sensores ou dispositivos IoT com pouca largura de banda, a sobrecarga do TCP pode resultar em menor eficiência na transmissão de dados.

3. **Segurança Limitada por Padrão**:
    - **Explicação**: o TCP/IP foi desenvolvido com pouca preocupação com a segurança, e muitas de suas funcionalidades nativas são vulneráveis a ataques. Medidas de segurança adicionais são frequentemente necessárias.
    - **Exemplo**: o protocolo não possui mecanismos de criptografia ou autenticação nativos, necessitando de camadas extras de segurança, como VPNs ou TLS, para proteger os dados.

# Faixa de Endereçamentos IP

## Entendendo o CIDR: Uma Maneira Flexível de Endereçar Redes

CIDR - Classless Inter-Domain Routing.

Imagine que você precisa organizar um grande número de casas em uma cidade. Em vez de usar nomes de ruas e números de casas individuais, você decide agrupá-las em bairros. 

Cada bairro tem um nome e um número que representa quantas casas ele contém. Essa é a ideia básica por trás do CIDR.

## O que é CIDR?

CIDR é um método para alocar e identificar endereços IP em redes de computadores. Ele substitui o antigo sistema de classes de endereços (A, B, C) por uma abordagem mais flexível. Em vez de classes fixas, o CIDR usa prefixos de comprimento variável para definir o tamanho de uma rede.

## Como Funciona?

Um endereço CIDR é composto por duas partes:

1. **Endereço IP:** um endereço IP normal (por exemplo, 192.168.1.0).
2. **Prefixo:** um número que indica quantos bits do endereço IP são usados para **identificar o bairro**, que nesse conceito, chama-se **REDE** (por exemplo, /24).

O prefixo define a máscara de sub-rede e o número de endereços IP disponíveis na rede. Por exemplo:

* **/24:** são 24 bits todos **1**, logo usamos uma máscara = 255.255.255.0, e sobram 8 bits, totalizando 256 endereços IP de **CASAS** ou **COMPUTADORES**;
* **/25:** são 26 bits todos **1**, logo usamos uma máscara = 255.255.255.128, e sobram 7 bits, totalizando 128 endereços IP de COMPUTADORES;
* **/26:** são 27 bits todos **1**, logo usamos uma máscara = 255.255.255.192, e sobram 6 bits, totalizando 64 endereços IP de COMPUTADORES;

**Vantagens do CIDR:**

* **Alocação Eficiente:** Permite alocar endereços IP de forma mais granular, evitando o desperdício de endereços que ocorria com as classes fixas.
* **Roteamento Simplificado:** Facilita o roteamento de pacotes na internet, pois os roteadores podem usar o prefixo para determinar rapidamente a rede de destino.
* **Escalabilidade:** Adapta-se facilmente ao crescimento da internet, permitindo a criação de redes de diferentes tamanhos.

## Faixas de Endereços Privados (Gratuitos)

São faixas reservadas para uso em redes locais e não são roteados na Internet pública. Você pode usá-los livremente dentro de sua rede doméstica ou empresarial:

* 10.x.x.x,
* 172.16.x.x a 172.31.x.x e
* 192.168.x.x 

**Exemplo Prático:**

Você tem uma rede com o endereço IP 192.168.1.0 e precisa dividi-la em quatro sub-redes menores. Usando o CIDR, você pode fazer o seguinte:

* **Sub-rede 1:** 192.168.1.0/26
* **Sub-rede 2:** 192.168.1.64/26
* **Sub-rede 3:** 192.168.1.128/26
* **Sub-rede 4:** 192.168.1.192/26

Cada sub-rede terá 64 endereços IP disponíveis para seus dispositivos.

**Conclusão:**

O CIDR é uma ferramenta essencial para o endereçamento de redes na internet moderna. Sua flexibilidade e eficiência o tornam ideal para lidar com o crescimento contínuo da rede e a demanda por endereços IP. Se você trabalha com redes de computadores, entender o CIDR é fundamental para planejar e gerenciar suas redes de forma eficaz.


# Prática usando ```ipconfig /all```

## Orientações

### 1) Cada aluno precisa abrir o link a seguir e preencher os campos em vermelho no respectivo assento da sua bancada. Use o comando ```ipconfig /all``` no CMD do seu computador para puxar os dados necessários. No iMAC faça testes com ```system_profiler SPNetworkDataType```

[CLIQUE AQUI](https://docs.google.com/presentation/d/1juQH2R2auQRocWxc2rCXlqJZy550fF74A7VYAapsnHk/edit?usp=sharing)

# Prática com Wireshark

Caso não tenha instalado o Wireshark, vai dando NEXT e marque todas as opções na tela do Ncap.
Se aparecer várias telas pedindo permissão de administrador, vai dando SIM em todas até não ter mais nenhuma.

Clique no ícone da barbatana azul do tubarão no canto esquerdo superior. Isso vai abrir uma janela de observação de protocolos.

### 2) Observe a tela do Wireshark monitorando os diferentes protocolos que aparecem por 5 minutos e anote 5 protocolos diferentes que estão na lista.

[RELATÓRIO](https://docs.google.com/document/d/1IGRt-VtoJPHgFFuW-glrpMJ2s2PYaDem2KLrSdBYAog/edit?usp=sharing)


| Tipo de Evento     | O que está acontecendo?                                                             |
| ------------------ | ----------------------------------------------------------------------------------- |
| ARP                | Dispositivos buscando/confirmando IPs na LAN.                                       |
| TCP/TLS (HTTPS)    | Sessões seguras entre cliente `10.128.1.72` e servidores externos (TLS 1.2 e 1.3).  |
| DNS                | Resolução de nomes como `slackb.com` para IPs públicos.                             |
| mDNS/SSDP          | Dispositivos descobrindo serviços de mídia e rede na LAN.                           |
| DHCP               | Dispositivos se conectando e negociando IP com o servidor.                          |
| ACKs fora de ordem | Alta carga de dados sendo transmitida, possível buffer ou reenvio por controle TCP. |


### 3) Cada grupo deve montar uma apresentação de 5min definindo os protocolos que está observando, dar um exemplo de um pacote observado. Os 2 melhores grupos que melhor fazer um historytelling explicando os seus protocolos com os seus exemplos, leva um chocolate.





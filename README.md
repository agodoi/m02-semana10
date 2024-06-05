# Mergulhando nas Redes

Nessa instrução vamos nos aprofundar sobre o que acontece quando uma requisição-resposta entre cliente e servidor é processada. Faremos atividades práticas para simular esses processos, e compreenderemos ainda mais sobre Redes de Computadores.

Roteiro

Explicar a rede PAN do aluno (teclado, mouse e fone de ouvido);
Explicar a rede LAN do Inteli (roteadores locais, firewall)
Rede WAN da ISP que o Inteli contratou (roteadores WAN), fibra óptica e rádio
Internet, comutação de pacotes, rede heterogênea, comutação de pacotes, backbone, cabos submarinos, satélites

Protocolos em Camadas, vantagens e desvantagens, conceituar, figura 1.13 do livro, 1.15
Modelo TCP/IP, explicar as camadas.

Uso do CIDR para organizar os endereços IP
Faixa de endereçso gratuitos

Prática:
ipconfig /all --> pegue o seu IP local, Gateway Padrão
ping
tracert
Wireshark, vai dando NEXT e marque todas as opções na tela do Ncap
Se aparecer várias telas pedindo permissão de administrador, vai dando SIM em todas.

Fazer um esquema no draw.io que monte uma rede com todos os computadores e nomes
nome do computador
Dados do Adaptador de Rede sem Fio:
IPv4, máscara, DNS, MAC address, IPV6, gateway, servidor DHCP

imagem 2.1
3.1 (transporte)
3.12
4.1 (rede)
5.1 (enlace)
6.1 (não confirmei se existe)
7.1

colisões entre pacotes no wifi, figura 6.7

Explicar os protocolos 

IMCP
UDP
TCP
SSDP
FTP


# Tipos de Redes

## 1) PAN

**Personal Area Network (PAN)** é uma rede de computadores usada para comunicação entre dispositivos próximos a uma pessoa. Normalmente, essas redes cobrem um raio de poucos metros. Na rede PAN têm-se os dispositivos:

* Smartphones;
* Computadores;
* Fones de ouvido;
* Mouse e teclado;
* Relógios;
* Impressoras e outros dispositivos pessoais.

[Diagrama de uma Rede PAN]

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

[Diagrama de uma Rede LAN]

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



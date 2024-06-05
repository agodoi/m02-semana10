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

* smartphones
* computadores
* fones de ouvido
* mouse e teclado
* relógios
* impressoras e outros dispositivos pessoais.

[Diagrama de uma Rede PAN]

### 1.1) Tecnologias de Conexão

As tecnologias mais comuns usadas em PANs são Bluetooth, ZigBee (conexão usada em ambientes com ruído eletromagnético) e NFC (Near Field Communication, usado no cartão de crédito) e, em alguns casos, o Wi-Fi.

### 1.2) Como Funciona uma Rede PAN?

As PANs funcionam através da comunicação direta entre dispositivos ou via um ponto de acesso central. A seguir, vamos explorar algumas das tecnologias mais comuns utilizadas em PANs.

### 1.3) Vantagens da PAN

* Mobilidade: permite a comunicação entre dispositivos pessoais em movimento.
* Fácil Configuração: geralmente, a configuração é simples e rápida.
* Conectividade Sem Fio: elimina a necessidade de cabos, proporcionando conveniência.

### 1.4) Desvantagens da PAN

* Alcance Limitado: o alcance é restrito a poucos metros.
* Interferência: pode haver interferência de outros dispositivos sem fio na mesma faixa de frequência.
* Segurança: a segurança pode ser uma preocupação, especialmente em tecnologias como Bluetooth.

### 1.5) Aplicações Práticas de Redes PAN

* Automação Residencial: conectar e controlar dispositivos domésticos como lâmpadas inteligentes, termostatos e fechaduras.
* Acessórios Pessoais: conectar fones de ouvido Bluetooth a smartphones.
* Saúde e Fitness: Sincronização de dados entre smartwatches e aplicativos de saúde em smartphones.

## 2) LAN

**Local Area Network (LAN)** é uma rede de computadores que abrange uma área geográfica limitada, como uma residência, escola, laboratório, universidade ou prédio comercial. A principal característica das LANs é que elas são redes de alta velocidade que conectam computadores e dispositivos em uma área relativamente pequena.)

Na rede LAN têm-se os dispositivos:
 
* Computadores
* Servidores
* Impressoras
* Switches (conectam dispositivos dentro da LAN)
* Roteadores (conectam a LAN à Internet)
* Cabos e Conectores
* Pontos de Acesso (AP)

[Diagrama de uma Rede LAN]

### 2.1) Tecnologias de Conexão

As LANs funcionam através de fio e de rádio. No fio, a tecnologia de conexão chama-se **Ethernet** e no sem fio, **Wi-Fi** (Wireless Fidelity).

### 2.2) Como Funciona uma Rede LAN?

As LANs funcionam através da interconexão de dispositivos usando cabos Ethernet ou conexões sem fio. A seguir, vamos explorar algumas das tecnologias mais comuns utilizadas em LANs. As redes cabeadas são sempre mais velozes.

### 2.3) Vantagens da LAN

* Alta Velocidade: oferece altas taxas de transferência de dados.
* Confiabilidade: conexões por cabo são muito estáveis e confiáveis.
* Compartilhamento de Recursos: facilita o compartilhamento de recursos como impressoras e arquivos.

### 2.4) Desvantagens da LAN

* Alcance Limitado: cobertura restrita a uma área geográfica pequena.
* Custo de Instalação: configurar uma LAN com cabeamento pode ser caro.
* Manutenção: requer manutenção regular para garantir o bom funcionamento.

### 2.5) Aplicações Práticas de Redes LAN

* Ambientes Empresariais: conectar computadores e servidores em um escritório.
* Instituições de Ensino: interconectar laboratórios de informática e dispositivos educacionais.
* Residências: conectar dispositivos domésticos como computadores, consoles de jogos e smart TVs.



## MAN

## WAN





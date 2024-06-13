# O que são redes?
<p align="center"><img src="/image-Redes/foto1.png" alt="Descrição da imagem" width=500 heigth=300>

Componentes Principais:
- **Nós**: Também chamados de "pontos" ou "vertices", são os elementos que fazem parte da rede. Em redes de computadores, por exemplo, os nós são os dispositivos.
- **Links**: As conexões ou caminhos que ligam os nós. Podem ser fios, cabos, sinais de rádio, etc.
- **Protocolo**: Conjunto de regras que determinam como os dados são transmitidos e recebidos na rede.

# Infraestrutura de redes e os principais equipamentos
MODEM
<p align="center"><img src="/image-Redes/foto2.png" alt="Descrição da imagem" width=200 heigth=300><br>

NIC 
<p align="center"><img src="/image-Redes/foto3.png" alt="Descrição da imagem" width=200 heigth=300><br>

HUB
<p align="center"><img src="/image-Redes/foto4.png" alt="Descrição da imagem" width=200 heigth=300><br>

SWITCH
<p align="center"><img src="/image-Redes/foto5.png" alt="SWITCH" width=200 heigth=300><br>

ROTEADOR
<p align="center"><img src="/image-Redes/foto6.png" alt="ROTEADOR" width=200 heigth=300><br><br>

O rack: Um armário para hospedar os equipamentos de hardwares como switches, roteadores, modens, fibras ópticas e organizar os cabos em patch panels. Ele é essencial em data centers e infraestruturas de redes.<br>

<img src="/image-Redes/foto7.png" alt="RACK" width=200 heigth=300><br><br>

# CABEAMENTO ESTRUTURADO
São padrões estabelecidos que definem como serão as organizações dos cabos e seus periféricos possibilitando melhor organização e performance na rede.

<img src="/image-cabeamento/c2.png" alt="Cabeamento" width=200 heigth=300><br>
---
PAR TRANÇADO

Eles são divididos categorias que determinam a velocidade de transmissão dos dados e alcance em metros que o cabo pode suportar sem a perda de pacote. <br>

<img src="/image-cabeamento/C1.png" alt="UTP" width=200 heigth=300><br>

---

<img src="/image-cabeamento/c3.png" alt="Cabo" width=500 heigth=300><br>

Fibra Óptica <br>

É a tecnologia guiada por cabo que oferece a maior velocidade de transmissão de dados chegando a altas velocidades na casa dos Gbps. A fibra é composta por pedaços de vidros que permitem a propagação dos raios de luz que sao convertidos por conversores nas extremidades das fibras.

<img src="/image-cabeamento/c4.png" alt="fibra" width=350 heigth=300><br>

# Modelo OSI e TCP/IP

<img src="/image-redes-osi/osi.png" alt="osi" width=350 heigth=300><br>

### Modelo OSI (Open Systems Interconnection)

O Modelo OSI foi desenvolvido pela ISO (International Organization for Standardization) e é composto por sete camadas, cada uma com funções específicas. Estas camadas, da mais baixa para a mais alta, são:

1. **Física**: Define os aspectos físicos da transmissão de dados, como cabos, conectores, e sinais elétricos ou ópticos.
2. **Enlace de Dados**: Responsável pela transferência de dados entre dois nós adjacentes na rede e pela detecção e correção de erros de camada física.
3. **Rede**: Gerencia o endereçamento e roteamento dos pacotes de dados entre dispositivos em diferentes redes.
4. **Transporte**: Garante a transferência confiável de dados, controle de fluxo e correção de erros de ponta a ponta.
5. **Sessão**: Estabelece, gerencia e termina sessões entre aplicações em dispositivos diferentes.
6. **Apresentação**: Traduz dados entre o formato da rede e o formato compreensível pelas aplicações, como criptografia e compressão.
7. **Aplicação**: Fornece serviços de rede diretamente às aplicações, como email, FTP, e navegadores web.

### Modelo TCP/IP (Transmission Control Protocol/Internet Protocol)

O Modelo TCP/IP foi desenvolvido pelo Departamento de Defesa dos Estados Unidos e é composto por quatro camadas, sendo mais simplificado e amplamente utilizado na prática, especialmente na Internet. As camadas são:

1. **Acesso à Rede:** Combina as funções das camadas Física e Enlace de Dados do modelo OSI, tratando do hardware e dos métodos de acesso ao meio físico.
2. **Internet**: Corresponde à camada de Rede do modelo OSI, sendo responsável pelo endereçamento, roteamento e encaminhamento dos pacotes. O principal protocolo é o IP .
3. **Transporte**: Similar à camada de Transporte do modelo OSI, proporciona comunicação ponta a ponta, controle de fluxo e correção de erros. Os principais protocolos são TCP (Transmission Control Protocol) e UDP (User Datagram Protocol).
4. **Aplicação**: Combina as funções das camadas Sessão, Apresentação e Aplicação do modelo OSI, fornecendo serviços de rede diretamente às aplicações. Exemplos incluem HTTP, FTP, SMTP.

### Comparação entre OSI e TCP/IP

- **Camadas**: O modelo OSI tem sete camadas, enquanto o TCP/IP tem quatro camadas.
- **Desenvolvimento**: OSI foi desenvolvido pela ISO como um padrão teórico, enquanto o TCP/IP foi desenvolvido pelo Departamento de Defesa dos EUA e é usado praticamente na Internet.
- **Implementação**: TCP/IP é amplamente utilizado na prática, enquanto o OSI é mais utilizado para fins educativos e de referência.

# IPVA e IPV6

<img src="/image-redes-osi/ip.png" alt="ip" width=350 heigth=300><br>

- Byte é um conjunto de bits, necessário 8 bits para formar um byte

- O IPv4 (Internet Protocol version 4) é a quarta versão do protocolo IP, um conjunto de regras que define como os dados são enviados e recebidos através da internet. O IPv4 usa endereços de 32 bits, o que permite cerca de 4,3 bilhões de endereços únicos. Um endereço IPv4 é geralmente escrito no formato decimal pontuado, como 192.168.0.1.

### Estrutura do IPv4

- Um endereço IPv4 é composto por quatro octetos (8 bits cada), representados como quatro números decimais separados por pontos. Cada octeto pode ter um valor de 0 a 255. Por exemplo, o endereço 192.168.1.1 é um endereço IPv4 válido.

### IP Público e NAT

- **IP Público**: Um endereço IP público é aquele que é acessível pela internet e é atribuído por um provedor de serviços de internet (ISP). Cada dispositivo que se comunica diretamente na internet deve ter um endereço IP público.
- **NAT (Network Address Translation)**: O NAT é uma técnica usada para mapear um endereço IP privado a um endereço IP público. Ele é frequentemente usado em roteadores para permitir que múltiplos dispositivos em uma rede local (com endereços privados) compartilhem um único endereço IP público. Técnica utilizada por roteadores para permitir que dispositivos em uma rede local (com endereços IP privados) acessem a internet (usando um endereço IP público).

Quando um dispositivo na rede local envia um pacote para a internet, o roteador usa NAT para substituir o endereço IP privado do remetente pelo endereço IP público do roteador. Quando a resposta chega, o roteador usa uma tabela de NAT para encaminhar o pacote de volta ao dispositivo correto na rede local.

Em resumo, o IPv4 e o NAT são fundamentais para o funcionamento eficiente da internet atual, permitindo a comunicação entre redes privadas e a internet pública, bem como a conservação de endereços IP públicos.

# IPV6

IPv6 (Internet Protocol version 6) é a versão mais recente do Protocolo de Internet (IP), projetada para substituir o IPv4 devido à escassez de endereços IP disponíveis no IPv4. Aqui está uma explicação detalhada sobre o IPv6, suas características e benefícios:

### Motivo para IPv6

- **Escassez de Endereços IPv4**: O IPv4 usa endereços de 32 bits, permitindo aproximadamente 4,3 bilhões de endereços únicos. Com o crescimento exponencial de dispositivos conectados à internet, esses endereços estão quase esgotados.
- **Necessidade de Mais Endereços**: O IPv6 usa endereços de 128 bits, permitindo um número extremamente grande de endereços (aproximadamente 3.4×1038 endereços), suficiente para acomodar o crescimento futuro da internet.
    
    3.4×10383.4 \times 10^{38}
    

### Estrutura do IPv6

Um endereço IPv6 é composto por 128 bits e é geralmente escrito como oito grupos de quatro dígitos hexadecimais, separados por dois pontos. 

### Benefícios do IPv6

1. **Espaço de Endereçamento Expandido**: Com 128 bits, o IPv6 oferece um número praticamente ilimitado de endereços, acomodando o crescimento da internet e a proliferação de dispositivos IoT (Internet das Coisas).
2. **Configuração Automática**: O IPv6 suporta auto-configuração de endereços sem a necessidade de um servidor DHCP, utilizando o SLAAC (Stateless Address Autoconfiguration).
3. **Segurança Integrada**: O suporte nativo ao IPsec (Internet Protocol Security) é incorporado ao IPv6, fornecendo autenticação e criptografia.
4. **Melhoria no Roteamento**: Simplifica as tabelas de roteamento e elimina a necessidade de NAT (Network Address Translation), facilitando a comunicação ponto a ponto.
5. **Qualidade de Serviço (QoS)**: Melhor suporte para identificar e priorizar o tráfego de dados, importante para serviços como VoIP e streaming de vídeo.

# Calculo de sub rede

<img src="/image-redes-osi/calculo.png" alt="calculo" width=350 heigth=300><br>

<img src="/image-redes-osi/ex.png" alt="ex" width=350 heigth=300><br>

### Converter cada octeto em binário

- **Octeto 1: 192**:
    - 192 dividido por 2 é igual a 96 com um resto de 0 (bit menos significativo).
    - 96 dividido por 2 é igual a 48 com um resto de 0.
    - 48 dividido por 2 é igual a 24 com um resto de 0.
    - 24 dividido por 2 é igual a 12 com um resto de 0.
    - 12 dividido por 2 é igual a 6 com um resto de 0.
    - 6 dividido por 2 é igual a 3 com um resto de 0.
    - 3 dividido por 2 é igual a 1 com um resto de 1.
    - 1 dividido por 2 é igual a 0 com um resto de 1 (bit mais significativo).
    
    Portanto, o octeto 192 em binário é 11000000.
    
- **Octeto 2: 168**:
    - Siga o mesmo processo de divisão por 2.
    
    168 dividido por 2 é igual a 84 com um resto de 0 (bit menos significativo).
    84 dividido por 2 é igual a 42 com um resto de 0.
    42 dividido por 2 é igual a 21 com um resto de 0.
    21 dividido por 2 é igual a 10 com um resto de 1.
    10 dividido por 2 é igual a 5 com um resto de 0.
    5 dividido por 2 é igual a 2 com um resto de 1.
    2 dividido por 2 é igual a 1 com um resto de 0.
    1 dividido por 2 é igual a 0 com um resto de 1 (bit mais significativo).
    
    Portanto, o octeto 168 em binário é 10101000.
    
- **Octeto 3: 10**:
    - Siga o mesmo processo de divisão por 2.
    
    10 dividido por 2 é igual a 5 com um resto de 0 (bit menos significativo).
    5 dividido por 2 é igual a 2 com um resto de 1.
    2 dividido por 2 é igual a 1 com um resto de 0.
    1 dividido por 2 é igual a 0 com um resto de 1 (bit mais significativo).
    
    Portanto, o octeto 10 em binário é 00001010.

- **Octeto 4: 1**:
    - Siga o mesmo processo de divisão por 2.
    
    1 dividido por 2 é igual a 0 com um resto de 1 (bit menos significativo).
    0 dividido por 2 é igual a 0 com um resto de 0 (bit mais significativo).
    
    Portanto, o octeto 1 em binário é 00000001.
    
    R : 
    
    11000000.10101000.00001010.00000001

<img src="/image-redes-osi/formula.png" alt="formula" width=350 heigth=300><br>

A máscara de sub-rede /24, isso significa que temos 24 bits para a parte da rede e 8 bits para a parte do host.

Então, usando a fórmula  2^b−2, onde b=8

2^8−2 =  256 − 2 = 254.

Portanto, em uma sub-rede com uma máscara de sub-rede /24, podemos ter 254 hosts.

# # **Domínios, DNS e latência**

O DNS (Domain Name System), é um sistema crucial na Internet que traduz nomes de domínio, como "[google.com](http://google.com/)" ou "[facebook.com](http://facebook.com/)", em endereços IP (Protocolo de Internet) numéricos, que são utilizados pelos computadores para se comunicarem na rede.

- **Tradução de Nomes para Endereços IP**: Quando você digita um nome de domínio em um navegador da web, como "[www.google.com](http://www.google.com/)", seu computador precisa descobrir o endereço IP associado a esse nome para poder se conectar ao servidor da web do Google. Ele faz isso consultando servidores DNS.

<img src="/image-redes-osi/root.png" alt="root" width=350 heigth=300><br>

<img src="/image-redes-osi/www.png" alt="www" width=350 heigth=300><br>

Domínio é um nome exclusivo que identifica um site na internet, como "[google.com](http://google.com/)" ou "[facebook.com](http://facebook.com/)". Ele serve como o endereço principal de um site na web. Um subdomínio é um domínio que está abaixo de um domínio principal, adicionando uma hierarquia adicional ao endereço web. Por exemplo, em "[blog.google.com](http://blog.google.com/)", "blog" é o subdomínio de "[google.com](http://google.com/)". Subdomínios podem ser usados para organizar e diferenciar seções específicas de um site.

LATÊNCIA 

Latência é o tempo de atraso que ocorre entre o envio de um pacote de dados de um ponto para outro e a recepção desse mesmo pacote. 

**Latência e Cache**:

- O cache é frequentemente usado para reduzir a latência em comunicações de rede. Quando um recurso é armazenado em cache localmente, ele pode ser acessado mais rapidamente do que se precisasse ser recuperado do servidor de origem toda vez. Isso reduz o tempo de espera e melhora a experiência do usuário, especialmente para recursos da web frequentemente acessados. Ao diminuir a necessidade de acessar recursos remotos, o cache ajuda a minimizar a latência percebida pelo usuário.

Latência e CDN:

- As CDNs reduzem a latência ao distribuir conteúdo por servidores próximos aos usuários. Quando alguém solicita um recurso, como uma imagem, a CDN envia essa solicitação ao servidor mais próximo, diminuindo o tempo de transmissão. Além disso, as CDNs usam cache para armazenar temporariamente conteúdo popular, reduzindo ainda mais a latência ao evitar acessos frequentes ao servidor de origem.

# Principais comandos de configuração

-ipconfig

A função desse comando é mostrar as configurções de Ip do windows

Usado para exibir e gerenciar a configuração da rede IP (Internet Protocol) do computador. Ele fornece várias informações e opções para administrar interfaces de rede, como adaptadores Ethernet, adaptadores sem fio e conexões VPN.

# ipconfig /flushdns

O comando no Windows é utilizado para limpar o cache do DNS (Domain Name System). O DNS é responsável por traduzir nomes de domínio legíveis (como www.example.com) em endereços IP numéricos que os computadores usam para identificar e se comunicar uns com os outros na rede.

# Comando PING

O comando `ping` é uma ferramenta de linha de comando utilizada para testar a conectividade de rede entre dois dispositivos na rede IP. Ele verifica se um dispositivo pode ser alcançado e mede o tempo que os pacotes de dados levam para viajar de um dispositivo para outro e retornar.

# `nslookup`

o comando `nslookup` pode ser usado para confirmar se o endereço IP que você obteve ao usar o comando `ping` está correto e corresponde ao nome de domínio que você está tentando alcançar

# `tracert`

O comando `tracert` é uma ferramenta de diagnóstico de rede usada para rastrear o caminho que os pacotes de dados percorrem da origem (seu computador) até um destino (um servidor ou outro dispositivo na rede). Ele mostra cada ponto intermediário (nós, roteadores) pelo qual os pacotes passam até chegar ao destino final, permitindo identificar onde podem estar ocorrendo problemas de conectividade ou desempenho na rede.

# ROUTE  PRINT

O comando `route print` no Windows exibe a tabela de roteamento do computador. A tabela de roteamento contém informações sobre as rotas disponíveis para diferentes redes e como os pacotes de dados devem ser encaminhados.

# `netstat`

O comando `netstat` é para monitorar e diagnosticar o estado das conexões de rede em um sistema. Ele fornece informações sobre as conexões ativas e portas em uso.

# Segurança

Métodos e práticas recomendadas para ajudar a proteger redes e dados:

### 1. Atualizações e Patches de Segurança:

- Mantenha seu sistema operacional, aplicativos e dispositivos de rede atualizados com os patches de segurança mais recentes para corrigir vulnerabilidades conhecidas.

### 2. Firewall:

- Utilize um firewall de rede para controlar o tráfego de entrada e saída, bloquear tráfego malicioso e filtrar pacotes indesejados.

### 3. Antivírus e Antimalware:

- Instale e mantenha atualizado um software antivírus/antimalware para proteger contra ameaças como vírus, worms, trojans e spyware.

### 4. Segurança de Senhas:

- Utilize senhas fortes e exclusivas para todas as contas e dispositivos, e evite compartilhar senhas entre diferentes sistemas.
- Considere o uso de autenticação de dois fatores (2FA) para adicionar uma camada extra de segurança.

### 5. Criptografia:

- Utilize protocolos de criptografia, como SSL/TLS, para proteger a comunicação entre os dispositivos e servidores, especialmente em conexões sensíveis, como transações financeiras e login de usuário.

### 6. Segurança da Rede Wi-Fi:

- Configure sua rede Wi-Fi com um protocolo de segurança forte (por exemplo, WPA2/WPA3), e evite o uso de senhas padrão ou fáceis de adivinhar.

### 7. Segmentação de Rede:

- Divida sua rede em segmentos separados para limitar o acesso de dispositivos e usuários apenas ao que é necessário, reduzindo assim a superfície de ataque.

### 8. Monitoramento de Rede:

- Implemente soluções de monitoramento de rede para detectar e responder rapidamente a atividades suspeitas ou anormais na sua rede.

# Ransomware

**Ransomware é um tipo de malware que criptografa arquivos ou bloqueia o acesso a sistemas, geralmente exigindo o pagamento de um resgate (ransom) para restaurar o acesso ou descriptografar os arquivos. Esse tipo de ataque pode causar danos significativos, tanto para indivíduos quanto para organizações, resultando na perda de dados críticos, interrupção de operações comerciais e até mesmo prejuízos financeiros.**

# Wireless

Wireless, é uma tecnologia que permite a comunicação entre dispositivos sem a necessidade de cabos físicos. Em sistemas de comunicação sem fio, os dados são transmitidos usando ondas de rádio, infravermelho ou outros meios de comunicação sem fio.
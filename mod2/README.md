# CLIENTES E SERVIDORES

Todos os computadores conectados a uma rede que participam diretamente na comunicação de rede são classificados como hosts. Os hosts podem enviar e receber mensagens na rede. 
Nas redes modernas, um host pode atuar como cliente, servidor ou ambos. O software instalado no computador determina qual função o computador desempenha.
	
# SERVIDORES 
*Servidores são hosts que têm um software instalado que os permite fornecer informações*, como e-mail ou páginas Web, a outros hosts na rede. Cada serviço exige um software de servidor separado. 
Cada destino que você acessa on-line é fornecido por um servidor localizado em algum lugar de uma rede conectada à Internet global.
Ex: Por exemplo, um servidor exige um software de servidor Web para forneça serviços web à rede.
			
# CLIENTES
*Clientes são computadores host que têm um software instalado que os permite solicitar e exibir as informações obtidas do servidor.*
Ex's de software cliente: Navegador da Web, como Internet Explorer, Safari, Mozilla Firefox ou Chrome.
			

# REDES PONTO-A-PONTO  /  P2P

A rede ponto-a-ponto mais simples consiste em dois computadores diretamente conectados por uma conexão com ou sem fio. Ambos os computadores podem usar essa rede simples para trocar dados e serviços entre si, atuando como cliente ou servidor conforme necessário.

Vários PCs também podem ser conectados para criar uma rede ponto-a-ponto maior, mas isso exige um dispositivo de rede (como um switch) para interconectar os computadores.
Em empresas de grande porte, devido ao potencial para quantidades altas de tráfego de rede, geralmente é necessário ter servidores dedicados para suportar o número de solicitações de serviço.
	
**VANTAGENS** da rede ponto-a-ponto:
- Fácil de configurar;
- Menos complexo;
- Menor custo porque os dispositivos de rede e os servidores dedicados podem não ser necessários;
- Pode ser usada para tarefas simples como transferir arquivos e compartilhar impressoras.

**DESVANTAGENS** das rede ponto-a-ponto:
- Nenhuma administração centralizada;
- Não é tão segura;
- Não é escalável
- Todos os dispositivos podem atuar como clientes e servidores, podendo deixar seu desempenho lento.
	
	
## APLICAÇÕES P2P
Um aplicação P2P permite que um dispositivo atue como cliente e servidor na mesma comunicação. Nesse modelo, todo cliente é um servidor e todo servidor é um cliente. 
Aplicações P2P exigem que cada dispositivo final forneça uma interface de usuário e execute um serviço em segundo plano.
Ex: Ambos os clientes podem enviar e receber mensagens simultaneamente.

## MÚLTIPLAS FUNÇÕES NA REDE
Um computador com software de servidor pode fornecer serviços simultaneamente a um ou vários clientes.	
Um único computador pode executar vários tipos de software de servidor. 
Ex: Em casa ou em uma empresa pequena, pode ser necessário que um computador atue como um servidor de arquivos, um servidor Web e um servidor de e-mail.
	
Um único computador pode também executar vários tipos de software cliente. Deve haver um software cliente para cada serviço necessário.	
Com vários softwares cliente instalados, um cliente pode se conectar a vários servidores ao mesmo tempo. 
Ex: um usuário pode verificar e-mails e exibir uma página Web enquanto envia mensagens instantâneas e ouve rádio pela Internet.

# INFRAESTRUTURA DE REDE

*Infraestrutura de rede é a plataforma que suporta a rede.* Ela fornece o canal estável e confiável sobre o qual nossas comunicações podem ocorrer.
	
A infraestrutura de rede contém três categorias de componentes de rede:
- **Dispositivos finais**
    Ex: Laptop, Computador, Impressora, Telefone IP.
    	
- **Dispositivos intermediários**
    Ex: Roteador sem fio, Roteador, Switch LAN.
    	
- **Meios físicos de rede**
    Ex: Meios sem fio, Mídia LAN, Mídia WAN
    	
Dispositivos e meios físicos são os elementos físicos ou o hardware da rede. 
- O hardware é geralmente composto pelos componentes visíveis da plataforma de rede.
    Ex's: laptop, PC, switch, roteador, access point sem fio ou os cabos usados para conectar os dispositivos. 
    	
- Ocasionalmente, alguns componentes podem não ser tão visíveis. 
    Ex: No caso de meios físicos sem fio, as mensagens são transmitidas pelo ar com a utilização de freqüência de rádio invisível ou ondas infravermelhas.
    	
## Dispositivos Finais

Um dispositivo final (ou host) é a origem ou o destino de uma mensagem transmitida pela rede. Quando um host inicia a comunicação, ele usa o endereço do host de destino para especificar onde a mensagem deve ser enviada.
	
*Para identificar hosts de forma exclusiva, endereços são usados.*
	
Os dispositivos de rede com os quais as pessoas são mais familiarizadas são chamados de dispositivos finais. Estes dispositivos formam a interface entre usuários e a rede de comunicação subjacente
	
Alguns exemplos de dispositivos finais são:
- Computadores (estações de trabalho, laptops, servidores de arquivo, servidores Web);
- Impressoras de rede;
- Telefones e equipamento de teleconferência
- Câmeras de segurança;
- Dispositivos móveis (como smartphones, tablets, PDAs, leitores de cartão de débito/crédito sem fio e scanners de código de barras)

# SERVIÇOS ISP - Provedor de serviços de Internet 
Cada ISP conecta-se a outros ISPs para formar uma rede de links que interconectam usuários em todo o mundo. Os ISPs são conectados de maneira hierárquica que garante que o tráfego da Internet geralmente siga o caminho mais curto da origem ao destino.

Um provedor de serviços de Internet (ISP) fornece o link entre a rede doméstica e a Internet. Um ISP pode ser o provedor de TV a cabo local, um provedor de serviços de telefonia fixa, a rede celular que fornece seu serviço de smartphone ou um provedor independente que aluga largura de banda na infraestrutura de rede física de outra empresa.

**CONEXÕES ISP**
A interconexão de ISPs, que forma a espinha dorsal da internet, é uma teia complexa de cabos de fibra ótica com switches e roteadores de rede caros que direcionam o fluxo de informações entre os hosts de origem e destino. 

- Opção mais simples de conexão com o ISP, consiste em um modem que fornece uma conexão direta entre um computador e o ISP. 
		* Esta opção não deve ser usada, pois seu computador não está protegido na internet.
		
- Opção de conexão mais comum, consiste em usar um roteador integrado sem fio para se conectar ao ISP. 
		- O roteador inclui um switch para conectar hosts com fio e um AP sem fio para conectar hosts sem fio. O roteador também fornece informações de endereçamento IP do cliente e segurança para hosts internos.
		
		
**CONEXÕES DE CABO e DSL**

- Cabo - O sinal de dados de internet é transportado no mesmo cabo coaxial que entrega a televisão a cabo. Ele fornece uma conexão com a internet sempre ativa com alta largura de banda.
    
- DSL - Linha digital do Assinante fornece uma conexão com a internet sempre ativa e com alta largura de banda. Ele requer um modem especial de alta velocidade que separa o sinal DSL do sinal de telefone e fornece uma conexão Ethernet para um computador host ou LAN. 
    	
**OPÇÕES ADICIONAIS PARA CONECTIVIDADE**
- CELULAR
- SATÉLITE	
- CONEXÃO DISCADA:	

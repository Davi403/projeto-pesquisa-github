# Pesquisa Colaborativa - Github

Grupo: [CyberDev]

## 1. Funções de um Sistema Operacional
---

Autor: [AnnaLaura08]

[[O Sistema Operacional é o grande gestor do computador, com muitas responsabilidades como: alocar recursos, gerenciar usuários e processos, controlar a execução de programas de usuários e muito mais.]

### 1.1. Gerenciamento de processos
---
[Gerenciamento de Processos: O SO é responsável por criar, agendar e terminar processos. Ele mantém o controle de todos os processos em execução, aloca recursos para processos e facilita a comunicação e sincronização entre eles. O gerenciamento de processos é uma área complexa e vital dos sistemas operacionais que abrange a criação, execução e coordenação de processos. Desde o escalonamento e comunicação entre processos até a prevenção de deadlocks e segurança, os desafios associados ao gerenciamento de processos são significativos.]

### 1.2. Gerenciamento de arquivos
---
[O sistema de arquivos é a estrutura que permite o gerenciamento de arquivos e realiza tarefas como: criação, exclusão, leitura, gravação, controle de acesso, proteção e organização dos dados.Um gerenciador de arquivos é uma ferramenta essencial para a administração de arquivos e diretórios em sistemas operacionais. Ele permite a navegação, organização, cópia, exclusão e movimentação de arquivos de maneira intuitiva e eficiente.]

![images](URL_da_imagem)

[https://vaniabrito.blogs.sapo.pt/3488.html](https://exemplo.com)


## 2. Sistemas de Arquivos
---

Autor: [Guilherme]

[Escreva a introdução]

### 2.1. O que é um sistema de arquivos?
[Um sistema de arquivos é uma estrutura usada pelo sistema operacional para organizar e gerenciar dados armazenados em dispositivos como HDs, SSDs e pendrives. Ele permite que os dados sejam gravados, lidos, modificados e apagados de forma eficiente. Cada sistema de arquivos define como os arquivos são nomeados, armazenados e acessados. Também gerencia o espaço disponível e registra informações como data de criação e permissões. Exemplos comuns incluem FAT32, NTFS, ext4 e APFS. Sem um sistema de arquivos, o computador não saberia onde começa ou termina um arquivo. Ele também organiza os dados em pastas (diretórios). É essencial para o funcionamento de qualquer sistema de armazenamento. Cada sistema de arquivos tem vantagens e limitações específicas.]

[Escreva aqui sua explicação. Use listas, destaques, imagens e links se quiser.]

### 2.2. Tipos de sistemas de arquivos: FAT32, NTFS, ext4
[FAT32
Compatível com quase todos os sistemas.
Limite de 4 GB por arquivo.
Ideal para pendrives e cartões de memória.

NTFS
Usado no Windows.
Suporta arquivos grandes e possui recursos de segurança.
Pouca compatibilidade com outros sistemas.

ext4
Padrão no Linux.
Rápido, estável e moderno.
Não funciona nativamente no Windows ou macOS.]

[Escreva aqui sua explicação. Use listas, destaques, imagens e links se quiser.]

[https://br.easeus.com/diskmanager/sistema-de-arquivo.html](https://exemplo.com)

![file-system-work-flow](URL_da_imagem)


## 3. Gerenciamento de Dispositivos
---

Autor: [AnnaLaura08]

[O conjunto de ferramentas para gerir dispositivos, incluindo a capacidade de implementar e atualizar software, configurar definições, impor políticas e monitorizar com dados e relatórios. A capacidade de administrar e gerir dispositivos virtuais e físicos, independentemente da respetiva localização física.O Gerenciador de dispositivos exibe uma exibição gráfica do hardware instalado no computador. Use essa ferramenta quando quiser exibir e gerenciar dispositivos de hardware e seus drivers.]

### 3.1. Como o SO se comunica com impressoras, HDs, mouses etc.
[O Sistema Operacional (SO) se comunica com periféricos como impressoras, HDs e mouses através de drivers, que são programas que permitem que o SO interaja com os dispositivos de hardware. Os drivers atuam como tradutores, convertendo as instruções do SO em comandos que o dispositivo compreende e vice-versa. 
Detalhes da comunicação:
1. Periféricos de entrada:
Dispositivos como teclado e mouse enviam dados (por exemplo, teclas pressionadas ou movimentos do cursor) para o SO, que os interpreta e os usa para realizar ações no sistema. 
2. Periféricos de saída:
Impressoras recebem dados do SO e os convertem em saída física (impressão em papel). 
3. Periféricos de armazenamento:
HDs recebem dados do SO e os armazenam de forma permanente. 
4. Drivers:
Os drivers são essenciais para essa comunicação. Eles fornecem a interface entre o SO e o hardware, permitindo que o SO reconheça e utilize os dispositivos corretamente. 
5. Interfaces:
A comunicação entre o SO e os dispositivos pode ocorrer através de diferentes interfaces, como USB, Ethernet, Bluetooth, entre outras, que definem o método físico de transmissão de dados. 
6. Solicitações e respostas:
O SO pode solicitar ao dispositivo que execute uma ação (por exemplo, imprimir um documento ou ler dados de um disco rígido) e o dispositivo responde com os resultados ou com sinais de erro. 
7. Gerenciamento de recursos:
O SO também é responsável por gerenciar os recursos dos dispositivos, como a memória e o tempo de acesso.]

[Escreva aqui sua explicação. Use listas, destaques, imagens e links se quiser.]

### 3.2. O papel dos drivers de dispositivos
[Os drivers de dispositivos são programas de software que permitem que o sistema operacional (SO) interaja com o hardware de um computador. Eles atuam como tradutores, permitindo que o SO envie comandos e receba dados do dispositivo. Sem os drivers, o hardware não funcionaria corretamente, pois o SO não teria a capacidade de entender e controlar o dispositivo. 
Em resumo, os drivers:
Permitem a comunicação entre o SO e o hardware:
Traduzem os comandos do SO para uma linguagem que o dispositivo entende, e vice-versa. 
Atuam como intermediários:
Facilita a interação entre o software e o hardware, permitindo que o SO utilize as funcionalidades do dispositivo. 
São essenciais para o funcionamento de qualquer dispositivo:
Sem um driver adequado, um dispositivo pode não funcionar, ou pode funcionar de forma incorreta. 
Exemplos de drivers:
Drivers para placas de vídeo: Permitem que o SO exiba imagens e vídeos na tela.
Drivers para impressoras: Permitem que o SO envie documentos para impressão.
Drivers para mouses e teclados: Permitem que o SO receba os comandos do usuário. 
Importância dos drivers:
Funcionamento do hardware:
Garante que os dispositivos de hardware funcionem corretamente, conforme a intenção do usuário. 
Atualizações e melhorias:
Os drivers são frequentemente atualizados para corrigir bugs, melhorar o desempenho e adicionar novas funcionalidades. 
Solução de problemas:
Em caso de problemas com um dispositivo, a atualização do driver pode ser uma solução. 
Tipos de drivers:
Drivers nativos: Drivers que já vêm pré-instalados no sistema operacional. 
Drivers de terceiros: Drivers que precisam ser instalados separadamente. 
Drivers de kernel: Drivers que são parte do núcleo do sistema operacional, permitindo acesso de baixo nível aos recursos do hardware. 
Em geral, os drivers são um componente essencial do sistema operacional e são responsáveis por garantir que o hardware funcione corretamente, permitindo que os usuários interajam com seus computadores de forma eficiente.]


[https://materialpublic.imd.ufrn.br/curso/disciplina/3/16/2/7](https://exemplo.com)

![download (2)](URL_da_imagem)


## 4. Painel de Controle e Configurações
---

Autor: [Guilherme]

[Escreva a introdução]

### 4.1. O que pode ser configurado: rede, som, tela, idioma
[No Painel de Controle (Acessibilidade clássica):
Lupa: Amplia partes da tela.

Narrador: Lê textos e elementos em voz alta.

Teclado Virtual: Teclado na tela para digitar com o mouse.

Alto Contraste: Melhora a visibilidade alterando cores da interface.

Facilidade de Acesso: Centraliza várias ferramentas acessíveis.

Em Configurações (versões mais recentes do Windows):
Acesso mais visual e organizado.

Audição: Legendas, feedback visual para sons.

Visão: Ampliar texto, eliminar animações, usar o Narrador.

Mobilidade: Teclas de aderência, uso por voz, controle ocular.

Tudo em: Configurações > Acessibilidade]



### 4.2. Ferramentas de acessibilidade
[As Ferramentas de Acessibilidade no Windows ajudam usuários com deficiências a usar o computador de forma mais fácil. Elas incluem:

Narrador (leitura de tela)

Ampliador (zoom)

Teclado na tela

Personalização de mouse/teclado

Contraste alto (para melhorar a visibilidade)

Controle por voz

Legendas personalizadas

Essas opções também estão disponíveis em dispositivos móveis.]

[
[https://ajuda.fastcommerce.com.br/como-configurar-o-painel-de-controle-do-windows-para-trabalhar-com-arquivos-csv](https://exemplo.com)

![download](URL_da_imagem)


## 5. Ferramentas do Sistema
---

Autor: Davi403

[Explicando ferramentas do sistema]

### 5.1. Gerenciador de Tarefas
---

O Gerenciador de Tarefas (no Windows) e o Monitor do Sistema (no Linux/macOS) são ferramentas essenciais para monitorar e gerenciar os processos que estão a ser executados num sistema operacional. Em resumo, ajudam a entender como o computador está a ser utilizado, identificar possíveis problemas e até mesmo forçar o encerramento de processos que estão a consumir muitos recursos.

### 5.2. Prompt de Comando / Terminal
---

O "Prompt de Comando" (Windows) e o "Terminal" (Unix/Linux/macOS) são interfaces de linha de comando que permitem aos usuários interagir com o sistema operacional através de comandos de texto. Eles oferecem um acesso direto e poderoso às funcionalidades do sistema, ideal para tarefas administrativas, automatização e resolução de problemas.


[nome do site](https://linuxavante.com/gotop-monitor-grafico-de-sistema-para-linha-de-comando)

![nome da imagem](https://linuxavante.com/user/pages/01.home/gotop-monitor-grafico-de-sistema-para-linha-de-comando/gotop.webp)

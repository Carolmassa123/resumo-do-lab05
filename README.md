# resumo-do-lab05
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Computação e Rede na Azure na DIO
* VM: Virtual Machine


Computação do Azure: serviço sob demanda para recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.

Máquinas Virtuais: emulações de software de computadores físicos. Processador virtual, memória, armazenamento e rede. Serviço IaaS, oferecendo personalização e controle total.

Conjunto de dimensionamento de VM: uma oportunidade de balanceamento de carga entre vm's pares (iguais) automaticamente, para larga escala.

Conjunto de disponibilidade de VM: dividido em Rack's (domínio de falha). Cada linha horizontal é um somínio de atualização.

Área de trabaho do Azure: virtualização da área de trbalaho e aplicativo executada na nuvem. Reduzir recursos deixados para trás. Permite: ambiente daa área de trabalho sem outros servidores de gateway; reduz o risco de recursos deixados para trás; implantações reais de várias sessões (limitar, segurança e logística).

Serviços de contêiner: ambiente leve e virtualizado que não exige o gerenciameno do sistema operacional. se altera sob demanda. Podendo utilizar mais rotinas, mais prático.


Tipos de Serviço:
* Intâncias: oferta de PaaS que executa um contêiner ou pod de contêiner.
* Aplicativos: PaaS, trabalho imediato, sem balanceamento de cargas e colocação em escala, menos flexibilidade.
* Serviço de Kubernetes do Azure (AKS): orquestração (organização) paara contêiners. Quando o contêiner perde a função elee entra para organizar arquiteturas, em locais de grandes volumes de contêiners.


Azure Functions: oferta de PaaS que ad suporte a operações de computação sem servidor. Baseado em eventos, executado quando chamado. Para funções rápidas, não exige infraestrutura quando inativo.


Comparação:
* VM: servidor em nuvem (Windows w Linux); útil para lift-and-shift (levar como está); sistema operacional completo, com host.
* área de trabalho: experiência de área de trbalaho do windows, acesso limitado. Aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno. Vários usuários na mesma máquina.
* Contêiners: ambiente leve e em miniatura, para microsserviços. Para escabilidade e resiliência por emio de AKS. Aplicativos e serviços que são empacotados, ou seja vários itens dentro de um sistema operacional, consumindo recursos, sem atrapalhos entre si, facilmente encerrável.


Serviços de aplicativos: plataforma gerenciadapara criar e dimensionar aplicativos Web e API's rapidamente. Oferta PaaS em nível coorporativo de desempenho, segurança e trbalha com: .NET, .NET Core, Node.js, Java, Python ou php. Aplicativo não mexe em sistema operacional.


Rede virtual do Azure (Vnet): permite a comunicação entre os recursos dentro do Azure. Duas Vnet's não se comunicam por padrão, necessitaa emparelhamento.

Sub-redes (dentro de uma Vnet( segn=mentam a rede para atender suas necessidades. O emparelhamento conecta redes privadas diretamente.

Gateway de VPN: tráfego criptografado de rede.

Express Route: com fio. direta. Mais caro e complicado.

DNS do Azure: Domain Name Services (resolução de nome de serviço) vai se basear no gerenciador de recursos, habilitando o controle de acesso. Endereço por trás do nome de pesquisa. Para que? facilitar o gerenciamento dos recursos externos e do Azure com um único DNS ("CEP"). Podemos assim usar nomes de domínio privados e totalmente personalizados em suas redes virtuais privadas.

"Os registros de alias dão suporta de alias para apontar diretamente para um recursos do Azure"

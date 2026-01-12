\*\* O Ambiente Virtual

\*\* Máquinas virtuais \*\*

Um hypervisor é um programa de software ou hardware que permite executar vários sistemas operacionais independentes em um sistema físico. Ele é um componente chave da virtualização. Existem dois métodos de virtualização:



Virtualização de hardware (hypervisor tipo 1) - o sistema operacional convidado é executado diretamente em uma plataforma de hardware, sob o controle do sistema host.

Virtualização hospedada (hypervisor tipo II) - um aplicativo em execução na máquina host é usado para criar máquinas virtuais que consistem totalmente em software e não contêm componentes de hardware.

Os ambientes de máquinas virtuais usam um sistema operacional, portanto, eles precisam ser corrigidos. As máquinas virtuais compartilham hardware e são executadas com privilégios muito altos. Esteja ciente de que um invasor que comprometa uma máquina virtual pode comprometer a máquina host.



\*\* Contêineres \*\*

Ao contrário de uma máquina virtual, um contêiner consiste apenas no aplicativo e suas dependências. Um contêiner usa um mecanismo para emulação de sistema operacional. O Docker é uma plataforma aberta que usa a virtualização no SO para distribuir software em pacotes (contêineres). Você pode facilmente mover contêineres e o aplicativo será executado. Um software especializado como o Kubernetes permite gerenciar seus contêineres.



Se um usuário ou aplicativo tiver privilégios elevados em um contêiner, o sistema operacional subjacente poderá ser comprometido.



\*\* Infraestrutura de desktops virtuais (VDI) \*\*

Os ambientes de desktop do usuário podem ser armazenados remotamente em um servidor usando thin client ou desktops virtuais. Isso torna muito fácil criar, excluir, copiar, arquivar ou baixar configurações com rapidez em uma rede. A virtualização de desktop requer alta disponibilidade e capacidade de armazenamento.


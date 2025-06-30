# -Gerenciando-M-quinas-Virtuais-no-Azure
1. Implantação de Máquinas Virtuais
Passo a passo básico:
Escolha da plataforma: No Azure, AWS, VMware ou VirtualBox.
Criação da VM:
Defina o sistema operacional (Windows, Linux etc.).
Escolha o tamanho da máquina (CPU, RAM).
Configure a rede virtual.
Disco e armazenamento:
Selecione o tipo de disco (SSD, HDD).
Defina o tamanho e se será criptografado.
Configuração de segurança:
Crie ou selecione um grupo de segurança.
Defina regras de acesso (RDP, SSH).
Revisão e criação:
Revise as configurações e clique em “Criar”.

2. Desanexando Disco da Máquina
Quando e por que fazer isso?
Para reutilizar o disco em outra VM.
Para fazer backup ou manutenção.
Para liberar recursos.
Passos no Azure (exemplo):
Desligue a VM (se necessário).
Vá até a VM no portal do Azure.
Acesse a aba Discos.
Selecione o disco que deseja remover.
Clique em Desanexar.
O disco continuará disponível no recurso de armazenamento e poderá ser anexado a outra VM.

3. Entendendo o Desafio
O desafio está em:
Garantir alta disponibilidade e segurança.
Evitar perda de dados ao desanexar discos.
Automatizar processos com scripts ou templates.

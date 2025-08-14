# Desafio DIO - Construindo arquiteturas no Azure - Curso DIO Azure Essential

# Componentes de Arquitetura do Azure

## Regiões e Zonas de Disponibilidade
O Azure está presente em mais de 60 regiões. As regiões é onde ficam os datacenters. Já as Zonas de Disponibilidade são Datacenters interligados pela propria microsoft usando fibra otica, a fim de aumentar disponibilidade e diminuir latencia, funcionando como uma replicação.

## Assinatura e Grupos de Recursos
Uma conta azure pode ter varias assinaturas. A Assinatura é um meio de separar as cobranças.
Já o Grupo de Recursos, voce pode agrupar recursos diferentes usados por um aplicativo por exemplo. Ou tambem pode criar um Grupo de Recursos por exemplo contendo todas as maquinas virtuais, outro Grupo de Recursos contendo todos armazenamentos, outro Grupo de Recursos contemdo todos bancos de dados, etc.

## Hierarquia das Contas
1 Conta pode ter várias assinaturas
1 Assinatura pode ter vários Grupos de Recursos. E somente pode estar interligada a uma única conta.



Através do site azure.microsoft.com, podemos explorar a infraestrutura global do Azure. Onde podemos ver como funciona os datacenters.

## No portal do azure vamos criar um Grupo de recurso.

1 - No menu lateral esquerdo ou na barra de pesquisa, localize Grupo de Recursos 

2 - Selecione Criar

3 - Informe os dados:
  - Assinatura
  - Grupo de Recursos
  - Região

4 - Clique em Revisar + Criar


## Selecionando o Grupo de Recuros, temos várias opções:

**Log de Atividade:** Podemos ver quando um recurso foi criado, excluido, por quem, etc. É um recurso de auditoria.

**IAM(Controle de Acesso):** Podemos dar acesso ou remover permissão de acesso a alguém. É importante dar o mínimo de permissão para cada pessoa, para evitar excecução de operações indevidas.

**Bloqueios:** Podendo restringir o usuário de excluir recursos.

**Visualizador de Recursos:** Mostra todos recursos que tem dentro do grupo de recursos de forma visual.

**Eventos:** Pode ser criado eventos automatizados.

**Implantações:** Mostra todos os recursos implantados.

**Gerenciamento de Custos**

**Monitoramento**







---
title: 'Apêndice A: Migração do IBM Domino para o Exchange Online'
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'A migração do IBM Domino para o Exchange Online inclui vários aspectos importantes, como o que acontece durante as fases abaixo:'
ms.openlocfilehash: 17d7b6669dbd5f8647ee7dcf7218f898ddac59fc
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929265"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Apêndice A: Migração do IBM Domino para o Exchange Online

A migração do IBM Domino para o Exchange Online inclui vários aspectos importantes, como o que acontece durante as fases abaixo: 
- [Fase Iniciar](#initiate-phase)   
- [Fase Avaliar](#assess-phase)
- [Fase Corrigir](#remediate-phase)  
- [Fase Habilitar](#enable-phase)  
- [Fase Migrar](#migrate-phase)
    
## <a name="identities"></a>Identidades

Você é responsável por criar e gerenciar as identidades (somente nuvem, sincronizadas ou federadas com o Active Directory local). Você deve concluir o mapeamento de identidades (se ainda não estiverem presentes) entre o Domino e o Active Directory local ou Azure Active Directory durante os estágios iniciais de integração.
  
## <a name="coexistence"></a>Coexistência

Os Benefícios do Centro FastTrack para Office 365 fornecem fluxo de emails bidirecionais entre o ambiente Domino do local e o Exchange Online de todos os clientes.
  
## <a name="migration"></a>Migração

O processo padrão do Centro FastTrack para a migração do Domino para o Exchange Online envolve o pré-teste de dados do Domino para o Azure, antes da migração para as caixas de correio do Exchange Online. As migrações do FastTrack exigem que você e o pessoal do Centro FastTrack realizem atividades em diferentes estágios da integração. Abordaremos essas atividades nas seções a seguir.
  
> [!NOTE]
> Os dados migrados por meio dos serviços do FastTrack podem ser transferidos para os EUA ou para qualquer lugar em que a Microsoft mantenha instalações. Também podem ser armazenados e processados nesses locais. Os serviços do FastTrack não são projetados para dados sujeitos a requisitos legais ou regulamentares especiais ou se destinam a eles. 
  
## <a name="initiate-phase"></a>Fase Iniciar

 **Ações essenciais**
  
- Identificar o Domino como plataforma de correio de origem.   
- Determinar se o Centro FastTrack deve realizar a migração.
    
 **Responsabilidades do cliente**
  
- Fornecer informações básicas sobre a plataforma de mensagens de origem e confirmar a intenção de migrar com o Centro FastTrack. 
- Participar de um passo a passo sobre os processos do Benefícios do Centro FastTrack.  
- Assinar o Contrato de Serviços FastTrack.
    
## <a name="assess-phase"></a>Fase Avaliar

 **Ações essenciais**
  
- O Centro FastTrack realiza um workshop de migração com o cliente. 
- Você conclui os pré-requisitos de migração, como o questionário de migração e o provisionamento de estações de trabalho do administrador.    
- A avaliação de migração para o Domino é executada em seu ambiente local.
    
 **Responsabilidades do cliente**
  
- Provisionar estações de trabalho do administrador que o Centro FastTrack usa para administrar tarefas de integração e migração, como avaliação, criação de réplica, auditoria, configuração de encaminhamento durante a migração e assim por diante.
    > [!NOTE]
    > A avaliação é essencial para o planejamento e a execução bem-sucedida de migrações de velocidade. Ela é realizada por uma arquitetura de migração que precisa de acesso específico ao ambiente Domino. Os componentes de estação de trabalho do administrador obrigatórios incluem um cliente Notes configurado para acessar todos os servidores de email Domino de origem e o servidor de teste de réplica do Domino do Azure. 
- Fornecer à equipe de migração acesso remoto a estações de trabalho do administrador, contas e permissões para realizar atividades de avaliação e migração. Isso inclui o provisionamento de várias contas locais e no Exchange Online, com a necessidade de permissões administrativas para a migração.    
- Abrir as portas do firewall. As portas de saída devem estar abertas entre os servidores de email Domino de origem e o servidor de preparo do Azure. Outras portas para comunicação (como estações de trabalho de administração, servidores Domino de origem e servidores Exchange locais, se houver), também devem estar abertas. 
- Habilitar a certificação cruzada entre o ambiente de origem do Domino e o servidor de teste do Domino do Azure para facilitar a replicação. As tarefas de certificação cruzada são coordenadas entre o administrador do Domino do cliente e o Centro FastTrack.  
- Preencha o questionário de migração, que captura as informações necessárias para configurar o ambiente de migração no Azure (como ferramentas, scripts e servidores de migração).   
- Verifique se as caixas de correio de destino no Office 365 têm o procolo Interface do Programa de Aplicativo de Mensagens (MAPI) habilitado.  
> [!NOTE]
> Alguns planos do Office 365 não oferecem suporte para o protocolo MAPI. Para migrar dados, caixas de correio desses planos precisam ser convertidas em um plano compatível com MAPI antes do evento de migração. Após a migração, esses planos podem ser alterados novamente. 
  
## <a name="remediate-phase"></a>Fase Corrigir

 **Ações essenciais**
  
- O Centro FastTrack examina o relatório de avaliação da migração e testa os detalhes que você fornece usando o questionário.   
- Os itens de correção sugeridos pelo Centro FastTrack devem ser concluídos por você.
    
 **Responsabilidades do cliente**
  
- Corrigir o ambiente Domino com base nas diretrizes que o Centro FastTrack fornece (por exemplo, definindo as permissões necessárias identificadas como ausentes nos arquivos de email).  
- Verificar se as caixas de correio do Domino estão abaixo do tamanho máximo permitido pela migração.
    > [!NOTE]
    >  Embora o FastTrack faça a migração de caixas de correio com até 85% do tamanho total permitido no destino, tentar migrar caixas de correio superiores a 2 GB pode apresentar riscos adicionais, como:    <br/> Duração estendida das migrações.    <br/> Uso de recursos usados para migrar outras caixas de correio.    <br/> Um aumento considerável nas taxas de erro. 
- Preparar os bancos de dados de email e as ACLs (listas de controle de acesso) deles para a migração. Você deve executar algumas etapas de correção para migrar bancos de dados do email e as permissões deles para uma caixa de correio compartilhada no Exchange Online. Algumas dessas etapas são indicadas abaixo: 
  - Remova as entradas de banco de dados no email existentes no diretório do Domino e crie novos registros de Pessoa.
  - Criar grupos de segurança universal habilitados para email no Active Directory local que são sincronizados com o Office 365 Azure Active Directory e usados para configurar permissões na caixa de correio compartilhada no Exchange Online. Isso transfere as permissões definidas no banco de dados de email para a caixa de correio compartilhada no Exchange Online.
    
> [!NOTE]
> A preparação do usuário final e o treinamento sobre o novo sistema e cliente de mensagens podem ser iniciados agora. 
  
## <a name="enable-phase"></a>Fase Habilitar

 **Ações essenciais**
  
- O Centro FastTrack: 
    - Configura o ambiente de migração no Azure.  
    - Configura as ferramentas de migração em estações de trabalho do administrador local. 
    - Configura e demonstra como usar a ferramenta de importação automática.  
    - Conduz a validação de todos os componentes de migração e realiza migração de teste.
    
 **Responsabilidades do cliente**
  
- A equipe responsável pelo agendamento da migração de caixa de correio precisa saber como usar a ferramenta de importação automática. Use essa ferramenta para importar o cronograma de migração para o banco de dados de agendamento, que o Centro FastTrack utiliza para realizar atividades de pré-migração. 
- Realizar atividades anteriores à migração, como importar cronogramas de usuário, analisar relatórios de auditoria, corrigir problemas e reimportar contas de usuário com problemas.
    
As atividades anteriores à migração são coordenadas entre você e o Centro FastTrack. A replicação no Azure começa depois que o cronograma de migração do usuário é importado. 
    
> [!NOTE]
> O tempo necessário para replicar depende da quantidade de dados. O Centro FastTrack executa a auditoria para determinar a preparação da migração. Os resultados de auditoria são fornecidos a você com o entendimento de que a correção subsequente normalmente é obrigatória. Todas essas etapas são chamadas de atividades "T-menos" porque elas devem começar antes da migração agendada dos usuários. 
  
## <a name="migrate-phase"></a>Fase Migrar

 **Ações essenciais**
  
- O Centro FastTrack:
    - Executa as migrações piloto e de velocidade.  
    - Executa os eventos de migração e as atividades T-menos.
    - Fornece assistência pós-migração.
    
 **Responsabilidades do cliente**
  
- Identificar e importar as agendas de migração 21 dias antes da migração.
    > [!NOTE]
    > Essa tarefa será crítica porque as atividades pré-migração envolvem correções e possíveis novas tentativas de criação de réplicas em diferentes estágios antes do dia real de migração (T-0). Enquanto estiver migrando algumas caixas de correio, as atividades T-menos estarão sendo executadas em outras. Isso torna obrigatório fazer um planejamento e uma coordenação adequados. 
- Corrija os problemas identificados durante as atividades T-menos.
- Trate e corrija problemas do servidor Domino que afetam as atividades de migração. 
- Faça as comunicações ao usuário final sobre a data de migração futura.
- Realize atividades de preparação de usuário final e treinamento sobre o novo sistema e cliente de mensagens.   
- Identifique e relate problemas pós-migração. O Centro FastTrack dá assistência pós-migração até T+5 dias após a migração; decorrido esse tempo, ele se torna sua responsabilidade. Você pode registrar bilhetes pós-migração para problemas como emails, itens de calendário e contatos ausentes, ou duplicados na caixa de correio.
    
O Centro FastTrack não cobre a implantação, as taxas de licença ou a assistência relacionada à preparação de diretório (incluindo a sincronização de diretórios Domino para Active Directory), complementos de software de coexistência para a interoperabilidade do aplicativo Notes, migração de autoatendimento ou migração de arquivos mortos.
  

  


---
title: 'Apêndice A: Migração do IBM Domino para o Exchange Online'
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 03/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'A migração do IBM Domino para o Exchange Online inclui vários aspectos importantes, como o que acontece durante as fases abaixo:'
ms.openlocfilehash: 2b8bad92665f92abaa718b78151ad49b3920bac3
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/01/2019
ms.locfileid: "30355231"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="b7888-103">Apêndice A: Migração do IBM Domino para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="b7888-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="b7888-104">A migração do IBM Domino para o Exchange Online inclui vários aspectos importantes, como o que acontece durante as fases abaixo:</span><span class="sxs-lookup"><span data-stu-id="b7888-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="b7888-105">Fase Iniciar</span><span class="sxs-lookup"><span data-stu-id="b7888-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="b7888-106">Fase Avaliar</span><span class="sxs-lookup"><span data-stu-id="b7888-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="b7888-107">Fase Corrigir</span><span class="sxs-lookup"><span data-stu-id="b7888-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="b7888-108">Fase Habilitar</span><span class="sxs-lookup"><span data-stu-id="b7888-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="b7888-109">Fase Migrar</span><span class="sxs-lookup"><span data-stu-id="b7888-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="b7888-110">Identidades</span><span class="sxs-lookup"><span data-stu-id="b7888-110">Identities</span></span>

<span data-ttu-id="b7888-111">Você é responsável por criar e gerenciar as identidades (somente nuvem, sincronizadas ou federadas com o Active Directory local).</span><span class="sxs-lookup"><span data-stu-id="b7888-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises ActiveDirectory_2nd).</span></span> <span data-ttu-id="b7888-112">Você deve concluir o mapeamento de identidades (se ainda não estiverem presentes) entre o Domino e o Active Directory local ou Azure Active Directory durante os estágios iniciais de integração.</span><span class="sxs-lookup"><span data-stu-id="b7888-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises ActiveDirectory_2nd or WindowsAzureAD_2nd during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="b7888-113">Coexistência</span><span class="sxs-lookup"><span data-stu-id="b7888-113">Coexistence</span></span>

<span data-ttu-id="b7888-114">Os Benefícios do Centro FastTrack para Office 365 fornecem fluxo de emails bidirecionais entre o ambiente Domino do local e o Exchange Online de todos os clientes.</span><span class="sxs-lookup"><span data-stu-id="b7888-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="b7888-115">Migração</span><span class="sxs-lookup"><span data-stu-id="b7888-115">Migration</span></span>

<span data-ttu-id="b7888-p102">O processo padrão do Centro FastTrack para a migração do Domino para o Exchange Online envolve o pré-teste de dados do Domino para o Azure, antes da migração para as caixas de correio do Exchange Online. As migrações do FastTrack exigem que você e o pessoal do Centro FastTrack realizem atividades em diferentes estágios da integração. Abordaremos essas atividades nas seções a seguir.</span><span class="sxs-lookup"><span data-stu-id="b7888-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="b7888-p103">Os dados migrados por meio dos serviços do FastTrack podem ser transferidos para os EUA ou para qualquer lugar em que a Microsoft mantenha instalações. Também podem ser armazenados e processados nesses locais. Os serviços do FastTrack não são projetados para dados sujeitos a requisitos legais ou regulamentares especiais ou se destinam a eles.</span><span class="sxs-lookup"><span data-stu-id="b7888-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="b7888-121">Fase Iniciar</span><span class="sxs-lookup"><span data-stu-id="b7888-121">Initiate phase</span></span>

 <span data-ttu-id="b7888-122">**Ações essenciais**</span><span class="sxs-lookup"><span data-stu-id="b7888-122">**Key actions**</span></span>
  
- <span data-ttu-id="b7888-123">Identificar o Domino como plataforma de correio de origem.</span><span class="sxs-lookup"><span data-stu-id="b7888-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="b7888-124">Determinar se o Centro FastTrack deve realizar a migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="b7888-125">**Responsabilidades do cliente**</span><span class="sxs-lookup"><span data-stu-id="b7888-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="b7888-126">Fornecer informações básicas sobre a plataforma de mensagens de origem e confirmar a intenção de migrar com o Centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="b7888-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="b7888-127">Participar de um passo a passo sobre os processos do Benefícios do Centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="b7888-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="b7888-128">Assinar o Contrato de Serviços FastTrack.</span><span class="sxs-lookup"><span data-stu-id="b7888-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="b7888-129">Fase Avaliar</span><span class="sxs-lookup"><span data-stu-id="b7888-129">Assess phase</span></span>

 <span data-ttu-id="b7888-130">**Ações essenciais**</span><span class="sxs-lookup"><span data-stu-id="b7888-130">**Key actions**</span></span>
  
- <span data-ttu-id="b7888-131">O Centro FastTrack realiza um workshop de migração com o cliente.</span><span class="sxs-lookup"><span data-stu-id="b7888-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="b7888-132">Você conclui os pré-requisitos de migração, como o questionário de migração e o provisionamento de estações de trabalho do administrador.</span><span class="sxs-lookup"><span data-stu-id="b7888-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="b7888-133">A avaliação de migração para o Domino é executada em seu ambiente local.</span><span class="sxs-lookup"><span data-stu-id="b7888-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="b7888-134">**Responsabilidades do cliente**</span><span class="sxs-lookup"><span data-stu-id="b7888-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="b7888-135">Provisionar estações de trabalho do administrador que o Centro FastTrack usa para administrar tarefas de integração e migração, como avaliação, criação de réplica, auditoria, configuração de encaminhamento durante a migração e assim por diante.</span><span class="sxs-lookup"><span data-stu-id="b7888-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="b7888-p104">A avaliação é essencial para o planejamento e a execução bem-sucedida de migrações de velocidade. Ela é realizada por uma arquitetura de migração que precisa de acesso específico ao ambiente Domino. Os componentes de estação de trabalho do administrador obrigatórios incluem um cliente Notes configurado para acessar todos os servidores de email Domino de origem e o servidor de teste de réplica do Domino do Azure.</span><span class="sxs-lookup"><span data-stu-id="b7888-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="b7888-p105">Fornecer à equipe de migração acesso remoto a estações de trabalho do administrador, contas e permissões para realizar atividades de avaliação e migração. Isso inclui o provisionamento de várias contas locais e no Exchange Online, com a necessidade de permissões administrativas para a migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="b7888-p106">Abrir as portas do firewall. As portas de saída devem estar abertas entre os servidores de email Domino de origem e o servidor de preparo do Azure. Outras portas para comunicação (como estações de trabalho de administração, servidores Domino de origem e servidores Exchange locais, se houver), também devem estar abertas.</span><span class="sxs-lookup"><span data-stu-id="b7888-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="b7888-p107">Habilitar a certificação cruzada entre o ambiente de origem do Domino e o servidor de teste do Domino do Azure para facilitar a replicação. As tarefas de certificação cruzada são coordenadas entre o administrador do Domino do cliente e o Centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="b7888-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="b7888-146">Preencha o questionário de migração, que captura as informações necessárias para configurar o ambiente de migração no Azure (como ferramentas, scripts e servidores de migração).</span><span class="sxs-lookup"><span data-stu-id="b7888-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="b7888-147">Verifique se as caixas de correio de destino no Office 365 têm o procolo Interface do Programa de Aplicativo de Mensagens (MAPI) habilitado.</span><span class="sxs-lookup"><span data-stu-id="b7888-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="b7888-p108">Alguns planos do Office 365 não oferecem suporte para o protocolo MAPI. Para migrar dados, caixas de correio desses planos precisam ser convertidas em um plano compatível com MAPI antes do evento de migração. Após a migração, esses planos podem ser alterados novamente.</span><span class="sxs-lookup"><span data-stu-id="b7888-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="b7888-151">Fase Corrigir</span><span class="sxs-lookup"><span data-stu-id="b7888-151">Remediate phase</span></span>

 <span data-ttu-id="b7888-152">**Ações essenciais**</span><span class="sxs-lookup"><span data-stu-id="b7888-152">**Key actions**</span></span>
  
- <span data-ttu-id="b7888-153">O Centro FastTrack examina o relatório de avaliação da migração e testa os detalhes que você fornece usando o questionário.</span><span class="sxs-lookup"><span data-stu-id="b7888-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="b7888-154">Os itens de correção sugeridos pelo Centro FastTrack devem ser concluídos por você.</span><span class="sxs-lookup"><span data-stu-id="b7888-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="b7888-155">**Responsabilidades do cliente**</span><span class="sxs-lookup"><span data-stu-id="b7888-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="b7888-156">Corrigir o ambiente Domino com base nas diretrizes que o Centro FastTrack fornece (por exemplo, definindo as permissões necessárias identificadas como ausentes nos arquivos de email).</span><span class="sxs-lookup"><span data-stu-id="b7888-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="b7888-157">Verificar se as caixas de correio do Domino estão abaixo do tamanho máximo permitido pela migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="b7888-158">Embora o FastTrack faça a migração de caixas de correio com até 85% do tamanho total permitido no destino, tentar migrar caixas de correio superiores a 2 GB pode apresentar riscos adicionais, como:</span><span class="sxs-lookup"><span data-stu-id="b7888-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="b7888-p109">Duração estendida das migrações.    </span><span class="sxs-lookup"><span data-stu-id="b7888-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="b7888-p110">Uso de recursos usados para migrar outras caixas de correio.    </span><span class="sxs-lookup"><span data-stu-id="b7888-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="b7888-161">Um aumento considerável nas taxas de erro.</span><span class="sxs-lookup"><span data-stu-id="b7888-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="b7888-p111">Preparar os bancos de dados de email e as ACLs (listas de controle de acesso) deles para a migração. Você deve executar algumas etapas de correção para migrar bancos de dados do email e as permissões deles para uma caixa de correio compartilhada no Exchange Online. Algumas dessas etapas são indicadas abaixo:</span><span class="sxs-lookup"><span data-stu-id="b7888-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="b7888-165">Remova as entradas de banco de dados no email existentes no diretório do Domino e crie novos registros de Pessoa.</span><span class="sxs-lookup"><span data-stu-id="b7888-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="b7888-166">Criar grupos de segurança universal habilitados para email no Active Directory local que são sincronizados com o Office 365 Azure Active Directory e usados para configurar permissões na caixa de correio compartilhada no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b7888-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure AD and used to configure permissions on the shared mailbox in Exchange Online. This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="b7888-167">Isso transfere as permissões definidas no banco de dados de email para a caixa de correio compartilhada no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b7888-167">This transfers the permissions set on the mail-in database over to the shared mailbox in MO_ExchangeOnline_2nd.</span></span>
    
> [!NOTE]
> <span data-ttu-id="b7888-168">A preparação do usuário final e o treinamento sobre o novo sistema e cliente de mensagens podem ser iniciados agora.</span><span class="sxs-lookup"><span data-stu-id="b7888-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="b7888-169">Fase Habilitar</span><span class="sxs-lookup"><span data-stu-id="b7888-169">Enable phase</span></span>

 <span data-ttu-id="b7888-170">**Ações essenciais**</span><span class="sxs-lookup"><span data-stu-id="b7888-170">**Key actions**</span></span>
  
- <span data-ttu-id="b7888-171">O Centro FastTrack:</span><span class="sxs-lookup"><span data-stu-id="b7888-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="b7888-172">Configura o ambiente de migração no Azure.</span><span class="sxs-lookup"><span data-stu-id="b7888-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="b7888-173">Configura as ferramentas de migração em estações de trabalho do administrador local.</span><span class="sxs-lookup"><span data-stu-id="b7888-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="b7888-174">Configura e demonstra como usar a ferramenta de importação automática.</span><span class="sxs-lookup"><span data-stu-id="b7888-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="b7888-175">Conduz a validação de todos os componentes de migração e realiza migração de teste.</span><span class="sxs-lookup"><span data-stu-id="b7888-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="b7888-176">**Responsabilidades do cliente**</span><span class="sxs-lookup"><span data-stu-id="b7888-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="b7888-p113">A equipe responsável pelo agendamento da migração de caixa de correio precisa saber como usar a ferramenta de importação automática. Use essa ferramenta para importar o cronograma de migração para o banco de dados de agendamento, que o Centro FastTrack utiliza para realizar atividades de pré-migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="b7888-179">Realizar atividades anteriores à migração, como importar cronogramas de usuário, analisar relatórios de auditoria, corrigir problemas e reimportar contas de usuário com problemas.</span><span class="sxs-lookup"><span data-stu-id="b7888-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="b7888-p114">As atividades anteriores à migração são coordenadas entre você e o Centro FastTrack. A replicação no Azure começa depois que o cronograma de migração do usuário é importado.</span><span class="sxs-lookup"><span data-stu-id="b7888-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="b7888-p115">O tempo necessário para replicar depende da quantidade de dados. O Centro FastTrack executa a auditoria para determinar a preparação da migração. Os resultados de auditoria são fornecidos a você com o entendimento de que a correção subsequente normalmente é obrigatória. Todas essas etapas são chamadas de atividades "T-menos" porque elas devem começar antes da migração agendada dos usuários.</span><span class="sxs-lookup"><span data-stu-id="b7888-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="b7888-186">Fase Migrar</span><span class="sxs-lookup"><span data-stu-id="b7888-186">Migrate phase</span></span>

 <span data-ttu-id="b7888-187">**Ações essenciais**</span><span class="sxs-lookup"><span data-stu-id="b7888-187">**Key actions**</span></span>
  
- <span data-ttu-id="b7888-188">O Centro FastTrack:</span><span class="sxs-lookup"><span data-stu-id="b7888-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="b7888-189">Executa as migrações piloto e de velocidade.</span><span class="sxs-lookup"><span data-stu-id="b7888-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="b7888-190">Executa os eventos de migração e as atividades T-menos.</span><span class="sxs-lookup"><span data-stu-id="b7888-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="b7888-191">Fornece assistência pós-migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="b7888-192">**Responsabilidades do cliente**</span><span class="sxs-lookup"><span data-stu-id="b7888-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="b7888-193">Identificar e importar as agendas de migração 21 dias antes da migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="b7888-p116">Essa tarefa será crítica porque as atividades pré-migração envolvem correções e possíveis novas tentativas de criação de réplicas em diferentes estágios antes do dia real de migração (T-0). Enquanto estiver migrando algumas caixas de correio, as atividades T-menos estarão sendo executadas em outras. Isso torna obrigatório fazer um planejamento e uma coordenação adequados.</span><span class="sxs-lookup"><span data-stu-id="b7888-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="b7888-197">Corrija os problemas identificados durante as atividades T-menos.</span><span class="sxs-lookup"><span data-stu-id="b7888-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="b7888-198">Trate e corrija problemas do servidor Domino que afetam as atividades de migração.</span><span class="sxs-lookup"><span data-stu-id="b7888-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="b7888-199">Faça as comunicações ao usuário final sobre a data de migração futura.</span><span class="sxs-lookup"><span data-stu-id="b7888-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="b7888-200">Realize atividades de preparação de usuário final e treinamento sobre o novo sistema e cliente de mensagens.</span><span class="sxs-lookup"><span data-stu-id="b7888-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="b7888-p117">Identifique e relate problemas pós-migração. O Centro FastTrack dá assistência pós-migração até T+5 dias após a migração; decorrido esse tempo, ele se torna sua responsabilidade. Você pode registrar bilhetes pós-migração para problemas como emails, itens de calendário e contatos ausentes, ou duplicados na caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="b7888-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="b7888-204">O Centro FastTrack não cobre a implantação, as taxas de licença ou a assistência relacionada à preparação de diretório (incluindo a sincronização de diretórios Domino para Active Directory), complementos de software de coexistência para a interoperabilidade do aplicativo Notes, migração de autoatendimento ou migração de arquivos mortos.</span><span class="sxs-lookup"><span data-stu-id="b7888-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  


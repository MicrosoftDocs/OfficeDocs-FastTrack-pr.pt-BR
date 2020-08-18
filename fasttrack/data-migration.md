---
title: Migração de dados
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776548"
---
# <a name="data-migration"></a><span data-ttu-id="b1b68-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="b1b68-104">Data Migration</span></span>

<span data-ttu-id="b1b68-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="b1b68-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="b1b68-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="b1b68-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="b1b68-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="b1b68-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="b1b68-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="b1b68-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="b1b68-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="b1b68-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-111">You create and schedule your migration events.</span></span> <span data-ttu-id="b1b68-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b1b68-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="b1b68-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="b1b68-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="b1b68-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="b1b68-115">Considerations</span></span>

  - <span data-ttu-id="b1b68-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="b1b68-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="b1b68-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b1b68-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="b1b68-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="b1b68-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="b1b68-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="b1b68-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="b1b68-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="b1b68-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="b1b68-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="b1b68-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="b1b68-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="b1b68-124">Migration service availability</span></span>

  - <span data-ttu-id="b1b68-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="b1b68-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="b1b68-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="b1b68-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="b1b68-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="b1b68-127">Migration to Exchange Online</span></span>

<span data-ttu-id="b1b68-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b1b68-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="b1b68-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="b1b68-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-130">You create and schedule your migration events.</span></span> <span data-ttu-id="b1b68-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b1b68-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b1b68-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b1b68-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="b1b68-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="b1b68-133">Considerations</span></span>

  - <span data-ttu-id="b1b68-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="b1b68-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="b1b68-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="b1b68-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b1b68-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="b1b68-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="b1b68-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="b1b68-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b1b68-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="b1b68-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="b1b68-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="b1b68-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="b1b68-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="b1b68-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="b1b68-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="b1b68-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="b1b68-143">Source environments</span></span>

<span data-ttu-id="b1b68-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="b1b68-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="b1b68-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="b1b68-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="b1b68-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="b1b68-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="b1b68-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="b1b68-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b1b68-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b1b68-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b1b68-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="b1b68-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b1b68-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="b1b68-154">
<strong>Observação:</strong>  Para dependências do Exchange local, confira  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Pré-requisitos de implantação híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="b1b68-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="b1b68-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="b1b68-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="b1b68-156">Emails</span><span class="sxs-lookup"><span data-stu-id="b1b68-156">Emails</span></span></li>
<li><span data-ttu-id="b1b68-157">Regras de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="b1b68-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="b1b68-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="b1b68-158">Delegates</span></span></li>
<li><span data-ttu-id="b1b68-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="b1b68-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b1b68-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="b1b68-160">Calendar</span></span> </li>
<li> <span data-ttu-id="b1b68-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b1b68-161">Tasks</span></span> </li>
<li> <span data-ttu-id="b1b68-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="b1b68-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="b1b68-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="b1b68-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="b1b68-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b1b68-164">Signatures</span></span> </li>
<li> <span data-ttu-id="b1b68-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="b1b68-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="b1b68-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="b1b68-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="b1b68-167">Public folders</span></span> </li>
<li> <span data-ttu-id="b1b68-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b1b68-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b1b68-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="b1b68-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="b1b68-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="b1b68-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="b1b68-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b1b68-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b1b68-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b1b68-174"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="b1b68-175">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Executar uma migração G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="b1b68-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="b1b68-176">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="b1b68-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-177">Emails</span><span class="sxs-lookup"><span data-stu-id="b1b68-177">Emails</span></span> </li>
<li> <span data-ttu-id="b1b68-178">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="b1b68-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="b1b68-179">Calendário</span><span class="sxs-lookup"><span data-stu-id="b1b68-179">Calendar</span></span> </li>
<li> <span data-ttu-id="b1b68-180">Rótulos</span><span class="sxs-lookup"><span data-stu-id="b1b68-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-181">Regras</span><span class="sxs-lookup"><span data-stu-id="b1b68-181">Rules</span></span> </li>
<li> <span data-ttu-id="b1b68-182">Representantes</span><span class="sxs-lookup"><span data-stu-id="b1b68-182">Delegates</span></span> </li>
<li> <span data-ttu-id="b1b68-183">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b1b68-183">Signatures</span></span> </li>
<li> <span data-ttu-id="b1b68-184">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b1b68-184">Tasks</span></span> </li>
<li> <span data-ttu-id="b1b68-185">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b1b68-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b1b68-186">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-187">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="b1b68-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="b1b68-188">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="b1b68-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="b1b68-189">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b1b68-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="b1b68-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="b1b68-191">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="b1b68-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="b1b68-192">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="b1b68-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="b1b68-193">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b1b68-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="b1b68-194">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="b1b68-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="b1b68-195">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="b1b68-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="b1b68-196">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b1b68-197"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="b1b68-198">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="b1b68-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="b1b68-199">Emails</span><span class="sxs-lookup"><span data-stu-id="b1b68-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="b1b68-200">Regras</span><span class="sxs-lookup"><span data-stu-id="b1b68-200">Rules</span></span> </li>
<li> <span data-ttu-id="b1b68-201">Representantes</span><span class="sxs-lookup"><span data-stu-id="b1b68-201">Delegates</span></span> </li>
<li> <span data-ttu-id="b1b68-202">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="b1b68-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="b1b68-203">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="b1b68-203">External contacts</span></span> </li>
<li> <span data-ttu-id="b1b68-204">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="b1b68-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="b1b68-205">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-206">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="b1b68-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b1b68-207">Calendário</span><span class="sxs-lookup"><span data-stu-id="b1b68-207">Calendar</span></span> </li>
<li> <span data-ttu-id="b1b68-208">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b1b68-208">Signatures</span></span> </li>
<li> <span data-ttu-id="b1b68-209">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b1b68-209">Tasks</span></span> </li>
<li> <span data-ttu-id="b1b68-210">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b1b68-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b1b68-211">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="b1b68-211">Archive data</span></span> </li>
<li> <span data-ttu-id="b1b68-212">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="b1b68-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="b1b68-213">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b1b68-214">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b1b68-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b1b68-215">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b1b68-215">FastTrack responsibilities</span></span>

<span data-ttu-id="b1b68-216">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-217">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b1b68-218">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="b1b68-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="b1b68-219">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b1b68-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b1b68-220">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b1b68-220">Your responsibilities</span></span>

<span data-ttu-id="b1b68-221">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-222">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b1b68-223">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="b1b68-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="b1b68-224">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b1b68-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="b1b68-225">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="b1b68-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b1b68-226">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="b1b68-227">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="b1b68-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="b1b68-228">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="b1b68-229">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="b1b68-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b1b68-230">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="b1b68-231">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b1b68-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="b1b68-232">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b1b68-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="b1b68-233">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="b1b68-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="b1b68-234">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="b1b68-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="b1b68-235">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="b1b68-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="b1b68-236">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="b1b68-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="b1b68-237">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="b1b68-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="b1b68-238">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="b1b68-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="b1b68-239">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b1b68-240">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b1b68-241">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-241">You create and schedule your migration events.</span></span> <span data-ttu-id="b1b68-242">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b1b68-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b1b68-243">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b1b68-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="b1b68-244">Considerações</span><span class="sxs-lookup"><span data-stu-id="b1b68-244">Considerations</span></span>

  - <span data-ttu-id="b1b68-245">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b1b68-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="b1b68-246">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="b1b68-247">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="b1b68-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b1b68-248">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="b1b68-248">Source environment details</span></span>

<span data-ttu-id="b1b68-249">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b1b68-250">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="b1b68-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b1b68-251">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b1b68-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b1b68-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="b1b68-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b1b68-253">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="b1b68-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b1b68-254">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b1b68-255"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b1b68-256"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b1b68-257"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b1b68-258"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b1b68-259"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b1b68-260">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-261">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-262">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-263">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b1b68-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b1b68-264">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="b1b68-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b1b68-265">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-266">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-267">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-267">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-268">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-268">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-269">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-269">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-270">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="b1b68-271">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="b1b68-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b1b68-272">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b1b68-273">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b1b68-274">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-275">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b1b68-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b1b68-276">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-277">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b1b68-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="b1b68-278">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="b1b68-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b1b68-279">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="b1b68-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b1b68-280">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="b1b68-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b1b68-281">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="b1b68-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b1b68-282">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="b1b68-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b1b68-283">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-284">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="b1b68-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b1b68-285">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="b1b68-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b1b68-286">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b1b68-287"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b1b68-288">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-289">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="b1b68-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="b1b68-290">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-291">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-292">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-293">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-294">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-295">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-295">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-296">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-296">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-297">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-297">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-298">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-299">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="b1b68-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b1b68-300">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-301">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-302">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b1b68-303">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-304">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-305">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-306">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-307">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-308">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-309">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-310">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-311">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="b1b68-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b1b68-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="b1b68-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b1b68-313">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="b1b68-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b1b68-314">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="b1b68-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b1b68-315">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-316">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-317">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="b1b68-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b1b68-318">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-319">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b1b68-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b1b68-321">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-322">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-322">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-323">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-324">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-325">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-326">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-327">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-328">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-328">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-329">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-329">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-330">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-330">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-331">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-332">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b1b68-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-333">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-334">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b1b68-335">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-336">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-337">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-338">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-339">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-340">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-341">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-342">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-343">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="b1b68-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b1b68-344">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b1b68-345">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-346">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-347">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b1b68-348"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="b1b68-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b1b68-349">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-350">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-350">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-351">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-352">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-353">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-354">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-355">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-356">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-356">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-357">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-357">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-358">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-358">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-359">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-360">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="b1b68-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b1b68-361">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b1b68-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-362">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-363">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b1b68-364">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-365">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-366">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-367">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-368">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-369">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-370">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-371">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="b1b68-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b1b68-372">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="b1b68-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b1b68-373">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="b1b68-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b1b68-374">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b1b68-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b1b68-375">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b1b68-376">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-377">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="b1b68-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="b1b68-378">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b1b68-379">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b1b68-379">FastTrack responsibilities</span></span>

<span data-ttu-id="b1b68-380">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-381">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="b1b68-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b1b68-382">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b1b68-382">Your responsibilities</span></span>

<span data-ttu-id="b1b68-383">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-384">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="b1b68-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="b1b68-385">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="b1b68-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="b1b68-386">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="b1b68-387">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="b1b68-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="b1b68-388">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b1b68-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b1b68-389">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b1b68-390">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-390">You create and schedule your migration events.</span></span> <span data-ttu-id="b1b68-391">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b1b68-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b1b68-392">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b1b68-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="b1b68-393">Considerações</span><span class="sxs-lookup"><span data-stu-id="b1b68-393">Considerations</span></span>

  - <span data-ttu-id="b1b68-394">Todas as migrações estão sujeitas a cotas do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b1b68-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="b1b68-395">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="b1b68-396">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="b1b68-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="b1b68-397">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b1b68-398">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="b1b68-398">Source environment details</span></span>

<span data-ttu-id="b1b68-399">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b1b68-400">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="b1b68-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b1b68-401">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b1b68-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b1b68-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="b1b68-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b1b68-403">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="b1b68-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b1b68-404">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b1b68-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="b1b68-405"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="b1b68-406"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="b1b68-407"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b1b68-408"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b1b68-409"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b1b68-410">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-411">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-411">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-412">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-413">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b1b68-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b1b68-414">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="b1b68-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b1b68-415">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-416">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-417">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-417">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-418">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-418">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-419">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-419">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-420">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="b1b68-421">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="b1b68-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b1b68-422">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b1b68-423">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b1b68-424">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="b1b68-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="b1b68-425">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b1b68-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b1b68-426">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-427">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b1b68-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="b1b68-428">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="b1b68-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b1b68-429">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="b1b68-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b1b68-430">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="b1b68-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b1b68-431">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="b1b68-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b1b68-432">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="b1b68-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b1b68-433">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-434">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="b1b68-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b1b68-435">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="b1b68-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b1b68-436">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b1b68-437"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b1b68-438">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-439">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="b1b68-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="b1b68-440">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-441">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-442">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-443">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-444">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-445">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-445">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-446">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-446">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-447">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-447">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-448">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-449">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="b1b68-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b1b68-450">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-451">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-452">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b1b68-453">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-454">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-455">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-456">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-457">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-458">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-459">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-460">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-461">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="b1b68-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b1b68-462">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="b1b68-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b1b68-463">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="b1b68-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b1b68-464">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="b1b68-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b1b68-465">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-466">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-467">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="b1b68-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b1b68-468">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-469">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b1b68-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="b1b68-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b1b68-471">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-472">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-472">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-473">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-474">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-475">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-476">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-477">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-478">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-478">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-479">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-479">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-480">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-480">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-481">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-482">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b1b68-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-483">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-484">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b1b68-485">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-486">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-487">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-488">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-489">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-490">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-491">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-492">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b1b68-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b1b68-493">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="b1b68-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b1b68-494">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b1b68-495">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-496">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-497">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b1b68-498"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="b1b68-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b1b68-499">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b1b68-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b1b68-500">Documentos</span><span class="sxs-lookup"><span data-stu-id="b1b68-500">Documents</span></span> </li>
<li> <span data-ttu-id="b1b68-501">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b1b68-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b1b68-502">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-503">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-504">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b1b68-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b1b68-505">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b1b68-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b1b68-506">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b1b68-506">Created date</span></span> </li>
<li> <span data-ttu-id="b1b68-507">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b1b68-507">Modified date</span></span> </li>
<li> <span data-ttu-id="b1b68-508">Criado por</span><span class="sxs-lookup"><span data-stu-id="b1b68-508">Created by</span></span> </li>
<li> <span data-ttu-id="b1b68-509">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b1b68-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b1b68-510">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="b1b68-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b1b68-511">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b1b68-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b1b68-512">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b1b68-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b1b68-513">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b1b68-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b1b68-514">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b1b68-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-515">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b1b68-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b1b68-516">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b1b68-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b1b68-517">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b1b68-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b1b68-518">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b1b68-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b1b68-519">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b1b68-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="b1b68-520">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b1b68-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b1b68-521">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="b1b68-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b1b68-522">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="b1b68-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b1b68-523">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="b1b68-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b1b68-524">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b1b68-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b1b68-525">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="b1b68-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b1b68-526">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b1b68-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b1b68-527">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b1b68-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b1b68-528">Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b1b68-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b1b68-529">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b1b68-529">FastTrack responsibilities</span></span>

<span data-ttu-id="b1b68-530">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-531">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b1b68-532">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b1b68-532">Your responsibilities</span></span>

<span data-ttu-id="b1b68-533">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b1b68-534">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b1b68-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b1b68-535">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="b1b68-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="b1b68-536">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b1b68-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

---
title: Migração de dados
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: 0e33e8a79ebc577188644dbc69cd78707a575838
ms.sourcegitcommit: 69a30fee5e7e199bd6830fb0837af1ae4904ef3b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/11/2021
ms.locfileid: "52312439"
---
# <a name="data-migration"></a><span data-ttu-id="271d6-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="271d6-104">Data Migration</span></span>

<span data-ttu-id="271d6-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="271d6-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="271d6-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="271d6-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="271d6-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="271d6-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="271d6-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="271d6-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="271d6-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="271d6-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-111">You create and schedule your migration events.</span></span> <span data-ttu-id="271d6-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="271d6-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="271d6-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="271d6-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="271d6-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="271d6-115">Considerations</span></span>

  - <span data-ttu-id="271d6-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="271d6-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="271d6-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="271d6-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="271d6-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="271d6-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="271d6-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="271d6-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="271d6-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="271d6-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="271d6-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="271d6-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="271d6-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="271d6-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="271d6-124">Migration service availability</span></span>

  - <span data-ttu-id="271d6-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="271d6-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="271d6-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="271d6-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="271d6-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="271d6-127">Migration to Exchange Online</span></span>

<span data-ttu-id="271d6-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="271d6-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="271d6-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="271d6-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-130">You create and schedule your migration events.</span></span> <span data-ttu-id="271d6-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="271d6-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="271d6-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="271d6-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="271d6-133">Considerations</span></span>

  - <span data-ttu-id="271d6-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="271d6-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="271d6-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="271d6-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="271d6-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="271d6-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="271d6-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="271d6-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="271d6-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="271d6-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="271d6-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="271d6-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="271d6-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="271d6-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="271d6-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="271d6-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="271d6-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="271d6-143">Source environments</span></span>

<span data-ttu-id="271d6-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="271d6-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="271d6-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="271d6-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="271d6-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="271d6-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="271d6-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="271d6-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="271d6-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="271d6-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="271d6-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="271d6-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="271d6-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="271d6-154">
<strong>Observação:</strong> Para dependências Exchange local, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Pré-requisitos de implantação híbrida.</span></a></span><span class="sxs-lookup"><span data-stu-id="271d6-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="271d6-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="271d6-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="271d6-156">Emails</span><span class="sxs-lookup"><span data-stu-id="271d6-156">Emails</span></span></li>
<li><span data-ttu-id="271d6-157">Regras de caixa de correio do lado do servidor</span><span class="sxs-lookup"><span data-stu-id="271d6-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="271d6-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="271d6-158">Delegates</span></span></li>
<li><span data-ttu-id="271d6-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="271d6-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="271d6-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="271d6-160">Calendar</span></span> </li>
<li> <span data-ttu-id="271d6-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="271d6-161">Tasks</span></span> </li>
<li> <span data-ttu-id="271d6-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="271d6-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="271d6-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="271d6-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="271d6-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="271d6-164">Signatures</span></span> </li>
<li> <span data-ttu-id="271d6-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="271d6-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="271d6-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="271d6-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="271d6-167">Public folders</span></span> </li>
<li> <span data-ttu-id="271d6-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="271d6-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="271d6-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="271d6-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="271d6-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="271d6-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="271d6-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="271d6-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="271d6-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="271d6-174">Regras de caixa de correio do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="271d6-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-175"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="271d6-176">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span><span class="sxs-lookup"><span data-stu-id="271d6-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="271d6-177">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="271d6-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-178">Emails</span><span class="sxs-lookup"><span data-stu-id="271d6-178">Emails</span></span> </li>
<li> <span data-ttu-id="271d6-179">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="271d6-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="271d6-180">Calendário</span><span class="sxs-lookup"><span data-stu-id="271d6-180">Calendar</span></span> </li>
<li> <span data-ttu-id="271d6-181">Rótulos</span><span class="sxs-lookup"><span data-stu-id="271d6-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-182">Regras</span><span class="sxs-lookup"><span data-stu-id="271d6-182">Rules</span></span> </li>
<li> <span data-ttu-id="271d6-183">Representantes</span><span class="sxs-lookup"><span data-stu-id="271d6-183">Delegates</span></span> </li>
<li> <span data-ttu-id="271d6-184">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="271d6-184">Signatures</span></span> </li>
<li> <span data-ttu-id="271d6-185">Tarefas</span><span class="sxs-lookup"><span data-stu-id="271d6-185">Tasks</span></span> </li>
<li> <span data-ttu-id="271d6-186">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="271d6-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="271d6-187">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-188">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="271d6-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="271d6-189">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="271d6-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="271d6-190">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="271d6-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="271d6-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="271d6-192">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="271d6-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="271d6-193">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="271d6-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="271d6-194">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="271d6-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="271d6-195">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="271d6-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="271d6-196">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="271d6-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="271d6-197">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="271d6-198"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="271d6-199">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="271d6-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="271d6-200">Emails</span><span class="sxs-lookup"><span data-stu-id="271d6-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="271d6-201">Regras</span><span class="sxs-lookup"><span data-stu-id="271d6-201">Rules</span></span> </li>
<li> <span data-ttu-id="271d6-202">Representantes</span><span class="sxs-lookup"><span data-stu-id="271d6-202">Delegates</span></span> </li>
<li> <span data-ttu-id="271d6-203">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="271d6-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="271d6-204">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="271d6-204">External contacts</span></span> </li>
<li> <span data-ttu-id="271d6-205">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="271d6-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="271d6-206">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-207">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="271d6-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="271d6-208">Calendário</span><span class="sxs-lookup"><span data-stu-id="271d6-208">Calendar</span></span> </li>
<li> <span data-ttu-id="271d6-209">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="271d6-209">Signatures</span></span> </li>
<li> <span data-ttu-id="271d6-210">Tarefas</span><span class="sxs-lookup"><span data-stu-id="271d6-210">Tasks</span></span> </li>
<li> <span data-ttu-id="271d6-211">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="271d6-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="271d6-212">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="271d6-212">Archive data</span></span> </li>
<li> <span data-ttu-id="271d6-213">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="271d6-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="271d6-214">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="271d6-215">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="271d6-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="271d6-216">Responsabilidades do FastTrack para Exchange Online migrações</span><span class="sxs-lookup"><span data-stu-id="271d6-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="271d6-217">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-218">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="271d6-219">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="271d6-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="271d6-220">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="271d6-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="271d6-221">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="271d6-221">Your responsibilities</span></span>

<span data-ttu-id="271d6-222">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-223">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="271d6-224">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="271d6-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="271d6-225">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="271d6-226">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="271d6-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="271d6-227">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="271d6-228">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="271d6-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="271d6-229">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="271d6-230">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="271d6-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="271d6-231">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="271d6-232">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="271d6-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="271d6-233">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="271d6-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="271d6-234">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="271d6-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="271d6-235">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="271d6-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="271d6-236">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="271d6-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="271d6-237">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="271d6-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="271d6-238">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="271d6-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="271d6-239">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="271d6-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="271d6-240">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="271d6-241">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="271d6-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="271d6-242">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-242">You create and schedule your migration events.</span></span> <span data-ttu-id="271d6-243">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="271d6-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="271d6-244">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="271d6-245">Considerações</span><span class="sxs-lookup"><span data-stu-id="271d6-245">Considerations</span></span>

 - <span data-ttu-id="271d6-246">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="271d6-247">Consulte SharePoint <a href="https://go.microsoft.com/fwlink/?LinkId=698855">para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="271d6-248">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="271d6-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="271d6-249">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="271d6-249">Source environment details</span></span>

<span data-ttu-id="271d6-250">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="271d6-251">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="271d6-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="271d6-252">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="271d6-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="271d6-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="271d6-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="271d6-254">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="271d6-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="271d6-255">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="271d6-256"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="271d6-257"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="271d6-258"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="271d6-259"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="271d6-260"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="271d6-261">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-262">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-262">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-263">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-264">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-265">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-266">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-267">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-268">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-268">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-269">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-269">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-270">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-270">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-271">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="271d6-272">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="271d6-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="271d6-273">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="271d6-274">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="271d6-275">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-276">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-277">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-278">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-279">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="271d6-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="271d6-280">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="271d6-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="271d6-281">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="271d6-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="271d6-282">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="271d6-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="271d6-283">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="271d6-284">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-285">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="271d6-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="271d6-286">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="271d6-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="271d6-287">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-288"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="271d6-289">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-290">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="271d6-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="271d6-291">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-292">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-293">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-294">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-295">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-296">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-296">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-297">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-297">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-298">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-298">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-299">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-300">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="271d6-301">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-302">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-303">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="271d6-304">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-305">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-306">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-307">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-308">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-309">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-310">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-311">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-312">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="271d6-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="271d6-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="271d6-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="271d6-314">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="271d6-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="271d6-315">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="271d6-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="271d6-316">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-317">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-318">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="271d6-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="271d6-319">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-320">Arquivos marcados como restritos ou não copiáveis</span><span class="sxs-lookup"><span data-stu-id="271d6-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="271d6-321">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="271d6-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="271d6-323">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-324">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-324">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-325">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-326">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-327">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-328">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-329">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-330">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-330">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-331">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-331">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-332">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-332">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-333">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-334">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="271d6-335">Notas de caixa (convertido no formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="271d6-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-336">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-337">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-338">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-339">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-340">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-341">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-342">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-343">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-344">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-345">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-346">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="271d6-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="271d6-347">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="271d6-348">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-349">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-350">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-351"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="271d6-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="271d6-352">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-353">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-353">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-354">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-355">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-356">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-357">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-358">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-359">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-359">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-360">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-360">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-361">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-361">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-362">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-363">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="271d6-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="271d6-364">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-365">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-366">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-367">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-368">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-369">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-370">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-371">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-372">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-373">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-374">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="271d6-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="271d6-375">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="271d6-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="271d6-376">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="271d6-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="271d6-377">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="271d6-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="271d6-378">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="271d6-379">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-380">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="271d6-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="271d6-381">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="271d6-382">Responsabilidades do FastTrack para migrações SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="271d6-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="271d6-383">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-384">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="271d6-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="271d6-385">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="271d6-385">Your responsibilities</span></span>

<span data-ttu-id="271d6-386">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-387">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="271d6-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="271d6-388">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="271d6-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="271d6-389">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="271d6-390">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="271d6-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="271d6-391">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="271d6-392">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="271d6-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="271d6-393">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-393">You create and schedule your migration events.</span></span> <span data-ttu-id="271d6-394">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="271d6-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="271d6-395">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="271d6-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="271d6-396">Considerações</span><span class="sxs-lookup"><span data-stu-id="271d6-396">Considerations</span></span>

  - <span data-ttu-id="271d6-397">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="271d6-398">Consulte SharePoint <a href="https://go.microsoft.com/fwlink/?LinkId=698855">para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="271d6-399">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="271d6-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="271d6-400">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="271d6-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="271d6-401">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="271d6-401">Source environment details</span></span>

<span data-ttu-id="271d6-402">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="271d6-403">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="271d6-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="271d6-404">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="271d6-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="271d6-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="271d6-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="271d6-406">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="271d6-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="271d6-407">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="271d6-408"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="271d6-409"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="271d6-410"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="271d6-411"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="271d6-412"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="271d6-413">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-414">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-414">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-415">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-416">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-417">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-418">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-419">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-420">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-420">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-421">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-421">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-422">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-422">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-423">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="271d6-424">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="271d6-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="271d6-425">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="271d6-426">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="271d6-427">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="271d6-428">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-429">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-430">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-431">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="271d6-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="271d6-432">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="271d6-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="271d6-433">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="271d6-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="271d6-434">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="271d6-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="271d6-435">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="271d6-436">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-437">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="271d6-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="271d6-438">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="271d6-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="271d6-439">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-440"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="271d6-441">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-442">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="271d6-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="271d6-443">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-444">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-445">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-446">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-447">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-448">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-448">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-449">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-449">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-450">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-450">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-451">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-452">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="271d6-453">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-454">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-455">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="271d6-456">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-457">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-458">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-459">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-460">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-461">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-462">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-463">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-464">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="271d6-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="271d6-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="271d6-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="271d6-466">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="271d6-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="271d6-467">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="271d6-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="271d6-468">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-469">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-470">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="271d6-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="271d6-471">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-472">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="271d6-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="271d6-474">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-475">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-475">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-476">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-477">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-478">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-479">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-480">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-481">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-481">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-482">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-482">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-483">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-483">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-484">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-485">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-486">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-487">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-488">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-489">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-490">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-491">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-492">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-493">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-494">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-495">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-496">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="271d6-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="271d6-497">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="271d6-498">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-499">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-500">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-501"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="271d6-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="271d6-502">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-503">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-503">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-504">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-505">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-506">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="271d6-507">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-508">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-509">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-509">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-510">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-510">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-511">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-511">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-512">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-513">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="271d6-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="271d6-514">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="271d6-515">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-516">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-517">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-518">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-519">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-520">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-521">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-522">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-523">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-524">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="271d6-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="271d6-525">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="271d6-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="271d6-526">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="271d6-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="271d6-527">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="271d6-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="271d6-528">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="271d6-529">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-530">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-531">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="271d6-532">Responsabilidades do FastTrack para OneDrive for Business migrações</span><span class="sxs-lookup"><span data-stu-id="271d6-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="271d6-533">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-534">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="271d6-535">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="271d6-535">Your responsibilities</span></span>

<span data-ttu-id="271d6-536">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-537">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="271d6-538">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="271d6-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="271d6-539">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="271d6-540">Migração para Microsoft Teams e Microsoft 365 Grupos</span><span class="sxs-lookup"><span data-stu-id="271d6-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="271d6-541">Quando você optar por usar o FastTrack para migrar seus arquivos para grupos Microsoft Teams e Microsoft 365, fornecemos orientações de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="271d6-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="271d6-542">Fornecemos orientações para ajudá-lo a planejar sua migração, configurar seus ambientes de origem e Teams e Microsoft 365 Grupos e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="271d6-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="271d6-543">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-543">You create and schedule your migration events.</span></span> <span data-ttu-id="271d6-544">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="271d6-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="271d6-545">Quando seus eventos de migração são concluídos, você pode esperar que os arquivos de fontes apropriadamente agendadas e qualificadas de seus ambientes de origem tenham sido migrados para grupos Teams e Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="271d6-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="271d6-546">Teams canais e Microsoft 365 grupos devem ser pré-provisionados pelo cliente antes que eles possam migrar dados para esses tipos de destino.</span><span class="sxs-lookup"><span data-stu-id="271d6-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="271d6-547">Teams e Microsoft 365 grupos afeta suas permissões no local de destino do arquivo.</span><span class="sxs-lookup"><span data-stu-id="271d6-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="271d6-548">Teams e Microsoft 365 grupos são construídos para permitir a colaboração.</span><span class="sxs-lookup"><span data-stu-id="271d6-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="271d6-549">O Teams ou Microsoft 365 grupo determinam quem tem acesso a esses arquivos ao migrar para esses destinos.</span><span class="sxs-lookup"><span data-stu-id="271d6-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="271d6-550">O FastTrack não adiciona usuários finais ou grupos a qualquer canal Teams ou permissão Microsoft 365 Grupos durante a migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="271d6-551">Considerações</span><span class="sxs-lookup"><span data-stu-id="271d6-551">Considerations</span></span>

- <span data-ttu-id="271d6-552">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="271d6-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="271d6-553">Consulte SharePoint <a href="https://go.microsoft.com/fwlink/?LinkId=698855">para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="271d6-554">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="271d6-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="271d6-555">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="271d6-555">Source environment details</span></span>

<span data-ttu-id="271d6-556">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="271d6-557">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="271d6-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="271d6-558">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="271d6-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="271d6-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="271d6-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="271d6-560">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="271d6-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="271d6-561">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="271d6-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="271d6-562"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="271d6-563"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="271d6-564"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="271d6-565"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="271d6-566"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="271d6-567">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-568">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-568">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-569">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-570">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-571">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-572">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-573">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-574">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-574">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-575">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-575">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-576">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-576">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-577">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="271d6-578">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="271d6-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="271d6-579">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="271d6-580">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="271d6-581">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="271d6-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="271d6-582">As permissões são impactadas pelo Microsoft 365 Grupo e/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="271d6-583">Se o destino for um Microsoft 365 grupo ou canal Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="271d6-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="271d6-584">Recomendamos não migrar permissões em arquivos migrando para um Microsoft 365 Group ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-585">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-586">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-587">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="271d6-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="271d6-588">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="271d6-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="271d6-589">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="271d6-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="271d6-590">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="271d6-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="271d6-591">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="271d6-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="271d6-592">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="271d6-593">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-594">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="271d6-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="271d6-595">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="271d6-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="271d6-596">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-597"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="271d6-598">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-599">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="271d6-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="271d6-600">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-601">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-602">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-603">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-604">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-605">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-605">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-606">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-606">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-607">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-607">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-608">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-609">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="271d6-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="271d6-610">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="271d6-611">\*As permissões são impactadas pelo Microsoft 365 Group e/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="271d6-612">Se o destino for um Microsoft 365 grupo ou canal Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="271d6-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="271d6-613">Recomendamos não migrar permissões em arquivos migrando para um Microsoft 365 Group ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="271d6-614">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-615">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="271d6-616">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-617">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-618">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-619">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-620">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-621">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-622">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-623">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-624">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="271d6-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="271d6-625">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="271d6-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="271d6-626">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="271d6-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="271d6-627">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="271d6-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="271d6-628">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-629">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-630">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="271d6-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="271d6-631">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-632">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="271d6-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="271d6-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="271d6-634">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-635">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-635">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-636">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-637">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-638">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-639">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-640">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-641">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-641">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-642">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-642">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-643">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-643">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-644">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-645">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="271d6-646">Notas de caixa (convertido no formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="271d6-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="271d6-647">\*As permissões são impactadas pelo Microsoft 365 Group e/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="271d6-648">Se o destino for um Microsoft 365 grupo ou canal Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="271d6-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="271d6-649">Recomendamos não migrar permissões em arquivos migrando para um Microsoft 365 Group ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="271d6-650">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-651">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-652">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-653">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-654">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-655">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-656">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-657">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-658">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-659">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="271d6-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="271d6-660">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="271d6-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="271d6-661">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="271d6-662">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-663">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-664">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="271d6-665"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="271d6-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="271d6-666">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="271d6-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="271d6-667">Documentos</span><span class="sxs-lookup"><span data-stu-id="271d6-667">Documents</span></span> </li>
<li> <span data-ttu-id="271d6-668">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="271d6-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="271d6-669">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="271d6-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-670">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="271d6-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="271d6-671">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="271d6-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="271d6-672">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="271d6-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="271d6-673">Data de criação</span><span class="sxs-lookup"><span data-stu-id="271d6-673">Created date</span></span> </li>
<li> <span data-ttu-id="271d6-674">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="271d6-674">Modified date</span></span> </li>
<li> <span data-ttu-id="271d6-675">Criado por</span><span class="sxs-lookup"><span data-stu-id="271d6-675">Created by</span></span> </li>
<li> <span data-ttu-id="271d6-676">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="271d6-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="271d6-677">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="271d6-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="271d6-678">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="271d6-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="271d6-679">\*As permissões são impactadas pelo Microsoft 365 Group e/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="271d6-680">Se o destino for um Microsoft 365 grupo ou canal Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="271d6-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="271d6-681">Recomendamos não migrar permissões em arquivos migrando para um Microsoft 365 Group ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="271d6-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="271d6-682">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="271d6-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="271d6-683">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="271d6-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="271d6-684">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="271d6-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-685">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="271d6-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="271d6-686">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="271d6-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="271d6-687">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="271d6-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="271d6-688">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="271d6-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="271d6-689">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="271d6-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="271d6-690">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="271d6-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="271d6-691">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="271d6-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="271d6-692">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="271d6-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="271d6-693">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="271d6-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="271d6-694">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="271d6-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="271d6-695">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="271d6-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="271d6-696">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="271d6-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="271d6-697">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="271d6-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="271d6-698">Arquivos ou pastas que excedem as restrições e limitações <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint online atuais</span></a> </span><span class="sxs-lookup"><span data-stu-id="271d6-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="271d6-699">Responsabilidades do FastTrack para migrações Microsoft Teams grupos Microsoft 365 grupos</span><span class="sxs-lookup"><span data-stu-id="271d6-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="271d6-700">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-701">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="271d6-702">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="271d6-702">Your responsibilities</span></span> 

<span data-ttu-id="271d6-703">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="271d6-704">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="271d6-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="271d6-705">Você também executa as seguintes atividades, específicas Microsoft Teams e Microsoft 365 grupos:</span><span class="sxs-lookup"><span data-stu-id="271d6-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="271d6-706">Provisione todos os Microsoft Teams e grupos Microsoft 365 como direcionados por seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="271d6-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="271d6-707">O FastTrack não pré-provisiona Microsoft Teams canais ou Microsoft 365 Grupos.</span><span class="sxs-lookup"><span data-stu-id="271d6-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="271d6-708">O FastTrack não adiciona usuários finais ou grupos a Microsoft Teams canais ou Microsoft 365 Grupos.</span><span class="sxs-lookup"><span data-stu-id="271d6-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="271d6-709">Você deve adicionar seus usuários finais ou grupos a todos os canais Microsoft Teams e grupos Microsoft 365 antes de migrar dados para esses destinos para que esses usuários finais tenham acesso a esses documentos recém-migrados</span><span class="sxs-lookup"><span data-stu-id="271d6-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>
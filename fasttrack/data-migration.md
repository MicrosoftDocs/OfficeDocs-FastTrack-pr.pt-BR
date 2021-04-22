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
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/21/2021
ms.locfileid: "51926993"
---
# <a name="data-migration"></a><span data-ttu-id="b68fa-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="b68fa-104">Data Migration</span></span>

<span data-ttu-id="b68fa-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="b68fa-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="b68fa-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="b68fa-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="b68fa-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="b68fa-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="b68fa-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="b68fa-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="b68fa-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="b68fa-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-111">You create and schedule your migration events.</span></span> <span data-ttu-id="b68fa-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b68fa-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="b68fa-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="b68fa-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="b68fa-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="b68fa-115">Considerations</span></span>

  - <span data-ttu-id="b68fa-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="b68fa-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="b68fa-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b68fa-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="b68fa-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="b68fa-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="b68fa-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="b68fa-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="b68fa-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="b68fa-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="b68fa-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="b68fa-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="b68fa-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="b68fa-124">Migration service availability</span></span>

  - <span data-ttu-id="b68fa-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="b68fa-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="b68fa-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="b68fa-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="b68fa-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="b68fa-127">Migration to Exchange Online</span></span>

<span data-ttu-id="b68fa-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b68fa-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="b68fa-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="b68fa-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-130">You create and schedule your migration events.</span></span> <span data-ttu-id="b68fa-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b68fa-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b68fa-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="b68fa-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="b68fa-133">Considerations</span></span>

  - <span data-ttu-id="b68fa-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="b68fa-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="b68fa-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="b68fa-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b68fa-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="b68fa-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="b68fa-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="b68fa-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b68fa-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="b68fa-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="b68fa-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="b68fa-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="b68fa-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="b68fa-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="b68fa-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="b68fa-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="b68fa-143">Source environments</span></span>

<span data-ttu-id="b68fa-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="b68fa-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="b68fa-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="b68fa-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="b68fa-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="b68fa-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="b68fa-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="b68fa-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b68fa-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b68fa-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b68fa-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="b68fa-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b68fa-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="b68fa-154">
<strong>Observação:</strong> Para dependências locais do Exchange, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Pré-requisitos de implantação híbrida.</span></a></span><span class="sxs-lookup"><span data-stu-id="b68fa-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="b68fa-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="b68fa-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="b68fa-156">Emails</span><span class="sxs-lookup"><span data-stu-id="b68fa-156">Emails</span></span></li>
<li><span data-ttu-id="b68fa-157">Regras de caixa de correio do lado do servidor</span><span class="sxs-lookup"><span data-stu-id="b68fa-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="b68fa-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="b68fa-158">Delegates</span></span></li>
<li><span data-ttu-id="b68fa-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="b68fa-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b68fa-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="b68fa-160">Calendar</span></span> </li>
<li> <span data-ttu-id="b68fa-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b68fa-161">Tasks</span></span> </li>
<li> <span data-ttu-id="b68fa-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="b68fa-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="b68fa-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="b68fa-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="b68fa-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b68fa-164">Signatures</span></span> </li>
<li> <span data-ttu-id="b68fa-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="b68fa-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="b68fa-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="b68fa-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="b68fa-167">Public folders</span></span> </li>
<li> <span data-ttu-id="b68fa-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b68fa-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b68fa-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="b68fa-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="b68fa-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="b68fa-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="b68fa-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b68fa-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b68fa-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="b68fa-174">Regras de caixa de correio do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="b68fa-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-175"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="b68fa-176">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span><span class="sxs-lookup"><span data-stu-id="b68fa-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="b68fa-177">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="b68fa-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-178">Emails</span><span class="sxs-lookup"><span data-stu-id="b68fa-178">Emails</span></span> </li>
<li> <span data-ttu-id="b68fa-179">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="b68fa-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="b68fa-180">Calendário</span><span class="sxs-lookup"><span data-stu-id="b68fa-180">Calendar</span></span> </li>
<li> <span data-ttu-id="b68fa-181">Rótulos</span><span class="sxs-lookup"><span data-stu-id="b68fa-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-182">Regras</span><span class="sxs-lookup"><span data-stu-id="b68fa-182">Rules</span></span> </li>
<li> <span data-ttu-id="b68fa-183">Representantes</span><span class="sxs-lookup"><span data-stu-id="b68fa-183">Delegates</span></span> </li>
<li> <span data-ttu-id="b68fa-184">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b68fa-184">Signatures</span></span> </li>
<li> <span data-ttu-id="b68fa-185">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b68fa-185">Tasks</span></span> </li>
<li> <span data-ttu-id="b68fa-186">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b68fa-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b68fa-187">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-188">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="b68fa-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="b68fa-189">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="b68fa-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="b68fa-190">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b68fa-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="b68fa-192">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="b68fa-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="b68fa-193">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="b68fa-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="b68fa-194">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b68fa-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="b68fa-195">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="b68fa-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="b68fa-196">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="b68fa-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="b68fa-197">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b68fa-198"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="b68fa-199">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="b68fa-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="b68fa-200">Emails</span><span class="sxs-lookup"><span data-stu-id="b68fa-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="b68fa-201">Regras</span><span class="sxs-lookup"><span data-stu-id="b68fa-201">Rules</span></span> </li>
<li> <span data-ttu-id="b68fa-202">Representantes</span><span class="sxs-lookup"><span data-stu-id="b68fa-202">Delegates</span></span> </li>
<li> <span data-ttu-id="b68fa-203">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="b68fa-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="b68fa-204">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="b68fa-204">External contacts</span></span> </li>
<li> <span data-ttu-id="b68fa-205">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="b68fa-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="b68fa-206">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-207">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="b68fa-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b68fa-208">Calendário</span><span class="sxs-lookup"><span data-stu-id="b68fa-208">Calendar</span></span> </li>
<li> <span data-ttu-id="b68fa-209">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="b68fa-209">Signatures</span></span> </li>
<li> <span data-ttu-id="b68fa-210">Tarefas</span><span class="sxs-lookup"><span data-stu-id="b68fa-210">Tasks</span></span> </li>
<li> <span data-ttu-id="b68fa-211">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="b68fa-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b68fa-212">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="b68fa-212">Archive data</span></span> </li>
<li> <span data-ttu-id="b68fa-213">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="b68fa-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="b68fa-214">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b68fa-215">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="b68fa-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b68fa-216">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b68fa-216">FastTrack responsibilities</span></span>

<span data-ttu-id="b68fa-217">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-218">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b68fa-219">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="b68fa-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="b68fa-220">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b68fa-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b68fa-221">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b68fa-221">Your responsibilities</span></span>

<span data-ttu-id="b68fa-222">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-223">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b68fa-224">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="b68fa-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="b68fa-225">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="b68fa-226">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="b68fa-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b68fa-227">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="b68fa-228">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="b68fa-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="b68fa-229">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="b68fa-230">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="b68fa-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b68fa-231">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="b68fa-232">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b68fa-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="b68fa-233">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="b68fa-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="b68fa-234">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="b68fa-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="b68fa-235">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="b68fa-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="b68fa-236">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="b68fa-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="b68fa-237">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="b68fa-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="b68fa-238">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="b68fa-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="b68fa-239">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="b68fa-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="b68fa-240">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b68fa-241">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b68fa-242">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-242">You create and schedule your migration events.</span></span> <span data-ttu-id="b68fa-243">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b68fa-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b68fa-244">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="b68fa-245">Considerações</span><span class="sxs-lookup"><span data-stu-id="b68fa-245">Considerations</span></span>

 - <span data-ttu-id="b68fa-246">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="b68fa-247">Consulte os <a href="https://go.microsoft.com/fwlink/?LinkId=698855">limites do SharePoint para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="b68fa-248">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="b68fa-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b68fa-249">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="b68fa-249">Source environment details</span></span>

<span data-ttu-id="b68fa-250">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b68fa-251">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="b68fa-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b68fa-252">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b68fa-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b68fa-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="b68fa-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b68fa-254">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="b68fa-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b68fa-255">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b68fa-256"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b68fa-257"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b68fa-258"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b68fa-259"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b68fa-260"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b68fa-261">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-262">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-262">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-263">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-264">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-265">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-266">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-267">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-268">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-268">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-269">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-269">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-270">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-270">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-271">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="b68fa-272">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="b68fa-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b68fa-273">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b68fa-274">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b68fa-275">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-276">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-277">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-278">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-279">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="b68fa-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b68fa-280">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="b68fa-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b68fa-281">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="b68fa-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b68fa-282">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="b68fa-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b68fa-283">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b68fa-284">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-285">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="b68fa-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b68fa-286">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="b68fa-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b68fa-287">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-288"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b68fa-289">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-290">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="b68fa-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="b68fa-291">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-292">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-293">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-294">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-295">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-296">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-296">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-297">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-297">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-298">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-298">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-299">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-300">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b68fa-301">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-302">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-303">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b68fa-304">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-305">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-306">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-307">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-308">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-309">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-310">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-311">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-312">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="b68fa-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b68fa-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="b68fa-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b68fa-314">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="b68fa-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b68fa-315">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="b68fa-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b68fa-316">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-317">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-318">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="b68fa-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b68fa-319">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-320">Arquivos marcados como restritos ou não copiáveis</span><span class="sxs-lookup"><span data-stu-id="b68fa-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="b68fa-321">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b68fa-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b68fa-323">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-324">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-324">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-325">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-326">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-327">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-328">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-329">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-330">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-330">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-331">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-331">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-332">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-332">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-333">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-334">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="b68fa-335">Notas de caixa (convertido no formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="b68fa-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-336">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-337">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-338">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-339">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-340">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-341">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-342">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-343">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-344">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-345">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-346">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="b68fa-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b68fa-347">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b68fa-348">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-349">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-350">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-351"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="b68fa-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b68fa-352">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-353">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-353">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-354">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-355">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-356">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-357">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-358">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-359">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-359">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-360">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-360">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-361">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-361">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-362">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-363">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="b68fa-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b68fa-364">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-365">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-366">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-367">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-368">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-369">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-370">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-371">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-372">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-373">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-374">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="b68fa-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b68fa-375">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="b68fa-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b68fa-376">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="b68fa-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b68fa-377">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b68fa-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b68fa-378">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b68fa-379">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-380">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="b68fa-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="b68fa-381">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b68fa-382">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b68fa-382">FastTrack responsibilities</span></span>

<span data-ttu-id="b68fa-383">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-384">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="b68fa-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b68fa-385">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b68fa-385">Your responsibilities</span></span>

<span data-ttu-id="b68fa-386">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-387">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="b68fa-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="b68fa-388">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="b68fa-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="b68fa-389">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="b68fa-390">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="b68fa-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="b68fa-391">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b68fa-392">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b68fa-393">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-393">You create and schedule your migration events.</span></span> <span data-ttu-id="b68fa-394">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b68fa-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b68fa-395">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b68fa-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="b68fa-396">Considerações</span><span class="sxs-lookup"><span data-stu-id="b68fa-396">Considerations</span></span>

  - <span data-ttu-id="b68fa-397">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="b68fa-398">Consulte os <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> limites do SharePoint para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="b68fa-399">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="b68fa-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="b68fa-400">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b68fa-401">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="b68fa-401">Source environment details</span></span>

<span data-ttu-id="b68fa-402">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b68fa-403">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="b68fa-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b68fa-404">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b68fa-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b68fa-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="b68fa-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b68fa-406">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="b68fa-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b68fa-407">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="b68fa-408"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="b68fa-409"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="b68fa-410"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b68fa-411"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b68fa-412"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b68fa-413">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-414">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-414">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-415">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-416">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-417">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-418">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-419">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-420">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-420">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-421">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-421">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-422">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-422">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-423">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="b68fa-424">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="b68fa-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b68fa-425">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b68fa-426">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b68fa-427">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="b68fa-428">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-429">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-430">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-431">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="b68fa-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b68fa-432">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="b68fa-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b68fa-433">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="b68fa-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b68fa-434">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="b68fa-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b68fa-435">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b68fa-436">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-437">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="b68fa-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b68fa-438">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="b68fa-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b68fa-439">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-440"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b68fa-441">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-442">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="b68fa-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="b68fa-443">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-444">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-445">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-446">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-447">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-448">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-448">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-449">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-449">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-450">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-450">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-451">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-452">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b68fa-453">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-454">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-455">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b68fa-456">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-457">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-458">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-459">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-460">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-461">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-462">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-463">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-464">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="b68fa-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b68fa-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="b68fa-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b68fa-466">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="b68fa-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b68fa-467">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="b68fa-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b68fa-468">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-469">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-470">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="b68fa-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b68fa-471">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-472">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b68fa-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b68fa-474">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-475">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-475">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-476">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-477">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-478">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-479">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-480">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-481">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-481">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-482">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-482">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-483">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-483">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-484">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-485">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-486">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-487">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-488">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-489">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-490">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-491">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-492">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-493">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-494">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-495">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-496">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="b68fa-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b68fa-497">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b68fa-498">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-499">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-500">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-501"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="b68fa-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b68fa-502">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-503">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-503">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-504">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-505">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-506">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-507">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-508">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-509">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-509">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-510">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-510">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-511">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-511">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-512">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-513">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="b68fa-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b68fa-514">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b68fa-515">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-516">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-517">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-518">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-519">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-520">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-521">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-522">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-523">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-524">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="b68fa-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b68fa-525">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="b68fa-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b68fa-526">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="b68fa-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b68fa-527">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b68fa-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b68fa-528">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b68fa-529">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-530">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-531">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b68fa-532">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b68fa-532">FastTrack responsibilities</span></span>

<span data-ttu-id="b68fa-533">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-534">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b68fa-535">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b68fa-535">Your responsibilities</span></span>

<span data-ttu-id="b68fa-536">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-537">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b68fa-538">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="b68fa-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="b68fa-539">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="b68fa-540">Migração para o Microsoft Teams e grupos do Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="b68fa-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="b68fa-541">Quando você optar por usar o FastTrack para migrar seus arquivos para o Microsoft Teams e grupos do Microsoft 365, fornecemos orientações de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b68fa-542">Fornecemos orientações para ajudá-lo a planejar sua migração, configurar seus ambientes de origem e grupos do Teams e do Microsoft 365 e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b68fa-543">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-543">You create and schedule your migration events.</span></span> <span data-ttu-id="b68fa-544">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="b68fa-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b68fa-545">Quando seus eventos de migração são concluídos, você pode esperar que os arquivos de fontes adequadamente agendadas e qualificadas de seus ambientes de origem tenham sido migrados para o Teams e grupos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b68fa-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="b68fa-546">Os canais do Teams e os Grupos do Microsoft 365 devem ser pré-provisionados pelo cliente antes que eles possam migrar dados para esses tipos de destino.</span><span class="sxs-lookup"><span data-stu-id="b68fa-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="b68fa-547">Os Grupos do Teams e do Microsoft 365 impactam suas permissões no local de destino do arquivo.</span><span class="sxs-lookup"><span data-stu-id="b68fa-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="b68fa-548">O Teams e os Grupos do Microsoft 365 são construídos para permitir a colaboração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="b68fa-549">O canal do Teams ou o grupo do Microsoft 365 determinam quem tem acesso a esses arquivos ao migrar para esses destinos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="b68fa-550">O FastTrack não adiciona usuários finais ou grupos a qualquer canal do Teams ou permissão de Grupos do Microsoft 365 durante a migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="b68fa-551">Considerações</span><span class="sxs-lookup"><span data-stu-id="b68fa-551">Considerations</span></span>

- <span data-ttu-id="b68fa-552">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b68fa-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="b68fa-553">Consulte os <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> limites do SharePoint para</a> obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="b68fa-554">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="b68fa-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="b68fa-555">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="b68fa-555">Source environment details</span></span>

<span data-ttu-id="b68fa-556">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="b68fa-557">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="b68fa-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="b68fa-558">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b68fa-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="b68fa-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="b68fa-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="b68fa-560">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="b68fa-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="b68fa-561">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="b68fa-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="b68fa-562"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="b68fa-563"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="b68fa-564"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b68fa-565"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b68fa-566"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b68fa-567">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-568">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-568">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-569">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-570">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-571">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-572">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-573">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-574">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-574">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-575">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-575">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-576">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-576">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-577">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="b68fa-578">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="b68fa-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b68fa-579">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b68fa-580">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b68fa-581">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="b68fa-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="b68fa-582">As permissões são impactadas pelo grupo do Microsoft 365 e/ou pelo canal do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="b68fa-583">Se o destino for um grupo do Microsoft 365 ou canal do Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="b68fa-584">Recomendamos não migrar permissões em arquivos migrando para um canal do Microsoft 365 Group ou Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-585">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-586">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-587">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="b68fa-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="b68fa-588">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="b68fa-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b68fa-589">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="b68fa-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b68fa-590">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="b68fa-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b68fa-591">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="b68fa-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b68fa-592">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b68fa-593">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-594">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="b68fa-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b68fa-595">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="b68fa-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b68fa-596">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-597"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b68fa-598">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-599">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="b68fa-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="b68fa-600">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-601">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-602">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-603">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-604">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-605">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-605">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-606">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-606">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-607">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-607">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-608">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-609">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="b68fa-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b68fa-610">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="b68fa-611">\*As permissões são impactadas pelo grupo do Microsoft 365 e/ou pelo canal do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="b68fa-612">Se o destino for um grupo do Microsoft 365 ou canal do Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="b68fa-613">Recomendamos não migrar permissões em arquivos migrando para um canal do Microsoft 365 Group ou Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="b68fa-614">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-615">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b68fa-616">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-617">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-618">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-619">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-620">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-621">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-622">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-623">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-624">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="b68fa-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b68fa-625">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="b68fa-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b68fa-626">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="b68fa-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b68fa-627">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="b68fa-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b68fa-628">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-629">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-630">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="b68fa-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b68fa-631">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-632">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b68fa-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="b68fa-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b68fa-634">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-635">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-635">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-636">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-637">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-638">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-639">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-640">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-641">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-641">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-642">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-642">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-643">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-643">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-644">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-645">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="b68fa-646">Notas de caixa (convertido no formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="b68fa-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="b68fa-647">\*As permissões são impactadas pelo grupo do Microsoft 365 e/ou pelo canal do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="b68fa-648">Se o destino for um grupo do Microsoft 365 ou canal do Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="b68fa-649">Recomendamos não migrar permissões em arquivos migrando para um canal do Microsoft 365 Group ou Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="b68fa-650">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-651">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-652">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-653">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-654">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-655">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-656">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-657">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-658">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-659">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="b68fa-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b68fa-660">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="b68fa-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b68fa-661">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b68fa-662">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-663">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-664">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b68fa-665"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="b68fa-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b68fa-666">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="b68fa-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b68fa-667">Documentos</span><span class="sxs-lookup"><span data-stu-id="b68fa-667">Documents</span></span> </li>
<li> <span data-ttu-id="b68fa-668">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="b68fa-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b68fa-669">Permissões de pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-670">Permissões de pasta no nível de grupo\*</span><span class="sxs-lookup"><span data-stu-id="b68fa-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b68fa-671">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="b68fa-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b68fa-672">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="b68fa-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b68fa-673">Data de criação</span><span class="sxs-lookup"><span data-stu-id="b68fa-673">Created date</span></span> </li>
<li> <span data-ttu-id="b68fa-674">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="b68fa-674">Modified date</span></span> </li>
<li> <span data-ttu-id="b68fa-675">Criado por</span><span class="sxs-lookup"><span data-stu-id="b68fa-675">Created by</span></span> </li>
<li> <span data-ttu-id="b68fa-676">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="b68fa-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b68fa-677">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="b68fa-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b68fa-678">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="b68fa-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="b68fa-679">\*As permissões são impactadas pelo grupo do Microsoft 365 e/ou pelo canal do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="b68fa-680">Se o destino for um grupo do Microsoft 365 ou canal do Microsoft Teams, o grupo ou canal determinará o perfil de permissões finais em arquivos migrados.</span><span class="sxs-lookup"><span data-stu-id="b68fa-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="b68fa-681">Recomendamos não migrar permissões em arquivos migrando para um canal do Microsoft 365 Group ou Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b68fa-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="b68fa-682">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="b68fa-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b68fa-683">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="b68fa-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b68fa-684">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="b68fa-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-685">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="b68fa-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b68fa-686">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="b68fa-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b68fa-687">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="b68fa-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b68fa-688">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="b68fa-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b68fa-689">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="b68fa-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="b68fa-690">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="b68fa-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b68fa-691">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="b68fa-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b68fa-692">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="b68fa-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b68fa-693">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="b68fa-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b68fa-694">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b68fa-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b68fa-695">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="b68fa-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b68fa-696">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="b68fa-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b68fa-697">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="b68fa-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b68fa-698">Arquivos ou pastas que excedem as restrições e limitações atuais <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="b68fa-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b68fa-699">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="b68fa-699">FastTrack responsibilities</span></span>

<span data-ttu-id="b68fa-700">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-701">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b68fa-702">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="b68fa-702">Your responsibilities</span></span> 

<span data-ttu-id="b68fa-703">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b68fa-704">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="b68fa-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="b68fa-705">Você também executa as seguintes atividades, específicas das migrações do Microsoft Teams e do Microsoft 365 Groups:</span><span class="sxs-lookup"><span data-stu-id="b68fa-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="b68fa-706">Provisione todos os canais do Microsoft Teams e grupos do Microsoft 365 como direcionados por seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="b68fa-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="b68fa-707">O FastTrack não pré-provisiona canais do Microsoft Teams ou grupos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b68fa-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="b68fa-708">O FastTrack não adiciona usuários finais ou grupos aos canais do Microsoft Teams ou grupos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b68fa-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="b68fa-709">Você deve adicionar seus usuários finais ou grupos a todos os canais do Microsoft Teams e grupos do Microsoft 365 antes de migrar dados para esses destinos para que esses usuários finais tenham acesso a esses documentos recém-migrados</span><span class="sxs-lookup"><span data-stu-id="b68fa-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>
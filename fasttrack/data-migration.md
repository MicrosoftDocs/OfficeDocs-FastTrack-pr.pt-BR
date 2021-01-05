---
title: Migração de dados
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750038"
---
# <a name="data-migration"></a><span data-ttu-id="df015-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="df015-104">Data Migration</span></span>

<span data-ttu-id="df015-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="df015-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="df015-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="df015-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="df015-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="df015-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="df015-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="df015-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="df015-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="df015-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="df015-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-111">You create and schedule your migration events.</span></span> <span data-ttu-id="df015-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="df015-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="df015-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="df015-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="df015-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="df015-115">Considerations</span></span>

  - <span data-ttu-id="df015-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="df015-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="df015-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="df015-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="df015-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="df015-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="df015-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="df015-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="df015-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="df015-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="df015-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="df015-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="df015-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="df015-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="df015-124">Migration service availability</span></span>

  - <span data-ttu-id="df015-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="df015-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="df015-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="df015-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="df015-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="df015-127">Migration to Exchange Online</span></span>

<span data-ttu-id="df015-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df015-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="df015-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="df015-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-130">You create and schedule your migration events.</span></span> <span data-ttu-id="df015-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="df015-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df015-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="df015-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="df015-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="df015-133">Considerations</span></span>

  - <span data-ttu-id="df015-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="df015-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="df015-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="df015-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="df015-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="df015-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="df015-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="df015-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="df015-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="df015-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="df015-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="df015-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="df015-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="df015-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="df015-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="df015-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="df015-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="df015-143">Source environments</span></span>

<span data-ttu-id="df015-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="df015-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="df015-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="df015-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="df015-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="df015-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="df015-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="df015-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="df015-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="df015-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="df015-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="df015-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="df015-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="df015-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df015-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="df015-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="df015-154">
<strong>Observação:</strong> Para dependências do Exchange local, confira <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">pré-requisitos de implantação híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="df015-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="df015-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="df015-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="df015-156">Emails</span><span class="sxs-lookup"><span data-stu-id="df015-156">Emails</span></span></li>
<li><span data-ttu-id="df015-157">Regras de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="df015-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="df015-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="df015-158">Delegates</span></span></li>
<li><span data-ttu-id="df015-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="df015-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="df015-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="df015-160">Calendar</span></span> </li>
<li> <span data-ttu-id="df015-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="df015-161">Tasks</span></span> </li>
<li> <span data-ttu-id="df015-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="df015-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="df015-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="df015-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="df015-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="df015-164">Signatures</span></span> </li>
<li> <span data-ttu-id="df015-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="df015-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="df015-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="df015-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="df015-167">Public folders</span></span> </li>
<li> <span data-ttu-id="df015-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="df015-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df015-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="df015-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="df015-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="df015-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="df015-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df015-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="df015-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df015-174"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="df015-175">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">perform a G Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="df015-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="df015-176">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="df015-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-177">Emails</span><span class="sxs-lookup"><span data-stu-id="df015-177">Emails</span></span> </li>
<li> <span data-ttu-id="df015-178">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="df015-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="df015-179">Calendário</span><span class="sxs-lookup"><span data-stu-id="df015-179">Calendar</span></span> </li>
<li> <span data-ttu-id="df015-180">Rótulos</span><span class="sxs-lookup"><span data-stu-id="df015-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-181">Regras</span><span class="sxs-lookup"><span data-stu-id="df015-181">Rules</span></span> </li>
<li> <span data-ttu-id="df015-182">Representantes</span><span class="sxs-lookup"><span data-stu-id="df015-182">Delegates</span></span> </li>
<li> <span data-ttu-id="df015-183">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="df015-183">Signatures</span></span> </li>
<li> <span data-ttu-id="df015-184">Tarefas</span><span class="sxs-lookup"><span data-stu-id="df015-184">Tasks</span></span> </li>
<li> <span data-ttu-id="df015-185">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="df015-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df015-186">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-187">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="df015-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="df015-188">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="df015-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="df015-189">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df015-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="df015-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="df015-191">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="df015-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="df015-192">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="df015-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="df015-193">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="df015-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="df015-194">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="df015-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="df015-195">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="df015-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="df015-196">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df015-197"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="df015-198">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="df015-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="df015-199">Emails</span><span class="sxs-lookup"><span data-stu-id="df015-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="df015-200">Regras</span><span class="sxs-lookup"><span data-stu-id="df015-200">Rules</span></span> </li>
<li> <span data-ttu-id="df015-201">Representantes</span><span class="sxs-lookup"><span data-stu-id="df015-201">Delegates</span></span> </li>
<li> <span data-ttu-id="df015-202">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="df015-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="df015-203">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="df015-203">External contacts</span></span> </li>
<li> <span data-ttu-id="df015-204">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="df015-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="df015-205">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-206">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="df015-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="df015-207">Calendário</span><span class="sxs-lookup"><span data-stu-id="df015-207">Calendar</span></span> </li>
<li> <span data-ttu-id="df015-208">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="df015-208">Signatures</span></span> </li>
<li> <span data-ttu-id="df015-209">Tarefas</span><span class="sxs-lookup"><span data-stu-id="df015-209">Tasks</span></span> </li>
<li> <span data-ttu-id="df015-210">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="df015-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df015-211">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="df015-211">Archive data</span></span> </li>
<li> <span data-ttu-id="df015-212">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="df015-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="df015-213">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df015-214">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="df015-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df015-215">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="df015-215">FastTrack responsibilities</span></span>

<span data-ttu-id="df015-216">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-217">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df015-218">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="df015-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="df015-219">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="df015-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df015-220">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="df015-220">Your responsibilities</span></span>

<span data-ttu-id="df015-221">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-222">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df015-223">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="df015-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="df015-224">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="df015-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="df015-225">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="df015-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="df015-226">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="df015-227">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="df015-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="df015-228">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="df015-229">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="df015-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="df015-230">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="df015-231">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="df015-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="df015-232">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="df015-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="df015-233">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="df015-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="df015-234">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="df015-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="df015-235">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="df015-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="df015-236">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="df015-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="df015-237">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="df015-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="df015-238">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="df015-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="df015-239">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df015-240">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="df015-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="df015-241">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-241">You create and schedule your migration events.</span></span> <span data-ttu-id="df015-242">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="df015-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df015-243">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="df015-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="df015-244">Considerações</span><span class="sxs-lookup"><span data-stu-id="df015-244">Considerations</span></span>

  - <span data-ttu-id="df015-245">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="df015-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="df015-246">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="df015-247">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="df015-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="df015-248">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="df015-248">Source environment details</span></span>

<span data-ttu-id="df015-249">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="df015-250">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="df015-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="df015-251">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="df015-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="df015-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="df015-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="df015-253">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="df015-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="df015-254">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="df015-255"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="df015-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="df015-256"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="df015-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="df015-257"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="df015-258"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df015-259"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="df015-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="df015-260">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-261">Documents</span></span> </li>
<li> <span data-ttu-id="df015-262">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-263">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="df015-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df015-264">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="df015-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df015-265">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-266">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-267">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-267">Created date</span></span> </li>
<li> <span data-ttu-id="df015-268">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-268">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-269">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-269">Created by</span></span> </li>
<li> <span data-ttu-id="df015-270">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="df015-271">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="df015-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="df015-272">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="df015-273">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="df015-274">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-275">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="df015-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="df015-276">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-277">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="df015-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="df015-278">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="df015-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="df015-279">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="df015-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="df015-280">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="df015-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="df015-281">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="df015-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="df015-282">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="df015-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="df015-283">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-284">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="df015-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="df015-285">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="df015-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="df015-286">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df015-287"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="df015-288">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-289">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="df015-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="df015-290">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-291">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-292">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-293">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-294">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-295">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-295">Created date</span></span> </li>
<li> <span data-ttu-id="df015-296">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-296">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-297">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-297">Created by</span></span> </li>
<li> <span data-ttu-id="df015-298">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-299">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="df015-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="df015-300">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="df015-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-301">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-302">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="df015-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="df015-303">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-304">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-305">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-306">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-307">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-308">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-309">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-310">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-311">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="df015-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="df015-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="df015-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="df015-313">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="df015-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="df015-314">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="df015-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="df015-315">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-316">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="df015-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df015-317">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="df015-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="df015-318">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="df015-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="df015-319">Arquivos marcados como restritos ou não copiados</span><span class="sxs-lookup"><span data-stu-id="df015-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="df015-320">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df015-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="df015-322">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-323">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-323">Documents</span></span> </li>
<li> <span data-ttu-id="df015-324">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-325">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-326">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-327">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-328">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-329">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-329">Created date</span></span> </li>
<li> <span data-ttu-id="df015-330">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-330">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-331">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-331">Created by</span></span> </li>
<li> <span data-ttu-id="df015-332">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-333">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="df015-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="df015-334">Anotações de caixa (convertidas em formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="df015-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-335">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-336">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="df015-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df015-337">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-338">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-339">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-340">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-341">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-342">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-343">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-344">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-345">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="df015-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="df015-346">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="df015-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="df015-347">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-348">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="df015-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df015-349">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df015-350"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="df015-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="df015-351">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-352">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-352">Documents</span></span> </li>
<li> <span data-ttu-id="df015-353">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-354">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-355">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-356">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-357">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-358">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-358">Created date</span></span> </li>
<li> <span data-ttu-id="df015-359">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-359">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-360">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-360">Created by</span></span> </li>
<li> <span data-ttu-id="df015-361">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-362">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="df015-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="df015-363">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="df015-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-364">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-365">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="df015-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df015-366">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-367">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-368">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-369">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-370">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-371">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-372">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-373">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="df015-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="df015-374">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="df015-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="df015-375">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="df015-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="df015-376">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="df015-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="df015-377">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="df015-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="df015-378">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-379">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="df015-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="df015-380">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df015-381">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="df015-381">FastTrack responsibilities</span></span>

<span data-ttu-id="df015-382">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-383">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="df015-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df015-384">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="df015-384">Your responsibilities</span></span>

<span data-ttu-id="df015-385">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-386">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="df015-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="df015-387">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="df015-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="df015-388">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="df015-389">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="df015-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="df015-390">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="df015-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df015-391">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="df015-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="df015-392">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-392">You create and schedule your migration events.</span></span> <span data-ttu-id="df015-393">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="df015-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df015-394">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="df015-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="df015-395">Considerações</span><span class="sxs-lookup"><span data-stu-id="df015-395">Considerations</span></span>

  - <span data-ttu-id="df015-396">Todas as migrações estão sujeitas a cotas do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="df015-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="df015-397">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="df015-398">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="df015-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="df015-399">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="df015-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="df015-400">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="df015-400">Source environment details</span></span>

<span data-ttu-id="df015-401">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="df015-402">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="df015-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="df015-403">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="df015-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="df015-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="df015-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="df015-405">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="df015-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="df015-406">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="df015-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="df015-407"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="df015-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="df015-408"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="df015-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="df015-409"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="df015-410"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="df015-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df015-411"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="df015-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="df015-412">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-413">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-413">Documents</span></span> </li>
<li> <span data-ttu-id="df015-414">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-415">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="df015-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df015-416">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="df015-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df015-417">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-418">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-419">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-419">Created date</span></span> </li>
<li> <span data-ttu-id="df015-420">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-420">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-421">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-421">Created by</span></span> </li>
<li> <span data-ttu-id="df015-422">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="df015-423">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="df015-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="df015-424">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="df015-425">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="df015-426">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="df015-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="df015-427">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="df015-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="df015-428">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-429">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="df015-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="df015-430">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="df015-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="df015-431">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="df015-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="df015-432">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="df015-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="df015-433">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="df015-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="df015-434">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="df015-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="df015-435">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-436">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="df015-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="df015-437">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="df015-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="df015-438">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df015-439"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="df015-440">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-441">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="df015-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="df015-442">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-443">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-444">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-445">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-446">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-447">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-447">Created date</span></span> </li>
<li> <span data-ttu-id="df015-448">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-448">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-449">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-449">Created by</span></span> </li>
<li> <span data-ttu-id="df015-450">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-451">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="df015-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="df015-452">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="df015-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-453">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-454">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="df015-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="df015-455">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-456">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-457">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-458">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-459">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-460">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-461">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-462">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-463">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="df015-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="df015-464">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="df015-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="df015-465">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="df015-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="df015-466">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="df015-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="df015-467">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-468">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="df015-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df015-469">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="df015-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="df015-470">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="df015-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="df015-471">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df015-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="df015-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="df015-473">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-474">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-474">Documents</span></span> </li>
<li> <span data-ttu-id="df015-475">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-476">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-477">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-478">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-479">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-480">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-480">Created date</span></span> </li>
<li> <span data-ttu-id="df015-481">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-481">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-482">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-482">Created by</span></span> </li>
<li> <span data-ttu-id="df015-483">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-484">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="df015-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-485">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-486">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="df015-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df015-487">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-488">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-489">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-490">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-491">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-492">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-493">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-494">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="df015-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df015-495">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="df015-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="df015-496">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="df015-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="df015-497">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-498">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="df015-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df015-499">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df015-500"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="df015-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="df015-501">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="df015-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df015-502">Documentos</span><span class="sxs-lookup"><span data-stu-id="df015-502">Documents</span></span> </li>
<li> <span data-ttu-id="df015-503">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="df015-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df015-504">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-505">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df015-506">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="df015-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df015-507">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="df015-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df015-508">Data de criação</span><span class="sxs-lookup"><span data-stu-id="df015-508">Created date</span></span> </li>
<li> <span data-ttu-id="df015-509">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="df015-509">Modified date</span></span> </li>
<li> <span data-ttu-id="df015-510">Criado por</span><span class="sxs-lookup"><span data-stu-id="df015-510">Created by</span></span> </li>
<li> <span data-ttu-id="df015-511">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="df015-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df015-512">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="df015-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="df015-513">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="df015-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df015-514">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="df015-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df015-515">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="df015-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df015-516">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="df015-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-517">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="df015-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df015-518">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="df015-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df015-519">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="df015-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df015-520">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="df015-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df015-521">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="df015-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="df015-522">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="df015-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df015-523">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="df015-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="df015-524">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="df015-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="df015-525">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="df015-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="df015-526">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="df015-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="df015-527">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="df015-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="df015-528">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="df015-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="df015-529">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="df015-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df015-530">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="df015-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df015-531">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="df015-531">FastTrack responsibilities</span></span>

<span data-ttu-id="df015-532">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-533">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df015-534">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="df015-534">Your responsibilities</span></span>

<span data-ttu-id="df015-535">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df015-536">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="df015-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df015-537">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="df015-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="df015-538">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="df015-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

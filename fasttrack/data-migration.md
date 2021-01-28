---
title: Migração de dados
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016467"
---
# <a name="data-migration"></a><span data-ttu-id="dc6de-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="dc6de-104">Data Migration</span></span>

<span data-ttu-id="dc6de-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="dc6de-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="dc6de-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="dc6de-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="dc6de-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="dc6de-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="dc6de-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="dc6de-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="dc6de-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="dc6de-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-111">You create and schedule your migration events.</span></span> <span data-ttu-id="dc6de-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="dc6de-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="dc6de-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="dc6de-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="dc6de-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="dc6de-115">Considerations</span></span>

  - <span data-ttu-id="dc6de-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="dc6de-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="dc6de-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="dc6de-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="dc6de-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="dc6de-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="dc6de-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="dc6de-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="dc6de-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="dc6de-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="dc6de-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="dc6de-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="dc6de-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="dc6de-124">Migration service availability</span></span>

  - <span data-ttu-id="dc6de-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="dc6de-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="dc6de-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="dc6de-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="dc6de-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="dc6de-127">Migration to Exchange Online</span></span>

<span data-ttu-id="dc6de-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="dc6de-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="dc6de-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="dc6de-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-130">You create and schedule your migration events.</span></span> <span data-ttu-id="dc6de-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="dc6de-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="dc6de-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="dc6de-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="dc6de-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="dc6de-133">Considerations</span></span>

  - <span data-ttu-id="dc6de-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="dc6de-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="dc6de-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="dc6de-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="dc6de-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="dc6de-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="dc6de-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="dc6de-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="dc6de-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="dc6de-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="dc6de-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="dc6de-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="dc6de-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="dc6de-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="dc6de-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="dc6de-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="dc6de-143">Source environments</span></span>

<span data-ttu-id="dc6de-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="dc6de-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="dc6de-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="dc6de-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="dc6de-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="dc6de-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="dc6de-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="dc6de-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dc6de-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="dc6de-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="dc6de-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="dc6de-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dc6de-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="dc6de-154">
<strong>Observação:</strong> Para dependências locais do Exchange, confira Pré-requisitos de implantação <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">híbrida.</span></a></span><span class="sxs-lookup"><span data-stu-id="dc6de-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="dc6de-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="dc6de-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="dc6de-156">Emails</span><span class="sxs-lookup"><span data-stu-id="dc6de-156">Emails</span></span></li>
<li><span data-ttu-id="dc6de-157">Regras de caixa de correio do lado do servidor</span><span class="sxs-lookup"><span data-stu-id="dc6de-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="dc6de-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="dc6de-158">Delegates</span></span></li>
<li><span data-ttu-id="dc6de-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="dc6de-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="dc6de-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="dc6de-160">Calendar</span></span> </li>
<li> <span data-ttu-id="dc6de-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="dc6de-161">Tasks</span></span> </li>
<li> <span data-ttu-id="dc6de-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="dc6de-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="dc6de-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="dc6de-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="dc6de-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="dc6de-164">Signatures</span></span> </li>
<li> <span data-ttu-id="dc6de-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="dc6de-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="dc6de-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="dc6de-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="dc6de-167">Public folders</span></span> </li>
<li> <span data-ttu-id="dc6de-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="dc6de-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="dc6de-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="dc6de-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="dc6de-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="dc6de-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="dc6de-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="dc6de-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="dc6de-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="dc6de-174">Regras de caixa de correio do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="dc6de-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dc6de-175"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="dc6de-176">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Executar uma migração do G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="dc6de-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="dc6de-177">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="dc6de-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-178">Emails</span><span class="sxs-lookup"><span data-stu-id="dc6de-178">Emails</span></span> </li>
<li> <span data-ttu-id="dc6de-179">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="dc6de-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="dc6de-180">Calendário</span><span class="sxs-lookup"><span data-stu-id="dc6de-180">Calendar</span></span> </li>
<li> <span data-ttu-id="dc6de-181">Rótulos</span><span class="sxs-lookup"><span data-stu-id="dc6de-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-182">Regras</span><span class="sxs-lookup"><span data-stu-id="dc6de-182">Rules</span></span> </li>
<li> <span data-ttu-id="dc6de-183">Representantes</span><span class="sxs-lookup"><span data-stu-id="dc6de-183">Delegates</span></span> </li>
<li> <span data-ttu-id="dc6de-184">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="dc6de-184">Signatures</span></span> </li>
<li> <span data-ttu-id="dc6de-185">Tarefas</span><span class="sxs-lookup"><span data-stu-id="dc6de-185">Tasks</span></span> </li>
<li> <span data-ttu-id="dc6de-186">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="dc6de-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="dc6de-187">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-188">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="dc6de-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="dc6de-189">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="dc6de-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="dc6de-190">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="dc6de-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="dc6de-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="dc6de-192">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="dc6de-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="dc6de-193">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="dc6de-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="dc6de-194">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="dc6de-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="dc6de-195">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="dc6de-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="dc6de-196">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="dc6de-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="dc6de-197">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dc6de-198"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="dc6de-199">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="dc6de-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="dc6de-200">Emails</span><span class="sxs-lookup"><span data-stu-id="dc6de-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="dc6de-201">Regras</span><span class="sxs-lookup"><span data-stu-id="dc6de-201">Rules</span></span> </li>
<li> <span data-ttu-id="dc6de-202">Representantes</span><span class="sxs-lookup"><span data-stu-id="dc6de-202">Delegates</span></span> </li>
<li> <span data-ttu-id="dc6de-203">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="dc6de-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="dc6de-204">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="dc6de-204">External contacts</span></span> </li>
<li> <span data-ttu-id="dc6de-205">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="dc6de-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="dc6de-206">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-207">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="dc6de-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="dc6de-208">Calendário</span><span class="sxs-lookup"><span data-stu-id="dc6de-208">Calendar</span></span> </li>
<li> <span data-ttu-id="dc6de-209">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="dc6de-209">Signatures</span></span> </li>
<li> <span data-ttu-id="dc6de-210">Tarefas</span><span class="sxs-lookup"><span data-stu-id="dc6de-210">Tasks</span></span> </li>
<li> <span data-ttu-id="dc6de-211">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="dc6de-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="dc6de-212">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="dc6de-212">Archive data</span></span> </li>
<li> <span data-ttu-id="dc6de-213">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="dc6de-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="dc6de-214">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="dc6de-215">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="dc6de-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="dc6de-216">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="dc6de-216">FastTrack responsibilities</span></span>

<span data-ttu-id="dc6de-217">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-218">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="dc6de-219">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="dc6de-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="dc6de-220">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="dc6de-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="dc6de-221">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="dc6de-221">Your responsibilities</span></span>

<span data-ttu-id="dc6de-222">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-223">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="dc6de-224">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="dc6de-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="dc6de-225">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="dc6de-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="dc6de-226">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="dc6de-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="dc6de-227">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="dc6de-228">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="dc6de-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="dc6de-229">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="dc6de-230">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="dc6de-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="dc6de-231">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="dc6de-232">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="dc6de-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="dc6de-233">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="dc6de-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="dc6de-234">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="dc6de-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="dc6de-235">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="dc6de-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="dc6de-236">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="dc6de-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="dc6de-237">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="dc6de-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="dc6de-238">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="dc6de-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="dc6de-239">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="dc6de-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="dc6de-240">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="dc6de-241">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="dc6de-242">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-242">You create and schedule your migration events.</span></span> <span data-ttu-id="dc6de-243">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="dc6de-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="dc6de-244">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="dc6de-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="dc6de-245">Considerações</span><span class="sxs-lookup"><span data-stu-id="dc6de-245">Considerations</span></span>

  - <span data-ttu-id="dc6de-246">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="dc6de-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="dc6de-247">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="dc6de-248">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="dc6de-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="dc6de-249">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="dc6de-249">Source environment details</span></span>

<span data-ttu-id="dc6de-250">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="dc6de-251">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="dc6de-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="dc6de-252">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="dc6de-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="dc6de-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="dc6de-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="dc6de-254">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="dc6de-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="dc6de-255">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="dc6de-256"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="dc6de-257"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="dc6de-258"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="dc6de-259"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dc6de-260"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="dc6de-261">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-262">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-262">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-263">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-264">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="dc6de-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="dc6de-265">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="dc6de-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="dc6de-266">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-267">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-268">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-268">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-269">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-269">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-270">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-270">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-271">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="dc6de-272">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="dc6de-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="dc6de-273">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="dc6de-274">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="dc6de-275">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-276">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="dc6de-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="dc6de-277">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-278">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="dc6de-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="dc6de-279">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="dc6de-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="dc6de-280">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="dc6de-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="dc6de-281">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="dc6de-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="dc6de-282">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="dc6de-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="dc6de-283">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="dc6de-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="dc6de-284">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-285">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="dc6de-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="dc6de-286">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="dc6de-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="dc6de-287">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dc6de-288"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="dc6de-289">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-290">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="dc6de-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="dc6de-291">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-292">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-293">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-294">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-295">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-296">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-296">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-297">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-297">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-298">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-298">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-299">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-300">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="dc6de-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="dc6de-301">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-302">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-303">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="dc6de-304">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-305">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-306">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-307">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-308">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-309">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-310">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-311">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-312">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="dc6de-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="dc6de-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="dc6de-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="dc6de-314">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="dc6de-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="dc6de-315">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="dc6de-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="dc6de-316">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-317">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-318">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="dc6de-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="dc6de-319">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-320">Arquivos marcados como restritos ou não copiados</span><span class="sxs-lookup"><span data-stu-id="dc6de-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="dc6de-321">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dc6de-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="dc6de-323">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-324">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-324">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-325">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-326">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-327">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-328">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-329">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-330">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-330">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-331">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-331">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-332">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-332">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-333">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-334">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="dc6de-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="dc6de-335">Anotações do Box (convertido para o formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="dc6de-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-336">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-337">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="dc6de-338">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-339">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-340">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-341">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-342">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-343">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-344">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-345">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-346">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="dc6de-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="dc6de-347">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="dc6de-348">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-349">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-350">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dc6de-351"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="dc6de-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="dc6de-352">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-353">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-353">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-354">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-355">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-356">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-357">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-358">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-359">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-359">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-360">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-360">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-361">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-361">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-362">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-363">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="dc6de-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="dc6de-364">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="dc6de-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-365">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-366">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="dc6de-367">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-368">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-369">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-370">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-371">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-372">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-373">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-374">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="dc6de-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="dc6de-375">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="dc6de-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="dc6de-376">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="dc6de-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="dc6de-377">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="dc6de-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="dc6de-378">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="dc6de-379">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-380">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="dc6de-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="dc6de-381">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="dc6de-382">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="dc6de-382">FastTrack responsibilities</span></span>

<span data-ttu-id="dc6de-383">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-384">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="dc6de-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="dc6de-385">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="dc6de-385">Your responsibilities</span></span>

<span data-ttu-id="dc6de-386">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-387">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="dc6de-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="dc6de-388">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="dc6de-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="dc6de-389">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="dc6de-390">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="dc6de-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="dc6de-391">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="dc6de-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="dc6de-392">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="dc6de-393">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-393">You create and schedule your migration events.</span></span> <span data-ttu-id="dc6de-394">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="dc6de-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="dc6de-395">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="dc6de-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="dc6de-396">Considerações</span><span class="sxs-lookup"><span data-stu-id="dc6de-396">Considerations</span></span>

  - <span data-ttu-id="dc6de-397">Todas as migrações estão sujeitas a cotas do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="dc6de-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="dc6de-398">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="dc6de-399">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="dc6de-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="dc6de-400">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="dc6de-401">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="dc6de-401">Source environment details</span></span>

<span data-ttu-id="dc6de-402">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="dc6de-403">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="dc6de-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="dc6de-404">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="dc6de-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="dc6de-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="dc6de-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="dc6de-406">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="dc6de-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="dc6de-407">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="dc6de-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="dc6de-408"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="dc6de-409"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="dc6de-410"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="dc6de-411"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="dc6de-412"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="dc6de-413">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-414">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-414">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-415">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-416">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="dc6de-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="dc6de-417">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="dc6de-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="dc6de-418">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-419">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-420">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-420">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-421">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-421">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-422">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-422">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-423">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="dc6de-424">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="dc6de-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="dc6de-425">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="dc6de-426">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="dc6de-427">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="dc6de-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="dc6de-428">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="dc6de-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="dc6de-429">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-430">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="dc6de-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="dc6de-431">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="dc6de-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="dc6de-432">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="dc6de-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="dc6de-433">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="dc6de-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="dc6de-434">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="dc6de-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="dc6de-435">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="dc6de-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="dc6de-436">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-437">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="dc6de-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="dc6de-438">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="dc6de-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="dc6de-439">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dc6de-440"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="dc6de-441">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-442">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="dc6de-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="dc6de-443">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-444">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-445">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-446">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-447">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-448">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-448">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-449">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-449">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-450">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-450">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-451">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-452">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="dc6de-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="dc6de-453">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-454">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-455">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="dc6de-456">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-457">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-458">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-459">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-460">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-461">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-462">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-463">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-464">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="dc6de-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="dc6de-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="dc6de-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="dc6de-466">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="dc6de-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="dc6de-467">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="dc6de-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="dc6de-468">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-469">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-470">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="dc6de-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="dc6de-471">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-472">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="dc6de-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="dc6de-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="dc6de-474">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-475">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-475">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-476">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-477">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-478">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-479">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-480">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-481">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-481">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-482">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-482">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-483">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-483">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-484">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-485">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="dc6de-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-486">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-487">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="dc6de-488">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-489">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-490">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-491">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-492">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-493">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-494">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-495">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="dc6de-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="dc6de-496">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="dc6de-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="dc6de-497">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="dc6de-498">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-499">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-500">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="dc6de-501"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="dc6de-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="dc6de-502">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="dc6de-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="dc6de-503">Documentos</span><span class="sxs-lookup"><span data-stu-id="dc6de-503">Documents</span></span> </li>
<li> <span data-ttu-id="dc6de-504">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="dc6de-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="dc6de-505">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-506">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-507">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="dc6de-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="dc6de-508">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="dc6de-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="dc6de-509">Data de criação</span><span class="sxs-lookup"><span data-stu-id="dc6de-509">Created date</span></span> </li>
<li> <span data-ttu-id="dc6de-510">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="dc6de-510">Modified date</span></span> </li>
<li> <span data-ttu-id="dc6de-511">Criado por</span><span class="sxs-lookup"><span data-stu-id="dc6de-511">Created by</span></span> </li>
<li> <span data-ttu-id="dc6de-512">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="dc6de-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="dc6de-513">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="dc6de-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="dc6de-514">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="dc6de-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="dc6de-515">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="dc6de-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="dc6de-516">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="dc6de-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="dc6de-517">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="dc6de-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-518">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="dc6de-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="dc6de-519">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="dc6de-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="dc6de-520">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="dc6de-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="dc6de-521">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="dc6de-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="dc6de-522">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="dc6de-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="dc6de-523">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="dc6de-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="dc6de-524">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="dc6de-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="dc6de-525">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="dc6de-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="dc6de-526">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="dc6de-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="dc6de-527">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="dc6de-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="dc6de-528">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="dc6de-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="dc6de-529">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="dc6de-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="dc6de-530">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="dc6de-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="dc6de-531">Arquivos ou pastas que excedem restrições e <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="dc6de-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="dc6de-532">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="dc6de-532">FastTrack responsibilities</span></span>

<span data-ttu-id="dc6de-533">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-534">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="dc6de-535">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="dc6de-535">Your responsibilities</span></span>

<span data-ttu-id="dc6de-536">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="dc6de-537">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="dc6de-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="dc6de-538">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="dc6de-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="dc6de-539">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="dc6de-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

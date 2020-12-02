---
title: Migração de dados
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525325"
---
# <a name="data-migration"></a><span data-ttu-id="c9b00-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="c9b00-104">Data Migration</span></span>

<span data-ttu-id="c9b00-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="c9b00-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="c9b00-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="c9b00-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="c9b00-107">**Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="c9b00-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="c9b00-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="c9b00-109">**Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="c9b00-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="c9b00-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-111">You create and schedule your migration events.</span></span> <span data-ttu-id="c9b00-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="c9b00-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="c9b00-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="c9b00-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="c9b00-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="c9b00-115">Considerations</span></span>

  - <span data-ttu-id="c9b00-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="c9b00-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="c9b00-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="c9b00-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="c9b00-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="c9b00-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="c9b00-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="c9b00-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="c9b00-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="c9b00-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="c9b00-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="c9b00-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="c9b00-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="c9b00-124">Migration service availability</span></span>

  - <span data-ttu-id="c9b00-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="c9b00-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="c9b00-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="c9b00-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="c9b00-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c9b00-127">Migration to Exchange Online</span></span>

<span data-ttu-id="c9b00-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c9b00-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="c9b00-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="c9b00-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-130">You create and schedule your migration events.</span></span> <span data-ttu-id="c9b00-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="c9b00-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c9b00-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c9b00-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="c9b00-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="c9b00-133">Considerations</span></span>

  - <span data-ttu-id="c9b00-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="c9b00-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="c9b00-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="c9b00-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c9b00-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="c9b00-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="c9b00-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="c9b00-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c9b00-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="c9b00-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="c9b00-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="c9b00-141">Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="c9b00-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="c9b00-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="c9b00-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="c9b00-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="c9b00-143">Source environments</span></span>

<span data-ttu-id="c9b00-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="c9b00-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="c9b00-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="c9b00-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="c9b00-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="c9b00-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="c9b00-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="c9b00-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c9b00-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c9b00-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c9b00-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="c9b00-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c9b00-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="c9b00-154">
<strong>Observação:</strong> Para dependências do Exchange local, confira <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">pré-requisitos de implantação híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="c9b00-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="c9b00-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="c9b00-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="c9b00-156">Emails</span><span class="sxs-lookup"><span data-stu-id="c9b00-156">Emails</span></span></li>
<li><span data-ttu-id="c9b00-157">Regras de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="c9b00-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="c9b00-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="c9b00-158">Delegates</span></span></li>
<li><span data-ttu-id="c9b00-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="c9b00-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c9b00-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="c9b00-160">Calendar</span></span> </li>
<li> <span data-ttu-id="c9b00-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="c9b00-161">Tasks</span></span> </li>
<li> <span data-ttu-id="c9b00-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="c9b00-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="c9b00-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="c9b00-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="c9b00-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="c9b00-164">Signatures</span></span> </li>
<li> <span data-ttu-id="c9b00-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="c9b00-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="c9b00-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="c9b00-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="c9b00-167">Public folders</span></span> </li>
<li> <span data-ttu-id="c9b00-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="c9b00-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c9b00-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="c9b00-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="c9b00-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="c9b00-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="c9b00-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c9b00-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="c9b00-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c9b00-174"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="c9b00-175">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">perform a G Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="c9b00-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="c9b00-176">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="c9b00-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-177">Emails</span><span class="sxs-lookup"><span data-stu-id="c9b00-177">Emails</span></span> </li>
<li> <span data-ttu-id="c9b00-178">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="c9b00-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="c9b00-179">Calendário</span><span class="sxs-lookup"><span data-stu-id="c9b00-179">Calendar</span></span> </li>
<li> <span data-ttu-id="c9b00-180">Rótulos</span><span class="sxs-lookup"><span data-stu-id="c9b00-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-181">Regras</span><span class="sxs-lookup"><span data-stu-id="c9b00-181">Rules</span></span> </li>
<li> <span data-ttu-id="c9b00-182">Representantes</span><span class="sxs-lookup"><span data-stu-id="c9b00-182">Delegates</span></span> </li>
<li> <span data-ttu-id="c9b00-183">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="c9b00-183">Signatures</span></span> </li>
<li> <span data-ttu-id="c9b00-184">Tarefas</span><span class="sxs-lookup"><span data-stu-id="c9b00-184">Tasks</span></span> </li>
<li> <span data-ttu-id="c9b00-185">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="c9b00-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c9b00-186">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-187">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="c9b00-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="c9b00-188">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="c9b00-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="c9b00-189">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c9b00-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="c9b00-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="c9b00-191">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="c9b00-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="c9b00-192">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="c9b00-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="c9b00-193">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="c9b00-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c9b00-194">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="c9b00-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="c9b00-195">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="c9b00-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="c9b00-196">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c9b00-197"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="c9b00-198">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="c9b00-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="c9b00-199">Emails</span><span class="sxs-lookup"><span data-stu-id="c9b00-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="c9b00-200">Regras</span><span class="sxs-lookup"><span data-stu-id="c9b00-200">Rules</span></span> </li>
<li> <span data-ttu-id="c9b00-201">Representantes</span><span class="sxs-lookup"><span data-stu-id="c9b00-201">Delegates</span></span> </li>
<li> <span data-ttu-id="c9b00-202">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="c9b00-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="c9b00-203">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="c9b00-203">External contacts</span></span> </li>
<li> <span data-ttu-id="c9b00-204">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="c9b00-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="c9b00-205">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-206">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="c9b00-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c9b00-207">Calendário</span><span class="sxs-lookup"><span data-stu-id="c9b00-207">Calendar</span></span> </li>
<li> <span data-ttu-id="c9b00-208">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="c9b00-208">Signatures</span></span> </li>
<li> <span data-ttu-id="c9b00-209">Tarefas</span><span class="sxs-lookup"><span data-stu-id="c9b00-209">Tasks</span></span> </li>
<li> <span data-ttu-id="c9b00-210">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="c9b00-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c9b00-211">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="c9b00-211">Archive data</span></span> </li>
<li> <span data-ttu-id="c9b00-212">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="c9b00-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="c9b00-213">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c9b00-214">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="c9b00-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c9b00-215">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="c9b00-215">FastTrack responsibilities</span></span>

<span data-ttu-id="c9b00-216">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-217">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c9b00-218">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="c9b00-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="c9b00-219">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="c9b00-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c9b00-220">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="c9b00-220">Your responsibilities</span></span>

<span data-ttu-id="c9b00-221">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-222">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c9b00-223">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="c9b00-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="c9b00-224">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c9b00-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="c9b00-225">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="c9b00-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c9b00-226">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="c9b00-227">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="c9b00-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="c9b00-228">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="c9b00-229">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="c9b00-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c9b00-230">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="c9b00-231">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="c9b00-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="c9b00-232">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="c9b00-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="c9b00-233">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="c9b00-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="c9b00-234">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="c9b00-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="c9b00-235">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="c9b00-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="c9b00-236">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="c9b00-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="c9b00-237">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="c9b00-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="c9b00-238">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c9b00-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="c9b00-239">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c9b00-240">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c9b00-241">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-241">You create and schedule your migration events.</span></span> <span data-ttu-id="c9b00-242">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="c9b00-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c9b00-243">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c9b00-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="c9b00-244">Considerações</span><span class="sxs-lookup"><span data-stu-id="c9b00-244">Considerations</span></span>

  - <span data-ttu-id="c9b00-245">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c9b00-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c9b00-246">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c9b00-247">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="c9b00-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c9b00-248">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="c9b00-248">Source environment details</span></span>

<span data-ttu-id="c9b00-249">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c9b00-250">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="c9b00-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c9b00-251">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="c9b00-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c9b00-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c9b00-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c9b00-253">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="c9b00-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c9b00-254">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c9b00-255"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c9b00-256"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c9b00-257"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c9b00-258"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c9b00-259"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c9b00-260">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-261">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-262">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-263">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="c9b00-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c9b00-264">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="c9b00-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c9b00-265">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-266">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-267">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-267">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-268">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-268">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-269">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-269">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-270">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="c9b00-271">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="c9b00-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c9b00-272">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c9b00-273">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c9b00-274">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-275">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="c9b00-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c9b00-276">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-277">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="c9b00-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="c9b00-278">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="c9b00-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c9b00-279">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="c9b00-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c9b00-280">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="c9b00-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c9b00-281">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="c9b00-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c9b00-282">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="c9b00-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c9b00-283">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-284">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="c9b00-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c9b00-285">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="c9b00-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c9b00-286">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c9b00-287"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c9b00-288">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-289">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="c9b00-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="c9b00-290">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-291">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-292">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-293">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-294">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-295">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-295">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-296">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-296">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-297">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-297">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-298">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-299">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="c9b00-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c9b00-300">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-301">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-302">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c9b00-303">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-304">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-305">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-306">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-307">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-308">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-309">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-310">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-311">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="c9b00-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c9b00-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="c9b00-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c9b00-313">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="c9b00-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c9b00-314">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="c9b00-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c9b00-315">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-316">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-317">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="c9b00-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c9b00-318">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-319">Arquivos marcados como restritos ou não copiados</span><span class="sxs-lookup"><span data-stu-id="c9b00-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="c9b00-320">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c9b00-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c9b00-322">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-323">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-323">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-324">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-325">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-326">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-327">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-328">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-329">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-329">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-330">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-330">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-331">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-331">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-332">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-333">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="c9b00-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="c9b00-334">Anotações de caixa (convertidas em formato de documento do Word)</span><span class="sxs-lookup"><span data-stu-id="c9b00-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-335">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-336">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c9b00-337">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-338">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-339">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-340">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-341">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-342">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-343">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-344">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-345">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="c9b00-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c9b00-346">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c9b00-347">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-348">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-349">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c9b00-350"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="c9b00-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c9b00-351">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-352">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-352">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-353">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-354">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-355">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-356">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-357">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-358">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-358">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-359">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-359">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-360">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-360">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-361">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-362">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="c9b00-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c9b00-363">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="c9b00-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-364">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-365">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c9b00-366">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-367">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-368">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-369">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-370">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-371">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-372">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-373">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="c9b00-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c9b00-374">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="c9b00-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c9b00-375">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="c9b00-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c9b00-376">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="c9b00-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c9b00-377">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c9b00-378">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-379">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="c9b00-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="c9b00-380">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c9b00-381">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="c9b00-381">FastTrack responsibilities</span></span>

<span data-ttu-id="c9b00-382">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-383">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="c9b00-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c9b00-384">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="c9b00-384">Your responsibilities</span></span>

<span data-ttu-id="c9b00-385">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-386">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="c9b00-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="c9b00-387">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="c9b00-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="c9b00-388">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="c9b00-389">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c9b00-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="c9b00-390">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="c9b00-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c9b00-391">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c9b00-392">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-392">You create and schedule your migration events.</span></span> <span data-ttu-id="c9b00-393">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="c9b00-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c9b00-394">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="c9b00-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="c9b00-395">Considerações</span><span class="sxs-lookup"><span data-stu-id="c9b00-395">Considerations</span></span>

  - <span data-ttu-id="c9b00-396">Todas as migrações estão sujeitas a cotas do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="c9b00-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="c9b00-397">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c9b00-398">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="c9b00-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="c9b00-399">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c9b00-400">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="c9b00-400">Source environment details</span></span>

<span data-ttu-id="c9b00-401">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c9b00-402">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="c9b00-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c9b00-403">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="c9b00-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c9b00-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c9b00-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c9b00-405">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="c9b00-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c9b00-406">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="c9b00-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c9b00-407"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c9b00-408"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c9b00-409"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c9b00-410"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c9b00-411"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c9b00-412">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-413">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-413">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-414">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-415">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="c9b00-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c9b00-416">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="c9b00-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c9b00-417">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-418">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-419">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-419">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-420">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-420">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-421">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-421">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-422">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c9b00-423">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="c9b00-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c9b00-424">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c9b00-425">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c9b00-426">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="c9b00-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c9b00-427">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="c9b00-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c9b00-428">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-429">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="c9b00-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="c9b00-430">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="c9b00-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c9b00-431">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="c9b00-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c9b00-432">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="c9b00-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c9b00-433">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="c9b00-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c9b00-434">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="c9b00-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c9b00-435">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-436">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="c9b00-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c9b00-437">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="c9b00-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c9b00-438">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c9b00-439"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c9b00-440">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-441">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="c9b00-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c9b00-442">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-443">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-444">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-445">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-446">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-447">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-447">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-448">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-448">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-449">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-449">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-450">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-451">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="c9b00-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c9b00-452">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-453">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-454">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c9b00-455">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-456">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-457">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-458">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-459">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-460">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-461">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-462">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-463">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="c9b00-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c9b00-464">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="c9b00-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c9b00-465">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="c9b00-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c9b00-466">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="c9b00-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c9b00-467">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-468">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-469">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="c9b00-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c9b00-470">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-471">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c9b00-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c9b00-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c9b00-473">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-474">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-474">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-475">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-476">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-477">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-478">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-479">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-480">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-480">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-481">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-481">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-482">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-482">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-483">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-484">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="c9b00-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-485">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-486">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c9b00-487">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-488">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-489">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-490">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-491">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-492">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-493">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-494">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="c9b00-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c9b00-495">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="c9b00-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c9b00-496">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c9b00-497">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-498">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-499">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c9b00-500"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="c9b00-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c9b00-501">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="c9b00-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c9b00-502">Documentos</span><span class="sxs-lookup"><span data-stu-id="c9b00-502">Documents</span></span> </li>
<li> <span data-ttu-id="c9b00-503">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="c9b00-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c9b00-504">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-505">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-506">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="c9b00-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c9b00-507">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="c9b00-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c9b00-508">Data de criação</span><span class="sxs-lookup"><span data-stu-id="c9b00-508">Created date</span></span> </li>
<li> <span data-ttu-id="c9b00-509">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="c9b00-509">Modified date</span></span> </li>
<li> <span data-ttu-id="c9b00-510">Criado por</span><span class="sxs-lookup"><span data-stu-id="c9b00-510">Created by</span></span> </li>
<li> <span data-ttu-id="c9b00-511">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="c9b00-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c9b00-512">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="c9b00-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c9b00-513">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="c9b00-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c9b00-514">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="c9b00-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c9b00-515">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="c9b00-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c9b00-516">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="c9b00-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-517">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="c9b00-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c9b00-518">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="c9b00-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c9b00-519">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="c9b00-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c9b00-520">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="c9b00-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c9b00-521">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="c9b00-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="c9b00-522">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="c9b00-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c9b00-523">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="c9b00-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c9b00-524">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="c9b00-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c9b00-525">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="c9b00-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c9b00-526">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="c9b00-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c9b00-527">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="c9b00-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c9b00-528">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="c9b00-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c9b00-529">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="c9b00-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c9b00-530">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c9b00-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c9b00-531">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="c9b00-531">FastTrack responsibilities</span></span>

<span data-ttu-id="c9b00-532">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-533">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c9b00-534">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="c9b00-534">Your responsibilities</span></span>

<span data-ttu-id="c9b00-535">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c9b00-536">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="c9b00-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c9b00-537">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="c9b00-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="c9b00-538">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="c9b00-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

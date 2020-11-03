---
title: Migração de dados
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827642"
---
# <a name="data-migration"></a><span data-ttu-id="5fe80-104">Migração de dados</span><span class="sxs-lookup"><span data-stu-id="5fe80-104">Data Migration</span></span>

<span data-ttu-id="5fe80-105">O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="5fe80-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="5fe80-106">O tipo de assistência que fornecemos depende do número de licenças do Office 365:</span><span class="sxs-lookup"><span data-stu-id="5fe80-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="5fe80-107">**Os locatários do Office 365 com as licenças 150-499** : Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="5fe80-108">Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.</span><span class="sxs-lookup"><span data-stu-id="5fe80-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="5fe80-109">**Os locatários do Office 365 com a 500 ou mais licenças** : FastTrack fornece diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="5fe80-110">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="5fe80-111">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-111">You create and schedule your migration events.</span></span> <span data-ttu-id="5fe80-112">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="5fe80-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="5fe80-113">Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="5fe80-114">Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="5fe80-115">Considerações</span><span class="sxs-lookup"><span data-stu-id="5fe80-115">Considerations</span></span>

  - <span data-ttu-id="5fe80-116">Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="5fe80-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="5fe80-117">Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="5fe80-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="5fe80-118">Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="5fe80-119">Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais.</span><span class="sxs-lookup"><span data-stu-id="5fe80-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="5fe80-120">À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).</span><span class="sxs-lookup"><span data-stu-id="5fe80-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="5fe80-121">Não podemos garantir a velocidade de migração emails ou arquivos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="5fe80-122">Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="5fe80-123">Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="5fe80-124">Disponibilidade do serviço de migração</span><span class="sxs-lookup"><span data-stu-id="5fe80-124">Migration service availability</span></span>

  - <span data-ttu-id="5fe80-125">**Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="5fe80-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="5fe80-126">**Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="5fe80-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="5fe80-127">Migração para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="5fe80-127">Migration to Exchange Online</span></span>

<span data-ttu-id="5fe80-128">Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5fe80-129">Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio.</span><span class="sxs-lookup"><span data-stu-id="5fe80-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="5fe80-130">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-130">You create and schedule your migration events.</span></span> <span data-ttu-id="5fe80-131">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="5fe80-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5fe80-132">Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5fe80-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="5fe80-133">Considerações</span><span class="sxs-lookup"><span data-stu-id="5fe80-133">Considerations</span></span>

  - <span data-ttu-id="5fe80-134">Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="5fe80-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="5fe80-135">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="5fe80-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5fe80-136">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="5fe80-137">O FastTrack migra apenas para caixas de correio do Office 365 ativas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="5fe80-138">Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="5fe80-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5fe80-139">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="5fe80-140">Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="5fe80-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="5fe80-141">Se as listas de distribuição (objetos *MailEnabledGroup* ) e contatos externos ( *objetos MailEnabledContact* ) estão no Active Directory local não fazem parte da migração de dado da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="5fe80-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="5fe80-142">No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="5fe80-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="5fe80-143">Ambientes de origem</span><span class="sxs-lookup"><span data-stu-id="5fe80-143">Source environments</span></span>

<span data-ttu-id="5fe80-144">Nosso serviço de migração de dados migra os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="5fe80-145">Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="5fe80-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="5fe80-146">Um ambiente de email único compatível com IMAP.</span><span class="sxs-lookup"><span data-stu-id="5fe80-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="5fe80-147">Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</span><span class="sxs-lookup"><span data-stu-id="5fe80-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="5fe80-148">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5fe80-149"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5fe80-150"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5fe80-151"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="5fe80-152"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5fe80-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="5fe80-154">
<strong>Observação:</strong> Para dependências do Exchange local, confira <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">pré-requisitos de implantação híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="5fe80-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="5fe80-155">Migração com implantação híbrida</span><span class="sxs-lookup"><span data-stu-id="5fe80-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="5fe80-156">Emails</span><span class="sxs-lookup"><span data-stu-id="5fe80-156">Emails</span></span></li>
<li><span data-ttu-id="5fe80-157">Regras de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="5fe80-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="5fe80-158">Representantes</span><span class="sxs-lookup"><span data-stu-id="5fe80-158">Delegates</span></span></li>
<li><span data-ttu-id="5fe80-159">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="5fe80-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5fe80-160">Calendário</span><span class="sxs-lookup"><span data-stu-id="5fe80-160">Calendar</span></span> </li>
<li> <span data-ttu-id="5fe80-161">Tarefas</span><span class="sxs-lookup"><span data-stu-id="5fe80-161">Tasks</span></span> </li>
<li> <span data-ttu-id="5fe80-162">Emails gerenciados por direitos</span><span class="sxs-lookup"><span data-stu-id="5fe80-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="5fe80-163">Emails criptografados</span><span class="sxs-lookup"><span data-stu-id="5fe80-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="5fe80-164">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="5fe80-164">Signatures</span></span> </li>
<li> <span data-ttu-id="5fe80-165">Arquivo morto pessoal migrado com caixas de correio de usuários</span><span class="sxs-lookup"><span data-stu-id="5fe80-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="5fe80-166">Itens recuperáveis</span><span class="sxs-lookup"><span data-stu-id="5fe80-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-167">Pastas públicas</span><span class="sxs-lookup"><span data-stu-id="5fe80-167">Public folders</span></span> </li>
<li> <span data-ttu-id="5fe80-168">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="5fe80-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5fe80-169">Arquivo morto de registro em diário ou solução de arquivo morto de terceiros</span><span class="sxs-lookup"><span data-stu-id="5fe80-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="5fe80-170">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-171">Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal)</span><span class="sxs-lookup"><span data-stu-id="5fe80-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="5fe80-172">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5fe80-173">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="5fe80-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5fe80-174"><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="5fe80-175">
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">perform a G Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="5fe80-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="5fe80-176">De substituição ou em fases</span><span class="sxs-lookup"><span data-stu-id="5fe80-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-177">Emails</span><span class="sxs-lookup"><span data-stu-id="5fe80-177">Emails</span></span> </li>
<li> <span data-ttu-id="5fe80-178">Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados)</span><span class="sxs-lookup"><span data-stu-id="5fe80-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="5fe80-179">Calendário</span><span class="sxs-lookup"><span data-stu-id="5fe80-179">Calendar</span></span> </li>
<li> <span data-ttu-id="5fe80-180">Rótulos</span><span class="sxs-lookup"><span data-stu-id="5fe80-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-181">Regras</span><span class="sxs-lookup"><span data-stu-id="5fe80-181">Rules</span></span> </li>
<li> <span data-ttu-id="5fe80-182">Representantes</span><span class="sxs-lookup"><span data-stu-id="5fe80-182">Delegates</span></span> </li>
<li> <span data-ttu-id="5fe80-183">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="5fe80-183">Signatures</span></span> </li>
<li> <span data-ttu-id="5fe80-184">Tarefas</span><span class="sxs-lookup"><span data-stu-id="5fe80-184">Tasks</span></span> </li>
<li> <span data-ttu-id="5fe80-185">Todos os emails ou anexos que excedem o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="5fe80-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5fe80-186">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-187">Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="5fe80-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="5fe80-188">Direitos gerenciados ou emails criptografados</span><span class="sxs-lookup"><span data-stu-id="5fe80-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="5fe80-189">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5fe80-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="5fe80-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="5fe80-191">Grupos do Google</span><span class="sxs-lookup"><span data-stu-id="5fe80-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="5fe80-192">Caixas de correio de recurso</span><span class="sxs-lookup"><span data-stu-id="5fe80-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="5fe80-193">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="5fe80-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="5fe80-194">Configurações de férias e configurações de resposta automática</span><span class="sxs-lookup"><span data-stu-id="5fe80-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="5fe80-195">Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento</span><span class="sxs-lookup"><span data-stu-id="5fe80-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="5fe80-196">\*\*As conversas do Hangout salvas como rótulo são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5fe80-197"><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="5fe80-198">Migração usando ferramentas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="5fe80-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="5fe80-199">Emails</span><span class="sxs-lookup"><span data-stu-id="5fe80-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="5fe80-200">Regras</span><span class="sxs-lookup"><span data-stu-id="5fe80-200">Rules</span></span> </li>
<li> <span data-ttu-id="5fe80-201">Representantes</span><span class="sxs-lookup"><span data-stu-id="5fe80-201">Delegates</span></span> </li>
<li> <span data-ttu-id="5fe80-202">Listas de distribuição</span><span class="sxs-lookup"><span data-stu-id="5fe80-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="5fe80-203">Contatos externos</span><span class="sxs-lookup"><span data-stu-id="5fe80-203">External contacts</span></span> </li>
<li> <span data-ttu-id="5fe80-204">Usuários habilitados para email</span><span class="sxs-lookup"><span data-stu-id="5fe80-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="5fe80-205">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-206">Contatos de caixas de correio</span><span class="sxs-lookup"><span data-stu-id="5fe80-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5fe80-207">Calendário</span><span class="sxs-lookup"><span data-stu-id="5fe80-207">Calendar</span></span> </li>
<li> <span data-ttu-id="5fe80-208">Assinaturas</span><span class="sxs-lookup"><span data-stu-id="5fe80-208">Signatures</span></span> </li>
<li> <span data-ttu-id="5fe80-209">Tarefas</span><span class="sxs-lookup"><span data-stu-id="5fe80-209">Tasks</span></span> </li>
<li> <span data-ttu-id="5fe80-210">Qualquer email que excede o limite de tamanho da mensagem</span><span class="sxs-lookup"><span data-stu-id="5fe80-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5fe80-211">Dados de arquivo morto</span><span class="sxs-lookup"><span data-stu-id="5fe80-211">Archive data</span></span> </li>
<li> <span data-ttu-id="5fe80-212">Email criptografado</span><span class="sxs-lookup"><span data-stu-id="5fe80-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="5fe80-213">Itens corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5fe80-214">Caixas de correio inativas</span><span class="sxs-lookup"><span data-stu-id="5fe80-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5fe80-215">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="5fe80-215">FastTrack responsibilities</span></span>

<span data-ttu-id="5fe80-216">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-217">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5fe80-218">Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="5fe80-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="5fe80-219">Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="5fe80-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5fe80-220">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="5fe80-220">Your responsibilities</span></span>

<span data-ttu-id="5fe80-221">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-222">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5fe80-223">Você também realiza as seguintes atividades, específicas das migrações do Exchange:</span><span class="sxs-lookup"><span data-stu-id="5fe80-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="5fe80-224">Concluir a integração principal do FastTrack para o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5fe80-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="5fe80-225">Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários.</span><span class="sxs-lookup"><span data-stu-id="5fe80-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5fe80-226">Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="5fe80-227">Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365.</span><span class="sxs-lookup"><span data-stu-id="5fe80-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="5fe80-228">Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="5fe80-229">Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local.</span><span class="sxs-lookup"><span data-stu-id="5fe80-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5fe80-230">Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="5fe80-231">Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="5fe80-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="5fe80-232">Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="5fe80-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="5fe80-233">Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino.</span><span class="sxs-lookup"><span data-stu-id="5fe80-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="5fe80-234">Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.</span><span class="sxs-lookup"><span data-stu-id="5fe80-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="5fe80-235">Migrar dados do lado do cliente se desejar.</span><span class="sxs-lookup"><span data-stu-id="5fe80-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="5fe80-236">Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.</span><span class="sxs-lookup"><span data-stu-id="5fe80-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="5fe80-237">Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="5fe80-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="5fe80-238">Migração para o SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="5fe80-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="5fe80-239">Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5fe80-240">Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5fe80-241">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-241">You create and schedule your migration events.</span></span> <span data-ttu-id="5fe80-242">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="5fe80-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5fe80-243">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="5fe80-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="5fe80-244">Considerações</span><span class="sxs-lookup"><span data-stu-id="5fe80-244">Considerations</span></span>

  - <span data-ttu-id="5fe80-245">Todas as migrações estão sujeitas a cotas do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="5fe80-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="5fe80-246">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="5fe80-247">É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="5fe80-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="5fe80-248">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="5fe80-248">Source environment details</span></span>

<span data-ttu-id="5fe80-249">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5fe80-250">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="5fe80-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5fe80-251">Um único ambiente do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5fe80-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5fe80-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5fe80-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5fe80-253">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="5fe80-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5fe80-254">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5fe80-255"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5fe80-256"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5fe80-257"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5fe80-258"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5fe80-259"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5fe80-260">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-261">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-262">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-263">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="5fe80-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5fe80-264">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="5fe80-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5fe80-265">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-266">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-267">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-267">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-268">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-268">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-269">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-269">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-270">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="5fe80-271">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="5fe80-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5fe80-272">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5fe80-273">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5fe80-274">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-275">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="5fe80-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5fe80-276">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-277">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="5fe80-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="5fe80-278">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="5fe80-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5fe80-279">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="5fe80-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5fe80-280">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="5fe80-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5fe80-281">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="5fe80-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5fe80-282">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="5fe80-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5fe80-283">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-284">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="5fe80-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5fe80-285">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="5fe80-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5fe80-286">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5fe80-287"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5fe80-288">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-289">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB</span><span class="sxs-lookup"><span data-stu-id="5fe80-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="5fe80-290">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-291">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-292">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-293">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-294">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-295">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-295">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-296">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-296">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-297">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-297">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-298">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-299">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="5fe80-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5fe80-300">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-301">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-302">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5fe80-303">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-304">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-305">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-306">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-307">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-308">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-309">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-310">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-311">Google Fotos, Formulários, Mapas e outras aplicações conectadas</span><span class="sxs-lookup"><span data-stu-id="5fe80-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5fe80-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="5fe80-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5fe80-313">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="5fe80-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5fe80-314">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="5fe80-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5fe80-315">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-316">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-317">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="5fe80-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5fe80-318">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-319">Arquivos marcados como restritos ou não copiados</span><span class="sxs-lookup"><span data-stu-id="5fe80-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="5fe80-320">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5fe80-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5fe80-322">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-323">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-323">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-324">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-325">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-326">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-327">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-328">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-329">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-329">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-330">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-330">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-331">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-331">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-332">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-333">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="5fe80-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-334">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-335">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5fe80-336">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-337">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-338">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-339">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-340">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-341">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-342">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-343">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-344">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="5fe80-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5fe80-345">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5fe80-346">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-347">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-348">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5fe80-349"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="5fe80-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5fe80-350">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-351">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-351">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-352">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-353">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-354">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-355">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-356">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-357">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-357">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-358">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-358">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-359">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-359">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-360">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-361">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="5fe80-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5fe80-362">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="5fe80-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-363">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-364">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5fe80-365">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-366">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-367">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-368">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-369">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-370">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-371">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-372">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="5fe80-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5fe80-373">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="5fe80-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5fe80-374">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="5fe80-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5fe80-375">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="5fe80-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5fe80-376">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5fe80-377">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-378">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração)</span><span class="sxs-lookup"><span data-stu-id="5fe80-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="5fe80-379">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5fe80-380">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="5fe80-380">FastTrack responsibilities</span></span>

<span data-ttu-id="5fe80-381">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-382">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="5fe80-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5fe80-383">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="5fe80-383">Your responsibilities</span></span>

<span data-ttu-id="5fe80-384">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-385">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes</span><span class="sxs-lookup"><span data-stu-id="5fe80-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="5fe80-386">Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="5fe80-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="5fe80-387">Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="5fe80-388">Migração para o OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="5fe80-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="5fe80-389">Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados.</span><span class="sxs-lookup"><span data-stu-id="5fe80-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5fe80-390">Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5fe80-391">Você cria e agenda seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-391">You create and schedule your migration events.</span></span> <span data-ttu-id="5fe80-392">Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.</span><span class="sxs-lookup"><span data-stu-id="5fe80-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5fe80-393">Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="5fe80-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="5fe80-394">Considerações</span><span class="sxs-lookup"><span data-stu-id="5fe80-394">Considerations</span></span>

  - <span data-ttu-id="5fe80-395">Todas as migrações estão sujeitas a cotas do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="5fe80-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="5fe80-396">Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="5fe80-397">É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).</span><span class="sxs-lookup"><span data-stu-id="5fe80-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="5fe80-398">O FastTrack migra apenas para o unidades do OneDrive for Business ativas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="5fe80-399">Detalhes do ambiente de origem</span><span class="sxs-lookup"><span data-stu-id="5fe80-399">Source environment details</span></span>

<span data-ttu-id="5fe80-400">Nossos serviços de migração de dados migram os dados desses ambientes de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5fe80-401">Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).</span><span class="sxs-lookup"><span data-stu-id="5fe80-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5fe80-402">Ambiente único do G Suite (apenas Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5fe80-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5fe80-403">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5fe80-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5fe80-404">Dropbox para equipes (Padrão e Avançado).</span><span class="sxs-lookup"><span data-stu-id="5fe80-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5fe80-405">A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:</span><span class="sxs-lookup"><span data-stu-id="5fe80-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="5fe80-406"><strong>Ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="5fe80-407"><strong>Tipo de migração</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="5fe80-408"><strong>O que migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5fe80-409"><strong>O que não migra</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5fe80-410"><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5fe80-411">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-412">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-412">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-413">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-414">Permissões de arquivo e pasta no nível do usuário\*</span><span class="sxs-lookup"><span data-stu-id="5fe80-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5fe80-415">Permissões de arquivo e pasta no nível do grupo\*</span><span class="sxs-lookup"><span data-stu-id="5fe80-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5fe80-416">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-417">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-418">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-418">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-419">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-419">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-420">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-420">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-421">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="5fe80-422">\*Configuração de sincronização de diretório necessária.</span><span class="sxs-lookup"><span data-stu-id="5fe80-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5fe80-423">Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5fe80-424">As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5fe80-425">Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</span><span class="sxs-lookup"><span data-stu-id="5fe80-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="5fe80-426">Histórico de propriedade e versões anteriores</span><span class="sxs-lookup"><span data-stu-id="5fe80-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5fe80-427">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-428">Versões anteriores</span><span class="sxs-lookup"><span data-stu-id="5fe80-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="5fe80-429">Atributos de arquivos e pastas do Windows (como somente leitura e oculto)</span><span class="sxs-lookup"><span data-stu-id="5fe80-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5fe80-430">Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:</span><span class="sxs-lookup"><span data-stu-id="5fe80-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5fe80-431">Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)</span><span class="sxs-lookup"><span data-stu-id="5fe80-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5fe80-432">Configuração de auditoria do NTFS</span><span class="sxs-lookup"><span data-stu-id="5fe80-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5fe80-433">Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)</span><span class="sxs-lookup"><span data-stu-id="5fe80-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5fe80-434">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-435">Compartilhamentos ocultos</span><span class="sxs-lookup"><span data-stu-id="5fe80-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5fe80-436">Compartilhamento (como permissões concedidas no nível de compartilhamento)</span><span class="sxs-lookup"><span data-stu-id="5fe80-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5fe80-437">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5fe80-438"><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5fe80-439">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-440">Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="5fe80-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="5fe80-441">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-442">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-443">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-444">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-445">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-446">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-446">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-447">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-447">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-448">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-448">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-449">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-450">Unidades compartilhadas (pastas e arquivos)</span><span class="sxs-lookup"><span data-stu-id="5fe80-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5fe80-451">Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-452">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-453">Descrições de arquivos e pastas, cores de pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5fe80-454">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-455">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-456">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-457">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-458">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-459">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-460">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-461">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-462">Google Fotos, Formulários, Mapas e outros aplicativos conectados</span><span class="sxs-lookup"><span data-stu-id="5fe80-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5fe80-463">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="5fe80-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5fe80-464">Conteúdo compartilhado externo à sua organização</span><span class="sxs-lookup"><span data-stu-id="5fe80-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5fe80-465">O conteúdo que está sendo migrado não pertencente à conta Google Drive</span><span class="sxs-lookup"><span data-stu-id="5fe80-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5fe80-466">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-467">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-468">Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive.</span><span class="sxs-lookup"><span data-stu-id="5fe80-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5fe80-469">Instrua os usuários finais a definir essas configurações de associação no destino antes da migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-470">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5fe80-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5fe80-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5fe80-472">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-473">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-473">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-474">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-475">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-476">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-477">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-478">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-479">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-479">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-480">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-480">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-481">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-481">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-482">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-483">Conteúdo compartilhado de propriedade da conta do Box está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="5fe80-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-484">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-485">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5fe80-486">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-487">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-488">Box Tags e metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-489">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-490">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-491">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-492">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-493">Usuários bloqueados ou inativos</span><span class="sxs-lookup"><span data-stu-id="5fe80-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5fe80-494">Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho</span><span class="sxs-lookup"><span data-stu-id="5fe80-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5fe80-495">O conteúdo não pertence à conta do Box migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5fe80-496">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-497">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-498">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5fe80-499"><strong>Dropbox para equipes (Padrão e Avançado)</strong> </span><span class="sxs-lookup"><span data-stu-id="5fe80-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5fe80-500">Uma ou várias passagens</span><span class="sxs-lookup"><span data-stu-id="5fe80-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5fe80-501">Documentos</span><span class="sxs-lookup"><span data-stu-id="5fe80-501">Documents</span></span> </li>
<li> <span data-ttu-id="5fe80-502">Estrutura de arquivo e pasta</span><span class="sxs-lookup"><span data-stu-id="5fe80-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5fe80-503">Permissões da pasta para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-504">Permissões da pasta para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-505">Arquivos com menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="5fe80-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5fe80-506">Metadados básicos de documentos e pastas:</span><span class="sxs-lookup"><span data-stu-id="5fe80-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5fe80-507">Data de criação</span><span class="sxs-lookup"><span data-stu-id="5fe80-507">Created date</span></span> </li>
<li> <span data-ttu-id="5fe80-508">Data de modificação</span><span class="sxs-lookup"><span data-stu-id="5fe80-508">Modified date</span></span> </li>
<li> <span data-ttu-id="5fe80-509">Criado por</span><span class="sxs-lookup"><span data-stu-id="5fe80-509">Created by</span></span> </li>
<li> <span data-ttu-id="5fe80-510">Última modificação por</span><span class="sxs-lookup"><span data-stu-id="5fe80-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5fe80-511">Pastas e conteúdos compartilhados pela equipe</span><span class="sxs-lookup"><span data-stu-id="5fe80-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5fe80-512">Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado</span><span class="sxs-lookup"><span data-stu-id="5fe80-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5fe80-513">Histórico de propriedade, versões anteriores e comentários</span><span class="sxs-lookup"><span data-stu-id="5fe80-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5fe80-514">Descrições de arquivos e pastas</span><span class="sxs-lookup"><span data-stu-id="5fe80-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5fe80-515">Permissões do arquivo para o nível do Usuário</span><span class="sxs-lookup"><span data-stu-id="5fe80-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-516">Permissões do arquivo para o nível do Grupo</span><span class="sxs-lookup"><span data-stu-id="5fe80-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5fe80-517">Metadados avançados</span><span class="sxs-lookup"><span data-stu-id="5fe80-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5fe80-518">Atributos de bloqueio de arquivo</span><span class="sxs-lookup"><span data-stu-id="5fe80-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5fe80-519">Conversão de URLs incorporados em conteúdo</span><span class="sxs-lookup"><span data-stu-id="5fe80-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5fe80-520">Itens na lixeira</span><span class="sxs-lookup"><span data-stu-id="5fe80-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="5fe80-521">Documentos inacessíveis ou corrompidos</span><span class="sxs-lookup"><span data-stu-id="5fe80-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5fe80-522">Pastas Dropbox não montadas</span><span class="sxs-lookup"><span data-stu-id="5fe80-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5fe80-523">Usuários excluídos ou desconectados</span><span class="sxs-lookup"><span data-stu-id="5fe80-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5fe80-524">Dropbox Paper, Showcases e Spaces</span><span class="sxs-lookup"><span data-stu-id="5fe80-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5fe80-525">Dropbox Aplicativos e Favoritos (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="5fe80-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5fe80-526">O conteúdo não pertence à conta Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="5fe80-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5fe80-527">Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos.</span><span class="sxs-lookup"><span data-stu-id="5fe80-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5fe80-528">Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração).</span><span class="sxs-lookup"><span data-stu-id="5fe80-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5fe80-529">Arquivos ou pastas que excedem as <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restrições e limitações atuais do SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="5fe80-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5fe80-530">Responsabilidades do FastTrack</span><span class="sxs-lookup"><span data-stu-id="5fe80-530">FastTrack responsibilities</span></span>

<span data-ttu-id="5fe80-531">Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-532">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5fe80-533">Suas responsabilidades</span><span class="sxs-lookup"><span data-stu-id="5fe80-533">Your responsibilities</span></span>

<span data-ttu-id="5fe80-534">Você realiza atividades padrão durante o projeto de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5fe80-535">Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.</span><span class="sxs-lookup"><span data-stu-id="5fe80-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5fe80-536">Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="5fe80-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="5fe80-537">Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.</span><span class="sxs-lookup"><span data-stu-id="5fe80-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

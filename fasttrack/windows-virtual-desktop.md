---
title: Área de Trabalho Virtual do Windows
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: O FastTrack fornece Windows diretrizes de implantação da Área de Trabalho Virtual para ajudá-lo a entrar nessa área de trabalho.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592434"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="bba65-103">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="bba65-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bba65-104"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="bba65-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="bba65-105"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="bba65-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="bba65-106"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="bba65-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bba65-107">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="bba65-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="bba65-108">O FastTrack fornece Windows diretrizes de implantação da Área de Trabalho Virtual para ajudá-lo a integrar esse serviço de virtualização de aplicativos e área de trabalho com facilidade enquanto aproveita Windows 10 experiência de várias sessões, otimizada para Microsoft 365 Apps para Enterprise com segurança e gerenciamento integrados para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bba65-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="bba65-109">Você trabalha com especialistas do FastTrack para:</span><span class="sxs-lookup"><span data-stu-id="bba65-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-110">Implante o ambiente WVD com Windows 10 Enterprise de várias sessões + Microsoft 365 Apps para Enterprise usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="bba65-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-111">Imagem do Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="bba65-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="bba65-112">Imagem Compartilhada</span><span class="sxs-lookup"><span data-stu-id="bba65-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="bba65-113">Office Implantação Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="bba65-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="bba65-114">Configurar FSLogix</span><span class="sxs-lookup"><span data-stu-id="bba65-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-115">Implantar agente FSLogix com contêiner de perfil</span><span class="sxs-lookup"><span data-stu-id="bba65-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="bba65-116">Implantar o Agente FSLogix com Office Contêiner</span><span class="sxs-lookup"><span data-stu-id="bba65-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="bba65-117">Configurar pasta FSLogix com exclusões de conteúdo</span><span class="sxs-lookup"><span data-stu-id="bba65-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="bba65-118">Implantar o Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="bba65-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="bba65-119">Implantar Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="bba65-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="bba65-120">Conexão usando Windows de Área de Trabalho Virtual</span><span class="sxs-lookup"><span data-stu-id="bba65-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="bba65-121"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="bba65-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-122">Project gerenciamento da implantação da Área de Trabalho Virtual do cliente Windows.</span><span class="sxs-lookup"><span data-stu-id="bba65-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="bba65-123">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="bba65-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="bba65-124">Virtualização/implantação de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="bba65-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="bba65-125">Imagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="bba65-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="bba65-126">Migrações e cenários envolvendo VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="bba65-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="bba65-127">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="bba65-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="bba65-128">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="bba65-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="bba65-129">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="bba65-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="bba65-130">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="bba65-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="bba65-131">Requisitos de licenciamento WVD</span><span class="sxs-lookup"><span data-stu-id="bba65-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="bba65-132">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="bba65-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-133">Sub-rede de criação de VNET &amp;</span><span class="sxs-lookup"><span data-stu-id="bba65-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="bba65-134">Grupos de segurança de rede/firewall</span><span class="sxs-lookup"><span data-stu-id="bba65-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="bba65-135">VPN /ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="bba65-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="bba65-136">Roteamento para o Azure no local</span><span class="sxs-lookup"><span data-stu-id="bba65-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="bba65-137">Regras de firewall para permitir a conectividade com o WVD</span><span class="sxs-lookup"><span data-stu-id="bba65-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="bba65-138">Referência de Documentos</span><span class="sxs-lookup"><span data-stu-id="bba65-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="bba65-139">Azure Active Directory Instalação geral</span><span class="sxs-lookup"><span data-stu-id="bba65-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-140">Estratégia de <strong>Identidade (Selecione APENAS 1 das 3 opções a seguir)</strong></span><span class="sxs-lookup"><span data-stu-id="bba65-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="bba65-141">Active Directory com o Azure AD Conexão no Azure</span><span class="sxs-lookup"><span data-stu-id="bba65-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="bba65-142">Active Directory com o Azure AD Conexão local sobre VPN/ER</span><span class="sxs-lookup"><span data-stu-id="bba65-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="bba65-143">Serviços de Domínio do Active Directory</span><span class="sxs-lookup"><span data-stu-id="bba65-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

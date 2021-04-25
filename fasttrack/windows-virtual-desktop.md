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
description: O FastTrack fornece diretrizes de implantação da Área de Trabalho Virtual do Windows para ajudá-lo a entrar nessa área de trabalho.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996229"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="40442-103">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="40442-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="40442-104"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="40442-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="40442-105"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="40442-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="40442-106"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="40442-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="40442-107">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="40442-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="40442-108">O FastTrack fornece diretrizes de implantação da Área de Trabalho Virtual do Windows para ajudá-lo a integrar esse serviço de virtualização de aplicativos e área de trabalho com facilidade ao aproveitar a experiência de várias sessões do Windows 10, otimizada para o Microsoft 365 Apps for Enterprise com segurança e gerenciamento integrados para o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="40442-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="40442-109">Você trabalha com especialistas do FastTrack para:</span><span class="sxs-lookup"><span data-stu-id="40442-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-110">Implantar o ambiente WVD com o Windows 10 Enterprise com várias sessões + Aplicativos do Microsoft 365 para Empresas usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="40442-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-111">Imagem do Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="40442-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="40442-112">Imagem Compartilhada</span><span class="sxs-lookup"><span data-stu-id="40442-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="40442-113">Office Deployment Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="40442-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="40442-114">Configurar FSLogix</span><span class="sxs-lookup"><span data-stu-id="40442-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-115">Implantar agente FSLogix com contêiner de perfil</span><span class="sxs-lookup"><span data-stu-id="40442-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="40442-116">Implantar agente FSLogix com contêiner do Office</span><span class="sxs-lookup"><span data-stu-id="40442-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="40442-117">Configurar pasta FSLogix com exclusões de conteúdo</span><span class="sxs-lookup"><span data-stu-id="40442-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="40442-118">Implantar o Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="40442-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="40442-119">Implantar o Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="40442-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="40442-120">Conectar-se usando clientes da Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="40442-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="40442-121"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="40442-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="40442-122">Gerenciamento de projetos da implantação da Área de Trabalho Virtual do Cliente.</span><span class="sxs-lookup"><span data-stu-id="40442-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="40442-123">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="40442-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="40442-124">Virtualização/implantação de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="40442-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="40442-125">Imagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="40442-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="40442-126">Migrações e cenários envolvendo VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="40442-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="40442-127">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="40442-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="40442-128">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="40442-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="40442-129">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="40442-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="40442-130">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="40442-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento WVD</a></span><span class="sxs-lookup"><span data-stu-id="40442-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="40442-132">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="40442-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-133">Sub-rede de criação de VNET &amp;</span><span class="sxs-lookup"><span data-stu-id="40442-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="40442-134">Grupos de segurança de rede/firewall</span><span class="sxs-lookup"><span data-stu-id="40442-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="40442-135">VPN /ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="40442-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="40442-136">Roteamento para o Azure no local</span><span class="sxs-lookup"><span data-stu-id="40442-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="40442-137">Regras de firewall para permitir a conectividade com o WVD</span><span class="sxs-lookup"><span data-stu-id="40442-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Referência de Documentos</a></span><span class="sxs-lookup"><span data-stu-id="40442-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="40442-139">Instalação geral do Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="40442-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="40442-140">Estratégia de <strong>Identidade (Selecione APENAS 1 das 3 opções a seguir)</strong></span><span class="sxs-lookup"><span data-stu-id="40442-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="40442-141">Active Directory com o Azure AD Connect no Azure</span><span class="sxs-lookup"><span data-stu-id="40442-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="40442-142">Active Directory com o Azure AD Connect On Premise sobre VPN/ER</span><span class="sxs-lookup"><span data-stu-id="40442-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="40442-143">Serviços de Domínio do Active Directory</span><span class="sxs-lookup"><span data-stu-id="40442-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

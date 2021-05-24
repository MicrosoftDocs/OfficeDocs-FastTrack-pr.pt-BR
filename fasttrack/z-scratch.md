---
title: Segurança e Conformidade
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: Detalhes de orientação do FastTrack para serviços Microsoft.
ms.openlocfilehash: 67dd428de8a8f48e0d52e4f6c6daf85cbd27ec76
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592388"
---
# <a name="security-and-compliance"></a><span data-ttu-id="12411-103">Segurança e Conformidade</span><span class="sxs-lookup"><span data-stu-id="12411-103">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="12411-104"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="12411-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="12411-105"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="12411-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="12411-106"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="12411-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="12411-107"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="12411-107"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="12411-108">Microsoft 365 O Defender é um pacote de defesa empresarial de pré e pós-violação unificado que coordena a detecção, a prevenção, a investigação e a resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="12411-108">Microsoft 365 Defender is a unified pre and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="12411-109">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-109">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="12411-110">Fornecendo uma visão geral do centro Microsoft 365 segurança.</span><span class="sxs-lookup"><span data-stu-id="12411-110">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="12411-111">Revisão de incidentes entre produtos, incluindo o foco no que é crítico, garantindo o escopo de ataque completo, os ativos afetados e as ações de correção automatizadas agrupadas.</span><span class="sxs-lookup"><span data-stu-id="12411-111">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="12411-112">Demonstrando como Microsoft 365 Defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidas por meio da auto-recuperação automatizada.</span><span class="sxs-lookup"><span data-stu-id="12411-112">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="12411-113">Explicando e fornecendo exemplos de como os clientes podem procurar proativamente tentativas de invasão e atividades de violação que afetam seu email, dados, dispositivos e contas em vários conjuntos de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-113">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="12411-114">Mostrando aos clientes como eles podem revisar e melhorar a postura de segurança de forma holística usando a Pontuação Segura da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="12411-114">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="12411-115"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="12411-115"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="12411-116">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="12411-116">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="12411-117">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="12411-117">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="12411-118">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="12411-118">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="12411-119">Como remediar ou interpretar os vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="12411-119">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="12411-120">Como investigar um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="12411-120">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="12411-121">Busca personalizada de ameaças.</span><span class="sxs-lookup"><span data-stu-id="12411-121">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="12411-122">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API.</span><span class="sxs-lookup"><span data-stu-id="12411-122">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="12411-123"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="12411-123"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="12411-124">Microsoft Cloud App Security é um Agente de Segurança do Cloud Access (CASB) que fornece visibilidade avançada, controle sobre viagens de dados e análises sofisticadas para identificar e combater ameaças cibernéticas em todos os serviços de nuvem da Microsoft e de terceiros.</span><span class="sxs-lookup"><span data-stu-id="12411-124">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="12411-125">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-125">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="12411-126">Configurando o portal, incluindo:</span><span class="sxs-lookup"><span data-stu-id="12411-126">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="12411-127">Importando grupos de usuários.</span><span class="sxs-lookup"><span data-stu-id="12411-127">Importing user groups.</span></span></li>
<li> <span data-ttu-id="12411-128">Gerenciando o acesso e as configurações do administrador.</span><span class="sxs-lookup"><span data-stu-id="12411-128">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="12411-129">Scoping sua implantação para selecionar determinados grupos de usuários para monitorar ou excluir do monitoramento.</span><span class="sxs-lookup"><span data-stu-id="12411-129">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="12411-130">Definindo intervalos e marcas IP.</span><span class="sxs-lookup"><span data-stu-id="12411-130">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="12411-131">Personalizando a experiência do usuário final com seu logotipo e mensagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="12411-131">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="12411-132">Configurando a descoberta na nuvem para fornecer a tecnologia de sombra usando:</span><span class="sxs-lookup"><span data-stu-id="12411-132">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="12411-133">Microsoft Defender para Pontos de Extremidade.</span><span class="sxs-lookup"><span data-stu-id="12411-133">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="12411-134">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="12411-134">Zscaler.</span></span></li>
<li> <span data-ttu-id="12411-135">iboss.</span><span class="sxs-lookup"><span data-stu-id="12411-135">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="12411-136">Conectando [aplicativos em destaque](/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps) usando conectores de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="12411-136">Connecting [featured apps](/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps) using app connectors.</span></span></li>
<li> <span data-ttu-id="12411-137">Configurando o Controle de Aplicativo de Acesso Condicional nos portais de acesso condicional e Cloud App Security para aplicar controles de sessão em tempo real.</span><span class="sxs-lookup"><span data-stu-id="12411-137">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="12411-138">Implantando os painéis Cloud App Security e Descoberta de Nuvem.</span><span class="sxs-lookup"><span data-stu-id="12411-138">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="12411-139">Personalização de pontuações de risco de aplicativo com base nas prioridades da sua organização.</span><span class="sxs-lookup"><span data-stu-id="12411-139">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="12411-140">Criando marcas e categorias de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="12411-140">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="12411-141">Sancionando e desemanando aplicativos.</span><span class="sxs-lookup"><span data-stu-id="12411-141">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="12411-142">Usando a atividade e os logs de arquivo.</span><span class="sxs-lookup"><span data-stu-id="12411-142">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="12411-143">Gerenciando aplicativos OAuth.</span><span class="sxs-lookup"><span data-stu-id="12411-143">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="12411-144">Noções básicas sobre a correlação de incidentes no portal Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="12411-144">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="12411-145">Fornecendo assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> principais casos de uso para CASBs (incluindo a criação ou atualização de até seis (6) políticas), exceto:</span><span class="sxs-lookup"><span data-stu-id="12411-145">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="12411-146">Auditoria da configuração da internet como ambientes de serviço (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="12411-146">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="12411-147">Monitorando as atividades do usuário para proteger contra ameaças em seus ambientes iaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="12411-147">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="12411-148"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="12411-148"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="12411-149">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="12411-149">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="12411-150">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="12411-150">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="12411-151">Configurando a infraestrutura, a instalação ou a implantação de carregamentos de log automáticos para relatórios contínuos usando o Docker ou um coletor de log.</span><span class="sxs-lookup"><span data-stu-id="12411-151">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="12411-152">Confira <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Os 20 principais casos de uso para CASBs</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="12411-152">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="12411-153">Criando um relatório de instantâneo de Descoberta na Nuvem.</span><span class="sxs-lookup"><span data-stu-id="12411-153">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="12411-154">Bloqueando o uso do aplicativo usando scripts de bloqueio.</span><span class="sxs-lookup"><span data-stu-id="12411-154">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="12411-155">Conectando aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="12411-155">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="12411-156">Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção contra perda de dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="12411-156">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="12411-157">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="12411-157">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="12411-158">Investigação e correção automatizadas, incluindo o Microsoft Power Automate playbooks.</span><span class="sxs-lookup"><span data-stu-id="12411-158">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="12411-159">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="12411-159">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="12411-160">Implantando Cloud App Security como prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="12411-160">Deploying Cloud App Security as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="odd">
<td><span data-ttu-id="12411-161"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="12411-161"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="12411-162">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="12411-162">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="12411-163">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-163">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="12411-164">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="12411-164">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="12411-165">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="12411-165">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="12411-166">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="12411-166">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="12411-167">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="12411-167">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="12411-168">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="12411-168">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="12411-169">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="12411-169">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="12411-170">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="12411-170">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-171">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="12411-171">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-172">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="12411-172">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-173">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="12411-173">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-174">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="12411-174">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-175">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="12411-175">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-176">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="12411-176">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="12411-177">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="12411-177">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="12411-178">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="12411-178">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="12411-179">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="12411-179">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="12411-180">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="12411-180">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="12411-181">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="12411-181">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-182">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="12411-182">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-183">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="12411-183">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-184">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="12411-184">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-185">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="12411-185">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-186">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="12411-186">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-187">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="12411-187">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="12411-188">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="12411-188">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="12411-189"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="12411-189"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="12411-190">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="12411-190">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="12411-191">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="12411-191">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="12411-192">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="12411-192">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="12411-193">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="12411-193">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-194">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="12411-194">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-195">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="12411-195">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-196">Linux.</span><span class="sxs-lookup"><span data-stu-id="12411-196">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-197">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="12411-197">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="12411-198">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="12411-198">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-199">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="12411-199">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-200">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="12411-200">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-201">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="12411-201">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-202">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="12411-202">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="12411-203">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="12411-203">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-204">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="12411-204">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-205">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="12411-205">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="12411-206">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="12411-206">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-207">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="12411-207">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="12411-208">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="12411-208">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="12411-209">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="12411-209">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-210">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="12411-210">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-211">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="12411-211">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="12411-212">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="12411-212">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="12411-213">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="12411-213">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="12411-214">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="12411-214">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="12411-215">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="12411-215">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="12411-216">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="12411-216">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="12411-217">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="12411-217">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="12411-218">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="12411-218">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="12411-219"><strong>Microsoft Defender para Identidade </strong></span><span class="sxs-lookup"><span data-stu-id="12411-219"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="12411-220">O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização.</span><span class="sxs-lookup"><span data-stu-id="12411-220">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="12411-221">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-221">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="12411-222">Criando sua instância do Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="12411-222">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="12411-223">Conectando o Defender para Identidade ao Active Directory.</span><span class="sxs-lookup"><span data-stu-id="12411-223">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="12411-224">Avaliando a preparação do seu ambiente para implantar o sensor Defender for Identity em seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="12411-224">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="12411-225">Executando a ferramenta de sizing para planejamento de capacidade de recursos.</span><span class="sxs-lookup"><span data-stu-id="12411-225">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="12411-226">Executando a ferramenta de auditoria para avaliar a compatibilidade dos controladores de domínio com o sensor.</span><span class="sxs-lookup"><span data-stu-id="12411-226">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="12411-227">Implantando o sensor para capturar e analisar o tráfego de rede e Windows eventos diretamente de seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="12411-227">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="12411-228">Baixando o pacote do sensor.</span><span class="sxs-lookup"><span data-stu-id="12411-228">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="12411-229">Configurando o sensor.</span><span class="sxs-lookup"><span data-stu-id="12411-229">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="12411-230">Instalando o sensor no controlador de domínio silenciosamente.</span><span class="sxs-lookup"><span data-stu-id="12411-230">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="12411-231">Implantando o sensor em seu ambiente de várias florestas.</span><span class="sxs-lookup"><span data-stu-id="12411-231">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="12411-232">Integrando o Defender para Identidade com Microsoft Cloud App Security (Cloud App Security licenciamento não é necessário).</span><span class="sxs-lookup"><span data-stu-id="12411-232">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="12411-233">Fornecendo diretrizes de implantação, assistência de configuração e educação em:</span><span class="sxs-lookup"><span data-stu-id="12411-233">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="12411-234">Ajustando o ambiente para reduzir "ruído".</span><span class="sxs-lookup"><span data-stu-id="12411-234">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="12411-235">Noções básicas sobre o relatório de avaliação de postura de segurança de identidade.</span><span class="sxs-lookup"><span data-stu-id="12411-235">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="12411-236">Noções básicas sobre a pontuação de prioridade de investigação do usuário e o relatório de classificação de investigação do usuário.</span><span class="sxs-lookup"><span data-stu-id="12411-236">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="12411-237">Noções básicas sobre o relatório do usuário inativo.</span><span class="sxs-lookup"><span data-stu-id="12411-237">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="12411-238">Fornecendo opções de correção em uma conta comprometida.</span><span class="sxs-lookup"><span data-stu-id="12411-238">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="12411-239">Facilitando a migração do Advanced Threat Analytics (ATA) para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="12411-239">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="12411-240"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="12411-240"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="12411-241">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="12411-241">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="12411-242">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="12411-242">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="12411-243">Implantando o sensor Defender para Identidade, incluindo:</span><span class="sxs-lookup"><span data-stu-id="12411-243">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="12411-244">Planejamento de capacidade manual.</span><span class="sxs-lookup"><span data-stu-id="12411-244">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="12411-245">Implantando o sensor em uma capacidade autônoma.</span><span class="sxs-lookup"><span data-stu-id="12411-245">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="12411-246">Implantando o sensor usando um adaptador de NIC (Network Interface Card).</span><span class="sxs-lookup"><span data-stu-id="12411-246">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="12411-247">Implantando o sensor por meio de uma ferramenta de terceiros.</span><span class="sxs-lookup"><span data-stu-id="12411-247">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="12411-248">Conectando-se ao serviço de nuvem Defender para Identidade por meio de uma conexão de proxy da Web.</span><span class="sxs-lookup"><span data-stu-id="12411-248">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="12411-249">Criação e gerenciamento de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="12411-249">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="12411-250">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="12411-250">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="12411-251">Correção ou interpretação de vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="12411-251">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="12411-252">Investigando um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="12411-252">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="12411-253">Ameaça ou busca avançada.</span><span class="sxs-lookup"><span data-stu-id="12411-253">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="12411-254">Resposta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="12411-254">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="12411-255">Fornecendo um tutorial do laboratório de alertas de segurança para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="12411-255">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="12411-256">Fornecer notificação quando o Defender for Identity detecta atividades suspeitas enviando alertas de segurança para seu servidor de syslog por meio de um sensor nomeado.</span><span class="sxs-lookup"><span data-stu-id="12411-256">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="12411-257">Configurar o Defender para Identidade para realizar consultas usando o protocolo SAMR (gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="12411-257">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="12411-258">Configurando soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.</span><span class="sxs-lookup"><span data-stu-id="12411-258">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="12411-259">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="12411-259">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="12411-260">Implantando sensores defender para identidade como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="12411-260">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="12411-261">Active Directory implantado.</span><span class="sxs-lookup"><span data-stu-id="12411-261">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="12411-262">Os controladores de domínio que você pretende instalar os sensores do Defender para Identidade têm conectividade com a Internet para o serviço de nuvem defender para identidade.</span><span class="sxs-lookup"><span data-stu-id="12411-262">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="12411-263">Seu firewall e proxy devem estar abertos para se comunicar com o serviço de nuvem Defender for Identity (\*.atp.azure.com porta 443 deve estar aberta).</span><span class="sxs-lookup"><span data-stu-id="12411-263">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="12411-264">Controladores de domínio em execução em um dos seguintes:</span><span class="sxs-lookup"><span data-stu-id="12411-264">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="12411-265">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="12411-265">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="12411-266">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="12411-266">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="12411-267">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="12411-267">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="12411-268">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="12411-268">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="12411-269">Windows Server 2019 com KB4487044 (com build do sistema operacional 17763.316).</span><span class="sxs-lookup"><span data-stu-id="12411-269">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="12411-270"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="12411-270"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="12411-271">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="12411-272">Rótulos e diretivas de retenção.</span><span class="sxs-lookup"><span data-stu-id="12411-272">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="12411-273">Gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="12411-273">Records management.</span></span>  </li>
<li>  <span data-ttu-id="12411-274">Diretivas de exclusão.</span><span class="sxs-lookup"><span data-stu-id="12411-274">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="12411-275">Conformidade da comunicação.</span><span class="sxs-lookup"><span data-stu-id="12411-275">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="12411-276">Gerenciamento de risco interno.</span><span class="sxs-lookup"><span data-stu-id="12411-276">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="12411-277">Descoberta Eletrônica Avançada.</span><span class="sxs-lookup"><span data-stu-id="12411-277">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="12411-278">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="12411-278">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="12411-279">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="12411-279">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="12411-280">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-280">Data connectors.</span></span></li>
<li> <span data-ttu-id="12411-281">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="12411-281">Information barriers.</span></span></li>
<li> <span data-ttu-id="12411-282">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="12411-282">Privileged access management.</span></span></li>
<li> <span data-ttu-id="12411-283">Desenvolvimento da arquitetura de informações em SharePoint.</span><span class="sxs-lookup"><span data-stu-id="12411-283">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="12411-284">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="12411-284">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="12411-285">Com exceção da parte <strong>Central de integração</strong> em <a href="products-and-capabilities.md#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="12411-285">Aside from the <strong>Core onboarding</strong> portion in <a href="products-and-capabilities.md#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="12411-286"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="12411-286"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="12411-287">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-287">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="12411-288">Classificação de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-288">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="12411-289">Tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="12411-289">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="12411-290">Criação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="12411-290">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="12411-291">Aplicando rótulos de sensibilidade.</span><span class="sxs-lookup"><span data-stu-id="12411-291">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="12411-292">Rotulagem unificada.</span><span class="sxs-lookup"><span data-stu-id="12411-292">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="12411-293">Classificadores treináveis.</span><span class="sxs-lookup"><span data-stu-id="12411-293">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="12411-294">Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.</span><span class="sxs-lookup"><span data-stu-id="12411-294">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="12411-295">Publicar etiquetas usando políticas (manual e automática).</span><span class="sxs-lookup"><span data-stu-id="12411-295">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="12411-296">Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="12411-296">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="12411-297">Criando políticas de DLP de ponto de extremidade para Windows 10 dispositivos.</span><span class="sxs-lookup"><span data-stu-id="12411-297">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="12411-298">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="12411-298">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="12411-299">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="12411-299">Customer key.</span></span></li>
<li><span data-ttu-id="12411-300">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="12411-300">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="12411-301">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="12411-301">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="12411-302">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="12411-302">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="12411-303">
<strong>Observação:</strong> Para obter mais informações, consulte <strong>Proteção de Informações do Azure</strong> em <a href="products-and-capabilities.md#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="12411-303">
<strong>Note:</strong> For more information, see <strong>Azure Information Protection</strong> in <a href="products-and-capabilities.md#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="12411-304">Com exceção da parte <strong>Central de integração</strong> em <a href="products-and-capabilities.md#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="12411-304">Aside from the <strong>Core onboarding</strong> portion in <a href="products-and-capabilities.md#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="12411-305"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="12411-305"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="12411-306">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-306">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="12411-307">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="12411-307">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="12411-308">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="12411-308">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="12411-309">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="12411-309">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="12411-310">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="12411-310">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="12411-311">Com exceção da parte <strong>Central de integração</strong> em <a href="products-and-capabilities.md#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="12411-311">Aside from the <strong>Core onboarding</strong> portion in <a href="products-and-capabilities.md#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="odd">
<td><span data-ttu-id="12411-312"><strong>Resposta & descoberta</strong></span><span class="sxs-lookup"><span data-stu-id="12411-312"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="12411-313"><strong>Advanced eDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="12411-313"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="12411-314">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="12411-314">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="12411-315">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="12411-315">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="12411-316">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="12411-316">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="12411-317">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="12411-317">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="12411-318"><strong>Auditoria Avançada</strong> (com suporte apenas no E5)</span><span class="sxs-lookup"><span data-stu-id="12411-318"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="12411-319">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-319">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="12411-320">Habilitando a auditoria avançada.</span><span class="sxs-lookup"><span data-stu-id="12411-320">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="12411-321">Executando uma interface do usuário do log de auditoria de pesquisa e comandos básicos de auditoria do PowerShell.</span><span class="sxs-lookup"><span data-stu-id="12411-321">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="12411-322">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="12411-322">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="12411-323">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-323">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="12411-324">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="12411-324">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="12411-325">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="12411-325">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="12411-326">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="12411-326">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="12411-327">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="12411-327">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="12411-328">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="12411-328">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="12411-329">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="12411-329">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="12411-330">Scripts personalizados ou codificação.</span><span class="sxs-lookup"><span data-stu-id="12411-330">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="12411-331">API de Descoberta Externa.</span><span class="sxs-lookup"><span data-stu-id="12411-331">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="12411-332">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-332">Data connectors.</span></span> </li>
<li> <span data-ttu-id="12411-333">Limites de conformidade e filtros de segurança.</span><span class="sxs-lookup"><span data-stu-id="12411-333">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="12411-334">Investigações de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-334">Data investigations.</span></span></li>
<li> <span data-ttu-id="12411-335">Solicitações de assunto de dados.</span><span class="sxs-lookup"><span data-stu-id="12411-335">Data subject requests.</span></span></li>
<li> <span data-ttu-id="12411-336">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="12411-336">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="12411-337">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="12411-337">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="12411-338">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="12411-338">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="12411-339">Com exceção da parte <strong>Central de integração</strong> em <a href="products-and-capabilities.md#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="12411-339">Aside from the <strong>Core onboarding</strong> portion in <a href="products-and-capabilities.md#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="12411-340"><strong>Gerenciamento de ameaças insider</strong></span><span class="sxs-lookup"><span data-stu-id="12411-340"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="12411-341">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-341">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="12411-342">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="12411-342">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="12411-343">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="12411-343">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="12411-344">Criar casos.</span><span class="sxs-lookup"><span data-stu-id="12411-344">Creating cases.</span></span></li>
<li> <span data-ttu-id="12411-345">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="12411-345">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="12411-346">Diretrizes sobre a criação do conector de recursos humanos (RH).</span><span class="sxs-lookup"><span data-stu-id="12411-346">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="12411-347">

<strong> Conformidade de comunicação </strong></span><span class="sxs-lookup"><span data-stu-id="12411-347">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="12411-348">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-348">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="12411-349">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="12411-349">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="12411-350">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="12411-350">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="12411-351">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="12411-351">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="12411-352">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="12411-352">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="12411-353">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="12411-353">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="12411-354">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="12411-354">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="12411-355">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="12411-355">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="12411-356">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="12411-356">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="12411-357">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="12411-357">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="12411-358">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="12411-358">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="12411-359">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="12411-359">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="12411-360">Criando e gerenciando Power Automate fluxos.</span><span class="sxs-lookup"><span data-stu-id="12411-360">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="12411-361">Conectores de dados (além do conector de RH).</span><span class="sxs-lookup"><span data-stu-id="12411-361">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="12411-362">Configurações de expressão regular personalizada (RegEx).</span><span class="sxs-lookup"><span data-stu-id="12411-362">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="12411-363">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="12411-363">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="12411-364">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="12411-364">Information barriers.</span></span></li>
<li> <span data-ttu-id="12411-365">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="12411-365">Privileged access management.</span></span></li>
<li> <span data-ttu-id="12411-366">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="12411-366">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="12411-367">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="12411-367">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="12411-368">Com exceção da parte <strong>Central de integração</strong> em <a href="products-and-capabilities.md#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="12411-368">Aside from the <strong>Core onboarding</strong> portion in <a href="products-and-capabilities.md#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


</tbody>
</table>












</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><span data-ttu-id="12411-369"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="12411-369"><strong>Service</strong></span></span></TD>
<TD width 50%><span data-ttu-id="12411-370"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="12411-370"><strong>FastTrack guidance details</strong></span></span></TD>
<TD width 25%><span data-ttu-id="12411-371"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="12411-371"><strong>Source environment expectations</strong></span></span></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>
---
title: Produtos e Recursos
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800963"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="80eda-104">Produtos e Recursos</span><span class="sxs-lookup"><span data-stu-id="80eda-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="80eda-105">Serviços e cenários com suportados pelo FastTrack</span><span class="sxs-lookup"><span data-stu-id="80eda-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="80eda-106">Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar.</span><span class="sxs-lookup"><span data-stu-id="80eda-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="80eda-107">Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="80eda-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="80eda-108">O FastTrack fornece orientações para ajudá-lo primeiro com os principais recursos (comuns para todos os serviços online da Microsoft) e, em seguida, com a integração de cada serviço qualificado:</span><span class="sxs-lookup"><span data-stu-id="80eda-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="80eda-109">Geral</span><span class="sxs-lookup"><span data-stu-id="80eda-109">General</span></span>](#general)
  - [<span data-ttu-id="80eda-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="80eda-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="80eda-111">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="80eda-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="80eda-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="80eda-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="80eda-113">Garantia de Aplicativo</span><span class="sxs-lookup"><span data-stu-id="80eda-113">App Assure</span></span>](Win-10-app-assure.md)
  - [<span data-ttu-id="80eda-114">O novo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="80eda-114">The new Microsoft Edge</span></span>](Win-10-microsoft-edge.md)

> [!NOTE]
> <span data-ttu-id="80eda-115">Para saber mais sobre as expectativas de ambiente de origem do Office 365 para o Governo norte-americano, confira  [Expectativas de Ambiente de Origem do Office 365 para o Governo norte-americano](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="80eda-115">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="80eda-116">Geral</span><span class="sxs-lookup"><span data-stu-id="80eda-116">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="80eda-117"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-117"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="80eda-118"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-118"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="80eda-119"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-119"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="80eda-120"><strong>Integração principal</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-120"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="80eda-121">Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário.</span><span class="sxs-lookup"><span data-stu-id="80eda-121">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="80eda-122">Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-122">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="80eda-123">A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.</span><span class="sxs-lookup"><span data-stu-id="80eda-123">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="80eda-124"></li>
</ul>  

<strong>Integração de identidade</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-124"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="80eda-125">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-125">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="80eda-126">Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</span><span class="sxs-lookup"><span data-stu-id="80eda-126">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="80eda-127">Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</span><span class="sxs-lookup"><span data-stu-id="80eda-127">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="80eda-128">Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</span><span class="sxs-lookup"><span data-stu-id="80eda-128">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="80eda-129">Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="80eda-129">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="80eda-130">Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="80eda-130">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="80eda-131">Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</span><span class="sxs-lookup"><span data-stu-id="80eda-131">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="80eda-132">Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</span><span class="sxs-lookup"><span data-stu-id="80eda-132">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="80eda-133">Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-133">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="80eda-134">Habilitar o provisionamento automático do usuário para aplicativos SaaS pré-integrados, como listados na <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Lista de tutoriais de integração de aplicativos</a>, (limitado apenas ao provisionamento de saída e de aplicativos SaaS da galeria do Azure AD).</span><span class="sxs-lookup"><span data-stu-id="80eda-134">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="80eda-135"><strong>Habilitação de rede </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="80eda-135"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="80eda-136">Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-136">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="80eda-137"><strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:</span><span class="sxs-lookup"><span data-stu-id="80eda-137"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-138">Uma única floresta do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="80eda-138">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="80eda-139">Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="80eda-139">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-140">Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="80eda-140">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-141">Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="80eda-141">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="80eda-142">Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.</span><span class="sxs-lookup"><span data-stu-id="80eda-142">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="80eda-143">Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.   </span><span class="sxs-lookup"><span data-stu-id="80eda-143">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="80eda-144">
  <strong>Importante:</strong>  </span><span class="sxs-lookup"><span data-stu-id="80eda-144">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="80eda-145">Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.</span><span class="sxs-lookup"><span data-stu-id="80eda-145">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="80eda-146">Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis.</span><span class="sxs-lookup"><span data-stu-id="80eda-146">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="80eda-147">Namespaces SMTP primários entre organizações do Exchange também devem ser separados.</span><span class="sxs-lookup"><span data-stu-id="80eda-147">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="80eda-148">Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-148">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="80eda-149">Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo.</span><span class="sxs-lookup"><span data-stu-id="80eda-149">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="80eda-150">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="80eda-150">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-151"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-151"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="80eda-152">Fornecemos orientações de implantação remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-152">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-153">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="80eda-153">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="80eda-154">Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="80eda-154">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="80eda-155">Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="80eda-155">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="80eda-156">Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="80eda-156">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="80eda-157">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-157">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="80eda-158">Seleção e configuração de uma instalação local ou na nuvem.</span><span class="sxs-lookup"><span data-stu-id="80eda-158">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="80eda-159">Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.</span><span class="sxs-lookup"><span data-stu-id="80eda-159">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="80eda-160">Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="80eda-160">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="80eda-161">Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo.</span><span class="sxs-lookup"><span data-stu-id="80eda-161">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="80eda-162">Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="80eda-162">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="80eda-163">O software do cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-163">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-164"><strong>Integridade da rede</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-164"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="80eda-165">Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-165">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="80eda-166">Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.</span><span class="sxs-lookup"><span data-stu-id="80eda-166">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="80eda-167">Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.</span><span class="sxs-lookup"><span data-stu-id="80eda-167">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="80eda-168">Acesso ao Centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-168">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="80eda-169">São necessárias versões atualizadas dos aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-169">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="80eda-170">Serviços de localização habilitados conforme as <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-170">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="80eda-171">Office 365</span><span class="sxs-lookup"><span data-stu-id="80eda-171">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="80eda-172"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-172"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="80eda-173"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-173"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="80eda-174"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-174"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="80eda-175"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-175"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="80eda-176">Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email.</span><span class="sxs-lookup"><span data-stu-id="80eda-176">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="80eda-177">As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.</span><span class="sxs-lookup"><span data-stu-id="80eda-177">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="80eda-178">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-178">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-179">Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-179">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-180">Apontar seus registros de troca de mensagens (MX) para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-180">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-181">Configurar o recurso do Office 365 ATP se ele fizer parte do seu serviço de assinatura.</span><span class="sxs-lookup"><span data-stu-id="80eda-181">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="80eda-182">Para mais informações, veja a parte dessa tabela <strong>Proteção Avançada contra Ameaças do Office 365</strong>.</span><span class="sxs-lookup"><span data-stu-id="80eda-182">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="80eda-p113">Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="80eda-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="80eda-p114">Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="80eda-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="80eda-187">
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-187">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="80eda-188">A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="80eda-188">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="80eda-189">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="80eda-189">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="80eda-190">Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).</span><span class="sxs-lookup"><span data-stu-id="80eda-190">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="80eda-191">Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).</span><span class="sxs-lookup"><span data-stu-id="80eda-191">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="80eda-192">Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-192">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-193">Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="80eda-193">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="80eda-194">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="80eda-194">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="80eda-195">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-195">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="80eda-196">Seu ambiente de origem deve ter um dos seguintes níveis mínimos:</span><span class="sxs-lookup"><span data-stu-id="80eda-196">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-197">Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.</span><span class="sxs-lookup"><span data-stu-id="80eda-197">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="80eda-198">Um único ambiente de email compatível com o protocolo IMAP.</span><span class="sxs-lookup"><span data-stu-id="80eda-198">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="80eda-199">Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).</span><span class="sxs-lookup"><span data-stu-id="80eda-199">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="80eda-200">Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-200">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="80eda-201">O software de cliente online, como o Project para Office 365, o Outlook para Windows, o Outlook para iOS e Android, o cliente de sincronização do OneDrive for Business, o Power BI Desktop e o Skype for Business, deve estar em um nível mínimo, conforme definido nos  <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema do Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-201">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-202"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-202"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="80eda-203">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-203">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-204">Governança de Informações.</span><span class="sxs-lookup"><span data-stu-id="80eda-204">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="80eda-205">Rótulos e diretivas de retenção.</span><span class="sxs-lookup"><span data-stu-id="80eda-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-206">Gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="80eda-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="80eda-207">Diretivas de exclusão.</span><span class="sxs-lookup"><span data-stu-id="80eda-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-208">Conformidade da comunicação.</span><span class="sxs-lookup"><span data-stu-id="80eda-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="80eda-209">Gerenciamento de risco interno.</span><span class="sxs-lookup"><span data-stu-id="80eda-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="80eda-210">Descoberta Eletrônica Avançada.</span><span class="sxs-lookup"><span data-stu-id="80eda-210">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-211">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="80eda-211">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-212"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-212"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="80eda-213">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-213">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-214">Classificação de dados.</span><span class="sxs-lookup"><span data-stu-id="80eda-214">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="80eda-215">Tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="80eda-215">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="80eda-216">Criação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-216">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="80eda-217">Aplicação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-217">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="80eda-218">Rotulagem unificada.</span><span class="sxs-lookup"><span data-stu-id="80eda-218">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="80eda-219">Classificadores treináveis.</span><span class="sxs-lookup"><span data-stu-id="80eda-219">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="80eda-220">Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.</span><span class="sxs-lookup"><span data-stu-id="80eda-220">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="80eda-221">Publicar etiquetas usando políticas (manual e automática).</span><span class="sxs-lookup"><span data-stu-id="80eda-221">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="80eda-222">Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="80eda-222">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-223">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="80eda-223">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-224"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-224"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="80eda-225">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-225">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-226">Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.</span><span class="sxs-lookup"><span data-stu-id="80eda-226">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="80eda-227">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="80eda-227">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="80eda-228">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="80eda-228">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="80eda-229">Confirmação da habilitação do Teams no seu locatário do Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-229">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="80eda-230">Habilitação ou desabilitação de licenças de usuário.</span><span class="sxs-lookup"><span data-stu-id="80eda-230">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="80eda-231">Avaliação Rede para o Teams:</span><span class="sxs-lookup"><span data-stu-id="80eda-231">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-232">Verificações de porta e de ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-232">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="80eda-233">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="80eda-233">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="80eda-234">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="80eda-234">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="80eda-235">Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="80eda-235">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="80eda-236">Se aplicável, também forneceremos diretrizes para:</span><span class="sxs-lookup"><span data-stu-id="80eda-236">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-237">Dispositivos para a Sala do Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="80eda-237">Microsoft Teams Room Devices:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="80eda-238">Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no  <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos do Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-238">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="80eda-239">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="80eda-239">Enabling Audio Conferencing:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="80eda-240">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="80eda-240">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="80eda-241">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-241">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="80eda-242">Sistema de Telefonia:</span><span class="sxs-lookup"><span data-stu-id="80eda-242">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-243">Configuração da organização para as configurações padrão do Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="80eda-243">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="80eda-244">Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):</span><span class="sxs-lookup"><span data-stu-id="80eda-244">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="80eda-245">Atribuição de números a usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-245">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="80eda-246">Orientação de portabilidade do número local pela IU (interface do usuário) até 999.</span><span class="sxs-lookup"><span data-stu-id="80eda-246">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="80eda-247">Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.</span><span class="sxs-lookup"><span data-stu-id="80eda-247">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-248">Diretrizes de Roteamento Direto:</span><span class="sxs-lookup"><span data-stu-id="80eda-248">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-249">Guia de configuração da organização para o design de Roteamento Direto de cenários hospedados pelo parceiro ou cenários implantados pelo cliente para um site único.</span><span class="sxs-lookup"><span data-stu-id="80eda-249">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for a single site.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="80eda-250">Habilitação dos eventos ao vivo do Teams.</span><span class="sxs-lookup"><span data-stu-id="80eda-250">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="80eda-251">Configuração e integração da organização com o Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="80eda-251">Organization setup and integration into Microsoft Stream.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="80eda-252">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-252">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-253">Usuários habilitados para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-253">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="80eda-254">Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).</span><span class="sxs-lookup"><span data-stu-id="80eda-254">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="80eda-255">Habilitado para Grupos do Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-255">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="80eda-256">
  <strong>Observação:</strong> Se os usuários não estiverem atribuídos e habilitados com licenças do SharePoint Online, eles não terão armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-256">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="80eda-257">O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-257">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="80eda-258">O Teams não oferece suporte para o SharePoint no local.</span><span class="sxs-lookup"><span data-stu-id="80eda-258">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="80eda-259">
  <strong>Observação:</strong>  O estado ideal é que todos os usuários tenham suas caixas de correio hospedadas no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-259">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="80eda-260">Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect.</span><span class="sxs-lookup"><span data-stu-id="80eda-260">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="80eda-261">Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.</span><span class="sxs-lookup"><span data-stu-id="80eda-261">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="80eda-262">Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-262">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-263"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="80eda-264">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-264">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-265">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="80eda-265">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="80eda-266">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="80eda-266">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="80eda-267">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="80eda-267">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="80eda-268">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="80eda-268">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-269">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="80eda-269">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-270"><strong>Outlook para iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-270"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="80eda-271">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-272">Baixe o Outlook para iOS e Android no Google Play e Apple App Store.</span><span class="sxs-lookup"><span data-stu-id="80eda-272">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="80eda-273">Configurar contas e acessar a caixa de correio do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-273">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="80eda-274">Proteger o Outlook Mobile (para obter mais informações, confira <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).</span><span class="sxs-lookup"><span data-stu-id="80eda-274">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="80eda-275">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-275">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-276">Exchange Online configurado e licenças atribuídas.</span><span class="sxs-lookup"><span data-stu-id="80eda-276">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-277"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-277"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="80eda-278">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-279">Atribuição de licenças do Power BI.</span><span class="sxs-lookup"><span data-stu-id="80eda-279">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="80eda-280">Implantação do aplicativo do Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="80eda-280">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-281">O software do cliente online, como o Power BI Desktop, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-281">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-282"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-282"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="80eda-283">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-283">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-284">Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.</span><span class="sxs-lookup"><span data-stu-id="80eda-284">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="80eda-285">Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.</span><span class="sxs-lookup"><span data-stu-id="80eda-285">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="80eda-286">Configurar o ERP (Pool de Recursos da Empresa).</span><span class="sxs-lookup"><span data-stu-id="80eda-286">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="80eda-287">Criando seu primeiro projeto.</span><span class="sxs-lookup"><span data-stu-id="80eda-287">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-288">O software do cliente online, como o Project para Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-288">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-289"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-289"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="80eda-290">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-291">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="80eda-291">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="80eda-292">Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="80eda-292">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="80eda-293">Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="80eda-293">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="80eda-294">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-294">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="80eda-295">Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-295">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="80eda-296">Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="80eda-296">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-297">O software do cliente online, como o Project para Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-297">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-298"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-298"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="80eda-299">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-299">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-300">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="80eda-300">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="80eda-301">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="80eda-301">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="80eda-302">Provisionar usuários e licenças.</span><span class="sxs-lookup"><span data-stu-id="80eda-302">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="80eda-303">Habilitar a criação de sites para o administrador do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-303">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="80eda-304">Planejamento de conjuntos de sites.</span><span class="sxs-lookup"><span data-stu-id="80eda-304">Planning site collections.</span></span></li>
<li><span data-ttu-id="80eda-305">Proteção de conteúdo e gerenciamento de permissões.</span><span class="sxs-lookup"><span data-stu-id="80eda-305">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="80eda-306">Configuração de recursos do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-306">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="80eda-307">Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.</span><span class="sxs-lookup"><span data-stu-id="80eda-307">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="80eda-308">Método de migração.</span><span class="sxs-lookup"><span data-stu-id="80eda-308">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="80eda-309">Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="80eda-309">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-310">Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.</span><span class="sxs-lookup"><span data-stu-id="80eda-310">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="80eda-311">Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="80eda-311">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="80eda-312">Planejar e implementar a distribuição única (ou em fases) para todos os usuários.</span><span class="sxs-lookup"><span data-stu-id="80eda-312">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="80eda-313">Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="80eda-313">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="80eda-314">Redirecionar ou mover pastas conhecidas para o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="80eda-314">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="80eda-315">Implantar o cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="80eda-315">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="80eda-316">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="80eda-316">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="80eda-317">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-317">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="80eda-318"><strong>Para o SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-318"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="80eda-319">A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-319">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="80eda-320">
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="80eda-320">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="80eda-321">Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.</span><span class="sxs-lookup"><span data-stu-id="80eda-321">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="80eda-322">
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo.</span><span class="sxs-lookup"><span data-stu-id="80eda-322">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="80eda-323">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="80eda-323">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="80eda-324">Confira mais informações em  <a href="https://go.microsoft.com/fwlink/?linkid=853548">Níveis mínimos de atualização pública dos recursos híbridos do SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="80eda-324">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="80eda-325">
  <strong>Observação:</strong> Para saber mais sobre Multi-Geo Capabilities, confira  <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities no OneDrive e no SharePoint Online no Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="80eda-325">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-326"><strong>Skype for Business Online</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-326"><strong>Skype for Business Online</strong></span></span></td>
<td>  <span data-ttu-id="80eda-327">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-328">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="80eda-328">Configuring firewall ports.</span></span>  </li>

<li>  <span data-ttu-id="80eda-329">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="80eda-329">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="80eda-330">Avaliação de rede:</span><span class="sxs-lookup"><span data-stu-id="80eda-330">Network assessment:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-331">Verificações de porta e de ponto de extremidade</span><span class="sxs-lookup"><span data-stu-id="80eda-331">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="80eda-332">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="80eda-332">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="80eda-333">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="80eda-333">Bandwidth estimates.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-334">Criar contas para dispositivos do sistema.</span><span class="sxs-lookup"><span data-stu-id="80eda-334">Creating accounts for any room system devices.</span></span>  </li>
<li>  <span data-ttu-id="80eda-335">Implantar um cliente Skype for Business online com suporte.</span><span class="sxs-lookup"><span data-stu-id="80eda-335">Deploying a supported Skype for Business Online client.</span></span>  </li>
<li>  <span data-ttu-id="80eda-336">Estabeleça a configuração do servidor de domínio dividido entre seu ambiente de servidor local do Lync 2010, Lync 2013 ou Skype for Business 2015 e o locatário do Skype for Business online (se aplicável), Planos de Chamada, Transmissão de Reunião do Skype e Sistema Telefônico e Planos de Chamada (em mercados disponíveis).</span><span class="sxs-lookup"><span data-stu-id="80eda-336">Establishing split domain server configuration between your on-premises Lync 2010, Lync 2013, or Skype for Business 2015 server environment and Skype for Business Online tenant (if applicable), Calling Plans, Skype Meeting Broadcast, and Phone System and Calling Plans (in available markets).</span></span>  
  <span data-ttu-id="80eda-337">Se for aplicável, o FastTrack também o orientará em:</span><span class="sxs-lookup"><span data-stu-id="80eda-337">If applicable, FastTrack also guides you through:</span></span>  </li>
<li>  <span data-ttu-id="80eda-338">Configurar o dispositivo do sistema de salas:</span><span class="sxs-lookup"><span data-stu-id="80eda-338">Configuring room system device:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-339">Criação de contas online necessárias para dispositivos de sala de conferência com suporte listados na guia Sistemas de sala de reunião, no  <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Catálogo de soluções do Skype for Business</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-339">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business solutions catalog</a>.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-340">Configurar servidores híbridos e de domínio dividido.</span><span class="sxs-lookup"><span data-stu-id="80eda-340">Configuring hybrid and split domain servers.</span></span>  </li>
<li>  <span data-ttu-id="80eda-341">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="80eda-341">Configuring Audio Conferencing:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-342">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="80eda-342">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="80eda-343">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-343">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-344">Configurações padrão do sistema de telefone:</span><span class="sxs-lookup"><span data-stu-id="80eda-344">Configuring Phone System default settings:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-345">Planos de chamadas:</span><span class="sxs-lookup"><span data-stu-id="80eda-345">Calling Plans:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-346">Atribuição de números à usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-346">Assignment of numbers to licenses users.</span></span>  </li>
<li>  <span data-ttu-id="80eda-347">Orientação de portabilidade do número local pela interface do usuário até 99</span><span class="sxs-lookup"><span data-stu-id="80eda-347">Local number porting guidance through user interface up to 99</span></span>  </li>
<li>  <span data-ttu-id="80eda-348">Suporte da solicitação de serviço à portabilidade do número local superior a 999</span><span class="sxs-lookup"><span data-stu-id="80eda-348">Local number porting service request support over 999</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="80eda-349">Configurar a Transmissão de Reunião do Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="80eda-349">Configure Skype for Business Meeting Broadcast:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-350">Configuração da organização para federação com o serviço de Transmissão de Reunião.</span><span class="sxs-lookup"><span data-stu-id="80eda-350">Organization setup for federation with Meeting Broadcast service.</span></span>  </li>
</ul></li>
</ul></td>
<td>  <span data-ttu-id="80eda-351"><strong>Para Lync híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-351"><strong>For Lync hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="80eda-352">Uma floresta única do Active Directory Domain Services local.</span><span class="sxs-lookup"><span data-stu-id="80eda-352">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="80eda-353">Um ambiente do Lync 2010 Server com ferramentas de administração do Lync 2013 ou do Skype for Business 2015 e uma função de servidor de borda do Lync 2010.</span><span class="sxs-lookup"><span data-stu-id="80eda-353">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  </li>
<li>  <span data-ttu-id="80eda-354">Um ambiente do Lync 2013 Server e uma função de servidor de borda do Lync 2013.</span><span class="sxs-lookup"><span data-stu-id="80eda-354">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  </li>
</ul><span data-ttu-id="80eda-355">
  <strong>Para Skype for Business híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-355">
  <strong>For Skype for Business hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="80eda-356">Uma floresta única do Active Directory Domain Services local.</span><span class="sxs-lookup"><span data-stu-id="80eda-356">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="80eda-357">Topologias de floresta única de conta do Active Directory progressiva e floresta de recursos (Exchange e/ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="80eda-357">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-358">Várias florestas de contas do Active Directory, sendo uma delas uma floresta do Active Directory centralizada com o Exchange e/ou o Skype for Business nela.</span><span class="sxs-lookup"><span data-stu-id="80eda-358">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  </li>
<li>  <span data-ttu-id="80eda-359">Um Ambiente do Server 2015 do Skype for Business, incluindo uma função de servidor de borda do Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="80eda-359">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  </li>
</ul><span data-ttu-id="80eda-360">
  <strong>Observação:</strong> Este serviço adicional é usado para configurar e validar as tarefas (híbridas) do domínio dividido e não inclui a introdução de componentes locais (por exemplo, ferramentas de administração do Lync 2013, servidores do Lync 2013/Skype for Business online, ou servidores de borda do Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="80eda-360">
  <strong>Note:</strong> This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-361"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-361"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="80eda-362">Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="80eda-362">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="80eda-363">O software do cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos de sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-363">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="80eda-364">Enterprise Mobility e Security</span><span class="sxs-lookup"><span data-stu-id="80eda-364">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-365"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-365"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="80eda-366">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="80eda-366">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="80eda-367">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="80eda-367">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="80eda-368">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="80eda-368">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="80eda-369">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="80eda-369">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="80eda-370">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="80eda-370">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="80eda-371">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="80eda-371">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="80eda-372">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="80eda-372">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="80eda-373">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="80eda-373">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="80eda-374">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="80eda-374">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="80eda-375">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-375">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="80eda-376">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="80eda-376">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="80eda-377">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="80eda-377">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="80eda-378">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-378">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="80eda-379">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-379">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="80eda-380">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="80eda-380">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="80eda-381">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-381">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="80eda-382">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-382">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="80eda-383">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-383">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-384">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-384">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-385">Gerenciar e controlar o acesso a contas privilegiadas com o Azure Active Directory Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="80eda-385">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="80eda-386">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-386">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="80eda-387">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="80eda-387">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="80eda-388">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-388">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="80eda-389">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-389">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="80eda-390">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-390">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="80eda-391">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="80eda-391">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="80eda-392">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="80eda-392">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="80eda-393"><strong>Proteção de Informações do Azure (P2 ou EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-393"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="80eda-394">Fornecemos orientações sobre como:</span><span class="sxs-lookup"><span data-stu-id="80eda-394">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-395">Ativar e configurar o locatário.</span><span class="sxs-lookup"><span data-stu-id="80eda-395">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="80eda-396">Criar e configurar rótulos e políticas.</span><span class="sxs-lookup"><span data-stu-id="80eda-396">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-397">Aplicação de proteção de informações aos documentos.</span><span class="sxs-lookup"><span data-stu-id="80eda-397">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="80eda-398">Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="80eda-398">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="80eda-399">Uso de arquivos em repouso com o scanner da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="80eda-399">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="80eda-400">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="80eda-400">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="80eda-401">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="80eda-401">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="80eda-402">Você já deve saber:</span><span class="sxs-lookup"><span data-stu-id="80eda-402">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-403">Usar o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-403">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="80eda-404">Usar o Windows ou o iOS (outros SOs estão fora do escopo).</span><span class="sxs-lookup"><span data-stu-id="80eda-404">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="80eda-405">
<strong>Observação</strong>: os computadores e dispositivos móveis devem ser executados em um <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operacional</a> que suporte a Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="80eda-405">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="80eda-406">Ter seus principais locais de compartilhamento de arquivos.</span><span class="sxs-lookup"><span data-stu-id="80eda-406">Have your main file share locations.</span></span>  </li><span data-ttu-id="80eda-407">
<strong>Observação</strong>: o suporte híbrido exige o conector AD RMS.</span><span class="sxs-lookup"><span data-stu-id="80eda-407">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="80eda-408">Ter uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="80eda-408">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="80eda-409">Entender as restrições normativas para o gerenciamento de chaves protegidas.</span><span class="sxs-lookup"><span data-stu-id="80eda-409">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="80eda-410">
</ul>
  
<strong>Scanner da Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-410">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="80eda-411">Você já deve saber:</span><span class="sxs-lookup"><span data-stu-id="80eda-411">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="80eda-412">Usar o Windows Server 2012 R2 ou o Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="80eda-412">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="80eda-413">Ter uma conexão à Internet.</span><span class="sxs-lookup"><span data-stu-id="80eda-413">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="80eda-414">Ter o Microsoft SQL Server 2012 em uma instância local ou remota.</span><span class="sxs-lookup"><span data-stu-id="80eda-414">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="80eda-415">Ter uma conta de serviço criada para o Active Directory local e sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-415">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="80eda-416">Ter baixado AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="80eda-416">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="80eda-417">Ter etiquetas configuradas para classificação/proteção automática.</span><span class="sxs-lookup"><span data-stu-id="80eda-417">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="80eda-418"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-418"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="80eda-419">Fornecemos orientações sobre como preparar-se para usar o Intune como o gerenciamento de dispositivo móvel baseado em nuvem (MDM) e o provedor de gerenciamento de aplicativo móvel (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="80eda-419">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="80eda-420">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="80eda-420">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="80eda-421">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="80eda-421">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-422">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="80eda-422">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="80eda-423">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="80eda-423">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="80eda-424">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="80eda-424">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="80eda-425">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="80eda-425">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-426">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="80eda-426">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-427">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="80eda-427">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-428">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="80eda-428">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-429">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="80eda-429">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-430">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="80eda-430">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="80eda-431">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="80eda-431">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-432">Implantação de email, redes sem fio e perfis VPN se tiver uma autoridade de certificação existente, uma infraestrutura de rede sem fio ou VPN em sua organização.</span><span class="sxs-lookup"><span data-stu-id="80eda-432">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="80eda-433">Configuração do Microsoft Intune Exchange Connector (quando aplicável).</span><span class="sxs-lookup"><span data-stu-id="80eda-433">Setting up the Microsoft Intune Exchange Connector (when applicable).</span></span>  </li>
<li>  <span data-ttu-id="80eda-434">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="80eda-434">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="80eda-435">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="80eda-435">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-436">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="80eda-436">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="80eda-437">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="80eda-437">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="80eda-438">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="80eda-438">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="80eda-439">Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="80eda-439">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-440">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-440">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="80eda-441">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="80eda-441">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-442">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="80eda-442">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="80eda-443">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-443">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="80eda-444">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="80eda-444">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-445">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="80eda-445">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-446">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-446">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="80eda-447">
  <strong>Observação</strong>: não há mais suporte para o gerenciamento de computador herdado desde 15 de outubro de 2020 em diante.</span><span class="sxs-lookup"><span data-stu-id="80eda-447">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="80eda-448"></li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-448"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="80eda-449">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-449">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="80eda-450">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="80eda-450">The exact steps depend on your source environment.</span></span> <span data-ttu-id="80eda-451">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="80eda-451">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="80eda-452">Explicar os benefícios de vincular o Configuration Manager à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-452">Explaining the benefits of cloud-attaching Configuration Manager with Intune.</span></span>  </li>
<li>  <span data-ttu-id="80eda-453">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="80eda-453">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="80eda-454">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="80eda-454">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="80eda-455">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="80eda-455">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="80eda-456">Habilitação de vinculação à nuvem no console do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="80eda-456">Enabling cloud-attach in the Configuration Manager console.</span></span>  </li>
<li>  <span data-ttu-id="80eda-457">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="80eda-457">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="80eda-458">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="80eda-458">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="80eda-459">Fornecimento de diretrizes sobre como configurar o gateway de gerenciamento de nuvem.</span><span class="sxs-lookup"><span data-stu-id="80eda-459">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="80eda-460">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-460">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="80eda-461">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-461">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="80eda-462"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="80eda-462"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="80eda-463">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="80eda-463">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="80eda-464">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="80eda-464">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-465">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="80eda-465">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="80eda-466">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="80eda-466">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-467">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-467">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="80eda-468">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="80eda-468">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-469">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="80eda-469">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="80eda-470">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="80eda-470">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="80eda-471"><strong>Observação</strong>: o FastTrack não é compatível com a proteção do Outlook para iOS e Android com as políticas de caixa de correio de dispositivo móvel do Exchange.</span><span class="sxs-lookup"><span data-stu-id="80eda-471"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="80eda-472">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="80eda-472">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="80eda-473">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-473">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="80eda-474"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-474"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  

<span data-ttu-id="80eda-475"><strong>Vincular Configuration Manager à nuvem com o Intune</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-475"><strong>Cloud-attach Configuration Manager with Intune</strong></span></span>  

 <span data-ttu-id="80eda-476">Com a vinculação à nuvem, os administradores de TI são responsáveis por preparar o ambiente local.</span><span class="sxs-lookup"><span data-stu-id="80eda-476">With cloud-attach, IT admins are responsible for preparing the on-premises environment.</span></span> <span data-ttu-id="80eda-477">Isso pode incluir a correção de problemas que impedem que você anexe à nuvem os seus ambientes do Configuration Manager com o Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-477">This can include remediation of issues that prevent you from cloud-attaching your Configuration Manager environments with Intune.</span></span>  
  <span data-ttu-id="80eda-478"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="80eda-478"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="80eda-479">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="80eda-479">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="80eda-480"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-480"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="80eda-481"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-481"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="80eda-482">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="80eda-482">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="80eda-483">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="80eda-483">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="80eda-484"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-484"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="80eda-485">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="80eda-485">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="80eda-486"><strong>Implantar o Outlook para iOS e Android de forma segura com o Intune</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-486"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="80eda-487">Identidades dos usuários habilitadas no Azure Active Directory para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-487">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-488">Exchange Online ou Exchange híbrido configurado com licenças de usuário atribuídas.</span><span class="sxs-lookup"><span data-stu-id="80eda-488">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="80eda-489">Windows 10</span><span class="sxs-lookup"><span data-stu-id="80eda-489">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="80eda-490"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-490"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="80eda-491"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-491"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="80eda-492"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-492"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="80eda-493"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-493"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="80eda-494">Fornecemos orientações para ajudar você a atualizar do Windows 7 Professional e do Windows 8.1 Professional para o Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="80eda-494">We provide guidance to help you upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="80eda-495">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-496">Entender a sua intenção do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-496">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="80eda-497">Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).</span><span class="sxs-lookup"><span data-stu-id="80eda-497">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="80eda-498">Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-498">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-499">Recomendamos opções para você avaliar os aplicativos do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-499">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="80eda-500">Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="80eda-500">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="80eda-501">Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="80eda-501">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="80eda-502">Avaliação das estratégias de gerenciamento modernas, inclusive a vinculação do Configuration Manager à nuvem com o Microsoft Intune ou a implantação do Intune como a única solução de gerenciamento de nuvem.</span><span class="sxs-lookup"><span data-stu-id="80eda-502">Assessing your modern management strategies, including cloud-attaching Configuration Manager with Microsoft Intune or deploying Intune as the sole cloud management solution.</span></span>  </li>
<li>  <span data-ttu-id="80eda-503">Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="80eda-503">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="80eda-504">Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.</span><span class="sxs-lookup"><span data-stu-id="80eda-504">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="80eda-505">Diretrizes de atualização para dar suporte ao seu movimento de implantação existente.</span><span class="sxs-lookup"><span data-stu-id="80eda-505">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="80eda-506">O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-506">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="80eda-507">As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="80eda-507">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="80eda-508">Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-508">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="80eda-509">Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="80eda-509">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="80eda-510">Orientação para habilitar o gerenciamento moderno pelo Configuration Manager vinculado à nuvem para o Intune ou implantando o Intune de forma independente.</span><span class="sxs-lookup"><span data-stu-id="80eda-510">Providing guidance to enable modern management by cloud-attaching Configuration Manager to Intune or by deploying Intune standalone (where required).</span></span>  </li>
</ul><span data-ttu-id="80eda-511">
  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-511">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="80eda-512">Atualizar o Configuration Manager para o Branch Atual.</span><span class="sxs-lookup"><span data-stu-id="80eda-512">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="80eda-513">Criar imagens personalizadas para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-513">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="80eda-514">Criar e dar suporte à implantação de scripts para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-514">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="80eda-515">Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).</span><span class="sxs-lookup"><span data-stu-id="80eda-515">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="80eda-516">Habilitar os recursos de segurança do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-516">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="80eda-517">Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="80eda-517">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="80eda-518">Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-518">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="80eda-519">Usar a Ferramenta de Migração de Estado do Usuário (USMT).</span><span class="sxs-lookup"><span data-stu-id="80eda-519">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="80eda-520">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="80eda-520">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="80eda-521">Para a atualização do computador, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="80eda-521">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-522">SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="80eda-522">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="80eda-523">Dispositivos: fator forma de desktop, notebook ou tablet.</span><span class="sxs-lookup"><span data-stu-id="80eda-523">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="80eda-524">SO de destino: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="80eda-524">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="80eda-525">Para atualização da infraestrutura, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="80eda-525">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-526">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="80eda-526">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="80eda-527">A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-527">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="80eda-528">Para obter mais informações, confira a tabela de suporte do Configuration Manager em  <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="80eda-528">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="80eda-529"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="80eda-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="80eda-530">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="80eda-530">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="80eda-531">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="80eda-531">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="80eda-532">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-532">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="80eda-533">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="80eda-533">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="80eda-534">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-534">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="80eda-535">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="80eda-535">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="80eda-536">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="80eda-536">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="80eda-537">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="80eda-537">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="80eda-538">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="80eda-538">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-539">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="80eda-539">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-540">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="80eda-540">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-541">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="80eda-541">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-542">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="80eda-542">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-543">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="80eda-543">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-544">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="80eda-544">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-545">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="80eda-545">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="80eda-546">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="80eda-546">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="80eda-547">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="80eda-547">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="80eda-548">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="80eda-548">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="80eda-549">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="80eda-549">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-550">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="80eda-550">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-551">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="80eda-551">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-552">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="80eda-552">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-553">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="80eda-553">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-554">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="80eda-554">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-555">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="80eda-555">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="80eda-556">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="80eda-556">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="80eda-557"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="80eda-557"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="80eda-558">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="80eda-558">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="80eda-559">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="80eda-559">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="80eda-560">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="80eda-560">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="80eda-561">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="80eda-561">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-562">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="80eda-562">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-563">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="80eda-563">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-564">Linux.</span><span class="sxs-lookup"><span data-stu-id="80eda-564">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-565">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="80eda-565">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-566">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="80eda-566">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-567">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="80eda-567">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-568">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="80eda-568">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-569">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="80eda-569">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-570">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="80eda-570">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-571">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="80eda-571">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-572">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="80eda-572">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-573">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="80eda-573">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="80eda-574">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="80eda-574">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-575">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="80eda-575">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-576">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="80eda-576">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="80eda-577">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="80eda-577">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-578">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="80eda-578">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-579">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="80eda-579">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="80eda-580">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="80eda-580">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="80eda-581">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="80eda-581">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="80eda-582">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="80eda-582">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="80eda-583">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="80eda-583">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="80eda-584">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="80eda-584">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="80eda-585">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="80eda-585">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="80eda-586">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="80eda-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

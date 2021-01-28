---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016683"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="d0490-104">Produtos e Recursos</span><span class="sxs-lookup"><span data-stu-id="d0490-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="d0490-105">Serviços e cenários com suportados pelo FastTrack</span><span class="sxs-lookup"><span data-stu-id="d0490-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="d0490-106">Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar.</span><span class="sxs-lookup"><span data-stu-id="d0490-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="d0490-107">Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="d0490-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="d0490-108">O FastTrack fornece orientações para ajudá-lo primeiro com os principais recursos (comuns para todos os Serviços Online da Microsoft) e, em seguida, com a integração de cada serviço qualificado:</span><span class="sxs-lookup"><span data-stu-id="d0490-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="d0490-109">Geral</span><span class="sxs-lookup"><span data-stu-id="d0490-109">General</span></span>](#general)
  - [<span data-ttu-id="d0490-110">Segurança e conformidade</span><span class="sxs-lookup"><span data-stu-id="d0490-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="d0490-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="d0490-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="d0490-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="d0490-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="d0490-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="d0490-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="d0490-114">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="d0490-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="d0490-115">Garantia de Aplicativo</span><span class="sxs-lookup"><span data-stu-id="d0490-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="d0490-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="d0490-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="d0490-117">Para saber mais sobre as expectativas de ambiente de origem para o Office 365 US Government, confira [Expectativas de Ambiente de Origem para o Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="d0490-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="d0490-118">Geral</span><span class="sxs-lookup"><span data-stu-id="d0490-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-119"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-120"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-121"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d0490-122"><strong>Integração principal</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="d0490-123">Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário.</span><span class="sxs-lookup"><span data-stu-id="d0490-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="d0490-124">Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="d0490-125">A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.</span><span class="sxs-lookup"><span data-stu-id="d0490-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="d0490-126"></li>
</ul>  

<strong>Integração de identidade</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="d0490-127">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="d0490-128">Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</span><span class="sxs-lookup"><span data-stu-id="d0490-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="d0490-129">Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</span><span class="sxs-lookup"><span data-stu-id="d0490-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="d0490-130">Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</span><span class="sxs-lookup"><span data-stu-id="d0490-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="d0490-131">Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="d0490-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="d0490-132">Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="d0490-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="d0490-133">Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</span><span class="sxs-lookup"><span data-stu-id="d0490-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="d0490-134">Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</span><span class="sxs-lookup"><span data-stu-id="d0490-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="d0490-135">Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="d0490-136">Habilitar o provisionamento automático do usuário para aplicativos SaaS pré-integrados, como listados na <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Lista de tutoriais de integração de aplicativos</a>, (limitado apenas ao provisionamento de saída e de aplicativos SaaS da galeria do Azure AD).</span><span class="sxs-lookup"><span data-stu-id="d0490-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="d0490-137"><strong>Habilitação de rede </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="d0490-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="d0490-138">Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="d0490-139"><strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:</span><span class="sxs-lookup"><span data-stu-id="d0490-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-140">Uma única floresta do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d0490-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="d0490-141">Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="d0490-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-142">Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="d0490-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-143">Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="d0490-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="d0490-144">Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0490-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="d0490-145">Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.</span><span class="sxs-lookup"><span data-stu-id="d0490-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="d0490-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="d0490-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="d0490-147">Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0490-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="d0490-148">Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis.</span><span class="sxs-lookup"><span data-stu-id="d0490-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="d0490-149">Namespaces SMTP primários entre organizações do Exchange também devem ser separados.</span><span class="sxs-lookup"><span data-stu-id="d0490-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="d0490-150">Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="d0490-151">Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo.</span><span class="sxs-lookup"><span data-stu-id="d0490-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="d0490-152">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="d0490-154">Fornecemos orientações de implantação remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-155">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="d0490-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="d0490-156">Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="d0490-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="d0490-157">Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="d0490-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="d0490-158">Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="d0490-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="d0490-159">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="d0490-160">Seleção e configuração de uma instalação local ou na nuvem.</span><span class="sxs-lookup"><span data-stu-id="d0490-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="d0490-161">Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.</span><span class="sxs-lookup"><span data-stu-id="d0490-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="d0490-162">Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="d0490-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="d0490-163">Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="d0490-164">Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="d0490-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="d0490-165">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos do sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para o Microsoft 365 e o Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-166"><strong>Integridade da rede</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="d0490-167">Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="d0490-168">Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.</span><span class="sxs-lookup"><span data-stu-id="d0490-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="d0490-169">Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="d0490-170">Acesso ao Centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="d0490-171">São necessárias versões atualizadas dos aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="d0490-172">Serviços de localização habilitados conforme as <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="d0490-173">Segurança e Conformidade</span><span class="sxs-lookup"><span data-stu-id="d0490-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-174"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-175"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-176"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="d0490-177"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="d0490-178">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="d0490-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="d0490-179">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="d0490-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="d0490-180">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="d0490-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="d0490-181">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="d0490-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="d0490-182">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="d0490-183">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="d0490-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="d0490-184">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="d0490-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="d0490-185">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="d0490-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="d0490-186">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="d0490-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="d0490-187">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="d0490-188">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="d0490-189">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="d0490-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="d0490-190">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="d0490-191">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-192">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="d0490-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-193">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-194">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="d0490-195">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-196">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-197">Gerenciar e controlar o acesso a contas privilegiadas de administrador com o Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="d0490-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-198">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-199">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="d0490-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="d0490-200">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-201">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-202">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-203">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="d0490-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-204">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="d0490-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-205"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="d0490-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="d0490-206">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-207">Ativando e configurando seu locatário.</span><span class="sxs-lookup"><span data-stu-id="d0490-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="d0490-208">Criação e configuração dos rótulos e políticas.</span><span class="sxs-lookup"><span data-stu-id="d0490-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-209">Aplicação de proteção de informações aos documentos.</span><span class="sxs-lookup"><span data-stu-id="d0490-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="d0490-210">Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="d0490-211">Descobrir e rotular arquivos em repouso usando o scanner da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="d0490-212">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="d0490-213">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="d0490-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="d0490-214">As responsabilidades dos pré-requisitos do cliente incluem:</span><span class="sxs-lookup"><span data-stu-id="d0490-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-215">Uma lista de locais de compartilhamento de arquivos a serem verificados.</span><span class="sxs-lookup"><span data-stu-id="d0490-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="d0490-216">Uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="d0490-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="d0490-217">Noções básicas sobre qualquer restrição regulamentar ou requisitos relacionados ao gerenciamento de chaves.</span><span class="sxs-lookup"><span data-stu-id="d0490-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-218">Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="d0490-219">Rótulos configurados para classificação e proteção.</span><span class="sxs-lookup"><span data-stu-id="d0490-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="d0490-220">Todos os pré-requisitos para o scanner da Proteção de Informações do Azure estão em uso.</span><span class="sxs-lookup"><span data-stu-id="d0490-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="d0490-221">Para saber mais, confira Pré-requisitos para instalar e implantar o scanner de rotulagem unificado da Proteção de Informações do <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="d0490-222">Certifique-se de que os dispositivos do usuário estão executando um sistema operacional com suporte e tenham os pré-requisitos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="d0490-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="d0490-223">Consulte o seguinte para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="d0490-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="d0490-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia do Administrador: Instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </span><span class="sxs-lookup"><span data-stu-id="d0490-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="d0490-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="d0490-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="d0490-226">Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector RMS do Active Directory (AD RMS) para suporte híbrido.</span><span class="sxs-lookup"><span data-stu-id="d0490-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="d0490-227">Configure e configure BYOK (Traga sua própria chave), DKE (criptografia de chave dupla) (somente cliente de rotulagem unificada) ou MANTENHA sua própria chave (HYOK) (somente cliente clássico) caso você rebaixe uma destas opções para sua implantação.</span><span class="sxs-lookup"><span data-stu-id="d0490-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="d0490-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="d0490-229">O Microsoft 365 Defender é um pacote unificado de defesa empresarial pré-e pós-violação que coordena de forma nativa a detecção, prevenção, investigação e resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="d0490-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="d0490-230">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="d0490-231">Fornecendo uma visão geral da central de segurança do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="d0490-232">Analisar incidentes entre produtos, incluindo o que é fundamental, garantindo o escopo completo do ataque, ativos afetados e ações de correção automatizadas agrupadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="d0490-233">Demonstrar como o Microsoft 365 Defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidos por meio de uma auto-recuperação automática.</span><span class="sxs-lookup"><span data-stu-id="d0490-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="d0490-234">Explicando e fornecendo exemplos de como os clientes podem buscar proativamente por tentativas de invasão e atividades de violação que afetem seu email, dados, dispositivos e contas em vários conjuntos de dados.</span><span class="sxs-lookup"><span data-stu-id="d0490-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="d0490-235">Mostrar aos clientes como eles podem revisar e melhorar a postura de segurança holisticamente usando o Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="d0490-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="d0490-236"><strong>O exemplo a seguir está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="d0490-237">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="d0490-238">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="d0490-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="d0490-239">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="d0490-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="d0490-240">Como remediar ou interpretar os vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="d0490-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="d0490-241">Como investigar um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="d0490-242">Busca personalizada de ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="d0490-243">Informações de segurança e gerenciamento de eventos (SIEM) ou integração de API.</span><span class="sxs-lookup"><span data-stu-id="d0490-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="d0490-245">O Microsoft Cloud App Security é um Agente de Segurança de Acesso à Nuvem (CASB) que fornece visibilidade avançada, controle sobre viagem de dados e análise sofisticada para identificar e combater ameaças cibernéticas em todos os serviços de nuvem da Microsoft e de terceiros.</span><span class="sxs-lookup"><span data-stu-id="d0490-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="d0490-246">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-247">Configuração do portal, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="d0490-248">Importação de grupos de usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="d0490-249">Gerenciando configurações e acesso de administrador.</span><span class="sxs-lookup"><span data-stu-id="d0490-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="d0490-250">Definindo o plano de implantação para selecionar determinados grupos de usuários a ser monitorado ou excluído do monitoramento.</span><span class="sxs-lookup"><span data-stu-id="d0490-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="d0490-251">Definição de marcas e intervalos de IP.</span><span class="sxs-lookup"><span data-stu-id="d0490-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="d0490-252">Personalizando a experiência do usuário final com seu logotipo e mensagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="d0490-253">Configurando a descoberta na nuvem para fornecer a IT de sombra usando:</span><span class="sxs-lookup"><span data-stu-id="d0490-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="d0490-254">Microsoft Defender para pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="d0490-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="d0490-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="d0490-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="d0490-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="d0490-257">Conexão de <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicativos em destaque</a> usando conectores de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="d0490-258">Configurar o Controle de Aplicativo de Acesso Condicional nos portais de Acesso Condicional e Segurança de Aplicativo na Nuvem para aplicar controles de sessão em tempo real.</span><span class="sxs-lookup"><span data-stu-id="d0490-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="d0490-259">Implantação dos painéis Cloud App Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="d0490-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="d0490-260">Personalização de pontuações de risco do aplicativo com base nas prioridades da sua organização.</span><span class="sxs-lookup"><span data-stu-id="d0490-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="d0490-261">Criação de marcas e categorias de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="d0490-262">Sancionando e não sancionando aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="d0490-263">Usando os logs de atividades e arquivos.</span><span class="sxs-lookup"><span data-stu-id="d0490-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="d0490-264">Gerenciando aplicativos OAuth.</span><span class="sxs-lookup"><span data-stu-id="d0490-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="d0490-265">Noções básicas sobre correlação de incidentes no portal do Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="d0490-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="d0490-266">Fornecer assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> principais casos de uso para CASBs (incluindo a criação ou atualização de até seis (6 políticas), exceto:</span><span class="sxs-lookup"><span data-stu-id="d0490-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="d0490-267">Auditoria da configuração de ambientes de Internet como serviço (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="d0490-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="d0490-268">Monitorar as atividades do usuário para se proteger contra ameaças em seus ambientes IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="d0490-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="d0490-269"><strong>O exemplo a seguir está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="d0490-270">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="d0490-271">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="d0490-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="d0490-272">Configurar a infraestrutura, a instalação ou a implantação de carregamentos automáticos de log para relatórios contínuos usando o Docker ou um coletor de log.</span><span class="sxs-lookup"><span data-stu-id="d0490-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="d0490-273">Confira <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">os 20 principais casos de uso para CASBs</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="d0490-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="d0490-274">Criar um relatório de instantâneo do Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="d0490-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="d0490-275">Bloqueando o uso do aplicativo usando scripts de bloco.</span><span class="sxs-lookup"><span data-stu-id="d0490-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="d0490-276">Conectando aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="d0490-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="d0490-277">Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção contra perda de dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="d0490-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="d0490-278">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="d0490-279">Investigação e correção automatizadas, incluindo os playbooks do Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="d0490-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="d0490-280">Informações de segurança e gerenciamento de eventos (SIEM) ou integração de API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="d0490-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="d0490-281">Implantação da Descoberta de Aplicativos na Nuvem como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="d0490-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="d0490-282"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="d0490-283">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="d0490-284">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-285">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="d0490-286">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="d0490-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="d0490-287">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="d0490-288">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="d0490-289">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="d0490-290">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="d0490-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="d0490-291">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="d0490-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-292">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="d0490-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-293">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="d0490-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-294">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="d0490-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-295">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="d0490-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-296">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-297">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="d0490-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-298">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="d0490-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="d0490-299">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="d0490-300">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="d0490-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="d0490-301">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="d0490-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="d0490-302">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="d0490-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="d0490-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="d0490-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-306">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="d0490-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-307">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="d0490-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-308">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="d0490-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="d0490-309">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="d0490-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="d0490-310"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-311">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="d0490-312">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="d0490-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="d0490-313">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="d0490-314">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="d0490-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="d0490-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="d0490-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="d0490-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-318">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="d0490-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-319">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="d0490-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-320">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="d0490-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-321">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d0490-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-322">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-323">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d0490-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-324">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="d0490-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-325">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-326">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="d0490-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="d0490-327">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="d0490-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-328">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="d0490-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-329">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="d0490-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-330">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="d0490-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-331">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-332">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="d0490-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-333">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-334">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="d0490-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="d0490-335">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="d0490-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="d0490-336">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="d0490-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="d0490-337">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="d0490-338">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="d0490-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="d0490-339">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="d0490-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="d0490-340"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="d0490-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="d0490-341">O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização.</span><span class="sxs-lookup"><span data-stu-id="d0490-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="d0490-342">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="d0490-343">Criar sua instância do Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="d0490-344">Conectando o Defender para Identidade ao Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d0490-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="d0490-345">Avaliando a preparação do ambiente para implantar o sensor do Defender for Identity em seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="d0490-346">Executando a ferramenta de replicação para planejamento de capacidade de recursos.</span><span class="sxs-lookup"><span data-stu-id="d0490-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="d0490-347">Executar a ferramenta de auditoria para avaliar a compatibilidade dos controladores de domínio com o sensor.</span><span class="sxs-lookup"><span data-stu-id="d0490-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="d0490-348">Implantar o sensor para capturar e analisar o tráfego de rede e eventos do Windows diretamente de seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="d0490-349">Baixando o pacote do sensor.</span><span class="sxs-lookup"><span data-stu-id="d0490-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="d0490-350">Configurando o sensor.</span><span class="sxs-lookup"><span data-stu-id="d0490-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="d0490-351">Instalar o sensor no controlador de domínio silenciosamente.</span><span class="sxs-lookup"><span data-stu-id="d0490-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="d0490-352">Implantar o sensor em seu ambiente de várias florestas.</span><span class="sxs-lookup"><span data-stu-id="d0490-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="d0490-353">Integração do Defender para Identidade com o Microsoft Cloud App Security (o licenciamento do Cloud App Security não é necessário).</span><span class="sxs-lookup"><span data-stu-id="d0490-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="d0490-354">Fornecendo diretrizes de implantação, assistência de configuração e educação em:</span><span class="sxs-lookup"><span data-stu-id="d0490-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="d0490-355">Ajustando o ambiente para reduzir o "ruído".</span><span class="sxs-lookup"><span data-stu-id="d0490-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="d0490-356">Noções básicas sobre o relatório de avaliação de postura de segurança de identidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="d0490-357">Noções básicas sobre a pontuação de prioridade de investigação do usuário e o relatório de classificação de investigação do usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="d0490-358">Noções básicas sobre o relatório de usuário inativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="d0490-359">Fornecendo opções de correção em uma conta comprometida.</span><span class="sxs-lookup"><span data-stu-id="d0490-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="d0490-360">Facilitar a migração do Advanced Threat Analytics (ATA) para o Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="d0490-361"><strong>O exemplo a seguir está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="d0490-362">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="d0490-363">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="d0490-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="d0490-364">Implantação do sensor do Defender para Identidade, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="d0490-365">Planejamento de capacidade manual.</span><span class="sxs-lookup"><span data-stu-id="d0490-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="d0490-366">Implantação do sensor em uma capacidade autônoma.</span><span class="sxs-lookup"><span data-stu-id="d0490-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="d0490-367">Implantação do sensor usando um adaptador de equipe NIC (Placa de Interface de Rede).</span><span class="sxs-lookup"><span data-stu-id="d0490-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="d0490-368">Implantar o sensor por meio de uma ferramenta de terceiros.</span><span class="sxs-lookup"><span data-stu-id="d0490-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="d0490-369">Conectando-se ao serviço de nuvem Do Defender para Identidade por meio de uma conexão de proxy da Web.</span><span class="sxs-lookup"><span data-stu-id="d0490-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="d0490-370">Criação e gerenciamento de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="d0490-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="d0490-371">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="d0490-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="d0490-372">Correção ou interpretação de vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="d0490-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="d0490-373">Investigando um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="d0490-374">Ameaça ou busca avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="d0490-375">Resposta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="d0490-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="d0490-376">Fornecendo um tutorial de laboratório de alerta de segurança para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="d0490-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="d0490-377">Fornecer notificação quando o Defender for Identity detecta atividades suspeitas enviando alertas de segurança para seu servidor syslog por meio de um sensor indicado.</span><span class="sxs-lookup"><span data-stu-id="d0490-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="d0490-378">Configurar o Defender for Identity para executar consultas usando o protocolo SAMR (gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="d0490-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="d0490-379">Configurar soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="d0490-380">Informações de segurança e gerenciamento de eventos (SIEM) ou integração de API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="d0490-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="d0490-381">Implantar sensores do Defender for Identity como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="d0490-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="d0490-382">Active Directory implantado.</span><span class="sxs-lookup"><span data-stu-id="d0490-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="d0490-383">Os controladores de domínio em que você pretende instalar os sensores do Defender for Identity têm conectividade com a Internet com o serviço de nuvem Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="d0490-384">Seu firewall e proxy devem estar abertos para se comunicar com o serviço de nuvem do Defender para Identidade (\*.atp.azure.com porta 443 deve estar aberta).</span><span class="sxs-lookup"><span data-stu-id="d0490-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="d0490-385">Controladores de domínio em execução em um dos seguintes:</span><span class="sxs-lookup"><span data-stu-id="d0490-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="d0490-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="d0490-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="d0490-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="d0490-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="d0490-388">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="d0490-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="d0490-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="d0490-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="d0490-390">Windows Server 2019 com KB4487044 (sistema operacional build 17763.316).</span><span class="sxs-lookup"><span data-stu-id="d0490-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="d0490-391"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="d0490-392">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-393">Rótulos e diretivas de retenção.</span><span class="sxs-lookup"><span data-stu-id="d0490-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-394">Gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="d0490-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-395">Diretivas de exclusão.</span><span class="sxs-lookup"><span data-stu-id="d0490-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-396">Conformidade da comunicação.</span><span class="sxs-lookup"><span data-stu-id="d0490-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="d0490-397">Gerenciamento de risco interno.</span><span class="sxs-lookup"><span data-stu-id="d0490-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-398">Descoberta Eletrônica Avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="d0490-399">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="d0490-400">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="d0490-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="d0490-401">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="d0490-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="d0490-402">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="d0490-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="d0490-403">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="d0490-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="d0490-404">Desenvolvimento da arquitetura de informações no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="d0490-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="d0490-405">Script e codificação personalizados.</span><span class="sxs-lookup"><span data-stu-id="d0490-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="d0490-406">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-407"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="d0490-408">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-409">Classificação de dados.</span><span class="sxs-lookup"><span data-stu-id="d0490-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="d0490-410">Tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="d0490-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="d0490-411">Criação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-412">Aplicando rótulos de sensibilidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-413">Rotulagem unificada.</span><span class="sxs-lookup"><span data-stu-id="d0490-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="d0490-414">Classificadores treináveis.</span><span class="sxs-lookup"><span data-stu-id="d0490-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="d0490-415">Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.</span><span class="sxs-lookup"><span data-stu-id="d0490-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="d0490-416">Publicar etiquetas usando políticas (manual e automática).</span><span class="sxs-lookup"><span data-stu-id="d0490-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="d0490-417">Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-418">Criação de políticas DLP do ponto de extremidade para dispositivos Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="d0490-419">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="d0490-420">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-420">Customer key.</span></span></li>
<li><span data-ttu-id="d0490-421">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="d0490-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="d0490-422">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="d0490-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="d0490-423">Script e codificação personalizados.</span><span class="sxs-lookup"><span data-stu-id="d0490-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="d0490-424">
<strong>Observação:</strong> Para saber mais, confira <strong>a Proteção de Informações do Azure</strong> no Enterprise <a href="#enterprise-mobility--security">Mobility + Security.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="d0490-425">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="d0490-427">Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado em nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="d0490-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="d0490-428">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="d0490-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="d0490-429">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-430">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="d0490-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="d0490-431">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="d0490-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="d0490-432">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-433">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-434">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-435">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="d0490-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-436">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-437">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="d0490-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-438">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="d0490-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="d0490-439">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-440">Implantação de email, redes sem fio e perfis VPN se você tiver uma autoridade de certificação, rede sem fio ou infraestrutura VPN existente em sua organização.</span><span class="sxs-lookup"><span data-stu-id="d0490-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="d0490-441">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="d0490-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="d0490-442">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="d0490-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-443">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="d0490-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="d0490-444">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="d0490-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="d0490-445">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="d0490-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="d0490-446">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-446">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="d0490-447">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="d0490-447">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-448">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="d0490-448">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="d0490-449">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-449">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="d0490-450">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="d0490-450">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-451">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-451">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-452">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-452">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="d0490-453">
 
</li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-453">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="d0490-454">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-454">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="d0490-455">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="d0490-455">The exact steps depend on your source environment.</span></span> <span data-ttu-id="d0490-456">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-456">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="d0490-457">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="d0490-457">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="d0490-458">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="d0490-458">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="d0490-459">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-459">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-460">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-460">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="d0490-461">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-461">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-462">Fornecer orientação sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.</span><span class="sxs-lookup"><span data-stu-id="d0490-462">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-463">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-463">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="d0490-464">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-464">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="d0490-465"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="d0490-465"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="d0490-466">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="d0490-466">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="d0490-467">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-467">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-468">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="d0490-468">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="d0490-469">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="d0490-469">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-470">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-470">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="d0490-471">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-471">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-472">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-472">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-473">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-473">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="d0490-474">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-474">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="d0490-475"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-475"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="d0490-476"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="d0490-476"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="d0490-477">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="d0490-478"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-478"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="d0490-479"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-479"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="d0490-480">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="d0490-480">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="d0490-481">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="d0490-482"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-482"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="d0490-483">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="d0490-483">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="d0490-484"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="d0490-485">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-485">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-486">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="d0490-486">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="d0490-487">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="d0490-487">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="d0490-488">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="d0490-488">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="d0490-489">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-489">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-490">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-490">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="d0490-491">Office 365</span><span class="sxs-lookup"><span data-stu-id="d0490-491">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-492"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-492"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-493"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-493"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-494"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-494"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d0490-495"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-495"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="d0490-496">Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email.</span><span class="sxs-lookup"><span data-stu-id="d0490-496">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="d0490-497">As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.</span><span class="sxs-lookup"><span data-stu-id="d0490-497">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="d0490-498">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-498">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-499">Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-499">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-500">Apontar seus registros de troca de mensagens (MX) para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-500">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-501">Configurar o recurso do Office 365 ATP se ele fizer parte do seu serviço de assinatura.</span><span class="sxs-lookup"><span data-stu-id="d0490-501">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="d0490-502">Para mais informações, veja a parte dessa tabela <strong>Proteção Avançada contra Ameaças do Office 365</strong>.</span><span class="sxs-lookup"><span data-stu-id="d0490-502">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="d0490-p126">Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="d0490-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="d0490-p127">Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="d0490-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="d0490-507">
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-507">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="d0490-508">A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="d0490-508">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="d0490-509">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="d0490-509">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="d0490-510">Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).</span><span class="sxs-lookup"><span data-stu-id="d0490-510">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="d0490-511">Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).</span><span class="sxs-lookup"><span data-stu-id="d0490-511">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="d0490-512">Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-512">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-513">Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="d0490-513">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="d0490-514">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="d0490-514">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="d0490-515">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-515">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="d0490-516">Seu ambiente de origem deve ter um dos seguintes níveis mínimos:</span><span class="sxs-lookup"><span data-stu-id="d0490-516">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-517">Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.</span><span class="sxs-lookup"><span data-stu-id="d0490-517">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="d0490-518">Um único ambiente de email compatível com o protocolo IMAP.</span><span class="sxs-lookup"><span data-stu-id="d0490-518">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-519">Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).</span><span class="sxs-lookup"><span data-stu-id="d0490-519">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="d0490-520">Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-520">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="d0490-521">Software de cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, cliente de sincronização do OneDrive for Business, Power BI Desktop e Skype for Business deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-521">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-522"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-522"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="d0490-523">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-523">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-524">Rótulos e diretivas de retenção.</span><span class="sxs-lookup"><span data-stu-id="d0490-524">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-525">Gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="d0490-525">Records management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-526">Diretivas de exclusão.</span><span class="sxs-lookup"><span data-stu-id="d0490-526">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-527">Conformidade da comunicação.</span><span class="sxs-lookup"><span data-stu-id="d0490-527">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="d0490-528">Gerenciamento de risco interno.</span><span class="sxs-lookup"><span data-stu-id="d0490-528">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-529">Descoberta Eletrônica Avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-529">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="d0490-530">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-530">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="d0490-531">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="d0490-531">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="d0490-532">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="d0490-532">Data connectors.</span></span></li>
<li> <span data-ttu-id="d0490-533">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="d0490-533">Information barriers.</span></span></li>
<li> <span data-ttu-id="d0490-534">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="d0490-534">Privileged access management.</span></span></li>
<li> <span data-ttu-id="d0490-535">Desenvolvimento da arquitetura de informações no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="d0490-535">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="d0490-536">Script e codificação personalizados.</span><span class="sxs-lookup"><span data-stu-id="d0490-536">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="d0490-537">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-537">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-538"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-538"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="d0490-539">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-539">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-540">Classificação de dados.</span><span class="sxs-lookup"><span data-stu-id="d0490-540">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="d0490-541">Tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="d0490-541">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="d0490-542">Criação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-542">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-543">Aplicando rótulos de sensibilidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-543">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-544">Rotulagem unificada.</span><span class="sxs-lookup"><span data-stu-id="d0490-544">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="d0490-545">Classificadores treináveis.</span><span class="sxs-lookup"><span data-stu-id="d0490-545">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="d0490-546">Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.</span><span class="sxs-lookup"><span data-stu-id="d0490-546">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="d0490-547">Publicar etiquetas usando políticas (manual e automática).</span><span class="sxs-lookup"><span data-stu-id="d0490-547">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="d0490-548">Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-548">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="d0490-549">Criação de políticas DLP do ponto de extremidade para dispositivos Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-549">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="d0490-550">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-550">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="d0490-551">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-551">Customer key.</span></span></li>
<li><span data-ttu-id="d0490-552">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="d0490-552">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="d0490-553">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="d0490-553">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="d0490-554">Script e codificação personalizados.</span><span class="sxs-lookup"><span data-stu-id="d0490-554">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="d0490-555">
<strong>Observação:</strong> Para saber mais, confira <strong>a Proteção de Informações do Azure</strong> no Enterprise <a href="#enterprise-mobility--security">Mobility + Security.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-555">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="d0490-556">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-556">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-557"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-557"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="d0490-558">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-558">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-559">Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-559">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="d0490-560">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="d0490-560">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="d0490-561">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="d0490-561">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="d0490-562">Confirmação da habilitação do Teams no seu locatário do Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-562">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="d0490-563">Habilitação ou desabilitação de licenças de usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-563">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="d0490-564">Avaliação Rede para o Teams:</span><span class="sxs-lookup"><span data-stu-id="d0490-564">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-565">Verificações de porta e de ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-565">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="d0490-566">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="d0490-566">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="d0490-567">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="d0490-567">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="d0490-568">Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="d0490-568">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="d0490-569">Se aplicável, também forneceremos diretrizes para:</span><span class="sxs-lookup"><span data-stu-id="d0490-569">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-570">Dispositivos para a Sala do Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="d0490-570">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="d0490-571">Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catálogo de dispositivos do Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-571">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="d0490-572">Assistência remota com a configuração do lado do serviço de dispositivos certificados de Salas do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-572">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="d0490-573">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="d0490-573">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="d0490-574">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="d0490-574">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="d0490-575">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-575">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="d0490-576">Sistema de Telefonia:</span><span class="sxs-lookup"><span data-stu-id="d0490-576">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-577">Configuração da organização para as configurações padrão do Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="d0490-577">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="d0490-578">Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):</span><span class="sxs-lookup"><span data-stu-id="d0490-578">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="d0490-579">Atribuição de números a usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-579">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="d0490-580">Orientação de portabilidade do número local pela IU (interface do usuário) até 999.</span><span class="sxs-lookup"><span data-stu-id="d0490-580">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="d0490-581">Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.</span><span class="sxs-lookup"><span data-stu-id="d0490-581">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-582">Diretrizes de Roteamento Direto:</span><span class="sxs-lookup"><span data-stu-id="d0490-582">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-583">Diretrizes de configuração da organização para o design de Roteamento Direto de cenários hospedados por parceiros ou cenários implantados pelo cliente para até 10 sites.</span><span class="sxs-lookup"><span data-stu-id="d0490-583">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="d0490-584">Revisão de configuração do Controlador de Borda da Sessão (SBC).</span><span class="sxs-lookup"><span data-stu-id="d0490-584">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="d0490-585">Assistência remota com configuração de plano de discagem.</span><span class="sxs-lookup"><span data-stu-id="d0490-585">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="d0490-586">Configuração de rota de voz.</span><span class="sxs-lookup"><span data-stu-id="d0490-586">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="d0490-587">Bypass de mídia e otimização de mídia local.</span><span class="sxs-lookup"><span data-stu-id="d0490-587">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="d0490-588">Habilitação dos eventos ao vivo do Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-588">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="d0490-589">Configuração e integração da organização com o Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="d0490-589">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="d0490-590">Diretrizes de transição do Skype for Business para o Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-590">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="d0490-591">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-591">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-592">Usuários habilitados para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-592">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="d0490-593">Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).</span><span class="sxs-lookup"><span data-stu-id="d0490-593">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="d0490-594">Habilitado para Grupos do Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-594">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="d0490-595">
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-595">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="d0490-596">O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-596">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="d0490-597">O Teams não oferece suporte para o SharePoint no local.</span><span class="sxs-lookup"><span data-stu-id="d0490-597">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="d0490-598">
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-598">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="d0490-599">Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect.</span><span class="sxs-lookup"><span data-stu-id="d0490-599">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="d0490-600">Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.</span><span class="sxs-lookup"><span data-stu-id="d0490-600">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="d0490-601">Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-601">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-602"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="d0490-603">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-603">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-604">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="d0490-604">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="d0490-605">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="d0490-605">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="d0490-606">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="d0490-606">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="d0490-607">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-607">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-608">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="d0490-608">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-609"><strong>Outlook para iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-609"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="d0490-610">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-610">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-611">Baixe o Outlook para iOS e Android no Google Play e Apple App Store.</span><span class="sxs-lookup"><span data-stu-id="d0490-611">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="d0490-612">Configurar contas e acessar a caixa de correio do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-612">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="d0490-613">Proteger o Outlook Mobile (para obter mais informações, confira <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).</span><span class="sxs-lookup"><span data-stu-id="d0490-613">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="d0490-614">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-614">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-615">Exchange Online configurado e licenças atribuídas.</span><span class="sxs-lookup"><span data-stu-id="d0490-615">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-616"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-616"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="d0490-617">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-617">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-618">Atribuição de licenças do Power BI.</span><span class="sxs-lookup"><span data-stu-id="d0490-618">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="d0490-619">Implantação do aplicativo do Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="d0490-619">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-620">O software cliente online, como o Power BI Desktop, deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-620">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-621"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-621"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="d0490-622">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-622">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-623">Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.</span><span class="sxs-lookup"><span data-stu-id="d0490-623">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="d0490-624">Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-624">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="d0490-625">Configurar o ERP (Pool de Recursos da Empresa).</span><span class="sxs-lookup"><span data-stu-id="d0490-625">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="d0490-626">Criando seu primeiro projeto.</span><span class="sxs-lookup"><span data-stu-id="d0490-626">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-627">Software cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-627">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-628"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-628"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="d0490-629">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-629">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-630">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="d0490-630">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="d0490-631">Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="d0490-631">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="d0490-632">Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="d0490-632">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="d0490-633">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-633">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="d0490-634">Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-634">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="d0490-635">Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="d0490-635">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-636">Software cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-636">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-637"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-637"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="d0490-638">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-638">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-639">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="d0490-639">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="d0490-640">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="d0490-640">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="d0490-641">Provisionar usuários e licenças.</span><span class="sxs-lookup"><span data-stu-id="d0490-641">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="d0490-642">Habilitar a criação de sites para o administrador do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-642">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="d0490-643">Planejamento de conjuntos de sites.</span><span class="sxs-lookup"><span data-stu-id="d0490-643">Planning site collections.</span></span></li>
<li><span data-ttu-id="d0490-644">Proteção de conteúdo e gerenciamento de permissões.</span><span class="sxs-lookup"><span data-stu-id="d0490-644">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="d0490-645">Configuração de recursos do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-645">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="d0490-646">Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.</span><span class="sxs-lookup"><span data-stu-id="d0490-646">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="d0490-647">Método de migração.</span><span class="sxs-lookup"><span data-stu-id="d0490-647">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="d0490-648">Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="d0490-648">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-649">Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.</span><span class="sxs-lookup"><span data-stu-id="d0490-649">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="d0490-650">Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="d0490-650">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="d0490-651">Planejar e implementar a distribuição única (ou em fases) para todos os usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-651">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="d0490-652">Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="d0490-652">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="d0490-653">Redirecionar ou mover pastas conhecidas para o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="d0490-653">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="d0490-654">Implantar o cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="d0490-654">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="d0490-655">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="d0490-655">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="d0490-656">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-656">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="d0490-657"><strong>Para o SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-657"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-658">A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-658">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="d0490-659">
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="d0490-659">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="d0490-660">Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.</span><span class="sxs-lookup"><span data-stu-id="d0490-660">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="d0490-661">
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo.</span><span class="sxs-lookup"><span data-stu-id="d0490-661">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="d0490-662">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-662">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="d0490-663">Para saber mais, confira Níveis <a href="https://go.microsoft.com/fwlink/?linkid=853548">mínimos de atualização pública para recursos híbridos do SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="d0490-663">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="d0490-664">
  <strong>Observação:</strong> Para saber mais sobre funcionalidades multi-geográficas, confira <a href="https://go.microsoft.com/fwlink/?linkid=831056">Funcionalidades multi-geográficas no OneDrive e no SharePoint Online no Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="d0490-664">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-665"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-665"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="d0490-666">Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="d0490-666">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="d0490-667">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos do sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para o Microsoft 365 e o Office.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-667">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="d0490-668">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="d0490-668">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-669"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-669"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-670"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-670"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-671"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-671"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="d0490-672"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-672"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="d0490-673">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="d0490-673">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="d0490-674">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="d0490-674">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="d0490-675">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="d0490-675">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="d0490-676">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="d0490-676">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="d0490-677">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-677">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="d0490-678">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="d0490-678">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="d0490-679">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="d0490-679">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="d0490-680">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="d0490-680">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="d0490-681">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="d0490-681">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="d0490-682">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-682">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="d0490-683">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-683">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="d0490-684">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="d0490-684">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="d0490-685">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-685">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="d0490-686">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-686">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-687">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="d0490-687">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-688">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-688">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-689">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-689">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="d0490-690">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-690">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-691">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-691">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-692">Gerenciar e controlar o acesso a contas privilegiadas de administrador com o Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="d0490-692">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-693">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-693">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-694">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="d0490-694">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="d0490-695">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-695">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-696">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-696">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-697">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-697">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-698">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="d0490-698">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="d0490-699">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="d0490-699">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d0490-700"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="d0490-700"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="d0490-701">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-701">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-702">Ativando e configurando seu locatário.</span><span class="sxs-lookup"><span data-stu-id="d0490-702">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="d0490-703">Criação e configuração dos rótulos e políticas.</span><span class="sxs-lookup"><span data-stu-id="d0490-703">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-704">Aplicação de proteção de informações aos documentos.</span><span class="sxs-lookup"><span data-stu-id="d0490-704">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="d0490-705">Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-705">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="d0490-706">Descobrir e rotular arquivos em repouso usando o scanner da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-706">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="d0490-707">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d0490-707">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="d0490-708">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="d0490-708">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="d0490-709">As responsabilidades dos pré-requisitos do cliente incluem:</span><span class="sxs-lookup"><span data-stu-id="d0490-709">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-710">Uma lista de locais de compartilhamento de arquivos a serem verificados.</span><span class="sxs-lookup"><span data-stu-id="d0490-710">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="d0490-711">Uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="d0490-711">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="d0490-712">Noções básicas sobre qualquer restrição regulatória ou requisitos relacionados ao gerenciamento de chaves.</span><span class="sxs-lookup"><span data-stu-id="d0490-712">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-713">Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-713">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="d0490-714">Rótulos configurados para classificação e proteção.</span><span class="sxs-lookup"><span data-stu-id="d0490-714">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="d0490-715">Todos os pré-requisitos para o scanner da Proteção de Informações do Azure estão em uso.</span><span class="sxs-lookup"><span data-stu-id="d0490-715">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="d0490-716">Para saber mais, confira Pré-requisitos para instalar e implantar o scanner de rotulagem unificado da Proteção de Informações do <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-716">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="d0490-717">Certifique-se de que os dispositivos do usuário estão executando um sistema operacional com suporte e tenham os pré-requisitos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="d0490-717">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="d0490-718">Consulte o seguinte para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="d0490-718">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="d0490-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia do Administrador: Instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </span><span class="sxs-lookup"><span data-stu-id="d0490-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="d0490-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="d0490-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="d0490-721">Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector RMS do Active Directory (AD RMS) para suporte híbrido.</span><span class="sxs-lookup"><span data-stu-id="d0490-721">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="d0490-722">Configure e configure BYOK (Traga sua própria chave), DKE (criptografia de chave dupla) (somente cliente de rotulagem unificada) ou MANTENHA sua própria chave (HYOK) (somente cliente clássico) caso você rebaixe uma destas opções para sua implantação.</span><span class="sxs-lookup"><span data-stu-id="d0490-722">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="d0490-723"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-723"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="d0490-724">Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado em nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="d0490-724">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="d0490-725">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="d0490-725">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="d0490-726">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-726">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-727">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="d0490-727">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="d0490-728">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="d0490-728">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="d0490-729">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-729">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-730">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="d0490-730">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-731">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-731">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-732">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="d0490-732">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-733">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-733">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-734">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="d0490-734">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-735">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="d0490-735">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="d0490-736">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-736">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-737">Implantação de email, redes sem fio e perfis VPN se você tiver uma autoridade de certificação, rede sem fio ou infraestrutura VPN existente em sua organização.</span><span class="sxs-lookup"><span data-stu-id="d0490-737">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="d0490-738">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="d0490-738">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="d0490-739">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="d0490-739">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-740">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="d0490-740">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="d0490-741">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="d0490-741">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="d0490-742">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="d0490-742">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-743">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-743">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="d0490-744">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="d0490-744">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-745">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="d0490-745">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="d0490-746">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-746">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="d0490-747">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="d0490-747">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-748">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="d0490-748">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-749">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-749">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="d0490-750">
  
</li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-750">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="d0490-751">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-751">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="d0490-752">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="d0490-752">The exact steps depend on your source environment.</span></span> <span data-ttu-id="d0490-753">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-753">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="d0490-754">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="d0490-754">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="d0490-755">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="d0490-755">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="d0490-756">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="d0490-756">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="d0490-757">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d0490-757">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="d0490-758">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="d0490-758">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-759">Fornecer orientação sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.</span><span class="sxs-lookup"><span data-stu-id="d0490-759">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="d0490-760">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-760">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="d0490-761">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-761">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="d0490-762"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="d0490-762"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="d0490-763">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="d0490-763">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="d0490-764">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="d0490-764">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-765">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="d0490-765">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="d0490-766">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="d0490-766">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-767">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-767">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="d0490-768">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-768">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-769">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-769">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="d0490-770">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-770">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="d0490-771">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-771">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="d0490-772"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-772"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="d0490-773"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="d0490-773"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="d0490-774">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-774">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="d0490-775"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-775"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="d0490-776"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-776"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="d0490-777">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="d0490-777">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="d0490-778">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="d0490-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="d0490-779"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-779"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="d0490-780">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="d0490-780">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="d0490-781">Windows 10</span><span class="sxs-lookup"><span data-stu-id="d0490-781">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-782"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-782"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-783"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-783"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-784"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-784"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d0490-785"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-785"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="d0490-786">Fornecemos orientações para atualizar do Windows 7 Professional e Windows 8.1 Professional para o Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="d0490-786">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="d0490-787">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-787">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-788">Entender a sua intenção do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-788">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="d0490-789">Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).</span><span class="sxs-lookup"><span data-stu-id="d0490-789">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="d0490-790">Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-790">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="d0490-791">Recomendamos opções para você avaliar os aplicativos do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-791">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="d0490-792">Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="d0490-792">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="d0490-793">Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="d0490-793">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="d0490-794">Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="d0490-794">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-795">Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.</span><span class="sxs-lookup"><span data-stu-id="d0490-795">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="d0490-796">Diretrizes de atualização para dar suporte ao seu movimento de implantação existente.</span><span class="sxs-lookup"><span data-stu-id="d0490-796">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="d0490-797">O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-797">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="d0490-798">As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="d0490-798">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="d0490-799">Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-799">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="d0490-800">Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-800">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="d0490-801">
  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-801">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-802">Atualizar o Configuration Manager para o Branch Atual.</span><span class="sxs-lookup"><span data-stu-id="d0490-802">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="d0490-803">Criar imagens personalizadas para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-803">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-804">Criar e dar suporte à implantação de scripts para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-804">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="d0490-805">Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).</span><span class="sxs-lookup"><span data-stu-id="d0490-805">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="d0490-806">Habilitar os recursos de segurança do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-806">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="d0490-807">Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="d0490-807">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="d0490-808">Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-808">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="d0490-809">Usar a Ferramenta de Migração de Estado do Usuário (USMT).</span><span class="sxs-lookup"><span data-stu-id="d0490-809">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="d0490-810">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="d0490-810">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="d0490-811">Para a atualização do computador, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="d0490-811">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-812">SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="d0490-812">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="d0490-813">Dispositivos: fator forma de desktop, notebook ou tablet.</span><span class="sxs-lookup"><span data-stu-id="d0490-813">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="d0490-814">SO de destino: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="d0490-814">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="d0490-815">Para atualização da infraestrutura, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="d0490-815">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-816">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d0490-816">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="d0490-817">A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-817">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="d0490-818">Para obter mais informações, confira a tabela de suporte do Configuration Manager em <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-818">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="d0490-819"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="d0490-820">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-820">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="d0490-821">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-821">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-822">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-822">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="d0490-823">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="d0490-823">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="d0490-824">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-824">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="d0490-825">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-825">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="d0490-826">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-826">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="d0490-827">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="d0490-827">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="d0490-828">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="d0490-828">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-829">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="d0490-829">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-830">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="d0490-830">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-831">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="d0490-831">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-832">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="d0490-832">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-833">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-833">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="d0490-834">Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="d0490-834">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="d0490-835">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="d0490-835">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-836">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="d0490-836">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="d0490-837">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-837">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="d0490-838">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="d0490-838">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="d0490-839">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="d0490-839">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="d0490-840">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="d0490-840">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-841">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-841">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-842">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="d0490-842">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-843">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="d0490-843">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-844">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="d0490-844">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-845">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="d0490-845">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-846">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="d0490-846">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="d0490-847">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="d0490-847">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="d0490-848"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-848"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-849">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-849">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="d0490-850">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="d0490-850">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="d0490-851">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="d0490-851">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="d0490-852">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="d0490-852">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-853">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="d0490-853">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-854">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="d0490-854">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-855">Linux.</span><span class="sxs-lookup"><span data-stu-id="d0490-855">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-856">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="d0490-856">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-857">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="d0490-857">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-858">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="d0490-858">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-859">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d0490-859">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-860">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-860">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-861">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d0490-861">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-862">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="d0490-862">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-863">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="d0490-863">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-864">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="d0490-864">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="d0490-865">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="d0490-865">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-866">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="d0490-866">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-867">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="d0490-867">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-868">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="d0490-868">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-869">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-869">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-870">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="d0490-870">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-871">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-871">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="d0490-872">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="d0490-872">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="d0490-873">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="d0490-873">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="d0490-874">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="d0490-874">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="d0490-875">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="d0490-875">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="d0490-876">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="d0490-876">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="d0490-877">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="d0490-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="d0490-878">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="d0490-878">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-879"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-879"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-880"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-880"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-881"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-881"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d0490-882"><strong>Área de Trabalho Virtual do Windows</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-882"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="d0490-883">Fornecemos orientações de implantação para integração à Área de Trabalho Virtual do Windows (um serviço de virtualização de aplicativo e área de trabalho).</span><span class="sxs-lookup"><span data-stu-id="d0490-883">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="d0490-884">A Área de Trabalho Virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para o Microsoft 365 Apps para Empresas com segurança e gerenciamento integrados para o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d0490-884">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="d0490-885">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="d0490-885">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="d0490-886">Implantar seu ambiente de Área de Trabalho Virtual do Windows com o Windows 10 Enterprise com várias sessões e o Microsoft 365 Apps para Empresas usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="d0490-886">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="d0490-887">Imagem do Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="d0490-887">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="d0490-888">Imagem compartilhada.</span><span class="sxs-lookup"><span data-stu-id="d0490-888">Shared image.</span></span></li>
<li><span data-ttu-id="d0490-889">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="d0490-889">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="d0490-890">Configurando o FSLogix:</span><span class="sxs-lookup"><span data-stu-id="d0490-890">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="d0490-891">Implantação do agente FSLogix com contêiner de perfil.</span><span class="sxs-lookup"><span data-stu-id="d0490-891">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="d0490-892">Implantação do FSLogix Agent com contêiner do Office.</span><span class="sxs-lookup"><span data-stu-id="d0490-892">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="d0490-893">Configurando a pasta FSLogix com exclusões de conteúdo.</span><span class="sxs-lookup"><span data-stu-id="d0490-893">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="d0490-894">Implantação do Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="d0490-894">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="d0490-895">Implantação do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d0490-895">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="d0490-896">Conectando-se usando clientes da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="d0490-896">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="d0490-897">

<strong>O exemplo a seguir está fora do escopo</strong>
</span><span class="sxs-lookup"><span data-stu-id="d0490-897">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="d0490-898">Gerenciamento de projetos da implantação da Área de Trabalho Virtual do Windows do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-898">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="d0490-899">Virtualização e implantação de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="d0490-899">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="d0490-900">Imagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="d0490-900">Custom images.</span></span></li>
<li><span data-ttu-id="d0490-901">Migrações e cenários envolvendo vMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="d0490-901">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="d0490-902">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="d0490-902">Linux scenarios.</span></span></li>
<li><span data-ttu-id="d0490-903">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="d0490-903">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="d0490-904">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="d0490-904">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="d0490-905">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="d0490-905">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="d0490-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento da Área de Trabalho Virtual do Windows.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="d0490-907">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="d0490-907">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="d0490-908">Criação e sub-rede da rede virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="d0490-908">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="d0490-909">Grupos de segurança de firewall e de rede.</span><span class="sxs-lookup"><span data-stu-id="d0490-909">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="d0490-910">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="d0490-910">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="d0490-911">Roteamento para o Azure a partir do local.</span><span class="sxs-lookup"><span data-stu-id="d0490-911">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="d0490-912">Regras de firewall para permitir a conectividade com a Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="d0490-912">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="d0490-913">Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Área de Trabalho Remota com suporte.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-913">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="d0490-914">Configuração geral do Azure AD:</span><span class="sxs-lookup"><span data-stu-id="d0490-914">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="d0490-915">Estratégia de <i>identidade (você pode usar apenas uma das três opções a seguir):</i>
</span><span class="sxs-lookup"><span data-stu-id="d0490-915">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="d0490-916">Active Directory com Azure AD Connect no Azure.</span><span class="sxs-lookup"><span data-stu-id="d0490-916">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="d0490-917">Active Directory com o Azure AD Connect local por VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="d0490-917">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="d0490-918">Active Directory Domain Services (AD DS).</span><span class="sxs-lookup"><span data-stu-id="d0490-918">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="d0490-919">Garantia do aplicativo</span><span class="sxs-lookup"><span data-stu-id="d0490-919">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-920"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-920"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-921"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-921"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-922"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-922"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="d0490-923"><strong>Garantia de Aplicativo</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-923"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="d0490-924">A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="d0490-924">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="d0490-925">Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais.</span><span class="sxs-lookup"><span data-stu-id="d0490-925">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="d0490-926">Também fornecemos orientações para clientes que enfrentam problemas de compatibilidade ao implantar a Área de Trabalho Virtual do Windows e o Microsoft Edge e fazer todo o possível para resolver problemas de compatibilidade.</span><span class="sxs-lookup"><span data-stu-id="d0490-926">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="d0490-927">Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:</span><span class="sxs-lookup"><span data-stu-id="d0490-927">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="d0490-928"><strong>Windows 10 </strong> (incluindo dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="d0490-928"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="d0490-929"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="d0490-929"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="d0490-930"><strong>Microsoft Edge -</strong> Para obter diretrizes de implantação, <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">consulte Visão geral dos canais do Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-930"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="d0490-931"><strong>Área de Trabalho Virtual do</strong> - Windows Para obter mais informações, consulte O que é a Área de Trabalho Virtual do <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows?</a> e perguntas frequentes sobre o <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise com várias sessões.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-931"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="d0490-932">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-932">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-933">Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="d0490-933">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="d0490-934">Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-934">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="d0490-935">Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-935">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="d0490-936">Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d0490-936">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="d0490-937">Para obter mais informações, confira <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</span><span class="sxs-lookup"><span data-stu-id="d0490-937">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="d0490-938">Serviços de embalagem do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-938">App packaging-only services.</span></span> <span data-ttu-id="d0490-939">No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-939">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="d0490-940">

<strong>As responsabilidades do cliente incluem</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-940">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="d0490-941">Criar um inventário de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="d0490-941">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="d0490-942">Validando esses aplicativos no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="d0490-942">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="d0490-943">
<strong>Observação:</strong>  A Microsoft não pode fazer alterações no código-fonte.</span><span class="sxs-lookup"><span data-stu-id="d0490-943">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="d0490-944">No entanto, a equipe da Garantia de Aplicativo da Área de Trabalho pode fornecer orientações para os desenvolvedores de aplicativo se o código-fonte estiver disponível para os aplicativos.</span><span class="sxs-lookup"><span data-stu-id="d0490-944">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="d0490-945">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="d0490-945">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="d0490-946"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="d0490-946"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-947">Os aplicativos que funcionavam no Windows 7, Windows 8.1, Office 2010 e Office 2013 também funcionam no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="d0490-947">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-948">
<strong>Windows 10 no ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="d0490-948">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="d0490-949">Os aplicativos que funcionaam no Windows 7, Office 2010 ou versões posteriores também funcionam no Windows 10 e no Microsoft 365 Apps em dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="d0490-949">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="d0490-950">
  <strong>Observação:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="d0490-950">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="d0490-951">A emulação x64 (64 bits) está disponível na visualização para clientes que participam do <a href="https://insider.windows.com/">Programa Windows Insider.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-951">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="d0490-952">Para clientes que não são do Windows Insider na versão 2004 do Windows 2004 (ou posterior), o PHOTOSHOP ARM64 tem suporte usando o OpenCL e o <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="d0490-952">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="d0490-953">Os clientes no Programa Windows Insider podem baixar uma versão do Insider do OpenCL e do Pacote de Compatibilidade do OpenGL para uso com aplicativos adicionais.</span><span class="sxs-lookup"><span data-stu-id="d0490-953">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="d0490-954">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="d0490-954">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-955">Se seus sites ou aplicativos Web funcionarem no Internet Explorer 11, nas versões compatíveis do Google Chrome ou em qualquer versão do Microsoft Edge, eles também funcionarão com o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="d0490-955">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-956">À medida que a Web está em constante evolução, <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">certifique-se</a>de revisar esta lista publicada de alterações conhecidas que a impactam na compatibilidade do site para o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="d0490-956">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-957">
  <strong>Área de Trabalho Virtual do Windows</strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-957">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="d0490-958">Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="d0490-958">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-959">Os aplicativos em execução em qualquer ambiente de VDI (infraestrutura de área de trabalho virtual) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="d0490-959">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-960">Os aplicativos em execução em dispositivos cliente do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="d0490-960">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="d0490-961">
  <strong>Observação:</strong> As exclusões e limitações de compatibilidade de várias sessões do Windows 10 Enterprise incluem:</span><span class="sxs-lookup"><span data-stu-id="d0490-961">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="d0490-962">Redirecionamento limitado de hardware.</span><span class="sxs-lookup"><span data-stu-id="d0490-962">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-963">Aplicativos de uso intensivo de A/V podem ser executados com uma capacidade reduzida.</span><span class="sxs-lookup"><span data-stu-id="d0490-963">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="d0490-964">Não há suporte para aplicativos de 16 bits na Área de Trabalho Virtual do Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="d0490-964">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="d0490-965">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="d0490-965">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d0490-966"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-966"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d0490-967"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-967"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="d0490-968"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="d0490-968"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="d0490-969"><strong>Microsoft Edge</strong> (para clientes do Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="d0490-969"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="d0490-970">Fornecemos orientações de implantação remota e assistência de compatibilidade para: implantação do Microsoft Edge no Windows 10 Enterprise com o Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="d0490-970">We provide remote deployment guidance and compatibility assistance for: Deploying Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="d0490-971">Configuração do Microsoft Edge (usando políticas de grupo ou configuração do aplicativo do Intune e políticas de aplicativos).</span><span class="sxs-lookup"><span data-stu-id="d0490-971">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="d0490-972">Inventariar a lista dos sites que podem exigir o uso no modo do Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="d0490-972">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="d0490-973">Habilitação do modo do Internet Explorer com a lista de sites corporativos existente.</span><span class="sxs-lookup"><span data-stu-id="d0490-973">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="d0490-974">Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional.</span><span class="sxs-lookup"><span data-stu-id="d0490-974">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="d0490-975">Consulte <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">Garantia de Aplicativo</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="d0490-975">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="d0490-976">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="d0490-976">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="d0490-977">Gerenciamento de projetos de implantação do Microsoft Edge do cliente.</span><span class="sxs-lookup"><span data-stu-id="d0490-977">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="d0490-978">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="d0490-978">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

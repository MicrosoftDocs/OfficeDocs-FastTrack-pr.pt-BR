---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: 7071187e2bc2b52930a03b4bf9dabd4f717b88df
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827101"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="09ff7-104">Produtos e Recursos</span><span class="sxs-lookup"><span data-stu-id="09ff7-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="09ff7-105">Serviços e cenários com suportados pelo FastTrack</span><span class="sxs-lookup"><span data-stu-id="09ff7-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="09ff7-106">Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar.</span><span class="sxs-lookup"><span data-stu-id="09ff7-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="09ff7-107">Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="09ff7-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="09ff7-108">O FastTrack fornece orientações para ajudá-lo primeiro com os principais recursos (comuns para todos os serviços online da Microsoft) e, em seguida, com a integração de cada serviço qualificado:</span><span class="sxs-lookup"><span data-stu-id="09ff7-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="09ff7-109">Geral</span><span class="sxs-lookup"><span data-stu-id="09ff7-109">General</span></span>](#general)
  - [<span data-ttu-id="09ff7-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="09ff7-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="09ff7-111">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="09ff7-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="09ff7-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="09ff7-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="09ff7-113">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="09ff7-113">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="09ff7-114">Garantia do Aplicativo</span><span class="sxs-lookup"><span data-stu-id="09ff7-114">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="09ff7-115">O novo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="09ff7-115">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="09ff7-116">Para saber mais sobre as expectativas de ambiente de origem para o Office 365 US Government, confira [Expectativas de Ambiente de Origem para o Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="09ff7-116">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="09ff7-117">Geral</span><span class="sxs-lookup"><span data-stu-id="09ff7-117">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-118"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-118"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-119"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-119"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-120"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-120"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09ff7-121"><strong>Integração principal</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-121"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-122">Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-122">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="09ff7-123">Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-123">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="09ff7-124">A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.</span><span class="sxs-lookup"><span data-stu-id="09ff7-124">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="09ff7-125"></li>
</ul>  

<strong>Integração de identidade</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-125"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="09ff7-126">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-126">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="09ff7-127">Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</span><span class="sxs-lookup"><span data-stu-id="09ff7-127">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="09ff7-128">Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-128">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="09ff7-129">Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</span><span class="sxs-lookup"><span data-stu-id="09ff7-129">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="09ff7-130">Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="09ff7-130">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="09ff7-131">Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="09ff7-131">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="09ff7-132">Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-132">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="09ff7-133">Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</span><span class="sxs-lookup"><span data-stu-id="09ff7-133">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="09ff7-134">Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-134">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="09ff7-135">Habilitar o provisionamento automático do usuário para aplicativos SaaS pré-integrados, como listados na <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Lista de tutoriais de integração de aplicativos</a>, (limitado apenas ao provisionamento de saída e de aplicativos SaaS da galeria do Azure AD).</span><span class="sxs-lookup"><span data-stu-id="09ff7-135">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="09ff7-136"><strong>Habilitação de rede </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="09ff7-136"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="09ff7-137">Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-137">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="09ff7-138"><strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:</span><span class="sxs-lookup"><span data-stu-id="09ff7-138"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-139">Uma única floresta do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="09ff7-139">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-140">Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="09ff7-140">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-141">Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="09ff7-141">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-142">Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="09ff7-142">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-143">Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.</span><span class="sxs-lookup"><span data-stu-id="09ff7-143">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-144">Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-144">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="09ff7-145">
  <strong>Importante:</strong>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-145">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="09ff7-146">Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.</span><span class="sxs-lookup"><span data-stu-id="09ff7-146">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-147">Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis.</span><span class="sxs-lookup"><span data-stu-id="09ff7-147">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="09ff7-148">Namespaces SMTP primários entre organizações do Exchange também devem ser separados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-148">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="09ff7-149">Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-149">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-150">Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-150">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="09ff7-151">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-151">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-152"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-152"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-153">Fornecemos orientações de implantação remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-153">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-154">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="09ff7-154">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-155">Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="09ff7-155">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-156">Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="09ff7-156">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-157">Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="09ff7-157">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-158">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-158">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-159">Seleção e configuração de uma instalação local ou na nuvem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-159">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-160">Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.</span><span class="sxs-lookup"><span data-stu-id="09ff7-160">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-161">Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="09ff7-161">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="09ff7-162">Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-162">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="09ff7-163">Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="09ff7-163">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="09ff7-164">O software cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-164">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-165"><strong>Integridade da rede</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-165"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-166">Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-166">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="09ff7-167">Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.</span><span class="sxs-lookup"><span data-stu-id="09ff7-167">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="09ff7-168">Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.</span><span class="sxs-lookup"><span data-stu-id="09ff7-168">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="09ff7-169">Acesso ao Centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-169">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-170">São necessárias versões atualizadas dos aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-170">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-171">Serviços de localização habilitados conforme as <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-171">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="09ff7-172">Office 365</span><span class="sxs-lookup"><span data-stu-id="09ff7-172">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-173"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-173"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-174"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-174"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-175"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-175"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09ff7-176"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-176"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-177">Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email.</span><span class="sxs-lookup"><span data-stu-id="09ff7-177">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="09ff7-178">As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.</span><span class="sxs-lookup"><span data-stu-id="09ff7-178">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="09ff7-179">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-179">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-180">Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-180">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-181">Apontar seus registros de troca de mensagens (MX) para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-181">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-182">Configurar o recurso do Office 365 ATP se ele fizer parte do seu serviço de assinatura.</span><span class="sxs-lookup"><span data-stu-id="09ff7-182">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="09ff7-183">Para mais informações, veja a parte dessa tabela <strong>Proteção Avançada contra Ameaças do Office 365</strong>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-183">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-p113">Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="09ff7-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="09ff7-p114">Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="09ff7-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="09ff7-188">
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-188">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="09ff7-189">A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="09ff7-189">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="09ff7-190">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="09ff7-190">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-191">Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).</span><span class="sxs-lookup"><span data-stu-id="09ff7-191">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-192">Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).</span><span class="sxs-lookup"><span data-stu-id="09ff7-192">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-193">Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-193">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-194">Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="09ff7-194">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="09ff7-195">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-195">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="09ff7-196">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-196">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="09ff7-197">Seu ambiente de origem deve ter um dos seguintes níveis mínimos:</span><span class="sxs-lookup"><span data-stu-id="09ff7-197">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-198">Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.</span><span class="sxs-lookup"><span data-stu-id="09ff7-198">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-199">Um único ambiente de email compatível com o protocolo IMAP.</span><span class="sxs-lookup"><span data-stu-id="09ff7-199">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-200">Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).</span><span class="sxs-lookup"><span data-stu-id="09ff7-200">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-201">Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-201">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-202">Software cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, o cliente de sincronização do OneDrive for Business, o Power BI desktop e o Skype for Business devem estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos de sistema do Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-202">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-203"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-203"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-204">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-204">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-205">Governança de Informações.</span><span class="sxs-lookup"><span data-stu-id="09ff7-205">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-206">Rótulos e diretivas de retenção.</span><span class="sxs-lookup"><span data-stu-id="09ff7-206">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-207">Gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="09ff7-207">Records management.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-208">Diretivas de exclusão.</span><span class="sxs-lookup"><span data-stu-id="09ff7-208">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-209">Conformidade da comunicação.</span><span class="sxs-lookup"><span data-stu-id="09ff7-209">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-210">Gerenciamento de risco interno.</span><span class="sxs-lookup"><span data-stu-id="09ff7-210">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-211">Descoberta Eletrônica Avançada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-211">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-212">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="09ff7-212">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-213"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-213"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-214">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-214">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-215">Classificação de dados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-215">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-216">Tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="09ff7-216">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-217">Criação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-217">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-218">Aplicação de rótulos de confidencialidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-218">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-219">Rotulagem unificada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-219">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-220">Classificadores treináveis.</span><span class="sxs-lookup"><span data-stu-id="09ff7-220">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-221">Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-221">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-222">Publicar etiquetas usando políticas (manual e automática).</span><span class="sxs-lookup"><span data-stu-id="09ff7-222">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-223">Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-223">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-224">Criação de políticas DLP para dispositivos gerenciados pelo Microsoft Endpoint Manager.</span><span class="sxs-lookup"><span data-stu-id="09ff7-224">Creating DLP policies for devices managed by Microsoft Endpoint Manager.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-225">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="09ff7-225">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-226"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-226"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-227">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-227">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-228">Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-228">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-229">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="09ff7-229">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-230">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="09ff7-230">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-231">Confirmação da habilitação do Teams no seu locatário do Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-231">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-232">Habilitação ou desabilitação de licenças de usuário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-232">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-233">Avaliação Rede para o Teams:</span><span class="sxs-lookup"><span data-stu-id="09ff7-233">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-234">Verificações de porta e de ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-234">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-235">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="09ff7-235">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-236">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="09ff7-236">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="09ff7-237">Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="09ff7-237">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-238">Se aplicável, também forneceremos diretrizes para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-238">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-239">Dispositivos para a Sala do Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="09ff7-239">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="09ff7-240">Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catálogo de dispositivos do Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-240">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-241">Assistência remota com a configuração do lado do serviço de dispositivos de salas certificadas do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-241">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-242">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="09ff7-242">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="09ff7-243">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-243">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-244">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-244">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="09ff7-245">Sistema de Telefonia:</span><span class="sxs-lookup"><span data-stu-id="09ff7-245">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-246">Configuração da organização para as configurações padrão do Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="09ff7-246">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-247">Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):</span><span class="sxs-lookup"><span data-stu-id="09ff7-247">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-248">Atribuição de números a usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-248">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-249">Orientação de portabilidade do número local pela IU (interface do usuário) até 999.</span><span class="sxs-lookup"><span data-stu-id="09ff7-249">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-250">Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.</span><span class="sxs-lookup"><span data-stu-id="09ff7-250">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-251">Diretrizes de Roteamento Direto:</span><span class="sxs-lookup"><span data-stu-id="09ff7-251">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-252">Orientação de configuração da organização para o design direto de roteamento de cenários hospedados por parceiros, ou cenários implantados pelo cliente para até 10 sites.</span><span class="sxs-lookup"><span data-stu-id="09ff7-252">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="09ff7-253">Análise da configuração do controlador de borda da sessão (SBC).</span><span class="sxs-lookup"><span data-stu-id="09ff7-253">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="09ff7-254">Assistência remota com a configuração do plano de discagem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-254">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="09ff7-255">Configuração da rota de voz.</span><span class="sxs-lookup"><span data-stu-id="09ff7-255">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="09ff7-256">Bypass de mídia e otimização de mídia local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-256">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="09ff7-257">Habilitação dos eventos ao vivo do Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-257">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-258">Configuração e integração da organização com o Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="09ff7-258">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-259">Diretrizes para a transição do Skype for Business para o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-259">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="09ff7-260">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-260">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-261">Usuários habilitados para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-261">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-262">Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).</span><span class="sxs-lookup"><span data-stu-id="09ff7-262">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-263">Habilitado para Grupos do Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-263">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="09ff7-264">
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-264">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="09ff7-265">O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-265">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="09ff7-266">O Teams não oferece suporte para o SharePoint no local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-266">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="09ff7-267">
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio hospedadas no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-267">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="09ff7-268">Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect.</span><span class="sxs-lookup"><span data-stu-id="09ff7-268">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="09ff7-269">Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.</span><span class="sxs-lookup"><span data-stu-id="09ff7-269">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="09ff7-270">Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-270">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-271"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-271"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-272">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-272">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-273">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="09ff7-273">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-274">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="09ff7-274">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-275">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="09ff7-275">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-276">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="09ff7-276">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-277">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="09ff7-277">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-278"><strong>Outlook para iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-278"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-279">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-279">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-280">Baixe o Outlook para iOS e Android no Google Play e Apple App Store.</span><span class="sxs-lookup"><span data-stu-id="09ff7-280">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-281">Configurar contas e acessar a caixa de correio do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-281">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-282">Proteger o Outlook Mobile (para obter mais informações, confira <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).</span><span class="sxs-lookup"><span data-stu-id="09ff7-282">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="09ff7-283">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-283">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-284">Exchange Online configurado e licenças atribuídas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-284">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-285"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-285"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-286">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-286">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-287">Atribuição de licenças do Power BI.</span><span class="sxs-lookup"><span data-stu-id="09ff7-287">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-288">Implantação do aplicativo do Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="09ff7-288">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-289">Software cliente online como o Power BI desktop deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-289">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-290"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-290"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-291">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-291">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-292">Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.</span><span class="sxs-lookup"><span data-stu-id="09ff7-292">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-293">Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.</span><span class="sxs-lookup"><span data-stu-id="09ff7-293">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-294">Configurar o ERP (Pool de Recursos da Empresa).</span><span class="sxs-lookup"><span data-stu-id="09ff7-294">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-295">Criando seu primeiro projeto.</span><span class="sxs-lookup"><span data-stu-id="09ff7-295">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-296">O software de cliente online, como o Project for Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-296">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-297"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-297"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-298">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-298">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-299">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="09ff7-299">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-300">Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="09ff7-300">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-301">Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="09ff7-301">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-302">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-302">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-303">Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-303">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-304">Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="09ff7-304">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-305">O software de cliente online, como o Project for Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-305">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-306"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-306"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-307">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-307">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-308">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="09ff7-308">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-309">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="09ff7-309">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-310">Provisionar usuários e licenças.</span><span class="sxs-lookup"><span data-stu-id="09ff7-310">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="09ff7-311">Habilitar a criação de sites para o administrador do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-311">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="09ff7-312">Planejamento de conjuntos de sites.</span><span class="sxs-lookup"><span data-stu-id="09ff7-312">Planning site collections.</span></span></li>
<li><span data-ttu-id="09ff7-313">Proteção de conteúdo e gerenciamento de permissões.</span><span class="sxs-lookup"><span data-stu-id="09ff7-313">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="09ff7-314">Configuração de recursos do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-314">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="09ff7-315">Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.</span><span class="sxs-lookup"><span data-stu-id="09ff7-315">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-316">Método de migração.</span><span class="sxs-lookup"><span data-stu-id="09ff7-316">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-317">Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="09ff7-317">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-318">Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-318">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-319">Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="09ff7-319">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-320">Planejar e implementar a distribuição única (ou em fases) para todos os usuários.</span><span class="sxs-lookup"><span data-stu-id="09ff7-320">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-321">Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="09ff7-321">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="09ff7-322">Redirecionar ou mover pastas conhecidas para o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="09ff7-322">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="09ff7-323">Implantar o cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="09ff7-323">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="09ff7-324">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-324">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="09ff7-325">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-325">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="09ff7-326"><strong>Para o SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-326"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="09ff7-327">A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-327">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="09ff7-328">
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="09ff7-328">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="09ff7-329">Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.</span><span class="sxs-lookup"><span data-stu-id="09ff7-329">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="09ff7-330">
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-330">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="09ff7-331">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-331">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="09ff7-332">Para obter mais informações, consulte <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum Public Update Levels for SharePoint Hybrid Features</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-332">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="09ff7-333">
  <strong>Observação:</strong> Para obter informações sobre recursos multigeográfico, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">recursos de várias geografias no onedrive e no SharePoint Online no Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-333">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-334"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-334"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="09ff7-335">Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="09ff7-335">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="09ff7-336">O software cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-336">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="09ff7-337">Enterprise Mobility e Security</span><span class="sxs-lookup"><span data-stu-id="09ff7-337">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-338"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-338"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-339">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="09ff7-339">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="09ff7-340">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-340">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="09ff7-341">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="09ff7-341">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-342">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="09ff7-342">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-343">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="09ff7-343">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-344">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="09ff7-344">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-345">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="09ff7-345">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-346">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="09ff7-346">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-347">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-347">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-348">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-348">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-349">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-349">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-350">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="09ff7-350">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-351">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-351">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="09ff7-352">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-352">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-353">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="09ff7-353">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-354">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-354">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-355">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-355">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="09ff7-356">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-356">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-357">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-357">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-358">Gerenciar e controlar o acesso a contas de administrador privilegiadas com o gerenciamento de identidade privilegiada do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-358">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-359">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-359">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-360">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="09ff7-360">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="09ff7-361">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-361">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-362">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-362">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-363">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-363">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-364">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="09ff7-364">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="09ff7-365">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="09ff7-365">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09ff7-366"><strong>Proteção de Informações do Azure (P2 ou EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-366"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-367">Fornecemos orientações sobre como:</span><span class="sxs-lookup"><span data-stu-id="09ff7-367">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-368">Ativar e configurar o locatário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-368">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-369">Criar e configurar rótulos e políticas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-369">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-370">Aplicação de proteção de informações aos documentos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-370">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-371">Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="09ff7-371">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-372">Uso de arquivos em repouso com o scanner da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="09ff7-372">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-373">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="09ff7-373">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-374">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="09ff7-374">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="09ff7-375">Você já deve saber:</span><span class="sxs-lookup"><span data-stu-id="09ff7-375">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-376">Usar o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-376">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-377">Usar o Windows ou o iOS (outros SOs estão fora do escopo).</span><span class="sxs-lookup"><span data-stu-id="09ff7-377">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="09ff7-378">
<strong>Observação</strong>: os computadores e dispositivos móveis devem ser executados em um <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operacional</a> que suporte a Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="09ff7-378">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="09ff7-379">Ter seus principais locais de compartilhamento de arquivos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-379">Have your main file share locations.</span></span>  </li><span data-ttu-id="09ff7-380">
<strong>Observação</strong>: o suporte híbrido exige o conector AD RMS.</span><span class="sxs-lookup"><span data-stu-id="09ff7-380">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="09ff7-381">Ter uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-381">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-382">Entender as restrições normativas para o gerenciamento de chaves protegidas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-382">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="09ff7-383">
</ul>
  
<strong>Scanner da Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-383">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="09ff7-384">Você já deve saber:</span><span class="sxs-lookup"><span data-stu-id="09ff7-384">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="09ff7-385">Usar o Windows Server 2012 R2 ou o Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="09ff7-385">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-386">Ter uma conexão à Internet.</span><span class="sxs-lookup"><span data-stu-id="09ff7-386">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-387">Ter o Microsoft SQL Server 2012 em uma instância local ou remota.</span><span class="sxs-lookup"><span data-stu-id="09ff7-387">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-388">Ter uma conta de serviço criada para o Active Directory local e sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-388">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-389">Ter baixado AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="09ff7-389">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-390">Ter etiquetas configuradas para classificação/proteção automática.</span><span class="sxs-lookup"><span data-stu-id="09ff7-390">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-391"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-391"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-392">Fornecemos orientações sobre como preparar-se para usar o Intune como o gerenciamento de dispositivo móvel baseado em nuvem (MDM) e o provedor de gerenciamento de aplicativo móvel (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-392">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="09ff7-393">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="09ff7-393">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="09ff7-394">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="09ff7-394">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-395">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="09ff7-395">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-396">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="09ff7-396">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-397">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="09ff7-397">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-398">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="09ff7-398">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-399">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="09ff7-399">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-400">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-400">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-401">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="09ff7-401">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-402">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="09ff7-402">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-403">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-403">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-404">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="09ff7-404">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-405">Implantação de email, redes sem fio e perfis VPN se tiver uma autoridade de certificação existente, uma infraestrutura de rede sem fio ou VPN em sua organização.</span><span class="sxs-lookup"><span data-stu-id="09ff7-405">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-406">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="09ff7-406">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-407">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="09ff7-407">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-408">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="09ff7-408">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-409">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="09ff7-409">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-410">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="09ff7-410">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-411">Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="09ff7-411">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-412">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-412">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="09ff7-413">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-413">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-414">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="09ff7-414">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-415">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-415">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-416">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-416">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-417">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-417">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-418">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-418">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="09ff7-419">
  <strong>Observação</strong>: não há mais suporte para o gerenciamento de computador herdado desde 15 de outubro de 2020 em diante.</span><span class="sxs-lookup"><span data-stu-id="09ff7-419">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="09ff7-420"></li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-420"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="09ff7-421">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-421">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="09ff7-422">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-422">The exact steps depend on your source environment.</span></span> <span data-ttu-id="09ff7-423">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="09ff7-423">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="09ff7-424">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="09ff7-424">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-425">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-425">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-426">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="09ff7-426">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-427">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="09ff7-427">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-428">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="09ff7-428">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-429">Fornecimento de diretrizes sobre como configurar o gateway de gerenciamento de nuvem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-429">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-430">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-430">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-431">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-431">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="09ff7-432"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="09ff7-432"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="09ff7-433">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-433">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="09ff7-434">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="09ff7-434">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-435">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="09ff7-435">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-436">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="09ff7-436">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-437">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-437">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-438">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-438">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-439">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="09ff7-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-440">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-440">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="09ff7-441"><strong>Observação</strong>: o FastTrack não é compatível com a proteção do Outlook para iOS e Android com as políticas de caixa de correio de dispositivo móvel do Exchange.</span><span class="sxs-lookup"><span data-stu-id="09ff7-441"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="09ff7-442">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-442">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="09ff7-443">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-443">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="09ff7-444"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-444"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="09ff7-445"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="09ff7-445"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="09ff7-446">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-446">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="09ff7-447"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-447"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="09ff7-448"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-448"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="09ff7-449">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="09ff7-449">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="09ff7-450">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="09ff7-450">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="09ff7-451"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-451"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="09ff7-452">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="09ff7-452">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="09ff7-453"><strong>Implantar o Outlook para iOS e Android de forma segura com o Intune</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-453"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="09ff7-454">Identidades dos usuários habilitadas no Azure Active Directory para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-454">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-455">Exchange Online ou Exchange híbrido configurado com licenças de usuário atribuídas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-455">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="09ff7-456">Windows 10</span><span class="sxs-lookup"><span data-stu-id="09ff7-456">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-457"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-457"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-458"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-458"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-459"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-459"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09ff7-460"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-460"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-461">Fornecemos orientações para a atualização do Windows 7 Professional e do Windows 8,1 Professional para o Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="09ff7-461">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="09ff7-462">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-462">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-463">Entender a sua intenção do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-463">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-464">Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).</span><span class="sxs-lookup"><span data-stu-id="09ff7-464">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-465">Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-465">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-466">Recomendamos opções para você avaliar os aplicativos do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-466">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-467">Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="09ff7-467">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-468">Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="09ff7-468">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-469">Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="09ff7-469">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-470">Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.</span><span class="sxs-lookup"><span data-stu-id="09ff7-470">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-471">Diretrizes de atualização para dar suporte ao seu movimento de implantação existente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-471">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="09ff7-472">O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-472">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="09ff7-473">As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="09ff7-473">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-474">Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-474">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="09ff7-475">Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-475">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="09ff7-476">
  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-476">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="09ff7-477">Atualizar o Configuration Manager para o Branch Atual.</span><span class="sxs-lookup"><span data-stu-id="09ff7-477">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-478">Criar imagens personalizadas para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-478">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-479">Criar e dar suporte à implantação de scripts para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-479">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-480">Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).</span><span class="sxs-lookup"><span data-stu-id="09ff7-480">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-481">Habilitar os recursos de segurança do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-481">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-482">Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="09ff7-482">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-483">Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-483">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-484">Usar a Ferramenta de Migração de Estado do Usuário (USMT).</span><span class="sxs-lookup"><span data-stu-id="09ff7-484">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-485">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="09ff7-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="09ff7-486">Para a atualização do computador, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="09ff7-486">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-487">SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="09ff7-487">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-488">Dispositivos: fator forma de desktop, notebook ou tablet.</span><span class="sxs-lookup"><span data-stu-id="09ff7-488">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-489">SO de destino: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="09ff7-489">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="09ff7-490">Para atualização da infraestrutura, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="09ff7-490">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-491">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="09ff7-491">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-492">A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-492">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="09ff7-493">Para obter mais informações, confira a tabela de suporte do Configuration Manager em <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-493">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="09ff7-494"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-494"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-495">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-495">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="09ff7-496">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-496">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-497">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-497">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-498">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-498">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-499">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-499">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-500">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-500">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-501">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="09ff7-501">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-502">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="09ff7-502">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-503">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="09ff7-503">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-504">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="09ff7-504">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-505">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="09ff7-505">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-506">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="09ff7-506">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-507">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="09ff7-507">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-508">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-508">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-509">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="09ff7-509">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-510">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="09ff7-510">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-511">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="09ff7-511">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-512">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="09ff7-512">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-513">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="09ff7-513">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-514">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="09ff7-514">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-515">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-515">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-516">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="09ff7-516">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-517">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="09ff7-517">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-518">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="09ff7-518">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-519">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="09ff7-519">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-520">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="09ff7-520">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="09ff7-521">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="09ff7-521">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="09ff7-522"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-522"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="09ff7-523">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-523">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-524">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-524">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-525">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="09ff7-525">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-526">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="09ff7-526">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-527">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="09ff7-527">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-528">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="09ff7-528">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-529">Linux.</span><span class="sxs-lookup"><span data-stu-id="09ff7-529">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-530">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="09ff7-530">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-531">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="09ff7-531">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-532">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="09ff7-532">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-533">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="09ff7-533">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-534">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="09ff7-534">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-535">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="09ff7-535">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-536">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="09ff7-536">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-537">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="09ff7-537">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-538">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="09ff7-538">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="09ff7-539">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="09ff7-539">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-540">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="09ff7-540">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-541">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="09ff7-541">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-542">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="09ff7-542">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-543">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-543">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-544">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="09ff7-544">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-545">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="09ff7-545">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="09ff7-546">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="09ff7-546">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-547">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="09ff7-547">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-548">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="09ff7-548">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-549">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-549">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-550">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="09ff7-550">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="09ff7-551">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="09ff7-551">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="09ff7-552">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="09ff7-552">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-553"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-553"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-554"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-554"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-555"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-555"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09ff7-556"><strong>Área de Trabalho Virtual do Windows</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-556"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="09ff7-557">Fornecemos orientações de implantação para integração com a área de trabalho virtual do Windows (um serviço de virtualização de desktop e aplicativos).</span><span class="sxs-lookup"><span data-stu-id="09ff7-557">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="09ff7-558">A área de trabalho virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para aplicativos da Microsoft 365 para empresas com segurança e gerenciamento integrados para o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="09ff7-558">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="09ff7-559">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="09ff7-559">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="09ff7-560">Implantação do ambiente de área de trabalho virtual do Windows com o Windows 10 Enterprise com várias sessões e o Microsoft 365 aplicativos para empresas usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="09ff7-560">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="09ff7-561">Imagem do Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="09ff7-561">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="09ff7-562">Imagem compartilhada.</span><span class="sxs-lookup"><span data-stu-id="09ff7-562">Shared image.</span></span></li>
<li><span data-ttu-id="09ff7-563">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="09ff7-563">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="09ff7-564">Configurando o FSLogix:</span><span class="sxs-lookup"><span data-stu-id="09ff7-564">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="09ff7-565">Implantando o agente FSLogix com contêiner de perfil.</span><span class="sxs-lookup"><span data-stu-id="09ff7-565">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="09ff7-566">Implantando o agente do FSLogix com o contêiner do Office.</span><span class="sxs-lookup"><span data-stu-id="09ff7-566">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="09ff7-567">Configurando a pasta FSLogix com exclusões de conteúdo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-567">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="09ff7-568">Implantar o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="09ff7-568">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="09ff7-569">Implantação do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="09ff7-569">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="09ff7-570">Conexão usando clientes da área de trabalho virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="09ff7-570">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="09ff7-571">

<strong>O seguinte está fora do escopo</strong>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-571">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="09ff7-572">Gerenciamento de projetos da implantação de área de trabalho virtual do Windows do cliente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-572">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="09ff7-573">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-573">On-site support.</span></span></li>
<li><span data-ttu-id="09ff7-574">Virtualização e implantação de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="09ff7-574">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="09ff7-575">Imagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="09ff7-575">Custom images.</span></span></li>
<li><span data-ttu-id="09ff7-576">Migrações e cenários envolvendo VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="09ff7-576">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="09ff7-577">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="09ff7-577">Linux scenarios.</span></span></li>
<li><span data-ttu-id="09ff7-578">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="09ff7-578">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="09ff7-579">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="09ff7-579">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="09ff7-580">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="09ff7-580">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="09ff7-581"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento de área de trabalho virtual do Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-581"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="09ff7-582">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="09ff7-582">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="09ff7-583">Criação e sub-rede de rede virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="09ff7-583">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="09ff7-584">Grupos de segurança de rede e firewall.</span><span class="sxs-lookup"><span data-stu-id="09ff7-584">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="09ff7-585">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="09ff7-585">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="09ff7-586">Roteamento para o Azure no local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-586">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="09ff7-587">Regras de firewall para permitir a conectividade com a área de trabalho virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="09ff7-587">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="09ff7-588">Confira mais informações em <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> clientes de área de trabalho remota compatíveis</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-588">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="09ff7-589">Configuração geral do Azure AD:</span><span class="sxs-lookup"><span data-stu-id="09ff7-589">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="09ff7-590">Estratégia de identidade <i>(você pode usar apenas uma das três opções a seguir):</i>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-590">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="09ff7-591">Active Directory com o Azure AD Connect no Azure.</span><span class="sxs-lookup"><span data-stu-id="09ff7-591">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="09ff7-592">Active Directory com o Azure AD Connect local via VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="09ff7-592">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="09ff7-593">Serviços de domínio do Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="09ff7-593">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="09ff7-594">Garantia do aplicativo</span><span class="sxs-lookup"><span data-stu-id="09ff7-594">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-595"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-595"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-596"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-596"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-597"><strong>Produtos suportados</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-597"><strong>Supported products</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-598"><strong>Garantia de Aplicativo</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-598"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="09ff7-599">A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="09ff7-599">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="09ff7-600">Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais.</span><span class="sxs-lookup"><span data-stu-id="09ff7-600">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="09ff7-601">Também fornecemos orientações para os clientes que enfrentam problemas de compatibilidade ao implantar a área de trabalho virtual do Windows e o novo Microsoft Edge e tornam cada esforço razoável para resolver problemas de compatibilidade.</span><span class="sxs-lookup"><span data-stu-id="09ff7-601">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="09ff7-602">Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:</span><span class="sxs-lookup"><span data-stu-id="09ff7-602">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="09ff7-603"><strong>Windows 10 </strong> (incluindo dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="09ff7-603"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="09ff7-604"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="09ff7-604"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="09ff7-605"><strong>O novo Microsoft Edge-</strong> Para obter diretrizes de implantação, confira <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">visão geral dos canais do Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-605"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-606"><strong>Área de trabalho</strong> - virtual do Windows Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">o que é a área de trabalho virtual do Windows?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">perguntas frequentes sobre várias sessões do Windows 10 Enterprise</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-606"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="09ff7-607">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-607">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="09ff7-608">Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="09ff7-608">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="09ff7-609">Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-609">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="09ff7-610">Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-610">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="09ff7-611">Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="09ff7-611">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="09ff7-612">Para obter mais informações, confira <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-612">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="09ff7-613">Serviços de embalagem do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-613">App packaging-only services.</span></span> <span data-ttu-id="09ff7-614">No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-614">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="09ff7-615">

<strong>Responsabilidades do cliente incluem</strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-615">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="09ff7-616">Criar um inventário de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="09ff7-616">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="09ff7-617">Validando esses aplicativos no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="09ff7-617">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="09ff7-618">
<strong>Observação:</strong>  A Microsoft não pode fazer alterações no código-fonte.</span><span class="sxs-lookup"><span data-stu-id="09ff7-618">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="09ff7-619">No entanto, a equipe da Garantia de Aplicativo da Área de Trabalho pode fornecer orientações para os desenvolvedores de aplicativo se o código-fonte estiver disponível para os aplicativos.</span><span class="sxs-lookup"><span data-stu-id="09ff7-619">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="09ff7-620">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="09ff7-620">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="09ff7-621"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-621"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-622">Os aplicativos que funcionavam no Windows 7, Windows 8.1, Office 2010 e Office 2013 também funcionam no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="09ff7-622">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-623">
<strong>Windows 10 no ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-623">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="09ff7-624">Os aplicativos que funcionaram no Windows 7, no Office 2010 ou nas versões posteriores funcionam em aplicativos do Windows 10 e Microsoft 365 em dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="09ff7-624">Apps that worked on Windows 7, Office 2010, or later versions work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="09ff7-625">
  <strong>Observação:</strong> As exclusões e limitações do Windows 10 no ARM incluem:</span><span class="sxs-lookup"><span data-stu-id="09ff7-625">
  <strong>Note:</strong> Windows 10 on ARM exclusions and limitations include:</span></span>
<ul>
<li>  
 <span data-ttu-id="09ff7-626">Aplicativos que dependem de drivers de software que não são compatíveis com o ARM.</span><span class="sxs-lookup"><span data-stu-id="09ff7-626">Apps that rely on software drivers that aren’t compatible in ARM.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-627">Aplicativos que usam OpenGL ou OpenCL.</span><span class="sxs-lookup"><span data-stu-id="09ff7-627">Apps that use OpenGL or OpenCL.</span></span>   
  </li>
<li>  
  <span data-ttu-id="09ff7-628">Os aplicativos estão disponíveis somente no 64-bit (x64).</span><span class="sxs-lookup"><span data-stu-id="09ff7-628">Apps only available in 64-bit (x64).</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-629">
<strong>O novo Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="09ff7-629">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-630">Se os seus sites ou aplicativo Web funcionarem no Internet Explorer 11, nas versões com suporte do Google Chrome ou em qualquer versão do Microsoft Edge, eles também funcionarão no novo Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="09ff7-630">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-631">Como a Web está em constante evolução, revise esta lista publicada de alterações conhecidas de <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">impacto na compatibilidade de site para o Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="09ff7-631">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-632">
  <strong>Área de Trabalho Virtual do Windows</strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-632">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="09ff7-633">Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="09ff7-633">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-634">Os aplicativos executados em qualquer ambiente VDI (Virtual Desktop Infrastructure) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da área de trabalho virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="09ff7-634">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-635">Os aplicativos executados nos dispositivos cliente do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da área de trabalho virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="09ff7-635">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="09ff7-636">
  <strong>Observação:</strong> As exclusões e limitações de compatibilidade de várias sessões do Windows 10 Enterprise incluem:</span><span class="sxs-lookup"><span data-stu-id="09ff7-636">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="09ff7-637">Redirecionamento limitado de hardware.</span><span class="sxs-lookup"><span data-stu-id="09ff7-637">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-638">Aplicativos de uso intensivo de A/V podem ser executados com uma capacidade reduzida.</span><span class="sxs-lookup"><span data-stu-id="09ff7-638">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="09ff7-639">Não há suporte para aplicativos de 16 bits na Área de Trabalho Virtual do Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="09ff7-639">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="09ff7-640">O novo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="09ff7-640">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09ff7-641"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-641"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="09ff7-642"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-642"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="09ff7-643"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="09ff7-643"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="09ff7-644"><strong>Microsoft Edge</strong> (para clientes do Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="09ff7-644"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="09ff7-645">Fornecemos assistência para a implantação e compatibilidade para: implantação do novo Microsoft Edge no Windows 10 Enterprise com o Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Microsoft Intune).</span><span class="sxs-lookup"><span data-stu-id="09ff7-645">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-646">Configuração do Microsoft Edge (usando políticas de grupo ou configuração do aplicativo do Intune e políticas de aplicativos).</span><span class="sxs-lookup"><span data-stu-id="09ff7-646">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="09ff7-647">Inventariar a lista dos sites que podem exigir o uso no modo do Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="09ff7-647">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="09ff7-648">Habilitação do modo do Internet Explorer com a lista de sites corporativos existente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-648">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="09ff7-649">Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional.</span><span class="sxs-lookup"><span data-stu-id="09ff7-649">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="09ff7-650">Consulte o <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">aplicativo garante</a> mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="09ff7-650">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="09ff7-651">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="09ff7-651">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="09ff7-652">Gerenciamento de projetos de implantação do Microsoft Edge do cliente.</span><span class="sxs-lookup"><span data-stu-id="09ff7-652">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="09ff7-653">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="09ff7-653">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

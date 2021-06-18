---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994860"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="f81ee-104">Produtos e Recursos</span><span class="sxs-lookup"><span data-stu-id="f81ee-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="f81ee-105">Serviços e cenários com suportados pelo FastTrack</span><span class="sxs-lookup"><span data-stu-id="f81ee-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="f81ee-106">Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar.</span><span class="sxs-lookup"><span data-stu-id="f81ee-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="f81ee-107">Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="f81ee-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="f81ee-108">FastTrack fornece orientações para ajudá-lo primeiro com os recursos principais (comuns para todos os Microsoft Online Services) e, em seguida, com a integração de cada serviço qualificado:</span><span class="sxs-lookup"><span data-stu-id="f81ee-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="f81ee-109">Geral</span><span class="sxs-lookup"><span data-stu-id="f81ee-109">General</span></span>](#general)
  - [<span data-ttu-id="f81ee-110">Segurança e conformidade</span><span class="sxs-lookup"><span data-stu-id="f81ee-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="f81ee-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="f81ee-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="f81ee-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f81ee-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="f81ee-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f81ee-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="f81ee-114">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="f81ee-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="f81ee-115">Garantia de Aplicativo</span><span class="sxs-lookup"><span data-stu-id="f81ee-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="f81ee-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f81ee-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="f81ee-117">Para saber mais sobre as expectativas de ambiente de origem para o Office 365 US Government, confira [Expectativas de Ambiente de Origem para o Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="f81ee-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="f81ee-118">Geral</span><span class="sxs-lookup"><span data-stu-id="f81ee-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-119"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-120"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-121"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f81ee-122"><strong>Integração principal</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-123">Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="f81ee-124">Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="f81ee-125">A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.</span><span class="sxs-lookup"><span data-stu-id="f81ee-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="f81ee-126"></li>
</ul>  

<strong>Integração de identidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="f81ee-127">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="f81ee-128">Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</span><span class="sxs-lookup"><span data-stu-id="f81ee-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="f81ee-129">Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="f81ee-130">Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</span><span class="sxs-lookup"><span data-stu-id="f81ee-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="f81ee-131">Escolhendo e habilitando uma experiência de autenticação mais conveniente para seus usuários com autenticação sem senha (FIDO)2 ou Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="f81ee-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="f81ee-132">Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f81ee-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="f81ee-133">Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="f81ee-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="f81ee-134">Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="f81ee-135">Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</span><span class="sxs-lookup"><span data-stu-id="f81ee-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="f81ee-136">Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="f81ee-137">Habilitando o provisionamento automático do usuário para aplicativos SaaS pré-integrados, conforme listado na lista <a href="/azure/active-directory/saas-apps/tutorial-list">de tutoriais </a> de integração de aplicativos (limitado a aplicativos SaaS da galeria do Azure AD e apenas provisionamento de saída).</span><span class="sxs-lookup"><span data-stu-id="f81ee-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="f81ee-138"><strong>Habilitação de rede </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="f81ee-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="f81ee-139">Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="f81ee-140"><strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:</span><span class="sxs-lookup"><span data-stu-id="f81ee-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-141">Uma única floresta do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f81ee-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-142">Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f81ee-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-143">Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f81ee-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-144">Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="f81ee-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-145">Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.</span><span class="sxs-lookup"><span data-stu-id="f81ee-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-146">Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="f81ee-147">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="f81ee-148">Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.</span><span class="sxs-lookup"><span data-stu-id="f81ee-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-149">Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis.</span><span class="sxs-lookup"><span data-stu-id="f81ee-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="f81ee-150">Namespaces SMTP primários entre organizações do Exchange também devem ser separados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="f81ee-151">Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-152">Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="f81ee-153">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f81ee-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-155">Fornecemos orientações de implantação remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-156">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-157">Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f81ee-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-158">Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="f81ee-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-159">Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="f81ee-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-160">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-161">Seleção e configuração de uma instalação local ou na nuvem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-162">Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-163">Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="f81ee-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="f81ee-164">Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="f81ee-165">Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f81ee-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f81ee-166">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos do sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-167"><strong>Integridade da rede</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-168">Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="f81ee-169">Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.</span><span class="sxs-lookup"><span data-stu-id="f81ee-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="f81ee-170">Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.</span><span class="sxs-lookup"><span data-stu-id="f81ee-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="f81ee-171">Acesso ao Centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-172">São necessárias versões atualizadas dos aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-173">Serviços de localização habilitados conforme as <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="f81ee-174">Segurança e Conformidade</span><span class="sxs-lookup"><span data-stu-id="f81ee-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-175"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-176"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-177"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="f81ee-178"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-179">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="f81ee-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f81ee-180">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f81ee-181">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f81ee-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="f81ee-182">Implantando FIDO2 ou Microsoft Authenticator App.</span><span class="sxs-lookup"><span data-stu-id="f81ee-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="f81ee-183">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="f81ee-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-184">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f81ee-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-185">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f81ee-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-186">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="f81ee-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-187">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f81ee-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-188">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-189">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-190">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-191">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="f81ee-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-192">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f81ee-193">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-194">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f81ee-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f81ee-195">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-196">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f81ee-197">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-198">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-199">Gerenciando e controlando o acesso a contas de administrador privilegiadas com o Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f81ee-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f81ee-200">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-201">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="f81ee-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f81ee-202">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-203">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-204">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-205">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="f81ee-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f81ee-206">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f81ee-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-207"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f81ee-208">Para obter mais informações sobre a Proteção de Informações do Azure, <strong>consulte Proteção de Informações da Microsoft</strong> nesta tabela.</span><span class="sxs-lookup"><span data-stu-id="f81ee-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="f81ee-209"><strong>Descobrir & Responder</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="f81ee-210"><strong>Descoberta Eletrônica Avançada</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="f81ee-211">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="f81ee-212">Criando um novo caso.</span><span class="sxs-lookup"><span data-stu-id="f81ee-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="f81ee-213">Colocar os custodiantes em espera.</span><span class="sxs-lookup"><span data-stu-id="f81ee-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-214">Realizando pesquisas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="f81ee-215">Adicionar os resultados da pesquisa a um conjunto de revisão.</span><span class="sxs-lookup"><span data-stu-id="f81ee-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="f81ee-216">Executando análises em um conjunto de revisão.</span><span class="sxs-lookup"><span data-stu-id="f81ee-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-217">Revisão e marcação de documentos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-218">Exportando dados do conjunto de revisão.</span><span class="sxs-lookup"><span data-stu-id="f81ee-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="f81ee-219">Importando dados não Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="f81ee-220"><strong>Auditoria Avançada</strong> (com suporte apenas no E5)</span><span class="sxs-lookup"><span data-stu-id="f81ee-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="f81ee-221">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="f81ee-222">Habilitando a auditoria avançada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="f81ee-223">Executando uma interface do usuário do log de auditoria de pesquisa e comandos básicos de auditoria do PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f81ee-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="f81ee-224">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f81ee-225">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f81ee-226">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f81ee-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f81ee-227">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f81ee-228">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f81ee-229">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f81ee-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f81ee-230">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f81ee-231">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f81ee-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f81ee-232">Scripts personalizados ou codificação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="f81ee-233">API de Descoberta Externa.</span><span class="sxs-lookup"><span data-stu-id="f81ee-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="f81ee-234">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="f81ee-235">Limites de conformidade e filtros de segurança.</span><span class="sxs-lookup"><span data-stu-id="f81ee-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="f81ee-236">Investigações de dados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="f81ee-237">Solicitações de assunto de dados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="f81ee-238">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f81ee-239">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f81ee-240">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="f81ee-241">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f81ee-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f81ee-242"><strong>Gerenciamento de riscos do Insider</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="f81ee-243">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="f81ee-244">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f81ee-245">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f81ee-246">Criar casos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="f81ee-247">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="f81ee-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="f81ee-248">Diretrizes sobre a criação do conector de recursos humanos (RH).</span><span class="sxs-lookup"><span data-stu-id="f81ee-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="f81ee-249">

<strong> Conformidade de comunicação </strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="f81ee-250">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="f81ee-251">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f81ee-252">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f81ee-253">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="f81ee-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="f81ee-254">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f81ee-255">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f81ee-256">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f81ee-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f81ee-257">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f81ee-258">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f81ee-259">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f81ee-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f81ee-260">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f81ee-261">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f81ee-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f81ee-262">Criando e gerenciando Power Automate fluxos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="f81ee-263">Conectores de dados (além do conector de RH).</span><span class="sxs-lookup"><span data-stu-id="f81ee-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="f81ee-264">Configurações de expressão regular personalizada (RegEx).</span><span class="sxs-lookup"><span data-stu-id="f81ee-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="f81ee-265">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f81ee-266">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="f81ee-267">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="f81ee-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="f81ee-268">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f81ee-269">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="f81ee-270">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f81ee-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="f81ee-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="f81ee-272">Microsoft 365 Defender é um pacote de defesa empresarial unificado de pré e pós-violação que coordena a detecção, a prevenção, a investigação e a resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="f81ee-273">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="f81ee-274">Fornecendo uma visão geral do centro Microsoft 365 segurança.</span><span class="sxs-lookup"><span data-stu-id="f81ee-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-275">Revisão de incidentes entre produtos, incluindo o foco no que é crítico, garantindo o escopo de ataque completo, os ativos afetados e as ações de correção automatizadas agrupadas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-276">Demonstrando como Microsoft 365 Defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidas por meio da auto-recuperação automatizada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="f81ee-277">Explicando e fornecendo exemplos de como os clientes podem procurar proativamente tentativas de invasão e atividades de violação que afetam seu email, dados, dispositivos e contas em vários conjuntos de dados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="f81ee-278">Mostrando aos clientes como eles podem revisar e melhorar a postura de segurança de forma holística usando a Pontuação Segura da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f81ee-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="f81ee-279"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f81ee-280">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f81ee-281">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f81ee-282">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="f81ee-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="f81ee-283">Como remediar ou interpretar os vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="f81ee-284">Como investigar um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f81ee-285">Busca personalizada de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="f81ee-286">Suporte <a href=" /fasttrack/us-gov-appendix-overview">GCC-High ou GCC-DoD (Office 365 Governo dos EUA)</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="f81ee-287">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API.</span><span class="sxs-lookup"><span data-stu-id="f81ee-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-289">Microsoft Cloud App Security é um Agente de Segurança do Cloud Access (CASB) que fornece visibilidade avançada, controle sobre viagens de dados e análises sofisticadas para identificar e combater ameaças cibernéticas em todos os serviços de nuvem da Microsoft e de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="f81ee-290">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-291">Configurando o portal, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f81ee-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="f81ee-292">Importando grupos de usuários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="f81ee-293">Gerenciando o acesso e as configurações do administrador.</span><span class="sxs-lookup"><span data-stu-id="f81ee-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="f81ee-294">Scoping sua implantação para selecionar determinados grupos de usuários para monitorar ou excluir do monitoramento.</span><span class="sxs-lookup"><span data-stu-id="f81ee-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="f81ee-295">Como configurar intervalos e marcas IP.</span><span class="sxs-lookup"><span data-stu-id="f81ee-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="f81ee-296">Personalizando a experiência do usuário final com seu logotipo e mensagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-297">Integrando serviços de primeira parte, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f81ee-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="f81ee-298">Microsoft Defender para Ponto de Extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="f81ee-299">Microsoft Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="f81ee-300">Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f81ee-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="f81ee-301">Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="f81ee-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-302">Configurando a descoberta na nuvem usando:</span><span class="sxs-lookup"><span data-stu-id="f81ee-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="f81ee-303">Microsoft Defender para Pontos de Extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="f81ee-304">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="f81ee-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="f81ee-305">iboss.</span><span class="sxs-lookup"><span data-stu-id="f81ee-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-306">Criando marcas e categorias de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="f81ee-307">Personalização de pontuações de risco de aplicativo com base nas prioridades da sua organização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="f81ee-308">Sancionando e desemanando aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="f81ee-309">Revisão dos painéis cloud app Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="f81ee-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="f81ee-310">Conectando <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> aplicativos em destaque</a> usando conectores de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="f81ee-311">Protegendo aplicativos com o Controle de Aplicativo de Acesso Condicional no Acesso Condicional nos portais de Segurança do Azure AD e cloud app.</span><span class="sxs-lookup"><span data-stu-id="f81ee-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="f81ee-312">Implantando o Controle de Aplicativo de Acesso Condicional para aplicativos em destaque.</span><span class="sxs-lookup"><span data-stu-id="f81ee-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="f81ee-313">Usando a atividade e os logs de arquivo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="f81ee-314">Gerenciando aplicativos OAuth.</span><span class="sxs-lookup"><span data-stu-id="f81ee-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="f81ee-315">Revisão e configuração de modelos de política.</span><span class="sxs-lookup"><span data-stu-id="f81ee-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="f81ee-316">Fornecendo assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> principais casos de uso para CASBs (incluindo a criação ou atualização de até seis (6) políticas), exceto:</span><span class="sxs-lookup"><span data-stu-id="f81ee-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="f81ee-317">Auditoria da configuração da internet como ambientes de serviço (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="f81ee-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="f81ee-318">Monitorando as atividades do usuário para proteger contra ameaças em seus ambientes iaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="f81ee-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-319">Noções básicas sobre a correlação de incidentes no portal do Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="f81ee-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="f81ee-320"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f81ee-321">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="f81ee-322">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f81ee-323">Discussões que comparam a Segurança do Aplicativo na Nuvem com outras ofertas CASB.</span><span class="sxs-lookup"><span data-stu-id="f81ee-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="f81ee-324">Configurando o Cloud App Security para atender a requisitos regulamentar ou de conformidade específicos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="f81ee-325">Implantando o serviço em um ambiente de produção que não seja de teste.</span><span class="sxs-lookup"><span data-stu-id="f81ee-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="f81ee-326">Implantando a Descoberta de Aplicativos na Nuvem como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="f81ee-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="f81ee-327">Suporte <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High ou GCC-DoD (Office 365 US Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="f81ee-328">Configurando a infraestrutura, a instalação ou a implantação de carregamentos de log automáticos para relatórios contínuos usando o Docker ou um coletor de log.</span><span class="sxs-lookup"><span data-stu-id="f81ee-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="f81ee-329">Criando um relatório de instantâneo de Descoberta na Nuvem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="f81ee-330">Bloqueando o uso do aplicativo usando scripts de bloqueio.</span><span class="sxs-lookup"><span data-stu-id="f81ee-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="f81ee-331">Conectando aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="f81ee-332">Integrando e implantando o Controle de Aplicativo de Acesso Condicional para aplicativos não em destaque.</span><span class="sxs-lookup"><span data-stu-id="f81ee-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="f81ee-333">Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção contra perda de dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="f81ee-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="f81ee-334">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="f81ee-335">Investigação e correção automatizadas, incluindo os playbooks do Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="f81ee-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="f81ee-336">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f81ee-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="f81ee-337"><strong>Microsoft Defender para Ponto de Extremidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-338">O Microsoft Defender for Endpoint é uma plataforma projetada para ajudar as redes corporativas a evitar, detectar, investigar e responder a ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f81ee-339">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-340">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-341">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-342">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-343">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-344">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="f81ee-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-345">Habilitando o serviço do Microsoft Defender para Ponto de Extremidade explicando como implantar um perfil de agente do Defender para Ponto de Extremidade usando um ponto de extremidade de integração.</span><span class="sxs-lookup"><span data-stu-id="f81ee-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-346">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="f81ee-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-347">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="f81ee-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-348">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="f81ee-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-349">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="f81ee-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-350">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="f81ee-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-351">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-352">Pontuação segura para dispositivos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="f81ee-353">Configuração do Microsoft Defender SmartScreen usando o Microsoft Endpoint Manager.</span><span class="sxs-lookup"><span data-stu-id="f81ee-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="f81ee-354">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="f81ee-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-355">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-356">Integrando o Microsoft Defender para Office 365 com o Microsoft Defender para Ponto de Extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-357">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f81ee-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-358">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="f81ee-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-359">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-360">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f81ee-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-361">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f81ee-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-362">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f81ee-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-363">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="f81ee-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-364">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="f81ee-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f81ee-365">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="f81ee-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f81ee-366"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f81ee-367">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="f81ee-368">Suporte <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High ou GCC-DoD (Office 365 US Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="f81ee-369">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-370">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-371">Integração ou configuração para os seguintes agentes do Microsoft Defender para Ponto de Extremidade:</span><span class="sxs-lookup"><span data-stu-id="f81ee-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-372">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="f81ee-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-373">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f81ee-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-374">Linux.</span><span class="sxs-lookup"><span data-stu-id="f81ee-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-375">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="f81ee-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="f81ee-376">Virtual Desktop Infrastructure (VDI) (persistente ou não persistente).</span><span class="sxs-lookup"><span data-stu-id="f81ee-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-377">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="f81ee-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-378">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="f81ee-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-379">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f81ee-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-380">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="f81ee-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-381">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f81ee-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-382">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="f81ee-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-383">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-384">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="f81ee-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f81ee-385">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="f81ee-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-386">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="f81ee-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-387">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="f81ee-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-388">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="f81ee-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-389">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="f81ee-390">Controle de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="f81ee-391">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-392">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="f81ee-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="f81ee-393">Configuração ou gerenciamento de recursos de proteção de conta como:</span><span class="sxs-lookup"><span data-stu-id="f81ee-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="f81ee-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="f81ee-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="f81ee-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="f81ee-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-396">Configuração ou gerenciamento do BitLocker.</span><span class="sxs-lookup"><span data-stu-id="f81ee-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="f81ee-397">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f81ee-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-398">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="f81ee-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-399">Registro ou configuração do Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="f81ee-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-400">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-401">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="f81ee-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="f81ee-402">Treinamento ou orientação sobre a configuração do Defender SmartScreen usando GPOs (Objetos de Política de Grupo), Segurança do Windows ou Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f81ee-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="f81ee-403">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f81ee-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="f81ee-404"><strong>Microsoft Defender para Identidade </strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="f81ee-405">O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="f81ee-406">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-407">Executando a ferramenta de sizing para planejamento de capacidade de recursos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="f81ee-408">Criando sua instância do Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="f81ee-409">Conectando o Defender para Identidade ao Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f81ee-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="f81ee-410">Implantando o sensor para capturar e analisar o tráfego de rede e Windows eventos diretamente de seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f81ee-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="f81ee-411">Baixando o pacote do sensor.</span><span class="sxs-lookup"><span data-stu-id="f81ee-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="f81ee-412">Configurando o sensor.</span><span class="sxs-lookup"><span data-stu-id="f81ee-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="f81ee-413">Instalando o sensor no controlador de domínio silenciosamente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="f81ee-414">Implantando o sensor em seu ambiente de várias florestas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="f81ee-415">Configurando o coletor Windows de eventos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="f81ee-416">Configurando o portal, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f81ee-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="f81ee-417">Integrando o Defender para Identidade com Microsoft Cloud App Security (Cloud App Security licenciamento não é necessário).</span><span class="sxs-lookup"><span data-stu-id="f81ee-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="f81ee-418">Configurando marcas de entidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="f81ee-419">Marcando contas confidenciais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="f81ee-420">Receber notificações por email para problemas de saúde e alertas de segurança.</span><span class="sxs-lookup"><span data-stu-id="f81ee-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="f81ee-421">Configurando exclusões de alerta.</span><span class="sxs-lookup"><span data-stu-id="f81ee-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="f81ee-422">Fornecendo diretrizes de implantação, assistência de configuração e educação em:</span><span class="sxs-lookup"><span data-stu-id="f81ee-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="f81ee-423">Noções básicas sobre o relatório de Avaliação de Postura de Segurança de Identidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="f81ee-424">Noções básicas sobre a Pontuação da Prioridade de Investigação de Usuário e o relatório de classificação de Investigação de Usuário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="f81ee-425">Noções básicas sobre o relatório do usuário inativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="f81ee-426">Explicação das opções de correção em uma conta comprometida.</span><span class="sxs-lookup"><span data-stu-id="f81ee-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="f81ee-427">Facilitando a migração do Advanced Threat Analytics (ATA) para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f81ee-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="f81ee-428"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="f81ee-429">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f81ee-430">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="f81ee-431">Implantando o Defender para Identidade como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="f81ee-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="f81ee-432">Suporte <a href=" /fasttrack/us-gov-appendix-overview">GCC-High ou GCC-DoD (Office 365 Governo dos EUA)</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="f81ee-433">Implantando ou executando as seguintes atividades do sensor Defender for Identity:</span><span class="sxs-lookup"><span data-stu-id="f81ee-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="f81ee-434">Planejamento de capacidade manual.</span><span class="sxs-lookup"><span data-stu-id="f81ee-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="f81ee-435">Executando a ferramenta auditoria.</span><span class="sxs-lookup"><span data-stu-id="f81ee-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="f81ee-436">Implantando o sensor autônomo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="f81ee-437">Implantando em servidores do Serviços de Federação do Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="f81ee-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="f81ee-438">Implantando o sensor usando um adaptador de NIC (Network Interface Card).</span><span class="sxs-lookup"><span data-stu-id="f81ee-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="f81ee-439">Implantando o sensor por meio de uma ferramenta de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="f81ee-440">Conectando-se ao serviço de nuvem Defender para Identidade por meio de uma conexão de proxy da Web.</span><span class="sxs-lookup"><span data-stu-id="f81ee-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="f81ee-441">Configurando a conta da Microsoft (MSA) no Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f81ee-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="f81ee-442">Criação e gerenciamento de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="f81ee-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="f81ee-443">Habilitando a Resolução de Nome de Rede (NNR).</span><span class="sxs-lookup"><span data-stu-id="f81ee-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="f81ee-444">Configuração do contêiner Objetos Excluídos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="f81ee-445">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="f81ee-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="f81ee-446">Correção ou interpretação de vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="f81ee-447">Investigando um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f81ee-448">Ameaça ou busca avançada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="f81ee-449">Resposta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="f81ee-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="f81ee-450">Fornecendo um tutorial do laboratório de alertas de segurança para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f81ee-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="f81ee-451">Fornecer notificação quando o Defender for Identity detecta atividades suspeitas enviando alertas de segurança para seu servidor de syslog por meio de um sensor nomeado.</span><span class="sxs-lookup"><span data-stu-id="f81ee-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="f81ee-452">Configurar o Defender para Identidade para realizar consultas usando o protocolo SAMR (gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="f81ee-453">Configurando soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="f81ee-454">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f81ee-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f81ee-455">Alinhado com os <a href="/defender-for-identity/prerequisites"> pré-requisitos</a>do Microsoft Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="f81ee-456">Active Directory implantado.</span><span class="sxs-lookup"><span data-stu-id="f81ee-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-457">Os controladores de domínio que você pretende instalar os sensores do Defender para Identidade têm conectividade com a Internet para o serviço de nuvem defender para identidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="f81ee-458">Seu firewall e proxy devem estar abertos para se comunicar com o serviço de nuvem Defender for Identity (\*.atp.azure.com porta 443 deve estar aberta).</span><span class="sxs-lookup"><span data-stu-id="f81ee-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-459">Controladores de domínio em execução em um dos seguintes:</span><span class="sxs-lookup"><span data-stu-id="f81ee-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="f81ee-460">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="f81ee-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="f81ee-461">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f81ee-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="f81ee-462">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="f81ee-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="f81ee-463">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f81ee-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="f81ee-464">Windows Server 2019 com KB4487044 (com build do sistema operacional 17763.316 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="f81ee-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-465">Microsoft .NET Framework 4.7 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="f81ee-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="f81ee-466">Um mínimo de cinco (5) GB de espaço em disco é necessário e 10 GB é recomendado.</span><span class="sxs-lookup"><span data-stu-id="f81ee-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="f81ee-467">Dois (2) núcleos e seis (6) GB de RAM instalados no controlador de domínio.</span><span class="sxs-lookup"><span data-stu-id="f81ee-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f81ee-468"><strong>Obter o Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-p114">O Microsoft Defender para Office 365 protege sua organização contra ameaças maliciosas representadas por mensagens de email, links (URLs) e ferramentas de colaboração. O Defender para Office 365 inclui:</span><span class="sxs-lookup"><span data-stu-id="f81ee-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="f81ee-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Políticas de proteção contra ameaças</a>: Defina políticas de proteção contra ameaças para definir o nível de proteção apropriado para sua organização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="f81ee-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Relatórios</a>: Exibir relatórios em tempo real para monitorar o Defender Office 365 desempenho em sua organização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="f81ee-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Recursos de investigação e resposta de ameaças</a>: use as ferramentas de ponta para investigar, compreender, simular e prevenir ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="f81ee-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Recursos de investigação e resposta automatizadas</a>: poupe tempo e esforço, investigando e reduzindo as ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="f81ee-475">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-476">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f81ee-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-477">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="f81ee-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-478">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="f81ee-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-479">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-480">Noções básicas sobre a correlação de incidentes Microsoft 365 Defender portal.</span><span class="sxs-lookup"><span data-stu-id="f81ee-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="f81ee-481"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f81ee-482">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="f81ee-483">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="f81ee-484">Suporte <a href=" /fasttrack/us-gov-appendix-overview">GCC-High ou GCC-DoD (Office 365 Governo dos EUA)</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="f81ee-485">Discussões que comparam o Defender Office 365 outras ofertas de segurança.</span><span class="sxs-lookup"><span data-stu-id="f81ee-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="f81ee-486">Implantando o Defender para Office 365 como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="f81ee-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="f81ee-487">Conectando aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="f81ee-488">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="f81ee-489">Investigação e correção automatizadas, incluindo o Microsoft Power Automate playbooks.</span><span class="sxs-lookup"><span data-stu-id="f81ee-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="f81ee-490">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f81ee-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="f81ee-491">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f81ee-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="f81ee-492"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="f81ee-493">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-494">Criação e publicação de rótulos e políticas de retenção (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="f81ee-495">Gerenciamento de registros (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="f81ee-496">Revisão da criação do plano de arquivos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="f81ee-497">Criando e gerenciando registros (incluindo registros baseados em eventos).</span><span class="sxs-lookup"><span data-stu-id="f81ee-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-498">Revisão da disposição.</span><span class="sxs-lookup"><span data-stu-id="f81ee-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="f81ee-499">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f81ee-500">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f81ee-501">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f81ee-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f81ee-502">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f81ee-503">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f81ee-504">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f81ee-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f81ee-505">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f81ee-506">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="f81ee-507">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="f81ee-508">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="f81ee-509">Desenvolvimento da arquitetura de informações no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f81ee-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="f81ee-510">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f81ee-511">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f81ee-512">Suporte para E3.</span><span class="sxs-lookup"><span data-stu-id="f81ee-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="f81ee-513">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f81ee-514">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="f81ee-515">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f81ee-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-516"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-517">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-518">Classificação de dados (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-519">Tipos de informações confidenciais (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-520">Criando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-521">Aplicando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-522">Classificadores com treinamento (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-523">Conhecer seus dados com o explorador de conteúdo e o explorador de atividades (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-524">Rótulos de publicação usando políticas (manuais e automáticas) (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-525">Criando políticas de prevenção contra perda de dados de ponto de extremidade (DLP) para dispositivos Windows 10 (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f81ee-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-526">Criando políticas de DLP para chats e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f81ee-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="f81ee-527">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f81ee-528">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f81ee-529">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f81ee-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f81ee-530">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f81ee-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f81ee-531">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f81ee-532">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f81ee-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f81ee-533">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f81ee-534">

<strong> Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="f81ee-535">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-536">Ativando e configurando seu locatário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-537">Criando e configurando rótulos e políticas (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f81ee-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-538">Aplicar proteção de informações a documentos (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f81ee-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-539">Classificando e rotulando automaticamente informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de Proteção de Informações do Azure (com suporte no P2).</span><span class="sxs-lookup"><span data-stu-id="f81ee-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-540">Descobrir e rotular arquivos em repouso usando o scanner de Proteção de Informações do Azure (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f81ee-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-541">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="f81ee-542">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="f81ee-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="f81ee-543"><strong>O seguinte está fora do escopo </strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="f81ee-544">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-544">Customer key.</span></span></li>
<li><span data-ttu-id="f81ee-545">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="f81ee-546">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="f81ee-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="f81ee-547">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f81ee-548">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="f81ee-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="f81ee-549">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f81ee-550">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f81ee-551">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="f81ee-552">Além da parte <strong>de integração principal</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema com exceção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="f81ee-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="f81ee-553"><strong>Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="f81ee-554">As responsabilidades de pré-requisito do cliente incluem:</span><span class="sxs-lookup"><span data-stu-id="f81ee-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-555">Uma lista de locais de compartilhamento de arquivos a serem verificados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-556">Uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="f81ee-557">Noções básicas sobre qualquer restrição regulamentar ou requisitos referentes ao gerenciamento de chaves.</span><span class="sxs-lookup"><span data-stu-id="f81ee-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-558">Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="f81ee-559">Rótulos configurados para classificação e proteção.</span><span class="sxs-lookup"><span data-stu-id="f81ee-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="f81ee-560">Todos os pré-requisitos para o scanner de Proteção de Informações do Azure estão no local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="f81ee-561">Para obter mais informações, consulte <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="f81ee-562">Verifique se os dispositivos de usuário estão executando um sistema operacional com suporte e ter os pré-requisitos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="f81ee-563">Consulte o seguinte para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f81ee-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="f81ee-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia de administração: instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </span><span class="sxs-lookup"><span data-stu-id="f81ee-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="f81ee-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="f81ee-566">Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector rms do Active Directory (AD RMS) para suporte híbrido.</span><span class="sxs-lookup"><span data-stu-id="f81ee-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="f81ee-567">Configuração e configuração de Bring Your Own Key (BYOK), DKE (Double Key Encryption) (somente cliente de rotulagem unificada) ou Hold Your Own Key (HYOK) (somente cliente clássico) caso você exigir uma dessas opções para sua implantação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-569">Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado na nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f81ee-570">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="f81ee-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f81ee-571">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f81ee-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-572">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-573">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f81ee-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-574">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-575">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f81ee-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-576">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="f81ee-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-577">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-578">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="f81ee-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-579">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="f81ee-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-580">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-581">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="f81ee-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-582">Implantação de perfis de email, redes sem fio e VPN se você tiver uma autoridade de certificação existente, rede sem fio ou infraestrutura VPN em sua organização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-583">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="f81ee-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-584">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="f81ee-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-585">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="f81ee-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-586">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="f81ee-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-587">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="f81ee-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="f81ee-588">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f81ee-589">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-590">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="f81ee-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-591">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-592">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-593">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-594">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f81ee-595">
 
</li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f81ee-596">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f81ee-597">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f81ee-598">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f81ee-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-599">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-600">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-601">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-602">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f81ee-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-603">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="f81ee-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-604">Fornecendo orientações sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.</span><span class="sxs-lookup"><span data-stu-id="f81ee-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-605">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-606">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f81ee-607"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f81ee-608">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f81ee-609">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="f81ee-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-610">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f81ee-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-611">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="f81ee-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-612">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-613">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-614">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f81ee-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-615">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="f81ee-616">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f81ee-617"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f81ee-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f81ee-618"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f81ee-619">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f81ee-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f81ee-620"><strong>Intune integrado ao Microsoft Defender para Ponto de Extremidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="f81ee-621"><strong>Observação</strong>: fornecemos assistência na integração do Intune com o Microsoft Defender para Endpoint e na criação de políticas de conformidade de dispositivos com base em sua avaliação de nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f81ee-622">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f81ee-623">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f81ee-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f81ee-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f81ee-625">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="f81ee-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="f81ee-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="f81ee-626">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-627"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-627"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-628"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-628"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-629"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-629"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f81ee-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-631">Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email.</span><span class="sxs-lookup"><span data-stu-id="f81ee-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="f81ee-632">As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.</span><span class="sxs-lookup"><span data-stu-id="f81ee-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="f81ee-633">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-634">Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-635">Apontar seus registros de troca de mensagens (MX) para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-636">Configurar o recurso do Microsoft Defender para Office 365 se ele faz parte do serviço de assinatura.</span><span class="sxs-lookup"><span data-stu-id="f81ee-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="f81ee-637">Para obter mais informações, consulte a parte <strong>do Microsoft Defender para Office 365</strong> desta tabela.</span><span class="sxs-lookup"><span data-stu-id="f81ee-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-p126">Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="f81ee-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="f81ee-p127">Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="f81ee-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="f81ee-642">
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="f81ee-643">A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="f81ee-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-644">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f81ee-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-645">Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).</span><span class="sxs-lookup"><span data-stu-id="f81ee-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-646">Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).</span><span class="sxs-lookup"><span data-stu-id="f81ee-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-647">Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-648">Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f81ee-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="f81ee-649">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f81ee-650">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="f81ee-651">Seu ambiente de origem deve ter um dos seguintes níveis mínimos:</span><span class="sxs-lookup"><span data-stu-id="f81ee-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-652">Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.</span><span class="sxs-lookup"><span data-stu-id="f81ee-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-653">Um único ambiente de email compatível com o protocolo IMAP.</span><span class="sxs-lookup"><span data-stu-id="f81ee-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-654">Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).</span><span class="sxs-lookup"><span data-stu-id="f81ee-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-655">Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="f81ee-656">Software de cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, cliente de sincronização do OneDrive for Business, Área de Trabalho do Power BI e Skype for Business deve estar em um nível mínimo conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="f81ee-657"><strong>Obter o Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-658">Para obter mais informações, consulte <strong>Microsoft Defender for Office 365</strong> em Segurança e <a href="/fasttrack/products-and-capabilities#security-and-compliance">Conformidade.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="f81ee-659"><strong>Gerência de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-660">Para obter mais informações, consulte <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-661"><strong>Proteção de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="f81ee-662">Para obter mais informações, <strong>consulte Proteção de Informações da Microsoft</strong> em Segurança e <a href="/fasttrack/products-and-capabilities#security-and-compliance">Conformidade.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-664">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-665">Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.</span><span class="sxs-lookup"><span data-stu-id="f81ee-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-666">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f81ee-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-667">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="f81ee-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-668">Confirmação da habilitação do Teams no seu locatário do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-669">Habilitação ou desabilitação de licenças de usuário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-670">Avaliação Rede para o Teams:</span><span class="sxs-lookup"><span data-stu-id="f81ee-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-671">Verificações de porta e de ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-672">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="f81ee-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-673">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="f81ee-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="f81ee-674">Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f81ee-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="f81ee-675">Se aplicável, também forneceremos diretrizes para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-676">Dispositivos para a Sala do Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="f81ee-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="f81ee-677">Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catálogo de dispositivos do Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-678">Assistência remota com configuração do lado do serviço de dispositivos Microsoft Teams Rooms certificados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-679">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="f81ee-679">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="f81ee-680">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="f81ee-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-681">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f81ee-682">Sistema de Telefonia:</span><span class="sxs-lookup"><span data-stu-id="f81ee-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-683">Configuração da organização para as configurações padrão do Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="f81ee-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-684">Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):</span><span class="sxs-lookup"><span data-stu-id="f81ee-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-685">Atribuição de números a usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="f81ee-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-686">Orientação de portabilidade do número local pela IU (interface do usuário) até 999.</span><span class="sxs-lookup"><span data-stu-id="f81ee-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-687">Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.</span><span class="sxs-lookup"><span data-stu-id="f81ee-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f81ee-688">Diretrizes de Roteamento Direto:</span><span class="sxs-lookup"><span data-stu-id="f81ee-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-689">Diretrizes de configuração da organização para o design de Roteamento Direto de cenários hospedados pelo parceiro ou cenários implantados pelo cliente para até 10 sites.</span><span class="sxs-lookup"><span data-stu-id="f81ee-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="f81ee-690">Revisão de configuração do Controlador de Borda de Sessão (SBC).</span><span class="sxs-lookup"><span data-stu-id="f81ee-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="f81ee-691">Assistência remota com configuração do plano de discagem.</span><span class="sxs-lookup"><span data-stu-id="f81ee-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="f81ee-692">Configuração de rota de voz.</span><span class="sxs-lookup"><span data-stu-id="f81ee-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="f81ee-693">Bypass de mídia e otimização de mídia local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="f81ee-694">Habilitação dos eventos ao vivo do Teams.</span><span class="sxs-lookup"><span data-stu-id="f81ee-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-695">Configuração e integração da organização com o Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="f81ee-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-696">Diretrizes para a transição do Skype for Business para o Teams.</span><span class="sxs-lookup"><span data-stu-id="f81ee-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f81ee-697">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-698">Usuários habilitados para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-699">Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).</span><span class="sxs-lookup"><span data-stu-id="f81ee-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-700">Habilitado para Grupos do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="f81ee-701">
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f81ee-702">O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f81ee-703">O Teams não oferece suporte para o SharePoint no local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="f81ee-704">
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio em casa no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="f81ee-705">Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect.</span><span class="sxs-lookup"><span data-stu-id="f81ee-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="f81ee-706">Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.</span><span class="sxs-lookup"><span data-stu-id="f81ee-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="f81ee-707">Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="f81ee-708"><strong>Outlook para iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-709">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-710">Baixe o Outlook para iOS e Android no Google Play e Apple App Store.</span><span class="sxs-lookup"><span data-stu-id="f81ee-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-711">Configurar contas e acessar a caixa de correio do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-712">Proteger o Outlook Mobile (para obter mais informações, confira <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).</span><span class="sxs-lookup"><span data-stu-id="f81ee-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f81ee-713">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-714">Exchange Online configurado e licenças atribuídas.</span><span class="sxs-lookup"><span data-stu-id="f81ee-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-716">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-717">Atribuição de licenças do Power BI.</span><span class="sxs-lookup"><span data-stu-id="f81ee-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-718">Implantação do aplicativo do Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="f81ee-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f81ee-719">Software cliente online como a Área de Trabalho do Power BI deve estar em um nível mínimo, conforme definido nos requisitos do sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-721">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-722">Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.</span><span class="sxs-lookup"><span data-stu-id="f81ee-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-723">Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-724">Configurar o ERP (Pool de Recursos da Empresa).</span><span class="sxs-lookup"><span data-stu-id="f81ee-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-725">Criando seu primeiro projeto.</span><span class="sxs-lookup"><span data-stu-id="f81ee-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f81ee-726">Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f81ee-727"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-728">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-729">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="f81ee-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-730">Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f81ee-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-731">Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="f81ee-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-732">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-733">Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-734">Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="f81ee-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f81ee-735">Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-736"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-737">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-738">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="f81ee-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-739">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f81ee-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-740">Provisionar usuários e licenças.</span><span class="sxs-lookup"><span data-stu-id="f81ee-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="f81ee-741">Habilitar a criação de sites para o administrador do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="f81ee-742">Planejamento de conjuntos de sites.</span><span class="sxs-lookup"><span data-stu-id="f81ee-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="f81ee-743">Proteção de conteúdo e gerenciamento de permissões.</span><span class="sxs-lookup"><span data-stu-id="f81ee-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="f81ee-744">Configuração de recursos do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="f81ee-745">Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.</span><span class="sxs-lookup"><span data-stu-id="f81ee-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-746">Método de migração.</span><span class="sxs-lookup"><span data-stu-id="f81ee-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="f81ee-747">Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="f81ee-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-748">Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-749">Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f81ee-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-750">Planejar e implementar a distribuição única (ou em fases) para todos os usuários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-751">Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="f81ee-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="f81ee-752">Redirecionar ou mover pastas conhecidas para o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f81ee-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="f81ee-753">Implantar o cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f81ee-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="f81ee-754">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f81ee-755">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="f81ee-756"><strong>Para o SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f81ee-757">A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f81ee-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="f81ee-758">
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="f81ee-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="f81ee-759">Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.</span><span class="sxs-lookup"><span data-stu-id="f81ee-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="f81ee-760">
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="f81ee-761">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f81ee-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="f81ee-762">Para obter mais informações, consulte <a href="https://go.microsoft.com/fwlink/?linkid=853548">Níveis mínimos de atualização pública para recursos híbridos do SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="f81ee-763">
  <strong>Observação:</strong> Para obter informações sobre recursos multi-geo, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="f81ee-765">Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f81ee-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="f81ee-766">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="f81ee-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f81ee-767">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-768"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-768"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-769"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-769"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-770"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-770"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f81ee-771"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-772">Para obter mais informações, consulte <strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong> em <a href="/fasttrack/products-and-capabilities#security-and-compliance">Segurança e Conformidade.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="f81ee-773">#segurança e conformidade</span><span class="sxs-lookup"><span data-stu-id="f81ee-773">#security-and-compliance</span></span>
<td><span data-ttu-id="f81ee-774"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-774"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f81ee-775">Para obter mais informações sobre a Proteção de Informações do Azure, consulte <strong>Proteção de Informações da Microsoft</strong> em Segurança e <a href="/fasttrack/products-and-capabilities#security-and-compliance">Conformidade.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-775">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f81ee-776"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-776"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-777">Para obter mais informações, consulte <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-777">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="f81ee-778">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f81ee-778">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-779"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-779"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-780"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-780"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-781"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-781"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f81ee-782"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-782"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-783">Fornecemos orientações para atualização do Windows 7 Professional e do Windows 8.1 Professional para o Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f81ee-783">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="f81ee-784">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-784">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-785">Entender a sua intenção do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-785">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-786">Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).</span><span class="sxs-lookup"><span data-stu-id="f81ee-786">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-787">Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-787">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-788">Recomendamos opções para você avaliar os aplicativos do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-788">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-789">Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="f81ee-789">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-790">Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f81ee-790">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-791">Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="f81ee-791">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-792">Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.</span><span class="sxs-lookup"><span data-stu-id="f81ee-792">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-793">Diretrizes de atualização para dar suporte ao seu movimento de implantação existente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-793">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="f81ee-794">O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-794">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="f81ee-795">As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="f81ee-795">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-796">Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-796">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="f81ee-797">Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-797">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="f81ee-798">
  
<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-798">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f81ee-799">Atualizar o Configuration Manager para o Branch Atual.</span><span class="sxs-lookup"><span data-stu-id="f81ee-799">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-800">Criar imagens personalizadas para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-800">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-801">Criar e dar suporte à implantação de scripts para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-801">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-802">Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).</span><span class="sxs-lookup"><span data-stu-id="f81ee-802">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-803">Habilitar os recursos de segurança do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-803">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-804">Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="f81ee-804">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-805">Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-805">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-806">Usar a Ferramenta de Migração de Estado do Usuário (USMT).</span><span class="sxs-lookup"><span data-stu-id="f81ee-806">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="f81ee-807">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f81ee-807">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="f81ee-808">Para a atualização do computador, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="f81ee-808">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-809">SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="f81ee-809">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-810">Dispositivos: fator forma de desktop, notebook ou tablet.</span><span class="sxs-lookup"><span data-stu-id="f81ee-810">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-811">SO de destino: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f81ee-811">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="f81ee-812">Para atualização da infraestrutura, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="f81ee-812">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-813">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f81ee-813">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-814">A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-814">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="f81ee-815">Para obter mais informações, confira a tabela de suporte do Configuration Manager em <a href="/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-815">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="f81ee-816"><strong>Microsoft Defender para Ponto de Extremidade</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-816"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-817">Para obter mais informações, consulte <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-817">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="f81ee-818">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="f81ee-818">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-819"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-819"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-820"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-820"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-821"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-821"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f81ee-822"><strong>Área de Trabalho Virtual do Windows</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-822"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="f81ee-823">Fornecemos diretrizes de implantação para integração à Área de Trabalho Virtual do Windows (um serviço de virtualização de aplicativo e área de trabalho).</span><span class="sxs-lookup"><span data-stu-id="f81ee-823">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="f81ee-824">A Área de Trabalho Virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para o Microsoft 365 Apps for Enterprise com segurança e gerenciamento integrados para o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-824">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="f81ee-825">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-825">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="f81ee-826">Implantação de várias sessões do Windows 10 Enterprise e aplicativos do Microsoft 365 para Empresas usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f81ee-826">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="f81ee-827">Imagem do Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="f81ee-827">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="f81ee-828">Imagem compartilhada.</span><span class="sxs-lookup"><span data-stu-id="f81ee-828">Shared image.</span></span></li>
<li><span data-ttu-id="f81ee-829">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="f81ee-829">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="f81ee-830">Configurando o Microsoft 365 Apps para FSLogix em uma Área de Trabalho Virtual nativa do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-830">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="f81ee-831">Para FSLogix:</span><span class="sxs-lookup"><span data-stu-id="f81ee-831">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="f81ee-832">Implantando o Agente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-832">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="f81ee-833">Configurando contêineres do Perfil e do Office.</span><span class="sxs-lookup"><span data-stu-id="f81ee-833">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="f81ee-834">Configurando exclusões de conteúdo e redirecionamentos de pastas para Aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f81ee-834">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="f81ee-835">Implantando o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f81ee-835">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="f81ee-836">Implantando o Microsoft Teams com otimização.</span><span class="sxs-lookup"><span data-stu-id="f81ee-836">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="f81ee-837">

<strong>O seguinte está fora do escopo</strong>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-837">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="f81ee-838">Gerenciamento de projetos da implantação de infraestrutura da Área de Trabalho Virtual do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-838">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="f81ee-839">Implantação e virtualização de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f81ee-839">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="f81ee-840">Criação de imagens personalizadas para a Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-840">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="f81ee-841">Migrações e cenários envolvendo VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="f81ee-841">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="f81ee-842">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="f81ee-842">Linux scenarios.</span></span></li>
<li><span data-ttu-id="f81ee-843">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="f81ee-843">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="f81ee-844">Configuração do Microsoft Endpoint Configuration Manager e Microsoft Endpoint Manager para Área de Trabalho Virtual do Windows (incluindo patching e gerenciamento).</span><span class="sxs-lookup"><span data-stu-id="f81ee-844">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="f81ee-845">Microsoft 365 Defender com Windows 10 multi-sessão.</span><span class="sxs-lookup"><span data-stu-id="f81ee-845">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="f81ee-846">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f81ee-846">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="f81ee-847">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f81ee-847">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="f81ee-848"><a href="/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento da Área de Trabalho Virtual do Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-848"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="f81ee-849">A <a href="/azure/virtual-desktop/overview"> infraestrutura necessária para dar suporte ao Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-849">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="f81ee-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Armazenamento para contêineres de perfil FSLogix no Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="f81ee-851">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="f81ee-851">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="f81ee-852">Criação e sub-rede de rede virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="f81ee-852">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="f81ee-853">Grupos de segurança de rede e firewall.</span><span class="sxs-lookup"><span data-stu-id="f81ee-853">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="f81ee-854">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f81ee-854">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="f81ee-855">Roteamento para o Azure no local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-855">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="f81ee-856">Regras de firewall para permitir a conectividade com a Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-856">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="f81ee-857">Para obter mais informações, consulte <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Área de Trabalho Remota com suporte.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-857">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="f81ee-858">Configuração geral do Azure AD:</span><span class="sxs-lookup"><span data-stu-id="f81ee-858">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="f81ee-859">Estratégia de <i>identidade (você pode usar apenas uma das três opções a seguir):</i>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-859">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="f81ee-860">Active Directory com o Azure AD Connect no Azure.</span><span class="sxs-lookup"><span data-stu-id="f81ee-860">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="f81ee-861">Active Directory com o Azure AD Connect local através de VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f81ee-861">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="f81ee-862">Serviços de Domínio do Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="f81ee-862">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="f81ee-863">Garantia do aplicativo</span><span class="sxs-lookup"><span data-stu-id="f81ee-863">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-864"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-864"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-865"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-865"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-866"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-866"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f81ee-867"><strong>Garantia de Aplicativo</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-867"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="f81ee-868">A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f81ee-868">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="f81ee-869">Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-869">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="f81ee-870">Também fornecemos orientações aos clientes que enfrentam problemas de compatibilidade ao implantar a Área de Trabalho Virtual do Windows e o Microsoft Edge e fazem todos os esforços razoáveis para resolver problemas de compatibilidade.</span><span class="sxs-lookup"><span data-stu-id="f81ee-870">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="f81ee-871">Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:</span><span class="sxs-lookup"><span data-stu-id="f81ee-871">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="f81ee-872"><strong>Windows 10 </strong> (incluindo dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="f81ee-872"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="f81ee-873"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="f81ee-873"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="f81ee-874"><strong>Microsoft Edge -</strong> Para obter orientações de implantação, consulte <a href="/DeployEdge/microsoft-edge-channels">Visão geral dos canais do Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-874"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-875"><strong>Área de trabalho virtual do</strong> - Windows Para obter mais informações, consulte O que é a Área de Trabalho Virtual do <a href="/azure/virtual-desktop/overview">Windows?</a> e Perguntas frequentes de várias <a href="/azure/virtual-desktop/windows-10-multisession-faq">sessões do Windows 10 Enterprise.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-875"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="f81ee-876">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-876">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f81ee-877">Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f81ee-877">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="f81ee-878">Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-878">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="f81ee-879">Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-879">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="f81ee-880">Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f81ee-880">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="f81ee-881">Para obter mais informações, confira <a href="/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-881">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="f81ee-882">Serviços de embalagem do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-882">App packaging-only services.</span></span> <span data-ttu-id="f81ee-883">No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-883">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="f81ee-884">

<strong>As responsabilidades do cliente incluem</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-884">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f81ee-885">Criar um inventário de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f81ee-885">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="f81ee-886">Validando esses aplicativos no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f81ee-886">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="f81ee-887">
<strong>Observação:</strong>  A Microsoft não pode fazer alterações no código-fonte.</span><span class="sxs-lookup"><span data-stu-id="f81ee-887">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="f81ee-888">No entanto, a equipe da Garantia de Aplicativo da Área de Trabalho pode fornecer orientações para os desenvolvedores de aplicativo se o código-fonte estiver disponível para os aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f81ee-888">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="f81ee-889">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f81ee-889">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="f81ee-890"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-890"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-891">Os aplicativos que funcionavam no Windows 7, Windows 8.1, Office 2010 e Office 2013 também funcionam no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f81ee-891">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="f81ee-892">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-892">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="f81ee-893">Os aplicativos que funcionaram no Windows 7, Office 2010 ou versões posteriores também funcionam no Windows 10 e no Microsoft 365 Apps em dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="f81ee-893">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="f81ee-894">
  <strong>Observação:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="f81ee-894">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="f81ee-895">A emulação x64 (64 bits) está disponível na visualização para clientes que participam do <a href="https://insider.windows.com/">Programa Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-895">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="f81ee-896">Para clientes que não são do Windows Insider no Windows 10 versão 2004 (ou posterior), o Arm64 Photoshop tem suporte usando o OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">o OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="f81ee-896">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="f81ee-897">Os clientes no Programa Windows Insider podem baixar uma versão insider do OpenCL e do OpenGL Compatibility Pack para uso com aplicativos adicionais.</span><span class="sxs-lookup"><span data-stu-id="f81ee-897">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="f81ee-898">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="f81ee-898">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-899">Se seus aplicativos web ou sites funcionarem no Internet Explorer 11, versões com suporte do Google Chrome ou qualquer versão do Microsoft Edge, eles também funcionarão com o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f81ee-899">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-900">Como a Web está em constante evolução, revise esta lista publicada de alterações conhecidas que impactam a compatibilidade do <a href="/microsoft-edge/web-platform/site-impacting-changes">site para o Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-900">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="f81ee-901">
  <strong>Área de Trabalho Virtual do Windows</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-901">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f81ee-902">Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-902">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-903">Aplicativos em execução em qualquer ambiente de infraestrutura de área de trabalho virtual (VDI) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-903">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-904">Aplicativos em execução em dispositivos cliente Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f81ee-904">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="f81ee-905">
  <strong>Observação:</strong> As exclusões e limitações de compatibilidade de várias sessões do Windows 10 Enterprise incluem:</span><span class="sxs-lookup"><span data-stu-id="f81ee-905">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="f81ee-906">Redirecionamento limitado de hardware.</span><span class="sxs-lookup"><span data-stu-id="f81ee-906">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-907">Aplicativos de uso intensivo de A/V podem ser executados com uma capacidade reduzida.</span><span class="sxs-lookup"><span data-stu-id="f81ee-907">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f81ee-908">Não há suporte para aplicativos de 16 bits na Área de Trabalho Virtual do Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="f81ee-908">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="f81ee-909">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f81ee-909">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f81ee-910"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-910"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f81ee-911"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-911"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f81ee-912"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f81ee-912"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f81ee-913"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="f81ee-913"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="f81ee-914">Fornecemos orientação e compatibilidade de implantação remota e adoção para:</span><span class="sxs-lookup"><span data-stu-id="f81ee-914">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="f81ee-915">Implantando Microsoft Edge no Windows 10 com Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="f81ee-915">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-916">Configurando Microsoft Edge (usando políticas de grupo ou configuração de aplicativos do Intune e políticas de aplicativo).</span><span class="sxs-lookup"><span data-stu-id="f81ee-916">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="f81ee-917">Inventário da lista de sites que podem exigir uso no modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="f81ee-917">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="f81ee-918">Habilitação do modo do Internet Explorer com a lista de sites corporativos existente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-918">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="f81ee-919">(Para obter mais informações, consulte <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span><span class="sxs-lookup"><span data-stu-id="f81ee-919">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="f81ee-920">Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional.</span><span class="sxs-lookup"><span data-stu-id="f81ee-920">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="f81ee-921">Para solicitar suporte de compatibilidade para o App Assure, entre no <a href="https://fasttrack.microsoft.com/portal#/signin">portal FastTrack para</a> iniciar um envolvimento.</span><span class="sxs-lookup"><span data-stu-id="f81ee-921">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="f81ee-922">Diretrizes de planejamento para adoção e configuração de borda para Pesquisa da Microsoft indicadores.</span><span class="sxs-lookup"><span data-stu-id="f81ee-922">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="f81ee-923">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f81ee-923">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="f81ee-924">Gerenciamento de projetos de implantação do Microsoft Edge do cliente.</span><span class="sxs-lookup"><span data-stu-id="f81ee-924">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="f81ee-925">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="f81ee-925">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

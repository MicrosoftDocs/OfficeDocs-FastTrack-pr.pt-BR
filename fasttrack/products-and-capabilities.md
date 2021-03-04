---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416560"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="f1b1f-104">Produtos e Recursos</span><span class="sxs-lookup"><span data-stu-id="f1b1f-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="f1b1f-105">Serviços e cenários com suportados pelo FastTrack</span><span class="sxs-lookup"><span data-stu-id="f1b1f-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="f1b1f-106">Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="f1b1f-107">Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="f1b1f-108">O FastTrack fornece orientações para ajudá-lo primeiro com os recursos principais (comuns para todos os Microsoft Online Services) e, em seguida, com a integração de cada serviço qualificado:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="f1b1f-109">Geral</span><span class="sxs-lookup"><span data-stu-id="f1b1f-109">General</span></span>](#general)
  - [<span data-ttu-id="f1b1f-110">Segurança e conformidade</span><span class="sxs-lookup"><span data-stu-id="f1b1f-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="f1b1f-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="f1b1f-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="f1b1f-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f1b1f-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="f1b1f-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f1b1f-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="f1b1f-114">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="f1b1f-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="f1b1f-115">Garantia de Aplicativo</span><span class="sxs-lookup"><span data-stu-id="f1b1f-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="f1b1f-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f1b1f-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="f1b1f-117">Para saber mais sobre as expectativas de ambiente de origem para o Office 365 US Government, confira [Expectativas de Ambiente de Origem para o Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="f1b1f-118">Geral</span><span class="sxs-lookup"><span data-stu-id="f1b1f-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-119"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-120"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-121"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f1b1f-122"><strong>Integração principal</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-123">Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="f1b1f-124">Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="f1b1f-125">A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="f1b1f-126"></li>
</ul>  

<strong>Integração de identidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="f1b1f-127">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-128">Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="f1b1f-129">Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="f1b1f-130">Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="f1b1f-131">Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="f1b1f-132">Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="f1b1f-133">Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="f1b1f-134">Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="f1b1f-135">Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="f1b1f-136">Habilitar o provisionamento automático do usuário para aplicativos SaaS pré-integrados, como listados na <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Lista de tutoriais de integração de aplicativos</a>, (limitado apenas ao provisionamento de saída e de aplicativos SaaS da galeria do Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="f1b1f-137"><strong>Habilitação de rede </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="f1b1f-138">Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="f1b1f-139"><strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-140">Uma única floresta do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-141">Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-142">Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-143">Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-144">Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-145">Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="f1b1f-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="f1b1f-147">Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-148">Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="f1b1f-149">Namespaces SMTP primários entre organizações do Exchange também devem ser separados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="f1b1f-150">Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-151">Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="f1b1f-152">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-154">Fornecemos orientações de implantação remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-155">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-156">Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-157">Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-158">Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-159">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-160">Seleção e configuração de uma instalação local ou na nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-161">Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-162">Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="f1b1f-163">Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="f1b1f-164">Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f1b1f-165">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-166"><strong>Integridade da rede</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-167">Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="f1b1f-168">Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="f1b1f-169">Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="f1b1f-170">Acesso ao Centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-171">São necessárias versões atualizadas dos aplicativos do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-172">Serviços de localização habilitados conforme as <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="f1b1f-173">Segurança e Conformidade</span><span class="sxs-lookup"><span data-stu-id="f1b1f-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-174"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-175"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-176"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="f1b1f-177"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-178">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f1b1f-179">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-180">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-181">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-182">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-183">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-184">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-185">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-186">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-187">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-188">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-189">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-190">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-191">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-192">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-193">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-194">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f1b1f-195">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-196">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-197">Gerenciando e controlando o acesso a contas de administrador privilegiadas com o Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-198">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-199">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f1b1f-200">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-201">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-202">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-203">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-204">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-205"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-206">Para obter mais informações sobre a Proteção de Informações do Azure, consulte <strong>Proteção de Informações</strong> da Microsoft mais adiante nesta tabela.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="f1b1f-207"><strong>Resposta & descoberta</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="f1b1f-208"><strong>Descoberta Avançada de EDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-209">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-210">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-211">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-212">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="f1b1f-213"><strong>Auditoria Avançada</strong> (com suporte apenas no E5)</span><span class="sxs-lookup"><span data-stu-id="f1b1f-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="f1b1f-214">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="f1b1f-215">Habilitando a auditoria avançada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="f1b1f-216">Executando uma interface do usuário do log de auditoria de pesquisa e comandos básicos de auditoria do PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="f1b1f-217">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-218">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-219">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-220">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-221">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-222">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-223">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-224">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f1b1f-225">Scripts personalizados ou codificação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="f1b1f-226">API de Descoberta Externa.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="f1b1f-227">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="f1b1f-228">Limites de conformidade e filtros de segurança.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="f1b1f-229">Investigações de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="f1b1f-230">Solicitações de assunto de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="f1b1f-231">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-232">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-233">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="f1b1f-234">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f1b1f-235"><strong>Gerenciamento de ameaças insider</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="f1b1f-236">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="f1b1f-237">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f1b1f-238">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f1b1f-239">Criar casos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="f1b1f-240">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="f1b1f-241">Diretrizes sobre a criação do conector de recursos humanos (RH).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="f1b1f-242">

<strong> Conformidade de comunicação </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="f1b1f-243">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="f1b1f-244">Criando políticas e revendo configurações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f1b1f-245">Acessando relatórios e alertas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f1b1f-246">Criando modelos de aviso.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="f1b1f-247">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-248">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-249">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-250">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-251">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-252">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-253">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-254">

<strong>O seguinte está fora do escopo </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f1b1f-255">Criando e gerenciando fluxos do Power Automate.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="f1b1f-256">Conectores de dados (além do conector de RH).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="f1b1f-257">Configurações de expressão regular personalizada (RegEx).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="f1b1f-258">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-259">Barreiras de informações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="f1b1f-260">Gerenciamento de acesso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="f1b1f-261">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-262">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="f1b1f-263">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="f1b1f-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="f1b1f-265">O Microsoft 365 Defender é um pacote de defesa empresarial unificado pré e pós-violação que coordena de forma nativa a detecção, prevenção, investigação e resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="f1b1f-266">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="f1b1f-267">Fornecendo uma visão geral do centro de segurança do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-268">Revisão de incidentes entre produtos, incluindo o foco no que é crítico, garantindo o escopo de ataque completo, os ativos afetados e as ações de correção automatizadas agrupadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-269">Demonstrando como o Microsoft 365 Defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidas por meio da auto-recuperação automatizada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-270">Explicando e fornecendo exemplos de como os clientes podem procurar proativamente tentativas de invasão e atividades de violação que afetam seu email, dados, dispositivos e contas em vários conjuntos de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="f1b1f-271">Mostrando aos clientes como eles podem revisar e melhorar a postura de segurança de forma holística usando a Pontuação Segura da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="f1b1f-272"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f1b1f-273">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f1b1f-274">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f1b1f-275">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="f1b1f-276">Como remediar ou interpretar os vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="f1b1f-277">Como investigar um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f1b1f-278">Busca personalizada de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="f1b1f-279">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-281">O Microsoft Cloud App Security é um Agente de Segurança do Cloud Access (CASB) que fornece visibilidade avançada, controle sobre viagens de dados e análises sofisticadas para identificar e combater ameaças cibernéticas em todos os serviços de nuvem da Microsoft e de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="f1b1f-282">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-283">Configurando o portal, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="f1b1f-284">Importando grupos de usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="f1b1f-285">Gerenciando o acesso e as configurações do administrador.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-286">Scoping sua implantação para selecionar determinados grupos de usuários para monitorar ou excluir do monitoramento.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="f1b1f-287">Definindo intervalos e marcas IP.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="f1b1f-288">Personalizando a experiência do usuário final com seu logotipo e mensagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-289">Configurando a descoberta na nuvem para fornecer a tecnologia de sombra usando:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="f1b1f-290">Microsoft Defender para Pontos de Extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="f1b1f-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="f1b1f-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-293">Conectando <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicativos em destaque</a> usando conectores de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="f1b1f-294">Configurando o Controle de Aplicativo de Acesso Condicional nos portais de Acesso Condicional e Segurança de Aplicativos na Nuvem para aplicar controles de sessão em tempo real.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-295">Implantando os painéis Cloud App Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="f1b1f-296">Personalização de pontuações de risco de aplicativo com base nas prioridades da sua organização.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="f1b1f-297">Criando marcas e categorias de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="f1b1f-298">Sancionando e desemanando aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="f1b1f-299">Usando a atividade e os logs de arquivo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="f1b1f-300">Gerenciando aplicativos OAuth.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="f1b1f-301">Noções básicas sobre a correlação de incidentes no portal do Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="f1b1f-302">Fornecendo assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> principais casos de uso para CASBs (incluindo a criação ou atualização de até seis (6) políticas), exceto:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="f1b1f-303">Auditoria da configuração da internet como ambientes de serviço (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="f1b1f-304">Monitorando as atividades do usuário para proteger contra ameaças em seus ambientes iaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="f1b1f-305"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f1b1f-306">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="f1b1f-307">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f1b1f-308">Configurando a infraestrutura, a instalação ou a implantação de carregamentos de log automáticos para relatórios contínuos usando o Docker ou um coletor de log.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="f1b1f-309">Confira <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Os 20 principais casos de uso para CASBs</a> para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="f1b1f-310">Criando um relatório de instantâneo de Descoberta na Nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="f1b1f-311">Bloqueando o uso do aplicativo usando scripts de bloqueio.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="f1b1f-312">Conectando aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="f1b1f-313">Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção contra perda de dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="f1b1f-314">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="f1b1f-315">Investigação e correção automatizadas, incluindo os playbooks do Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="f1b1f-316">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="f1b1f-317">Implantando a Descoberta de Aplicativos na Nuvem como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="f1b1f-318"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-319">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f1b1f-320">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-321">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-322">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-323">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-324">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-325">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-326">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-327">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-328">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-329">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-330">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-331">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-332">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-333">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-334">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-335">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-336">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-337">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-338">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-342">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-343">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-344">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f1b1f-345">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f1b1f-346"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-347">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-348">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-349">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-350">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-351">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-354">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="f1b1f-355">Virtual Desktop Infrastructure (VDI) (persistente ou não persistente).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-356">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-357">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-358">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-359">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-360">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-361">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-362">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-363">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f1b1f-364">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-365">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-366">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-367">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-368">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="f1b1f-369">Controle de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="f1b1f-370">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-371">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="f1b1f-372">Configuração ou gerenciamento de recursos de proteção de conta como:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="f1b1f-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="f1b1f-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="f1b1f-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="f1b1f-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-375">Configuração ou gerenciamento do BitLocker.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="f1b1f-376">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-377">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-378">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-379">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-380">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="f1b1f-381">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="f1b1f-382"><strong>Microsoft Defender para Identidade </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-383">O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="f1b1f-384">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="f1b1f-385">Criando sua instância do Defender para Identidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="f1b1f-386">Conectando o Defender para Identidade ao Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="f1b1f-387">Avaliando a preparação do seu ambiente para implantar o sensor Defender for Identity em seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="f1b1f-388">Executando a ferramenta de sizing para planejamento de capacidade de recursos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-389">Executando a ferramenta de auditoria para avaliar a compatibilidade dos controladores de domínio com o sensor.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="f1b1f-390">Implantando o sensor para capturar e analisar o tráfego de rede e eventos do Windows diretamente de seus controladores de domínio, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="f1b1f-391">Baixando o pacote do sensor.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-392">Configurando o sensor.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-393">Instalando o sensor no controlador de domínio silenciosamente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-394">Implantando o sensor em seu ambiente de várias florestas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="f1b1f-395">Integrando o Defender para Identidade com o Microsoft Cloud App Security (o licenciamento de Segurança do Aplicativo na Nuvem não é necessário).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="f1b1f-396">Fornecendo diretrizes de implantação, assistência de configuração e educação em:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="f1b1f-397">Ajustando o ambiente para reduzir "ruído".</span><span class="sxs-lookup"><span data-stu-id="f1b1f-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-398">Noções básicas sobre o relatório de avaliação de postura de segurança de identidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-399">Noções básicas sobre a pontuação de prioridade de investigação do usuário e o relatório de classificação de investigação do usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="f1b1f-400">Noções básicas sobre o relatório do usuário inativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-401">Fornecendo opções de correção em uma conta comprometida.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f1b1f-402">Facilitando a migração do Advanced Threat Analytics (ATA) para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="f1b1f-403"><strong>O seguinte está fora do escopo</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="f1b1f-404">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f1b1f-405">Gerenciamento contínuo, resposta a ameaças e correção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-406">Implantando o sensor Defender para Identidade, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="f1b1f-407">Planejamento de capacidade manual.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="f1b1f-408">Implantando o sensor em uma capacidade autônoma.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="f1b1f-409">Implantando o sensor usando um adaptador de NIC (Network Interface Card).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="f1b1f-410">Implantando o sensor por meio de uma ferramenta de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="f1b1f-411">Conectando-se ao serviço de nuvem Defender para Identidade por meio de uma conexão de proxy da Web.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="f1b1f-412">Criação e gerenciamento de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="f1b1f-413">Diretrizes de implantação ou educação em:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="f1b1f-414">Correção ou interpretação de vários tipos de alerta e atividades monitoradas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-415">Investigando um usuário, computador, caminho de movimento lateral ou entidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f1b1f-416">Ameaça ou busca avançada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="f1b1f-417">Resposta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="f1b1f-418">Fornecendo um tutorial do laboratório de alertas de segurança para o Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="f1b1f-419">Fornecer notificação quando o Defender for Identity detecta atividades suspeitas enviando alertas de segurança para seu servidor de syslog por meio de um sensor nomeado.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-420">Configurar o Defender para Identidade para realizar consultas usando o protocolo SAMR (gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="f1b1f-421">Configurando soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-422">Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="f1b1f-423">Implantando sensores defender para identidade como uma prova de conceito.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f1b1f-424">Active Directory implantado.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-425">Os controladores de domínio que você pretende instalar os sensores do Defender para Identidade têm conectividade com a Internet para o serviço de nuvem defender para identidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="f1b1f-426">Seu firewall e proxy devem estar abertos para se comunicar com o serviço de nuvem Defender for Identity (\*.atp.azure.com porta 443 deve estar aberta).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-427">Controladores de domínio em execução em um dos seguintes:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="f1b1f-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="f1b1f-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="f1b1f-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="f1b1f-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="f1b1f-432">Windows Server 2019 com KB4487044 (com build do sistema operacional 17763.316).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="f1b1f-433"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="f1b1f-434">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-435">Criação e publicação de rótulos e políticas de retenção (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="f1b1f-436">Gerenciamento de registros (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="f1b1f-437">Revisão da criação do plano de arquivos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-438">Criando e gerenciando registros (incluindo registros baseados em eventos).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-439">Revisão da disposição.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="f1b1f-440">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-441">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-442">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-443">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-444">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-445">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-446">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-447">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="f1b1f-448">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="f1b1f-449">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="f1b1f-450">Desenvolvimento da arquitetura de informações no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="f1b1f-451">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f1b1f-452">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-453">Suporte para E3.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="f1b1f-454">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-455">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="f1b1f-456">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-457"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-458">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-459">Classificação de dados (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-460">Tipos de informações confidenciais (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-461">Criando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-462">Aplicando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-463">Classificadores com treinamento (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-464">Conhecer seus dados com o explorador de conteúdo e o explorador de atividades (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-465">Rótulos de publicação usando políticas (manuais e automáticas) (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-466">Criando políticas de prevenção contra perda de dados de ponto de extremidade (DLP) para dispositivos Windows 10 (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-467">Criando políticas de DLP para chats e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-468">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-469">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-470">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-471">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-472">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-473">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-474">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-475">

<strong> Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="f1b1f-476">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-477">Ativando e configurando seu locatário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-478">Criando e configurando rótulos e políticas (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-479">Aplicar proteção de informações a documentos (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-480">Classificando e rotulando automaticamente informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de Proteção de Informações do Azure (com suporte no P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-481">Descobrir e rotular arquivos em repouso usando o scanner de Proteção de Informações do Azure (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-482">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="f1b1f-483">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="f1b1f-484"><strong>O seguinte está fora do escopo </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="f1b1f-485">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-485">Customer key.</span></span></li>
<li><span data-ttu-id="f1b1f-486">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="f1b1f-487">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="f1b1f-488">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f1b1f-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="f1b1f-490">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-491">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-492">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="f1b1f-493">Além da parte <strong>de integração principal</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema com exceção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="f1b1f-494"><strong>Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="f1b1f-495">As responsabilidades de pré-requisito do cliente incluem:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-496">Uma lista de locais de compartilhamento de arquivos a serem verificados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-497">Uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="f1b1f-498">Noções básicas sobre qualquer restrição regulamentar ou requisitos referentes ao gerenciamento de chaves.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-499">Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-500">Rótulos configurados para classificação e proteção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="f1b1f-501">Todos os pré-requisitos para o scanner de Proteção de Informações do Azure estão no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="f1b1f-502">Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-503">Verifique se os dispositivos de usuário estão executando um sistema operacional com suporte e ter os pré-requisitos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="f1b1f-504">Consulte o seguinte para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="f1b1f-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia de administração: instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </span><span class="sxs-lookup"><span data-stu-id="f1b1f-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="f1b1f-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-507">Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector rms do Active Directory (AD RMS) para suporte híbrido.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-508">Configuração e configuração de Bring Your Own Key (BYOK), DKE (Double Key Encryption) (somente cliente de rotulagem unificada) ou Hold Your Own Key (HYOK) (somente cliente clássico) caso você exigir uma dessas opções para sua implantação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-510">Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado na nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f1b1f-511">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f1b1f-512">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-513">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-514">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-515">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-516">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-517">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-518">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-519">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-520">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-521">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-522">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-523">Implantação de perfis de email, redes sem fio e VPN se você tiver uma autoridade de certificação existente, rede sem fio ou infraestrutura VPN em sua organização.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-524">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-525">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-526">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-527">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-528">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="f1b1f-529">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-530">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-531">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-532">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-533">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-534">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-535">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-536">
 
</li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f1b1f-537">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f1b1f-538">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f1b1f-539">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-540">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-541">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-542">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-543">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-544">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-545">Fornecendo orientações sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-546">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-547">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f1b1f-548"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f1b1f-549">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f1b1f-550">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-551">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-552">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-553">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-554">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-555">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-556">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="f1b1f-557">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f1b1f-558"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f1b1f-559"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f1b1f-560">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f1b1f-561"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="f1b1f-562"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f1b1f-563">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f1b1f-564">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f1b1f-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f1b1f-566">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f1b1f-567"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-568">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-569">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-570">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-571">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-572">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-573">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="f1b1f-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="f1b1f-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-575"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-576"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-577"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f1b1f-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-579">Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="f1b1f-580">As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="f1b1f-581">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-582">Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-583">Apontar seus registros de troca de mensagens (MX) para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-584">Configurar o recurso do Office 365 ATP se ele fizer parte do seu serviço de assinatura.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="f1b1f-585">Para mais informações, veja a parte dessa tabela <strong>Proteção Avançada contra Ameaças do Office 365</strong>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-p127">Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="f1b1f-p128">Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="f1b1f-590">
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="f1b1f-591">A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-592">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-593">Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-594">Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-595">Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-596">Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="f1b1f-597">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f1b1f-598">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="f1b1f-599">Seu ambiente de origem deve ter um dos seguintes níveis mínimos:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-600">Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-601">Um único ambiente de email compatível com o protocolo IMAP.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-602">Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-603">Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="f1b1f-604">Software de cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, cliente de sincronização do OneDrive for Business, Área de Trabalho do Power BI e Skype for Business deve estar em um nível mínimo conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-605"><strong>Governança de informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-606">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-607">Criação e publicação de rótulos e políticas de retenção (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="f1b1f-608">Gerenciamento de registros (com suporte apenas no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="f1b1f-609">Revisão da criação do plano de arquivos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-610">Criando e gerenciando registros (incluindo registros baseados em eventos).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-611">Revisão da disposição.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="f1b1f-612">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-613">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-614">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-615">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-616">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-617">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-618">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-619">

  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="f1b1f-620">Desenvolvimento de um plano de arquivo de gerenciamento de registros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="f1b1f-621">Conectores de dados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="f1b1f-622">Desenvolvimento da arquitetura de informações no SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="f1b1f-623">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f1b1f-624">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-625">Suporte para E3.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="f1b1f-626">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-627">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="f1b1f-628">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-629"><strong>Proteção de Informações da Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-630">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-631">Classificação de dados (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-632">Tipos de informações confidenciais (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-633">Criando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-634">Aplicando rótulos de sensibilidade (com suporte no E3 e no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-635">Classificadores com treinamento (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-636">Conhecer seus dados com o explorador de conteúdo e o explorador de atividades (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-637">Rótulos de publicação usando políticas (manuais e automáticas) (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-638">Criando políticas de prevenção contra perda de dados de ponto de extremidade (DLP) para dispositivos Windows 10 (com suporte no E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-639">Criando políticas de DLP para chats e canais do Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-640">

<strong> Gerenciador de Conformidade</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f1b1f-641">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f1b1f-642">Revisão de tipos de função.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-643">Adicionando e configurando avaliações.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f1b1f-644">Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f1b1f-645">Revisar o mapeamento de controles internos e a avaliação de controles.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f1b1f-646">Gerando um relatório dentro de uma avaliação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f1b1f-647">

<strong> Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="f1b1f-648">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-649">Ativando e configurando seu locatário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-650">Criando e configurando rótulos e políticas (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-651">Aplicar proteção de informações a documentos (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-652">Classificando e rotulando automaticamente informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de Proteção de Informações do Azure (com suporte no P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-653">Descobrir e rotular arquivos em repouso usando o scanner de Proteção de Informações do Azure (com suporte em P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-654">Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="f1b1f-655">As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="f1b1f-656"><strong>O seguinte está fora do escopo </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="f1b1f-657">Chave do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-657">Customer key.</span></span></li>
<li><span data-ttu-id="f1b1f-658">Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="f1b1f-659">Criação ou modificação de dicionários de palavras-chave.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="f1b1f-660">Scripts personalizados e codificação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f1b1f-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="f1b1f-662">Design, arquiteto e revisão de documentos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f1b1f-663">Conformidade com regulamentos e requisitos do setor e regionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f1b1f-664">Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="f1b1f-665">Além da parte <strong>de integração principal</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema com exceção da Proteção de Informações do Azure.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="f1b1f-666"><strong>Proteção de Informações do Azure</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="f1b1f-667">As responsabilidades de pré-requisito do cliente incluem:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-668">Uma lista de locais de compartilhamento de arquivos a serem verificados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-669">Uma taxonomia de classificação aprovada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="f1b1f-670">Noções básicas sobre qualquer restrição regulamentar ou requisitos referentes ao gerenciamento de chaves.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-671">Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-672">Rótulos configurados para classificação e proteção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="f1b1f-673">Todos os pré-requisitos para o scanner de Proteção de Informações do Azure estão no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="f1b1f-674">Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="f1b1f-675">Verifique se os dispositivos de usuário estão executando um sistema operacional com suporte e ter os pré-requisitos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="f1b1f-676">Consulte o seguinte para obter mais detalhes.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="f1b1f-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia de administração: instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </span><span class="sxs-lookup"><span data-stu-id="f1b1f-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="f1b1f-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="f1b1f-679">Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector rms do Active Directory (AD RMS) para suporte híbrido.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-680">Configuração e configuração de Bring Your Own Key (BYOK), DKE (Double Key Encryption) (somente cliente de rotulagem unificada) ou Hold Your Own Key (HYOK) (somente cliente clássico) caso você exigir uma dessas opções para sua implantação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-682">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-683">Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-684">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-685">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-686">Confirmação da habilitação do Teams no seu locatário do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-687">Habilitação ou desabilitação de licenças de usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-688">Avaliação Rede para o Teams:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-689">Verificações de porta e de ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-690">Verificações de qualidade da conexão.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-691">Estimativas de largura de banda.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="f1b1f-692">Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="f1b1f-693">Se aplicável, também forneceremos diretrizes para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-694">Dispositivos para a Sala do Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="f1b1f-695">Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catálogo de dispositivos do Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-696">Assistência remota com configuração do lado do serviço de dispositivos Microsoft Teams Rooms certificados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-697">Habilitar a Audioconferência:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-698">Configuração da organização para as configurações padrão da ponte de conferência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-699">Atribuição da ponte de conferência para usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f1b1f-700">Sistema de Telefonia:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-701">Configuração da organização para as configurações padrão do Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-702">Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):</span><span class="sxs-lookup"><span data-stu-id="f1b1f-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-703">Atribuição de números a usuários licenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-704">Orientação de portabilidade do número local pela IU (interface do usuário) até 999.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-705">Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-706">Diretrizes de Roteamento Direto:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-707">Diretrizes de configuração da organização para o design de Roteamento Direto de cenários hospedados pelo parceiro ou cenários implantados pelo cliente para até 10 sites.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-708">Revisão de configuração do Controlador de Borda de Sessão (SBC).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="f1b1f-709">Assistência remota com configuração do plano de discagem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="f1b1f-710">Configuração de rota de voz.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="f1b1f-711">Bypass de mídia e otimização de mídia local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-712">Habilitação dos eventos ao vivo do Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-713">Configuração e integração da organização com o Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-714">Diretrizes para a transição do Skype for Business para o Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f1b1f-715">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-716">Usuários habilitados para o SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-717">Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-718">Habilitado para Grupos do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-719">
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f1b1f-720">O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f1b1f-721">O Teams não oferece suporte para o SharePoint no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="f1b1f-722">
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio em casa no Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="f1b1f-723">Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="f1b1f-724">Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="f1b1f-725">Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-726"><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-727">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-728">Habilitação de Links Seguros, Anexos Seguros e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-729">Configuração de automação, investigação e resposta.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-730">Uso do Simulador de Ataques.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-731">Relatórios e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-732">Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-733"><strong>Outlook para iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-734">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-735">Baixe o Outlook para iOS e Android no Google Play e Apple App Store.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-736">Configurar contas e acessar a caixa de correio do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-737">Proteger o Outlook Mobile (para obter mais informações, confira <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f1b1f-738">Identidades dos usuários habilitadas no Azure Active Directory para Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-739">Exchange Online configurado e licenças atribuídas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-741">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-742">Atribuição de licenças do Power BI.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-743">Implantação do aplicativo do Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-744">Software cliente online como a Área de Trabalho do Power BI deve estar em um nível mínimo, conforme definido nos requisitos do sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-746">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-747">Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-748">Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-749">Configurar o ERP (Pool de Recursos da Empresa).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-750">Criando seu primeiro projeto.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-751">Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-752"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-753">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-754">Solução de problemas de implantação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-755">Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-756">Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-757">Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-758">Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-759">Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-760">Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-761"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-762">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-763">Configuração do DNS.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-764">Configurar portas do firewall.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-765">Provisionar usuários e licenças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="f1b1f-766">Habilitar a criação de sites para o administrador do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="f1b1f-767">Planejamento de conjuntos de sites.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="f1b1f-768">Proteção de conteúdo e gerenciamento de permissões.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="f1b1f-769">Configuração de recursos do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="f1b1f-770">Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-771">Método de migração.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="f1b1f-772">Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-773">Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-774">Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-775">Planejar e implementar a distribuição única (ou em fases) para todos os usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-776">Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="f1b1f-777">Redirecionar ou mover pastas conhecidas para o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="f1b1f-778">Implantar o cliente de sincronização do OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-779">
  <strong>Migração de dados</strong>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f1b1f-780">Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="f1b1f-781"><strong>Para o SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-782">A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-783">
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-784">Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-785">
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="f1b1f-786">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="f1b1f-787">Para obter mais informações, consulte <a href="https://go.microsoft.com/fwlink/?linkid=853548">Níveis mínimos de atualização pública para recursos híbridos do SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="f1b1f-788">
  <strong>Observação:</strong> Para obter informações sobre recursos multi-geo, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="f1b1f-790">Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="f1b1f-791">O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">do sistema para o Microsoft 365 e o Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="f1b1f-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f1b1f-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-793"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-794"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-795"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f1b1f-796"><strong>Azure AD (Active Directory) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-797">Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f1b1f-798">

<strong>Proteger a infraestrutura de base</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-799">Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-800">Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-801">Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-802">Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-803">Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-804">Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-805">Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-806">Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-807">Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-808">Configurar o ingresso no Azure AD híbrido.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-809">Configurar o ingresso no Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-810">
  
<strong>Métricas e relatórios</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-811">Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-812">
  
<strong>Governança</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-813">Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f1b1f-814">Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-815">Revisar os termos de uso do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-816">Gerenciando e controlando o acesso a contas de administrador privilegiadas com o Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-817">
  
<strong>Automação e eficiência </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-818">Habilitar o Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f1b1f-819">Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-820">Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-821">Habilitar os grupos dinâmicos do Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-822">Organizar aplicativos no portal Meus Aplicativos usando coleções.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f1b1f-823">O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f1b1f-824"><strong>Proteção de Informações do Azure </strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-825">Para obter mais informações sobre a Proteção de Informações do Azure, consulte <strong>Proteção de Informações da Microsoft</strong> em Segurança e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Conformidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f1b1f-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-827">Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado na nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f1b1f-828">As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f1b1f-829">As etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-830">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-831">Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-832">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-833">Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-834">Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-835">Fornecendo instruções MDM para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-836">Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-837">Configuração do gerenciamento das políticas e serviços do MDM, como:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-838">Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-839">Políticas de Acesso Condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-840">Implantação de perfis de email, redes sem fio e VPN se você tiver uma autoridade de certificação existente, rede sem fio ou infraestrutura VPN em sua organização.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-841">Conexão ao Intune Data Warehouse.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-842">Integração do Intune com:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-843">O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-844">Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-845">Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-846">Registração dos dispositivos de todas as plataformas compatíveis com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-847">Fornecendo diretrizes de proteção de aplicativos para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-848">Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-849">Configurar as políticas de acesso condicional para aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-850">Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-851">Usar os relatórios de uso de aplicativos gerenciados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-852">Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-853">
  
</li>
</ul>
  
<strong>Vincular à nuvem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f1b1f-854">Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f1b1f-855">As etapas exatas dependem do ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f1b1f-856">Essas etapas podem incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f1b1f-857">Licenciamento para os usuários finais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-858">A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-859">Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-860">Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-861">Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-862">Fornecendo orientações sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-863">Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-864">Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f1b1f-865"><strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f1b1f-866">As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f1b1f-867">Isso pode incluir:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-868">Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-869">Fornece orientação sobre como configurar:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-870">O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-871">Políticas de proteção de aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-872">Políticas de acesso condicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-873">Políticas de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="f1b1f-874">Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f1b1f-875"><strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f1b1f-876"><strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f1b1f-877">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f1b1f-878"><strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="f1b1f-879"><strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f1b1f-880">Não fornecemos assistência na compra, licenciamento ou ativação.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f1b1f-881">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f1b1f-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f1b1f-883">Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="f1b1f-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f1b1f-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-885"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-886"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-887"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f1b1f-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-889">Fornecemos orientações para atualização do Windows 7 Professional e do Windows 8.1 Professional para o Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="f1b1f-890">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-891">Entender a sua intenção do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-892">Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-893">Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-894">Recomendamos opções para você avaliar os aplicativos do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-895">Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-896">Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-897">Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-898">Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-899">Diretrizes de atualização para dar suporte ao seu movimento de implantação existente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="f1b1f-900">O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="f1b1f-901">As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-902">Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="f1b1f-903">Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-904">
  <strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-905">Atualizar o Configuration Manager para o Branch Atual.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-906">Criar imagens personalizadas para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-907">Criar e dar suporte à implantação de scripts para a implantação do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-908">Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-909">Habilitar os recursos de segurança do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-910">Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-911">Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-912">Usar a Ferramenta de Migração de Estado do Usuário (USMT).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="f1b1f-913">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="f1b1f-914">Para a atualização do computador, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-915">SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-916">Dispositivos: fator forma de desktop, notebook ou tablet.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-917">SO de destino: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="f1b1f-918">Para atualização da infraestrutura, você deve atender a esses requisitos:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-920">A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="f1b1f-921">Para obter mais informações, confira a tabela de suporte do Configuration Manager em <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="f1b1f-922"><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-923">A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f1b1f-924">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-925">Implantar as tecnologias para proteger seus pontos de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-926">Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-927">Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-928">Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-929">Avaliar proxies e firewalls que restringem o tráfego de rede.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-930">Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-931">Diretrizes de implantação, assistência de configuração e treinamento em:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-932">Gerenciamento de ameaças e vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-933">Redução da superfície do ataque.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-934">Proteção da próxima geração.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-935">Detecção e resposta do terminal.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-936">Investigação e correção automatizadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="f1b1f-937">Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="f1b1f-938">Classificação de segurança.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-939">Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-940">Visão geral dos recursos de relatório e análise de ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-941">Integrar o ATP do Office 365 com o ATP do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-942">Conduzir instruções do Portal do centre de segurança do Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-943">Um dos seguintes sistemas operacionais:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-947">Windows Server 2019, Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-948">Canal semestral do Windows Server (SAC) versão 1803.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-949">macOS versões 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f1b1f-950">
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f1b1f-951"></li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-952">Gerenciamento de projetos das atividades de correção do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-953">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-954">Gerenciamento contínuo e resposta a ameaças.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-955">Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-956">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-959">Dispositivos móveis (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="f1b1f-960">Virtual Desktop Infrastructure (VDI) (persistente ou não persistente).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-961">Integração e configuração do servidor:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-962">Configurar um servidor proxy para comunicações offline.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-963">Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-964">Servidores de integração com a Central de Segurança do Azure.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-965">Os servidores não são gerenciados pelo Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-966">Integração e configuração do macOS:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-967">Implantação manual baseada no Intune.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-968">Implantação baseada em JAMF.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f1b1f-969">Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-970">Implantação manual.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f1b1f-971">Configuração dos seguintes recursos de redução da superfície de ataque:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-972">Isolamento baseado em hardware.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-973">Controle de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="f1b1f-974">Controle de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="f1b1f-975">Explorar proteção.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-976">Firewall da rede.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="f1b1f-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="f1b1f-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="f1b1f-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="f1b1f-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="f1b1f-979">Configuração ou gerenciamento do BitLocker.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="f1b1f-980">Inscrição ou configuração dos Peritos em ameaças da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-981">Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-982">Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-983">Treinamento ou orientação sobre a caça avançada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-984">Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="f1b1f-985">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="f1b1f-986">Área de Trabalho Virtual do Windows</span><span class="sxs-lookup"><span data-stu-id="f1b1f-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-987"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-988"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-989"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f1b1f-990"><strong>Área de Trabalho Virtual do Windows</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="f1b1f-991">Fornecemos diretrizes de implantação para integração à Área de Trabalho Virtual do Windows (um serviço de virtualização de aplicativo e área de trabalho).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="f1b1f-992">A Área de Trabalho Virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para o Microsoft 365 Apps for Enterprise com segurança e gerenciamento integrados para o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="f1b1f-993">Fornecemos orientações remotas para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="f1b1f-994">Implantando seu ambiente de Área de Trabalho Virtual do Windows com várias sessões do Windows 10 Enterprise e Aplicativos do Microsoft 365 para Empresas usando o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-995">Imagem do Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="f1b1f-996">Imagem compartilhada.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-996">Shared image.</span></span></li>
<li><span data-ttu-id="f1b1f-997">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="f1b1f-998">Configurando FSLogix:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-999">Implantando o agente FSLogix com contêiner de perfil.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="f1b1f-1000">Implantando o agente FSLogix com o contêiner do Office.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="f1b1f-1001">Configurando a pasta FSLogix com exclusões de conteúdo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="f1b1f-1002">Implantando o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="f1b1f-1003">Implantando o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="f1b1f-1004">Conectando-se usando clientes da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="f1b1f-1005">

<strong>O seguinte está fora do escopo</strong>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="f1b1f-1006">Gerenciamento de projetos da implantação da Área de Trabalho Virtual do Cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="f1b1f-1007">Implantação e virtualização de aplicativos de terceiros.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="f1b1f-1008">Imagens personalizadas.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1008">Custom images.</span></span></li>
<li><span data-ttu-id="f1b1f-1009">Migrações e cenários envolvendo VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="f1b1f-1010">Cenários do Linux.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="f1b1f-1011">Conversão ou migrações de perfis de usuário.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="f1b1f-1012">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="f1b1f-1013">Você já deve ter o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento da Área de Trabalho Virtual do Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="f1b1f-1015">Rede do Azure:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-1016">Criação e sub-rede de rede virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="f1b1f-1017">Grupos de segurança de rede e firewall.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="f1b1f-1018">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="f1b1f-1019">Roteamento para o Azure no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="f1b1f-1020">Regras de firewall para permitir a conectividade com a Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="f1b1f-1021">Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Área de Trabalho Remota com suporte.</a></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="f1b1f-1022">Configuração geral do Azure AD:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="f1b1f-1023">Estratégia de <i>identidade (você pode usar apenas uma das três opções a seguir):</i>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="f1b1f-1024">Active Directory com o Azure AD Connect no Azure.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="f1b1f-1025">Active Directory com o Azure AD Connect local através de VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="f1b1f-1026">Serviços de Domínio do Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="f1b1f-1027">Garantia do aplicativo</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-1028"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-1029"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-1030"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f1b1f-1031"><strong>Garantia de Aplicativo</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="f1b1f-1032">A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="f1b1f-1033">Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="f1b1f-1034">Também fornecemos orientações aos clientes que enfrentam problemas de compatibilidade ao implantar a Área de Trabalho Virtual do Windows e o Microsoft Edge e fazem todos os esforços razoáveis para resolver problemas de compatibilidade.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="f1b1f-1035">Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="f1b1f-1036"><strong>Windows 10 </strong> (incluindo dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="f1b1f-1037"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="f1b1f-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="f1b1f-1038"><strong>Microsoft Edge -</strong> Para obter orientações de implantação, consulte <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Visão geral dos canais do Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-1039"><strong>Área de trabalho virtual do</strong> - Windows Para obter mais informações, consulte O que é a Área de Trabalho Virtual do <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows?</a> e Perguntas frequentes de várias <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">sessões do Windows 10 Enterprise.</a></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="f1b1f-1040">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-1041">Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1041">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="f1b1f-1042">Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1042">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="f1b1f-1043">Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1043">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="f1b1f-1044">Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="f1b1f-1045">Para obter mais informações, confira <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="f1b1f-1046">Serviços de embalagem do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1046">App packaging-only services.</span></span> <span data-ttu-id="f1b1f-1047">No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="f1b1f-1048">

<strong>As responsabilidades do cliente incluem</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f1b1f-1049">Criar um inventário de aplicativo.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="f1b1f-1050">Validando esses aplicativos no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="f1b1f-1051">
<strong>Observação:</strong>  A Microsoft não pode fazer alterações no código-fonte.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="f1b1f-1052">No entanto, a equipe da Garantia de Aplicativo da Área de Trabalho pode fornecer orientações para os desenvolvedores de aplicativo se o código-fonte estiver disponível para os aplicativos.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="f1b1f-1053">Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="f1b1f-1054"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-1055">Os aplicativos que funcionavam no Windows 7, Windows 8.1, Office 2010 e Office 2013 também funcionam no Windows 10 e no Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-1056">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="f1b1f-1057">Os aplicativos que funcionaram no Windows 7, Office 2010 ou versões posteriores também funcionam no Windows 10 e no Microsoft 365 Apps em dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="f1b1f-1058">
  <strong>Observação:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="f1b1f-1059">A emulação x64 (64 bits) está disponível na visualização para clientes que participam do <a href="https://insider.windows.com/">Programa Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="f1b1f-1060">Para clientes que não são do Windows Insider no Windows 10 versão 2004 (ou posterior), o Arm64 Photoshop tem suporte usando o OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">o OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="f1b1f-1061">Os clientes no Programa Windows Insider podem baixar uma versão insider do OpenCL e do OpenGL Compatibility Pack para uso com aplicativos adicionais.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="f1b1f-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-1063">Se seus aplicativos web ou sites funcionarem no Internet Explorer 11, versões com suporte do Google Chrome ou qualquer versão do Microsoft Edge, eles também funcionarão com o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-1064">Como a Web está em constante evolução, revise esta lista publicada de alterações conhecidas que impactam a compatibilidade do <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site para o Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-1065">
  <strong>Área de Trabalho Virtual do Windows</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f1b1f-1066">Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-1067">Aplicativos em execução em qualquer ambiente de infraestrutura de área de trabalho virtual (VDI) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-1068">Aplicativos em execução em dispositivos cliente Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="f1b1f-1069">
  <strong>Observação:</strong> As exclusões e limitações de compatibilidade de várias sessões do Windows 10 Enterprise incluem:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="f1b1f-1070">Redirecionamento limitado de hardware.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-1071">Aplicativos de uso intensivo de A/V podem ser executados com uma capacidade reduzida.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f1b1f-1072">Não há suporte para aplicativos de 16 bits na Área de Trabalho Virtual do Windows de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="f1b1f-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f1b1f-1074"><strong>Serviço</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f1b1f-1075"><strong>Detalhes da orientação do FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f1b1f-1076"><strong>Expectativas do ambiente de origem</strong></span><span class="sxs-lookup"><span data-stu-id="f1b1f-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f1b1f-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="f1b1f-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="f1b1f-1078">Fornecemos orientação e compatibilidade de implantação remota e adoção para:</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="f1b1f-1079">Implantando o Microsoft Edge no Windows 10 com o Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-1080">Configurando o Microsoft Edge (usando políticas de grupo ou configuração de aplicativos do Intune e políticas de aplicativo).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-1081">Inventário da lista de sites que podem exigir uso no modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="f1b1f-1082">Habilitação do modo do Internet Explorer com a lista de sites corporativos existente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="f1b1f-1083">(Para obter mais informações, consulte <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="f1b1f-1084">Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="f1b1f-1085">Para solicitar suporte de compatibilidade para o App Assure, entre no <a href="https://fasttrack.microsoft.com/portal#/signin">portal do FastTrack</a> para iniciar um envolvimento.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="f1b1f-1086">Diretrizes de planejamento para adoção de borda e orientação de configuração para indicadores da Pesquisa da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="f1b1f-1087">

<strong>O seguinte está fora do escopo </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="f1b1f-1088">Gerenciamento de projetos de implantação do Microsoft Edge do cliente.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="f1b1f-1089">Suporte no local.</span><span class="sxs-lookup"><span data-stu-id="f1b1f-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

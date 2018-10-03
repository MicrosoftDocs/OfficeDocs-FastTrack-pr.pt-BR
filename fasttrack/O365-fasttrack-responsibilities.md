---
title: Responsibilities do FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9840bd79-fb09-4f8e-b7c9-e96dfdcd3a33
description: Os Especialistas do FastTrack têm as seguintes responsabilidades durante a integração.
ms.openlocfilehash: 813fc4c1f4fdb48bdae8184b9afc0528dcb4feb7
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353728"
---
# <a name="fasttrack-responsibilities"></a>Responsibilities do FastTrack

Os Especialistas do FastTrack têm as seguintes responsabilidades durante a integração.\*
  
## <a name="general"></a>Geral

- Fornecer assistência remota para o desenvolvimento e a implementação do planejamento de sucesso e para as atividades de configuração necessárias conforme o especificado nas descrições de fase.
- Fornecemos a documentação, as ferramentas de software, os consoles de administrador e os scripts disponíveis para oferecer orientações para reduzir ou a eliminar as tarefas de configuração e os recursos do planejamento de sucesso. 
    
## <a name="initiate-phase"></a>Fase Iniciar

- Trabalhar com você para compreender sua finalidade, as metas organizacionais e os planos de uso do serviço.
- Trabalhar com você usando serviços de colaboração do Office 365 (como Microsoft Teams) para iniciar a integração.   
- Define que serviços qualificados você deseja integrar. 
    
## <a name="assess-phase"></a>Fase Avaliar

- Mantenha uma chamada de planejamento de sucesso para obter orientações sobre como ter uma adoção de usuários eficiente.  
- Fornece uma visão geral administrativa.
- Fornece orientação sobre: 
  - Necessidades de DNS (Sistema de Nomes de Domínio), rede e infraestrutura.
  - As necessidades do cliente, como navegador da Internet, sistema operacional e requisitos dos serviços.
  - Identidade do usuário e provisionamento.
  - Habilitação de serviços qualificados que são comprados e definidos como parte da integração. 
  - Agregando valor ao serviço e gerando sua adoção.  
- Estabelecimento da linha do tempo para atividades de correção.
- Fornecimento de uma lista de verificação da correção. 
- Avaliar a infraestrutura existente do SharePoint Server 2013 ou do SharePoint Server 2016, incluindo:
  - Pré-requisitos para Implantação Híbrida do SharePoint Online. 
  - Disponibilidade de infraestrutura local para recursos do Implantação Híbrida do SharePoint Online.
  - Acesso aos pontos de extremidade necessários do SharePoint Online.
  - Audiências do Implantação Híbrida do OneDrive for Business. 
- Avaliar a infraestrutura existente do Lync ou do Skype for Business online, incluindo:
  - Estratégia de implantação do cliente do Skype for Business com suporte
  - Acesso aos pontos de extremidade.
  - Qualidade da conexão
  - Estimativas de largura de banda.
  - Pré-requisitos de suporte para a configuração de servidor de domínio dividido.
  - Preparação de usuários identificados para transferir para o Skype for Business online.
- Avaliação da infraestrutura de mensagens, incluindo: 
  - Fluxo de email geral e princípios de roteamento.
  - Acesso para cliente (incluindo pontos de extremidade de acesso para clientes publicados existentes).
  - Ambiente de mensagens de origem para atender às necessidades da integração
- Fornece migração de dados se o serviço de migração de dados do Centro FastTrack for usado e se você estiver qualificado.
    
## <a name="remediate-phase"></a>Fase Corrigir

- Realiza chamadas de conferência com você de acordo com o cronograma acordado para analisar o progresso das atividades de correção e planejamento de sucesso. 
- Orienta você na execução de ferramentas de avaliação para identificar e solucionar problemas e para interpretar os resultados.
    
## <a name="enable-phase"></a>Fase Habilitar

Fornece orientação sobre: 
- Avaliando o progresso do planejamento de sucesso e determinando se é necessário realizar assistência adicional.
- Ativação do locatário do Office 365.  
- Configuração de protocolos TCP/IP e portas do firewall.
- Configuração do DNS para serviços qualificados. 
- Validação da conectividade com o Office 365.
- Conexão do Microsoft Active Diretory local ao Azure Active Directory:
  - Instalação de um servidor de sincronização de diretórios entre os seus Active Directory Domain Services (AD DS) e o Office 365, se necessário. 
  - Configuração de sincronização de senha (hash de senha) para o Office 365 (Azure Active Directory) com a ferramenta Azure Active Directory Connect Health, quando necessário.
  - Para ambientes com uma única ou várias florestas:
      - Configurar a autenticação de passagem do Azure Active Directory, se necessário.\*\*
      - Configurar o logon único (SSO) contínuo do Azure Active Directory, se necessário.\*\*\*
    > [!NOTE]
    > A autenticação de passagem do Azure Active Directory para ambientes com várias florestas será compatível se houver uma relação de confiança na floresta entre as florestas do Active Directory e se o roteamento do sufixo do nome estiver devidamente configurado. Agentes adicionais podem ser instalados em vários servidores locais para oferecer alta disponibilidade para solicitações de entrada. Para obter mais informações, confira [Autenticação de passagem do Azure Active Directory: início rápido](https://go.microsoft.com/fwlink/?linkid=860094) e [Logon único contínuo do Azure Active Directory: Início rápido](https://go.microsoft.com/fwlink/?linkid=860095). 
- Para uma única floresta, quando as identidades federadas são o destino: 
  - Instalando e configurando o AD FS para autenticação de domínio local com o Office 365 em uma configuração de site único e tolerante a falhas, se necessário.
  - Instalar e configurar WAP para publicar sua infraestrutura AD FS na Internet, quando necessário.
    > [!NOTE]
    > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo. 
- Teste da funcionalidade de SSO, se implantada.
- Agregando valor ao serviço e gerando sua adoção.
    
\*\*Confira mais informações sobre os limites de autenticação de passagem em [Autenticação de passagem do Azure Active Directory: limitações atuais](https://go.microsoft.com/fwlink/?linkid=860356). 

\*\*\*Para mais informações sobre problemas de SSO Contínuo, confira [Solucionar problemas de Logon Único Contínuo do Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926).

## <a name="exchange-online"></a>Exchange Online

Fornece orientação sobre:
- Criando ou atualizando registros DNS. 
- Habilitar o roteamento de emails entre o sistema de mensagens de origem e ambientes do Office 365. 
- Configurar recursos do Proteção do Exchange Online (incluindo recursos do Proteção Avançada Contra Ameaças do Exchange Online, caso esteja disponível em sua assinatura) e verificar os registros MX para que apontem para o Office 365 em todos os domínios habilitados para email validados.
- Configurar a instalação híbrida entre a organização local única do Exchange e o Office 365 *ou* entre várias organizações locais do Exchange e o Office 365. 
    
Para saber mais sobre as responsabilidades de migração de dados, confira [Migração de dados](O365-data-migration.md).
  
## <a name="sharepoint-online"></a>SharePoint Online

Fornece orientação sobre:
- Configuração de provisionamento de usuário incluindo licenciamento.
- Habilitar a criação de sites para o administrador do SharePoint Online.    
- Planejamento de conjuntos de sites. 
- Proteção de conteúdo e gerenciamento de permissões.
- Habilitação de sites pessoais e recursos sociais.
- Configuração de recursos do SharePoint Online. 
- Fornecimento de migração de dados se o serviço de migração de dados do Centro FastTrack for usado e se você estiver qualificado.
- Avaliação da configuração da infraestrutura de farm do SharePoint local necessária para o Implantação Híbrida do SharePoint Online. 
- Uso de ferramentas e automação para:
  - Configurar aplicativos de serviço Pesquisa na Nuvem locais. 
  - Configurar a confiança entre os ambientes locais e de nuvem do SharePoint.
- Configurar sites locais do SharePoint para usar recursos do Implantação Híbrida do SharePoint Online.
    
## <a name="onedrive-for-business"></a>OneDrive for Business

Fornece orientação sobre:
- Identificação da versão local do SharePoint e opções de integração. 
- Identificação de opções de identidade e sincronização.
- Seleção de uma opção de distribuição:   
  - Distribuição Just-In-Time.
  - Distribuição em etapas (sequenciada e faseada).
- Preparação do ambiente local para implantação do OneDrive for Business:
  - Identificando o cliente de sincronização correto do OneDrive for Business.
  - Configuração de DNS, portas de rede e firewall. 
- Atribuição de licenças de usuário final. 
- Configuração de audiências do SharePoint Online para controlar e reger quem obtém o OneDrive for Business. 
- Implantar o cliente de sincronização do OneDrive for Business em computadores.   
- Como configurar o redirecionamento do OneDrive for Business na Implantação Híbrida do SharePoint Online (apenas SharePoint 2013 e SharePoint 2016).
- Migração de dados se o serviço de migração de dados do Centro FastTrack for usado e se você estiver qualificado.
    
## <a name="skype-for-business-online"></a>Skype for Business online

Fornece orientação sobre:
- Provisionamento de identidades do Skype for Business para o Office 365. 
- Habilitando mensagens instantâneas (IM) e recursos de presença para o Office 365. 
- Criação de contas para associar aos dispositivos do sistema de sala com suporte (até 10 contas). 
- Configuração de um ambiente de servidor de domínio dividido para fornecer suporte à implantação híbrida do Lync ou a cenários de implantação híbrida do Skype for Business online, quando aplicável.
- Habilitar a Audioconferência:
  - Configuração da organização para as configurações padrão da ponte de conferência.
  - Atribuição de uma ponte de conferência para usuários licenciados
- Habilitar o Sistema Telefônico:
  - Habilitar a integração de Sistema Telefônico e Planos de Chamada (em mercados disponíveis).
  - Atribuição de números a usuários licenciados.
  - Orientação de portabilidade do número local pela interface do usuário até 999.
  - Suporte SR à portabilidade do número local superior a 999.
- Habilitar Transmissão de Reunião do Skype for Business:
  - Habilitando a integração orientada de Transmissão de Reunião do Skype for Business
  - Configuração da organização para federação com o serviço Transmissão da Reunião.
    
## <a name="microsoft-teams"></a>Microsoft Teams

Fornece orientação sobre:
- Confirmação dos requisitos mínimos.
- Configurar portas do firewall.
- Configuração do DNS.  
- Confirmação de que o Microsoft Teams está habilitado no seu locatário do Office 365.
- Habilitação ou desabilitação de licenças de usuário.
- Distribuição de clientes do Microsoft Teams.
- Recursos do IT Pro e do administrador.
- Principais recursos do produto.
- Modelos de sucesso dos clientes.
    
## <a name="power-bi"></a>Power BI

Fornece orientação sobre:
- Como analisar os planos de assinatura do Power BI. 
- Adicionar o serviço do Power BI. 
- Baixando o aplicativo do Power BI Desktop.
    
## <a name="project-online"></a>Project Online

Fornece orientação sobre:
- Como analisar planos de assinatura.
- Como verificar funcionalidades básicas do SharePoint.
- Adicionar o serviço do Project Online.
- Como adicionar usuários ao Project Online, inclusive a Sincronização do ERP
- Como verificar as funcionalidades básicas do Project Online durante a criação de um projeto
    
## <a name="project-online-professional-and-project-online-premium"></a>Project Online Professional e Project Online Premium

Fornece orientação sobre:
- Solução de problemas de implantação.
- Atribuição de licenças de usuário final usando o Centro de administração do Office 365 e o Windows PowerShell.
- Como baixar e instalar o Cliente da Área de Trabalho do Project Online pelo portal.   
- A definição de configurações de atualização usando os modelos de Ferramenta de Implantação ou Política de Grupo do Office.
- Como configurar um servidor de distribuição local exclusivo para o Cliente da Área de Trabalho do Project Online, incluindo orientação para criar um arquivo configuration.xml para a Ferramenta de Implantação do Office 2016. 
- Conexão do Cliente da Área de Trabalho do Project Online ao Project Online.
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Fornecer orientação sobre como converter sua rede do Yammer Basic única em uma rede do Yammer Enterprise única.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Fornece orientação sobre:
- Solução de problemas de implantação.
- Atribuição de licenças de usuário final usando o Centro de administração do Office 365 e o Windows PowerShell.
- Instalação do Office 365 ProPlus pelo portal do Office 365 usando Clique para Executar.
- Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS, Android ou Windows Mobile. 
- Configurar definições de atualização usando os modelos de Ferramenta de Implantação ou Política de Grupo do Office 2016.
- Configurar um servidor de distribuição local único para o Office 365 ProPlus, incluindo orientação para criar um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office.
- A implantação usando o System Center Configuration Manager, incluindo orientações para criar um pacote do System Center Configuration Manager.
    
## <a name="microsoft-staffhub"></a>Microsoft StaffHub

Fornece orientação sobre:
- Confirmação de que o Microsoft StaffHub está habilitado no seu locatário do Office 365.
- Habilitação ou desabilitação de licenças de usuário.
- Principais recursos do produto.
- Locais de download para o Microsoft StaffHub.
    
\*Para saber mais sobre as responsabilidades do FastTrack para Office 365 US Government, confira [Responsabilidades do FastTrack para Office 365 US Government](US-Gov-appendix-fasttrack-responsibilities.md).

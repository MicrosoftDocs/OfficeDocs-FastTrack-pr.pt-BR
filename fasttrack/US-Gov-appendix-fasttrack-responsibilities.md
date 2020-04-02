---
title: Responsabilidades do FastTrack para o governo dos EUA do Office 365
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Os Especialistas do FastTrack têm as seguintes responsabilidades durante a integração.
ms.openlocfilehash: 2a39c7fb74d0b8d9e369a0b61a7a97b892aa9e7a
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098249"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Responsabilidades do FastTrack para o governo dos EUA do Office 365

Os Especialistas do FastTrack têm as seguintes responsabilidades durante a integração.  
  
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
  - Pré-requisitos para o SharePoint Online híbrido.  
  - Preparação da infraestrutura local para os recursos híbridos do SharePoint Online.  
  - Acesso aos pontos de extremidade necessários do SharePoint Online. 
  - Públicos do OneDrive for Business híbrido.    
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
      - Configurando a autenticação de passagem do Azure Active Directory, se necessário (não disponível nos planos GCC High ou DoD).
      - Configurar o logon único (SSO) contínuo do Azure Active Directory, se necessário (não disponível nos planos GCC High ou DoD).
    > [!NOTE]
    > A autenticação de passagem do Azure Active Directory para ambientes com várias florestas será compatível se houver uma relação de confiança na floresta entre as florestas do Active Directory e se o roteamento do sufixo do nome estiver devidamente configurado. Agentes adicionais podem ser instalados em vários servidores locais para oferecer alta disponibilidade para solicitações de entrada. Para obter mais informações, confira [Autenticação de passagem do Azure Active Directory: início rápido](https://go.microsoft.com/fwlink/?linkid=860094) e [Logon único contínuo do Azure Active Directory: Início rápido](https://go.microsoft.com/fwlink/?linkid=860095).[!NOTE]
    > Confira mais informações sobre os limites de autenticação de passagem em [Autenticação de passagem do Azure Active Directory: limitações atuais](https://go.microsoft.com/fwlink/?linkid=860356).[!NOTE]
    > Para mais informações sobre problemas de SSO Contínuo, confira [Solucionar problemas de Logon Único Contínuo do Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926). 
- Para uma única floresta, quando as identidades federadas são o destino: 
  - Instalando e configurando o AD FS para autenticação de domínio local com o Office 365 em uma configuração de site único e tolerante a falhas, se necessário.  
  - Instalar e configurar WAP para publicar sua infraestrutura AD FS na Internet, quando necessário. 
    > [!NOTE]
    > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo. 
- Teste da funcionalidade de SSO, se implantada.   
- Agregando valor ao serviço e gerando sua adoção.
    
## <a name="exchange-online"></a>Exchange Online

Fornece orientação sobre: 
- Criação ou atualização de registros DNS.    
- Habilitação de roteamento de emails entre o sistema de mensagens de origem e ambientes do Office 365.    
- Configurar recursos do Proteção do Exchange Online (incluindo recursos do Proteção Avançada Contra Ameaças do Exchange Online, caso esteja disponível em sua assinatura) e verificar os registros MX para que apontem para o Office 365 em todos os domínios habilitados para email validados.   
- Configurar a instalação híbrida entre a organização local única do Exchange e o Office 365 *ou* entre várias organizações locais do Exchange e o Office 365. 
- Configurar a Unificação de mensagens (UM) com o Exchange Online (o UM não está disponível nos planos do GCC DoD). 
    
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
- Avaliação da configuração da infraestrutura de farm do SharePoint local necessária para o SharePoint Online híbrido.    
- Uso de ferramentas e automação para: 
  - Configurar aplicativos de serviço Pesquisa na Nuvem locais.    
  - Configurar a confiança entre os ambientes locais e de nuvem do SharePoint.   
- Configurar os sites locais do SharePoint para usar os recursos do SharePoint Online híbrido.
    
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
- Como configurar o redirecionamento do OneDrive for Business para o SharePoint Online híbrido (apenas SharePoint 2013 e SharePoint 2016).  
- Migração de dados se o serviço de migração de dados do Centro FastTrack for usado e se você estiver qualificado.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Fornece orientação sobre:
- Provisionamento de identidades do Skype for Business para o Office 365.   
- Habilitando mensagens instantâneas (IM) e recursos de presença para o Office 365.  
- Criação de contas para associar aos dispositivos do sistema de sala com suporte (até 10 contas).    
- Configuração de um ambiente de servidor de domínio dividido para fornecer suporte à implantação híbrida do Lync ou a cenários de implantação híbrida do Skype for Business online, quando aplicável.   
- Habilitar a Audioconferência:   
  - Configuração da organização para as configurações padrão da ponte de conferência.   
  - Atribuição de uma ponte de conferência para usuários licenciados 
- Habilitando o sistema de telefonia (não está disponível nos planos GCC High ou DoD):  
  - Habilitar a integração de Sistema Telefônico e Planos de Chamada (em mercados disponíveis). 
  - Atribuição de números a usuários licenciados.  
  - Orientação de portabilidade do número local pela interface do usuário até 999.  
  - Suporte SR à portabilidade do número local superior a 999.  
- Habilitar a transmissão de reunião do Skype for Business (não está disponível nos planos GCC High ou DoD):  
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
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Fornecer orientação sobre como converter sua rede do Yammer Basic única em uma rede do Yammer Enterprise única.

> [!NOTE]
> O Yammer Enterprise não é um componente do governo dos EUA do Office 365, mas pode ser adquirido sem custo como uma oferta autônoma para cada usuário licenciado para o Office 365 em GCC. Atualmente, essa oferta é limitada a clientes que compram o Office 365 GCC sob acordos corporativos e contratos de assinatura corporativa. O Yammer não está disponível nos planos GCC High ou DoD.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Fornece orientação sobre:
- Solução de problemas de implantação.   
- Atribuição de licenças de usuário final usando o [centro de administração do Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) e o Windows PowerShell.  
- Instalação do Office 365 ProPlus pelo portal do Office 365 usando Clique para Executar.   
- Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS, Android ou Windows Mobile.   
- Configurar definições de atualização usando os modelos de Ferramenta de Implantação ou Política de Grupo do Office 2016.   
- Configurar um servidor de distribuição local único para o Office 365 ProPlus, incluindo orientação para criar um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.   
- Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.

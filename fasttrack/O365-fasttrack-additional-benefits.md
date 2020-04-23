---
title: Apêndice B Benefício adicional do Centro do FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Os clientes que compram pelo menos vinte mil licenças para um locatário do Exchange Online estão qualificados para usar serviços adicionais do Centro FastTrack. Para saber mais, confira Serviços e planos qualificados.
ms.openlocfilehash: 62d0f5cf99624fbfb69a3bcb950f4718e0372512
ms.sourcegitcommit: 1aa423e2a720d57d2a37fba930fb4d4b0e8f93c9
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43666107"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Apêndice B: Benefício adicional do Centro FastTrack

Os clientes que compram pelo menos vinte mil licenças para um locatário do Exchange Online estão qualificados para usar serviços adicionais do Centro FastTrack. Para saber mais, confira [Serviços e planos qualificados](M365-eligible-services-and-plans.md). 
  
## <a name="onboarding-and-migration-phases"></a>Fases de integração e migração

## <a name="core"></a>Serviços básicos

As adições dos serviços de integração básica incluem orientação para a configuração de Serviços de Federação do Active Directory (AD FS) com redundância geográfica e políticas de acesso de cliente do AD FS para o serviço. 
  
## <a name="exchange-online"></a>Exchange Online

Para o Exchange Online, fornecemos orientação de configuração para:
- Definir a UM (Unificação de Mensagens) com o Exchange Online.
- Configurar a coexistência entre o Exchange Online e pastas públicas locais herdadas.
- Integração com o aplicativo habilitado para email. 
- Planejamento e agrupamento da migração da caixa de correio.
    
## <a name="skype-for-business-online"></a>Skype for Business online

Para o Skype for Business online, fornecemos orientação para migração de usuários do Lync e do Skype for Business locais para o Skype for Business online.
  
## <a name="microsoft-365-apps"></a>Microsoft 365 Apps

Para o Microsoft 365 Apps, fornecemos diretrizes para: 
- Avaliação e planejamento voltados para a preparação do ambiente para implantação inicial e gerenciamento de atualizações de acordo com as práticas recomendadas da Microsoft. 
- Desenvolvimento de configurações de implantação e de atualização usando a Ferramenta de Personalização do Office e a Ferramenta de Implantação e Personalização do Office 365. 
- Empacotamento de implantações usando o Gerenciador de Configurações do Microsoft Endpoint.  
- Habilitação do uso do Readiness Toolkit for Office para identificar possíveis problemas de compatibilidade com as macros e suplementos do Microsoft Visual Basic para Applications (VBA) que você usa com o Office.
    
## <a name="fasttrack-responsibilities"></a>Responsabilidades do FastTrack

Os especialistas do FastTrack têm as responsabilidades a seguir durante a integração. Elas podem ser adicionais ou em substituição às atividades definidas em [Responsibilities do FastTrack](O365-fasttrack-responsibilities.md).
  
## <a name="general"></a>Geral

- Fornecer assistência remota para o desenvolvimento, a implementação do planejamento de sucesso e as atividades de configuração necessárias, conforme especificado em [Fases de integração e migração](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Fase Avaliar

- Mantenha uma chamada de planejamento de sucesso para obter orientações sobre como ter uma adoção de usuários eficiente. 
- Avaliar seu ambiente para dar suporte à configurações do AD FS com redundância geográfica.  
- Executar uma avaliação para identificar seus requisitos de acesso do cliente do AD FS.
    
## <a name="enable-phase"></a>Fase Habilitar

### <a name="geo-redundant-ad-fs-guidance"></a>Orientação do AD FS com redundância geográfica

- Fornecer o design de arquitetura de referência padrão para uma topologia do AD FS com redundância geográfica abrangendo dois (2) datacenters. A arquitetura padrão fornece:
  - Autenticação federada dos serviços no escopo para o Benefício do Centro FastTrack. 
  - Resiliência de único site.  
  - Alta disponibilidade e failover.  
  - Orientação de dimensionamento. 
- Fornecer orientação sobre como usar o Banco de Dados Interno do Windows e o SQL Server como a instância do banco de dados para o farm do AD FS.   
- Validar o estabelecimento de autenticação federada para cada floresta no escopo.  
- Confirmar a funcionalidade da autenticação federada para até 10 usuários.
    
> [!NOTE]
> As implantações do AD FS estão no escopo para clientes qualificados para o benefício adicional com várias configurações de floresta do Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Orientação da política de acesso de cliente do AD FS

- Examinar as políticas e as configurações necessárias para proteger os recursos do Office 365.  
- Fornecer orientação e assistência para a configuração da política de acesso de cliente do AD FS para cenários de acesso de cliente identificados nos limites dos cenários com suporte. Para saber mais, confira [Limitar o acesso aos serviços do Office 365 com base no local do cliente](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Validar a funcionalidade da autenticação federada com políticas de acesso para cliente modificadas para cenários de acesso identificados com configurações de até 10 usuários.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Orientação de Mensagens Unificadas do Exchange

- Fornecer orientações sobre a configuração necessária do Exchange Online para habilitar até 10: 
  - Planos de discagem da UM.   
  - Políticas de caixa de correio da UM. 
  - Atendedores automáticos.  
- Fornecer orientações para a configuração do ambiente do Lync no local ou do Skype for Business para habilitar a UM e, especificamente:  
  - Políticas hospedadas pelo Exchange Online.  
  - Políticas de correio de voz hospedadas pelo Exchange Online. 
  - Unificação de mensagens de contatos de atendedor automático e correio de voz do Outlook para redirecionar usuários para o Exchange Online. 
  - Auxiliar na criação de registros de SRV (Local do Serviço), conforme necessário para a federação.
> [!NOTE]
> A UM pode ser configurada com gateways IP da UM com suporte e SBCS (controladores de borda de sessão). Para saber mais, confira [Integração do sistema telefônico com UM](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Orientação de coexistência de pastas públicas

- Fornecer orientação sobre a coexistência da árvore de pasta pública única, incluindo:  
  - A preparação da pasta pública no Exchange 2007, no Exchange 2010 e no Exchange 2013. 
  - A configuração do Exchange Online para redirecionar o acesso à pasta pública para pastas públicas locais.  
  - A configuração de acesso a pastas públicas do Exchange Online para um único ambiente local do Exchange 2007, do Exchange 2010 ou do Exchange 2013.  
  - Ajudar na validação de acesso para o ambiente de pasta pública para até 10 usuários no Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Orientação para integração de aplicativo habilitado para email

- Fornece modelos de orientação para:  
  - Aplicativos de envio em massa.  
  - Aplicativos que roteiam emails pelo Exchange.  
  - Aplicativos que usam caixas de correio do Exchange.  
  - Aplicativos que precisam que componentes de terceiros ou personalizados sejam instalados em servidores do Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Planejamento e agrupamento da migração da caixa de correio

- Fornecer orientações para a criação de um plano de migração, incluindo:  
  - Agrupamento de usuários e recursos em lotes.
  - Coordenação da implantação dos pacotes de software necessários com os lotes de migração.   
  - Orientação para criar um plano de comunicação para os usuários finais. 
  - Coordenação do tamanho dos lotes de migração, das taxas de erro e da assistência técnica esperada. 
- Fornecer orientação para o agrupamento de usuários e caixas de correio de recursos em lotes por tipo, função comercial e acesso de delegado com base nas informações relevantes fornecidas pelo cliente.
    
## <a name="skype-for-business-online"></a>Skype for Business online

- Fornecer orientação sobre como migrar usuários em lotes em uma implantação híbrida do Skype for Business (mantendo as listas de contatos dos usuários).
    
## <a name="microsoft-365-apps"></a>Microsoft 365 Apps

- Fornecer orientação e assistência para:  
  - Avaliação e planejamento voltados para implantação inicial e gerenciamento de atualizações de acordo com as práticas recomendadas da Microsoft.
  - Habilitação do uso do Readiness Toolkit for Office para identificar possíveis problemas de compatibilidade com as macros e os suplementos do Microsoft VBA que você usa com o Office.
  
## <a name="your-responsibilities"></a>Suas responsabilidades

Você tem as responsabilidades a seguir durante a integração. Elas são adicionais às responsabilidades definidas na seção [Suas Responsabilidades](O365-your-responsibilities.md). 
  
- Atribuir e gerenciar recursos de acordo com o plano do projeto.  
- Agir em tempo hábil para amenizar riscos e resolver problemas indicados pelo cliente, pelos gerentes de projeto do parceiro e o Gerente do FastTrack.   
- Examinar os relatórios de status e tomar as medidas necessárias.   
- Atribuir um patrocinador ou líder operacional com autoridade para tomar decisões para liderar o comitê de direcionamento.  
- Atribuir um patrocinador executivo para trabalhar com o patrocinador executivo da Microsoft.  
- Estabelecer uma reunião mensal do comitê de direcionamento.

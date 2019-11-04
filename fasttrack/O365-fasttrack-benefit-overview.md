---
title: Visão geral dos Benefícios do Centro FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Com os Benefícios do Centro FastTrack para Office 365, você trabalha remotamente com Especialistas do FastTrack para deixar seu ambiente do Office 365 pronto para uso e planeja a implantação e o uso em sua organização. Para saber mais sobre a qualificação, confira Benefícios do Centro FastTrack para Office 365.
ms.openlocfilehash: ae92d6dc3984f0de2c64b4a7545c09df18fcbb8b
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921493"
---
# <a name="fasttrack-center-benefit-overview"></a>Visão geral dos Benefícios do Centro FastTrack

Com os Benefícios do Centro FastTrack para Office 365, você trabalha remotamente com Especialistas do FastTrack para deixar seu ambiente do Office 365 pronto para uso e planeja a implantação e o uso em sua organização. Para saber mais sobre a qualificação, confira [Benefícios do Centro FastTrack para Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Falamos sobre os seguintes tópicos:
- [O processo FastTrack](O365-fasttrack-process.md) 
- [Expectativas do ambiente de origem](O365-source-environment-expectations.md)
- [Fases de integração e migração](O365-onboarding-and-migration.md)
- [Migração de dados](O365-data-migration.md)
- [Responsibilities do FastTrack](O365-fasttrack-responsibilities.md)
- [Suas responsabilidades](O365-your-responsibilities.md) 
- [Apêndice A: Migração do IBM Domino para o Exchange Online](O365-from-ibm-domino-to-exchange-online.md)
- [Apêndice B: Benefício adicional do Centro do FastTrack](O365-fasttrack-additional-benefits.md)
- [Apêndice C: Acordo de Parceiro Comercial HIPAA do Centro FastTrack](O365-hipaa-business-associate-agreement.md)
- [Apêndice D: Visão geral dos Benefícios do Centro FastTrack do Office 365 US Government](US-Gov-appendix-overview.md)
    
Seu locatário do Office 365 é criado quando a integração estiver concluída. Os usuários licenciados podem acessar o Office 365 usando uma das seguintes opções de identidade:
- Identidades de nuvem com contas exclusivas do Office 365.
- Identidades sincronizadas com as contas do Office 365 sincronizadas de seu Active Directory local com o Azure Active Directory Connect (sincronização de Hash de senha ou autenticação de passagem). Existem para clientes com:
  - Um ambiente de única floresta do Active Directory.
  - Topologia de várias florestas do Active Directory com suporte. Para ver as topologias com suporte, confira [Source Environment Expectations](O365-source-environment-expectations.md).
- Identidades Federadas com contas do Office 365 que são:
  - Sincronizadas a partir do Active Directory com a ferramenta Azure Active Directory Connect para clientes com:
      - Uma configuração de floresta única do Active Directory.
      - Uma única floresta de conta do Active Directory (também conhecida como "floresta de logon") e uma única configuração de floresta de recursos do Active Directory.
  - Configurada com uma infraestrutura dos Serviços de Federação do Active Directory (AD FS) local que é:
      - Federada com a função do AD FS Windows Server 2012 R2 ou posterior de seu Active Directory local.
      - Quando for necessário, uma função Windows Application Proxy (WAP) do Windows Server 2012 R2 em diante é usada para publicar sua infraestrutura do AD FS local na internet.
    > [!NOTE]
    > A implantação e configuração do AD FS e do WAP são feitas usando o [Assistente de configuração do Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) a partir de seu ambiente local. 
  
- Os usuários licenciados agora podem acessar [Serviços e planos qualificados](M365-eligible-services-and-plans.md).
    

 

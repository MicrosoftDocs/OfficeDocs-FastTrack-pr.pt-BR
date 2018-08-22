---
title: Visão geral dos Benefícios do Centro FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 8/2/18
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Com os Benefícios do Centro FastTrack para Office 365, você trabalha remotamente com Especialistas do FastTrack para deixar seu ambiente do Office 365 pronto para uso e planeja a implantação e o uso em sua organização. Para saber mais sobre a qualificação, confira Benefícios do Centro FastTrack para Office 365.
ms.openlocfilehash: 4b54fd05314f9eac96b6f3781e14e988e1282c6c
ms.sourcegitcommit: 7865f572bf312a6ec49f72981d983c6370f34b11
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/10/2018
ms.locfileid: "22449045"
---
# <a name="fasttrack-center-benefit-overview"></a>Visão geral dos Benefícios do Centro FastTrack

Com os Benefícios do Centro FastTrack para Office 365, você trabalha remotamente com Especialistas do FastTrack para deixar seu ambiente do Office 365 pronto para uso e planeja a implantação e o uso em sua organização. Para saber mais sobre a qualificação, confira [Benefícios do Centro FastTrack para Office 365](fasttrack-benefit-for-office-365.md).
  
Falamos sobre os seguintes tópicos:
  
- [O processo FastTrack](fasttrack-process.md)
    
- [Expectativas do ambiente de origem](source-environment-expectations.md)
    
- [Fases de integração e migração](onboarding-and-migration.md)
    
- [Migração de dados](data-migration.md)
    
- [Responsibilities do FastTrack](fasttrack-responsibilities.md)
    
- [Suas responsabilidades](your-responsibilities.md)
    
- [Apêndice A: Migração do IBM Domino para o Exchange Online](from-ibm-domino-to-exchange-online.md)
    
- [Apêndice B: Benefício adicional do Centro do FastTrack](fasttrack-additional-benefits.md)
    
Seu locatário do Office 365 é criado quando a integração estiver concluída. Os usuários licenciados podem acessar o Office 365 usando uma das seguintes opções de identidade:
  
- Identidades de nuvem com contas exclusivas do Office 365.
    
- Identidades sincronizadas com as contas do Office 365 sincronizadas de seu Active Directory local com o Azure Active Directory Connect (sincronização de Hash de senha ou autenticação de passagem). Existem para clientes com:
    
  - Um ambiente de única floresta do Active Directory.
    
  - Topologia de várias florestas do Active Directory com suporte. Para ver as topologias com suporte, confira [Source Environment Expectations](source-environment-expectations.md).
    
- Identidades Federadas com contas do Office 365 que são:
    
  - Sincronizadas a partir do Active Directory com a ferramenta Azure Active Directory Connect para clientes com:
    
      - Uma configuração de floresta única do Active Directory.
    
      - Uma única floresta de conta do Active Directory (também conhecida como "floresta de logon") e uma única configuração de floresta de recursos do Active Directory.
    
  - Configurada com uma infraestrutura dos Serviços de Federação do Active Directory (AD FS) local que é:
    
      - Federada com a função do AD FS Windows Server 2012 R2 ou posterior de seu Active Directory local.
    
      - Quando for necessário, uma função Windows Application Proxy (WAP) do Windows Server 2012 R2 em diante é usada para publicar sua infraestrutura do AD FS local na internet.
    
    > [!NOTE]
    > A implantação e configuração do AD FS e do WAP são feitas usando o [Assistente de configuração do Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) a partir de seu ambiente local. 
  
- Os usuários licenciados agora podem acessar [Serviços e planos qualificados](eligible-services-and-plans.md).
    

 

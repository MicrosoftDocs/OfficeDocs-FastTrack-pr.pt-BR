---
title: Visão geral dos Benefícios do Centro FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011329"
---
# <a name="fasttrack-center-benefit-overview"></a>Visão geral dos Benefícios do Centro FastTrack

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Falamos sobre os seguintes tópicos:
- [O processo FastTrack](O365-fasttrack-process.md) 
- [Expectativas do ambiente de origem](O365-source-environment-expectations.md)
- [Fases de integração e migração](O365-onboarding-and-migration.md)
- [Migração de dados](O365-data-migration.md)
- [Responsibilities do FastTrack](O365-fasttrack-responsibilities.md)
- [Suas responsabilidades](O365-your-responsibilities.md) 
- [Apêndice A: benefício adicional do Centro FastTrack](O365-fasttrack-additional-benefits.md)
- [Apêndice B: acordo de Parceiro Comercial HIPAA do Centro FastTrack](O365-hipaa-business-associate-agreement.md)
- [Apêndice C: visão geral dos benefícios do Centro FastTrack do Office 365 US Government](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- Identidades de nuvem com contas exclusivas do Office 365.
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - Um ambiente de única floresta do Active Directory.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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


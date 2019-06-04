---
title: Processo FastTrack
description: Visão geral do processo de integração de Benefício do Centro do FastTrack
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 06/04/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0b24a3d1b339836fb07137a7ad2138f85ed7709b
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673242"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Processo de Benefício do Centro do FastTrack para o Enterprise Mobility + Security (EMS)
Se sua organização está qualificada para o Centro de Benefício do FastTrack para EMS, você pode trabalhar remotamente com Especialistas do FastTrack para obter o Microsoft Azure Active Directory Premium, o Microsoft Intune e a Proteção de Informações do Azure prontos para uso. Você também pode solicitar ajuda por meio do [site FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) para Proteção de Informações do Azure, Microsoft Cloud App Security e Microsoft Advanced Threat Analytics. Para saber se sua organização está qualificada, consulte [Serviços e Planos Elegíveis](M365-eligible-services-and-plans.md).


Veja aqui o que abordamos sobre o processo de integração:

-   [Visão geral do processo de integração](EMS-fasttrack-benefit-overview.md)

-   [Expectativas para o ambiente de origem](EMS-source-environment-expectations.md)

-   [Fases do processo de Integração](EMS-onboarding-phases.md)

-   [Responsabilidades do FastTrack](EMS-fasttrack-responsibilities.md) para cada fase

-   [Responsabilidades do Cliente](EMS-your-responsibilities.md) para cada fase

Veja a seguir o que você pode esperar quando a integração for concluída:

-   Os locatários de EMS dos serviços selecionados são criados.

-   Os usuários licenciados podem acessar os Serviços EMS usando uma das seguintes opções de identidade:

    -   Identidades de Nuvem (contas exclusivas do EMS).

    -   Identidades Sincronizadas: As contas do EMS sincronizadas do Active Directory local com a ferramenta Azure Active Directory Connect (Sincronização de Hash de Senha ou Autenticação de Passagem). Essa opção destina-se aos clientes com uma única ou várias florestas do Active Directory.

    -   Identidades Federadas com contas Microsoft EMS, que são:

        -   Sincronizado do Active Directory com a ferramenta Azure AD Connect. Essa opção destina-se aos clientes com uma única configuração de floresta do Active Directory.

        -   Federado com os Serviços de Federação do Active Directory (AD FS) 2.0 do Windows Server 2012 R2 ou posteriores no Active Directory local.

        -   Capacidade de classificar automaticamente e proteger informações em repouso e em trânsito com a Proteção de Informações do Azure. 

        -   Capacidade de descobrir informações em compartilhamentos de arquivos locais e servidores do SharePoint com o scanner de Proteção de Informações do Azure. 

        -   Capacidade de gerenciar as chaves do locatário de Proteção de Informações do Azure no Azure Key Vault. 

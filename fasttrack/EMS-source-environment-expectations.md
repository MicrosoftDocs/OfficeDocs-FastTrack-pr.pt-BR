---
title: Expectativas do ambiente de origem
description: Requisitos do ambiente de origem para o uso dos Benefícios do Centro do FastTrack para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 5/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: edb877cad106fd8073524c9082e2491943eed66a
ms.sourcegitcommit: 2775660fc5ccab2e92aee9383e326dba22b7a16b
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/01/2020
ms.locfileid: "43999649"
---
# <a name="source-environment-expectations"></a>Expectativas do Ambiente de Origem

Ao usar os [Benefícios do Centro do FastTrack para Enterprise Mobility + Security (EMS) ](EMS-fasttrack-benefit-for-EMS.md), para que o Microsoft Azure Active Directory Premium, o Microsoft Intune e a Proteção de Informações do Azure estejam prontos para uso, seu ambiente precisa atender às expectativas descritas nas seções a seguir.

Talvez você já tenha o Active Directory local em sua organização que deseja integrar com o Enterprise Mobility + Security (EMS) ou qualquer um de seus serviços individuais que usem o gerenciamento avançado de identidades de um único console. Os Benefícios do Centro do FastTrack para o Enterprise Mobility + Security (EMS) inclui ajudar a integrar o Azure Active Directory ao seu ambiente local existente do Active Directory.

A tabela a seguir mostra o que o seu ambiente de origem deverá conter para a integração.

|Atividade|Expectativa de ambiente de origem|
|------------|----------------------------------|
|Integração do núcleo|Florestas do Active Directory com o nível funcional de floresta definido como o Windows Server 2008 ou superior, com a seguinte configuração de floresta:<br /><br />– Única floresta do Active Directory.<br />– Várias florestas do Active Directory. </br></br>**Observação**: Para todas as configurações de várias florestas, a implantação do Serviço de Federação do Active Directory (AD FS) está fora do escopo do Benefício do Centro FastTrack.|
|Integração do Azure AD Premium|O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, que inclui a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.|
|Integração do Intune| Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, WiFi e VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis WiFi e VPN com o Intune.<br /><br /> **Observação**: o benefício de serviço não inclui assistência para instalar ou configurar Autoridades de Certificação, WiFi, infraestruturas de VPN ou certificados enviados por push de MDM da Apple    |
|Vincular Configuration Manager à nuvem com Intune|Com a vinculação à nuvem, os administradores de TI são responsáveis por preparar o ambiente local, o que pode incluir a correção de problemas que impedem a vinculação dos ambientes do Configuration Manager à nuvem com Intune.<br /><br />**Observação**: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem. |
|Intune integrado à Proteção Avançada contra Ameaças (ATP) do Microsoft Defender|**Observação**: O benefício do serviço FastTrack fornece assistência na integração do Intune à ATP do Microsoft Defender e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10. O benefício do serviço não fornece assistência na compra, licenciamento ou ativação. |
|Windows Autopilot|Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot. |
|Implantar o Outlook para iOS e Android de forma segura com o Intune|<br /><br />– Identidades dos usuários habilitadas no Azure Active Directory para Office 365.<br />– Exchange Online ou Exchange Híbrido configurado com licenças de usuário atribuídas.<br />|
|Proteção de Informações do Azure (P2 ou EMS E5)|<br /><br />Os usuários já devem saber: <br /> – Usar o Azure AD.<br />– Usar o Windows ou o iOS (outros SOs estão fora do escopo).<br /> – Usar clientes do Office mais recentes que o Office 2010 SP2 que não dependam do Office como cliente principal. <br /> – Ter seus principais locais de compartilhamento de arquivos.  <br /> – Ter atualizado a partir de Active Directory Rights Management Services (AD RMS). <br /> – Ter uma taxonomia de classificação aprovada. <br /> – Entender as restrições normativas para o gerenciamento de chaves protegidas. <br />|
|Scanner da Proteção de Informações do Azure|<br /><br /> Os usuários já devem saber: <br /> Usar Windows Server 2012 R2 ou Windows Server 2016.<br /> – Ter uma conexão de Internet. <br /> – Ter o Microsoft SQL Server 2012 em uma instância local ou remota.  <br /> – Ter uma conta de serviço criada para o Active Directory local e sincronizada com o Azure AD.  <br /> – Ter baixado AzInfoProtection.exe. <br /> – Ter etiquetas configuradas para Classificação/Proteção Automática.<br />|

> [!NOTE]
> **Quer saber mais?**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Próximas etapas

[Benefícios do Centro do FastTrack para as fases de integração EMS](EMS-onboarding-phases.md)


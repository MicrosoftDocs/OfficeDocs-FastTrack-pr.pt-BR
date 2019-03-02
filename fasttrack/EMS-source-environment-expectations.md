---
title: Expectativas do ambiente de origem
description: Requisitos de ambiente de origem para usar o benefício do FastTrack Center para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359979"
---
# <a name="source-environment-expectations"></a>Expectativas do ambiente de origem

Quando você usa o [FastTrack Center Benefit for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) para obter o Microsoft Azure Active Directory Premium e o Microsoft Intune prontos para uso, seu ambiente precisa atender às expectativas descritas nas seções a seguir.

Talvez você já tenha o Active Directory local em sua organização que você deseja integrar com o Enterprise Mobility + Security (EMS) ou qualquer um de seus serviços individuais que usem o gerenciamento de identidade avançado de um único console. O FastTrack Center Benefit for Enterprise Mobility + Security (EMS) inclui ajudá-lo a integrar o Azure Active Directory ao seu ambiente local do Active Directory.

A tabela a seguir mostra as expectativas para seu ambiente de origem existente para a integração.

|Atividade|Expectativa de ambiente de origem|
|------------|----------------------------------|
|Integração principal|Florestas do Active Directory com o nível de floresta funcional definido como Windows Server 2008 ou superior, com a seguinte configuração de floresta:<br /><br />-Floresta única do Active Directory<br />– Várias florestas do Active Directory </br></br>**Observação**: para todas as configurações de várias florestas, a implantação do AD FS (serviços de Federação do Active Directory) está fora do escopo do benefício do centro FastTrack.|
|Integração do Azure AD Premium|O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, que inclui a correção de problemas identificados que impedem a integração com o Azure AD e recursos do Azure AD Premium.|
|Integração do Intune| Os administradores de ti precisam ter as infra-estruturas de autoridade de certificação, WiFi e VPN existentes já funcionando em seus ambientes de produção ao planejar a implantação de perfis WiFi e VPN com o Intune.<br /><br /> **Observação**: o benefício do serviço não inclui assistência para configurar ou configurar autoridades de certificação, WiFi, infraestruturas VPN ou certificados de push do Apple MDM para  |
|Gerenciamento de Cogestão|Com o outmanagement, os administradores de ti são responsáveis por preparar o ambiente local, que pode incluir a correção de problemas que impedem o gerenciamento simultâneo de dispositivos Windows 10 usando o Configuration Manager e o Intune.<br /><br />**Observação**: o benefício do serviço FastTrack não inclui assistência para configurar ou atualizar o servidor de site do Configuration Manager e/ou o cliente do Configuration Manager para os requisitos mínimos necessários para dar suporte ao cogerenciamento com dispositivos Windows 10. |
|Intune integrado com a proteção avançada contra ameaças do Windows Defender (Windows Defender ATP)|Sua assinatura ATP do Windows Defender foi ativada e configurada com base nos requisitos de segurança de sua empresa.<br /><br />**Observação**: o benefício do serviço FastTrack fornece assistência sobre a integração do Intune com o Windows Defender ATP e a criação de políticas de conformidade do dispositivo com base em sua avaliação do nível de risco do Windows 10. O benefício do serviço FastTrack não fornece assistência na compra, licenciamento, ativação ou uso do Windows Defender ATP e do console da central de segurança. |
|Windows Autopilot|Os administradores de ti são responsáveis por registrar seus dispositivos em sua organização, fazendo com que o fornecedor do hardware carregue suas IDs de hardware em seu nome ou carregando-o por conta própria no serviço do Windows AutoPilot. |
|Implantar o Outlook para iOS e Android com segurança com o Intune|<br /><br />-Identidades do usuário habilitadas no Azure AD para Office 365.<br />– Exchange Online ou Hybrid Exchange configurados com licenças de usuário atribuídas.<br />|

> [!NOTE]
> **Quer saber mais?** 
>  [Mobilidade corporativa + segurança](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Próximas etapas

[Benefício do FastTrack Center para fases de integração EMS](EMS-onboarding-phases.md)

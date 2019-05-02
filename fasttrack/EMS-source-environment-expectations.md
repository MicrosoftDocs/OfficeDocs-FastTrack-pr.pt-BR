---
title: Expectativas do ambiente de origem
description: Requisitos de ambiente de origem para usar o benefício do FastTrack Center para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513146"
---
# <a name="source-environment-expectations"></a>Expectativas do ambiente de origem

Ao usar o [FastTrack Center Benefit for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) para obter o Microsoft Azure Active Directory Premium, o Microsoft Intune e a proteção de informações do Azure prontos para uso, seu ambiente precisa atender às expectativas descrito nas seções a seguir.

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
|Proteção de informações do Azure (P2 ou EMS E5)|<br /><br />Os clientes já devem: <br /> – Use o Azure AD.<br />– Use o Windows ou o iOS (outros SOS estão fora do escopo).<br /> – Use clientes do Office mais recentes do que o Office 2010 SP2 que não se baseia no Office Online como o cliente principal. <br /> – Ter seus locais de compartilhamento de arquivos principais.  <br /> -Atualize o Active Directory Rights Management Services (AD RMS). <br /> – Ter uma taxonomia de classificação aprovada. <br /> – Entenda quaisquer restrições de regulamentação para o gerenciamento de chaves protegido. <br />|
|Verificador de proteção de informações do Azure|<br /><br /> Os clientes já devem: <br /> – Use o Windows Server 2012 R2 ou o Windows Server 2016.<br /> – Ter uma conexão com a Internet. <br /> – Tenha o Microsoft SQL Server 2012 em uma instância local ou remota.  <br /> – Tenha uma conta de serviço criada para seu Active Directory local e sincronizada com o Azure AD.  <br /> – Tenha baixado o AzInfoProtection. exe. <br /> – Tenha rótulos configurados para classificação/proteção automática.<br />|

> [!NOTE]
> **Quer saber mais?** 
>  [Mobilidade corporativa + segurança](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Próximas etapas

[Benefício do FastTrack Center para fases de integração EMS](EMS-onboarding-phases.md)

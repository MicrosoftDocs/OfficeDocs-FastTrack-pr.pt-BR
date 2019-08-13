---
title: Fases da Integração
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/13/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'A integração do Windows 10 tem quatro fases principais: Iniciar, Avaliar, Corrigir e Habilitar.'
ms.openlocfilehash: 0789cb80e25a085d2d631d6032b5c7663bd1b8c2
ms.sourcegitcommit: d469f9b0dfa7f39fde051c38f255d6f5790f62f5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/12/2019
ms.locfileid: "36294357"
---
# <a name="onboarding-phases"></a>Fases da Integração

A integração do Windows 10 tem quatro fases principais: Iniciar, Avaliar, Corrigir e Habilitar.

## <a name="initiate"></a>Iniciar

Durante esta fase, discutimos o processo de integração, verificamos dados e agendamos uma reunião de apresentação. Isso inclui trabalhar com você para compreender sua intenção do Windows 10.

## <a name="assess"></a>Avaliar

Os especialistas do FastTrack trabalham com você para avaliar o ambiente de origem e os requisitos. Certifique-se de que o System Center Configuration Manager esteja atualizado para o nível necessário para dar suporte à implantação do Windows 10. 

Fornecemos opções recomendadas para você avaliar os aplicativos do Windows 10. O FastTrack fornece orientação para habilitar o uso do Desktop Analytics e orienta você durante a criação de um plano de implantação do Desktop Analytics.

O FastTrack também pode guiar a sua avaliação de compatibilidade do Office 365 ProPlus aproveitando o painel de preparação do Office 365 no Configuration Manager ou com o Readiness Toolkit autônomo para o Office. Para obter mais informações sobre serviços disponíveis, confira [Benefícios do Centro FastTrack para o Office 365](O365-fasttrack-benefit-for-office-365.md). 

## <a name="remediate"></a>Corrigir

Você realiza as tarefas de correção com base em seu ambiente de origem para atender aos requisitos de integração. Fornecemos uma lista de verificação de correção para preparar seu ambiente e validar se esses elementos estão em vigor para adequar seu ambiente de origem aos requisitos mínimos para uma implantação bem-sucedida. 

## <a name="enable"></a>Habilitar

O FastTrack fornece diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários. As diretrizes de atualização são fornecidas para dar suporte ao seu movimento de implantação existente. O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10. As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot). 

Fornecemos diretrizes para implantar o Office 365 ProPlus usando o Configuration Manager como parte da implantação do Windows 10. Confira [Office 365 ProPlus](O365-onboarding-and-migration.md#office-365-proplus) para obter mais detalhes sobre serviços associados.

Fornecemos diretrizes para ajudar sua organização a manter-se atualizada com o Windows 10 Enterprise e o Office 365 ProPlus usando seu ambiente existente do Configuration Manager ou o Microsoft 365.

> [!NOTE]
> Se você não tiver um plano ou processo existente para implantação e manutenção, podemos fornecer diretrizes sobre práticas recomendadas com base no cenário de atualização in-loco (recomendado) ou no [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot).

## <a name="out-of-scope"></a>Fora do escopo

O FastTrack não fornece diretrizes para:

- Atualizar o Configuration Manager para o Branch Atual.
- Criar imagens personalizadas para a implantação do Windows 10.
- Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).
- Habilitar os recursos de segurança do Windows 10. 
- Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).
- Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.
- Usar a Ferramenta de Migração de Estado do Usuário (USMT).

  > [!NOTE]
  > Entre em contato um [parceiro da Microsoft](https://go.microsoft.com/fwlink/?linkid=2080150) para fornecer assistência para serviços identificados como fora do escopo.

 
---
title: Área de Trabalho Virtual do Windows
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: O FastTrack fornece Windows diretrizes de implantação da Área de Trabalho Virtual para ajudá-lo a entrar nessa área de trabalho.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592434"
---
# <a name="windows-virtual-desktop"></a>Área de Trabalho Virtual do Windows

<table>
<thead>
<tr class="header">
<th><strong>Serviço</strong></th>
<th><strong>Detalhes da orientação do FastTrack</strong></th>
<th><strong>Expectativas do ambiente de origem</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Área de Trabalho Virtual do Windows</td>
<td><p>O FastTrack fornece Windows diretrizes de implantação da Área de Trabalho Virtual para ajudá-lo a integrar esse serviço de virtualização de aplicativos e área de trabalho com facilidade enquanto aproveita Windows 10 experiência de várias sessões, otimizada para Microsoft 365 Apps para Enterprise com segurança e gerenciamento integrados para Microsoft 365.</p>
<p>Você trabalha com especialistas do FastTrack para:</p>
<ul>
<li><p>Implante o ambiente WVD com Windows 10 Enterprise de várias sessões + Microsoft 365 Apps para Enterprise usando o seguinte:</p>
<ul>
<li><p>Imagem do Azure Marketplace</p></li>
<li><p>Imagem Compartilhada</p></li>
<li><p>Office Implantação Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurar FSLogix</p>
<ul>
<li><p>Implantar agente FSLogix com contêiner de perfil</p></li>
<li><p>Implantar o Agente FSLogix com Office Contêiner</p></li>
<li><p>Configurar pasta FSLogix com exclusões de conteúdo</p></li>
</ul></li>
<li><p>Implantar o Microsoft Edge</p></li>
<li><p>Implantar Microsoft Teams</p></li>
<li><p>Conexão usando Windows de Área de Trabalho Virtual</p></li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li><p>Project gerenciamento da implantação da Área de Trabalho Virtual do cliente Windows.</p></li>
<li><p>Suporte no local.</p></li>
<li><p>Virtualização/implantação de aplicativos de terceiros.</p></li>
<li><p>Imagens personalizadas.</p></li>
<li><p>Migrações e cenários envolvendo VMware e Citrix.</p></li>
<li><p>Cenários do Linux.</p></li>
<li><p>Conversão ou migrações de perfis de usuário.</p></li>
</ul>
<p>Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</p></td>
<td><p>Você já deve ter o seguinte:</p>
<ul>
<li><p>[Requisitos de licenciamento WVD](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Rede do Azure:</p>
<ul>
<li><p>Sub-rede de criação de VNET &amp;</p></li>
<li><p>Grupos de segurança de rede/firewall</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Roteamento para o Azure no local</p></li>
<li><p>Regras de firewall para permitir a conectividade com o WVD</p>
<ul>
<li><p>[Referência de Documentos](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Instalação geral</p>
<ul>
<li><p>Estratégia de <strong>Identidade (Selecione APENAS 1 das 3 opções a seguir)</strong></p>
<ul>
<li><p>Active Directory com o Azure AD Conexão no Azure</p></li>
<li><p>Active Directory com o Azure AD Conexão local sobre VPN/ER</p></li>
<li><p>Serviços de Domínio do Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

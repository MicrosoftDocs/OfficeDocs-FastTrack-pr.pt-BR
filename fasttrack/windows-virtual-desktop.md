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
description: O FastTrack fornece diretrizes de implantação da Área de Trabalho Virtual do Windows para ajudá-lo a entrar nessa área de trabalho.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996229"
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
<td><p>O FastTrack fornece diretrizes de implantação da Área de Trabalho Virtual do Windows para ajudá-lo a integrar esse serviço de virtualização de aplicativos e área de trabalho com facilidade ao aproveitar a experiência de várias sessões do Windows 10, otimizada para o Microsoft 365 Apps for Enterprise com segurança e gerenciamento integrados para o Microsoft 365.</p>
<p>Você trabalha com especialistas do FastTrack para:</p>
<ul>
<li><p>Implantar o ambiente WVD com o Windows 10 Enterprise com várias sessões + Aplicativos do Microsoft 365 para Empresas usando o seguinte:</p>
<ul>
<li><p>Imagem do Azure Marketplace</p></li>
<li><p>Imagem Compartilhada</p></li>
<li><p>Office Deployment Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurar FSLogix</p>
<ul>
<li><p>Implantar agente FSLogix com contêiner de perfil</p></li>
<li><p>Implantar agente FSLogix com contêiner do Office</p></li>
<li><p>Configurar pasta FSLogix com exclusões de conteúdo</p></li>
</ul></li>
<li><p>Implantar o Microsoft Edge</p></li>
<li><p>Implantar o Microsoft Teams</p></li>
<li><p>Conectar-se usando clientes da Área de Trabalho Virtual do Windows</p></li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li><p>Gerenciamento de projetos da implantação da Área de Trabalho Virtual do Cliente.</p></li>
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
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento WVD</a></p></li>
<li><p>Rede do Azure:</p>
<ul>
<li><p>Sub-rede de criação de VNET &amp;</p></li>
<li><p>Grupos de segurança de rede/firewall</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Roteamento para o Azure no local</p></li>
<li><p>Regras de firewall para permitir a conectividade com o WVD</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Referência de Documentos</a></p></li>
</ul></li>
</ul></li>
<li><p>Instalação geral do Azure Active Directory</p>
<ul>
<li><p>Estratégia de <strong>Identidade (Selecione APENAS 1 das 3 opções a seguir)</strong></p>
<ul>
<li><p>Active Directory com o Azure AD Connect no Azure</p></li>
<li><p>Active Directory com o Azure AD Connect On Premise sobre VPN/ER</p></li>
<li><p>Serviços de Domínio do Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

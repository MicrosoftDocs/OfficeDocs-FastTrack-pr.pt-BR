---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: 7071187e2bc2b52930a03b4bf9dabd4f717b88df
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827101"
---
# <a name="products-and-capabilities"></a>Produtos e Recursos

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Serviços e cenários com suportados pelo FastTrack

Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.

O FastTrack fornece orientações para ajudá-lo primeiro com os principais recursos (comuns para todos os serviços online da Microsoft) e, em seguida, com a integração de cada serviço qualificado:

  - [Geral](#general)
  - [Office 365](#office-365)
  - [Enterprise Mobility & Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Área de Trabalho Virtual do Windows](#windows-virtual-desktop)
  - [Garantia do Aplicativo](#app-assure)
  - [O novo Microsoft Edge](#the-new-microsoft-edge)

> [!NOTE]
> Para saber mais sobre as expectativas de ambiente de origem para o Office 365 US Government, confira [Expectativas de Ambiente de Origem para o Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
## <a name="general"></a>Geral

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
<td><strong>Integração principal</strong></td>
<td>  Fornecemos orientação remota sobre a integração principal, que envolve o provisionamento do serviço, a integração de identidade e locatário. Isso também inclui etapas para fornecer uma base de integração de serviços como o Exchange Online, o SharePoint Online e o Microsoft Teams, incluindo uma discussão <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">sobre segurança, conectividade de rede e conformidade</a>.  
  A integração de um ou mais serviços qualificados poderá começar quando a integração básica estiver concluída.
</li>
</ul>  

<strong>Integração de identidade</strong>

Fornecemos orientações remotas para:
<ul>
<li>Preparar as identidades locais do Active Directory para sincronização com o Azure Active Directory (Azure AD), incluindo instalar e configurar o Azure AD Connect (com uma única ou várias florestas) e licenciamento (incluindo o licenciamento baseado em grupo).</li>
<li>Criar identidades de nuvem, incluindo importação em massa e licenciamento, incluindo o uso de licenciamento baseado em grupo.</li>
<li>Escolher e habilitar o método de autenticação correto para o seu percurso na nuvem, a sincronização de hash de senha, a autenticação de passagem ou o AD FS (Serviços de Federação do Active Directory).</li>
<li>Habilitar o AD FS para clientes com uma única floresta do Active Directory e identidades sincronizadas com a ferramenta Azure AD Connect. Isso exige os Serviços de Federação do Active Directory do Windows Server 2012 R2 versão 2.0 ou posterior.</li>
<li>Migrar a autenticação do AD FS para o Azure AD usando a sincronização de hash de senha ou a autenticação de passagem.</li>
<li>Migrar aplicativos pré-integrados (como a galeria de aplicativos de software como serviço (SaaS) do Azure AD) do AD FS para o Azure AD para logon único (SSO).</li>
<li>Habilitar integrações de aplicativos SaaS com o SSO da galeria do Azure AD.</li>
<li>Habilitar o provisionamento automático do usuário para aplicativos SaaS pré-integrados, como listados na <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Lista de tutoriais de integração de aplicativos</a>, (limitado apenas ao provisionamento de saída e de aplicativos SaaS da galeria do Azure AD).  </li>
</td>

<td>  <strong>Habilitação de rede </strong>  
  <br>Como parte do serviço de benefícios do FastTrack, aconselhamos você a obter as melhores maneiras de se conectar aos serviços na nuvem para garantir os mais altos níveis de desempenho do Microsoft 365.  
  
<strong>Florestas do Active Directory</strong> Essas possuem um nível funcional de floresta definido para o Windows Server 2003 ou superior, com a seguinte configuração de floresta:
<ul>
<li>  Uma única floresta do Active Directory.  </li>
<li>  Topologias de uma única floresta de conta do Active Directory e de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).  </li>
<li>  Topologias de várias florestas de contas do Active Directory ou de uma floresta de recursos (Exchange e/ou Lync 2010, Lync 2013 ou Skype for Business).  </li>
<li>  Várias florestas de contas do Active Directory com uma das florestas sendo uma floresta de conta do Active Directory centralizada que inclui o Exchange e/ou o Lync 2010, o Lync 2013 ou o Skype for Business.  </li>
<li>  Várias florestas de conta do Active Directory, cada uma com sua própria organização do Exchange.  </li>
<li>  Tarefas necessárias para configuração de locatário e integração ao Azure Active Directory, caso seja necessário.   </li>
</ul>
  <strong>Importante:</strong>  <ul>
<li>  Para cenários de várias florestas do Active Directory, caso o Lync 2010, o Lync 2013 ou o Skype for Business esteja implantado, ele deverá ser implantado na mesma floresta do Active Directory como o Exchange.  </li>
<li>  Ao implementar diversas florestas do Active Directory com várias organizações do Exchange em uma configuração multi-híbrida do Exchange, namespaces de UPN (nome UPN) compartilhados entre florestas de origem não são compatíveis. Namespaces SMTP primários entre organizações do Exchange também devem ser separados. Confira mais informações em <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implantações híbridas com várias florestas do Active Directory</a>.  </li>
<li>  Para todas as configurações de várias florestas, a implantação dos Serviços de Federação do Active Directory (AD FS) está fora do escopo. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Fornecemos orientações de implantação remotas para:
<ul>
<li>  Solução de problemas de implantação.  </li>
<li>  Atribuição de licenças baseadas em dispositivos e usuários finais usando o Centro de administração do Microsoft 365 e o Windows PowerShell.  </li>
<li>  Instalação de Aplicativos do Microsoft 365 pelo portal do Office 365 usando Clique para Executar.  </li>
<li>  Instalar os aplicativos do Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) em dispositivos iOS ou Android.  </li>
<li>  Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.  </li>
<li>  Seleção e configuração de uma instalação local ou na nuvem.  </li>
<li>  Criação do XML de configuração da Ferramenta de Implantação do Office com a Ferramenta de Personalização do Office ou XML nativo para configurar o pacote de implantação.  </li>
<li>  Implantação usando o Gerenciador de Configurações do Microsoft Endpoint, incluindo assistência na criação de pacotes do Gerenciador de Configurações do Microsoft Endpoint.  
  Além disso, se você tiver uma macro ou suplemento que funcionou com versões anteriores do Office e tiver problemas de compatibilidade, forneceremos orientação para corrigir esses problemas sem custos adicionais, por meio do programa de Garantia de Aplicativo. Confira a parte da <strong>Garantia de Aplicativo</strong> do <a href="#windows-10">Windows 10</a> para obter mais detalhes. </li>
</ul></td>
<td><ul>
<li>  O software cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Integridade da rede</strong></td>
<td>  Fornecemos uma orientação remota com a obtenção e interpretação dos principais dados de conectividade de rede do seu ambiente, mostrando o quão os sites da sua organização se alinham aos <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">princípios de conectividade de rede da Microsoft</a>. Isso destaca a pontuação de desempenho da rede, o que afeta diretamente a velocidade de migração, a experiência do usuário, o desempenho e a confiabilidade do serviço.  
  Também guiamos você pelas etapas de resolução destacadas por esses dados para ajudá-lo a melhorar a pontuação da rede.  </td>
<td><ul>
<li>  Acesso ao Centro de administração do Microsoft 365.  </li>
<li>  São necessárias versões atualizadas dos aplicativos do Microsoft 365.  </li>
<li>  Serviços de localização habilitados conforme as <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">recomendações de desempenho de rede no Centro de administração do Microsoft 365</a>.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

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
<td><strong>Exchange Online</strong></td>
<td>  Para o Exchange Online, guiamos você pelo processo de preparar a sua organização para usar o email. As etapas exatas variam de acordo com o ambiente de origem e os planos de migração de email.  
  Fornecemos orientações remotas para:
<ul>
<li>  Configurar os recursos do EOP (Proteção do Exchange Online) para todos os domínios habilitados para email validados no Office 365.  </li>
<li>  Apontar seus registros de troca de mensagens (MX) para o Office 365.  </li>
<li>  Configurar o recurso do Office 365 ATP se ele fizer parte do seu serviço de assinatura. Para mais informações, veja a parte dessa tabela <strong>Proteção Avançada contra Ameaças do Office 365</strong>.  </li>
<li>  Configurar o recurso de DLP (prevenção contra perda de dados) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </li>
<li>  Configurar o recurso de OME (Criptografia de Mensagens do Office 365) para todos os domínios habilitados para email validados no Office 365 como parte do serviço de assinatura. Isso é feito quando seus registros MX apontam para o Office 365.  </li>
</ul>
  <strong>Observação:</strong>O serviço de Replicação de Caixa de Correio (MRS) tenta migrar os emails do Gerenciamento de Direitos de Informação (IRM) da caixa de correio local para a caixa de correio correspondente do Exchange Online. A capacidade de ler o conteúdo protegido após a migração depende dos modelos de mapeamento e cópia do cliente dos Serviços Gerenciados por Direitos do Active Directory (AD RMS) para o Serviço de Gerenciamento de Direitos do Azure (Azure RMS).  
<ul>
<li>  Configurar portas do firewall.  </li>
<li>  Configurar o DNS, incluindo a Descoberta Automática necessária, a Sender Policy Framework (SPF), a DomainKeys Identified Mail (DKIM), a autenticação de mensagem baseada em domínio, os Relatórios e Conformidade (DMARC) e os registros MX (conforme necessário).  </li>
<li>  Configurando o fluxo de email entre seu ambiente de mensagens de origem e o Exchange Online (conforme a necessidade).  </li>
<li>  Fornecer orientações para a migração de email do ambiente de mensagens de origem para o Office 365.  </li>
<li>  Configuração de clientes de caixa de correio (Outlook para Windows, Outlook na web e Outlook para iOS e Android).  </li>
</ul>
  <strong>Migração de dados</strong>  <br>
Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.   
<td>  Seu ambiente de origem deve ter um dos seguintes níveis mínimos:
<ul>
<li>  Uma ou várias organizações do Exchange com o Exchange Server 2003 e posteriores.  </li>
<li>  Um único ambiente de email compatível com o protocolo IMAP.  </li>
<li>  Um único ambiente do G Suite (apenas Gmail, Contatos e Calendário).  </li>
<li>  Para saber mais sobre Multi-Geo Capabilities, confira <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities no Exchange Online</a>.  </li>
</ul>
Software cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, o cliente de sincronização do OneDrive for Business, o Power BI desktop e o Skype for Business devem estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos de sistema do Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Governança de informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Governança de Informações.  </li>
<li>  Rótulos e diretivas de retenção.  </li>
<li>  Gerenciamento de registros.  </li>
<li>  Diretivas de exclusão.  </li>
<li>  Conformidade da comunicação.  </li>
<li>  Gerenciamento de risco interno.  </li>
<li>  Descoberta Eletrônica Avançada.  </li>
</ul></td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="odd">
<td><strong>Proteção de Informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Classificação de dados.  </li>
<li>  Tipos de informações confidenciais.  </li>
<li>  Criação de rótulos de confidencialidade.  </li>
<li>  Aplicação de rótulos de confidencialidade.  </li>
<li>  Rotulagem unificada.  </li>
<li>  Classificadores treináveis.  </li>
<li>  Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.  </li>
<li>  Publicar etiquetas usando políticas (manual e automática).  </li>
<li>  Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.  </li>
<li>  Criação de políticas DLP para dispositivos gerenciados pelo Microsoft Endpoint Manager.  </li>
</ul></td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Confirmar requisitos mínimos no Exchange Online, no SharePoint Online, nos Grupos do Office 365 e no Azure AD para oferecer suporte ao Teams.  </li>
<li>  Configurar portas do firewall.  </li>
<li>  Configuração do DNS.  </li>
<li>  Confirmação da habilitação do Teams no seu locatário do Office 365.  </li>
<li>  Habilitação ou desabilitação de licenças de usuário.  </li>
<li>  Avaliação Rede para o Teams:
<ul>
<li>  Verificações de porta e de ponto de extremidade.  </li>
<li>  Verificações de qualidade da conexão.  </li>
<li>  Estimativas de largura de banda.  </li>
</ul>
<ul>
<li>  Configurar a política de aplicativos do Teams (aplicativo Web do Teams, aplicativo de área de trabalho do Teams e aplicativo do Teams para iOS e Android).  </li>
</ul>
Se aplicável, também forneceremos diretrizes para:
<ul>
<li>  Dispositivos para a Sala do Microsoft Teams:  </li>
<ul>
<li>  Criação de contas online necessárias para os dispositivos de sala de conferências e de telefonia com suporte listados no <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catálogo de dispositivos do Teams</a>.  </li>
<li>  Assistência remota com a configuração do lado do serviço de dispositivos de salas certificadas do Microsoft Teams.  </li>
<li>  Habilitar a Audioconferência:  </li>
<li>  Configuração da organização para as configurações padrão da ponte de conferência.  </li>
<li>  Atribuição da ponte de conferência para usuários licenciados.  </li>
</ul>
<li>  Sistema de Telefonia:
<ul>
<li>  Configuração da organização para as configurações padrão do Cloud Voice.  </li>
<li>  Diretrizes de planos de chamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponíveis</a>):
<ul>
<li>  Atribuição de números a usuários licenciados.  </li>
<li>  Orientação de portabilidade do número local pela IU (interface do usuário) até 999.  </li>
<li>  Suporte SR (solicitação de serviço) à portabilidade do número local superior a 999.  </li>
</ul></li>
<li>  Diretrizes de Roteamento Direto:
<ul>
<li>  Orientação de configuração da organização para o design direto de roteamento de cenários hospedados por parceiros, ou cenários implantados pelo cliente para até 10 sites.  </li>
<li> Análise da configuração do controlador de borda da sessão (SBC). </li>

<li> Assistência remota com a configuração do plano de discagem. </li>

<li> Configuração da rota de voz.</li>

<li> Bypass de mídia e otimização de mídia local. </li>

</ul></li>
</ul></li>
<li>  Habilitação dos eventos ao vivo do Teams.  </li>
<li>  Configuração e integração da organização com o Microsoft Stream.  </li>
<li>  Diretrizes para a transição do Skype for Business para o Microsoft Teams.  </li>
</ul></td>
<td><ul>
<li>  Identidades dos usuários habilitadas no Azure Active Directory para Office 365.  </li>
<li>  Usuários habilitados para o SharePoint Online.  </li>
<li>  Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).  </li>
<li>  Habilitado para Grupos do Office 365.  </li>
</ul>
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão o armazenamento do OneDrive for Business no Office 365. O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365. O Teams não oferece suporte para o SharePoint no local.  <br>
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio hospedadas no Exchange Online. Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect. Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.  
  Os instaladores dos clientes de área de trabalho do Microsoft Teams para Windows e Mac podem ser baixados em <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
</tr>
<tr class="odd">
<td><strong>Proteção Avançada contra Ameaças do Office 365 (ATP)</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Habilitação de Links Seguros, Anexos Seguros e anti-phishing.  </li>
<li>  Configuração de automação, investigação e resposta.  </li>
<li>  Uso do Simulador de Ataques.  </li>
<li>  Relatórios e análise de ameaças.  </li>
</ul></td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="even">
<td><strong>Outlook para iOS e Android</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Baixe o Outlook para iOS e Android no Google Play e Apple App Store.  </li>
<li>  Configurar contas e acessar a caixa de correio do Exchange Online.  </li>
<li>  Proteger o Outlook Mobile (para obter mais informações, confira <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Proteger o Outlook para iOS e Android no Exchange Online</a>).  </li>
</ul></td>
<td><ul>
<li>  Identidades dos usuários habilitadas no Azure Active Directory para Office 365.  </li>
<li>  Exchange Online configurado e licenças atribuídas.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Atribuição de licenças do Power BI.  </li>
<li>  Implantação do aplicativo do Power BI Desktop.  </li>
</ul></td>
<td>Software cliente online como o Power BI desktop deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Verificar as funcionalidades básicas do SharePoint nos quais o Project Online se baseia.  </li>
<li>  Adicionar o serviço do Project Online ao locatário, inclusive adicionar assinaturas para os usuários.  </li>
<li>  Configurar o ERP (Pool de Recursos da Empresa).  </li>
<li>  Criando seu primeiro projeto.  </li>
</ul></td>
<td>O software de cliente online, como o Project for Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional e Premium</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Solução de problemas de implantação.  </li>
<li>  Atribuição de licenças de usuário final usando o Centro de administração do Microsoft 365 e o Windows PowerShell.  </li>
<li>  Instalação do Cliente de Área de Trabalho do Microsoft Project Online pelo portal do Office 365 usando Clique para Executar.  </li>
<li>  Definir as configurações de atualização usando a Ferramenta de Implantação do Office 365.  </li>
<li>  Configurar um único servidor de distribuição no local para o Cliente de Área de Trabalho do Microsoft Project Online, inclusive assistência com a criação de um arquivo configuration.xml para uso com a Ferramenta de Implantação do Office 365.  </li>
<li>  Conexão do Cliente de Área de Trabalho do Microsoft Project Online ao Project Online Professional ou Project Online Premium.  </li>
</ul></td>
<td>O software de cliente online, como o Project for Office 365, deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online e OneDrive for Business</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Configuração do DNS.  </li>
<li>  Configurar portas do firewall.  </li>
<li>  Provisionar usuários e licenças.  </li>
<li>Habilitar a criação de sites para o administrador do SharePoint Online.</li>
<li>Planejamento de conjuntos de sites.</li>
<li>Proteção de conteúdo e gerenciamento de permissões.</li>
<li>Configuração de recursos do SharePoint Online.</li>
<li>  Configurar recursos híbridos do SharePoint, como pesquisa híbrida, sites híbridos, taxonomia híbrida, tipos de conteúdo, criação de sites de autoatendimento híbridos (SharePoint Server 2013 apenas), inicializador de aplicativos estendido, OneDrive for Business híbrido e sites extranet.  </li>
<li>  Método de migração.  </li>
</ul>
Serão fornecidas diretrizes adicionais para o OneDrive for Business, dependendo da versão do SharePoint, como:
<ul>
<li>  Identificar as opções de integração, revisar a largura de banda e a infraestrutura de rede local e online.  </li>
<li>  Instalar o SharePoint Online 2013 SP1 (se aplicável), planejar e implementar requisitos de sincronização e identidade e identificar seu cliente de sincronização do OneDrive for Business.  </li>
<li>  Planejar e implementar a distribuição única (ou em fases) para todos os usuários.  </li>
<li>  Atribuir licenças, redirecionar Meus Sites e bibliotecas de documentos pessoais para o Office 365 (aplicável ao SharePoint Online 2013), configurar audiências para controlar o acesso ao OneDrive (aplicável ao SharePoint Online 2013).  </li>
<li>Redirecionar ou mover pastas conhecidas para o OneDrive.</li>
<li>  Implantar o cliente de sincronização do OneDrive for Business.  </li>
</ul>
  <strong>Migração de dados</strong>  <br>
Para saber mais sobre como usar os benefícios do FastTrack para migração de dados para o Office 365, confira <a href="https://docs.microsoft.com/fasttrack/data-migration">Migração de dados</a>.
</ul></td>
<td><br><strong>Para o SharePoint híbrido:</strong>  
<ul>
<li>  A configuração da implantação híbrida do SharePoint inclui pesquisa híbrida, sites, taxonomia, tipos de conteúdo, OneDrive for Business, um iniciador de aplicativos estendido, sites de extranet e criação de sites de autoatendimento conectados de um ambiente local a um ambiente de destino único do SharePoint Online.  </li>
</ul>
  <strong>Observação:</strong> A criação de sites de autoatendimento não está no escopo com servidores locais que executam o SharePoint 2013.  
<ul>
<li>  Para habilitar a implantação híbrida do SharePoint, é necessário ter um dos seguintes ambientes locais do SharePoint Server: 2013, 2016, ou 2019.  </li>
</ul>
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência. Para obter mais informações, consulte <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum Public Update Levels for SharePoint Hybrid Features</a><em>.</em>  <br>
  <strong>Observação:</strong> Para obter informações sobre recursos multigeográfico, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">recursos de várias geografias no onedrive e no SharePoint Online no Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.  
</ul></td>
<td>O software cliente online deve estar em um nível mínimo, conforme definido nos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos do sistema para o Microsoft 365 e o Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility e Security

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure AD (Active Directory) e Azure AD Premium</strong></td>
<td>  Fornecemos orientações remotas para a proteção de identidades na nuvem para os cenários a seguir.  

 <br/>

<strong>Proteger a infraestrutura de base</strong>  </ul>
<ul>
<li>  Configurar e habilitar uma autenticação forte para as identidades, incluindo a proteção com a autenticação multifator do Microsoft Azure (MFA) (somente na nuvem), do aplicativo Microsoft Authenticator e registro combinado para o Azure MFA e a redefinição de senha de autoatendimento (SSPR).  </li>
<li>  Para clientes que não são do Azure AD Premium, a orientação é fornecida para proteger as identidades usando padrões de segurança.  </li>
<li>  Para clientes do Azure AD Premium, a orientação é fornecida para proteger as identidades com o acesso condicional.  </li>
<li>  Detectar e bloquear o uso de senhas fracas com o Azure Active Directory Identity Protection.  </li>
<li>  Fornecer acesso remoto seguro a aplicativos locais com o Azure AD Application Proxy.  </li>
<li>  Permitir a detecção e a correção baseadas em risco com o Azure AD Identity Protection.  </li>
<li>  Habilitar uma tela de entrada personalizada, incluindo o logotipo, o texto e as imagens com identidade visual personalizada.  </li>
<li>  Compartilhamento seguro de aplicativos e serviços com usuários convidados usando a B2B do Azure AD.  </li>
<li>  Gerenciar o acesso dos administradores do Office 365 usando o controle de acesso baseado em função (RBAC), funções administrativas internas e reduzir o número de contas administrativas privilegiadas.  </li>
<li>  Configurar o ingresso no Azure AD híbrido.  </li>
<li>  Configurar o ingresso no Azure AD.  </li>
</ul>
  
<strong>Métricas e relatórios</strong>  
<ul>
<li>  
  Habilitar o monitoramento remoto para AD FS, Azure AD Connect e controladores de domínio com o Azure Active Directory Connect Health.  
  </li>
</ul>
  
<strong>Governança</strong>  
<ul>
<li>  
  Gerenciar o ciclo de vida do Azure AD Identity em escala com o gerenciamento de direitos do Azure AD.
  </li>
<li>  
  Gerenciar associações de grupos do Azure AD, acesso a aplicativos corporativos e atribuições de funções com as revisões de acesso do Azure AD.  
  </li>
<li>  
  Revisar os termos de uso do Azure AD.  
  </li>
<li>  
  Gerenciar e controlar o acesso a contas de administrador privilegiadas com o gerenciamento de identidade privilegiada do Azure AD.  
  </li>
</ul>
  
<strong>Automação e eficiência </strong>  
<ul>
<li>  
  Habilitar o Azure AD SSPR.  
  </li>
<li>  Permitir que os usuários criem e gerenciem seus próprios recursos de segurança na nuvem ou do Office 365 com o gerenciamento de grupos de autoatendimento do Azure AD.  </li>
<li>  Gerenciar o acesso delegado a aplicativos empresariais com o gerenciamento de grupos delegados do Azure AD.  </li>
<li>  Habilitar os grupos dinâmicos do Azure AD.  </li>
<li>  Organizar aplicativos no portal Meus Aplicativos usando coleções.  </li>
</ul></td>
<td>O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, incluindo a correção de problemas identificados que impedem a integração com o Azure AD e os recursos do Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Proteção de Informações do Azure (P2 ou EMS E5)</strong></td>
<td>  Fornecemos orientações sobre como:
<ul>
<li>  Ativar e configurar o locatário.  </li>
<li>  Criar e configurar rótulos e políticas.  </li>
<li>  Aplicação de proteção de informações aos documentos.  </li>
<li>  Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.  </li>
<li>  Uso de arquivos em repouso com o scanner da Proteção de Informações do Azure.  </li>
<li>  Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.  </li>
</ul>
As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).  </td>
<td>  Você já deve saber:
<ul>
<li>  Usar o Azure AD.  </li>
<li>  Usar o Windows ou o iOS (outros SOs estão fora do escopo).  
  </ul>
<strong>Observação</strong>: os computadores e dispositivos móveis devem ser executados em um <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operacional</a> que suporte a Proteção de Informações do Azure.  
<li>  Ter seus principais locais de compartilhamento de arquivos.  </li>
<strong>Observação</strong>: o suporte híbrido exige o conector AD RMS. 
<li>  Ter uma taxonomia de classificação aprovada.  </li>
<li>  Entender as restrições normativas para o gerenciamento de chaves protegidas.  </li>
</ul>
  
<strong>Scanner da Proteção de Informações do Azure</strong>  
  
Você já deve saber:  
<ul>
<li>  Usar o Windows Server 2012 R2 ou o Windows Server 2016.  </li>
<li>  Ter uma conexão à Internet.  </li>
<li>  Ter o Microsoft SQL Server 2012 em uma instância local ou remota.  </li>
<li>  Ter uma conta de serviço criada para o Active Directory local e sincronizada com o Azure AD.  </li>
<li>  Ter baixado AzInfoProtection.exe.  </li>
<li>  Ter etiquetas configuradas para classificação/proteção automática.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Fornecemos orientações sobre como preparar-se para usar o Intune como o gerenciamento de dispositivo móvel baseado em nuvem (MDM) e o provedor de gerenciamento de aplicativo móvel (MAM) para seus aplicativos e dispositivos. As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis. As etapas podem incluir:
<ul>
<li>  Licenciamento para os usuários finais.  </li>
<li>  Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Microsoft Azure AD).  </li>
<li>  Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.  </li>
<li>  Configuração da autoridade MDM com base em suas necessidades de gerenciamento, incluindo:
<ul>
<li>  Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.  </li>
</ul></li>
<li>  Fornecendo instruções MDM para:
<ul>
<li>  Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.  </li>
<li>  Configuração do gerenciamento das políticas e serviços do MDM, como:
<ul>
<li>  Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.  </li>
<li>  Políticas de Acesso Condicional.  </li>
<li>  Implantação de email, redes sem fio e perfis VPN se tiver uma autoridade de certificação existente, uma infraestrutura de rede sem fio ou VPN em sua organização.  </li>
<li>  Conexão ao Intune Data Warehouse.  </li>
<li>  Integração do Intune com:
<ul>
<li>  O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).  </li>
<li>  Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).  </li>
<li>  Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).  </li>
<li>  Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).  </li>
</ul></li>
<li>  Registração dos dispositivos de todas as plataformas compatíveis com o Intune.  </li>
</ul></li>
</ul></li>
<li>  Fornecendo diretrizes de proteção de aplicativos para:
<ul>
<li>  Configurar as políticas de proteção de aplicativo para cada plataforma com suporte.  </li>
<li>  Configurar as políticas de acesso condicional para aplicativos gerenciados.  </li>
<li>  Direcionar os grupos de usuários apropriados com as políticas de MAM mencionadas anteriormente.  </li>
<li>  Usar os relatórios de uso de aplicativos gerenciados.  </li>
</ul></li>
<li>  Fornecer uma guia de migração de gerenciamento de computador herdado para o MDM do Intune.  </li>
</ul>
  <strong>Observação</strong>: não há mais suporte para o gerenciamento de computador herdado desde 15 de outubro de 2020 em diante.  
</li>
</ul>
  
<strong>Vincular à nuvem</strong>  

  Orientamos você a se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune. As etapas exatas dependem do ambiente de origem. Essas etapas podem incluir:  
<ul>
<li>  Licenciamento para os usuários finais.  </li>
<li>  A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.  </li>
<li>  Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.  </li>
<li>  Fornecimento de diretrizes de configuração da associação híbrida do Microsoft Azure AD.  </li>
<li>  Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.  </li>
<li>  Fornecimento de diretrizes sobre como configurar o gateway de gerenciamento de nuvem.  </li>
<li>  Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.  </li>
<li>  Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.  </li>
</ul> 

<strong>Implantar o Outlook Mobile para iOS e Android de maneira segura</strong> podemos fornecer orientação para ajudar você a implantar o Outlook móvel para iOS e Android com segurança em sua organização, a fim de garantir que os usuários tenham todos os aplicativos necessários instalados.  
  As etapas para implantar o Outlook móvel para iOS e Android com Intune dependem do seu ambiente de origem. Isso pode incluir:
<ul>
<li>  Baixar o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo Portal da Empresa do Intune por meio da Apple App Store ou do Google Play Store.  </li>
<li>  Fornece orientação sobre como configurar:
<ul>
<li>  O Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativos do Portal da Empresa do Intune com o Intune.  </li>
<li>  Políticas de proteção de aplicativos.  </li>
<li>  Políticas de acesso condicional.  </li>
<li>  Políticas de configuração do usuário.  </li>
</ul></li>
</ul>
  
  <strong>Observação</strong>: o FastTrack não é compatível com a proteção do Outlook para iOS e Android com as políticas de caixa de correio de dispositivo móvel do Exchange. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.  
  </td>
<td>  Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.  
  <strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.  
 
  <strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.

  <strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong> 
 
  <strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10. Não fornecemos assistência na compra, licenciamento ou ativação. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.  
  
<strong>Windows Autopilot</strong> 
 
  Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.  
  
<strong>Implantar o Outlook para iOS e Android de forma segura com o Intune</strong>  
<ul>
<li>  Identidades dos usuários habilitadas no Azure Active Directory para o Office 365.  </li>
<li>  Exchange Online ou Exchange híbrido configurado com licenças de usuário atribuídas.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

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
<td><strong>Windows 10</strong></td>
<td>  Fornecemos orientações para a atualização do Windows 7 Professional e do Windows 8,1 Professional para o Windows 10 Enterprise.  
  Fornecemos orientações remotas para:
<ul>
<li>  Entender a sua intenção do Windows 10.  </li>
<li>  Verificar o seu ambiente de origem e os requisitos (certificar-se que o Microsoft Endpoint Configuration Manager está atualizado para o nível necessário para dar suporte à implantação do Windows 10).  </li>
<li>  Implantar o Windows 10 Enterprise e o Microsoft 365 Apps usando o Microsoft Endpoint Configuration Manager ou o Microsoft 365.  </li>
<li>  Recomendamos opções para você avaliar os aplicativos do Windows 10.  </li>
<li>  Habilitação do uso do Desktop Analytics e orientação durante a criação de um plano de implantação do Desktop Analytics.  </li>
<li>  Avaliação de compatibilidade do Microsoft 365 Apps, aproveitando o painel de prontidão do Office 365 no Gerenciador de configurações ou com o Readiness Toolkit do Office independente, além de assistência na implantação do Microsoft 365 Apps.  </li>
<li>  Criação de uma lista de verificação de correções sobre o que você precisa fazer para dar ao ambiente de origem os requisitos mínimos para uma implantação bem-sucedida.  </li>
<li>  Diretrizes para atualizar seus dispositivos existentes para o Windows 10 Enterprise, desde que atendam aos requisitos de hardware de dispositivo necessários.  </li>
<li>  Diretrizes de atualização para dar suporte ao seu movimento de implantação existente. O FastTrack recomenda e fornece diretrizes para uma atualização in-loco para o Windows 10. As diretrizes também estão disponíveis para a instalação de imagem limpa do Windows e cenários de implantação do Windows Autopilot.  </li>
<li>  Implantação do Microsoft 365 Apps usando o Configuration Manager como parte da implantação do Windows 10.   </li>
<li>  Orientação para ajudar sua organização a se manter atualizada com o Windows 10 Enterprise e Microsoft 365 Apps usando seu ambiente de Configuration Manager existente ou Microsoft 365.  </li>
</ul>
  <strong>O seguinte está fora do escopo </strong>  
<ul>
<li>  Atualizar o Configuration Manager para o Branch Atual.  </li>
<li>  Criar imagens personalizadas para a implantação do Windows 10.  </li>
<li>  Criar e dar suporte à implantação de scripts para a implantação do Windows 10.  </li>
<li>  Converter um sistema Windows 10 do BIOS para a UEFI (Unified Extensible Firmware Interface).  </li>
<li>  Habilitar os recursos de segurança do Windows 10.  </li>
<li>  Configurar os Serviços de Implantação do Windows (WDS) para inicialização do Preboot Execution Environment (PXE).  </li>
<li>  Usar o Kit de Ferramentas de Implantação da Microsoft (MDT) para capturar e implantar imagens do Windows 10.  </li>
<li>  Usar a Ferramenta de Migração de Estado do Usuário (USMT).  </li>
</ul>
Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.  </td>
<td>  Para a atualização do computador, você deve atender a esses requisitos:
<ul>
<li>  SO de origem: Windows 7 Enterprise ou Professional, Windows 8.1 Enterprise ou Professional.  </li>
<li>  Dispositivos: fator forma de desktop, notebook ou tablet.  </li>
<li>  SO de destino: Windows 10 Enterprise.  </li>
</ul>
Para atualização da infraestrutura, você deve atender a esses requisitos:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  A versão do Configuration Manager deve ter suporte na versão de destino do Windows 10. Para obter mais informações, confira a tabela de suporte do Configuration Manager em <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Suporte para Windows 10 no Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong></td>
<td>  A Proteção Avançada contra Ameaças do Microsoft Defender (ATP) é uma plataforma projetada para ajudar as redes corporativas a prevenir, detectar, investigar e responder à ameaças avançadas.  
  Fornecemos orientações remotas para:
<ul>
<li>  Implantar as tecnologias para proteger seus pontos de extremidade.  </li>
<li>  Configurando proteção de ponto de extremidade e os perfis de restrição do dispositivo.  </li>
<li>  Avaliar a versão do sistema operacional e o gerenciamento de dispositivo (incluindo o Intune, o Microsoft Endpoint Configuration Manager, GPOs (objetos de política de grupo) e configurações de terceiros), bem como o status dos serviços do AV do Windows Defender ou de outro software de segurança do ponto de extremidade.  </li>
<li>  Avaliar o status dos seus serviços AV do Windows ou outro software de segurança do ponto de extremidade.  </li>
<li>  Avaliar proxies e firewalls que restringem o tráfego de rede.  </li>
<li>  Habilitar o serviço Microsoft Defender ATP, explicando como implantar um perfil de agente ATP usando um ponto de extremidade integrado.  </li>
<li>  Diretrizes de implantação, assistência de configuração e treinamento em:
<ul>
<li>  
  Gerenciamento de ameaças e vulnerabilidades.  
  </li>
<li>  
  Redução da superfície do ataque.  
  </li>
<li>  
  Proteção da próxima geração.  
  </li>
<li>  
  Detecção e resposta do terminal.  
  </li>
<li>  
  Investigação e correção automatizadas.  
  </li>
<li>  
  Classificação de segurança.  
  </li>
</ul></li>
<li>  Analisar simulações e tutoriais (como cenários de prática, malware falso e investigações automatizadas).  </li>
<li>  Visão geral dos recursos de relatório e análise de ameaças.  </li>
<li>  Integrar o ATP do Office 365 com o ATP do Microsoft Defender.  </li>
<li>  Conduzir instruções do Portal do centre de segurança do Microsoft Defender.  </li>
<li>  Um dos seguintes sistemas operacionais:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019, Core Edition.  
  </li>
<li>  
  Canal semestral do Windows Server (SAC) versão 1803.  
  </li>
<li>  
  macOS versões 10.13, 10.14 e 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Observação:</strong> todas as versões do Windows Server devem ser gerenciadas pela versão mais recente do System Center Configuration Manager 2012 (versões 1012 R2, 1511 ou 1602) ou do Microsoft Endpoint Configuration Manager (versão 2002 ou posterior). 

</li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>  Gerenciamento de projetos das atividades de correção do cliente.  </li>
<li>  Suporte no local.  </li>
<li>  Gerenciamento contínuo e resposta a ameaças.  </li>
<li>  Integração ou configuração para os seguintes agentes do Microsoft Defender ATP:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Dispositivos móveis (Android e iOS).  
  </li>
</ul></li>
<li>  Integração e configuração do servidor:
<ul>
<li>  
  Configurar um servidor proxy para comunicações offline.  
  </li>
<li>  
  Configurar pacotes de implantação do Configuration Manager no nível inferior de instâncias e versões do Configuration Manager.  
  </li>
<li>  
  Servidores de integração com a Central de Segurança do Azure.  
  </li>
<li>  
  Os servidores não são gerenciados pelo Configuration Manager.  
  </li>
</ul></li>
<li>  Integração e configuração do macOS:
<ul>
<li>  
  Implantação manual baseada no Intune.  
  </li>
<li>  
  Implantação baseada em JAMF.
  </li>
<li>  
  Outra implantação baseada em produtos de gerenciamento de dispositivo móvel (MDM).  
  </li>
<li>  
  Implantação manual.  
  </li>
</ul></li>
<li>  Configuração dos seguintes recursos de redução da superfície de ataque:
<ul>
<li>  
  Isolamento baseado em hardware.  
  </li>
<li>  
  Controle de aplicativo.  
  </li>
<li>  
  Explorar proteção.  
  </li>
<li>  
  Firewall da rede.  
  </li>
</ul></li>
<li>  Inscrição ou configuração dos Peritos em ameaças da Microsoft.  </li>
<li>  Configuração ou treinamento revisando a API ou as conexões de informações de segurança e gerenciamento de eventos (SIEM).  </li>
<li>  Registro ou configuração da Proteção contra ameaças da Microsoft (MTP).  </li>
<li>  Treinamento ou orientação sobre a caça avançada.  </li>
<li>  Treinamento ou diretrizes que abordam o uso do ou a criação de consultas Kusto.</li>
</li>
</ul>
Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Área de Trabalho Virtual do Windows

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
<td><strong>Área de Trabalho Virtual do Windows</strong></td>
<td><p>Fornecemos orientações de implantação para integração com a área de trabalho virtual do Windows (um serviço de virtualização de desktop e aplicativos). A área de trabalho virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para aplicativos da Microsoft 365 para empresas com segurança e gerenciamento integrados para o Microsoft 365.</p>
<p>Fornecemos orientações remotas para:</p>
<ul>
<li>Implantação do ambiente de área de trabalho virtual do Windows com o Windows 10 Enterprise com várias sessões e o Microsoft 365 aplicativos para empresas usando o seguinte:
<ul>
<li>Imagem do Azure Marketplace.</li>
<li>Imagem compartilhada.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configurando o FSLogix:
<ul>
<li>Implantando o agente FSLogix com contêiner de perfil.</li>
<li>Implantando o agente do FSLogix com o contêiner do Office.</li>
<li>Configurando a pasta FSLogix com exclusões de conteúdo.</li>
</ul></li>
<li>Implantar o Microsoft Edge.</li>
<li>Implantação do Microsoft Teams.</li>
<li>Conexão usando clientes da área de trabalho virtual do Windows.</li>
</ul>

<strong>O seguinte está fora do escopo</strong>
<ul>
<li>Gerenciamento de projetos da implantação de área de trabalho virtual do Windows do cliente.</li>
<li>Suporte no local.</li>
<li>Virtualização e implantação de aplicativos de terceiros.</li>
<li>Imagens personalizadas.</li>
<li>Migrações e cenários envolvendo VMware e Citrix.</li>
<li>Cenários do Linux.</li>
<li>Conversão ou migrações de perfis de usuário.</li>
</ul>
Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</td>
<td>Você já deve ter o seguinte:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento de área de trabalho virtual do Windows</a>.</li>
<li>Rede do Azure:
<ul>
<li>Criação e sub-rede de rede virtual (VNET).</li>
<li>Grupos de segurança de rede e firewall.</li>
<li>VPN e ExpressRoute.</li>
<li>Roteamento para o Azure no local.</li>
<li>Regras de firewall para permitir a conectividade com a área de trabalho virtual do Windows.
</ul>
Confira mais informações em <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> clientes de área de trabalho remota compatíveis</a>.
</ul>
<ul><li>Configuração geral do Azure AD:
<ul>
<li>Estratégia de identidade <i>(você pode usar apenas uma das três opções a seguir):</i>
<ul>
<li>Active Directory com o Azure AD Connect no Azure.</li>
<li>Active Directory com o Azure AD Connect local via VPN ou ExpressRoute.</li>
<li>Serviços de domínio do Active Directory (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>Garantia do aplicativo


<table>
<thead>
<tr class="header">
<th><strong>Serviço</strong></th>
<th><strong>Detalhes da orientação do FastTrack</strong></th>
<th><strong>Produtos suportados</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Garantia de Aplicativo</strong></td>
<td>  A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps. Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais. Também fornecemos orientações para os clientes que enfrentam problemas de compatibilidade ao implantar a área de trabalho virtual do Windows e o novo Microsoft Edge e tornam cada esforço razoável para resolver problemas de compatibilidade. Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:
<ul>
<li>  <strong>Windows 10 </strong> (incluindo dispositivos ARM64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>O novo Microsoft Edge-</strong> Para obter diretrizes de implantação, confira <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">visão geral dos canais do Microsoft Edge</a>.  </li>
<li>  <strong>Área de trabalho</strong> - virtual do Windows Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">o que é a área de trabalho virtual do Windows?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">perguntas frequentes sobre várias sessões do Windows 10 Enterprise</a>.  </li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>  Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps. Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>. Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</li>
<li>  Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10. Para obter mais informações, confira <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</li>
<li>Serviços de embalagem do aplicativo. No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</li>
</ul>

<strong>Responsabilidades do cliente incluem</strong>  
<ul>
<li>  Criar um inventário de aplicativo.</li>
<li>  Validando esses aplicativos no Windows 10 e no Microsoft 365 Apps.</li>
</ul>
<strong>Observação:</strong>  A Microsoft não pode fazer alterações no código-fonte. No entanto, a equipe da Garantia de Aplicativo da Área de Trabalho pode fornecer orientações para os desenvolvedores de aplicativo se o código-fonte estiver disponível para os aplicativos. 


  Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.  </td>

</td>
<td><strong>Windows 10 e Microsoft 365 Apps</strong>
<ul>
<li>  
  Os aplicativos que funcionavam no Windows 7, Windows 8.1, Office 2010 e Office 2013 também funcionam no Windows 10 e no Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 no ARM</strong>
<ul>
<li>  
Os aplicativos que funcionaram no Windows 7, no Office 2010 ou nas versões posteriores funcionam em aplicativos do Windows 10 e Microsoft 365 em dispositivos ARM64. 
  </li>
</ul>
  <strong>Observação:</strong> As exclusões e limitações do Windows 10 no ARM incluem:
<ul>
<li>  
 Aplicativos que dependem de drivers de software que não são compatíveis com o ARM.  
  </li>
<li>  
  Aplicativos que usam OpenGL ou OpenCL.   
  </li>
<li>  
  Os aplicativos estão disponíveis somente no 64-bit (x64).  
  </li>
</ul>
<strong>O novo Microsoft Edge</strong>
<ul>
<li>  
  Se os seus sites ou aplicativo Web funcionarem no Internet Explorer 11, nas versões com suporte do Google Chrome ou em qualquer versão do Microsoft Edge, eles também funcionarão no novo Microsoft Edge.  
  </li>
<li>  
  Como a Web está em constante evolução, revise esta lista publicada de alterações conhecidas de <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">impacto na compatibilidade de site para o Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Área de Trabalho Virtual do Windows</strong>  
<ul>
<li>  
  Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.  
  </li>
<li>  
  Os aplicativos executados em qualquer ambiente VDI (Virtual Desktop Infrastructure) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da área de trabalho virtual do Windows.  
  </li>
<li>  
  Os aplicativos executados nos dispositivos cliente do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da área de trabalho virtual do Windows.  
  </li>
</ul>
  <strong>Observação:</strong> As exclusões e limitações de compatibilidade de várias sessões do Windows 10 Enterprise incluem:
<ul>
<li>  
  Redirecionamento limitado de hardware.  
  </li>
<li>  
  Aplicativos de uso intensivo de A/V podem ser executados com uma capacidade reduzida.  
  </li>
<li>  
  Não há suporte para aplicativos de 16 bits na Área de Trabalho Virtual do Windows de 64 bits.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a>O novo Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Serviço</strong></th>
<th><strong>Detalhes da orientação do FastTrack</strong></th>
<th><strong>Expectativas do ambiente de origem</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Microsoft Edge</strong> (para clientes do Windows 10 Enterprise)</td>
<td><ul>
<li>  Fornecemos assistência para a implantação e compatibilidade para: implantação do novo Microsoft Edge no Windows 10 Enterprise com o Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Microsoft Intune).  </li>
<li>  Configuração do Microsoft Edge (usando políticas de grupo ou configuração do aplicativo do Intune e políticas de aplicativos).  </li>
<li>  Inventariar a lista dos sites que podem exigir o uso no modo do Internet Explorer.  </li>
<li>  Habilitação do modo do Internet Explorer com a lista de sites corporativos existente.  
  Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional. Consulte o <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">aplicativo garante</a> mais detalhes.  </li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>Gerenciamento de projetos de implantação do Microsoft Edge do cliente.</li>
<li>  Suporte no local.</li>

</td>
<td></td>
</tr>
</tbody>
</table>

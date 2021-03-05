---
title: Produtos e Recursos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.
ms.openlocfilehash: e49ada61aee869785f061bbebbee4ae14aaee045
ms.sourcegitcommit: 895a8b9df9a7cd26e27e95e5fd3145e7306c78e8
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464203"
---
# <a name="products-and-capabilities"></a>Produtos e Recursos

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Serviços e cenários com suportados pelo FastTrack 

Este tópico inclui detalhes sobre os cenários de carga de trabalho suportados pelo FastTrack e as expectativas necessárias do ambiente de origem antes de começar. Baseado na sua configuração atual, trabalhamos com você na criação de um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida.

O FastTrack fornece orientações para ajudá-lo primeiro com os recursos principais (comuns para todos os Microsoft Online Services) e, em seguida, com a integração de cada serviço qualificado:

  - [Geral](#general)
  - [Segurança e conformidade](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Área de Trabalho Virtual do Windows](#windows-virtual-desktop)
  - [Garantia de Aplicativo](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

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
  <strong>Importante</strong>  <ul>
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
<li>  O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">do sistema para o Microsoft 365 e o Office</a>.  </li>
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

## <a name="security-and-compliance"></a>Segurança e Conformidade

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
  Gerenciando e controlando o acesso a contas de administrador privilegiadas com o Azure AD Privileged Identity Management.  
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
<td><strong>Proteção de Informações do Azure </strong></td>
<td>  Para obter mais informações sobre a Proteção de Informações do Azure, consulte <strong>Proteção de Informações</strong> da Microsoft mais adiante nesta tabela.

  </td>
<td>  
  <tr class="odd">
<td><strong>Resposta & descoberta</strong></td>
<td>  

<strong>Descoberta Avançada de EDiscovery</strong>
  
<ul>
<li>  Habilitação de Links Seguros, Anexos Seguros e anti-phishing.  </li>
<li>  Configuração de automação, investigação e resposta.  </li>
<li>  Uso do Simulador de Ataques.  </li>
<li>  Relatórios e análise de ameaças.  </li>
</ul>

<strong>Auditoria Avançada</strong> (com suporte apenas no E5)

Fornecemos orientações remotas para:  
<ul>
<li> Habilitando a auditoria avançada.</li>
<li> Executando uma interface do usuário do log de auditoria de pesquisa e comandos básicos de auditoria do PowerShell.</li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

<strong>O seguinte está fora do escopo </strong> 
<ul>
<li> Scripts personalizados ou codificação.</li>
<li> API de Descoberta Externa. </li>
<li> Conectores de dados. </li>
<li> Limites de conformidade e filtros de segurança.</li>
<li> Investigações de dados.</li>
<li> Solicitações de assunto de dados.</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul>
</td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>

<tr class="odd">
<td><strong>Gerenciamento de ameaças insider</strong></td>

<td>  Fornecemos orientações remotas para:
<ul>
<li> Criando políticas e revendo configurações.</li>
<li> Acessando relatórios e alertas.</li>
<li> Criar casos.</li>
<li> Criando modelos de aviso.</li>
<li> Diretrizes sobre a criação do conector de recursos humanos (RH).</li>
</ul>

<strong> Conformidade de comunicação </strong> 

Fornecemos orientações remotas para: 
<ul>
<li> Criando políticas e revendo configurações.</li>
<li> Acessando relatórios e alertas.</li>
<li> Criando modelos de aviso.</li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

<strong>O seguinte está fora do escopo </strong> 
<ul>
<li> Criando e gerenciando fluxos do Power Automate.</li>
<li> Conectores de dados (além do conector de RH). </li>
<li> Configurações de expressão regular personalizada (RegEx).</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Barreiras de informações.</li>
<li> Gerenciamento de acesso privilegiado.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul></td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> O Microsoft 365 Defender é um pacote de defesa empresarial unificado pré e pós-violação que coordena de forma nativa a detecção, prevenção, investigação e resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados. Fornecemos orientações remotas para: </p> 
<ul>
<li>  Fornecendo uma visão geral do centro de segurança do Microsoft 365.  </li>
<li>  Revisão de incidentes entre produtos, incluindo o foco no que é crítico, garantindo o escopo de ataque completo, os ativos afetados e as ações de correção automatizadas agrupadas.  </li>
<li>  Demonstrando como o Microsoft 365 Defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidas por meio da auto-recuperação automatizada. </li>
<li>  Explicando e fornecendo exemplos de como os clientes podem procurar proativamente tentativas de invasão e atividades de violação que afetam seu email, dados, dispositivos e contas em vários conjuntos de dados.   </li>
<li> Mostrando aos clientes como eles podem revisar e melhorar a postura de segurança de forma holística usando a Pontuação Segura da Microsoft.</li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li> Gerenciamento de projetos das atividades de correção do cliente. </li>
<li> Gerenciamento contínuo, resposta a ameaças e correção. </li>
<li> Diretrizes de implantação ou educação em:
<ul>
<li> Como remediar ou interpretar os vários tipos de alerta e atividades monitoradas. </li>
<li> Como investigar um usuário, computador, caminho de movimento lateral ou entidade. </li>
<li> Busca personalizada de ameaças.  </li>
</ul>
</li>
<li> Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  O Microsoft Cloud App Security é um Agente de Segurança do Cloud Access (CASB) que fornece visibilidade avançada, controle sobre viagens de dados e análises sofisticadas para identificar e combater ameaças cibernéticas em todos os serviços de nuvem da Microsoft e de terceiros. Fornecemos orientações remotas para:
<ul>
<li>  Configurando o portal, incluindo:  </li>
<ul>
<li> Importando grupos de usuários.</li>
<li> Gerenciando o acesso e as configurações do administrador.  </li>
<li> Scoping sua implantação para selecionar determinados grupos de usuários para monitorar ou excluir do monitoramento.</li>
<li> Definindo intervalos e marcas IP.</li>
<li> Personalizando a experiência do usuário final com seu logotipo e mensagens personalizadas.</li>
</ul>
<li> Configurando a descoberta na nuvem para fornecer a tecnologia de sombra usando:</li>
<ul>
<li> Microsoft Defender para Pontos de Extremidade.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Conectando <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicativos em destaque</a> usando conectores de aplicativo.</li>
<li> Configurando o Controle de Aplicativo de Acesso Condicional nos portais de Acesso Condicional e Segurança de Aplicativos na Nuvem para aplicar controles de sessão em tempo real.</li>
<li> Implantando os painéis Cloud App Security e Cloud Discovery.</li>
<li> Personalização de pontuações de risco de aplicativo com base nas prioridades da sua organização.</li>
<li> Criando marcas e categorias de aplicativos.</li>
<li> Sancionando e desemanando aplicativos.</li>
<li> Usando a atividade e os logs de arquivo.</li>
<li> Gerenciando aplicativos OAuth.</li>
<li> Noções básicas sobre a correlação de incidentes no portal do Microsoft 365 Defender.</li>
<li> Fornecendo assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> principais casos de uso para CASBs (incluindo a criação ou atualização de até seis (6) políticas), exceto: </li>
<ul>
<li> Auditoria da configuração da internet como ambientes de serviço (IaaS) (#18).</li>
<li> Monitorando as atividades do usuário para proteger contra ameaças em seus ambientes iaaS (#19).</li>
</ul>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li> Gerenciamento de projetos das atividades de correção do cliente.</li>
<li> Gerenciamento contínuo, resposta a ameaças e correção. </li>
<li> Configurando a infraestrutura, a instalação ou a implantação de carregamentos de log automáticos para relatórios contínuos usando o Docker ou um coletor de log. Confira <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Os 20 principais casos de uso para CASBs</a> para obter mais detalhes.</li>
<li> Criando um relatório de instantâneo de Descoberta na Nuvem.</li>
<li> Bloqueando o uso do aplicativo usando scripts de bloqueio.</li>
<li> Conectando aplicativos personalizados.</li>
<li> Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção contra perda de dados (DLP).</li>
<li> Treinamento ou orientação sobre a caça avançada.</li>
<li> Investigação e correção automatizadas, incluindo os playbooks do Microsoft Power Automate.</li>
<li> Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel).</li>
<li> Implantando a Descoberta de Aplicativos na Nuvem como uma prova de conceito.</li>
</ul></td>
</tr>



<tr class="even">
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
<li> Virtual Desktop Infrastructure (VDI) (persistente ou não persistente).  </li>
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
<li> Controle de dispositivo.</li>
<li>  
  Explorar proteção.  
  </li>
<li>  
  Firewall da rede.  
  </li>



</ul></li>
<li> Configuração ou gerenciamento de recursos de proteção de conta como: </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Configuração ou gerenciamento do BitLocker.</li>
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

<tr class="odd">
<td><strong>Microsoft Defender para Identidade </strong></td>
<td>  O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização. Fornecemos orientações remotas para:
<ul>
<li>   Criando sua instância do Defender para Identidade. </li>
<li>   Conectando o Defender para Identidade ao Active Directory. </li>
<li>   Avaliando a preparação do seu ambiente para implantar o sensor Defender for Identity em seus controladores de domínio, incluindo:</li>   
<ul> 
<li>  Executando a ferramenta de sizing para planejamento de capacidade de recursos. </li>
<li>  Executando a ferramenta de auditoria para avaliar a compatibilidade dos controladores de domínio com o sensor. </li>
</ul>
<li>  Implantando o sensor para capturar e analisar o tráfego de rede e eventos do Windows diretamente de seus controladores de domínio, incluindo: </li>
<ul> 
<li>  Baixando o pacote do sensor. </li>
<li>  Configurando o sensor. </li>
<li>  Instalando o sensor no controlador de domínio silenciosamente. </li>
<li>  Implantando o sensor em seu ambiente de várias florestas. </li>
</ul>
<li>  Integrando o Defender para Identidade com o Microsoft Cloud App Security (o licenciamento de Segurança do Aplicativo na Nuvem não é necessário). </li>
<li>  Fornecendo diretrizes de implantação, assistência de configuração e educação em: </li>
<ul>
<li> Ajustando o ambiente para reduzir "ruído".  </li>
<li>  Noções básicas sobre o relatório de avaliação de postura de segurança de identidade. </li>
<li>  Noções básicas sobre a pontuação de prioridade de investigação do usuário e o relatório de classificação de investigação do usuário. </li>
<li> Noções básicas sobre o relatório do usuário inativo.  </li>
<li> Fornecendo opções de correção em uma conta comprometida.  </li>
</ul>
<li>  Facilitando a migração do Advanced Threat Analytics (ATA) para o Defender for Identity. </li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>

<li> Gerenciamento de projetos das atividades de correção do cliente. </li>
<li> Gerenciamento contínuo, resposta a ameaças e correção.  </li>
<li> Implantando o sensor Defender para Identidade, incluindo: </li>
<ul>
<li> Planejamento de capacidade manual. </li>
<li> Implantando o sensor em uma capacidade autônoma. </li>
<li> Implantando o sensor usando um adaptador de NIC (Network Interface Card). </li>
<li> Implantando o sensor por meio de uma ferramenta de terceiros. </li>
<li> Conectando-se ao serviço de nuvem Defender para Identidade por meio de uma conexão de proxy da Web. </li>
</ul>
<li> Criação e gerenciamento de honeytokens. </li>
<li> Diretrizes de implantação ou educação em: </li>
<ul>
<li> Correção ou interpretação de vários tipos de alerta e atividades monitoradas.  </li>
<li> Investigando um usuário, computador, caminho de movimento lateral ou entidade. </li>
<li> Ameaça ou busca avançada. </li>
<li> Resposta a incidentes. </li>
</ul>
<li> Fornecendo um tutorial do laboratório de alertas de segurança para o Defender for Identity. </li>
<li> Fornecer notificação quando o Defender for Identity detecta atividades suspeitas enviando alertas de segurança para seu servidor de syslog por meio de um sensor nomeado.  </li>
<li> Configurar o Defender para Identidade para realizar consultas usando o protocolo SAMR (gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas. </li>
<li> Configurando soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.  </li>
<li> Informações de segurança e gerenciamento de eventos (SIEM) ou integração à API (incluindo o Azure Sentinel). </li>
<li> Implantando sensores defender para identidade como uma prova de conceito.</li>
</ul></td>
<td><ul>
<li>  Active Directory implantado.  </li>
<li>  Os controladores de domínio que você pretende instalar os sensores do Defender para Identidade têm conectividade com a Internet para o serviço de nuvem defender para identidade.  </li>
<ul>
<li> Seu firewall e proxy devem estar abertos para se comunicar com o serviço de nuvem Defender for Identity (*.atp.azure.com porta 443 deve estar aberta).</li>
</ul>
<li> Controladores de domínio em execução em um dos seguintes:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 com KB4487044 (com build do sistema operacional 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Governança de informações da Microsoft</strong></td>

<td>  Fornecemos orientações remotas para:
<ul>
<li>  Criação e publicação de rótulos e políticas de retenção (com suporte apenas no E5).  
</li>
<li>  Gerenciamento de registros (com suporte apenas no E5).  </li>
<ul><li>  Revisão da criação do plano de arquivos. </li>
<li>  Criando e gerenciando registros (incluindo registros baseados em eventos).  </li>
<li>  Revisão da disposição. </ul> </li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

  <strong>O seguinte está fora do escopo </strong>  
<ul>
<li> Desenvolvimento de um plano de arquivo de gerenciamento de registros.</li>
<li> Conectores de dados.</li>
<li> Desenvolvimento da arquitetura de informações no SharePoint.</li>
<li> Scripts personalizados e codificação.</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Suporte para E3.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul>

</td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="odd">
<td><strong>Proteção de Informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Classificação de dados (com suporte no E3 e no E5).  </li>
<li>  Tipos de informações confidenciais (com suporte no E3 e no E5).  </li>
<li>  Criando rótulos de sensibilidade (com suporte no E3 e no E5).  </li>
<li>  Aplicando rótulos de sensibilidade (com suporte no E3 e no E5).  </li>
<li>  Classificadores com treinamento (com suporte no E5).  </li>
<li>  Conhecer seus dados com o explorador de conteúdo e o explorador de atividades (com suporte no E5).  </li>
<li>  Rótulos de publicação usando políticas (manuais e automáticas) (com suporte no E5).  </li>
<li>  Criando políticas de prevenção contra perda de dados de ponto de extremidade (DLP) para dispositivos Windows 10 (com suporte no E5).  </li>
<li>  Criando políticas de DLP para chats e canais do Microsoft Teams.  </li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

<strong> Proteção de Informações do Azure</strong>

Fornecemos orientações remotas para:  
<ul>
<li>  Ativando e configurando seu locatário.  </li>
<li>  Criando e configurando rótulos e políticas (com suporte em P1 e P2).  </li>
<li>  Aplicar proteção de informações a documentos (com suporte em P1 e P2).  </li>
<li>  Classificando e rotulando automaticamente informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de Proteção de Informações do Azure (com suporte no P2).  </li>
<li>  Descobrir e rotular arquivos em repouso usando o scanner de Proteção de Informações do Azure (com suporte em P1 e P2).  </li>
<li>  Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.  </li>
</ul>

  As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>Chave do cliente.</li>
<li>Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</li>
<li>Criação ou modificação de dicionários de palavras-chave.</li>
<li>Scripts personalizados e codificação.</li>
<li> Azure Purview.</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul>

<ul>

</td>
<td>Além da parte <strong>de integração principal</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema com exceção da Proteção de Informações do Azure.

<strong>Proteção de Informações do Azure</strong>

As responsabilidades de pré-requisito do cliente incluem:  
<ul>
<li>  Uma lista de locais de compartilhamento de arquivos a serem verificados.  </li>
<li>  Uma taxonomia de classificação aprovada. </li>
<li> Noções básicas sobre qualquer restrição regulamentar ou requisitos referentes ao gerenciamento de chaves.  </li>
<li>  Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD. </li>
<li>  Rótulos configurados para classificação e proteção. </li>
<li> Todos os pré-requisitos para o scanner de Proteção de Informações do Azure estão no local. Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>. </li>
<li>  Verifique se os dispositivos de usuário estão executando um sistema operacional com suporte e ter os pré-requisitos necessários instalados. Consulte o seguinte para obter mais detalhes.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia de administração: instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </li>
</ul>
<li> Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector rms do Active Directory (AD RMS) para suporte híbrido.  </li>
<li> Configuração e configuração de Bring Your Own Key (BYOK), DKE (Double Key Encryption) (somente cliente de rotulagem unificada) ou Hold Your Own Key (HYOK) (somente cliente clássico) caso você exigir uma dessas opções para sua implantação.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado na nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos. As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis. As etapas podem incluir:
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
<li>  Implantação de perfis de email, redes sem fio e VPN se você tiver uma autoridade de certificação existente, rede sem fio ou infraestrutura VPN em sua organização.  </li>
<li>  Conexão ao Intune Data Warehouse.  </li>
<li>  Integração do Intune com:
<ul>
<li>  O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).  </li>
<li>  Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).  </li>
<li>  Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).  </li>

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
<li>  Fornecendo orientações sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.  </li>
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
  </td>
<td>  Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.  
  <strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.  
 
  <strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.

  <strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong> 
 
  <strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10. Não fornecemos assistência na compra, licenciamento ou ativação. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.  
  
<strong>Windows Autopilot</strong> 
 
  Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.  
  
</td>
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
Software de cliente online como o Project para Office 365, Outlook para Windows, Outlook para iOS e Android, cliente de sincronização do OneDrive for Business, Área de Trabalho do Power BI e Skype for Business deve estar em um nível mínimo conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Governança de informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Criação e publicação de rótulos e políticas de retenção (com suporte apenas no E5).  
</li>
<li>  Gerenciamento de registros (com suporte apenas no E5).  </li>
<ul><li>  Revisão da criação do plano de arquivos. </li>
<li>  Criando e gerenciando registros (incluindo registros baseados em eventos).  </li>
<li>  Revisão da disposição. </ul> </li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

  <strong>O seguinte está fora do escopo </strong>  
<ul>
<li> Desenvolvimento de um plano de arquivo de gerenciamento de registros.</li>
<li> Conectores de dados.</li>
<li> Desenvolvimento da arquitetura de informações no SharePoint.</li>
<li> Scripts personalizados e codificação.</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Suporte para E3.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul>


</td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="odd">
<td><strong>Proteção de Informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Classificação de dados (com suporte no E3 e no E5).  </li>
<li>  Tipos de informações confidenciais (com suporte no E3 e no E5).  </li>
<li>  Criando rótulos de sensibilidade (com suporte no E3 e no E5).  </li>
<li>  Aplicando rótulos de sensibilidade (com suporte no E3 e no E5).  </li>
<li>  Classificadores com treinamento (com suporte no E5).  </li>
<li>  Conhecer seus dados com o explorador de conteúdo e o explorador de atividades (com suporte no E5).  </li>
<li>  Rótulos de publicação usando políticas (manuais e automáticas) (com suporte no E5).  </li>
<li>  Criando políticas de prevenção contra perda de dados de ponto de extremidade (DLP) para dispositivos Windows 10 (com suporte no E5).  </li>
<li>  Criando políticas de DLP para chats e canais do Microsoft Teams.  </li>
</ul>

<strong> Gerenciador de Conformidade</strong>

Fornecemos orientações remotas para:  

<ul> <li>Revisão de tipos de função.  </li>
<li> Adicionando e configurando avaliações.</li>
<li> Avaliando a conformidade implementando ações de melhoria e determinando como isso afeta sua pontuação de conformidade.</li>
<li> Revisar o mapeamento de controles internos e a avaliação de controles.</li>
<li> Gerando um relatório dentro de uma avaliação.</li>
</ul>

<strong> Proteção de Informações do Azure</strong>

Fornecemos orientações remotas para:  
<ul>
<li>  Ativando e configurando seu locatário.  </li>
<li>  Criando e configurando rótulos e políticas (com suporte em P1 e P2).  </li>
<li>  Aplicar proteção de informações a documentos (com suporte em P1 e P2).  </li>
<li>  Classificando e rotulando automaticamente informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de Proteção de Informações do Azure (com suporte no P2).  </li>
<li>  Descobrir e rotular arquivos em repouso usando o scanner de Proteção de Informações do Azure (com suporte em P1 e P2).  </li>
<li>  Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.  </li>
</ul>
  
As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando o Microsoft Azure AD Rights Management (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>Chave do cliente.</li>
<li>Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</li>
<li>Criação ou modificação de dicionários de palavras-chave.</li>
<li>Scripts personalizados e codificação.</li>
<li> Azure Purview.</li>
<li> Design, arquiteto e revisão de documentos de terceiros.</li>
<li> Conformidade com regulamentos e requisitos do setor e regionais.</li>
<li> Implementação prática das ações de melhoria recomendadas para avaliações no Gerenciador de Conformidade.</li>
</ul>

</td>
<td>Além da parte <strong>de integração principal</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema com exceção da Proteção de Informações do Azure.

<strong>Proteção de Informações do Azure</strong>

As responsabilidades de pré-requisito do cliente incluem:  
<ul>
<li>  Uma lista de locais de compartilhamento de arquivos a serem verificados.  </li>
<li>  Uma taxonomia de classificação aprovada. </li>
<li> Noções básicas sobre qualquer restrição regulamentar ou requisitos referentes ao gerenciamento de chaves.  </li>
<li>  Uma conta de serviço criada para o Active Directory local que foi sincronizada com o Azure AD. </li>
<li>  Rótulos configurados para classificação e proteção. </li>
<li> Todos os pré-requisitos para o scanner de Proteção de Informações do Azure estão no local. Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>. </li>
<li>  Verifique se os dispositivos de usuário estão executando um sistema operacional com suporte e ter os pré-requisitos necessários instalados. Consulte o seguinte para obter mais detalhes.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guia de administração: instalar o cliente de rotulagem unificada da Proteção de Informações do Azure para usuários</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">O que é o aplicativo de Proteção de Informações do Azure para iOS ou Android?</a>  </li>
</ul>
<li> Instalação e configuração do conector e servidores do Azure RMS, incluindo o conector rms do Active Directory (AD RMS) para suporte híbrido.  </li>
<li> Configuração e configuração de Bring Your Own Key (BYOK), DKE (Double Key Encryption) (somente cliente de rotulagem unificada) ou Hold Your Own Key (HYOK) (somente cliente clássico) caso você exigir uma dessas opções para sua implantação.  </li>
  </ul>
</ul>.

</td>
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
<li>  Assistência remota com configuração do lado do serviço de dispositivos Microsoft Teams Rooms certificados.  </li>
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
<li>  Diretrizes de configuração da organização para o design de Roteamento Direto de cenários hospedados pelo parceiro ou cenários implantados pelo cliente para até 10 sites.  </li>
<li> Revisão de configuração do Controlador de Borda de Sessão (SBC). </li>

<li> Assistência remota com configuração do plano de discagem. </li>

<li> Configuração de rota de voz.</li>

<li> Bypass de mídia e otimização de mídia local. </li>

</ul></li>
</ul></li>
<li>  Habilitação dos eventos ao vivo do Teams.  </li>
<li>  Configuração e integração da organização com o Microsoft Stream.  </li>
<li>  Diretrizes para a transição do Skype for Business para o Teams.  </li>
</ul></td>
<td><ul>
<li>  Identidades dos usuários habilitadas no Azure Active Directory para Office 365.  </li>
<li>  Usuários habilitados para o SharePoint Online.  </li>
<li>  Caixas de correio do Exchange estão presentes (online e no local em uma configuração híbrida do Exchange).  </li>
<li>  Habilitado para Grupos do Office 365.  </li>
</ul>
  <strong>Observação:</strong> Se os usuários não são atribuídos e habilitados com licenças do SharePoint Online, eles não terão armazenamento do OneDrive for Business no Office 365. O compartilhamento de arquivos continuará a funcionar em Canais, mas os usuários não poderão compartilhar arquivos em Chats sem o armazenamento do OneDrive for Business no Office 365. O Teams não oferece suporte para o SharePoint no local.  <br>
  <strong>Observação:</strong> O estado ideal é que todos os usuários tenham suas caixas de correio em casa no Exchange Online. Os usuários com caixas de correio hospedadas no local devem ter suas identidades sincronizadas com o diretório do Office 365 por meio do Azure Active Directory Connect. Para esses clientes híbridos do Exchange, se a caixa de correio do usuário estiver no local, o usuário não poderá adicionar ou configurar Conectores.  
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
<td>Software cliente online como a Área de Trabalho do Power BI deve estar em um nível mínimo, conforme definido nos requisitos do sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para o Microsoft 365 e o Office</a>.</td>
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
<td>Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</td>
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
<td>Software de cliente online como o Project para Office 365 deve estar em um nível mínimo, conforme definido nos requisitos do sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">o Microsoft 365 e o Office</a>.</td>
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
  <strong>Observação:</strong> A atualização de ambientes locais do SharePoint para o SharePoint Server não está no escopo. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência. Para obter mais informações, consulte <a href="https://go.microsoft.com/fwlink/?linkid=853548">Níveis mínimos de atualização pública para recursos híbridos do SharePoint.</a><em></em>  <br>
  <strong>Observação:</strong> Para obter informações sobre recursos multi-geo, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Fornecemos instruções remotas para habilitar o serviço do Yammer Enterprise.  
</ul></td>
<td>O software cliente online deve estar em um nível mínimo, conforme definido nos requisitos <a href="https://go.microsoft.com/fwlink/?LinkID=723597">do sistema para o Microsoft 365 e o Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>Serviço</strong></th>
<th><strong>Detalhes da orientação do FastTrack</strong></th>
<th><strong>Expectativas do ambiente de origem</strong></th>
</tr>
</thead>
<tbody>
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
  Gerenciando e controlando o acesso a contas de administrador privilegiadas com o Azure AD Privileged Identity Management.  
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
<td><strong>Proteção de Informações do Azure </strong></td>
<td>  Para obter mais informações sobre a Proteção de Informações do Azure, consulte <strong>Proteção de Informações da Microsoft</strong> em Segurança e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Conformidade.  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Fornecemos orientações remotas sobre como se preparar para usar o Intune como o MDM (gerenciamento de dispositivo móvel) baseado na nuvem e o provedor de gerenciamento de aplicativos móveis (MAM) para seus aplicativos e dispositivos. As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis. As etapas podem incluir:
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
<li>  Implantação de perfis de email, redes sem fio e VPN se você tiver uma autoridade de certificação existente, rede sem fio ou infraestrutura VPN em sua organização.  </li>
<li>  Conexão ao Intune Data Warehouse.  </li>
<li>  Integração do Intune com:
<ul>
<li>  O Team Viewer para assistência remota (é necessária uma assinatura do Team Viewer).  </li>
<li>  Soluções para parceiros de defesa contra ameaças móveis (é necessária uma assinatura da MTD).  </li>
<li>  Soluções de gerenciamento de despesas de telecomunicações (é necessária uma assinatura de solução de gerenciamento de despesas de telecomunicações).  </li>
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
<li>  Fornecendo orientações sobre como configurar o gateway de gerenciamento de nuvem quando usado como uma solução para o co-gerenciamento do gerenciamento remoto de dispositivos baseados na Internet.  </li>
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
  </td>
<td>  Os administradores de TI precisam ter infraestruturas de Autoridade de Certificação, rede sem fio e infraestruturas VPN já existentes em seus ambientes de produção ao planejar a implantação de perfis VPN e de rede sem fio com o Intune.  
  <strong>Observação</strong>: o benefício do serviço FastTrack não inclui assistência para instalar ou configurar Autoridades de Certificação, redes sem fio, infraestruturas de VPN ou certificados enviados por push de MDM da Apple para o Intune.  
 
  <strong>Observação</strong>: o benefício do serviço do FastTrack não inclui assistência para configurar ou atualizar o servidor de site ou cliente do Configuration Manager com os requisitos mínimos necessários para oferecer suporte à vinculação à nuvem. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.

  <strong>Intune integrado à Proteção Avançada contra Ameaças do Microsoft Defender (ATP)</strong> 
 
  <strong>Observação</strong>: Fornecemos assistência na integração do Intune com o Microsoft Defender ATP e na criação de políticas de conformidade de dispositivo com base na avaliação do nível de risco do Windows 10. Não fornecemos assistência na compra, licenciamento ou ativação. Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência.  
  
<strong>Windows Autopilot</strong> 
 
  Os administradores de TI são responsáveis por registrar os dispositivos em sua organização, fazendo com que o fornecedor de hardware carregue os IDs de hardware em nome deles ou fazendo o upload deles no serviço do Windows AutoPilot.  
  
</td>
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
<td>  Fornecemos orientações para atualização do Windows 7 Professional e do Windows 8.1 Professional para o Windows 10 Enterprise.  
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
<li> Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).  </li>
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
<li> Virtual Desktop Infrastructure (VDI) (persistente ou não persistente).  </li>
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
<li> Controle de dispositivo.</li>
<li>  
  Explorar proteção.  
  </li>
<li>  
  Firewall da rede.  
  </li>

<ul>
<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>

</ul></li>
<li> Configuração ou gerenciamento do BitLocker.</li>
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
<td><p>Fornecemos diretrizes de implantação para integração à Área de Trabalho Virtual do Windows (um serviço de virtualização de aplicativo e área de trabalho). A Área de Trabalho Virtual do Windows aproveita a experiência de várias sessões do Windows 10 e é otimizada para o Microsoft 365 Apps for Enterprise com segurança e gerenciamento integrados para o Microsoft 365.</p>
<p>Fornecemos orientações remotas para:</p>
<ul>
<li>Implantando seu ambiente de Área de Trabalho Virtual do Windows com várias sessões do Windows 10 Enterprise e Aplicativos do Microsoft 365 para Empresas usando o seguinte:
<ul>
<li>Imagem do Azure Marketplace.</li>
<li>Imagem compartilhada.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configurando FSLogix:
<ul>
<li>Implantando o agente FSLogix com contêiner de perfil.</li>
<li>Implantando o agente FSLogix com o contêiner do Office.</li>
<li>Configurando a pasta FSLogix com exclusões de conteúdo.</li>
</ul></li>
<li>Implantando o Microsoft Edge.</li>
<li>Implantando o Microsoft Teams.</li>
<li>Conectando-se usando clientes da Área de Trabalho Virtual do Windows.</li>
</ul>

<strong>O seguinte está fora do escopo</strong>
<ul>
<li>Gerenciamento de projetos da implantação da Área de Trabalho Virtual do Cliente.</li>
<li>Implantação e virtualização de aplicativos de terceiros.</li>
<li>Imagens personalizadas.</li>
<li>Migrações e cenários envolvendo VMware e Citrix.</li>
<li>Cenários do Linux.</li>
<li>Conversão ou migrações de perfis de usuário.</li>
</ul>
Consulte o seu <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Parceiro da Microsoft</a> para obter assistência com esses serviços.</td>
<td>Você já deve ter o seguinte:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licenciamento da Área de Trabalho Virtual do Windows</a>.</li>
<li>Rede do Azure:
<ul>
<li>Criação e sub-rede de rede virtual (VNET).</li>
<li>Grupos de segurança de rede e firewall.</li>
<li>VPN e ExpressRoute.</li>
<li>Roteamento para o Azure no local.</li>
<li>Regras de firewall para permitir a conectividade com a Área de Trabalho Virtual do Windows.
</ul>
Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Área de Trabalho Remota com suporte.</a>
</ul>
<ul><li>Configuração geral do Azure AD:
<ul>
<li>Estratégia de <i>identidade (você pode usar apenas uma das três opções a seguir):</i>
<ul>
<li>Active Directory com o Azure AD Connect no Azure.</li>
<li>Active Directory com o Azure AD Connect local através de VPN ou ExpressRoute.</li>
<li>Serviços de Domínio do Active Directory (AD DS).</li>
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
<th><strong>Expectativas do ambiente de origem</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Garantia de Aplicativo</strong></td>
<td>  A Garantia de Aplicativo garante um serviço projetado para solucionar problemas de compatibilidade com os aplicativos do Windows 10 e do Microsoft 365 Apps. Ao solicitar o serviço de Garantia de Aplicativo, nós trabalhamos com você para solucionar problemas com aplicativos válidos sem custos adicionais. Também fornecemos orientações aos clientes que enfrentam problemas de compatibilidade ao implantar a Área de Trabalho Virtual do Windows e o Microsoft Edge e fazem todos os esforços razoáveis para resolver problemas de compatibilidade. Fornecemos assistência de correção para os aplicativos implantados nos seguintes produtos da Microsoft:
<ul>
<li>  <strong>Windows 10 </strong> (incluindo dispositivos ARM64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Para obter orientações de implantação, consulte <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Visão geral dos canais do Microsoft Edge.</a>  </li>
<li>  <strong>Área de trabalho virtual do</strong> - Windows Para obter mais informações, consulte O que é a Área de Trabalho Virtual do <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows?</a> e Perguntas frequentes de várias <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">sessões do Windows 10 Enterprise.</a>  </li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>  Inventário e teste de aplicativos para determinar o que funciona e o que não funciona no Windows 10 e no Microsoft 365 Apps. Para mais orientações sobre este processo, visite o <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de Implantação do Computador</a>. Se você estiver interessado em uma avaliação de preparação para atualização detalhada, preencha o formulário <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitação de Cliente para Avaliação de Computador Moderno</a>.</li>
<li>  Pesquisar aplicativos ISV de terceiros para as instruções de compatibilidade e suporte do Windows 10. Para obter mais informações, confira <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análise da Área de Trabalho</a>.</li>
<li>Serviços de embalagem do aplicativo. No entanto, os pacotes de equipe da Garantia de Aplicativo foram corrigidos no Windows 10 para garantir que possam ser implantados no ambiente do cliente.</li>
</ul>

<strong>As responsabilidades do cliente incluem</strong>  
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
<strong>Windows 10 on ARM</strong>
<ul>
<li>  
Os aplicativos que funcionaram no Windows 7, Office 2010 ou versões posteriores também funcionam no Windows 10 e no Microsoft 365 Apps em dispositivos ARM64. 
  </li>
</ul>
  <strong>Observação:</strong> 
<ul>
<li> A emulação x64 (64 bits) está disponível na visualização para clientes que participam do <a href="https://insider.windows.com/">Programa Windows Insider</a>.  </li>
<li>  
 Para clientes que não são do Windows Insider no Windows 10 versão 2004 (ou posterior), o Arm64 Photoshop tem suporte usando o OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">o OpenGL Compatibility Pack.</a> 
  </li>
<li>  
  Os clientes no Programa Windows Insider podem baixar uma versão insider do OpenCL e do OpenGL Compatibility Pack para uso com aplicativos adicionais.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Se seus aplicativos web ou sites funcionarem no Internet Explorer 11, versões com suporte do Google Chrome ou qualquer versão do Microsoft Edge, eles também funcionarão com o Microsoft Edge.  
  </li>
<li>  
  Como a Web está em constante evolução, revise esta lista publicada de alterações conhecidas que impactam a compatibilidade do <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site para o Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Área de Trabalho Virtual do Windows</strong>  
<ul>
<li>  
  Aplicativos virtualizados executados em um Host de Sessão de Área de Trabalho Remota do Windows Server (RDSH) também são executados no Windows 10 Enterprise multisessão como parte da Área de Trabalho Virtual do Windows.  
  </li>
<li>  
  Aplicativos em execução em qualquer ambiente de infraestrutura de área de trabalho virtual (VDI) do Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.  
  </li>
<li>  
  Aplicativos em execução em dispositivos cliente Windows 7 ou Windows 10 também são executados no Windows 7 Enterprise e no Windows 10 Enterprise como parte da Área de Trabalho Virtual do Windows.  
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

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Serviço</strong></th>
<th><strong>Detalhes da orientação do FastTrack</strong></th>
<th><strong>Expectativas do ambiente de origem</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Fornecemos orientação e compatibilidade de implantação remota e adoção para: <ul> <li>Implantando o Microsoft Edge no Windows 10 com o Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).  </li>
<li>  Configurando o Microsoft Edge (usando políticas de grupo ou configuração de aplicativos do Intune e políticas de aplicativo).  </li>
<li>  Inventário da lista de sites que podem exigir uso no modo Internet Explorer.  </li>
<li>  Habilitação do modo do Internet Explorer com a lista de sites corporativos existente. (Para obter mais informações, consulte <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>). Além disso, se você tiver um aplicativo Web ou um site que funciona com o Internet Explorer ou com o Google Chrome e tiver problemas de compatibilidade, fornecemos orientações para resolver o problema sem custo adicional. Para solicitar suporte de compatibilidade para o App Assure, entre no <a href="https://fasttrack.microsoft.com/portal#/signin">portal do FastTrack</a> para iniciar um envolvimento.  </li>
<li> Diretrizes de planejamento para adoção de borda e orientação de configuração para indicadores da Pesquisa da Microsoft.</li>
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

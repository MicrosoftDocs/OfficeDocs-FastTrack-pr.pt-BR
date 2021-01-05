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
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> O Microsoft 365 defender é um pacote de defesa de negócios unificado de pré e pós-violação que coordena nativamente a detecção, prevenção, investigação e resposta entre pontos de extremidade, identidades, email e aplicativos para fornecer proteção integrada contra ataques sofisticados. Fornecemos orientações remotas para: </p> 
<ul>
<li>  Fornecer uma visão geral da central de segurança do Microsoft 365.  </li>
<li>  Análise de incidentes entre produtos, incluindo o foco no que é crítico ao garantir o escopo completo dos ataques, os ativos impactados e as ações de correção automatizadas que são agrupadas.  </li>
<li>  Demonstrar como o Microsoft 365 defender pode orquestrar a investigação de ativos, usuários, dispositivos e caixas de correio que podem ter sido comprometidos por meio da auto-recuperação automatizada. </li>
<li>  Explicando e fornecendo exemplos de como os clientes podem procurar proativamente tentativas de invasão e atividades de violação que afetam seus emails, dados, dispositivos e contas em vários conjuntos de dados.   </li>
<li> Mostrando aos clientes como eles podem revisar e aprimorar a postura de segurança de forma holística, usando a pontuação segura da Microsoft.</li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li> Gerenciamento de projetos das atividades de correção do cliente. </li>
<li> Gerenciamento contínuo, resposta a ameaças e remediação. </li>
<li> Orientações de implantação ou educação em:
<ul>
<li> Como corrigir ou interpretar os vários tipos de alerta e atividades monitoradas. </li>
<li> Como investigar um usuário, computador, caminho de movimento lateral ou entidade. </li>
<li> Busca da ameaça personalizada.  </li>
</ul>
</li>
<li> Gerenciamento de eventos e informações de segurança (SIEM) ou integração com a API.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  O Microsoft Cloud app Security é um CASB (agente de segurança de acesso à nuvem) que oferece visibilidade rica, controle sobre a viagem de dados e análises sofisticadas para identificar e combater ameaças de terceiros em todos os serviços de nuvem da Microsoft e de terceiros. Fornecemos orientações remotas para:
<ul>
<li>  Configuração do portal, incluindo:  </li>
<ul>
<li> Importação de grupos de usuários.</li>
<li> Gerenciamento de acesso e configurações de administrador.  </li>
<li> Escopo sua implantação para selecionar determinados grupos de usuários para monitorar ou excluir do monitoramento.</li>
<li> Definindo intervalos e marcas de IP.</li>
<li> Personalizar a experiência do usuário final com o logotipo e a mensagem personalizada.</li>
</ul>
<li> Configurando a descoberta de nuvem para fornecer sombras usando:</li>
<ul>
<li> Microsoft defender para pontos de extremidade.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Conexão de <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">aplicativos em destaque</a> usando os conectores de aplicativos.</li>
<li> Configuração do controle de aplicativo de acesso condicional nos portais de acesso condicional e do Cloud app Security para aplicar controles de sessão em tempo real.</li>
<li> Implantação do Cloud app Security and Cloud Discovery Dashboards.</li>
<li> Personalizando pontuações de risco de aplicativo com base nas prioridades da sua organização.</li>
<li> Criação de Tags e categorias de aplicativos.</li>
<li> Aplicativos de sanções e desaprovados.</li>
<li> Usando os logs de atividade e de arquivo.</li>
<li> Gerenciamento de aplicativos OAuth.</li>
<li> Noções básicas sobre correlação de incidentes no portal do Microsoft 365 defender.</li>
<li> Fornecer assistência de configuração com os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos de uso principais para o CASBs</a> (incluindo a criação ou a atualização de até seis (6) políticas), exceto: </li>
<ul>
<li> A auditoria da configuração de seus ambientes de Internet como serviço (IaaS) (#18).</li>
<li> Monitorar as atividades do usuário para proteger contra ameaças em seus ambientes IaaS (#19).</li>
</ul>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>
<li> Gerenciamento de projetos das atividades de correção do cliente.</li>
<li> Gerenciamento contínuo, resposta a ameaças e remediação. </li>
<li> Configuração da infraestrutura, instalação ou implantação de carregamentos automáticos de logs para relatórios contínuos usando o Docker ou um coletor de logs. Veja os <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos de uso do CASBs</a> para obter mais detalhes.</li>
<li> Criar um relatório de instantâneo de descoberta de nuvem.</li>
<li> Bloqueio do uso do aplicativo usando scripts de bloco.</li>
<li> Conexão de aplicativos personalizados.</li>
<li> Integração com provedores de identidade de terceiros (IsPs) e provedores de prevenção de perda de dados (DLP).</li>
<li> Treinamento ou orientação sobre a caça avançada.</li>
<li> Investigação e correção automatizadas, incluindo o Microsoft Power Automated manuals.</li>
<li> Gerenciamento de eventos e informações de segurança (SIEM) ou integração com a API (incluindo o Azure Sentinel).</li>
<li> Implantação do Cloud app Security como uma prova de conceito.</li>
</ul></td>
</tr>



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

<tr class="odd">
<td><strong>Microsoft defender para identidade </strong></td>
<td>  O Microsoft Defender para Identidade é uma solução de segurança baseada em nuvem que aproveita os sinais do Active Directory local para identificar, detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas direcionadas à sua organização. Fornecemos orientações remotas para:
<ul>
<li>   Criar sua instância do defender para identidade. </li>
<li>   Conexão do defender para identidade ao Active Directory. </li>
<li>   Avaliar a prontidão do seu ambiente para implantar o defender for Identity sensor nos seus controladores de domínio, incluindo:</li>   
<ul> 
<li>  Executar a ferramenta de dimensionamento para o planejamento de capacidade de recurso. </li>
<li>  Executar a ferramenta de auditoria para avaliar a compatibilidade dos controladores de domínio com o sensor. </li>
</ul>
<li>  Implantar o sensor para capturar e analisar o tráfego de rede e eventos do Windows diretamente de seus controladores de domínio, incluindo: </li>
<ul> 
<li>  Baixar o pacote do sensor. </li>
<li>  Configurando o sensor. </li>
<li>  Instalação silenciosa do sensor no seu controlador de domínio. </li>
<li>  Implantação do sensor no seu ambiente de várias florestas. </li>
</ul>
<li>  Integração do defender for Identity com o Microsoft Cloud app Security (o licenciamento do Cloud app Security não é necessário). </li>
<li>  Fornecer orientações de implantação, assistência de configuração e educação em: </li>
<ul>
<li> Ajustar o ambiente para reduzir o "ruído".  </li>
<li>  Noções básicas sobre o relatório de avaliação de postura de segurança de identidade. </li>
<li>  Noções básicas sobre a pontuação de prioridade de investigação de usuário e o relatório de classificação de investigação de usuário </li>
<li> Noções básicas sobre o relatório de usuário inativo.  </li>
<li> Fornecer opções de correção em uma conta comprometida.  </li>
</ul>
<li>  Facilitar a migração da análise avançada contra ameaças (ATA) para o defender para identidade. </li>
</ul>
<p><strong>O seguinte está fora do escopo</strong></p>
<ul>

<li> Gerenciamento de projetos das atividades de correção do cliente. </li>
<li> Gerenciamento contínuo, resposta a ameaças e remediação.  </li>
<li> Implantação do sensor do defender for Identity, incluindo: </li>
<ul>
<li> Planejamento manual da capacidade. </li>
<li> Implantação do sensor em uma capacidade autônoma. </li>
<li> Implantação do sensor usando um adaptador de equipe da placa de interface de rede (NIC). </li>
<li> Implantação do sensor por meio de uma ferramenta de terceiros. </li>
<li> Conectar-se ao defender para o serviço de nuvem de identidade por meio de uma conexão de proxy da Web. </li>
</ul>
<li> Criação e gerenciamento do honeytokens. </li>
<li> Orientações de implantação ou educação em: </li>
<ul>
<li> Correção ou interpretação de vários tipos de alerta e atividades monitoradas.  </li>
<li> Investigar um usuário, computador, caminho de movimento lateral ou entidade. </li>
<li> Ameaça ou busca avançada. </li>
<li> Resposta de incidente. </li>
</ul>
<li> Fornecer um tutorial de laboratório de alerta de segurança para defender para identidade. </li>
<li> Fornecer notificações quando o defender para identidade detecta atividades suspeitas enviando alertas de segurança para seu servidor syslog por meio de um sensor indicado.  </li>
<li> Configurando o defender para identidade para realizar consultas usando o protocolo SAMR (Gerenciador de contas de segurança) para identificar administradores locais em máquinas específicas. </li>
<li> Configurar soluções VPN para adicionar informações da conexão VPN à página de perfil de um usuário.  </li>
<li> Gerenciamento de eventos e informações de segurança (SIEM) ou integração com a API (incluindo o Azure Sentinel). </li>
<li> Implantar o defender para sensores de identidade como prova de conceito.</li>
</ul></td>
<td><ul>
<li>  Active Directory implantado.  </li>
<li>  Os controladores de domínio que você pretende instalar o defender para que os sensores de identidade têm conectividade com a Internet para o defender para o serviço de nuvem de identidade.  </li>
<ul>
<li> O firewall e o proxy devem estar abertos para se comunicar com o defender para o serviço de nuvem de identidade (*. atp.azure.com a porta 443 deve estar aberta).</li>
</ul>
<li> Controladores de domínio em execução em um dos seguintes:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 com KB4487044 (so Build 17763,316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Governança de informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Rótulos e diretivas de retenção.  </li>
<li>  Gerenciamento de registros.  </li>
<li>  Diretivas de exclusão.  </li>
<li>  Conformidade da comunicação.  </li>
<li>  Gerenciamento de risco interno.  </li>
<li>  Descoberta Eletrônica Avançada.  </li>
</ul>

  <strong>O seguinte está fora do escopo </strong>  
<ul>
<li> Desenvolvimento de um plano de arquivo de gerenciamento de registros.</li>
<li> Conectores de dados.</li>
<li> Barreiras de informação.</li>
<li> Gerenciamento de acesso privilegiado.</li>
<li> Desenvolvimento da arquitetura de informações no SharePoint.</li>
<li> Script e codificação personalizados.</li>
</td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
</tr>
<tr class="odd">
<td><strong>Proteção de Informações da Microsoft</strong></td>
<td>  Fornecemos orientações remotas para:
<ul>
<li>  Classificação de dados.  </li>
<li>  Tipos de informações confidenciais.  </li>
<li>  Criação de rótulos de confidencialidade.  </li>
<li>  Aplicar rótulos de sensibilidade.  </li>
<li>  Rotulagem unificada.  </li>
<li>  Classificadores treináveis.  </li>
<li>  Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.  </li>
<li>  Publicar etiquetas usando políticas (manual e automática).  </li>
<li>  Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.  </li>
<li>  Criação de políticas de DLP de ponto de extremidade para dispositivos Windows 10.  </li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>Chave do cliente.</li>
<li>O desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</li>
<li>Criação ou modificação de dicionários de palavras-chave.</li>
<li>Script e codificação personalizados.</li>
</ul>
<strong>Observação:</strong> Confira mais informações em <strong> proteção de informações do Azure </strong> no <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
<ul>

</td>
<td>Com exceção da parte <strong>Central de integração</strong> em <a href="#general">Geral</a>, não há requisitos mínimos do sistema.</td>
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


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Serviço</strong></TD>
<TD width 50%><strong>Detalhes da orientação do FastTrack</strong></TD>
<TD width 25%><strong>Expectativas do ambiente de origem</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>
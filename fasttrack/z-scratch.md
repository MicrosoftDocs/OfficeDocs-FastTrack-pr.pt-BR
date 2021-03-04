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
<tr class="even">
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
<li> Conectando <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">aplicativos em destaque</a> usando conectores de aplicativo.</li>
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
<li> Implantando o Cloud App Security como prova de conceito.</li>
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
<li> Barreiras de informações.</li>
<li> Gerenciamento de acesso privilegiado.</li>
<li> Desenvolvimento da arquitetura de informações no SharePoint.</li>
<li> Scripts personalizados e codificação.</li>
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
<li>  Aplicando rótulos de sensibilidade.  </li>
<li>  Rotulagem unificada.  </li>
<li>  Classificadores treináveis.  </li>
<li>  Conhecer seus dados com o explorador de conteúdo e o explorador de atividade.  </li>
<li>  Publicar etiquetas usando políticas (manual e automática).  </li>
<li>  Criação de políticas de proteção contra perda de dados (DLP) em bate-papos e canais do Microsoft Teams.  </li>
<li>  Criando políticas de DLP de ponto de extremidade para dispositivos Windows 10.  </li>
</ul>

<strong>O seguinte está fora do escopo </strong>  
<ul>
<li>Chave do cliente.</li>
<li>Desenvolvimento de expressões regulares personalizadas (RegEx) para tipos de informações confidenciais.</li>
<li>Criação ou modificação de dicionários de palavras-chave.</li>
<li>Scripts personalizados e codificação.</li>
</ul>
<strong>Observação:</strong> Para obter mais informações, consulte <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
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


</tbody>
</table>












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
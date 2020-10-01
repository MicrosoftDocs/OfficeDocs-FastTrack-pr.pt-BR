---
title: Migração de dados
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). O tipo de assistência que fornecemos depende do número de licenças do Office 365.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319943"
---
# <a name="data-migration"></a>Migração de dados

O FastTrack pode ajudar a migrar emails e dados de arquivos em seus ambientes de origem para o Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).

O tipo de assistência que fornecemos depende do número de licenças do Office 365:

  - **Os locatários do Office 365 com as licenças 150-499**: Você é responsável pela realização da migração de dados, FastTrack somente fornece diretrizes de migração. Vamos orientá-lo na documentação que ajuda a planejar e usar as ferramentas gratuitas para executar uma migração de autoatendimento.
  - **Os locatários do Office 365 com a 500 ou mais licenças**: FastTrack fornece diretrizes de migração e serviços de migração de dados. Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o locatário do Office 365 e aproveitar nossos serviços de migração de dados para migrar seus dados. Você cria e agenda seus eventos de migração. Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status.

> [!NOTE]
> Se comprou ou renovou um plano comercial do antes de 1/9/2017, você precisa de apenas 150 licenças para se qualificar para os serviços de migração de dados. Para os planos educacionais, somente professores e funcionários estão qualificados para serviços de migração.

### <a name="considerations"></a>Considerações

  - Seus ambientes de origem devem atender a expectativas específicas para migrar os dados para o Office 365. Confira o [Produtos e recursos](products-and-capabilities.md) para obter mais informações sobre as expectativas do ambiente de origem do Exchange, do Microsoft Office SharePoint Online e do OneDrive for Business.
  - Exigimos acesso e permissões apropriados para os seus ambientes de origem e o locatário do Office 365 para fornecer serviços de migração de dados.
  - Nossos serviços de migração de dados não foram projetados nem destinam-se a dados sujeitos a requisitos normativos e legais. À medida que migramos os dados, eles podem ser transferidos para o, armazenados e processados em qualquer lugar, onde mantivemos as instalações (exceto as fornecidas para seu projeto de migração do FastTrack).
  - Não podemos garantir a velocidade de migração emails ou arquivos.
  - Os problemas inesperados (como itens ilegíveis ou indesejados no ambiente de origem) podem impedir a migração de alguns de seus itens de dados.
  - Os fatores externos além de nosso controle (como as alterações feitas em interfaces de programação de aplicativos de terceiros (APIs)) podem resultar em alterações no, atrasos ou suspensão de nossos serviços de migração de dados.

### <a name="migration-service-availability"></a>Disponibilidade do serviço de migração

  - **Para clientes governamentais comerciais e do Reino Unido:** Fornecemos serviços de migração de dados 24 horas por dia, sete (7) dias por semana (24x7).
  - **Para os clientes do Governo dos EUA/DOD:** Fornecemos serviços de migração de dados 24 horas por dia, cinco (5) dias úteis por semana (24x5).

## <a name="migration-to-exchange-online"></a>Migração para o Exchange Online

Quando você escolhe usar o FastTrack para migrar seu email para o Exchange Online, fornecemos diretrizes de migração e serviços de migração de dados. Fornecemos orientações que ajudam a planejar sua migração, configurar seus ambientes de origem e o Exchange Online, além de aproveitar nossos serviços de migração de dados para migrar suas caixas de correio. Você cria e agenda seus eventos de migração. Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status. Quando os eventos de migração estiverem concluídos, você poderá esperar que os emails de caixas de correio de origem agendadas e qualificadas apropriadamente sejam migrados para o Exchange Online.

### <a name="considerations"></a>Considerações

  - Antes da migração, você deve concluir a integração principal do FastTrack para o Exchange Online;
      - Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários. Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.
  - O FastTrack migra apenas para caixas de correio do Office 365 ativas.
  - Você deve atender a requisitos específicos se pretende migrar de um ambiente do Exchange local. Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.
  - Cada ambiente de origem deve estar no nível mais recente do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa para o respectivo produto no ambiente de origem.
  - Se as listas de distribuição (objetos *MailEnabledGroup*) e contatos externos (*objetos MailEnabledContact*) estão no Active Directory local não fazem parte da migração de dado da caixa de correio. No entanto, você pode sincronizá-los usando o Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Ambientes de origem

Nosso serviço de migração de dados migra os dados desses ambientes de origem:

  - Uma ou várias florestas do Active Directory com uma ou várias organizações do Exchange (cada sistema de email do Exchange deve ser Exchange 2010 ou posterior).
  - Um ambiente de email único compatível com IMAP.
  - Ambiente do G Suite (apenas Gmail, Contatos e Calendário)

A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:

<table>
<thead>
<tr class="header">
<th><strong>Ambiente de origem</strong></th>
<th><strong>Tipo de migração</strong></th>
<th><strong>O que migra</strong></th>
<th><strong>O que não migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Observação:</strong>  Para dependências do Exchange local, confira  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Pré-requisitos de implantação híbrida</span></a>.</td>
<td>Migração com implantação híbrida</td>
<td><ul>
<li>Emails</li>
<li>Regras de caixas de correio</li>
<li>Representantes</li>
<li>Contatos de caixas de correio </li>
<li> Calendário </li>
<li> Tarefas </li>
<li> Emails gerenciados por direitos </li>
<li> Emails criptografados </li>
<li> Assinaturas </li>
<li> Arquivo morto pessoal migrado com caixas de correio de usuários </li>
<li> Itens recuperáveis </li>
</ul></td>
<td><ul>
<li> Pastas públicas </li>
<li> Qualquer email que excede o limite de tamanho da mensagem </li>
<li> Arquivo morto de registro em diário ou solução de arquivo morto de terceiros </li>
<li> Usuários bloqueados ou inativos </li>
<li> Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal) </li>
<li> Itens corrompidos </li>
<li> Caixas de correio inativas </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ambiente do G Suite (apenas Gmail, Contatos e Calendário)</strong><br />
<br />
<strong>Observação:</strong> Seu ambiente do G Suite deve atender aos pré-requisitos descritos em <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Executar uma migração G Suite</a>.</td>
<td>De substituição ou em fases</td>
<td><ul>
<li> Emails </li>
<li> Contatos de caixa de correio (no máximo 3 endereços de email por contato são migrados) </li>
<li> Calendário </li>
<li> Rótulos </li>
</ul></td>
<td><ul>
<li> Regras </li>
<li> Representantes </li>
<li> Assinaturas </li>
<li> Tarefas </li>
<li> Todos os emails ou anexos que excedem o limite de tamanho da mensagem </li>
<li> Usuários bloqueados ou inativos </li>
<li> Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault) </li>
<li> Direitos gerenciados ou emails criptografados </li>
<li> Itens corrompidos </li>
<li> Google Hangouts** </li>
<li> Grupos do Google </li>
<li> Caixas de correio de recurso </li>
<li> Caixas de correio inativas </li>
<li> Configurações de férias e configurações de resposta automática </li>
<li> Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento </li>
</ul>
**As conversas do Hangout salvas como rótulo são migradas. </td>
</tr>
<tr class="odd">
<td><strong>Origem IMAP4 (como Domino, GroupWise e Zimbra)</strong></td>
<td>Migração usando ferramentas nativas de IMAP4</td>
<td><li>Emails </li></td>
<td><ul>
<li> Regras </li>
<li> Representantes </li>
<li> Listas de distribuição </li>
<li> Contatos externos </li>
<li> Usuários habilitados para email </li>
<li> Usuários bloqueados ou inativos </li>
<li> Contatos de caixas de correio </li>
<li> Calendário </li>
<li> Assinaturas </li>
<li> Tarefas </li>
<li> Qualquer email que excede o limite de tamanho da mensagem </li>
<li> Dados de arquivo morto </li>
<li> Email criptografado </li>
<li> Itens corrompidos </li>
<li> Caixas de correio inativas </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades do FastTrack

Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.

Os especialistas do FastTrack também realizam as seguintes atividades, específicas das migrações do Exchange:

  -  Fornecem orientação para ajudar a habilitar a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.

## <a name="your-responsibilities"></a>Suas responsabilidades

Você realiza atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.

Você também realiza as seguintes atividades, específicas das migrações do Exchange:

  - Concluir a integração principal do FastTrack para o Exchange Online. Se você tiver feito a integração por conta própria, deverá passar as verificações e os pré-requisitos necessários. Confira [Produtos e recursos](products-and-capabilities.md) para obter detalhes.
  -  Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365. Confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) para obter detalhes.
  -  Atender a requisitos específicos se você pretende migrar de um ambiente do Exchange local. Confira [Pré-requisitos de Implantação Híbrida](https://go.microsoft.com/fwlink/?LinkId=787528) para obter detalhes.
  -  Garanta que todos os ambientes de origem estejam no nível de atualização do Service Pack (SP) e atualização do pacote cumulativo/atualização cumulativa mais recente, se aplicável.
  -  Configure e valide a coexistência de roteamento de email SMTP entre seus ambientes de origem e o Exchange Online, se aplicável.
  -  Verifique se o tamanho da caixa de correio de origem não ultrapassa a cota de destino. Dependendo da plataforma de origem, talvez seja necessário limitar os dados de origem para 85% da cota de caixa de correio de destino.
  -  Migrar dados do lado do cliente se desejar. Isso inclui, mas não se limita a, catálogos de endereços locais, dados em arquivos PST locais, regras do Outlook e configurações locais do Outlook.
  -  Auxilie seu usuários finais com a correção de problemas de migração do lado do cliente.

## <a name="migration-to-sharepoint-online"></a>Migração para o SharePoint Online

Quando você escolhe usar o FastTrack para migrar seus arquivos para o SharePoint Online, fornecemos diretrizes de migração e serviços de migração de dados. Fornecemos orientações para ajudá-lo a planejar a migração, configurar os ambientes de origem e o SharePoint Online e aproveitar nossos serviços de migração de dados para migrar seus arquivos. Você cria e agenda seus eventos de migração. Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status. Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o SharePoint Online.

## <a name="considerations"></a>Considerações

  - Todas as migrações estão sujeitas a cotas do SharePoint Online. Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.
  - É recomendável limitar o valor total de migrar para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).

## <a name="source-environment-details"></a>Detalhes do ambiente de origem

Nossos serviços de migração de dados migram os dados desses ambientes de origem:

  - Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).
  - Um único ambiente do G Suite (apenas Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox para equipes (Padrão e Avançado).

A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:

<table>
<thead>
<tr class="header">
<th><strong>Ambiente de origem</strong></th>
<th><strong>Tipo de migração</strong></th>
<th><strong>O que migra</strong></th>
 <th><strong>O que não migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões de arquivo e pasta no nível do usuário* </li>
<li> Permissões de arquivo e pasta no nível do grupo* </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
</ul>
*Configuração de sincronização de diretório necessária. Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas. As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas. Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.</td>
<td><ul>
<li> Histórico de propriedade e versões anteriores </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Versões anteriores </li>
<li> Atributos de arquivos e pastas do Windows (como somente leitura e oculto) </li>
<li> Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS: </li>
<li> Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai) </li>
<li> Configuração de auditoria do NTFS </li>
<li> Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos) </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Compartilhamentos ocultos </li>
<li> Compartilhamento (como permissões concedidas no nível de compartilhamento) </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Unidades compartilhadas (pastas e arquivos) </li>
<li> Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas, cores de pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Usuários bloqueados ou inativos </li>
<li> Google Fotos, Formulários, Mapas e outras aplicações conectadas </li>
<li> Google Drawings </li>
<li> Conteúdo compartilhado externo à sua organização </li>
<li> O conteúdo que está sendo migrado não pertencente à conta Google Drive </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração). </li>
<li> Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive. Instrua os usuários finais a definir essas configurações de associação no destino antes da migração). </li>
<li> Arquivos marcados como restritos ou não copiados </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Conteúdo compartilhado de propriedade da conta do Box está sendo migrado </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Box Tags e metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Usuários bloqueados ou inativos </li>
<li> Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho </li>
<li> O conteúdo não pertence à conta do Box migrada </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração). </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox para equipes (Padrão e Avançado)</strong> </td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Pastas e conteúdos compartilhados pela equipe </li>
<li> Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Pastas Dropbox não montadas </li>
<li> Usuários excluídos ou desconectados </li>
<li> Dropbox Paper, Showcases e Spaces </li>
<li> Dropbox Aplicativos e Favoritos (Pins/Stars) </li>
<li> O conteúdo não pertence à conta Dropbox migrada </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração) </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades do FastTrack

Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes

## <a name="your-responsibilities"></a>Suas responsabilidades

Você realiza atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes

Você também realiza as seguintes atividades, especificamente para migrações do SharePoint Online:

  - Provisionar todos os sites de equipe do Microsoft Office SharePoint Online para ser direcionado a seus eventos de migração.

## <a name="migration-to-onedrive-for-business"></a>Migração para o OneDrive for Business

Quando você escolhe usar o FastTrack para migrar seus arquivos para o OneDrive for Business, fornecemos diretrizes de migração e serviços de migração de dados. Fornecemos orientações que ajudam a planejar sua migração, configurar os ambientes de origem e o OneDrive for Business e aproveitar nossos serviços de migração de dados para migrar seus arquivos. Você cria e agenda seus eventos de migração. Iniciamos os eventos de migração de acordo com sua agenda, monitoramos o progresso dele e fornecem relatórios de status. Quando os eventos de migração estiverem concluídos, você poderá esperar arquivos de fontes agendadas e qualificadas apropriadamente dos seus ambientes de origem para migrar para o OneDrive for Business.

## <a name="considerations"></a>Considerações

  - Todas as migrações estão sujeitas a cotas do OneDrive for Business. Confira [<span class="underline">O SharePoint Online e o OneDrive for Business: delimitações e limites de software</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obter detalhes.
  - É recomendável limitar o valor total que você migra para 75% da cota de armazenamento geral do SharePoint Online à qual você está qualificado (incluindo o armazenamento adicional que pode ter comprado separadamente).
  - O FastTrack migra apenas para o unidades do OneDrive for Business ativas.

## <a name="source-environment-details"></a>Detalhes do ambiente de origem

Nossos serviços de migração de dados migram os dados desses ambientes de origem:

  - Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).
  - Ambiente único do G Suite (apenas Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox para equipes (Padrão e Avançado).

A tabela a seguir apresenta detalhes de migração específicos para cada ambiente de origem:

<table>
<thead>
<tr class="header">
 <th><strong>Ambiente de origem</strong></th>
 <th><strong>Tipo de migração</strong></th>
 <th><strong>O que migra</strong></th>
 <th><strong>O que não migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões de arquivo e pasta no nível do usuário* </li>
<li> Permissões de arquivo e pasta no nível do grupo* </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
</ul>
<br>
*Configuração de sincronização de diretório necessária. Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas. As permissões gerenciadas diretamente em dispositivos de compartilhamento de arquivos não são migradas. Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas. </td>
<td><ul>
<li> Histórico de propriedade e versões anteriores </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Versões anteriores </li>
<li> Atributos de arquivos e pastas do Windows (como somente leitura e oculto) </li>
<li> Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS: </li>
<li> Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai) </li>
<li> Configuração de auditoria do NTFS </li>
<li> Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos) </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Compartilhamentos ocultos </li>
<li> Compartilhamento (como permissões concedidas no nível de compartilhamento) </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Um único ambiente do G Suite (apenas Google Drive)</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB) </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Unidades compartilhadas (pastas e arquivos) </li>
<li> Conteúdo compartilhado pertencente à conta do Google Drive sendo migrada </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas, cores de pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Usuários bloqueados ou inativos </li>
<li> Google Fotos, Formulários, Mapas e outros aplicativos conectados </li>
<li> Google Drawings </li>
<li> Conteúdo compartilhado externo à sua organização </li>
<li> O conteúdo que está sendo migrado não pertencente à conta Google Drive </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração). </li>
<li> Permissões de associação compartilhadas do Drive (<strong>Observação</strong>: Use relatórios do administrador do Google Drive para identificar as associações compartilhadas do Drive. Instrua os usuários finais a definir essas configurações de associação no destino antes da migração). </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Conteúdo compartilhado de propriedade da conta do Box está sendo migrado </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Box Tags e metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Usuários bloqueados ou inativos </li>
<li> Os Aplicativos do Box, os Marcadores, os Favoritos e os Fluxos de trabalho </li>
<li> O conteúdo não pertence à conta do Box migrada </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Box para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração). </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox para equipes (Padrão e Avançado)</strong> </td>
<td>Uma ou várias passagens</td>
<td><ul>
<li> Documentos </li>
<li> Estrutura de arquivo e pasta </li>
<li> Permissões da pasta para o nível do Usuário </li>
<li> Permissões da pasta para o nível do Grupo </li>
<li> Arquivos com menos de 15 GB </li>
<li> Metadados básicos de documentos e pastas:
<ul>
<li> Data de criação </li>
<li> Data de modificação </li>
<li> Criado por </li>
<li> Última modificação por </li>
</ul></li>
<li> Pastas e conteúdos compartilhados pela equipe </li>
<li> Conteúdo compartilhado de propriedade da conta do Dropbox está sendo migrado </li>
</ul></td>
<td><ul>
<li> Histórico de propriedade, versões anteriores e comentários </li>
<li> Descrições de arquivos e pastas </li>
<li> Permissões do arquivo para o nível do Usuário </li>
<li> Permissões do arquivo para o nível do Grupo </li>
<li> Metadados avançados </li>
<li> Atributos de bloqueio de arquivo </li>
<li> Conversão de URLs incorporados em conteúdo </li>
<li> Itens na lixeira </li>
<li> Documentos inacessíveis ou corrompidos </li>
<li> Pastas Dropbox não montadas </li>
<li> Usuários excluídos ou desconectados </li>
<li> Dropbox Paper, Showcases e Spaces </li>
<li> Dropbox Aplicativos e Favoritos (Pins/Stars) </li>
<li> O conteúdo não pertence à conta Dropbox migrada </li>
<li> Permissões e metadados básicos de usuários externos (<strong>Observação</strong>: Use relatórios do Dropbox para identificar conteúdo compartilhado com usuários externos. Instrua os usuários finais a recompartilhar o conteúdo com usuários externos após a migração). </li>
<li> Arquivos ou pastas que excedem as  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restrições e limitações atuais do SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades do FastTrack

Os especialistas do FastTrack realizam atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.

## <a name="your-responsibilities"></a>Suas responsabilidades

Você realiza atividades padrão durante o projeto de migração. Confira as informações sobre responsabilidades de migração de dados no [Processo e expectativas](process-and-expectations.md) para obter detalhes.

Você também executa as seguintes atividades, específicas das migrações do OneDrive for Business:

  - Configure todos os sites do OneDrive for Business que serão direcionados para os seus eventos de migração.

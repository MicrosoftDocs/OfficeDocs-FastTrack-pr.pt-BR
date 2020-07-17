---
title: Migração de dados
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Os Especialistas FastTrack fornecem orientações sobre etapas para migração de dados no Office 365. Isso está disponível para todos os clientes qualificados com serviços do Office 365 do Exchange Online, OneDrive for Business e SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011305"
---
# <a name="data-migration"></a>Migração de dados

Você pode ter informações nos seus ambientes de origem os quais você queira migrar para o Office 365.

**Para locatários do Office 365 com 150-499 licenças:** Fornecemos orientações utilizando uma combinação de ferramentas e documentação para que a sua migração ocorra da forma suave e eficiente. 

**Para locatários do Office 365 com 500 ou mais licenças\*:** Os serviços de migração de dados estão disponíveis para Exchange Online, SharePoint Online, e OneDrive for Business. O seu benefício FastTrack inclui o fornecimento de orientações para a integração com o ambiente de origem e a migração dos seus dados.
  
\*Se você adquiriu ou renovou um plano comercial antes de 01/09/2017, 150 assentos é a exigência de assentos mínimos durante todo o período de assinatura atual para receber o benefício de migração. Para planos de educação, apenas as licenças pagas de professores e funcionários são elegíveis para serviços de migração. 
  
> [!NOTE]
> Os dados migrados por meio dos serviços do FastTrack podem ser transferidos, armazenados ou processados em qualquer lugar em que a Microsoft mantenha instalações (exceto se estabelecido de outra forma para seu contrato específico do FastTrack). Os serviços do FastTrack não são projetados para dados sujeitos a requisitos regulamentares ou a leis especiais e não se destinam a eles. 
  
> [!NOTE]
> Problemas imprevistos (incluindo, mas não se limitado a itens corrompidos ou ilegíveis no ambiente de origem) podem impedir a migração de alguns itens. 
  
> [!NOTE]
> A assistência de migração está disponível em alemão, chinês simplificado e tradicional (os recursos falam apenas mandarim), espanhol, francês, inglês, italiano, japonês e português (Brasil). 
  
> [!NOTE]
> Se a integração for necessária, seu ambiente de origem deverá estar em um nível mínimo para esse aplicativo. 
  
> [!NOTE]
> Novidades de março de 2020, a Microsoft está disponibilizando licenças de avaliação de seis meses do [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) e [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) para auxiliar o trabalho remoto e o aprendizado conforme os clientes respondem à epidemia COVID-19. Como exceção, o FastTrack está disponibilizando serviços de migração de dados para locatários com 500 ou mais licenças de avaliação e o [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) para estudantes, de março de 2020 a agosto de 2020. A Microsoft se reserva o direito de cancelar, alterar ou suspender essa oferta a qualquer momento, sem aviso prévio.

A tabela a seguir descreve o que deve ser migrado em seu ambiente de origem existente.
  

|**Atividade**|**Expectativa de ambiente de origem**|
|:-----|:-----|
|**Migração do Exchange Online**  <br/> | A Microsoft migra qualquer combinação dos ambientes de origem listados abaixo, um de cada vez. Podemos migrar o sistema de mensagens integrado usando o Centro FastTrack ou se tiver passado nas verificações do Centro FastTrack, o que inclui:  <br/>  Uma única floresta do Active Directory ou várias com uma única organização do Exchange ou várias, se um Exchange 2010 híbrido ou posterior é implementado em cada organização e sistemas do correio do Exchange são 2003 ou posterior.  <br/>  Um ambiente de email único compatível com IMAP.  <br/>  Ambientes do G Suite (apenas Gmail, Contatos e Agenda) <br/> <br/> **Observação** *A integração do Exchange Online deve ser concluída antes da migração.* <br/> <br/> **Observação** *O FastTrack migra apenas para caixas de correio ativas do Office 365.* <br/> <br/> **Observação** *Para dependências do Exchange local, confira [Pré-requisitos de implantação híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Observação** *Ao migrar vários ambientes de mensagem de origem (como várias organizações do Exchange ou domínios Domino), essas migrações ocorrem de forma sequencial.*| 
|**Migração do SharePoint Online**  <br/> | Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante). <br/> Ambiente único do G Suite (apenas Google Drive).<br/>  Box (Starter, Business, Enterprise).  <br/> Dropbox para equipes (Padrão e Avançado).<br/> |
|**Migração do OneDrive for Business**  <br/> | Compartilhamentos de arquivos (compartilhamentos de arquivos com protocolo SMB em dispositivos compatíveis com SMB 2.0 em diante).  <br/>  Ambiente único do G Suite (apenas Google Drive).  <br/>  Box (Starter, Business, Enterprise). <br/> Dropbox para equipes (Padrão e Avançado).<br/><br/> **Observação** *O FastTrack migra apenas para unidades ativas do Office 365.*|
   
## <a name="migration-to-exchange-online"></a>Migração para o Exchange Online
''
### <a name="enable-to-migrate"></a>Habilitar para migrar
  
Se você usar a Microsoft para migrar seu email, forneceremos orientações para habilitar o Exchange Online e o ambiente de origem para a migração. Podemos realizar diversas etapas de Habilitar, dependendo da origem. Damos orientações usando uma combinação de ferramentas e documentação, além de realizar tarefas de configuração, quando for aplicável e viável. Sujeito a parâmetros aplicáveis, migramos as caixas de correio, monitoramos trabalhos e fornecemos relatórios de status.
"A Microsoft pode exigir permissões e acesso apropriados ao seu sistema de email para realizar as atividades de migração.
  
### <a name="migration-policy-and-steps"></a>Etapas e políticas de migração
  
> [!NOTE]
> Um intervalo de tempo de migração também é chamado de lote de migração.

#### <a name="commercial-and-uk-government"></a>Comercial e governo do Reino Unido

As migrações são feitas 24 horas por dia, sete (7) dias por semana (24x7) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração.

#### <a name="us-governmentdod"></a>Governo dos EUA/DOD

As migrações são feitas 24 horas por dia, cinco (5) dias úteis por semana (24x5) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração. Existem cinco dias de migração em uma semana, das 2h de segunda-feira até a meia-noite de sexta-feira, no Tempo Universal Coordenado (UTC). Isso significa que a última migração programada ocorre às 20h (UTC) de sexta-feira.
    
 ### <a name="end-state"></a>Estado final
  
O estado final esperado após um lote de migração inclui:
- Os dados das caixas de correio de origem devidamente qualificados e programados no ambiente de origem são migrados para o Office 365. 
- Um relatório pós-migração do lote de migração fornecido pela Microsoft.
    
O estado final esperado depois que todas as migrações são concluídas:
- Os dados de caixas de correio de origem qualificada serão migrados para o Office 365 conforme definido na tabela a seguir.
- O tipo de dados a migrar varia de acordo com o ambiente de origem, conforme descrito na tabela a seguir.
    
> [!NOTE]
> Todos os ambientes de origem precisam estar no nível dos service packs (SP) e distribuição (RU)/atualização cumulativa (CU) mais recentes para o respectivo produto no ambiente de origem no final da fase Habilitar. Os serviços de migração de dados estão sujeitos a fatores externos além do controle da Microsoft, como alterações às interfaces de programação de aplicativo (APIs) de terceiros, que podem resultar em mudanças, atrasos ou suspensão desses serviços. Durante a apresentação dos serviços do FastTrack, os dados que você disponibilizar para a Microsoft poderão ser acessados de qualquer lugar em que a Microsoft e os fornecedores dela mantenham instalações. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente de origem**|**Tipo de migração**|**O que migrará da caixa de correio de origem**|**O que não pode ser migrado**|
|**Exchange 2003 em diante**|Substituição| Emails <br/> Regras de caixas de correio <br/> Representantes <br/> Contatos de caixas de correio <br/> Calendário <br/> Tarefas <br/> Emails gerenciados por direitos <br/> Emails criptografados| Pastas públicas <br/> Contatos pessoais <br/> Usuários habilitados para email <br/> Usuários bloqueados ou inativos <br/> Assinaturas <br/> Dumpster de caixas de correio <br/>  Qualquer email que excede o limite de tamanho da mensagem <br/> Dados de arquivo morto <br/> Itens corrompidos <br/>  Caixas de correio inativas |
|**Exchange 2003 e Exchange 2007**|Em estágios| Emails <br/> Regras de caixas de correio <br/> Representantes <br/> Contatos de caixas de correio <br/> Calendário <br/> Tarefas <br/> Emails gerenciados por direitos <br/> Emails criptografados| Pastas públicas <br/> Contatos pessoais <br/> Usuários habilitados para email <br/> Usuários bloqueados ou inativos <br/> Assinaturas <br/> Dumpster de caixas de correio <br/> Qualquer email que excede o limite de tamanho da mensagem <br/> Dados de arquivo morto <br/> Itens corrompidos <br/> Caixas de correio inativas |
|**Exchange 2010, Exchange 2013, Exchange 2016 e Exchange 2019** <br/><br/> **Observação** *Para dependências do Exchange local, confira [Pré-requisitos de implantação híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migração com implantação híbrida| Emails <br/> Regras de caixas de correio <br/> Representantes <br/> Contatos de caixas de correio <br/> Calendário <br/> Tarefas <br/> Assinaturas <br/> Arquivo morto pessoal migrado com caixas de correio de usuários <br/> Itens recuperáveis <br/> Emails gerenciados por direitos <br/> Emails criptografados| Pastas públicas <br/> Qualquer email que excede o limite de tamanho da mensagem <br/> Arquivo morto de registro em diário ou solução de arquivo morto de terceiros <br/> Usuários bloqueados ou inativos <br/> Dados de arquivo morto dos arquivos PST (tabela de armazenamento pessoal) <br/> Itens corrompidos <br/> Caixas de correio inativas |
|**Ambiente do G Suite (apenas Gmail, Contatos e Calendário)** <br/> <br/> **Observação** *Seu ambiente do G Suite precisa ter as APIs e o SDK Admin do Google habilitados para estender a funcionalidade.* <br/>          |De substituição ou em fases| Emails <br/> Contatos de caixas de correio\*  <br/> Calendário <br/> Rótulos <br/> \*No máximo três endereços de email por contato são migrados| Regras <br/> Representantes <br/> Assinaturas <br/> Tarefas <br/> Todos os emails ou anexos que excedem o limite de tamanho da mensagem <br/> Usuários bloqueados ou inativos <br/> Dados de arquivo morto de arquivos PST ou qualquer solução de arquivamento de terceiros (por exemplo, Google Vault) <br/> Direitos gerenciados ou emails criptografados <br/> Itens corrompidos <br/> Google Hangouts\*\* <br/> Grupos do Google <br/> Caixas de correio de recurso <br/> Caixas de correio inativas <br/> Configurações de férias e configurações de resposta automática <br/> Calendários compartilhados, anexos na nuvem, links do Google Hangout e cores do evento <br/>\*\*As conversas do Hangout salvas como rótulo são migradas |
|** Origem IMAP4 (como Domino, GroupWise e Zimbra) ** |Migração usando ferramentas nativas de IMAP4| Emails | Regras <br/> Representantes <br/> Listas de distribuição <br/> Contatos externos <br/> Usuários habilitados para email <br/> Usuários bloqueados ou inativos <br/> Contatos de caixas de correio <br/> Calendário <br/> Assinaturas <br/> Tarefas <br/> Qualquer email que excede o limite de tamanho da mensagem <br/> Dados de arquivo morto <br/> Email criptografado <br/> Itens corrompidos <br/> Caixas de correio inativas |
   
> [!NOTE]
> Se as listas de distribuição (objetos MailEnabledGroup) e contatos externos (objetos MailEnabledContact) estão no Active Directory no local, eles podem ser sincronizados usando o Azure AD Connect. No entanto, eles não são fazem parte da migração de dados de caixa de correio. Para saber mais, confira o exemplo **Integração de identidade** no [Core](O365-onboarding-and-migration.md#core). 
  
Os Especialistas do FastTrack executam as seguintes tarefas durante as migrações:
- Fornecer um modelo padrão para o agendamento de migrações de caixa de correio.
- Fornecer informações sobre as permissões necessárias para Especialistas da FastTrack. 
- Coletar um agendamento para a migração de caixas de correio predeterminadas no formatos predeterminados.
- Tentar realizar a migração de uma única caixa de correio até duas vezes em um lote de migração, antes de relatar essa caixa de correio como uma falha na migração.
- Para ambientes de origem no Exchange e baseados em IMAP4, migre o conteúdo da caixa de correio, até 85% do limite de armazenamento da caixa de correio do usuário (por exemplo, se o limite de armazenamento da caixa de correio for de 50 GB, a Microsoft migrará até 85% do limite de armazenamento de 50 GB). 
- Habilitar a coexistência de roteamento de email SMTP entre o ambiente de mensagens de origem e o Exchange Online do Office 365, a menos que esteja usando uma migração de substituição.
- Fornecer relatórios pós-migração.
- Fornecer assistência pós-migração para problemas críticos. Consideramos críticos os seguintes problemas:
  - Perda de dados durante a migração.
  - O ambiente de origem fica indisponível durante a migração.
  - As atividades de migração geram problemas no ambiente de origem.
    
Execute as seguintes tarefas durante as migrações:
- Conclua a integração do Exchange Online ou passe as verificações necessárias usando o Centro FastTrack.
- Tratar de todas as comunicações com usuários finais.  
- Instalar o nível apropriado do software do cliente conforme descrito nas diretrizes do Office 365. Para saber mais, confira [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Validar a coexistência de roteamento de email SMTP entre o ambiente de mensagens de origem e o Office 365 Exchange Online, quando aplicável.
- Fornecer um agendamento de um método definido e uma lista de caixas de correio específicas a migrar para cada evento de migração.
- Remover caixas de correio do agendamento até 24 horas antes do lote de migração. 
- Agendar uma média de destino de caixas de correio, em um período de 24 horas, conforme listado na tabela a seguir.
    
|||
|:-----|:-----|
|**Número de caixas de correio qualificadas para migração** <br/> |**Média mínima de caixas de correio em um período de 24 horas** <br/> |
|150-1000  <br/> |25% do total  <br/> |
|1001-5000  <br/> |20% do total  <br/> |
|5001-10000  <br/> |15% do total  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Esses números são baseados em práticas recomendadas. No entanto, o número de caixas de correio que migram por dia pode variar, de acordo com as restrições do ambiente, do negócio e da preparação. A Microsoft não pode garantir a velocidade de migração da caixa de correio. 
  
- Agende no mínimo 35 caixas de correio em um lote de migração. 
- Corrigir falhas de pré-migração (quando for o caso).  
- Fornecer acesso e permissões para o ambiente de origem a Especialistas da FastTrack para a realização de atividades de migração. 
- Adquirir e/ou fornecer contas administrativas licenciadas no Office 365 para realizar atividades de migração (conforme apropriado). 
- Fornecer assistência para problemas de migração do lado do cliente e executar operações pós-migração quando for necessário. 
- Migrar dados do lado o cliente, quando desejado. Isso inclui, dentre outros, catálogos locais de endereços, dados dos arquivos PST locais, regras do Outlook e configurações locais do Outlook.   
- Reduzir o tamanho da caixa de correio para menos de 85% do limite da caixa de correio do Office 365 de destino, quando for o caso.   
- Lidar com ações de um relatório de pós-migração, incluindo caixas de correio que não foram transferidas.  
- Corrigir falhas pós-migração e reagendar as caixas de correio (quando for o caso).   
- Participar da assistência pós-migração para problemas críticos. Consideramos críticos os seguintes problemas:
  - Perda de dados durante a migração.
  - O ambiente de origem fica indisponível durante a migração.
  - As atividades de migração geram problemas no ambiente de origem.
    
Você deve realizar o processo de migração padrão e estabelecer contato com a Microsoft adequadamente. Isso inclui fornecer acesso e permissões para o Office 365 e para os ambientes de origem, fornecer os agendamentos de migração, corrigir quaisquer causas de erros de migração, etc. Você deve também contatar os usuários finais para tratar das comunicações, agendamento de migração de caixas de correio e para lidar com problemas relacionados à migração.
  
> [!NOTE]
> As migrações só usam contas de acordo com os requisitos de segurança definidos durante a integração. Se você não usa essas contas, poderá passar por atrasos de migração. 
  
## <a name="migration-to-sharepoint-online"></a>Migração para o SharePoint Online

### <a name="enable-to-migrate"></a>Habilitar para migrar
  
Se usar a Microsoft para migrar seus dados, vamos fornecer orientação para habilitar o SharePoint Online e o ambiente de origem para a migração. Podemos realizar diversas etapas de Habilitar, dependendo da origem. Oferecemos orientações usando uma combinação de ferramentas e documentação, além de realizar tarefas de configuração, quando for aplicável e viável.
  
Você deve fornecer acessos e permissões adequados para que a Microsoft realize determinadas atividades.
  
### <a name="migration-policy-and-steps"></a>Etapas e políticas de migração
  
> [!NOTE]
> Um intervalo de tempo de migração também é chamado de lote de migração.

#### <a name="commercial-and-uk-government"></a>Comercial e governo do Reino Unido

As migrações são feitas 24 horas por dia, sete (7) dias por semana (24x7) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração.

#### <a name="us-governmentdod"></a>Governo dos EUA/DOD

As migrações são feitas 24 horas por dia, cinco (5) dias úteis por semana (24x5) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração. Existem cinco dias de migração em uma semana, das 2h de segunda-feira até a meia-noite de sexta-feira, no Tempo Universal Coordenado (UTC). Isso significa que a última migração programada ocorre às 20h (UTC) de sexta-feira.

- Todas as migrações estão sujeitas às cotas do SharePoint Online descritas no artigo [Limites de software do SharePoint Online e do OneDrive for Business](https://go.microsoft.com/fwlink/?LinkID=616612).   
- A quantidade geral de dados migrados será vinculada a 75% da cota de armazenamento geral do SharePoint Online para o qual você está qualificado, incluindo o armazenamento adicional comprado separadamente.
    
 ### <a name="end-state"></a>Estado final
  
O estado final esperado após um lote de migração inclui: 
- Os dados de fontes devidamente qualificadas e agendadas no ambiente de origem são migrados para o SharePoint Online.   
- Um relatório pós-migração do lote de migração fornecido pela Microsoft.
    
O estado final esperado depois que todas as migrações são concluídas: 
- Os dados de origem qualificada serão migrados para o Office 365 conforme definido na tabela a seguir.  
- O tipo de dados a migrar varia de acordo com o ambiente de origem, conforme descrito na tabela abaixo:
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente de origem** <br/> |**Tipo de migração** <br/> |**O que vai migrar** <br/> |**O que não pode ser migrado** <br/> |
|**Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante**  <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões de arquivo e pasta no nível do usuário\*  <br/>  Permissões de arquivo e pasta no nível do grupo\*  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/><br/> \**Configuração de sincronização de diretório necessária. Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas. As permissões gerenciadas diretamente nos dispositivos de compartilhamento de arquivos não são migradas. Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.* <br/> | Histórico de propriedade e versões anteriores  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Versões anteriores  <br/>  Atributos de arquivos e pastas do Windows (como somente leitura e oculto)  <br/>  Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:  <br/>  Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)  <br/>  Configuração de auditoria do NTFS  <br/>  Metadados de arquivo adicionais fornecidos pela FCI (Infraestrutura de Classificação de Arquivos)  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Compartilhamentos ocultos  <br/>  Compartilhamento (como permissões concedidas no nível de compartilhamento)  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Um único ambiente do G Suite (apenas Google Drive)**  <br/> |Uma ou várias passagens  <br/> | <br/>  Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office), incluindo aqueles com mais de 10 MB <br/>  Estrutura de arquivo e pasta  <br/>  Permissões da pasta para o nível do Usuário  <br/>  Permissões da pasta para o nível do Grupo <br/>  Arquivos com menos de 15 GB  <br/> Metadados básicos de documentos e pastas: <br/> Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/> Unidades compartilhadas (pastas e arquivos) <br/>  O conteúdo compartilhado da conta Google Drive está sendo migrado (se compartilhado explicitamente com usuários ou grupos)\*  <br/><br/> \**Use o administrador do Google Drive para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários <br/>  Descrições de arquivos e pastas, cores de pastas  <br/>  Permissões do arquivo para o nível do Usuário  <br/>  Permissões do arquivo para o nível do Grupo  <br/>  Metadados avançados  <br/>  Atributos de bloqueio de arquivo  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Itens na lixeira  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Usuários bloqueados ou inativos  <br/>  Google Fotos, Formulários, Mapas e outras aplicações conectadas  <br/>  Google Drawings  <br/>  Conteúdo compartilhado externo à sua organização  <br/> O conteúdo que está sendo migrado não pertencente à conta Google Drive <br/>Permissões e metadados básicos de usuários externos  <br/> Permissões de membros da Unidade Compartilhada\* <br/> Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Use o administrador do Google Drive para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/>|
|**Box (Starter, Business, Enterprise)**  <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões de pasta no nível do usuário  <br/>  Permissões de pasta no nível do grupo  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/>  Conteúdo compartilhado de propriedade da conta Box que está sendo migrada (se compartilhada explicitamente com usuários ou grupos)\*  <br/><br/> \**Use relatórios do Box para identificar as contas externas. Instrua os usuários finais a compartilhar seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários <br/>  Permissões de arquivo no nível do usuário  <br/>  Permissões de arquivo no nível do grupo  <br/>  Descrições de arquivos e pastas  <br/>  Box Tags e metadados avançados  <br/>  Atributos de bloqueio de arquivo  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Itens na lixeira  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Usuários bloqueados ou inativos  <br/>  Box Notes (não funcionais à medida que migram sem conversão)  <br/>  Box Apps, Bookmarks, Favorites e Workflows  <br/>  Conteúdo não pertencente à conta Box migrada (pastas compartilhadas)  <br/>  Permissões e metadados básicos de usuários externos\*  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**Use o administrador do Google Drive para identificar a associação à unidade compartilhada. Instrua os usuários finais a configurarem as configurações de associação no destino antes da migração.* |
|**Dropbox para equipes (Padrão e Avançado)**   <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões da pasta para o nível do Usuário  <br/>  Permissões da pasta para o nível do Grupo  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/> Pastas e conteúdos compartilhados pela equipe <br/>  O conteúdo compartilhado que pertence à conta Dropbox está sendo migrado (se compartilhado explicitamente com usuários ou grupos)\*  <br/> <br/> \**Utilize os relatórios Dropbox para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários <br/>  Descrições de arquivos e pastas <br/>  Permissões do arquivo para o nível do Usuário  <br/>  Permissões do arquivo para o nível do Grupo    <br/> Metadados avançados  <br/>  Atributos de bloqueio de arquivo  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Itens na lixeira  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Pastas Dropbox não montadas <br/>  Usuários excluídos ou desconectados <br/>  Dropbox Paper, Showcases e Spaces  <br/> Dropbox Aplicativos e Favoritos (Pins/Stars) <br/> O conteúdo não pertence à conta Dropbox migrada  <br/>  Permissões e metadados básicos de usuários externos\*  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Utilize os relatórios Dropbox para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> |
   
Os Especialistas do FastTrack executam as seguintes tarefas durante as migrações: 
- Conduz um workshop passo a passo de migração abrangendo o processo e a abordagem para o cenário de migração selecionado.
- Fornece pré-requisitos para ferramentas de avaliação e migração conforme o aplicável para o cenário.   
- Fornece pré-requisitos para o acesso da equipe de migração no ambiente de origem e destino para fins de avaliação e migração. 
- Fornece ferramentas de avaliação para efetuar avaliações do ambiente de origem de destino ou fornecer instruções sobre como usar funções da plataforma fonte nativa para criar relatórios de avaliação.   
- Auxilia na implantação e na execução de ferramentas de avaliação e migração (se aplicável).   
- Configura infraestrutura de migração em preparação para a migração de conteúdo (quando aplicável).    
- Conduz uma migração de teste limitado para validar a infraestrutura de migração e os pré-requisitos necessários.   
- Provisiona os sites de destino prontos do SharePoint Online como parte da migração.    
- Conduz uma migração piloto antes da migração de velocidade.   
- Fornece orientações sobre agendamento de migração para o cenário selecionado. 
- Conduz ondas de migração de velocidade de conteúdo de acordo com o cronograma de migração fornecido pelo cliente e validado pelos recursos do FastTrack.   
- Fornece resultados de migração depois de cada janela de migração.   
- Participa de triagem de problemas de migração de velocidade e fornecer orientações sobre possíveis opções de correção.   
- Fornece um relatório de migração final para cada janela de migração de velocidade.   
- Fornece assistência pós-migração durante o teste de aceitação do usuário até cinco dias após a conclusão da migração.
    
Execute as seguintes tarefas durante as migrações: 
- Fornecer os recursos de projeto recomendados para atividades de avaliação e de migração. Entre as quais: 
  - Gerenciamento de projetos. 
  - Teste de Aceitação do Usuário (UAT).  
  - Administradores responsáveis por plataformas de conteúdo de origem e de destino.  
- Fornecer pré-requisitos de infraestrutura para atividades de avaliação e migração (se necessário).  
- Forneça acesso e permissões para os ambientes de origem e destino aos Especialistas da FastTrack para a realização das atividades de migração (se necessário).
    > [!NOTE]
    > As migrações só usam contas de acordo com os requisitos de segurança definidos durante a integração. Se você não usa essas contas, poderá passar por atrasos de migração. 
- Forneça pré-requisitos e realize as atividades necessárias para dar suporte aos processos de avaliação e migração.   
- Instalar ferramentas de avaliação fornecidas pelo FastTrack e concluir atividades de coleta de dados de avaliação (se aplicável).   
- Instalar no local software de migração fornecido pelo FastTrack (se aplicável).   
- Concluir as atividades de correção indicadas no relatório de correção fornecido pelo FastTrack (se aplicável).  
- Fornecer um cronograma de migração usando modelos e diretrizes do FastTrack.   
- Conduzir teste de aceitação do usuário e garantia de qualidade de migração.   
- Conduzir correção de migração pós-migração (se aplicável).
- Planejar e implementar comunicações de usuário final e gerenciamento de alterações (se aplicável).   
- Administrar e configurar as alterações feitas no sistema de origem e nos dispositivos necessários para a realização bem-sucedida das atividades de avaliação e migração.
- Fornece o agendamento de um método definido e de uma lista de dados específicos do usuário a migrar para cada evento de migração, com pelo menos três (3) dias de antecedência.
- Remover os dados do usuário do agendamento até 24 horas antes do lote de migração. Deve corresponder ao lote de migração final.
> [!NOTE]
> A Microsoft não garante a velocidade de migração de arquivos.
    
## <a name="migration-to-onedrive-for-business"></a>Migração para o OneDrive for Business

 ### <a name="enable-to-migrate"></a>Habilitar para migrar
  
Se usar a Microsoft para migrar seus dados, vamos fornecer orientação para habilitar o OneDrive for Business e o ambiente de origem para a migração. Podemos realizar diversas etapas de Habilitar, dependendo da origem. Vamos ajudar você com algumas atividades usando uma combinação de ferramentas, documentação e orientação, e também realizando tarefas de configuração, quando for aplicável e viável.
  
Você pode fornecer acesso e permissões adequadas para que a Microsoft realize determinadas atividades. Caso não forneça acesso e/ou permissões, você deverá executar determinadas tarefas definidas por si próprio, mas com a orientação da Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Etapas e políticas de migração
  
> [!NOTE]
> Um intervalo de tempo de migração também é chamado de lote de migração.

#### <a name="commercial-and-uk-government"></a>Comercial e governo do Reino Unido

As migrações são feitas 24 horas por dia, sete (7) dias por semana (24x7) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração.

#### <a name="us-governmentdod"></a>Governo dos EUA/DOD

As migrações são feitas 24 horas por dia, cinco (5) dias úteis por semana (24x5) de forma padronizada e pré-agendada em intervalos de tempo de migração predefinidos. Existem três lotes de migração por dia de migração. Existem cinco dias de migração em uma semana, das 2h de segunda-feira até a meia-noite de sexta-feira, no Tempo Universal Coordenado (UTC). Isso significa que a última migração programada ocorre às 20h (UTC) de sexta-feira.
    
- Todas as migrações requerem acesso e permissões adequados ao ambiente de origem.   
- Todas as migrações estão sujeitas às cotas do OneDrive for Business descritas no artigo [Limites de software do SharePoint Online e do OneDrive for Business](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Estado final
  
O estado final esperado após um lote de migração inclui:  
- Os dados das caixas de correio de origem devidamente qualificados e programados no ambiente de origem são migrados para o OneDrive for Business.  
- Um relatório pós-migração do lote de migração fornecido pela Microsoft.
    
O estado final esperado depois que todas as migrações são concluídas:
- Os dados de origem qualificada serão migrados para o Office 365 conforme definido na tabela a seguir.  
- O tipo de dados a migrar varia de acordo com o ambiente de origem, conforme descrito na tabela a seguir.
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente de origem**|**Tipo de migração**|**O que vai migrar**|**O que não pode ser migrado**|
|**Dispositivos de compartilhamento de arquivos compatíveis com SMB 2.0 em diante**  <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões de arquivo e pasta no nível do usuário\*  <br/>  Permissões de arquivo e pasta no nível do grupo\*  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/> <br/>\**Configuração de sincronização de diretório necessária. Apenas as permissões NTFS expostas ao Explorador de Arquivos do Windows são migradas. As permissões gerenciadas diretamente nos dispositivos de compartilhamento de arquivos não são migradas. Se os dados são armazenados em um dispositivo SMB 2.0, as permissões equivalentes NTFS expostas pelo protocolo SMB são migradas.* <br/> | Histórico de propriedade e versões anteriores  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Versões anteriores  <br/>  Atributos de arquivos e pastas do Windows (como somente leitura e oculto)  <br/>  Permissões avançadas e configurações especiais do Sistema de arquivos de nova tecnologia não-Windows (NTFS) e NTFS:  <br/>  Permissões de negação explícita (removidas após migração, conteúdo sujeito a permissões paralelas ou permissões na pasta pai)  <br/>  Configuração de auditoria do NTFS  <br/>  Metadados de arquivo adicionais fornecidos pela FCI  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Compartilhamentos ocultos  <br/>  Compartilhamento (como permissões concedidas no nível de compartilhamento)  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Um único ambiente do G Suite (apenas Google Drive)**  <br/> |Uma ou várias passagens  <br/> | Documentos, Planilhas e Slides do Google (os arquivos são convertidos para o formato equivalente do Office, incluindo aqueles com mais de 10 MB)  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões da pasta para o nível do Usuário  <br/>  Permissões da pasta para o nível do Grupo  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/> Unidades compartilhadas (pastas e arquivos) <br/> O conteúdo compartilhado da conta Google Drive está sendo migrado (se compartilhado explicitamente com usuários ou grupos)\* <br/> <br/>\**Use o administrador do Google Drive para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários  <br/>  Descrições de arquivos e pastas, cores de pastas  <br/>   Permissões do arquivo para o nível do Usuário  <br/>  Permissões do arquivo para o nível do Grupo  <br/> Metadados avançados <br/>  Atributos de bloqueio de arquivo <br/> Conversão de URLs incorporados em conteúdo  <br/> Itens na lixeira <br/> Documentos inacessíveis ou corrompidos <br/> Usuários bloqueados ou inativos <br/> Google Fotos <br/> Formulários, Mapas e outros aplicativos conectados <br/> Google Drawings <br/> Conteúdo compartilhado externo à sua organização <br/> O conteúdo que está sendo migrado não pertencente à conta Google Drive <br/> Permissões e metadados básicos de usuários externos<br/> Permissões dos membros da unidade compartilhada\*<br/> Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/><br/> \**Utilize o administrador do Google Drive para identificar a associação à unidade compartilhada. Instrua os usuários finais a definirem as configurações de associação no destino, antes da migração.* <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões de pasta no nível do usuário  <br/>  Permissões de pasta no nível do grupo  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/>  Conteúdo compartilhado de propriedade da conta Box que está sendo migrada (se compartilhada explicitamente com usuários ou grupos)\*  <br/><br/> \**Use relatórios do Box para identificar as contas externas. Instrua os usuários finais a compartilhar seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários  <br/>  Descrições de arquivos e pastas  <br/>  Permissões de arquivo no nível do usuário  <br/>  Permissões de arquivo no nível do grupo  <br/>  Box Tags e metadados avançados  <br/>  Atributos de bloqueio de arquivo  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Itens na lixeira  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Usuários bloqueados ou inativos  <br/>  Box Notes (não funcionais à medida que migram sem conversão)  <br/>  Box Apps, Bookmarks, Favorites e Workflows  <br/>  Conteúdo não pertencente à conta Box migrada (pastas compartilhadas)  <br/>  Permissões e metadados básicos de usuários externos\*  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Dropbox para equipes (Padrão e Avançado)**   <br/> |Uma ou várias passagens  <br/> | Documentos  <br/>  Estrutura de arquivo e pasta  <br/>  Permissões da pasta para o nível do Usuário  <br/>  Permissões da pasta para o nível do Grupo  <br/>  Arquivos com menos de 15 GB  <br/>  Metadados básicos de documentos e pastas:  <br/>  Data de criação  <br/>  Data de modificação  <br/>  Criado por  <br/>  Última modificação por  <br/> Pastas e conteúdos compartilhados pela equipe <br/> O conteúdo compartilhado que pertence à conta Dropbox está sendo migrado (se compartilhado explicitamente com usuários ou grupos)\*  <br/> <br/> \**Utilize os relatórios Dropbox para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> | Histórico de propriedade, versões anteriores e comentários <br/>  Descrições de arquivos e pastas <br/>  Permissões do arquivo para o nível do Usuário  <br/>  Permissões do arquivo para o nível do Grupo    <br/> Metadados avançados  <br/>  Atributos de bloqueio de arquivo  <br/>  Conversão de URLs incorporados em conteúdo  <br/>  Itens na lixeira  <br/>  Documentos inacessíveis ou corrompidos  <br/>  Pastas Dropbox não montadas <br/>  Usuários excluídos ou desconectados <br/>  Dropbox Paper, Showcases e Spaces  <br/> Dropbox Aplicativos e Favoritos (Pins/Stars) <br/> O conteúdo não pertence à conta Dropbox migrada  <br/>  Permissões e metadados básicos de usuários externos\*  <br/>  Arquivos ou pastas que excedem as [restrições e limitações atuais do SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Utilize os relatórios Dropbox para identificar as contas externas. Instrua os usuários finais a compartilharem novamente o seu conteúdo após a migração.* <br/> |
   
Os Especialistas do FastTrack executam as seguintes tarefas durante as migrações:  
- Conduz um workshop passo a passo de migração abrangendo o processo e a abordagem para o cenário de migração selecionado.   
- Fornece pré-requisitos para ferramentas de avaliação e migração conforme o aplicável para o cenário.  
- Fornece pré-requisitos para o acesso da equipe de migração no ambiente de origem e destino para fins de avaliação e migração.   
- Fornece ferramentas de avaliação para efetuar avaliações do ambiente de origem de destino ou fornecer instruções sobre como usar funções da plataforma fonte nativa para criar relatórios de avaliação.    
- Auxilia na implantação e na execução de ferramentas de avaliação e migração (se aplicável).   
- Configura infraestrutura de migração em preparação para a migração de conteúdo (quando aplicável).    
- Conduz uma migração de teste limitado para validar a infraestrutura de migração e os pré-requisitos necessários.    
- Provisiona os sites de destino prontos do OneDrive for Business como parte da migração.    
- Conduz uma migração piloto antes da migração de velocidade.
- Fornece orientações sobre agendamento de migração para o cenário selecionado.   
- Conduz ondas de migração de velocidade de conteúdo de acordo com o cronograma de migração fornecido pelo cliente e validado pelos recursos do FastTrack.   
- Fornece resultados de migração depois de cada janela de migração.   
- Participa de triagem de problemas de migração de velocidade e fornecer orientações sobre possíveis opções de correção. 
- Fornece um relatório de migração final para cada janela de migração de velocidade.   
- Fornece assistência pós-migração durante o teste de aceitação do usuário até cinco dias após a conclusão da migração.
   
Execute as seguintes tarefas durante as migrações:
- Fornecer os recursos de projeto recomendados para atividades de avaliação e de migração. Entre as quais:
  - Gerenciamento de projetos.
  - UAT.
  - Administradores responsáveis por plataformas de conteúdo de origem e de destino.
- Fornecer pré-requisitos de infraestrutura para atividades de avaliação e migração (se necessário).   
- Forneça acesso e permissões para os ambientes de origem e destino aos Especialistas da FastTrack para a realização das atividades de migração (se necessário).  
    > [!NOTE]
    > As migrações só usam contas de acordo com os requisitos de segurança definidos durante a integração. Se você não usa essas contas, poderá passar por atrasos de migração. 
- Instalar ferramentas de avaliação fornecidas pelo FastTrack e concluir atividades de coleta de dados de avaliação (se aplicável).
- Instalar no local software de migração fornecido pelo FastTrack (se aplicável).  
- Concluir as atividades de correção indicadas no relatório de correção fornecido pelo FastTrack (se aplicável).   
- Fornecer um cronograma de migração usando modelos e diretrizes do FastTrack. 
- Fornecer um agendamento de um método definido e uma lista de dados específicos do usuário a migrar para cada evento de migração.
- Remove dados do usuário do agendamento até 24 horas antes do lote de migração. Deve corresponder ao lote de migração final.
- Conduzir teste de aceitação do usuário e garantia de qualidade de migração.   
- Conduzir correção de migração pós-migração (se aplicável).  
- Planejar e implementar comunicações de usuário final e gerenciamento de alterações (se aplicável).  
- Administrar e configurar as alterações feitas no sistema de origem e nos dispositivos necessários para a realização bem-sucedida das atividades de avaliação e migração.
    
> [!NOTE]
> A Microsoft não garante a velocidade de migração de arquivos. 



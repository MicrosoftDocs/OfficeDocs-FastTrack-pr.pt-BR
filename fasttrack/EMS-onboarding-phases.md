---
title: Fases de integração e migração
description: 'Fases dos Benefícios do Centro FastTrack '
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.openlocfilehash: f763358a44878f025d588a10eb97fcd20a5ed984
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800471"
---
# <a name="onboarding-phases"></a>Fases da Integração

> [!CAUTION]
> Este conteúdo não é mais atual e está agendado para remoção. Use o Sumário na navegação à esquerda para o conteúdo atual.

Ao usar os serviços [e planos](M365-eligible-services-and-plans.md) qualificados para obter o Microsoft Azure Active Directory Premium, o Microsoft Intune e a proteção de informações do Azure prontos para uso, há várias fases envolvidas no processo. As seções a seguir descrevem todas as fases do processo de integração.

A integração tem quatro fases principais:

![As quatro fases do processo de integração do FastTrack](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>Fase inicial

Após adquirir o número e tipos de licença apropriados, siga as orientações do email de confirmação de compra para associar as licenças ao seu locatário existente ou ao novo locatário. Em seguida, a Microsoft verifica a qualificação para os Benefícios do Centro FastTrack e tenta entrar em contato com você para oferecer assistência de integração.

> [!NOTE]
> Você também pode solicitar assistência no [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) se estiver pronto para implantar esses serviços em sua organização.

### <a name="to-request-assistance"></a>Para solicitar assistência

1. Acesse o [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selecione **Solicitar assistência para o Microsoft 365** nas **ações rápidas** na parte superior da sua página de destino ou selecionando **Solicitar assistência para o Microsoft 365** no cartão de implantação.
3. Preencha o formulário **Solicitar assistência para o Microsoft 365**.

Assim que o suporte de integração for iniciado, definiremos um cronograma de reuniões online.

Os parceiros da Microsoft também podem obter ajuda no [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) em nome de um cliente. Para fazer isso:

1. Acesse o [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selecione **Meus Clientes**.
3. Pesquise seu cliente ou selecione na lista de clientes.
4. Selecione **Serviços**.
5. Preencha o formulário **Solicitar assistência para o Microsoft 365**.

Quando o suporte à integração começar, o FastTrack agendará uma programação de reuniões online com você para discutir o processo de integração, verificar dados e configurar uma reunião de lançamento.

![Fase inicial de integração](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>Fase Avaliar

Assim que o processo de integração começar, o Centro FastTrack trabalhará com você para avaliar o seu ambiente de origem e seus requisitos. As ferramentas são executadas para avaliar o seu ambiente e os especialistas do FastTrack orientam você durante a avaliação do seu Active Directory local, navegadores da Internet, sistemas operacionais de dispositivos do cliente, DNS (sistema de nomes de domínio), rede, infraestrutura e sistema de identidade para determinar se as alterações são necessárias para integração.

O Centro FastTrack também conecta você com orientações sobre como direcionar a adoção bem-sucedida dos serviços qualificados.

Baseado em suas configuração atual, fornecemos um plano de correção que leva seu ambiente de origem aos requisitos mínimos para uma integração bem-sucedida ao EMS ou aos seus serviços de nuvem individuais. Também configuramos as chamadas apropriadas do ponto de verificação para a fase de correção.

![Fase de avaliação de integração](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>Fase de correção
Execute as tarefas do plano de correção no ambiente de origem para atender aos requisitos de integração e adoção de cada serviço (caso necessário).

![Fase de correção de integração](./media/ft-remediate-phase.png)

Antes de começar a fase Habilitar, verificaremos em conjunto os resultados das atividades de correção para garantir que você está pronto para continuar.

## <a name="enable-phase"></a>Fase Habilitar
Quando todas as atividades de correção estiverem concluídas, o projeto passa a configurar a infraestrutura básica para o consumo do serviço e para provisionar cada serviço de nuvem do EMS qualificado.

**Fase Habilitar: Funcionalidades básicas**

A integração básica envolve o provisionamento do serviço e a integração de identidade e locatário. Ele também inclui etapas para fornecer uma base para integração de serviços online, como o Azure AD Premium, o Intune e a proteção de informações do Azure.

![Integração da fase Habilitar: Funcionalidades básicas](./media/ft-enable-phase-core-01.png)

![Integração da fase Habilitar: Funcionalidades básicas](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP significa Web Application Proxy (Proxy de Aplicativo da Web). SSL significa Secure Sockets Layer (Camada de Soquetes Seguros). SDS significa School Data Sync (Sincronização de Dados Escolares). Para saber mais sobre SDS, confira [Bem-vindo ao Microsoft School Data Sync](https://go.microsoft.com/fwlink/?linkid=871480).

> [!NOTE]
> Um método de autenticação gerenciada inclui, mas não se limita a sincronização de hash de senha. A integração de identidade é uma atividade ocasional e não inclui migração ou descomissionamento de métodos de autenticação existentes, como gerenciados ou federados.

### <a name="enable-phase---azure-ad-premium"></a>Fase habilitar Azure AD Premium

O ambiente do Azure AD Premium pode ser configurado usando a ferramenta de sincronização de diretório do Azure Active Directory Connect e os serviços de Federação do Active Directory(AD FS) (conforme necessário).

Para cenários do Azure AD Premium que incluem a sincronização de identidades locais para a nuvem, podemos ajudá-lo a adicionar administradores de TI e usuários à sua assinatura, configurar os pré-requisitos de gerenciamento, configurar o Azure AD Premium, configurando o diretório de sincronização com autenticação gerenciada e AD FS usando a ferramenta Azure AD Connect, configurando os usuários do teste e validando seus principais casos de uso para o serviço.

A configuração do Azure AD Premium inclui os recursos a seguir:

-   Autoatendimento de Redefinição de Senha do Azure Active Directory (SSPR).

-   Autenticação Multifator do Azure (Azure MFA).

-   Até três (3) ou mais integrações de aplicativos de Software como um serviço (SaaS) com Logon Único (SSO) do [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

-   Provisionamento automático do usuário para aplicativos SaaS pré-instalados, como listados na [Lista de tutoriais de integração de aplicativost](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), limitado apenas ao provisionamento de saída.

-   Tela de logon personalizada, incluindo logotipo, texto e imagens.

-   Autoatendimento e Grupos Dinâmicos (Grupos).

-   Proxy de Aplicativo do Azure Active Directory.

-   Azure Active Directory Connect Health.

-   Acesso Condicional do Azure Active Directory.

-   Termos de uso do Azure Active Directory.

-   Proteção de identidade do Azure Active Directory.

-   Azure Active Directory Privileged Identity Management.

-   Revisões de Acesso do Azure Active Directory.

-   Proteção de senha do Azure Active Directory.

-   B2B do Azure Active Directory.

![Fase de habilitação de integração - Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>Fase de Habilitação – Intune

Para o Intune, vamos orientá-lo a começar a usar o Microsoft Intune para gerenciar dispositivos. As etapas exatas dependem do ambiente de origem e se baseiam nas necessidades de gerenciamento de aplicativos móveis e de dispositivos móveis. As etapas podem incluir:

-   Licenciamento para os usuários finais. Além disso, fornecemos assistência sobre como ativar licenças por volume para o locatário do serviço de nuvem da Microsoft (conforme necessário).

-   Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem.

-   Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.

-   Configuração da autoridade de Gerenciamento de Dispositivo Móvel (MDM), com base em suas necessidades de gerenciamento, incluindo:

    -   Configure o Intune como sua autoridade MDM quando o Intune for sua única solução MDM.

-   Fornecendo instruções MDM para:

    -   Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.

    -   Configuração do gerenciamento das políticas e serviços do MDM, como:

        -   Implantação de aplicativos para cada plataforma com suporte por meio de links da web ou links profundos.

        -   Políticas de acesso condicional.

        -   Implantação de email, redes sem fio e perfis VPN se tiver uma autoridade de certificação existente, uma infraestrutura de rede Wi-Fi ou VPN em sua organização.

        -   Configuração do Microsoft Intune Exchange Connector (quando aplicável).

        -   Conexão ao Intune Data Warehouse.

        -   Integração do Intune com:
            -   O Team Viewer para assistência remota (É necessária a assinatura do Team Viewer).

            -   Soluções para parceiros de proteção de ameaças móveis (MTD) (É necessária a assinatura de Defesa contra Ameaças Móveis).

            -   Soluções de gerenciamento de despesas de telecomunicações (É necessário a assinatura de solução de gerenciamento de despesas de telecomunicações).

            -   Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).

    -   Registrando dispositivos de todas [as plataformas](https://technet.microsoft.com/library/dn600287.aspx) compatíveis com o Intune.

-   Fornecendo diretrizes de proteção de aplicativos em:

    -   Configuração e implantação das políticas de proteção de aplicativo para cada plataforma com suporte.

    -   Configurar políticas de acesso condicional para aplicativos gerenciados.

    -   Direcionar os grupos de usuários apropriados com as políticas de MAM acima.

    -   Usando relatórios de uso de aplicativos gerenciados.

-   Fornecendo diretrizes de gerenciamento de computador em:

    -   Instalar o software cliente do Intune (quando necessário).

    -   Usando os relatórios de software e hardware disponíveis no Intune.

    > [!IMPORTANT]
    > O FastTrack não dá suporte ao gerenciamento clássico de computador do Windows 10 com o Intune. O FastTrack é compatível apenas com o gerenciamento do dispositivo do Windows 10 por meio do serviço de gerenciamento de dispositivo móvel do Intune (MDM).

#### <a name="windows-autopilot"></a>Windows Autopilot

O FastTrack pode ajudar a simplificar o provisionamento de dispositivos com o piloto automático do Windows e o Intune, fornecendo novos dispositivos para seus usuários finais sem a necessidade de criar, manter e aplicar imagens personalizadas do sistema operacional aos seus dispositivos.

O FastTrack é compatível com os seguintes cenários de piloto automático:

- **Autoatendimento do Azure AD:** os dispositivos entram no Azure AD e se inscrevem no Intune. Esse cenário tem suporte ao usar o Windows 10 1703 e as versões mais recentes.

- **Autoatendimento do AAD híbrido:** os dispositivos entram no AD local e no Azure AD e se inscrevem no Intune. Esse cenário tem suporte ao usar o Windows 10 1809 e as versões mais recentes.

- **Autoprovisionagem:** os dispositivos entram automaticamente no Azure AD. Esse cenário tem suporte ao usar o Windows 1809 e as versões mais recentes.

    > [!IMPORTANT]
    > O FastTrack não dá suporte a cenários de piloto automático iniciados pelo Configuration Manager.

As etapas para configurar o piloto automático do Windows dependem do seu ambiente de origem e podem incluir:

- Configuração e instalação do Microsoft Intune para Windows Autopilot.

- Configuração dos grupos de Azure AD Dynamic 

- Adição da marca da sua Empresa no Azure AD.

- Criação e atribuição de dispositivos aos perfis do Windows Autopilot (por exemplo, um perfil do Windows Autopilot que restringe a criação de contas de Administrador Local).

- Personalização da experiência inicial (OOBE) para ser compatível com os requisitos da organização.

- Configuração do registro automático MDM no Azure AD e no Intune.

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>Implantar o Outlook para iOS e Android com segurança.

O FastTrack pode ajudar a implantar o Outlook para iOS e Android com segurança em sua organização, para garantir que os usuários tenham todos os aplicativos necessários instalados.

As etapas para implantar o Outlook Mobile para iOS e Android com Intune dependem do seu ambiente de origem e podem incluir:

- Baixe o Outlook para iOS e Android, o Microsoft Authenticator e o aplicativo portal da empresa do Intune por meio da Apple App Store ou do Google Play Store.
- Fornece orientação sobre a configuração:
    - Outlook para iOS e Android, o Microsoft Authenticator e a implantação do aplicativo portal da empresa com o Intune.
    - Políticas de proteção de aplicativos
    - Políticas de acesso condicional
    - Políticas de configuração do usuário

    > [!IMPORTANT]
    > A equipe FastTrack não é compatível com a proteção do Outlook para iOS e Android com as políticas de caixa de correio de dispositivo móvel do Exchange.

#### <a name="cloud-attach"></a>Vincular à nuvem

O FastTrack guia você para se preparar para vincular ambientes existentes do Gerenciador de Configurações à nuvem com o Intune. As etapas exatas dependem do ambiente de origem. Essas etapas podem incluir:

- Explicar os benefícios de vincular o Configuration Manager à nuvem com o Intune.

- Licenciamento para os usuários finais. O FastTrack também oferece assistência sobre como ativar licenças por volume para o locatário do serviço de nuvem da Microsoft (conforme necessário).

- A configuração de identidades que será usada pelo Intune, aproveitando o Active Directory local e as identidades de nuvem.

- Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.

- Habilitação de vinculação à nuvem no console do Configuration Manager.

- Fornecimento de diretrizes de configuração da associação híbrida do Azure Active Directory.

- Fornecimento de diretrizes para configuração do Azure Active Directory para o registro automático do MDM.

- Fornecimento de diretrizes sobre como configurar o gateway de gerenciamento de nuvem.

- Configuração de cargas de trabalho compatíveis que você deseja passar para o Intune.

- Instalação do cliente do Configuration Manager em dispositivos registrados no Intune.

O FastTrack também fornece diretrizes sobre como direcionar a adoção bem-sucedida dos serviços qualificados.

![Integração da fase de habilitação – Intune](./media/ft-enable-phase_intune_mam.png)

![Integração da fase de habilitação – Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![Integração da fase de habilitação - Vincular à nuvem](./media/cloud-attach-diagram.png) 

#### <a name="enable-phase--azure-information-protection"></a>Fase de habilitação – Proteção de Informações do Azure

Os clientes têm orientação sobre como: 

- Ativar e configurar o locatário.
- Criar e configurar rótulos e políticas.
- Aplicação de proteção de informações aos documentos. 
- Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.
- Uso de arquivos em repouso com o scanner da Proteção de Informações do Azure.
- Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.

As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando Serviços de Gerenciamento de Direitos do Microsoft Azure (Azure RMS), Criptografia de Mensagens do Office 365 (OME) e Prevenção Contra Perda de Dados (DLP).

> [!NOTE]
> **Quer saber mais?**, consulte[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Próximas etapas

[Benefícios do FastTrack para EMS – Responsabilidades da Microsoft](EMS-fasttrack-responsibilities.md)


---
title: Fases de integração e migração
description: Fases do benefício do FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: e51f030b-8b08-4fea-96c9-d4ded435a264
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ed490839cda702174d356b2735469a54636fa591
ms.sourcegitcommit: 28dafb1d0904d29c4e113b03d3c1b0fcd2257508
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/13/2019
ms.locfileid: "33967980"
---
# <a name="onboarding-phases"></a>Fases da Integração

Quando você usa os [serviços e planos qualificados](M365-eligible-services-and-plans.md) para obter a proteção de informações do Microsoft Azure Active Directory Premium, Microsoft Intune e Azure pronta para uso, há várias fases envolvidas no processo. As seções a seguir descrevem cada fase do processo de integração.

A integração tem quatro fases principais:

![As quatro fases do processo de integração do FastTrack](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>Fase Iniciar

Após adquirir o número apropriado de licenças, siga as orientações do email de confirmação de compra para associar as licenças ao locatário existente ou ao novo locatário. A Microsoft verifica a qualificação para o benefício do FastTrack Center e tenta contatá-lo para oferecer assistência de integração.

> [!NOTE]
> Você também pode solicitar assistência do [FastTrack Center](https://go.microsoft.com/fwlink/?linkid=780698) se estiver pronto para implantar esses serviços em sua organização.

### <a name="to-request-assistance"></a>Para solicitar assistência

1. Acesse o [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selecione **FastTrack**.
3. Selecione **Serviços**.
4. Conclua a **solicitação de assistência com o formulário do Microsoft 365**.

Após o início do suporte de integração, configuraremos um cronograma de reuniões online.

> [!NOTE]
> Se você tiver um parceiro da Microsoft listado em seu locatário do Office 365, você não verá essa opção. Consulte seu parceiro da Microsoft para obter assistência.

Os parceiros da Microsoft também podem obter ajuda no [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) em nome de um cliente. Para fazer isso:

1. Acesse o [site do FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selecione **FastTrack**.
3. Selecione **Meus Clientes**.
4. Pesquise seu cliente ou selecione na lista de clientes.
5. Selecione **Serviços**.
6. Conclua a **solicitação de assistência com o formulário do Microsoft 365**.

Depois que o suporte de integração for iniciado, o FastTrack configurará um cronograma de reuniões online com você para discutir o processo de integração, verificar dados e configurar uma reunião de início.

![Fase inicial de integração](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>Fase Avaliar

Após o início do processo de integração, o FastTrack Center trabalha com você para avaliar seu ambiente de origem e os requisitos. As ferramentas são executadas para avaliar seu ambiente, e os especialistas do FastTrack orientam você na avaliação do Active Directory local, navegadores da Internet, sistemas operacionais dos dispositivos clientes, DNS (sistema de nomes de domínio), rede, infraestrutura e sistema de identidade para Determine se as alterações são necessárias para a integração.

O FastTrack Center também conecta você com orientações sobre como conduzir a adoção bem-sucedida dos serviços qualificados.

Com base em sua configuração atual, fornecemos um plano de correção que traz o ambiente de origem para os requisitos mínimos para a integração bem-sucedida com o EMS ou seus serviços de nuvem individuais. Também configuramos as chamadas de ponto de verificação apropriadas para a fase de correção.

![Fase de avaliação de integração](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>Fase Corrigir
Você realiza as tarefas no plano de correção no seu ambiente de origem para atender aos requisitos de integração e adoção de cada serviço (conforme necessário).

![Fase de correção de integração](./media/ft-remediate-phase.png)

Antes de começar a fase habilitar, verificaremos em conjunto os resultados das atividades de correção para garantir que você está pronto para prosseguir.

## <a name="enable-phase"></a>Fase Habilitar
Quando todas as atividades de correção estiverem concluídas, o projeto mudará para a configuração da infraestrutura principal para o consumo de serviço e o provisionamento de cada serviço de nuvem do EMS qualificado.

**Habilitar recursos de fase central**

A integração básica envolve o provisionamento do serviço e a integração de identidade e locatário. Ele também inclui etapas para fornecer uma base para a integração de serviços online, como o Azure AD Premium, o Intune e a proteção de informações do Azure.

![Recursos básicos da fase de habilitação de integração](./media/ft-enable-phase-core-01.png)

![Recursos básicos da fase de habilitação de integração](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP significa Web Application Proxy (Proxy de Aplicativo da Web). SSL significa Secure Sockets Layer (Camada de Soquetes Seguros). SDS significa School Data Sync (Sincronização de Dados Escolares). Para saber mais sobre SDS, confira [Bem-vindo ao Microsoft School Data Sync](https://go.microsoft.com/fwlink/?linkid=871480).

> [!NOTE]
> Um método de autenticação gerenciada inclui, mas não está limitado à sincronização de hash de senha. A integração de identidade é uma atividade única e não inclui migração ou descomissionamento de métodos de autenticação existentes, como gerenciados ou federados.

### <a name="enable-phase---azure-ad-premium"></a>Fase habilitar-Azure AD Premium

O ambiente do Azure AD Premium pode ser configurado usando a sincronização de diretórios do Azure Active Directory Connect Tool e os serviços de Federação do Active Directory (conforme necessário).

Para cenários do Azure Active Directory Premium que incluem a sincronização de identidades locais para a nuvem, ajudamos você a adicionar administradores de ti e usuários à sua assinatura, configurar pré-requisitos de gerenciamento, configurar o Azure AD Premium, configurar o diretório sincronização com a autenticação gerenciada e o AD FS usando a ferramenta Azure AD Connect, configurando os usuários de teste e validando seus casos de uso principais para o serviço.

A configuração do Azure AD Premium inclui a habilitação dos seguintes recursos:

-   Redefinição de senha de autoatendimento do Azure Active Directory (SSPR).

-   Autenticação multifator do Azure (Azure MFA).

-   Até três (3) ou mais integrações de aplicativos de software como serviço (SaaS) com logon único (SSO) do [Marketplace do Azure Active Directory](https://azure.microsoft.com/marketplace/active-directory/).

-   Provisionamento automático de usuário para aplicativos SaaS previamente integrados, conforme listado na [lista de tutorial de integração de aplicativos](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitado somente a provisionamento de saída.

-   Tela de logon personalizada, incluindo logotipo, texto e imagens.

-   Grupos de autoatendimento e dinâmicos (grupos).

-   Proxy de aplicativo do Azure Active Directory.

-   Integridade do Azure Active Directory Connect.

-   Acesso condicional do Azure Active Directory.

-   Termos de uso do Azure Active Directory.

-   Proteção de identidade do Azure Active Directory.

-   Gerenciamento de identidade privilegiada do Azure Active Directory.

-   Revisões do acesso ao Active Directory do Azure.

![Fase habilitar integração-Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>Fase habilitar-Intune

Para o Intune, nós o orientamos a preparar o uso do Microsoft Intune para gerenciar dispositivos. As etapas exatas dependem do ambiente de origem e se baseiam em suas necessidades de gerenciamento de aplicativo móvel e dispositivo móvel. As etapas podem incluir:

-   Licenciar seus usuários finais. Também fornecemos ajuda sobre como ativar as licenças de volume para o locatário do serviço de nuvem da Microsoft (conforme necessário).

-   Configurar identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem.

-   Adicionar usuários à sua assinatura do Intune, definir funções de administrador de ti e criar grupos de usuários e de dispositivos.

-   Configurar sua autoridade de gerenciamento de dispositivo móvel (MDM), com base em suas necessidades de gerenciamento, incluindo:

    -   Configuração do Intune como sua autoridade de MDM quando o Intune é sua única solução MDM ou em conjunto com o gerenciamento de dispositivos móveis para o Office 365.

-   Fornecendo orientações sobre o MDM para:

    -   Configuração de grupos de testes a serem usados para validar políticas de gerenciamento do MDM.

    -   Configurando serviços e políticas de gerenciamento do MDM como:

        -   Implantação de aplicativo para cada plataforma suportada por meio de links da Web ou links de fundo.

        -   Políticas de acesso condicional.

        -   Implantação de emails, redes sem fio e perfis de rede privada virtual (VPN) se você tiver uma autoridade de certificação, Wi-Fi ou infraestrutura de VPN existente em sua organização.

        -   Configuração do Microsoft Intune Exchange Connector (quando aplicável).

        -   Conectando-se ao data warehouse do Intune

        -   Integração do Intune com:
            -   Team Viewer para assistência remota (a assinatura do Team Viewer é necessária).

            -   Soluções de parceiros do MTD (defesa contra ameaças móveis) (a assinatura de defesa contra ameaças móveis é necessária).

            -   Solução de gerenciamento de despesas de telecomunicações (a assinatura da solução de gerenciamento de despesas de telecomunicações é necessária).

            -   A proteção avançada contra ameaças do Windows Defender (licenças do Windows E5 ou do Microsoft 365 E5 são necessárias).

    -   Registrar dispositivos de cada [plataforma](https://technet.microsoft.com/library/dn600287.aspx) suportada no Intune.

-   Fornecer orientações sobre a proteção de aplicativos em:

    -   Configurar as políticas de proteção de aplicativos para cada plataforma suportada.

    -   Configurando políticas de acesso condicional para aplicativos gerenciados.

    -   Direcionar os grupos de usuários apropriados com as políticas MAM acima.

    -   Usando relatórios de uso de aplicativos gerenciados.

-   Fornecendo orientações de gerenciamento de PC em:

    -   Instalação do software do cliente do Intune (quando necessário).

    -   Usando os relatórios de software e hardware disponíveis no Intune.

    > [!IMPORTANT]
    > O FastTrack não dá suporte ao gerenciamento clássico de computador com o Windows 10 com o Intune. O FastTrack é compatível apenas com o gerenciamento de dispositivos do Windows 10 através do Intune Mobile Device Management (MDM).

#### <a name="windows-autopilot"></a>Windows Autopilot

O FastTrack pode ajudá-lo a simplificar o provisionamento do dispositivo com o Windows AutoPilot e o Intune, fornecendo novos dispositivos aos seus usuários finais, sem a necessidade de criar, manter e aplicar imagens personalizadas do sistema operacional aos seus dispositivos.

O FastTrack oferece suporte aos seguintes cenários de piloto automático:

- **Autoatendimento do Azure AD:** Os dispositivos ingressam no Azure AD e se registram no Intune. Este cenário tem suporte ao usar o Windows 10 1703 e versões mais recentes.

- **Autoatendimento do AAD híbrido:** Os dispositivos ingressam no AD local e no Azure AD e se registram no Intune. Este cenário tem suporte ao usar o Windows 10 1809 e versões mais recentes.

- **Autoprovisionamento:** Os dispositivos ingressam automaticamente no Azure AD. Este cenário tem suporte ao usar o Windows 1809 e versões mais recentes.

    > [!IMPORTANT]
    > O FastTrack não oferece suporte a cenários do AutoPilot iniciados a partir do Configuration Manager.

As etapas para configurar o piloto automático do Windows dependem do ambiente de origem e podem incluir:

- Configurar e configurar o piloto automático do Microsoft Intune para Windows.

- Configurar grupos dinâmicos do Azure AD

- Adicione a identidade visual da empresa no Azure AD.

- Crie e atribua dispositivos aos perfis do Windows AutoPilot (por exemplo, um perfil do Windows AutoPilot que restringe a criação de contas de administrador local).

- Personalizar o OOBE (uso da experiência) para cumprir os requisitos da organização.

- Configurando o registro automático do MDM no Azure AD e no Intune.

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>Implantar o Outlook para iOS e Android com segurança

O FastTrack pode ajudá-lo a implantar o Outlook para iOS e Android com segurança em sua organização para garantir que seus usuários tenham todos os aplicativos necessários instalados.

As etapas para implantar com segurança o Outlook Mobile para iOS e Android com o Intune dependem do ambiente de origem e podem incluir:

- Baixe o Outlook para iOS e Android, Microsoft Authenticator e o aplicativo do portal da empresa do Intune por meio da Apple App Store ou do Google Play Store.
- Além disso, forneça orientações sobre como configurar:
    - Outlook para iOS e Android, Microsoft Authenticator e a implantação do aplicativo do portal da empresa do Intune com o Intune.
    - Políticas de proteção de aplicativos
    - Políticas de acesso condicional
    - Políticas de configuração de aplicativos

    > [!IMPORTANT]
    > A equipe do FastTrack não é compatível com a proteção do Outlook para iOS e do Android com as políticas de caixa de correio do dispositivo móvel do Exchange.

#### <a name="co-management"></a>Co-Management

O FastTrack orienta você durante a preparação para o gerenciamento simultâneo de dispositivos Windows 10 com o Configuration Manager e o Intune. As etapas exatas dependem do ambiente de origem e podem incluir:

- Explique os benefícios do co-Management.

- Licenciar seus usuários finais. O FastTrack também fornece assistência sobre como ativar licenças de volume para o locatário do serviço de nuvem da Microsoft (conforme necessário).

- Configure as identidades a serem usadas pelo Intune aproveitando o Active Directory local e/ou as identidades de nuvem.

- Adicionar usuários à sua assinatura do Intune, definir funções de administrador de ti e criar grupos de usuários e de dispositivos.

- Fornecer orientação sobre como migrar do Intune integrado com o System Center Configuration Manager (híbrido) para o Intune autônomo.

- Fornecer orientação sobre como configurar o Azure Active Directory para o registro automático do MDM.

- Forneça orientações sobre como configurar a junção híbrida do Azure Active Directory.

- Fornecer orientação sobre como configurar o gateway de gerenciamento de nuvem

- Habilite o gerenciamento de Cogestão no console do Configuration Manager.

- Configure as cargas de trabalho suportadas que você deseja alternar para o Intune.

- Instale o cliente do Configuration Manager nos dispositivos registrados do Intune.

- Forneça orientações sobre como monitorar a atividade de co-Management em seu ambiente.

O FastTrack também fornece orientações sobre como conduzir a adoção bem-sucedida dos serviços qualificados.

![Fase de habilitação da integração do Intune](./media/ft-enable-phase_intune_mam.png)

![Fase de habilitação da integração do Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![Integração ativar fase de gerenciamento](./media/ft-9-enable-phase-comanagement.png)

#### <a name="enable-phase--azure-information-protection"></a>Fase habilitar – proteção de informações do Azure

A proteção de informações do Azure fornece orientações sobre: 

- Os clientes classifiquem e etiquetem automaticamente as informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e usando o cliente de proteção de informações do Azure. 
- Arquivos em repouso usando o verificador de proteção de informações do Azure.
- Emails em trânsito usando regras de fluxo de email do Exchange Online. 

O suporte também é fornecido aos clientes que desejam aplicar proteção usando o Microsoft Azure Rights Management Services (Azure RMS), criptografia de mensagens do Office 365 (OME) e prevenção de perda de dados (DLP). 

Os clientes são fornecidos com orientações sobre como: 

- Ative e configure seu locatário.
- Criar e configurar rótulos e políticas.
- Aplicar proteção de informações a documentos. 


> [!NOTE]
> **Quer saber mais?** consulte [Enterprise Mobility + Security](https://www.microsoft.com/en-us/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Próximas etapas

[Benefícios do FastTrack para o EMS-responsabilidades da Microsoft](EMS-fasttrack-responsibilities.md)

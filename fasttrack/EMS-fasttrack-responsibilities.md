---
title: Responsabilidades do FastTrack
description: Responsabilidades do FastTrack quando os clientes usam os Benefícios do Centro FastTrack para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 3/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6bf4be4247f65ced12052e75692f9fda47cab0ac
ms.sourcegitcommit: 7a2535e510420496dabfcea5accbb36ab2fe21d2
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/30/2020
ms.locfileid: "43052256"
---
# <a name="fasttrack-responsibilities"></a>Responsabilidades do FastTrack

O FastTrack tem as seguintes responsabilidades durante a integração.

## <a name="general"></a>Geral

-   Fornece suporte de assistência remota para as atividades de configuração necessárias que estão listadas nas descrições detalhadas das fases.

-   Fornecemos a documentação, as ferramentas de software e os consoles de administrador para ajudar a reduzir ou a eliminar as tarefas de configuração.

## <a name="initiate-phase"></a>Fase inicial

-   Trabalha com você para iniciar a integração.

-   Define que serviços qualificados você deseja integrar.

## <a name="assess-phase"></a>Fase Avaliar

-   Fornece uma visão geral administrativa.

-   Fornece orientação sobre:

    -   As necessidades de infraestrutura, rede e DNS.

    -   As necessidades do cliente (navegador da Internet, sistema operacional do cliente e necessidades de serviços)

    -   Identidade do usuário e provisionamento.

    -   Habilitação de serviços qualificados que tenham sido comprados e definidos como parte da integração.

-   Estabelecimento da linha do tempo para atividades de correção.

-   Fornece uma lista de verificação de correção para o Intune e o Azure AD Premium.

## <a name="remediate-phase"></a>Fase de correção

-   Realiza chamadas em conferência com você de acordo com a programação acordada para revisar o andamento das atividades de correção. Por exemplo, o guiará pelos pré-requisitos de instalação antes de integrar um serviço de nuvem da Microsoft.

## <a name="enable-phase"></a>Fase Habilitar
Fornece orientação sobre:

-   Ativação do seu locatário ou assinatura do serviço online da Microsoft.

-   Configuração de protocolos TCP/IP e portas do firewall.

-   Configuração do DNS para serviços qualificados.

-   Validação da conectividade com os serviços online da Microsoft.

-   Para um ambiente de floresta única:

    -   Instalação de um servidor de sincronização de diretórios entre os seus Active Directory Domain Services (AD DS) e os serviços online da Microsoft (orientado apenas se necessário).

    -   Configuração de autenticação gerenciada (Sincronização de Hash da Senha ou Autenticação de Passagem) com a ferramenta Azure Active Directory Connect. (Orientado apenas se necessário).

        > [!NOTE]
        > Desenvolvimento e implementação de extensão de regras personalizadas estão fora do escopo.

-   Para uma única floresta, quando as identidades federadas são o destino: Instalação e configuração dos Serviços de Federação do Active Directory (AD FS) para autenticação de domínio local com o Intune em uma configuração de site único tolerante a falhas, se necessário.

    > [!NOTE]
    > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo.

-   Teste da funcionalidade de logon único (SSO), se implantado.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase de ativação – Microsoft Azure Active Directory Premium

Fornece orientação sobre:

- Ativação do locatário do Azure AD Premium.

- Configuração das portas do firewall.

- Configuração do DNS para serviços qualificados.

- Validação da conectividade aos serviços do Azure AD Premium.

- Para um ambiente de floresta única:

  -   Instalação de um servidor de sincronização de diretórios entre os seus Serviços de Domínio Active Directory (AD DS) e o Azure AD Connect, se necessário.

  -   Configuração de um método de autenticação (Sincronização de Hash da Senha ou Autenticação de Passagem) com a ferramenta Azure AD Connect.

- Para um ambiente de várias floresta:

  -   Instalação da sincronização do Azure AD Connect configurada para vários cenários de floresta.
- Para ambientes com uma única ou várias florestas:
  - Configurar a autenticação de passagem do Azure Active Directory, se necessário.
  - Configurar o logon único (SSO) contínuo do Azure Active Directory, se necessário.
    > [!NOTE]
    > A autenticação de passagem do Azure Active Directory para ambientes com várias florestas será compatível se houver uma relação de confiança na floresta entre as florestas do Active Directory e se o roteamento do sufixo do nome estiver devidamente configurado. Agentes adicionais podem ser instalados em vários servidores locais para oferecer alta disponibilidade para solicitações de entrada.

  - Para obter mais informações, confira [Autenticação de passagem do Azure Active Directory: início rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) e [Logon único contínuo do Azure Active Directory: Início rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Confira mais informações sobre os limites de autenticação de passagem em [Autenticação de passagem do Azure Active Directory: limitações atuais](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Para mais informações sobre problemas de SSO Contínuo, confira [Solucionar problemas de Logon Único Contínuo do Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Sincronização de hash da senha de e write-back de senha dão suporte a várias florestas. No entanto, outros cenários de write-back não possuem suporte.

  - Configuração da sincronização entre florestas locais do Active Directory e do diretório do Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Desenvolvimento e implementação de extensão de regras personalizadas estão fora do escopo.

- Para uma única floresta, quando as identidades federadas são o destino:

  -   Instalação e configuração do AD FS para autenticação de domínio local com o Azure AD Premium em uma configuração de site único e tolerante a falhas (se necessário).

  > [!NOTE]
  > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo.

- Teste da funcionalidade do SSO (se implantado).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Fase de habilitação – Azure AD Premium – com o Azure AD Connect e o AD FS

Fornece orientação sobre a configuração:

- Provisionamento do usuário, inclusive licenciamento.

- Sincronização de diretório do Azure AD Connect (com write-back de senha e sincronização de hash de senha).

  - Autoatendimento de Redefinição de Senha do Azure Active Directory (SSPR).

  - Autenticação Multifator do Azure.

  - Até três (3) ou mais integrações de aplicativos de Software como um serviço (SAAS) com Logon Único (SSO) do [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Provisionamento automático do usuário para aplicativos SaaS pré-instalados, como listados na [Lista de tutoriais de integração de aplicativost](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), limitado apenas ao provisionamento de saída.

  - Tela de logon personalizada, incluindo logotipo, texto e imagens.

  - Autoatendimento e Grupos Dinâmicos (Grupos).

  - Proxy de Aplicativo do Azure Active Directory.

  - Azure Active Directory Connect Health.

  - Acesso Condicional do Azure Active Directory.

  - Termos de uso do Azure Active Directory.

  - Proteção de identidade do Azure Active Directory.

  - Azure Active Directory Privileged Identity Management.

  - Revisões de Acesso do Azure Active Directory.

  -   Proteção de senha do Azure Active Directory.

  -   B2B do Azure Active Directory.

### <a name="enable-phase---intune"></a>Fase de Habilitação – Intune

> [!IMPORTANT]
> O FastTrack não dá suporte ao gerenciamento clássico de computador do Windows 10 com o Intune. O FastTrack é compatível apenas com o gerenciamento do Windows 10 pela autoridade de gerenciamento de dispositivo móvel do Intune (MDM).

Fornece orientações sobre:

-   Configuração de identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Azure Active Directory).

-   Licenciamento para os usuários finais.

-   Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.

-   Configuração da autoridade de Gerenciamento de Dispositivo Móvel (MDM), com base em suas necessidades de gerenciamento, incluindo:

    -   Configuração do Intune como autoridade do MDM.

    -   Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.

    -   Navegação pelo portal de administração do Intune para localizar informações sobre dispositivos e usuários.

    -   Configuração das funções do Intune (Operadora de suporte técnico, administradores, etc.)

    -   Configuração do gerenciamento das políticas e serviços do MDM, como:

        -   Implantação de aplicativos para cada plataforma com suporte por meio de links da web, MSI e/ou links profundos.

        -   Implantação do Office ProPlus em dispositivos Windows 10.

        -   Programas de compra de volume para implantação de aplicativos, incluindo o VPP da Apple, Windows Store for Business e o Google Play for Work Store.

        -   Implantação de email, redes sem fio e perfis VPN se tiver uma autoridade de certificação existente, uma infraestrutura de rede Wi-Fi ou VPN em sua organização.

        -   Configuração do Microsoft Intune Exchange Connector (quando aplicável).

        -   Perfis de configuração de dispositivo para plataformas de dispositivos com suporte.

    -   Configuração das políticas de acesso condicional.

    -   Configuração e implantação das políticas de proteção de aplicativo do Intune para cada plataforma com suporte.

    -   Preparação de aplicativos de linha de negócios (LOB) para políticas de proteção de aplicativos Intune, com orientações nas opções disponíveis.

    -   Registro dos dispositivos de todas as plataformas compatíveis com Intune ou Gerenciador de Configuração com serviço do Microsoft Intune. 

    -   Conexão ao Intune Data Warehouse.

    -   Integração do Intune com:
        -   O Team Viewer para assistência remota (É necessária a assinatura do Team Viewer).

        -   Soluções para parceiros de Defesa contra Ameaças Móveis (É necessária a assinatura de solução para parceiros de Defesa contra Ameaças Móveis). 

        -   Soluções de gerenciamento de despesas de telecomunicações (É necessário o gerenciamento de despesas de telecomunicações).

        -   Proteção Avançada Contra Ameaças do Microsoft Defender (são necessárias licenças do Windows E5 ou Microsoft 365 E5).

    -   Configuração das atualizações de Software para plataformas com suporte aplicável.

    -   Recursos para planejamento de adoção do usuário.

- Configuração do Windows Autopilot:

    - Configuração e instalação do Microsoft Intune para Windows Autopilot.

    - Configuração dos grupos de Azure AD Dynamic 

    - Adição da marca da sua Empresa no Azure AD.

    - Criação e atribuição de dispositivos aos perfis do Windows Autopilot (por exemplo, um perfil do Windows Autopilot que restringe a criação de contas de Administrador Local).

    - Personalização da experiência inicial (OOBE) para ser compatível com os requisitos da organização.

    - Configuração do registro automático MDM no Azure AD e no Intune.

    > [!NOTE]
    > Configuração do Windows Autopilot fora do Intune está fora do escopo dos benefícios do FastTrack.

### <a name="enable-phase---cloud-attach"></a>Fase de habilitação - Vincular à nuvem

Fornece orientações sobre:

-   Licenciamento para os usuários finais.

-   Implementação da vinculação à nuvem no console do Configuration Manager.

-   Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de usuários e grupos de dispositivos (se o Intune não estiver instalado).

-   Configuração da adição híbrida do Azure Active Directory.

-   Configuração do Azure Active Directory para o registro automático do MDM.

-   Configuração do Gateway de Gerenciamento de Nuvem.

-   Adição de usuários à sua assinatura do Intune, definição de funções de administrador de TI e criação de grupos de dispositivos e usuários.

-   Preparando o serviço do Intune para o gerenciamento de dispositivos:

    -   Definição da autoridade de gerenciamento de dispositivo móvel (MDM) para o Intune.

    -   Configuração de grupos de testes a serem usados para validar as políticas de gerenciamento do MDM.

    -   Navegação pelo portal de administração do Intune para localizar informações sobre dispositivos e usuários.

    -   Definição das funções do Intune (operador da assistência técnica, administradores e assim por diante).

    -   Registro de dispositivos com Windows 10 para o Intune.

    -   Alternância de cargas de trabalho para gerenciamento do Intune conforme desejado.

### <a name="enable-phase--azure-information-protection"></a>Fase de habilitação – Proteção de Informações do Azure

Orientações fornecidas sobre: 

- Ativação e configuração do locatário do cliente.

- Criação e configuração dos rótulos e políticas.

- Aplicação de proteção de informações aos documentos. 

- Classificação e rotulação automática de informações em aplicativos do Office (como Word, PowerPoint, Excel e Outlook) em execução no Windows e que usam o Cliente da Proteção de Informações do Azure.

- Uso de arquivos em repouso com o scanner da Proteção de Informações do Azure.

- Monitoramento de emails em trânsito usando as regras de fluxo de email do Exchange Online.

As orientações também são fornecidas aos clientes que desejam aplicar a proteção usando Serviços de Gerenciamento de Direitos do Microsoft Azure (Azure RMS), Criptografia de Mensagens do Office 365 e Prevenção Contra Perda de Dados (DLP).

> [!NOTE]
> **Quer saber mais?**, consulte[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Próximas etapas

[Benefícios do FastTrack para EMS – Suas responsabilidades](EMS-your-responsibilities.md)


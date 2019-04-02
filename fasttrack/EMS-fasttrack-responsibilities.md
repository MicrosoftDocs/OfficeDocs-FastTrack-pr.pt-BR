---
title: Responsibilities do FastTrack
description: Responsabilidades do FastTrack quando os clientes estão usando o benefício do FastTrack Center para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ca5de05adc154a6adb0119fd71de46280cb4cb23
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016907"
---
# <a name="fasttrack-responsibilities"></a>Responsibilities do FastTrack

O FastTrack tem as seguintes responsabilidades durante a integração.

## <a name="general"></a>Geral

-   Forneça assistência remota para as atividades de configuração necessárias, conforme listado nas descrições detalhadas da fase.

-   Fornecer documentação disponível, ferramentas de software e consoles de administração para ajudá-lo a reduzir ou eliminar tarefas de configuração.

## <a name="initiate-phase"></a>Fase Iniciar

-   Trabalhe com você para começar a integração.

-   Define que serviços qualificados você deseja integrar.

## <a name="assess-phase"></a>Fase Avaliar

-   Fornece uma visão geral administrativa.

-   Fornece orientação sobre:

    -   Necessidades de DNS, rede e infraestrutura.

    -   As necessidades do cliente (navegador da Internet, sistema operacional cliente e necessidades dos serviços).

    -   Identidade do usuário e provisionamento.

    -   Habilitar serviços qualificados que foram comprados e definidos como parte da integração.

-   Estabelecimento da linha do tempo para atividades de correção.

-   Fornecer uma lista de verificação de correção para o Intune e o Azure AD Premium.

## <a name="remediate-phase"></a>Fase Corrigir

-   Realizar chamadas de conferência com você de acordo com o cronograma acordado para analisar o progresso das atividades de correção, por exemplo, orientá-lo pelos pré-requisitos de instalação antes de fazer a integração com um serviço de nuvem da Microsoft.

## <a name="enable-phase"></a>Fase Habilitar
Fornece orientação sobre:

-   Ativação do Microsoft Online Service locatário ou assinatura.

-   Configuração de protocolos TCP/IP e portas do firewall.

-   Configuração do DNS para serviços qualificados.

-   Validar a conectividade com o Microsoft Online Services.

-   Para um ambiente de floresta única:

    -   Instalação de um servidor de sincronização de diretório entre o AD DS (serviços de domínio Active Directory) e os serviços online da Microsoft qualificados (somente diretrizes, se necessário).

    -   ConFigurando a autenticação gerenciada (sincronização de hash de senha ou autenticação de passagem) com a ferramenta Azure Active Directory Connect. (apenas diretrizes, se necessário).

        > [!NOTE]
        > O desenvolvimento e a implementação de extensões de regras personalizadas estão fora do escopo.

-   Para uma única floresta quando o destino é federativo identidades: instalar e configurar os serviços de Federação do Active Directory (AD FS) para autenticação de domínio local com o Intune em uma configuração de site único e tolerante a falhas, se necessário.

    > [!NOTE]
    > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo.

-   Testar a funcionalidade de logon único (SSO), se implantada.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase habilitar-Microsoft Azure Active Directory Premium

Fornece orientação sobre:

- Ativação do locatário do Azure AD Premium.

- Configurar portas do firewall.

- Configuração do DNS para serviços qualificados.

- Validar a conectividade com os serviços premium do Azure AD.

- Para um ambiente de floresta única:

  -   Instalação de uma sincronização de diretório entre o AD DS (serviços de domínio Active Directory) e o Azure AD Connect, se necessário.

  -   Configuração de um método de autenticação (sincronização de hash de senha ou autenticação de passagem) com a ferramenta Azure AD Connect.

- Para um ambiente de várias florestas:

  -   Instalação da sincronização do Azure AD Connect, configurada para cenários de várias florestas.
- Para ambientes com uma única ou várias florestas:
  - Configurar a autenticação de passagem do Azure Active Directory, se necessário.
  - Configurar o logon único (SSO) contínuo do Azure Active Directory, se necessário.
    > [!NOTE]
    > A autenticação de passagem do Azure Active Directory para ambientes com várias florestas será compatível se houver uma relação de confiança na floresta entre as florestas do Active Directory e se o roteamento do sufixo do nome estiver devidamente configurado. Agentes adicionais podem ser instalados em vários servidores locais para oferecer alta disponibilidade para solicitações de entrada.

  - Para obter mais informações, confira [Autenticação de passagem do Azure Active Directory: início rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) e [Logon único contínuo do Azure Active Directory: Início rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Para obter mais informações sobre os limites de autenticação de passagem, confira [Autenticação de passagem do Azure Active Directory: Limites atuais](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Para mais informações sobre problemas de SSO Contínuo, confira [Solucionar problemas de Logon Único Contínuo do Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > A sincronização de hash de senha e o Write-back de senha aceitam várias florestas. No enTanto, não há suporte para outros cenários de write-back.

  - Configurar a sincronização entre florestas do Active Directory no local e diretório Premium do Microsoft Azure Active Directory (Azure Active Directory).

    > [!NOTE]
    > O desenvolvimento e a implementação de extensões de regras personalizadas estão fora do escopo.

- Para uma única floresta quando o destino é federativo identidades:

  -   Instalando e Configurando o AD FS para autenticação de domínio local com o Azure AD Premium em uma configuração de site único e tolerante a falhas (se necessário).

  > [!NOTE]
  > Para todas as configurações de várias florestas, as implantações do AD FS estão fora do escopo.

- Testar a funcionalidade de SSO (se implantada).

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Fase habilitar-Azure AD Premium--com o Azure AD Connect e o AD FS

Forneça orientações sobre como configurar:

- Provisionamento de usuário, incluindo licenciamento.

- Sincronização de diretório do Azure AD Connect (com o Write-back de senha e sincronização de hash de senha).

  - ReDefinição de senha de autoAtendimento do Azure Active Directory (SSPR).

  - Autenticação multiFator do Azure.

  - Até três (3) ou mais integrações de aplicativos de software como serviço (SaaS) com logon único (SSO) do [Marketplace do Azure Active Directory](https://azure.microsoft.com/marketplace/active-directory/).

  - Provisionamento automático de usuário para aplicativos SaaS previamente integrados, conforme listado na [lista de tutorial de integração de aplicativos](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitado somente a provisionamento de saída.

  - Tela de logon personalizada, incluindo logotipo, texto e imagens.

  - Grupos de autoAtendimento e dinâmicos (grupos).

  - Proxy de aplicativo do Azure Active Directory.

  - Integridade do Azure Active Directory Connect.

  - Acesso condicional do Azure Active Directory.

  - Termos de uso do Azure Active Directory.

  - Proteção de identidade do Azure Active Directory.

  - Gerenciamento de identidade privilegiada do Azure Active Directory.

  - Revisões do acesso ao Active Directory do Azure.

### <a name="enable-phase---intune"></a>Fase habilitar-Intune

> [!IMPORTANT]
> O FastTrack não dá suporte ao gerenciamento clássico de computador com o Windows 10 com o Intune. O FastTrack oferece suporte somente ao gerenciamento do Windows 10 por meio do gerenciamento de dispositivo móvel do Intune (MDM).

Fornecer **orientações** sobre:

-   Configurar identidades a serem usadas pelo Intune, aproveitando o Active Directory local ou as identidades de nuvem (Azure Active Directory).

-   Licenciar seus usuários finais.

-   Adicionar usuários à sua assinatura do Intune, definir funções de administrador de ti e criar grupos de usuários e de dispositivos.

-   Configurar sua autoridade de gerenciamento de dispositivo móvel do MDM, com base em suas necessidades de gerenciamento, incluindo:

    -   Configuração do Intune como sua autoridade MDM.

    -   Configuração de grupos de testes a serem usados para validar políticas de gerenciamento do MDM.

    -   Navegar pelo portal de administração do Intune para localizar informações sobre usuários e dispositivos.

    -   Configuração de funções do Intune (operadora de assistência técnica, administradores, etc.)

    -   ConFigurando serviços e políticas de gerenciamento do MDM como:

        -   Implantação de aplicativo para cada plataforma suportada por meio de links da Web, MSI e/ou links profundos.

        -   Implantação do Office proPlus em dispositivos Windows 10.

        -   Programas de compra de volume para implantação de aplicativos, incluindo o VPP da Apple, a Windows Store para empresas e o Google Play para o repositório de trabalho.

        -   Implantação de email, redes sem fio e perfis de VPN se você tiver uma autoridade de certificação, Wi-Fi ou infraestrutura de VPN existente em sua organização.

        -   Configuração do Microsoft Intune Exchange Connector (quando aplicável).

        -   Perfis de configuração de dispositivo para plataformas de dispositivo suportadas.

    -   Configuração de políticas de acesso condicional.

    -   Configurar e implantar as políticas de proteção de aplicativos do Intune para cada plataforma suportada.

    -   Preparar aplicativos de LOB (linha de negócios) para políticas de proteção de aplicativos do Intune, com orientações sobre as opções disponíveis.

    -   Registrar dispositivos de cada plataforma suportada no seu Intune ou no Gerenciador de configuração com o serviço do Microsoft Intune.

    -   Conexão ao armazém de dados do Intune.

    -   Integração do Intune com:
        -   Team Viewer para assistência remota (a assinatura do Team Viewer é necessária).

        -   Soluções de parceiros de defesa contra ameaças móveis (a assinatura do Mobile Threat Defense Partner Solution é necessária).

        -   Soluções de gerenciamento de despesas de telecomunicações (a assinatura da solução de gerenciamento de despesas de telecomunicações é necessária).

        -   A proteção avançada contra ameaças do Windows Defender (licenças do Windows E5 ou do Microsoft 365 E5 são necessárias).

    -   Configuração de atualizações de software para plataformas compatíveis aplicáveis.

    -   Recursos para o planejamento de adoção do usuário.

- ConFigurando o piloto automático do Windows:

    - Configurar e configurar o piloto automático do Microsoft Intune para Windows.

    - Configurar grupos dinâmicos do Azure AD

    - Adicione a identidade visual da empresa no Azure AD.

    - Crie e atribua dispositivos aos perfis do Windows AutoPilot (por exemplo, um perfil do Windows AutoPilot que restringe a criação de contas de administrador local).

    - Personalizar o OOBE (uso da experiência) para cumprir os requisitos da organização.

    - ConFigurando o registro automático do MDM no Azure AD e no Intune.

    > [!NOTE]
    > Configurar o Windows AutoPilot fora do Intune está fora do escopo para o benefício do FastTrack.

### <a name="enable-phase---co-management"></a>Habilitar o gerenciamento em fases

Fornece orientação sobre:

-   Licenciar seus usuários finais.

-   Adição de usuários à sua assinatura do Intune, definição de funções de administrador de ti e criação de grupos de usuários e dispositivos (se o Intune não estiver instalado).

-   Configuração do Azure Active Directory para o registro automático do MDM.

-   Configurar ingresso híbrida do Azure Active Directory.

-   Configurar o gateway de gerenciamento de nuvem.

-   Adicionar usuários à sua assinatura do Intune, definir funções de administrador de ti e criar grupos de usuários e de dispositivos.

-   Preparar o Intune (se o Intune não estiver instalado):

    -   Configurar sua autoridade de gerenciamento de dispositivo móvel do MDM, com base em suas necessidades de gerenciamento, incluindo:

    -   Configuração do Intune como sua autoridade MDM.

    -   Configuração de grupos de testes a serem usados para validar políticas de gerenciamento do MDM.

    -   Navegar pelo portal de administração do Intune para localizar informações sobre usuários e dispositivos.

    -   Configuração de funções do Intune (operadora de assistência técnica, administradores, etc.)

    -   Configurar e implantar as políticas de proteção de aplicativos do Intune para cada plataforma suportada.

    -   Registrar dispositivos Windows 10 no seu Intune.

- Habilite o gerenciamento de coGestão no console do Configuration Manager.

- Mudar cargas de trabalho para o Intune.

- Monitore a atividade de co-Management em seu ambiente.

> [!NOTE]
> **Quer saber mais?** consulte [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Próximas etapas

[Benefícios do FastTrack para o EMS-suas responsabilidades](EMS-your-responsibilities.md)

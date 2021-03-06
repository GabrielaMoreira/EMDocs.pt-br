---
title: Expectativas para o ambiente de origem
description: Requisitos de ambiente de origem para usar o Benefício do FastTrack Center para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 06/01/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: d3faae6afb90ab44af454fa194a7f9f65e14bd80
ms.sourcegitcommit: 3a51276eebdd8f1f18994a7efdcaa22e394180df
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/04/2018
ms.locfileid: "34569503"
---
# <a name="source-environment-expectations"></a>Expectativas para o Ambiente de Origem

Quando você usa o [Benefício do FastTrack Center para EMS (Enterprise Mobility + Security)](fasttrack-center-benefit-for-enterprise-mobility-suite-ems.md) para tornar o Microsoft Azure Active Directory Premium e o Microsoft Intune prontos para uso, seu ambiente precisa atender às expectativas descritas nas seções a seguir.

Talvez você já tenha o Active Directory local em sua organização e queira integrá-lo com o EMS ou com qualquer um de seus serviços individuais a fim de aproveitar o gerenciamento avançado de identidade em um único console. O Benefício do FastTrack Center para EMS ajuda você a integrar o Azure Active Directory com seu ambiente atual do Active Directory local.

A tabela a seguir mostra o que é esperado do seu ambiente de origem existente para integração.

|Atividade|Expectativa para o ambiente de origem|
|------------|----------------------------------|
|Integração de núcleo|Florestas do Active Directory com o nível funcional de floresta definido como Windows Server 2008 ou superior, com a seguinte configuração de floresta:<br /><br />-   Floresta única do Active Directory<br />-   Várias florestas do Active Directory </br></br>**Observação**: para todas as configurações com várias florestas, a implantação do AD FS (Serviços de Federação do Active Directory) está fora do escopo do Benefício do FastTrack Center.|
|Integração do Azure AD Premium|O Active Directory local e seu ambiente foram preparados para o Azure AD Premium, que inclui a correção dos problemas identificados que poderiam impedir a integração com o Azure AD e os recursos do Azure AD Premium.|
|Intune, somente em nuvem ou integrado ao System Center Configuration Manager, integração|Para gerenciamento de dispositivos com o Configuration Manager 2012 R2 ou posterior, conectado ao Intune, os administradores de TI precisam seguir a [Lista de verificação do administrador: configurando o Configuration Manager para gerenciar dispositivos móveis usando o Microsoft Intune](https://technet.microsoft.com/library/jj943763.aspx).</br></br> **Observação**: o benefício de serviço não inclui assistência para configurar ou atualizar o Configuration Manager para os requisitos mínimos necessários para a integração do Microsoft Intune com o Configuration Manager. </br></br>Para implantação de perfil de Wi-Fi e VPN, os administradores de TI precisam ter infraestruturas de Wi-Fi, VPN e autoridade de certificação existentes e já em funcionamento nos ambientes de produção.</br></br> **Observação**: o benefício do serviço não inclui assistência para instalação ou configuração de infraestruturas de Wi-Fi, VPN ou autoridades de certificação. |
|Cogerenciamento|Com o cogerenciamento, os administradores de TI são responsáveis por preparar o ambiente local, o que pode incluir a correção dos problemas que impedem você de gerenciar simultaneamente os dispositivos Windows 10 usando o Configuration Manager e o Intune. </br></br> **Observação**: o benefício do serviço FastTrack não inclui assistência para configurar ou atualizar o servidor de site do Configuration Manager e/ou o cliente do Configuration Manager com os requisitos mínimos necessários para dar suporte ao cogerenciamento com dispositivos Windows 10. |
|Intune integrado ao Windows Defender ATP (Proteção Avançada contra Ameaças do Windows Defender)|Sua assinatura do Windows Defender ATP foi ativada e configurada com base nos requisitos de segurança da sua empresa.<br /><br />**Observação**: o benefício do serviço FastTrack fornece assistência para integrar o Intune ao Windows Defender ATP e criar políticas de conformidade do dispositivo com base na avaliação de nível de risco do Windows 10. O benefício do serviço FastTrack não dá assistência na compra, no licenciamento, na ativação nem no uso do Windows Defender ATP e seu console central de segurança. |

> [!NOTE]
> **Quer saber mais?**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Próximas etapas

[Benefício do FastTrack Center para as fases de migração e integração do EMS](fasttrack-center-benefit-process-for-ems-phases.md)

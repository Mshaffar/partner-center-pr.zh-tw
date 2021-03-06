---
title: 建立使用者帳戶與設定權限 | 合作夥伴中心
ms.topic: article
ms.date: 02/26/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: 了解如何在合作夥伴中心內，為每位需要存取權的員工建立使用者帳戶並指派角色。 具有不同系統管理員權限的使用者都可以執行此動作。
ms.assetid: 75D805AE-9922-4CFD-9427-196047D70963
author: LauraBrenner
ms.author: labrenne
Keywords: 角色, 權限, 新增使用者, 指派角色, 系統管理員, 代理人,
ms.localizationpriority: high
ms.openlocfilehash: f163e37f537f537b6eae086e355c87d892d1a745
ms.sourcegitcommit: faf7b1ac1653497f963b428bbfafcd821378adaa
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2020
ms.locfileid: "82798486"
---
# <a name="create-user-accounts-and-assign-permissions"></a>建立使用者帳戶和指派權限

**適當的角色**

- 帳戶管理員
- 全域系統管理員
- 使用者管理系統管理員

為需要存取合作夥伴中心的員工建立使用者帳戶。 這些工作必須由使用者管理系統管理員、帳戶系統管理員或全域系統管理員來完成。執行這些工作的使用者也必須獲派 Azure Active Directory (AAD) 的「使用者管理員」或「全域管理員」角色。 如需 AAD 角色的詳細資訊，請參閱 [Azure Active Directory 中的管理員角色權限](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-assign-admin-roles)。


## <a name="add-a-new-user"></a>新增使用者

1. 從合作夥伴中心右上角的 [設定]  圖示中，選取 [使用者管理]  。

2. 選取 [新增使用者]  。

3. 輸入使用者的全名和唯一電子郵件地址。

4. 選取您要指派給使用者的代理人類型及/或系統管理員類型。 合作夥伴中心存取權是以角色為基礎，讓您可以指派權限，自訂使用者檢視，只顯示使用者完成特定工作所需的功能。  若使用者想要角色指派，他們可以移至 [使用者管理]  並篩選全域系統管理員，找到要連絡的全域系統管理員。

5. 選取 [新增]  建立使用者帳戶。 在下一頁，確認使用者的詳細資料。

> [!IMPORTANT]  
> 記下此頁面上顯示的新使用者登入資訊。 請務必將這項資訊複製及傳送給新的使用者，因為稍後您將無法再次存取。 


使用者必須使用其使用者名稱和暫時密碼登入合作夥伴中心。 當使用者第一次登入合作夥伴中心時，系統會提示他們變更密碼。 


### <a name="find-your-global-admin"></a>尋找您的全域系統管理員

有時候使用者可能需要變更其角色，或者新的使用者可能想要特定的角色指派。  
若要尋找可進行角色變更或將角色指派給新使用者的全域系統管理員，請從合作夥伴中心右上角的 [設定]  圖示中選取 [使用者管理]  ，然後篩選全域系統管理員。 


### <a name="new-global-admin"></a>新的全域系統管理員

如果您的全域系統管理員離開組織，而需要其他人擔任此角色，則可以將票證提交給 Azure 或 Office 365 小組。 如需執行這項操作的相關資訊，請選取下列其中一個選項。

[新的 Azure 全域系統管理員](https://support.microsoft.com/help/4505981/what-to-do-if-the-only-admin-for-your-mpn-program-has-left-the-company)

[新的 Office 365 全域系統管理員](https://admin.microsoft.com/)


## <a name="assign-user-roles"></a>指派使用者角色

若要在合作夥伴中心中工作，您必須具有指派的角色。  目前，這些角色包括 Azure Active Directory 租用戶角色、雲端解決方案提供者 (CSP) 角色，以及非 AAD 公司角色。 個別公司可能需要所有這些角色。

>[!Important]
>個人必須列示在您的租用戶中，才能存取合作夥伴中心。 角色指派會提供額外的存取權。


**AAD 租用戶角色包括**：
- 全域系統管理員
- 使用者系統管理員

**CSP 角色包括**：
- 系統管理代理人
- 帳單系統管理員
- 銷售代理人
- 技術服務代理人

**管理 MPN 會員資格和公司 (非 AAD) 的角色**
- MPN 合作夥伴系統管理員
- 帳戶管理員
- 推薦系統管理員
- 商務設定檔管理員
- 獎勵系統管理員和使用者

**控制台廠商是 CSP 和非 AAD 角色**。
- 全域系統管理員

**來賓使用者**必須是 AAD 租用戶的一部分，而且可以具有任何非 AAD 角色。

如需角色的特定資訊以及每個角色可以執行哪些任務的相關資訊，請參閱[指派使用者權限](permissions-overview.md)。

## <a name="associate-a-users-microsoft-learn-account-in-partner-center"></a>關聯使用者在合作夥伴中心的 Microsoft Learn 帳戶

為了能夠看到您的使用者對專長認證所採取的訓練和學習路徑，他們必須將其 MCP 識別碼關聯至其合作夥伴中心帳戶。 身為全域系統管理員，當您新增使用者時，請務必提醒他們將其 MCP 識別碼關聯至其帳戶。 

### <a name="how-to-associate-your-mcp-id-to-your-partner-center-account"></a>如何將您的 MCP 識別碼關聯至您的合作夥伴中心帳戶

1. 從合作夥伴中心儀表板，選取儀表板右上角的 [您的帳戶]  圖示，然後選取 [我的設定檔]  。

2. 在 [您的學習]  之下，您將能夠關聯 Microsoft Learning 帳戶，也可以將您的 Microsoft 帳戶連線到 Partner University。








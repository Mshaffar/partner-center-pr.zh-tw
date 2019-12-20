---
title: Azure AD 服務主體 |合作夥伴中心
ms.topic: article
ms.date: 12/11/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: 將服務主體新增至您的 Azure AD 租用戶
author: LauraBrenner
ms.author: labrenne
Keywords: Azure、Azure 方案、服務主體、Azure AD 應用程式
robots: ''
ms.localizationpriority: High
ms.openlocfilehash: 1fe4211879df2063f7b865c249870c49a346f518
ms.sourcegitcommit: 369aceafc54e960ac0bd3a023edc85b06361492b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/12/2019
ms.locfileid: "75010379"
---
# <a name="add-an-azure-ad-application-service-principal-in-partner-center"></a>在合作夥伴中心新增 Azure AD 應用程式 (服務主體)

在合作夥伴中心的商務 Marketplace 計畫中，您現在可以將 Azure AD 應用程式 (服務主體) 新增為 Azure AD 租用戶中的使用者 (您可以先在 Cloud Partner 入口網站 (CPP) 帳戶中執行此動作，但現在您已移轉至合作夥伴中心，而 CPP 帳戶是唯讀的)。請注意，服務主體與 Azure AD 應用程式是同義。

## <a name="add-an-azure-ad-application-service-principal"></a>新增 Azure AD 應用程式 (服務主體)

1. 在合作夥伴中心儀表板，選取 [設定]  ，然後選取 [開發人員設定]  。

2. 選取 [使用者]  ，然後選取 [新增 Azure AD 應用程式]  。

3. 選取現有的 Azure AD 應用程式，或建立新的應用程式。

4. 如果建立新的 Azure AD 應用程式，請包含下列資訊：  
  
**名稱**：這與 CPP 入口網站中的 [易記名稱] 欄位類似。

**回覆 URL**：這是讓使用者登入以使用您的 Azure AD 應用程式的 URL。 

**應用程式識別碼 URI**：這是 Azure AD 應用程式的邏輯識別碼，是在傳送單一登入要求至 Azure AD 時提供。 

**安全性角色**：**管理員** (與 CPP 中的「擁有者」角色相同) 和**開發人員** (與 CPP 中的「參與者」角色相同) 角色適用於合作夥伴中心內的商務 Marketplace 計畫，而且可與此 Azure AD 應用程式相關聯。  

當您選取 [儲存]  以在合作夥伴中心建立此資訊時，此資訊也會同步處理至 CPP 系統。  
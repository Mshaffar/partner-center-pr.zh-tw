---
title: 讓客戶在 CSP 中購買自己的服務
description: 瞭解 CSP 方案合作夥伴如何讓客戶針對在合作夥伴中心購買的訂用帳戶購買自己的服務（例如 Azure 保留）。
ms.topic: article
ms.date: 05/18/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: LauraBrenner
ms.author: labrenne
Keywords: 訂用帳戶，自助式購買，自助 RI，啟用 RI，停用 RI，自助，客戶購買，客戶許可權，客戶購買保留實例，客戶購買 Azure 保留，開啟自助服務，關閉自助服務
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: d04f7aad779a6bf3be08b24f43da6abc4dfdac4d
ms.sourcegitcommit: 2a980b50cf177753c15ebfd7770e14cf6d486cf7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/22/2020
ms.locfileid: "83795109"
---
# <a name="give-customers-permission-in-partner-center-to-buy-their-own-products-or-services"></a><span data-ttu-id="03e74-104">授與客戶合作夥伴中心的許可權，以購買自己的產品或服務</span><span class="sxs-lookup"><span data-stu-id="03e74-104">Give customers permission in Partner Center to buy their own products or services</span></span>

<span data-ttu-id="03e74-105">**適用於**</span><span class="sxs-lookup"><span data-stu-id="03e74-105">**Applies to**</span></span>

- <span data-ttu-id="03e74-106">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="03e74-106">Partner Center</span></span>
- <span data-ttu-id="03e74-107">雲端解決方案提供者方案中的合作夥伴</span><span class="sxs-lookup"><span data-stu-id="03e74-107">Partners in the CSP program</span></span>

<span data-ttu-id="03e74-108">**適當的角色**</span><span class="sxs-lookup"><span data-stu-id="03e74-108">**Appropriate roles**</span></span>

- <span data-ttu-id="03e74-109">系統管理代理人</span><span class="sxs-lookup"><span data-stu-id="03e74-109">Admin agent</span></span>
- <span data-ttu-id="03e74-110">銷售代理人</span><span class="sxs-lookup"><span data-stu-id="03e74-110">Sales agent</span></span>

<span data-ttu-id="03e74-111">本文說明雲端解決方案提供者（CSP）方案中的合作夥伴如何提供客戶購買部分自己的服務或資源的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-111">This article shows how a partner in the Cloud Solution Provider (CSP) program can give a customer permission to buy some of their own services or resources.</span></span>

<span data-ttu-id="03e74-112">CSP 方案中的合作夥伴通常會使用合作夥伴中心和其商業 marketplace，為客戶購買解決方案和服務。</span><span class="sxs-lookup"><span data-stu-id="03e74-112">Partners in the CSP program often use Partner Center and its commercial marketplace to buy solutions and services for their customers.</span></span> <span data-ttu-id="03e74-113">然後，合作夥伴可以讓某些客戶直接從 Azure 入口網站布建這些服務。</span><span class="sxs-lookup"><span data-stu-id="03e74-113">Partners then allow some customers to provision these services themselves directly from the Azure portal.</span></span>

<span data-ttu-id="03e74-114">以下是範例。</span><span class="sxs-lookup"><span data-stu-id="03e74-114">Here's an example.</span></span> <span data-ttu-id="03e74-115">假設您在合作夥伴中心購買客戶的 Azure 方案訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-115">Let's say you buy an Azure Plan subscription for a customer in Partner Center.</span></span> <span data-ttu-id="03e74-116">接著，您決定將其他資源或服務新增至該訂用帳戶（代表客戶）。</span><span class="sxs-lookup"><span data-stu-id="03e74-116">You then decide to add other resources or services to that subscription on the customer's behalf.</span></span> <span data-ttu-id="03e74-117">在此情況下，您可以將 Azure 保留專案新增至客戶的訂用帳戶（例如，新增保留的虛擬機器實例）。</span><span class="sxs-lookup"><span data-stu-id="03e74-117">In this case, you might add Azure reservations to the customer's subscription (such as, adding reserved, virtual machine instances).</span></span> <span data-ttu-id="03e74-118">接著，您可以允許客戶進一步在 Azure 入口網站中布建 Azure 保留資源本身。</span><span class="sxs-lookup"><span data-stu-id="03e74-118">You might then allow the customer to further provision the Azure reservation resources themselves in the Azure portal.</span></span>

<span data-ttu-id="03e74-119">現在，透過**客戶**權力功能，您可以使用 Azure 資源為客戶提供更多的自助選項。</span><span class="sxs-lookup"><span data-stu-id="03e74-119">Now, with the **Customer permissions** feature, you give customers more self-service options with Azure resources.</span></span> <span data-ttu-id="03e74-120">藉由開啟客戶的許可權，您可以讓客戶購買自己的資源（例如購買自己的 Azure 保留）。</span><span class="sxs-lookup"><span data-stu-id="03e74-120">By turning on permissions for the customer, you allow customers to buy their own resources (such as, buying their own Azure reservations).</span></span>  

## <a name="overview-of-customer-permissions-in-partner-center"></a><span data-ttu-id="03e74-121">合作夥伴中心的客戶許可權總覽</span><span class="sxs-lookup"><span data-stu-id="03e74-121">Overview of customer permissions in Partner Center</span></span>

<span data-ttu-id="03e74-122">使用 [客戶**帳戶**] 頁面，即可開啟（或關閉）客戶的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-122">Use the Customer **Account** page to turn on (or turn off) customer permissions.</span></span> <span data-ttu-id="03e74-123">目前，這項功能支援：</span><span class="sxs-lookup"><span data-stu-id="03e74-123">Currently, this feature supports:</span></span>

- <span data-ttu-id="03e74-124">**Azure 保留：** 開啟此許可權可讓客戶為您購買的特定 Azure 訂用帳戶購買自己的 Azure 保留專案。</span><span class="sxs-lookup"><span data-stu-id="03e74-124">**Azure reservations:** Turning on this permission allows the customer to purchase their own Azure reservations for a specific Azure subscription you've purchased for them.</span></span>

<span data-ttu-id="03e74-125">在您開啟客戶許可權之前，請注意下列重點：</span><span class="sxs-lookup"><span data-stu-id="03e74-125">Before you turn on customer permissions, note these important points:</span></span>

- <span data-ttu-id="03e74-126">根據預設，合作夥伴中心內的客戶許可權會自動停用（關閉）。</span><span class="sxs-lookup"><span data-stu-id="03e74-126">By default, customer permissions are automatically disabled (turned off) in Partner Center.</span></span>

- <span data-ttu-id="03e74-127">您必須先將 [合作夥伴中心] 中的 [系統管理員] 角色指派給您，才可以開啟或關閉客戶的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-127">Before you can turn on (or turn off) permissions for a customer, you must be assigned the role of Admin Agent in Partner Center.</span></span>

  <span data-ttu-id="03e74-128">獲派「銷售代理程式」或「服務台」代理程式角色具有唯讀存取權，且無法開啟或關閉客戶許可權的夥伴。</span><span class="sxs-lookup"><span data-stu-id="03e74-128">Partners assigned the role of Sales Agent or Help Desk Agent have read-only access and can't turn customer permissions on or off.</span></span>

- <span data-ttu-id="03e74-129">您可以為您選擇的任何客戶開啟（啟用）許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-129">You can turn on (enable) permissions for any customer you choose.</span></span>

- <span data-ttu-id="03e74-130">您可以使用合作夥伴中心儀表板或[合作夥伴中心 api](https://docs.microsoft.com/partner-center/develop/manage-customers)來開啟（或關閉）客戶的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-130">You can turn on (or turn off) customer permissions using either the Partner Center dashboard or [Partner Center APIs](https://docs.microsoft.com/partner-center/develop/manage-customers).</span></span>

- <span data-ttu-id="03e74-131">在您開啟（啟用）特定客戶的許可權之後，您會負責支付該客戶所做的任何後續購買。</span><span class="sxs-lookup"><span data-stu-id="03e74-131">After you turn on (enable) permissions for a specific customer, you will be responsible to pay for any subsequent purchases made by that customer.</span></span> <span data-ttu-id="03e74-132">若客戶想要交換、取消或續訂已進行的購買（或他們想要變更保留的初始範圍），他們將無法自行執行。</span><span class="sxs-lookup"><span data-stu-id="03e74-132">If customers want to exchange, cancel or renew a purchase they've made (or they want to change the initial scope of a reservation), they will not be able to do so themselves.</span></span> <span data-ttu-id="03e74-133">他們需要以合作夥伴的身分詢問您，以協助他們交換、取消和續約購買，或對保留範圍進行變更。</span><span class="sxs-lookup"><span data-stu-id="03e74-133">They need to ask you, as the partner, to help them exchange, cancel, and renew purchases, or make later changes to a reservation's scope.</span></span>  

- <span data-ttu-id="03e74-134">開啟特定客戶的許可權之後，您將**不會**收到任何稍後的客戶購買通知。</span><span class="sxs-lookup"><span data-stu-id="03e74-134">After you turn on permissions for a specific customer, you will **not be** notified of any later purchases made by the customer.</span></span>

- <span data-ttu-id="03e74-135">客戶日後購買的內容將會顯示在合作夥伴中心，以及您所做的任何購買。</span><span class="sxs-lookup"><span data-stu-id="03e74-135">Later purchases made by the customer will appear in Partner Center along with any purchases made by you.</span></span> <span data-ttu-id="03e74-136">您可以在客戶的 [**訂單歷程記錄**] 頁面、[**保留**] 頁面或 [[**活動記錄**](activity-logs.md)] 中找到這些購買專案。</span><span class="sxs-lookup"><span data-stu-id="03e74-136">You can find these purchases on the customer's **Order history** page, their **Reservations** page, or in the [**Activity Log**](activity-logs.md).</span></span>

>[!NOTE]
> <span data-ttu-id="03e74-137">如需客戶將支付的價格，以及如何協助客戶管理其購買的相關資訊，請參閱[協助客戶管理他們所購買的保留](give-customers-permission.md#help-customers-manage-reservations-they-purchase)。</span><span class="sxs-lookup"><span data-stu-id="03e74-137">For information about prices the customer will pay and how to help customers manage their purchases, see [Help customers manage reservations they purchase](give-customers-permission.md#help-customers-manage-reservations-they-purchase).</span></span>

## <a name="give-customers-permission-to-buy-their-own-azure-reservations"></a><span data-ttu-id="03e74-138">授與客戶購買自己的 Azure 保留的許可權</span><span class="sxs-lookup"><span data-stu-id="03e74-138">Give customers permission to buy their own Azure reservations</span></span>

<span data-ttu-id="03e74-139">Azure 保留是以折扣費率購買 Azure 服務的絕佳方式。</span><span class="sxs-lookup"><span data-stu-id="03e74-139">Azure reservations are a great way to buy Azure services at a discounted rate.</span></span> <span data-ttu-id="03e74-140">若要深入瞭解 Azure 保留的優點，請參閱[什麼是 Azure 保留專案？](https://docs.microsoft.com/azure/cost-management-billing/reservations/save-compute-costs-reservations)</span><span class="sxs-lookup"><span data-stu-id="03e74-140">To learn more about the benefits of Azure reservations, see [What are Azure Reservations?](https://docs.microsoft.com/azure/cost-management-billing/reservations/save-compute-costs-reservations)</span></span>

<span data-ttu-id="03e74-141">現在您可以選擇代表您的客戶購買 Azure 保留，因為您可能已經完成。</span><span class="sxs-lookup"><span data-stu-id="03e74-141">Now you have the choice to buy Azure reservations on behalf of your customers, as you may have already been doing.</span></span> <span data-ttu-id="03e74-142">或者，您可以授與客戶購買自己的 Azure 保留區的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-142">Or, you can give customers permission to buy their own Azure reservations.</span></span>

>[!NOTE]
> <span data-ttu-id="03e74-143">在您授與客戶購買自己的 Azure 保留的許可權之後，請協助他們管理所購買的任何保留。</span><span class="sxs-lookup"><span data-stu-id="03e74-143">After you give customers permission to buy their own Azure reservations, help them manage any reservations they purchase.</span></span> <span data-ttu-id="03e74-144">如需詳細資訊，請參閱[協助客戶管理他們所購買的保留](give-customers-permission.md#help-customers-manage-reservations-they-purchase)。</span><span class="sxs-lookup"><span data-stu-id="03e74-144">For more information, see [Help customers manage reservations they purchase](give-customers-permission.md#help-customers-manage-reservations-they-purchase).</span></span>

### <a name="to-enable-customers-to-buy-their-own-azure-reservations"></a><span data-ttu-id="03e74-145">讓客戶購買自己的 Azure 保留專案</span><span class="sxs-lookup"><span data-stu-id="03e74-145">To enable customers to buy their own Azure reservations</span></span>

1. <span data-ttu-id="03e74-146">確認客戶已有您購買的現有 Azure 方案或 Azure 全域訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-146">Verify the customer has an existing Azure Plan or Azure Global subscription you purchased on their behalf.</span></span>

2. <span data-ttu-id="03e74-147">確認客戶已獲指派此訂用帳戶的**擁有**者角色。</span><span class="sxs-lookup"><span data-stu-id="03e74-147">Verify the customer has been assigned the **Owner** role for this subscription.</span></span>

3. <span data-ttu-id="03e74-148">啟用客戶權力 **（開啟此功能）** 來購買自己的 Azure 保留。</span><span class="sxs-lookup"><span data-stu-id="03e74-148">Enable customer permissions (turn this feature **On**) to purchase their own Azure reservations.</span></span>

<span data-ttu-id="03e74-149">每個步驟如下所示。</span><span class="sxs-lookup"><span data-stu-id="03e74-149">Each step appears below.</span></span>

### <a name="verify-the-customer-has-an-existing-azure-subscription"></a><span data-ttu-id="03e74-150">確認客戶有現有的 Azure 訂用帳戶</span><span class="sxs-lookup"><span data-stu-id="03e74-150">Verify the customer has an existing Azure subscription</span></span>

<span data-ttu-id="03e74-151">在您授與客戶購買自己的 Azure 保留專案的許可權之前，您必須確認客戶有現有的 Azure 方案或 Azure 全域訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-151">Before you give customers permission to buy their own Azure reservations, you must verify the customer has an existing Azure Plan or Azure Global subscription.</span></span> <span data-ttu-id="03e74-152">如果客戶在合作夥伴中心沒有顯示目前的 Azure 訂用帳戶，您必須先為他們購買訂用帳戶，然後再開啟其客戶許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-152">If the customer shows no current Azure subscription in Partner Center, you must buy a subscription for them before you turn on their customer permissions.</span></span>

- <span data-ttu-id="03e74-153">若要查看客戶是否已有 Azure 訂用帳戶，請登入 [合作夥伴中心] 儀表板，然後選取 [ **CSP** ] 和 [**客戶**]。</span><span class="sxs-lookup"><span data-stu-id="03e74-153">To see if a customer already has an Azure subscription, sign into the Partner Center dashboard, then select **CSP** followed by **Customers**.</span></span> <span data-ttu-id="03e74-154">從清單中選取特定的客戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-154">Select the specific customer from the list.</span></span> <span data-ttu-id="03e74-155">**然後選取 [** 訂用帳戶]，然後尋找 azure 方案或 azure Global 的任何以使用量為基礎的訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-155">Then select **Subscriptions** and look for any usage-based subscriptions for either Azure Plan or Azure Global.</span></span>

- <span data-ttu-id="03e74-156">如果客戶沒有現有的 Azure 訂用帳戶，您可以為他們購買訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-156">If a customer doesn't have an existing Azure subscription, you can buy a subscription for them.</span></span> <span data-ttu-id="03e74-157">請參閱[購買 Azure 方案](purchase-azure-plan.md)。</span><span class="sxs-lookup"><span data-stu-id="03e74-157">See [Purchase the Azure Plan](purchase-azure-plan.md).</span></span>

### <a name="verify-the-customer-has-been-assigned-the-correct-role-in-azure"></a><span data-ttu-id="03e74-158">確認已在 Azure 中為客戶指派正確的角色</span><span class="sxs-lookup"><span data-stu-id="03e74-158">Verify the customer has been assigned the correct role in Azure</span></span>

<span data-ttu-id="03e74-159">在您確認客戶擁有現有的 Azure 訂用帳戶之後，您也需要確認與您的客戶相關聯的金鑰使用者已獲指派該 Azure 訂用帳戶的正確**擁有**者角色。</span><span class="sxs-lookup"><span data-stu-id="03e74-159">After you verify the customer has an existing Azure subscription, you also need to verify the key users associated with your customer have been assigned the correct **Owner** role for that Azure subscription.</span></span> <span data-ttu-id="03e74-160">這是客戶需要為您購買的 Azure 訂用帳戶購買 Azure 保留的角色型存取（RBAC）。</span><span class="sxs-lookup"><span data-stu-id="03e74-160">This is the role-based access (RBAC) the customer needs to buy Azure reservations for an Azure subscription you purchased.</span></span>

<span data-ttu-id="03e74-161">某些合作夥伴可能已將「**擁有**者」角色指派給想要主動管理和布建自己的 Azure 資源的客戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-161">Some partners may have already assigned the **Owner** role to customers wanting to actively manage and provision their own Azure resources.</span></span> <span data-ttu-id="03e74-162">如果您已將 [**擁有**者] 狀態指派給客戶，以管理您為其購買的先前訂用帳戶，則可以略過此步驟。</span><span class="sxs-lookup"><span data-stu-id="03e74-162">If you have already assigned **Owner** status to a customer to manage prior subscriptions you've purchased for them, you can skip this step.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="03e74-163">如果尚未將「**擁有**者」角色指派給客戶，他們會在 Azure 入口網站中收到錯誤，使其無法購買 Azure 保留。</span><span class="sxs-lookup"><span data-stu-id="03e74-163">If a customer has not been assigned the **Owner** role, they will receive an error in the Azure portal preventing them from buying Azure reservations.</span></span>

<span data-ttu-id="03e74-164">若要確認客戶已獲指派 Azure 訂用帳戶的**擁有**者角色：</span><span class="sxs-lookup"><span data-stu-id="03e74-164">To verify the customer has been assigned the **Owner** role for an Azure subscription:</span></span>

1. <span data-ttu-id="03e74-165">登入合作夥伴中心[儀表板](https://partner.microsoft.com/dashboard)。</span><span class="sxs-lookup"><span data-stu-id="03e74-165">Sign into the Partner Center [dashboard](https://partner.microsoft.com/dashboard).</span></span>

2. <span data-ttu-id="03e74-166">依序選取 [ **CSP**] 和 [**客戶**]，然後選取特定的客戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-166">Select **CSP**, then **Customers** and select the specific customer.</span></span>

3. <span data-ttu-id="03e74-167">選取**該客戶的 [** 訂用帳戶]，並找出特定的 Azure 訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="03e74-167">Select **Subscriptions** for that customer and locate the specific Azure subscription.</span></span>

4. <span data-ttu-id="03e74-168">選取該客戶訂用帳戶旁的 [**管理**] 按鈕。</span><span class="sxs-lookup"><span data-stu-id="03e74-168">Select the **Manage** button next to that customer's subscription.</span></span> <span data-ttu-id="03e74-169">這麼做會開啟[Azure 入口網站](https://portal.azure.com/)。</span><span class="sxs-lookup"><span data-stu-id="03e74-169">Doing so opens the [Azure portal](https://portal.azure.com/).</span></span>

5. <span data-ttu-id="03e74-170">若要將**擁有**者角色指派給特定使用者，請遵循下列步驟，[將使用者指派為系統管理員](https://docs.microsoft.com/azure/cost-management-billing/manage/add-change-subscription-administrator#to-assign-a-user-as-an-administrator)。</span><span class="sxs-lookup"><span data-stu-id="03e74-170">To assign the **Owner** role to a specific user, follow these steps [To assign a user as an administrator](https://docs.microsoft.com/azure/cost-management-billing/manage/add-change-subscription-administrator#to-assign-a-user-as-an-administrator).</span></span>

### <a name="turn-on-or-turn-off-customer-permissions-to-purchase-their-own-azure-reservations"></a><span data-ttu-id="03e74-171">開啟或關閉客戶的許可權以購買自己的 Azure 保留專案</span><span class="sxs-lookup"><span data-stu-id="03e74-171">Turn on or turn off customer permissions to purchase their own Azure reservations</span></span>

<span data-ttu-id="03e74-172">在您確認客戶具有現有的 Azure 訂用帳戶，而且已將該訂用帳戶的**擁有**者角色指派給使用者之後，您就可以開啟（啟用）客戶的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-172">After you verify the customer has an existing Azure subscription and users are assigned the **Owner** role for that subscription, you're ready to turn on (enable) customer permissions.</span></span> <span data-ttu-id="03e74-173">您也可以使用這些步驟來關閉（停用）客戶的許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-173">You can also use these steps to turn off (disable) customer permissions.</span></span> <span data-ttu-id="03e74-174">您可以使用合作夥伴中心儀表板或[合作夥伴中心 api](https://docs.microsoft.com/partner-center/develop/manage-customers)來啟用或停用客戶許可權。</span><span class="sxs-lookup"><span data-stu-id="03e74-174">You can enable or disable customer permissions using either the Partner Center dashboard or [Partner Center APIs](https://docs.microsoft.com/partner-center/develop/manage-customers).</span></span>

<span data-ttu-id="03e74-175">若要在合作夥伴中心開啟（或關閉）客戶的許可權：</span><span class="sxs-lookup"><span data-stu-id="03e74-175">To turn on (or turn off) customer permissions in Partner Center:</span></span>

1. <span data-ttu-id="03e74-176">登入合作夥伴中心[儀表板](https://partner.microsoft.com/dashboard)。</span><span class="sxs-lookup"><span data-stu-id="03e74-176">Sign into the Partner Center [dashboard](https://partner.microsoft.com/dashboard).</span></span>

2. <span data-ttu-id="03e74-177">從左側導覽功能表中，依序選取 [ **CSP**] 和 [**客戶**]。</span><span class="sxs-lookup"><span data-stu-id="03e74-177">From the left navigation menu, select **CSP**, then **Customers**.</span></span> <span data-ttu-id="03e74-178">客戶清單隨即出現。</span><span class="sxs-lookup"><span data-stu-id="03e74-178">A customer list appears.</span></span>

3. <span data-ttu-id="03e74-179">選取特定的客戶名稱。</span><span class="sxs-lookup"><span data-stu-id="03e74-179">Select a specific customer name.</span></span>

4. <span data-ttu-id="03e74-180">從 [客戶] 功能表中選取 [**帳戶**]。</span><span class="sxs-lookup"><span data-stu-id="03e74-180">Select **Account** from the customer menu.</span></span> <span data-ttu-id="03e74-181">[客戶**帳戶**] 頁面隨即出現。</span><span class="sxs-lookup"><span data-stu-id="03e74-181">The customer **Account** page appears.</span></span>

5. <span data-ttu-id="03e74-182">找出頁面底部的 [**客戶許可權**] 區域。</span><span class="sxs-lookup"><span data-stu-id="03e74-182">Locate the **Customer permissions** area at the bottom of the page.</span></span>

   :::image type="content" source="images/give-customers-permission-reservations.png" alt-text="客戶在帳戶頁面上的許可權。" border="true":::

6. <span data-ttu-id="03e74-184">在 [ **Azure 保留**] 底下，找出 [**允許客戶購買**] 選項。</span><span class="sxs-lookup"><span data-stu-id="03e74-184">Under **Azure reservations**, locate the **Allow customer to purchase** option.</span></span>

7. <span data-ttu-id="03e74-185">若要開啟客戶許可權，請將此選項旁邊的切換開關移至 [**開啟**] 位置。</span><span class="sxs-lookup"><span data-stu-id="03e74-185">To turn on customer permissions, move the switch next to this option to the **On** position.</span></span> <span data-ttu-id="03e74-186">若要關閉客戶權力，請將切換開關移至 [**關閉**] 位置。</span><span class="sxs-lookup"><span data-stu-id="03e74-186">To turn off customer permissions, move the switch to the **Off** position.</span></span>

>[!NOTE]
> <span data-ttu-id="03e74-187">若要瞭解當您開啟客戶的許可權來購買自己的 Azure 保留時，會發生什麼事，請參閱[合作夥伴中心的客戶許可權總覽](give-customers-permission.md#overview-of-customer-permissions-in-partner-center)。</span><span class="sxs-lookup"><span data-stu-id="03e74-187">To learn what else happens when you turn on a customer's permissions to purchase their own Azure reservations, see [Overview of customer permissions in Partner Center](give-customers-permission.md#overview-of-customer-permissions-in-partner-center).</span></span>
>
><span data-ttu-id="03e74-188">當您開啟（或關閉）客戶許可權時，活動記錄會記錄每個動作。</span><span class="sxs-lookup"><span data-stu-id="03e74-188">When you turn on (or turn off) customer permissions, the Activity log records each action.</span></span> <span data-ttu-id="03e74-189">（當您選取 [合作夥伴中心] 儀表板頂端的齒輪圖示時，就可以存取此記錄）。</span><span class="sxs-lookup"><span data-stu-id="03e74-189">(This log is accessible when you select the Gear icon from the top of the Partner Center dashboard).</span></span> <span data-ttu-id="03e74-190">當您開啟或關閉客戶權力時，此動作將會顯示為 [在活動記錄中**建立客戶購買許可權**或**刪除客戶購買許可權**]。</span><span class="sxs-lookup"><span data-stu-id="03e74-190">When you turn customer permissions on or off, the action will appear as either **Create Customer Purchase Permissions** or **Delete Customer Purchase Permissions** in the Activity log.</span></span>

## <a name="help-customers-manage-reservations-they-purchase"></a><span data-ttu-id="03e74-191">協助客戶管理他們所購買的保留</span><span class="sxs-lookup"><span data-stu-id="03e74-191">Help customers manage reservations they purchase</span></span>

<span data-ttu-id="03e74-192">一旦授與客戶購買自己的 Azure 保留的許可權，您就可以協助他們更有效地管理他們所購買的任何資源。</span><span class="sxs-lookup"><span data-stu-id="03e74-192">Once you give customers permission to purchase their own Azure reservations, you can help them better manage any resources they purchase.</span></span> <span data-ttu-id="03e74-193">客戶可以直接從[Azure 入口網站](https://portal.azure.com/)管理 Azure 保留專案的許多層面。</span><span class="sxs-lookup"><span data-stu-id="03e74-193">Customers can manage many aspects of Azure reservations themselves directly from the [Azure portal](https://portal.azure.com/).</span></span> <span data-ttu-id="03e74-194">在您的 CSP 訂用帳戶中，他們將需要協助您管理 Azure 保留專案的一些其他層面。</span><span class="sxs-lookup"><span data-stu-id="03e74-194">They will need your help managing a few, other aspects of Azure reservations they purchase within your CSP subscription.</span></span>  

<span data-ttu-id="03e74-195">協助客戶深入瞭解如何管理 Azure 保留專案的下列各方面：</span><span class="sxs-lookup"><span data-stu-id="03e74-195">Help customers understand more about managing these aspects of Azure reservations:</span></span>

- <span data-ttu-id="03e74-196">客戶將支付 Azure 保留費用</span><span class="sxs-lookup"><span data-stu-id="03e74-196">Prices customers will pay for Azure reservations</span></span>
- <span data-ttu-id="03e74-197">客戶可以如何將 Azure 保留專案優化</span><span class="sxs-lookup"><span data-stu-id="03e74-197">How customers can optimize use of Azure reservations</span></span>
- <span data-ttu-id="03e74-198">當客戶購買具有共用範圍的保留時，會發生什麼事？</span><span class="sxs-lookup"><span data-stu-id="03e74-198">What happens when customers purchase reservations with a shared scope?</span></span>
- <span data-ttu-id="03e74-199">若客戶想要變更、取消和更新保留，或變更其範圍，會發生什麼事？</span><span class="sxs-lookup"><span data-stu-id="03e74-199">What happens if customers want to change, cancel, and renew a reservation, or change its scope?</span></span>

<span data-ttu-id="03e74-200">**客戶會支付其保留費用。**</span><span class="sxs-lookup"><span data-stu-id="03e74-200">**Prices customers will pay for their reservations.**</span></span> <span data-ttu-id="03e74-201">您的客戶將會根據您先前在 CSP 合作夥伴帳單帳戶中購買的訂用帳戶來購買 Azure 保留。</span><span class="sxs-lookup"><span data-stu-id="03e74-201">Your customer will be purchasing Azure reservations based on a subscription you previously bought for them in your CSP partner billing account.</span></span> <span data-ttu-id="03e74-202">根據此訂用帳戶購買之任何 Azure 保留的客戶價格也會由您設定。</span><span class="sxs-lookup"><span data-stu-id="03e74-202">The customer's price for any Azure reservations they purchase based on this subscription is also set by you.</span></span> <span data-ttu-id="03e74-203">此價格可能與客戶在 Azure 入口網站中看到的 Web Direct 價格不同。</span><span class="sxs-lookup"><span data-stu-id="03e74-203">This price may be different from the Web Direct price the customer sees in the Azure portal.</span></span>

<span data-ttu-id="03e74-204">**客戶可以如何將保留的使用優化。**</span><span class="sxs-lookup"><span data-stu-id="03e74-204">**How customers can optimize their use of a reservation.**</span></span> <span data-ttu-id="03e74-205">某些客戶可能會受益于深入瞭解如何優化保留的使用方式，或如何在購買期間指派保留的初始範圍。</span><span class="sxs-lookup"><span data-stu-id="03e74-205">Some customers might benefit from learning more about how to optimize their use of a reservation or how to assign a reservation’s initial scope during their purchase.</span></span> <span data-ttu-id="03e74-206">如需詳細資訊，請要求客戶閱讀[管理 Azure 資源的保留](https://docs.microsoft.com/azure/cost-management-billing/reservations/manage-reserved-vm-instance)。</span><span class="sxs-lookup"><span data-stu-id="03e74-206">For more information, ask customers to read [Manage reservations for Azure resources](https://docs.microsoft.com/azure/cost-management-billing/reservations/manage-reserved-vm-instance).</span></span>

<span data-ttu-id="03e74-207">**當客戶購買具有共用範圍的保留時，會發生什麼事？**</span><span class="sxs-lookup"><span data-stu-id="03e74-207">**What happens when a customer purchases a reservation with a shared scope?**</span></span> <span data-ttu-id="03e74-208">當客戶根據先前的 CSP 訂用帳戶購買保留區，並將共用範圍指派給該保留時，CSP 提供給客戶的任何折扣將會套用至 CSP 合作夥伴為該客戶購買之所有訂用帳戶的相符使用量。</span><span class="sxs-lookup"><span data-stu-id="03e74-208">When customers purchase a reservation based on a prior CSP subscription and assign a shared scope to that reservation, any discounts the customer has been given by the CSP will apply to matching usage for all subscriptions the CSP partner has purchased for that customer.</span></span>

<span data-ttu-id="03e74-209">**如果他們想要交換、取消或續訂已進行的購買，或變更保留的初始範圍，客戶該怎麼做？**</span><span class="sxs-lookup"><span data-stu-id="03e74-209">**What should customers do if they want to exchange, cancel, or renew a purchase they have made, or change the initial scope of a reservation?**</span></span> <span data-ttu-id="03e74-210">客戶必須要求合作夥伴協助他們變更保留的初始範圍。</span><span class="sxs-lookup"><span data-stu-id="03e74-210">Customers need to ask their partner to help them change a reservation's initial scope.</span></span> <span data-ttu-id="03e74-211">他們也需要合作夥伴的協助，以交換、取消或更新保留。</span><span class="sxs-lookup"><span data-stu-id="03e74-211">They also need a partner's help to exchange, cancel, or renew a reservation.</span></span> <span data-ttu-id="03e74-212">他們無法根據 CSP 合作夥伴為其購買的訂閱，自行執行這些工作。</span><span class="sxs-lookup"><span data-stu-id="03e74-212">They cannot perform these tasks themselves with reservations based on subscriptions purchased for them by a CSP partner.</span></span>

## <a name="next-steps"></a><span data-ttu-id="03e74-213">後續步驟</span><span class="sxs-lookup"><span data-stu-id="03e74-213">Next steps</span></span>

- [<span data-ttu-id="03e74-214">代表您的客戶購買 Azure 保留專案</span><span class="sxs-lookup"><span data-stu-id="03e74-214">Buy Azure reservations on behalf of your customers</span></span>](azure-reservations-buying.md)

- [<span data-ttu-id="03e74-215">合作夥伴中心-銷售 Microsoft 預約</span><span class="sxs-lookup"><span data-stu-id="03e74-215">Partner Center - Sell Microsoft reservations</span></span>](azure-reservations.md)

- [<span data-ttu-id="03e74-216">代表您的客戶管理 Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="03e74-216">Manage Azure reservations on behalf of your customers</span></span>](azure-reservations-manage.md)
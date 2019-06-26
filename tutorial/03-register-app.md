<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="d04bc-101">В этом упражнении вы создадите регистрацию нового веб-приложения Azure AD с помощью центра администрирования Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d04bc-101">In this exercise, you will create a new Azure AD web application registration using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="d04bc-102">Откройте браузер и перейдите к [Центру администрирования Azure Active Directory](https://aad.portal.azure.com).</span><span class="sxs-lookup"><span data-stu-id="d04bc-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com).</span></span> <span data-ttu-id="d04bc-103">Войдите с помощью **личной учетной записи** (т.е. учетной записи Microsoft) или **рабочей (учебной) учетной записи**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-103">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="d04bc-104">Выберите **Azure Active Directory** в левой панели навигации, а затем выберите **Регистрация приложений** в разделе **Управление**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-104">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations** under **Manage**.</span></span>

    ![<span data-ttu-id="d04bc-105">Снимок экрана с регистрациями приложений</span><span class="sxs-lookup"><span data-stu-id="d04bc-105">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="d04bc-106">Выберите **Новая регистрация**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-106">Select **New registration**.</span></span> <span data-ttu-id="d04bc-107">На странице**Зарегистрировать приложение** задайте необходимые значения следующим образом.</span><span class="sxs-lookup"><span data-stu-id="d04bc-107">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="d04bc-108">Введите **имя** `Ruby Graph Tutorial`.</span><span class="sxs-lookup"><span data-stu-id="d04bc-108">Set **Name** to `Ruby Graph Tutorial`.</span></span>
    - <span data-ttu-id="d04bc-109">Введите **поддерживаемые типы учетных записей** для **учетных записей в любом каталоге организаций и личных учетных записей Microsoft**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-109">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="d04bc-110">В разделе **URI адрес перенаправления** введите значение в первом раскрывающемся списке `Web` и задайте значение `http://localhost:3000/auth/microsoft_graph_auth/callback`.</span><span class="sxs-lookup"><span data-stu-id="d04bc-110">Under **Redirect URI**, set the first drop-down to `Web` and set the value to `http://localhost:3000/auth/microsoft_graph_auth/callback`.</span></span>

    ![Снимок страницы "регистрация приложения"](./images/aad-register-an-app.png)

1. <span data-ttu-id="d04bc-112">Выберите **регистр**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-112">Select **Register**.</span></span> <span data-ttu-id="d04bc-113">На странице **Tutorial "Диаграмма Ruby** " СКОПИРУЙТЕ значение **идентификатора Application (Client)** и сохраните его, он понадобится на следующем шаге.</span><span class="sxs-lookup"><span data-stu-id="d04bc-113">On the **Ruby Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Снимок экрана с ИДЕНТИФИКАТОРом приложения для новой регистрации приложения](./images/aad-application-id.png)

1. <span data-ttu-id="d04bc-115">Выберите **Сертификаты и секреты** в разделе **Управление**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-115">Select **Certificates & secrets** under **Manage**.</span></span> <span data-ttu-id="d04bc-116">Нажмите кнопку **Новый секрет клиента**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-116">Select the **New client secret** button.</span></span> <span data-ttu-id="d04bc-117">Введите значение в поле **Описание** и выберите один из вариантов истечения **срока действия** , а затем нажмите кнопку **добавить**.</span><span class="sxs-lookup"><span data-stu-id="d04bc-117">Enter a value in **Description** and select one of the options for **Expires** and select **Add**.</span></span>

    ![Снимок экрана: диалоговое окно добавления секрета клиента](./images/aad-new-client-secret.png)

1. <span data-ttu-id="d04bc-119">Скопируйте значение секрета клиента, а затем покиньте эту страницу.</span><span class="sxs-lookup"><span data-stu-id="d04bc-119">Copy the client secret value before you leave this page.</span></span> <span data-ttu-id="d04bc-120">Оно вам понадобится на следующем шаге.</span><span class="sxs-lookup"><span data-stu-id="d04bc-120">You will need it in the next step.</span></span>

    > [!IMPORTANT]
    > <span data-ttu-id="d04bc-121">Это секрет клиента, он никогда не отображается еще раз, поэтому убедитесь, что вы скопировали его.</span><span class="sxs-lookup"><span data-stu-id="d04bc-121">This client secret is never shown again, so make sure you copy it now.</span></span>

    ![Снимок экрана с недавно добавленным секретом клиента](./images/aad-copy-client-secret.png)

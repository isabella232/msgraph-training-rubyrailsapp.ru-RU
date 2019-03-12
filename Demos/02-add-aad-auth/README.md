# <a name="completed-module-add-azure-ad-authentication"></a>Завершенный модуль: Добавление проверки подлинности Azure AD

Версия проекта в этом каталоге соответствует завершению работы с руководством [Добавление проверки подлиннОсти Azure AD](https://docs.microsoft.com/graph/training/ruby-tutorial?tutorial-step=3). Если вы используете эту версию проекта, вам необходимо выполнить остальные руководства, начиная с [получения данных календаря](https://docs.microsoft.com/graph/training/ruby-tutorial?tutorial-step=4).

> **Примечание:** Предполагается, что вы уже зарегистрировали приложение на портале регистрации приложений, как указано в разделе [Регистрация приложения на портале](https://docs.microsoft.com/graph/training/ruby-tutorial?tutorial-step=2). Эту версию примера необходимо настроить следующим образом:
>
> 1. Переименуйте `./config/oauth_environment_variables.rb.example` файл в `oauth_environment_variables.rb`.
> 1. Измените `oauth_environment_variables.rb` файл и внесите следующие изменения.
>     1. Замените `YOUR_APP_ID_HERE` идентификатором **приложения** , полученНым на портале регистрации приложений.
>     1. Замените `YOUR APP PASSWORD HERE` паролем, полученНым на портале регистрации приложений.
[![Build Status](https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_apis/build/status/PL_Release?branchName=master)](https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_build/latest?definitionId=3&branchName=master)
[![NeosyntezApiClient package in NS_API_Feed@Release feed in Azure Artifacts](https://feeds.dev.azure.com/neolantservice4/644f90da-893b-4e55-86c6-90b8ec342f2d/_apis/public/Packaging/Feeds/2a945164-16de-49e4-98e5-2a5c21a830d4%409e997b01-d157-4d0b-8363-39f5c750f3d7/Packages/4f45664c-a73b-44eb-874a-9e8d670cefa3/Badge)](https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_packaging?_a=package&feed=2a945164-16de-49e4-98e5-2a5c21a830d4%409e997b01-d157-4d0b-8363-39f5c750f3d7&package=4f45664c-a73b-44eb-874a-9e8d670cefa3&preferRelease=true)
<h3 style="padding-left: 15pt;">.NET адаптер REST API СУИД НЕОСИНТЕЗ</h3>
<div style="padding-left: 15pt;padding-top: 20px;">
    <div>
        Проект адаптера работы с REST API СУИД НЕОСИНТЕЗ.
    </div>
    <div style="padding-top: 20px;">
        <strong>Цель проекта:</strong>
        Упростить создание разных интеграций с СУИД.
    </div>

</div>
<div style="padding-left: 15pt; padding-top: 20px;">
    <strong>Проект включает в себя:</strong>
    <ol type="1">
        <li> Исходные коды адаптера разделенные на модули директория <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fsrc"><strong>/src</strong></a>:
            <ul>
                <li>
                   <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fsrc%2FClient.Application"><strong>Client.Application/</strong></a> пространство имен сервисов работы с REST API
                </li>
                <li>
                    <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fsrc%2FClient.Domain"><strong>Client.Domain/</strong></a> домен/ядро приложения включающее в себя модели и контракты используемые для
                    взаимодействия с REST API
                </li>
                <li>
                   <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fsrc%2FClient.AutofacModule"><strong>Client.AutofacModule/</strong></a>  пространство имен модуля настройки Адаптера через DI Autofac.
            </ul>
        </li>
        <li>
            Краткие <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fexamples%2FApiExamples"><strong>примеры</strong></a> использования адатпера. Примеры включают в себя вариант подключения через
            <strong>Microsoft.Extensions.DependencyInjection</strong>, а так же краткое описние работы с сервисами.
        </li>
        <li>
            Тесты <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Ftests"><strong>/tests</strong></a>. Тесты разделены на Unit и Интеграционные, для воспроизведения интеграционных тестов требуется
            настройка взаимодействия с действующим экземпляром Неосинтез.
        </li>
        <li>
            Скрипты сборки и тестирования в среде Azure <a href="https://dev.azure.com/neolantservice4/NEOSYNTEZ%20API/_git/NEOSYNTEZ%20API?path=%2Fbuild"><strong>/build</strong></a> .
        </li>
        <li>
           Обратная связь через <a href="https://github.com/stv-ckv/NEOSYNTEZ-API/issues"><strong>issue</strong></a>
        </li>
    </ol>
</div>
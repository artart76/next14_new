Есть несколько преимуществ реализации поиска с параметрами URL:

URL-адреса с возможностью добавления в закладки и общего доступа . Поскольку параметры поиска находятся в URL-адресе, пользователи могут добавлять в закладки текущее состояние приложения, включая свои поисковые запросы и фильтры, для дальнейшего использования или совместного использования.
Серверный рендеринг и первоначальная загрузка : параметры URL-адреса могут напрямую использоваться на сервере для рендеринга исходного состояния, что упрощает обработку серверного рендеринга.
Аналитика и отслеживание . Наличие поисковых запросов и фильтров непосредственно в URL-адресе упрощает отслеживание поведения пользователей без необходимости дополнительной логики на стороне клиента.


Полезно знать : в HTML атрибуту передается URL-адрес action. Этот URL-адрес будет местом назначения, куда должны быть отправлены данные вашей формы (обычно конечная точка API).

Однако в React actionатрибут считается специальной опорой — это означает, что React строится на его основе, позволяя вызывать действия. Вместо явного вызова API вы можете передать функцию в action.

За кулисами действия сервера создают POSTконечную точку API. Вот почему вам не нужно вручную создавать конечные точки API при использовании действий сервера.


Повторная проверка и перенаправление
Next.js имеет клиентский кэш маршрутизатора , который какое-то время сохраняет сегменты маршрута в браузере пользователя. Наряду с предварительной выборкой этот кеш гарантирует, что пользователи могут быстро перемещаться между маршрутами, одновременно сокращая количество запросов к серверу.


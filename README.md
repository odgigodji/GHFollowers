# GFFollowers
Приложение на основе github API. 
<!-- ![](https://i.ibb.co/gg0yRk8/Frame-13.png) -->
![](https://i.ibb.co/bsZphHL/white-mode.png)

![](https://i.ibb.co/4mB5nLZ/dark3.jpg)

Состоит из 4х экранов:
### Поиск пользователя(SearchVC):
-Вводим имя пользователя и переходим на экран с его подписчиками

### Экран с подписчиками(FollowersListVC):

- Показывает всех подписчиков по 100 на одной странице
- После того как спустились вниз подгружает еще оставшихся
- Можно искать пользователей через 'SearchBar'
- По тапу на пользователя переходи на экран с детальной информацией
- На '+' в верхнем правом углу добавляем пользователя в избранное

### Экран с информацией о пользователе(UserInfoVC):
- Состоит из 3х View
- Верхняя выводит ник, имя, локацию и био 
- Средняя - репозитории и кнопка со ссылокой на профиль в Safari
- Нижняя - подписчики/подписки и кнопка показать всех подписчиков
- Внизу label с датой регисрации

### Избранное(FavoritesListVC):
- TableView с всеми пользователями которых мы добавили
- По тапу переходим на подписчиков пользователя
- По свайпу удаляем из избранного

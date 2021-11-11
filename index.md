## Welcome to GitHub Pages

<script src="https://pxl.altcraft.denis-kolesnik.lan/ak_container.js?id=MXwz" ></script>

<button id="init_sub">Подписаться на уведомления</button> // Кнопка подписки
 
<script>
    document.getElementById('init_sub').addEventListener('click', function() { // По клику на кнопку..
    try {
        var akPush = new AKPush(AIzaSyA93JppIAkhHU5I0LS2SEnsHfghO3Y2f6w);
        akPush.initSubscription() // ..показать форму подписки
        }
    catch (e) {
        console.log(e); // Или записать ошибку в консоль браузера
        }
    });
</script>

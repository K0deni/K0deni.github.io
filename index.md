## Welcome to GitHub Pages

<script src="https://pxl.altcraft.denis-kolesnik.lan/ak_container.js?id=MXwz" ></script>

<button id="init_sub">Подписаться на уведомления</button>
 
<script>
    document.getElementById('init_sub').addEventListener('click', function() { // По клику на кнопку..
    try {
        var akPush = new AKPush(AAAA90RyZqo:APA91bEJJ50W5i3lSBKtMdaMml7d1I5dCeCES1v_sqQ4MDZUCdXpyoPvXtTs8OwY5q_U);
        akPush.initSubscription() // ..показать форму подписки
        }
    catch (e) {
        console.log(e); // Или записать ошибку в консоль браузера
        }
    });
</script>

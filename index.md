## Welcome to GitHub Pages

<script src="https://www.gstatic.com/firebasejs/5.2.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/5.2.0/firebase-messaging.js"></script>

<script type="text/javascript" src="/ak-push.js"></script>
<link rel="manifest" href="/manifest.json"></link>

<button id="init_sub">Подписаться на уведомления</button>
 
<script>
    document.getElementById('init_sub').addEventListener('click', function() { // По клику на кнопку..
    try {
        var akPush = new AKPush();
        akPush.initSubscription() // ..показать форму подписки
        }
    catch (e) {
        console.log(e); // Или записать ошибку в консоль браузера
        }
    });
</script>

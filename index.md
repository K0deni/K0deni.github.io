## Welcome to GitHub Pages

<script src="https://pxl.altcraft.denis-kolesnik.lan/ak_container.js?id=AAAA_02fOV0:APA91bF7oThHQ-af_FVYR6zyfozQV8e0jXaPHdDO4Zzj9m7kpi9vkWXpE_zok5aXbA1ZBnL_MXRwVD643Ytgtmql_J-hzKLi4V_PmeyqKTwJoa65Gfb8PYKO51NMDv4NMx4obE00AsMB" ></script>

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

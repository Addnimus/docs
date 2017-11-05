
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<h2>DocLister: Лексиконы</h2>

<h3 class="sub-header text-bold">&amp;customLang</h3>
<p>Загрузка произвольного лексикона.</p>
<p><span class="text-bold">Возможные значения</span> - имя php файла из папки /lang/ с ассоциативным массивом $_lang</p>
<p><span class="text-bold">Значение по умолчанию</span> - пусто.</p>
<p>При помощи лексикона можно переопределить как стандартные языковые сообщения из папки /core/lang/[(manager_language)]/, так и создавать новые. Для переопределения важно в массиве указывать полные название стандартного языкового ключа (например, core.test или paginate.next). Для использования лексикона достаточно в шаблоне написать тег [%КлючЛексикона%]</p>
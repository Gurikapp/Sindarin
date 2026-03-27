<script>
	import AudioPlayer from '$lib/components/AudioPlayer.svelte';
	import LessonTextField from '$lib/components/LessonTextField.svelte';
	import Sochinenie from '$lib/components/Sochinenie.svelte';
	import WordInput from '$lib/components/WordInput.svelte';
</script>

<div class="maincontent">
	<p class="zaglavie">Урок 3<span>Cerin naid rim</span></p>

	<div class="zadanie">
		<p class="textMain">
			1. Соедините слова на синдарине с их переводом. После этого образуйте множественное число.
			Запишите ответы в своей тетради и сверьтесь с ответами.
		</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">1) Aras <WordInput /></p>
		<p class="textMain">2) Adan <WordInput /></p>
		<p class="textMain">3) Laboth <WordInput /></p>
		<p class="textMain">4) Brog <WordInput /></p>
		<p class="textMain">5) Ungo <WordInput /></p>
		<p class="textMain">6) Garaf <WordInput /></p>
		<p class="textMain">7) Draug <WordInput /></p>
		<p class="textMain">А. Паук <WordInput /></p>
		<p class="textMain">Б. Олень <WordInput /></p>
		<p class="textMain">В. Варг <WordInput /></p>
		<p class="textMain">Г. Волк <WordInput /></p>
		<p class="textMain">Д. Человек <WordInput /></p>
		<p class="textMain">Е. Заяц <WordInput /></p>
		<p class="textMain">Ж. Медведь <WordInput /></p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			2. Прослушайте слова. Запишите их и перевод. Укажите число (ед.ч. или мн.ч.).
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok3_Upr2.mp3" />
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Именительный и родительный падеж</p>
	</div>
	<p class="textMain">
		Очень часто приходиться говорить о каком-то определённом объекте. Чтобы отобразить это в речи,
		существует определённый артикль. Для единственного числа это «i», а для множественного – «in»
		(Аналогом в английском является артикль «the»). Если существительное стоит в единственном числе
		и начинается на согласную, то артикль и существительное можно совместить. Если существительное
		во множественном числе имеет форму, отличную от формы единственного числа (edheledhil, но не
		ion-ion), артикль «in» можно сократить до «i», что очень часто и делают.
	</p>
	<br />
	<p class="prim">
		Внимание! По правилам, некоторые начальные согласные существительного изменяются, если перед
		ними стоит определённый артикль. Мы обсудим это позднее (урок 4).
	</p>
	<br />
	<p class="textMain">Примеры</p>
	<br />
	<p class="textMain">edhel (эльф) – i edhel (этот эльф)</p>
	<p class="textMain">edhil (эльфы) – in edhil (эти эльфы)</p>
	<p class="textMain">naug (гном) – i naug (этот гном) – iNaug (этот гном, так тоже можно)</p>
	<p class="textMain">brog (медведь) – i vrog (этот медведь) – iVrog (этот медведь)</p>
	<div class="divider"></div>

	<p class="textMain">
		Родительный падеж образуется в эльфийском с помощью порядка слов и иногда специального артикля.
		Если второе слово неопределённое или это название чеголибо, то родительный падеж выражается
		просто порядком слов.
	</p>
	<br />
	<p class="textMain">Примеры</p>
	<br />
	<p class="textMain">аran Gondor (король Гондора)</p>
	<p class="textMain">hîr Imladris (владыка Ривенделла)</p>
	<p class="textMain">ion aran (сын короля)</p>
	<div class="divider"></div>

	<p class="textMain">
		Если второе слово определённое, то следует использовать или артикль «i»-«in», или специальный
		артикль родительного падежа: «en» для ед.ч. и «ennan» для мн.ч. Лучше использовать специальный
		артикль, т.к. таким образом вы показываете, что это именно родительный падеж, и у слушающего вас
		эльфа не возникнет возможности - 13 - разного толкования. Если первая согласная во втором
		существительном – это «n», то «ennan» сокращается до «en».
	</p>
	<br />
	<p class="prim">
		Внимание! По правилам, некоторые начальные согласные второго существительного в родительном
		падеже изменяются, мы рассмотрим это позднее (урок 4). Также «en» можно сокращать до «e-», но
		это влечёт за собой другие специальные изменения согласной второго существительного. Это тоже
		будет объяснено позднее, можете пока не заморачивать себе этим голову. Однако, пока воздержитесь
		от образования определённого именительного и родительного падежей для существительных с первыми
		согласными.
	</p>
	<br />
	<p class="textMain">Примеры</p>
	<br />
	<p class="textMain">
		ion i aran (сын этого короля. «Этого» не следует понимать буквально, просто считайте, что это
		какой-то определённый король)
	</p>
	<p class="textMain">ion in erain (сын этих королей)</p>
	<p class="textMain">ion en aran (сын этого короля)</p>
	<p class="textMain">ion enan erain (сын этих королей)</p>
	<p class="textMain">aran en noeg (король этих гномов)</p>
	<p class="textMain">
		aran enan Ennorath (король Средиземья. Фактически, Средиземье – множественное число, т.к.
		дословно «Средние земли»)
	</p>
	<p class="textMain">aran enan dhroeg (король этих варгов)</p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			3. * Прослушайте диалог. Письменно ответьте на вопросы. (Задание повышенной сложности. Ничего
			страшного, если сейчас оно у вас не получится. Вы можете вернутся к нему позднее).
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok3_Upr3.mp3" />
	</div>
	<br />
	<p class="textMain">1) Man i eneth en edhel?</p>
	<p class="textMain">2) Man i eneth en adan?</p>
	<Sochinenie />
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">4. Переведите на эльфийский.</p>
	</div>
	<p class="textMain">1) «Этот» олень;<WordInput /></p>
	<p class="textMain">2) «Эти» гномы;<WordInput /></p>
	<p class="textMain">3) «Эти» зайцы;<WordInput /></p>
	<p class="textMain">4) король «этих» гор;<WordInput /></p>
	<p class="textMain">5) король Лотлориэна;<WordInput /></p>
	<p class="textMain">6) владыка «этого» моря.<WordInput /></p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Спряжение глаголов. Настоящее время</p>
	</div>
	<p class="textMain">
		В эльфийском существует два вида глаголов: i-глаголы и a-глаголы. Вне зависимости от типа
		глагола, спряжение по лицам и числам выражается при помощи окончаний. Они представлены ниже в
		таблице.
	</p>
	<p class="textMain">
		Так как окончания i-глаголов и a-глаголов различаются, важно уметь отличать их друг от друга.
		Как же это сделать? Всё довольно просто: начальные формы i-глаголов всегда оканчиваются на
		согласный и сами по себе небольшие (как правило состоят из трёх букв). Инфинитив же a-глаголов
		оканчивается на гласный и более длинный.
	</p>
	<table class="tableZ">
		<thead>
			<tr>
				<th colspan="2">Примеры</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>i-глаголы</td>
				<td>a-глаголы</td>
			</tr>
			<tr>
				<td>Ped – Говорить</td>
				<td>Linna – Петь</td>
			</tr>
			<tr>
				<td>Can – Звать </td>
				<td>Minna – Входить</td>
			</tr>
			<tr>
				<td>Cen – Видеть </td>
				<td>Aníra – Желать, жаждать</td>
			</tr>
			<tr>
				<td>Nor – Бежать, ехать верхом</td>
				<td>Dortha – Жить</td>
			</tr>
			<tr>
				<td>Cab – Прыгать</td>
				<td>Revia – Странствовать</td>
			</tr>
		</tbody>
	</table>
	<br />
	<table class="tableZ">
		<thead>
			<tr>
				<th>Таблица спряжения i-глаголов</th>
				<th>Единственное число </th>
				<th>Множественно число</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Глагол сам по себе</td>
				<td colspan="2">ped</td>
			</tr>
			<tr>
				<td>Начальная форма</td>
				<td colspan="2">Pedi (говорить)</td>
			</tr>
			<tr>
				<td>Повелительное наклонение</td>
				<td colspan="2">Pedo! (Говори!) </td>
			</tr>
			<tr>
				<td>Герундий</td>
				<td colspan="2">Peded (“говорение”, разговор)</td>
			</tr>
			<tr>
				<td>1-е лицо</td>
				<td>Pedin (Я говорю)</td>
				<td>Pedim (Мы говорим)</td>
			</tr>
			<tr>
				<td>2-е лицо</td>
				<td>Pedig (Ты говоришь) Pedil (Вы говорите, уваж.) </td>
				<td>Pedigir (Вы говорите) Pedilir (Вы говорите, уваж.)</td>
			</tr>
			<tr>
				<td>3-е лицо</td>
				<td>Pêd (Он говорит) </td>
				<td>Pedir (Они говорят)</td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<table class="tableZ">
		<thead>
			<tr>
				<th>Таблица спряжения a-глаголов</th>
				<th>Единственное число</th>
				<th>Множественно число</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Глагол сам по себе</td>
				<td colspan="2">linna</td>
			</tr>
			<tr>
				<td>Начальная форма</td>
				<td colspan="2">Linno (петь)</td>
			</tr>
			<tr>
				<td>Повелительное наклонение</td>
				<td colspan="2">Linno! (Пой!)</td>
			</tr>
			<tr>
				<td>Герундий</td>
				<td colspan="2">Linnad (пение)</td>
			</tr>
			<tr>
				<td>1-е лицо</td>
				<td>Linnon (Я пою)</td>
				<td>Linnam (Мы поём)</td>
			</tr>
			<tr>
				<td>2-е лицо</td>
				<td>Linnog (Ты поёшь) Linnal (Вы поёте, уваж.) </td>
				<td>Linnagir (Вы поёте) Linnalir (Вы поёте, уваж.)</td>
			</tr>
			<tr>
				<td>3-е лицо</td>
				<td>Linna (Он поёт)</td>
				<td>Linnar (Они поют)</td>
			</tr>
		</tbody>
	</table>
	<br />

	<p class="prim">
		Внимание! Умные слова! Если вы вдруг не знаете, что такое «инфинитив» или «герундий» - ничего
		страшного. «Инфинитив» - тоже самое, что и «начальная форма», т.е. глагол с «ть», «ти» или «чь»
		на конце («идти», «бежать», «петь»). «Герундий» - фактически это существительное, образованное
		от глагола («прыгать» - «прыжок», «говорить» - «разговор»).
	</p>
	<div class="divider"></div>

	<p class="textMain">
		В отличии от русского или английского языков, в Синдарине глагол уже несёт в себе местоимение:
	</p>
	<br />
	<p class="textMain">Linnon. – Я пою.</p>
	<br />
	<p class="textMain">
		Если вы хотите употребить местоимение отдельно, то стоит поставить глагол в форму третьего лица
		единственного числа*:
	</p>
	<br />
	<p class="textMain">Im linna. – Я пою.</p>
	<br />
	<p class="textMain">Говорить «Im linnon» – неправильно («я я пою», получается ерунда)</p>
	<br />
	<p class="textMain">
		Также важно запомнить следующее: если в корне i-глагола есть «а» или «о», то при спряжении
		глагола они меняются на «e». Например:
	</p>
	<br />
	<p class="textMain">Car – делать; ceri – инфинитив; cerin – я делаю и так далее.</p>
	<br />
	<p class="textMain">
		В третьем лице единственном числе в i-глаголах ставится «треугольник» над гласной – показатель
		того, что эта гласная длинная:
	</p>
	<br />
	<p class="textMain">«ped» - «pêd» (говорить – он/она/оно говорит)</p>
	<br />
	<p class="textMain">«nor» - «nôr» (бежать – он/она/оно бежит)</p>
	<br />
	<p class="prim">
		*Для множественного числа “linnar”. Подробнее об этом вы узнаете в будущих уроках, а пока не
		спешите использовать личные местоимения и глаголы вместе, это не общепринято и редко встречается
	</p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			5. Какого вида глаголы “nor”, “cab”, “cen”, “minna”, “aníra” и “dortha” (i- или a-?).
			Проспрягайте их письменно в тетради во всех формах, что приведены в таблицах. Не забудьте
			повелительное наклонение, герундий и инфинитив.
		</p>
	</div>
	<Sochinenie />
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			6. Прочитайте и переведите. Если вам будут встречаться новые слова, обратитесь к словарю в
			конце этой главы.
		</p>
	</div>
	<p class="textMain">
		Pedo mellon a minno! Dortham. Pedig. Linnad enan edhil. Aníron. Lastagir in edhil linno? Losto
		Caradhras! Noro lim! Cabed en aras.
	</p>
	<Sochinenie />
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			7. Переведите на эльфийский. При написании первой части вы можете подглядывать в учебник, а во
			время второй и третьей – нет. Это важно! Если во второй или третьей части у вас есть ошибки,
			не переходите к следующему уроку, подучите те слова или правила, которые у вас «западают».
		</p>
	</div>
	<p class="textMain">
		I. Я бегу. Вы спите. Она говорит (здесь нет контекста, так что лучше с местоимением). Они поют.
		Арагорн странствует. Жизнь эльфов.
	</p>
	<Sochinenie />
	<br />
	<p class="textMain">
		III. Горы. Имя гнома. Луна. Тёмный. Паук. Медведь. Друг. Земля. Моря. Герои. Бабочка. Заяц.
		Волк. Варг. Смотритель.
	</p>
	<Sochinenie />
	<br />
	<p class="textMain">
		III. 1) – Ты гном? – Да, я гном. – Как тебя зовут? – Я Траин. 2) – Привет! – Здравствуй! – Как
		тебя зовут? – Я Арагорн. – А я Леголас. Ты эльф? – Нет. Я человек. А ты? – Да, я эльф. – До
		встречи, Леголас! – Прощай.
	</p>
	<Sochinenie />
	<br />
	<div class="divider"></div>
	<div class="zadanie">
		<p class="textMain">
			8. Это первое упражнение в этом учебнике на произношение. Так как теперь вы более менее знаете
			некоторые слова и правила, вы сможете понять, что говорила Арвен в «Братстве Кольца», когда
			везла Фродо в Ривенделл. Прослушайте её фразу. Затем прочитайте это предложение сами и
			переведите. После этого снова прослушайте и прочитайте. Делайте это столько раз, сколько
			потребуется – вам необходимо добиться такой же скорости и произношения, как и у Арвен.
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok3_Upr8.mp3" />
	</div>
	<p class="textMain">Noro lim, Asfaloth, noro lim!</p>
	<div class="divider"></div>
	<table class="tableZ">
		<thead>
			<tr>
				<th colspan="2">Слова, которые следует выучить</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Синдэрин</td>
				<td>Перевод</td>
			</tr>
			<tr>
				<td>Ped</td>
				<td>Говорить</td>
			</tr>
			<tr>
				<td>Can</td>
				<td>Кричать, звать</td>
			</tr>
			<tr>
				<td>Tir</td>
				<td>Смотреть, наблюдать</td>
			</tr>
			<tr>
				<td>Cen</td>
				<td>Видеть</td>
			</tr>
			<tr>
				<td>Nor</td>
				<td>Бежать, ехать верхом, скакать</td>
			</tr>
			<tr>
				<td>Cab</td>
				<td>Прыгать</td>
			</tr>
			<tr>
				<td>Linna</td>
				<td>Петь</td>
			</tr>
			<tr>
				<td>Minna</td>
				<td>Входить</td>
			</tr>
			<tr>
				<td>Aníra</td>
				<td>Желать, жаждать</td>
			</tr>
			<tr>
				<td>Dortha</td>
				<td>Жить</td>
			</tr>
			<tr>
				<td>Dartha</td>
				<td>Ждать</td>
			</tr>
			<tr>
				<td>Pada</td>
				<td>Идти</td>
			</tr>
			<tr>
				<td>Lasta</td>
				<td>Слышать</td>
			</tr>
			<tr>
				<td>Losta</td>
				<td>Спать</td>
			</tr>
			<tr>
				<td>Caradhras</td>
				<td>Карадрас (название гор)</td>
			</tr>
			<tr>
				<td>Lim</td>
				<td>Быстро, скоро</td>
			</tr>
			<tr>
				<td>Gar</td>
				<td>Иметь</td>
			</tr>
			<tr>
				<td>Tol</td>
				<td>Идти, приходить</td>
			</tr>
			<tr>
				<td>Revia</td>
				<td>Странствовать</td>
			</tr>
			<tr>
				<td>Teitha</td>
				<td>Писать</td>
			</tr>
			<tr>
				<td>Parf</td>
				<td>Книга</td>
			</tr>
			<tr>
				<td>Maetha</td>
				<td>Сражаться</td>
			</tr>
			<tr>
				<td>Gwanna</td>
				<td>Умирать</td>
			</tr>
			<tr>
				<td>Anor</td>
				<td>Солнце</td>
			</tr>
			<tr>
				<td>Mi</td>
				<td>В</td>
			</tr>
			<tr>
				<td>Na</td>
				<td>К, в</td>
			</tr>
			<tr>
				<td>Maer</td>
				<td>Хороший</td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Ответы</p>
	</div>
	<p class="textMain">1.</p>
	<p class="textMain">1 – Б – Erais</p>
	<p class="textMain">2 – Д – Edain</p>
	<p class="textMain">3 – E – Lebyth</p>
	<p class="textMain">4 – Ж – Bryg</p>
	<p class="textMain">5 – А – Yngyl</p>
	<p class="textMain">6 – Г – Geraif</p>
	<p class="textMain">7 – В – Droeg</p>
	<br />
	<p class="textMain">
		2. Periain (хоббиты, мн.ч.); mellon (друг, ед.ч.); gwilwileth (бабочка, ед.ч.); edain (люди,
		мн.ч.); ardh (земля, ед.ч.); thelyn (герои, мн.ч.); enith (имена, мн.ч.); Ennorath (Средиземье,
		мн.ч.).
	</p>
	<br />
	<p class="textMain">3.</p>
	<p class="textMain">1) I eneth en edhel Belegon</p>
	<p class="textMain">2) I eneth en adan Aragorn.</p>
	<br />
	<p class="textMain">Belegon: Le suilon!</p>
	<p class="textMain">Aragorn: Mae govannen! Man i eneth lîn?</p>
	<p class="textMain">Belegon: Im Belegon. A ci?</p>
	<p class="textMain">Aragorn: I eneth nîn Aragorn.</p>
	<p class="textMain">Belegon: Lastog i linnad?</p>
	<p class="textMain">Aragorn: Ma</p>
	<p class="textMain">Belegon: Hai edhil be ni. Hai mellyn nîn.</p>
	<p class="textMain">Aragorn: I linnad vain. Novaer!</p>
	<p class="textMain">Belegon: Cuio vae!</p>
	<br />
	<p class="textMain">4.</p>
	<p class="textMain">1) i aras;</p>
	<p class="textMain">2) in noeg;</p>
	<p class="textMain">3) in lebyth;</p>
	<p class="textMain">4) aran enan eryd (или aran in eryd);</p>
	<p class="textMain">5) aran Lothlorien;</p>
	<p class="textMain">6) hîr en aer (или hîr i aer).</p>
	<br />
	<p class="textMain">5.</p>
	<p class="textMain">Nor, cab, cen – i-глаголы;</p>
	<p class="textMain">Minna, aníra, dortha – a-глаголы.</p>
	<br />
	<p class="textMain">
		Nor – neri – noro – nored – nerin – nerig (neril) – nôr – nerim – nerigir (nerilir) – nerir
	</p>
	<br />
	<p class="textMain">
		Cab – cebi – cabo – cabed – cebin – cebig (cebil) – câb – cebim – cebigir (cebilir) – cebir
	</p>
	<br />
	<p class="textMain">
		Cen – ceni – ceno – cened – cenin – cenig (cenil) – cên – cenim – cenigir (cenilir) – cenir
	</p>
	<br />
	<p class="textMain">
		Minna – minno – minno – minnad – minnon – minnog (minnal) – minna – minnam – minnagir (minnalir)
		– minnar
	</p>
	<br />
	<p class="textMain">
		Aníra – aníro – aníro – anírad – aníron – anírog (aníral) – aníra – aníram – aníragir (aníralir)
		– anírar
	</p>
	<br />
	<p class="textMain">
		Dortha – dortho – dortho – dorthad – dorthon – dorthog (dorthal) – dortha – dortham – dorthagir
		(dorthalir) – dorthar
	</p>
	<br />
	<p class="textMain">
		6. Скажи «друг» и входи. Мы живём. Ты говоришь. Пение эльфов. Я хочу (желаю, жажду). Слышите,
		как поют эльфы? Спи, Карадрас! Скачи быстро! Прыжок оленя.
	</p>
	<br />
	<p class="textMain">7.</p>
	<p class="textMain">I. Nerin. Lostagir. He pêd. Linnar. Aragorn revia. Dorthad enan edhil.</p>
	<br />
	<p class="textMain">
		II. Eryd. Eneth i naug. Ithil. Dûr. Ungol. Brog. Mellon. Ardh. Aer. Thelyn. Gwilwileth. Laboth.
		Garaf. Draug. Tiriel
	</p>
	<br />
	<p class="textMain">
		III. 1) – Ci naug? – Ma, ni naug. – Man i eneth gîn? – Im Thrain. 2) – Ai! – Le suilon! – Man i
		eneth gîn? – Im Aragorn. – Ah im Legolas. Ci edhel? – Uin, ni adan. A ci? – Ma, ni edhel. – Cuio
		vae, Legolas! – Novaer.
	</p>
	<br />
	<p class="textMain">8. Скачи быстро, Асфалот, скачи быстро.</p>
</div>

<style lang="scss">
	@import '$lib/styles/urok.scss';
</style>

<script>
	import AudioPlayer from '$lib/components/AudioPlayer.svelte';
	import LessonTextField from '$lib/components/LessonTextField.svelte';
	import Sochinenie from '$lib/components/Sochinenie.svelte';
	import WordInput from '$lib/components/WordInput.svelte';
</script>

<div class="maincontent">
	<p class="zaglavie">Урок 2 <span>Levain en Ennorath</span></p>
	<div class="zadanie">
		<p class="textMain">1. Прочитайте и переведите диалог.</p>
	</div>
	<div class="zadanieText">
		<p class="textMain"><span class="italic">Maethor</span>: - Le suilon!</p>
		<p class="textMain"><span class="italic">Taeriel</span>: - Mae govannen! Man i eneth lîn?</p>
		<p class="textMain"><span class="italic">Maethor</span>: - Im Maethor. A ci?</p>
		<p class="textMain"><span class="italic">Taeriel</span>: - I eneth nîn Taeriel. Im elleth.</p>
		<p class="textMain"><span class="italic">Maethor</span>: - Novaer, Taeriel!</p>
		<p class="textMain"><span class="italic">Taeriel</span>: - Namariё!</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">2. Посмотрите на текст и исправьте пять ошибок.</p>
	</div>
	<p class="textMain">Mae govanen! Enedh nîn Erchelion. Im edhell. Navaer!</p>
	<Sochinenie />
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			3. Прослушайте диалог. Вставьте пропущенные слова. После этого прочитайте его сами.
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok2_Upr3.mp3" />
	</div>
	<div class="zadanieText">
		<p class="textMain"><span class="italic">Lindir</span>: - Mae govannen!</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - A, <WordInput />! Suilon gen a vellyn <WordInput />!
		</p>
		<p class="textMain">
			<span class="italic">Lindir</span>: - Ho Maethor ah he Taeriel. Hai <WordInput />.
		</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - Im <WordInput />. Adar nîn peredhel. E hîr en <WordInput
			/>.
		</p>
		<p class="textMain"><span class="italic">Maethor</span>: - I eneth în <WordInput />?</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - Ma. Lastagir in <WordInput /> linno?
		</p>
		<p class="textMain"><span class="italic">Lindir</span>: - Thinna.</p>
		<p class="textMain">
			<span class="italic">Taeriel</span>: - <WordInput />, ha aduial mi Imladris.
		</p>
		<div class="divider"></div>

		<p class="textMain"><span class="italic">Линдир</span>: - Здравствуй!</p>
		<p class="textMain">
			<span class="italic">Арвен</span>: - А, Линдир! Приветствую тебя и твоих друзей!
		</p>
		<p class="textMain">
			<span class="italic">Линдир</span>: - Это Маэсор, а это Таэриель. Они эльфы.
		</p>
		<p class="textMain">
			<span class="italic">Арвен</span>: - Я эльфийка. А мой отец полуэльф. Он владыка Ривенделла.
		</p>
		<p class="textMain"><span class="italic">Маэсор</span>: - Его зовут Элронд?</p>
		<p class="textMain"><span class="italic">Арвен</span>: - Да. Слышите, как поют эльфы?</p>
		<p class="textMain"><span class="italic">Линдир</span>: - Вечереет.</p>
		<p class="textMain">
			<span class="italic">Таэриель</span>: - Да, сейчас (это) вечер в Ривенделле.
		</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">4. Переведите на Синдарин.</p>
	</div>
	<p class="textMain">1) Я человек.<WordInput /></p>
	<div class="divider"></div>
	<p class="textMain">2) Ты эльфийка. <WordInput /></p>
	<div class="divider"></div>
	<p class="textMain">3) Он гном.<WordInput /></p>
	<div class="divider"></div>
	<p class="textMain">4) Мы хоббиты.<WordInput /></p>
	<div class="divider"></div>
	<p class="textMain">5) Вы эльфы.<WordInput /></p>
	<div class="divider"></div>
	<p class="textMain">6) Они люди.<WordInput /></p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			5. В Средиземье есть множество разных животных. Вероятно, вам будет полезно знать, как их
			называют эльфы. Это пригодится на охоте, прогулке или просто при чтении разных интересных книг
			в Ривенделле. Выучите эти слова наизусть.
		</p>
	</div>
	<p class="textMain">Aras — Олень</p>
	<p class="textMain">Garaf — Волк</p>
	<p class="textMain">Gwilwileth — Бабочка</p>
	<p class="textMain">Laboth — Заяц</p>
	<p class="textMain">Brog — Медведь</p>
	<p class="textMain">Aew — Птица</p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Образование множественного числа</p>
	</div>
	<p class="textMain">
		В Синдарине множественное число образуется путём изменения гласных букв в слове. Внимательно
		изучите таблицу, посмотрите на примеры. Обратите внимание на то, что дифтонги (некоторые
		сочетания двух гласных) изменяются по-другому.
	</p>
	<table class="tableZ">
		<thead>
			<tr>
				<th>Гласная</th>
				<th>В начале-середине</th>
				<th>В конце</th>
				<th>Примеры</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>A</td>
				<td>e</td>
				<td>ai (арх. ei*)</td>
				<td>Adan – Edain <br />Aras - Erais</td>
			</tr>
			<tr>
				<td>E</td>
				<td>e</td>
				<td>i</td>
				<td>Edhel - Edhil</td>
			</tr>
			<tr>
				<td>I </td>
				<td>i</td>
				<td>i</td>
				<td>Ithil - Ithil</td>
			</tr>
			<tr>
				<td>O</td>
				<td>e</td>
				<td>y</td>
				<td>Orod – Eryd<br /> Brog - Bryg</td>
			</tr>
			<tr>
				<td>U</td>
				<td>y</td>
				<td
					>y<br />
					ui (долгая)</td
				>
				<td
					>Ungol – Yngyl<br />
					Dûr - Duir
				</td>
			</tr>
			<tr>
				<td>Y</td>
				<td>y</td>
				<td>y</td>
				<td>Ylf - Ylf</td>
			</tr>
			<tr>
				<td>io</td>
				<td>y</td>
				<td>y</td>
				<td>Thalion - Thelyn</td>
			</tr>
			<tr>
				<td>au</td>
				<td>oe</td>
				<td>oe</td>
				<td>Draug - Droeg</td>
			</tr>
			<tr>
				<td>ie</td>
				<td>ie</td>
				<td>i</td>
				<td>Tiriel - Tiril</td>
			</tr>
			<tr>
				<td colspan="2">Всё остальное</td>
				<td colspan="2">Без изменений</td>
			</tr>
		</tbody>
	</table>
	<p class="prim">
		* Арх. – архаичный. Это означает, что раньше, в Первую Эпоху, множественное число образовывалось
		с помощью “ei”, а во времена Фродо – с помощью “ai”. Эта информация может быть полезна, если вы
		захотите сымитировать древний Синдарин.
	</p>
	<p class="prim">
		Внимание! Существует группа слов, которые образуют множественное число по-другому. Они будут
		рассмотрены немного позже.
	</p>
	<div class="divider"></div>

	<p class="textMain">
		Теперь давайте разберём несколько примеров вместе, а затем вы сделаете упражнение и проверите
		себя. Правило образования множественного числа (как и все другие правила) следует знать
		наизусть, иначе вам будет очень сложно общаться на сероэльфийском языке.
	</p>
	<table class="tableZ">
		<thead>
			<tr>
				<th>Примеры</th>
				<th>Комментарии</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>1) Edhel – Edhil</td>
				<td
					>Первая “e” не изменяется, т.к. стоит вначале слова, вторая “e” изменяется на “i”, т.к.
					стоит в конце (см. таблицу).</td
				>
			</tr>
			<tr>
				<td>2) Draug (Варг) – Droeg </td>
				<td>Дифтонг “au” изменяется на “oe”, т.к. стоит в конце (является последним).</td>
			</tr>
			<tr>
				<td>3) Aer (Море) – Aer</td>
				<td
					>Дифтонг “ae” никогда не изменяется (и все прочие дифтонги, кроме тех, которые приведены в
					таблице, тоже!).
				</td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			6. Переведите данные слова и образуйте множественное число. Запишите получившиеся пары слов в
			свою тетрадь. Сверьтесь с ответами в конце учебника.
		</p>
	</div>
	<p class="textMain">1) Garaf <WordInput /></p>
	<br />
	<p class="textMain">2) Naug <WordInput /></p>
	<br />
	<p class="textMain">3) Perian <WordInput /></p>
	<br />
	<p class="textMain">4) Mellon <WordInput /></p>
	<br />
	<p class="textMain">5) Gwilwileth <WordInput /></p>
	<br />
	<p class="textMain">6) Laboth <WordInput /></p>
	<br />
	<p class="textMain">7) Aew <WordInput /></p>
	<br />
	<p class="textMain">8) Elleth <WordInput /></p>
	<div class="divider"></div>

	<table class="tableZ">
		<thead>
			<tr>
				<th colspan="2">Слова, которые следует выучить</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Синдарин</td>
				<td>Перевод</td>
			</tr>
			<tr>
				<td>Aras</td>
				<td>Олень</td>
			</tr>
			<tr>
				<td>Garaf</td>
				<td>Волк</td>
			</tr>
			<tr>
				<td>Gwilwileth</td>
				<td>Бабочка</td>
			</tr>
			<tr>
				<td>Laboth</td>
				<td>Заяц</td>
			</tr>
			<tr>
				<td>Brog</td>
				<td>Медведь</td>
			</tr>
			<tr>
				<td>Aew</td>
				<td>Птица</td>
			</tr>
			<tr>
				<td>Ithil</td>
				<td>Луна</td>
			</tr>
			<tr>
				<td>Orod</td>
				<td>Гора</td>
			</tr>
			<tr>
				<td>Ungol</td>
				<td>Паук</td>
			</tr>
			<tr>
				<td>Dûr</td>
				<td>Тёмный</td>
			</tr>
			<tr>
				<td>Ylf</td>
				<td>Сосуд («для питья»)</td>
			</tr>
			<tr>
				<td>Thalion</td>
				<td>Герой</td>
			</tr>
			<tr>
				<td>Draug</td>
				<td>Варг, волк</td>
			</tr>
			<tr>
				<td>Tiriel</td>
				<td>Смотритель</td>
			</tr>
			<tr>
				<td>Aer</td>
				<td>Море</td>
			</tr>
			<tr>
				<td>Lavan</td>
				<td>Зверь</td>
			</tr>
			<tr>
				<td>Lobor</td>
				<td>Лошадь</td>
			</tr>
			<tr>
				<td>Roch</td>
				<td>Лошадь, быстрая лошадь для езды</td>
			</tr>
			<tr>
				<td>Hû</td>
				<td>Собака</td>
			</tr>
			<tr>
				<td>Rŷn</td>
				<td>Охотничья собака, гончая</td>
			</tr>
			<tr>
				<td>Fileg</td>
				<td>Маленькая птица, “птичка”</td>
			</tr>
			<tr>
				<td>Lim</td>
				<td>Рыба</td>
			</tr>
			<tr>
				<td>Raw</td>
				<td>Лев</td>
			</tr>
			<tr>
				<td>Graw</td>
				<td>Медведь (более современное слово)</td>
			</tr>
			<tr>
				<td>Rusc</td>
				<td>Лиса</td>
			</tr>
			<tr>
				<td>Annabon</td>
				<td>Слон</td>
			</tr>
			<tr>
				<td>Fara-</td>
				<td>Охотиться</td>
			</tr>
			<tr>
				<td>Lhûg</td>
				<td>Змея, червь</td>
			</tr>
			<tr>
				<td>Alph</td>
				<td>Лебедь</td>
			</tr>
			<tr>
				<td>Cabor</td>
				<td>Лягушка</td>
			</tr>
		</tbody>
	</table>
	<p class="textMain">
		Прежде, чем приступать к следующему уроку, проверьте себя – вы уже должны уметь знакомиться,
		помнить наизусть все личные местоимения и правило образования множественного числа, а также
		знать как минимум семь различных животных. Можете ли вы прямо сейчас это проговорить вслух (про
		себя)? Если вы действительно выучили всё перечисленное, то смело переходите к третьему уроку.
		Если нет – не торопитесь и сначала доучите до конца. После этого устройте себе проверку ещё раз
	</p>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Ответы</p>
	</div>
	<p class="textMain">2. Mae govannen! I eneth nîn Erchelion. Im edhell. Novaer!</p>
	<br />
	<div class="zadanieText">
		<p class="textMain"><span class="italic">3. <br />Lindir</span>: - Mae govannen!</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - A, <span class="underline">Lindir</span>!  Suilon gen a vellyn <span class="underline">gin</span>!
		</p>
		<p class="textMain">
			<span class="italic">Lindir</span>r: - Ho Maethor ah he Taeriel. Hai <span class="underline">edhil</span>.
		</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - Im <span class="underline">elleth</span>. Adar nin peredhel. E hír en <span class="underline">Imladris</span>.
		</p>
		<p class="textMain"><span class="italic">Maethor</span>: - I eneth ín <span class="underline">Elrond</span>?</p>
		<p class="textMain">
			<span class="italic">Arwen</span>: - Ma. Lastagir in <span class="underline">edhil</span> linno?
		</p>
		<p class="textMain"><span class="italic">Lindir</span>: - Thinna.</p>
		<p class="textMain">
			<span class="italic">Taeriel</span>: - <span class="underline">Ma</span>, ha aduial mi Imladris.
		</p>
	</div>
	<br>
		<p class="textMain">4. 1) Im adan. 2) Ci elleth. 3) Ho naug. 4) Mi periain. 5) Ci edhil. 6) Hai edain.</p>
	<br />
	<p class="textMain">6.<br> 1) Garaf (Волк) – Geraif;<br>
 2) Naug (Гном) – Noeg;<br>
 3) Perian (Хоббит) – Periain;<br>
 4) Mellon (Друг) – Mellyn;<br>
 5) Gwilwileth (Бабочка) – Gwilwilith;<br>
 6) Laboth (Заяц) – Lebyth;<br>
 7) Aew (Птица) – Aew;<br>
 8) Elleth (Эльфийка) – Ellith.
</p>
</div>

<style lang="scss">
	@import '$lib/styles/urok.scss';
</style>

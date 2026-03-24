<script>
	import AudioPlayer from '$lib/components/AudioPlayer.svelte';
	import LessonTextField from '$lib/components/LessonTextField.svelte';
</script>

<div class="maincontent">
	<p class="zaglavie">Урок 1 <span>Man i eneth lîn?</span></p>
	<div class="zadanie">
		<p class="textMain">1. Прослушайте диалог. После этого прочитайте его сами.</p>
		<AudioPlayer src="/audio/Edhellen_Urok1_Upr1.mp3" />
	</div>
	<div class="zadanieText">
		<p class="textMain"><span class="italic">Lindir</span>: - Mae govannen!</p>
		<p class="textMain"><span class="italic">Eglerion</span>: - Le suilon! Man i eneth lîn?</p>
		<p class="textMain"><span class="italic">Lindir</span>: - Im Lindir.</p>
		<p class="textMain"><span class="italic">Eglerion</span>: - I eneth nîn Eglerion. Ci edhel?</p>
		<p class="textMain"><span class="italic">Lindir</span>: - Ma. A ci adan?</p>
		<p class="textMain"><span class="italic">Eglerion</span>: - Uin. Im edhel.</p>
		<p class="textMain"><span class="italic">Lindir</span>: - Novaer, Eglerion!</p>
		<p class="textMain"><span class="italic">Eglerion</span>: - Cuio vae!</p>
		<div class="divider"></div>
		<p class="textMain">
			<span class="italic">Линдир</span>: - Здравствуй! (дословно «Добрая встреча»)
		</p>
		<p class="textMain">
			<span class="italic">Эглерион</span>: - Приветствую тебя! Как тебя зовут?
		</p>
		<p class="textMain"><span class="italic">Линдир</span>: - Я Линдир.</p>
		<p class="textMain"><span class="italic">Эглерион</span>: - Меня зовут Эглерион. Ты эльф?</p>
		<p class="textMain"><span class="italic">Линдир</span>: - Да. А ты человек?</p>
		<p class="textMain"><span class="italic">Эглерион</span>: - Нет. Я эльф.</p>
		<p class="textMain"><span class="italic">Линдир</span>: - Прощай, Эглерион!</p>
		<p class="textMain"><span class="italic">Эглерион</span>: - До встречи!</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			2. Посмотрите на различные способы приветствия, знакомства и прощания. Прослушайте
			аудиозапись. Прочитайте самостоятельно. Выучите наизусть.
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok1_Upr2.mp3" />
	</div>

	<table class="tableZ">
		<thead>
			<tr>
				<th>Приветствие</th>
				<th>Вопрос про имя</th>
				<th>Ответ</th>
				<th>Прощание</th>
			</tr>
		</thead>

		<tbody>
			<tr>
				<td>
					Mae govannen!<br />
					Здравствуй!
				</td>

				<td rowspan="3">
					Man i eneth lín?<br />
					Как тебя зовут?
				</td>

				<td>
					Im ______.<br />
					Я ______.
				</td>

				<td>
					Novaer!<br />
					Прощай!
				</td>
			</tr>

			<tr>
				<td>
					Le suilon! (уваж.)<br />
					Gen suilon! (другу)<br />
					Приветствую тебя!
				</td>

				<td rowspan="2">
					Le eneth nîn ______.<br />
					Меня зовут ______.
				</td>

				<td>
					Cuio vae!<br />
					До встречи!<br />
					(пожелание доброй жизни)
				</td>
			</tr>

			<tr>
				<td>
					Ai!<br />
					Привет!
				</td>

				<td>
					Namárië!<br />
					Прощай! (на Квенья, тоже очень часто используется)
				</td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			3. Представьте, что вы бродили по лесу и встретили эльфа по имени Маэсор (Maethor). Составьте
			диалог (приветствие, знакомство, прощание) и расскажите его вслух. Обращайте внимание на звуки
			“th” и “ui” – старайтесь произносить их правильно.
		</p>
	</div>

	<div class="zadanie">
		<p class="textMain">4. Вставьте недостающие буквы.</p>
	</div>

	<div class="zadanie-VstavBukvi">
		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">1)</p>
			<LessonTextField />
			<p class="textMain">a</p>
			<LessonTextField /><span class="probel"></span>
			<LessonTextField />
			<p class="textMain">ovan</p>
			<LessonTextField />
			<p class="textMain">en</p>
		</div>

		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">2)</p>
			<LessonTextField />
			<p class="textMain">a</p>
			<LessonTextField />
			<span class="probel"></span>
			<LessonTextField />
			<span class="probel"></span>
			<LessonTextField />
			<p class="textMain">ne</p>
			<LessonTextField />
			<p class="textMain">h</p>
			<span class="probel"></span>
			<p class="textMain">l</p>
			<LessonTextField />
			<p class="textMain">n</p>
		</div>

		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">3)</p>
			<p class="textMain">L</p>
			<LessonTextField />
			<span class="probel"></span>
			<p class="textMain">s</p>
			<LessonTextField />
			<LessonTextField />
			<p class="textMain">lon</p>
		</div>

		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">4)</p>
			<LessonTextField />
			<p class="textMain">am</p>
			<LessonTextField />
			<p class="textMain">r</p>
			<LessonTextField />
			<p class="textMain">e</p>
		</div>

		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">5)</p>
			<LessonTextField />
			<p class="textMain">o</p>
			<LessonTextField />
			<p class="textMain">v</p>
			<LessonTextField />
			<p class="textMain">er</p>
		</div>

		<div class="zadanie-VstavBukvi-stolb-stroka">
			<p class="textMain">6)</p>
			<p class="textMain">C</p>
			<LessonTextField />
			<p class="textMain">io</p>
			<span class="probel"></span>
			<LessonTextField />
			<p class="textMain">a</p>
			<LessonTextField />
		</div>
	</div>

	<div class="zadanie">
		<p class="textMain">
			5. Как переводится “adan” и “edhel”? Какая разница между ними? Расскажите немного о них на
			русском.
		</p>
	</div>

	<div class="zadanie">
		<p class="textMain">6. Посмотрите на таблицу личных местоимений. Выучите их.</p>
	</div>

	<table class="tableZ">
		<thead>
			<tr>
				<th>Личные местоимения</th>
				<th>Единственное число</th>
				<th>Множественное число</th>
			</tr>
		</thead>

		<tbody>
			<tr>
				<td>1-е лицо</td>
				<td>Im, ni (Я)</td>
				<td>Mi (Мы)</td>
			</tr>

			<tr>
				<td>2-е лицо (уваж.)</td>
				<td>Le (Вы) </td>
				<td>Le (Вы)</td>
			</tr>

			<tr>
				<td>2-е лицо </td>
				<td>Ci, ech (Ты)</td>
				<td>Ci (Вы)</td>
			</tr>

			<tr>
				<td>3-е лицо (муж.род)</td>
				<td>Ho, e (Он)</td>
				<td>Hy (Они – все муж.рода)</td>
			</tr>

			<tr>
				<td>3-е лицо (жен. род)</td>
				<td>He, e (Она)</td>
				<td>Hi (Они – все жен. рода) </td>
			</tr>

			<tr>
				<td>3-е лицо (средний род)</td>
				<td>Ha, e (Оно)</td>
				<td>Hai (Они – любого рода) </td>
			</tr>
		</tbody>
	</table>

	<p class="textMain">
		“Hy” следует использовать, если известно, что все члены группы мужского рода, “Hi” – если все
		женского рода. Если же это неизвестно или в группе есть как женщины, так и мужчины, то
		используйте “Hai”.
	</p>

	<div class="divider"></div>

	<table class="tableZ">
		<thead>
			<tr>
				<th>Слова, которые следует выучить</th>
			</tr>
		</thead>

		<tbody>
			<tr>
				<td>Синдарин</td>
				<td>Перевод</td>
			</tr>

			<tr>
				<td>Edhellen</td>
				<td>Синдарин, эльфийский язык </td>
			</tr>

			<tr>
				<td>Edhel (Edhil)</td>
				<td>Эльф (Эльфы) </td>
			</tr>

			<tr>
				<td>Elleth</td>
				<td>Эльфийка</td>
			</tr>

			<tr>
				<td>Adan (Edain)</td>
				<td>Человек (Люди)</td>
			</tr>

			<tr>
				<td>Naug (Noeg) </td>
				<td>Гном (Гномы)</td>
			</tr>

			<tr>
				<td>Perian (Periain) </td>
				<td>Хоббит (Хоббиты) </td>
			</tr>

			<tr>
				<td>Imladris</td>
				<td>Ривенделл </td>
			</tr>

			<tr>
				<td>Lothlorien </td>
				<td>Лотлориен </td>
			</tr>

			<tr>
				<td>Ardh</td>
				<td>Земля (планета), страна (государство)</td>
			</tr>

			<tr>
				<td>Ma</td>
				<td>Да</td>
			</tr>

			<tr>
				<td>Uin</td>
				<td>Нет</td>
			</tr>

			<tr>
				<td>Eneth</td>
				<td>Имя</td>
			</tr>

			<tr>
				<td>Mellon (Mellyn) </td>
				<td>Друг (Друзья)</td>
			</tr>
		</tbody>
	</table>

	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Ответы</p>
	</div>
	<p class="textMain">4. 1) Mae govannen; 2) Man i eneth lîn; 3) Le suilon; 4) Namariё; 5) Novaer; 6) Cuio vae.</p>
	<p class="textMain">5. Adan – человек; Edhel – эльф.</p>
</div>

<style lang="scss">
	@import '$lib/styles/urok.scss';
</style>

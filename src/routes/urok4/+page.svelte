<script>
	import AudioPlayer from '$lib/components/AudioPlayer.svelte';
	import LessonTextField from '$lib/components/LessonTextField.svelte';
	import Sochinenie from '$lib/components/Sochinenie.svelte';
	import WordInput from '$lib/components/WordInput.svelte';
</script>

<div class="maincontent">
	<p class="zaglavie">Урок 4<span>Sen i ‘ardh vain!</span></p>
	<div class="zadanie">
		<p class="textMain">Мягкая мутация (лениция)</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">
			Прежде чем рассмотреть подробно мягкую мутацию, скажем, что такое мутация «вообще». Мутация –
			это изменение первой буквы в слове при определённых условиях. Она создана для придания
			плавности речи. А так как как речь эльфов течёт словно ручей – для Толкина это было одной из
			основных задач – без мутации не обойтись.
		</p>
		<br />
		<p class="textMain">
			В Синдарине существует несколько видов мутаций, основная из них – мягкая мутация. Она
			«срабатывает» в следующих случаях:
		</p>
		<br />
		<p class="textMain">
			1) Существительное единственного числа с определённым артиклем изменяется (iDhraug);
		</p>
		<p class="textMain">
			2) Глагол-сказуемое, стоящий сразу после подлежащего, изменяется (Beleg bâd);
		</p>
		<p class="textMain">
			3) Дополнение (винительный и дательный падежи) изменяется (Padon nan garas);
		</p>
		<p class="textMain">
			4) Прилагательное, стоящее за определяемым существительным, изменяется (iLinnad vain);
		</p>
		<p class="textMain">5) Вторая часть составного слова изменяется.</p>
		<p class="textMain">6) Перед словом стоит частица отрицания «ú-»</p>
	</div>
	<div class="divider"></div>

	<table class="tableZ">
		<thead>
			<tr>
				<th>Согласная</th>
				<th>Её мутация</th>
				<th>Пример</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>s</td>
				<td>h</td>
				<td>Saew – iHaew <br /> Sîr – Padon na hîr</td>
			</tr>
			<tr>
				<td>h</td>
				<td>ch</td>
				<td>Hîr – iChîr <br /> Haew – Û-eglerion iChaew</td>
			</tr>
			<tr>
				<td>m</td>
				<td>v</td>
				<td>mellon – iVellon <br /> magol – Anno vagol nîn! </td>
			</tr>
			<tr>
				<td>b</td>
				<td>v</td>
				<td>band – iVand <br /> bauglir – Dennim vauglir</td>
			</tr>
			<tr>
				<td>c</td>
				<td>g</td>
				<td>calad – iGalad <br /> car – Edhil gerir var</td>
			</tr>
			<tr>
				<td>g</td>
				<td>‘</td>
				<td>galadh – i ‘aladh <br />gova – Mellyn ‘ovar na chitorod</td>
			</tr>
			<tr>
				<td>t</td>
				<td>d</td>
				<td>tawar – iDawar <br />tir – Maethor dîr na rhûn</td>
			</tr>
			<tr>
				<td>d</td>
				<td>dh</td>
				<td>daw – iDhaw <br /> draug – Cenim dhraug na daur</td>
			</tr>
			<tr>
				<td>p</td>
				<td>b</td>
				<td>pethron – iBethron <br />pada – E bada na garas</td>
			</tr>
			<tr>
				<td>lh</td>
				<td>thl</td>
				<td rowspan="2">Изменение происходит только в первых трёх случаях</td>
			</tr>
			<tr>
				<td>rh</td>
				<td>thr</td>
			</tr>
			<tr>
				<td>Остальные </td>
				<td>Без изменений</td>
				<td></td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Внимание!</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">1) «‘» – не произносится. Т.е. «‘ovar» читается как «овар».</p>
		<p class="textMain">
			2) Мутация происходит только один раз, даже если слово попадает под два случая сразу.
		</p>
		<p class="textMain">3) Мутируют только согласные, любые гласные остаются без изменений.</p>
		<p class="textMain">
			4) Сказуемое мутирует только в том случае, если стоит сразу после подлежащего. Aragorn aran
			Gondor pada na Imladris (Арагорн, король Гондора, идёт в Ривенделл) – здесь глагол «pada» не
			изменяется, т.к. между подлежащим и сказуемым есть ещё другие слова.
		</p>
		<p class="textMain">
			5) «th», «dh», «ch», «lh» и «rh» надо рассматривать как одну «букву». Т.е. «th», в отличии от
			«t», мутировать не будет! Taur – iDaur, но Thond – iThond
		</p>
	</div>
	<div class="divider"></div>

	<div class="zadanieText">
		<p class="textMain">Примеры</p>
		<br />
		<p class="textMain">
			1) iVrog – здесь произошла лениция, т.к. это существительное стоит с определённым артиклем.
			Из-за того, что в «v» мутируют и «m», и «b», об исходном слове придётся догадаться. Во-первых
			может помочь контекст, во-вторых одного из слов может просто не существовать (в синдарине нет
			слова «mrog»).
		</p>
		<br />
		<p class="textMain">
			2) Padon na hîr – здесь произошла лениция, т.к. hîr – дополнение. Исходное слово «sîr» (река),
			потому что «s» мутирует в «h» (см. таблицу). Перевод предложения – «Я иду к реке».
		</p>
		<br />
		<p class="textMain">
			3) Aragorn bada na Imladris – здесь лениция вызвана сказуемым, которое идёт сразу после
			подлежащего. Исходное слово «pada», т.к. «p» мутирует в «b». Перевод предложения – «Арагорн
			идёт в Ривенделл».
		</p>
		<br />
		<p class="prim">Теперь закрепите этот материал, и мы перейдём к новой лексике.</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			1. Перепишите предложения, раскрыв скобки. Каждый раз проговаривайте, почему в этом случае
			происходит или не происходит мутация. Если встретите незнакомые слова, посмотрите их перевод в
			конце урока.
		</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">1) Cenin (d)raug. E (m)ithren.</p>
		<Sochinenie />
		<br />
		<p class="textMain">2) Mellon nîn (p)êd man melin Eleniel dan sen ú-(th)and.</p>
		<Sochinenie />
		<br />
		<p class="textMain">3) Padon na (e)ryd.</p>
		<Sochinenie />
		<br />
		<p class="textMain">4) Mithrandir (p)êd dan ú-(l)aston. E na (h)aered.</p>
		<Sochinenie />
		<br />
		<p class="textMain">5) Iston i(H)û. Ho (m)ellon nîn.</p>
		<Sochinenie />
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">2. Перепишите данные слова с определённым артиклем.</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">1) Brog <WordInput /></p>
		<br />
		<p class="textMain">2) Laboth <WordInput /></p>
		<br />
		<p class="textMain">3) Cabor <WordInput /></p>
		<br />
		<p class="textMain">4) Aras <WordInput /></p>
		<br />
		<p class="textMain">5) Annabon <WordInput /></p>
		<br />
		<p class="textMain">6) Ithil <WordInput /></p>
		<br />
		<p class="textMain">7) Graw <WordInput /></p>
		<br />
		<p class="textMain">8) Galadh <WordInput /></p>
		<br />
		<p class="textMain">9) Tiriel <WordInput /></p>
		<br />
		<p class="textMain">10) Mellon <WordInput /></p>
		<br />
		<p class="textMain">11) Aew <WordInput /></p>
		<br />
		<p class="textMain">12) Rusc <WordInput /></p>
		<br />
		<p class="textMain">13) Gwilwileth <WordInput /></p>
		<br />
		<p class="textMain">14) Hû <WordInput /></p>
		<br />
		<p class="textMain">15) Perian <WordInput /></p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			3. Представьте, что вы шли в магазин и внезапно встретили гнома и эльфа, которые говорят на
			Синдарине. Вам захотелось подойти к ним и познакомиться. Составьте диалог (приветствие,
			знакомство, прощание) и расскажите его вслух. Если вы учите эльфийский в группе, прочитайте
			диалог по ролям.
		</p>
	</div>
	<div class="zadanieText"><Sochinenie /></div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Прилагательные</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">
			В синдарине прилагательные идут после существительного и подвергаются мягкой мутации. Если
			прилагательных несколько, и они идут «через запятую», мутации подвергается лишь первое. Если
			два прилагательных соединены союзом «и», мутации подвергаются оба прилагательных. Если
			существительное стоит во множественном числе, прилагательное тоже следует поставить во
			множественное число. Оно образуется как и у существительных – путём изменения гласных.
		</p>
		<br />
		<p class="textMain">Примеры</p>
		<br />
		<p class="textMain">
			Mellon vilui maer – Добрый, хороший друг (milui – добрый, maer - хороший)<br /> Elleth vain a hael
			– Красивая и мудрая эльфийка (bain – красивый, sael - мудрый)
		</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Цвета</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">
			Без знания цветов в Средиземье, да и во всей Арде, вам не обойтись. Так что их просто
			необходимо выучить наизусть (как впрочем и все остальные слова в Синдарине :) ).
		</p>
		<br />
		<p class="textMain">Caran - Красный</p>
		<br />
		<p class="textMain">Carnin - Алый</p>
		<br />
		<p class="textMain">Luin – Синий</p>
		<br />
		<p class="textMain">Elu - Голубой</p>
		<br />
		<p class="textMain">Malen - Жёлтый</p>
		<br />
		<p class="textMain">Calen, Laeg (арх.) – Зелёный, зелёный (арх.)</p>
		<br />
		<p class="textMain">Morn – Чёрный</p>
		<br />
		<p class="textMain">Baran – Тёмно-коричневый</p>
		<br />
		<p class="textMain">Rhosg - Коричневый</p>
		<br />
		<p class="textMain">Faen, fain - Белый</p>
		<br />
		<p class="textMain">Nimp - Бледный</p>
		<br />
		<p class="textMain">Glos - Белоснежный</p>
		<br />
		<p class="textMain">Mith - Серый</p>
		<br />
		<p class="textMain">Cull - Оранжевый</p>
		<br />
		<p class="textMain">Crinth – Розовый</p>
		<br />
		<p class="textMain">Ling - Фиолетовый</p>
		<br />

		<p class="textMain">Примеры</p>
		<br />
		<table class="tableZ">
			<tbody>
				<tr>
					<td>Laboth faen – Белый заяц </td>
					<td
						>Прилагательное идёт после существительного, оно подвергается мягкой мутации, но не
						изменяется, т.к. «f» остаётся без изменений (см. таблицу мягкой мутации)</td
					>
				</tr>
				<tr>
					<td>Yrch vyrn – Чёрные орки </td>
					<td
						>Слово «morn» подвергается мягкой мутации («m» переходит в «v»); т.к. слово «orch» стоит
						во мн.ч., прилагательное тоже ставится во мн.ч. («o» переходит в «y» в конце слова – см.
						таблицу образования множественных чисел во втором уроке)
					</td>
				</tr>
			</tbody>
		</table>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Я вижу… (Cenin…)</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">
			Часто бывает необходимо описать что-либо. Например, вы разведчик в отряде эльфов и забрались
			на дерево, чтобы осмотреть окрестности. И надо рассказать о том, что вы видите. Для этого
			можно использовать глагол «cen» - «видеть». Дополнение, идущее после глагола, будет мутировать
			(3-ий случай, см. правило).
		</p>
		<br />
		<table class="tableZ">
			<tbody>
				<tr>
					<td>Примеры</td>
					<td>Комментарии</td>
				</tr>
				<tr>
					<td>Cenin vrog rhosg – Я вижу коричневого медведя </td>
					<td
						>Внимание! Если вы посмотрите в таблицу мутаций, то увидите, что «rh» изменяется на
						«thr». Но стоит помнить, что это происходит лишь в первых трёх случаях, а прилагательное
						– четвёртый.
					</td>
				</tr>
				<tr>
					<td>Cenin adab Arwen – Я вижу дом Арвен</td>
					<td>«En» для родительного падежа опускается, т.к. «Арвен» - имя собственное </td>
				</tr>
			</tbody>
		</table>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			4. Посмотрите на картинки и скажите, что вы видите. Ниже можно найти полезные слова, которые
			пригодятся при описании. Запишите к каждой картинке как можно больше предложений.
		</p>
	</div>
	<div class="zadanieText">
		<img src="/images/4-1.jpg" alt="urok 4 img 1" />
		<Sochinenie />
		<br />
		<img src="/images/4-2.jpg" alt="urok 4 img 2" />
		<Sochinenie />
		<br />
		<img src="/images/4-3.jpg" alt="urok 4 img 3" />
		<Sochinenie />
		<br />
		<p class="textMain">Caras - Поселение</p>
		<p class="textMain">Ost - Город</p>
		<p class="textMain">Lanthir – Водопад</p>
		<p class="textMain">Galadh – Дерево</p>
		<p class="textMain">Sîr – Река, поток</p>
		<p class="textMain">Ithron – Маг, волшебник</p>
		<p class="textMain">Lad – Долина</p>
		<p class="textMain">Calad – Свет</p>
		<p class="textMain">Amon – Холм</p>
		<p class="textMain">Gwilith – Небо</p>
		<p class="textMain">Othronn – Подземный город, крепость</p>
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">
			5. Прослушайте диалог. Заполните пропуски. Переведите. После этого прочитайте по ролям с
			диктором.
		</p>
		<AudioPlayer src="/audio/Edhellen_Urok4_Upr5.mp3" />
	</div>
	<div class="zadanieText">
		<p class="textMain">
			Aragorn ‘obada adan gaeleb na <WordInput />. Reviar min daur galen. Govadar <WordInput />.
		</p>
		<br />
		<p class="textMain"><span class="italic">Aragorn</span>: Mae govannen!</p>
		<p class="textMain"><span class="italic">Edhel</span>: Arad vaer! Man i <WordInput /> lîn?</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Im <WordInput /> Arathornion. Tegin vellon nîn na <WordInput
			/>, e caeleb.
		</p>
		<p class="textMain"><span class="italic">Edhe</span>: Cenin. Im Eglerion. Pelin thaed?</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Ma. Sí yrch rim. Gobada ven a dago hain!
		</p>
		<p class="textMain">
			<span class="italic">Edhel</span>: Mae. <WordInput /> gîn fîr. <WordInput />!
		</p>
		<br />
		<p class="textMain">Thinna. Aduial tel min <WordInput />.</p>
		<br />
		<p class="textMain"><span class="italic">Edhel</span>: <WordInput />, tiro!</p>
		<p class="textMain"><span class="italic">Aragorn</span>: Man cenig?</p>
		<p class="textMain">
			<span class="italic">Edhel</span>: Nîn luin Bruinen. A Elbereth, ennas <WordInput />!
		</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Ma, ha ennas! Hannon, <WordInput />. Novaer!
		</p>
		<p class="textMain">
			<span class="italic">Edhel</span>: Glassen. <WordInput />, Aragorn Arathornion!
		</p>
		<br />
		<p class="textMain">Ответьте на вопросы по диалогу:</p>
		<br />
		<p class="textMain">1) Кто шёл с Арагорном?</p>
		<Sochinenie />
		<p class="textMain">2) Куда направлялся Арагорн со своим спутником и почему?</p>
		<Sochinenie />
		<p class="textMain">3) Кого встретил Арагорн? Как его зовут?</p>
		<Sochinenie />
		<p class="textMain">4) Какая помощь нужна была Арагорну?</p>
		<Sochinenie />
		<p class="textMain">5) Почему незнакомец попросил Арагорна поторопиться?</p>
		<Sochinenie />
		<p class="textMain">6) Что увидел незнакомец вечером? Почему его это так взволновало?</p>
		<Sochinenie />
	</div>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Притяжательные местоимения</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">
			Притяжательные местоимения – это местоимения «мой», «твой», «его» и другие. В Синдарине они
			ничем не отличаются от прилагательных: стоят после существительного и подвергаются мутации.
		</p>
		<br />
		<table class="tableZ">
			<tbody>
				<tr>
					<th>Притяжательные местоимения</th>
					<th>Единственное число</th>
					<th>Множественное число</th>
				</tr>
				<tr>
					<th>1-е лицо</th>
					<th>Nîn (мой)</th>
					<th>Mîn (наш)</th>
				</tr>
				<tr>
					<th>2-е лицо (уваж.)</th>
					<th>Lîn (ваш)</th>
					<th>Lîn (ваш)</th>
				</tr>
				<tr>
					<th>2-е лицо</th>
					<th>Cîn (твой)</th>
					<th>Cîn (ваш)</th>
				</tr>
				<tr>
					<th>3-е лицо</th>
					<th>Tîn (его/её/его)</th>
					<th>Tîn (их)</th>
				</tr>
				<tr>
					<th>3-е лицо (возвратные)</th>
					<th>În (его/её/его)</th>
					<th>În (их)</th>
				</tr>
			</tbody>
		</table>
		<br />
		<p class="textMain">Внимание!</p>
		<br />
		<p class="textMain">
			1) Возвратные местоимения следует использовать, если предмет принадлежит тому, о ком говорится
			в предложении. Например: «Maba i ylf în» – «Он берёт свою [собственную] чашку»; «Maba i ylf
			dîn» - «Он берёт его чашку [т.е. чашку кого-то другого]».
		</p>
		<p class="textMain">
			2) Перед существительным с притяжательным местоимением всегда ставится определённый артикль.
			Он опускается лишь в том случае, если существительное – человек (персона). Например: «Maetha i
			vaeth în» - «Он сражается в его собственной битве»; «Cenin vess dîn» - «Я вижу его жену».
		</p>
	</div>
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
				<td>Mallen</td>
				<td>Золотой</td>
			</tr>
			<tr>
				<td>Celeb</td>
				<td>Серебряный</td>
			</tr>
			<tr>
				<td>Rustui</td>
				<td>Медный</td>
			</tr>
			<tr>
				<td>Man</td>
				<td>Что</td>
			</tr>
			<tr>
				<td>Mel</td>
				<td>Любить</td>
			</tr>
			<tr>
				<td>Sen</td>
				<td>Это</td>
			</tr>
			<tr>
				<td>Thand</td>
				<td>Правда</td>
			</tr>
			<tr>
				<td>Dan</td>
				<td>Но</td>
			</tr>
			<tr>
				<td>Haered</td>
				<td>Даль, большое расстояние</td>
			</tr>
			<tr>
				<td>Ista</td>
				<td>Знать</td>
			</tr>
			<tr>
				<td>Milui</td>
				<td>Дружелюбный, добрый</td>
			</tr>
			<tr>
				<td>Bain</td>
				<td>Красивый</td>
			</tr>
			<tr>
				<td>Sael</td>
				<td>Мудрый</td>
			</tr>
			<tr>
				<td>Caras</td>
				<td>Поселение (чаще на деревьях)</td>
			</tr>
			<tr>
				<td>Galadh</td>
				<td>Дерево</td>
			</tr>
			<tr>
				<td>Lad</td>
				<td>Долина</td>
			</tr>
			<tr>
				<td>Calad</td>
				<td>Свет</td>
			</tr>
			<tr>
				<td>Amon</td>
				<td>Холм</td>
			</tr>
			<tr>
				<td>Ost</td>
				<td>Город</td>
			</tr>
			<tr>
				<td>Sîr</td>
				<td>Река, поток</td>
			</tr>
			<tr>
				<td>Gwilith</td>
				<td>Небо</td>
			</tr>
			<tr>
				<td>Lanthir</td>
				<td>Водопад</td>
			</tr>
			<tr>
				<td>Ithron</td>
				<td>Маг, волшебник</td>
			</tr>
			<tr>
				<td>Othronn</td>
				<td>Подземный город, крепость</td>
			</tr>
			<tr>
				<td>Gopad</td>
				<td>Идти с (кем-то)</td>
			</tr>
			<tr>
				<td>Caeleb</td>
				<td>Больной, заболевший, нездоровый</td>
			</tr>
			<tr>
				<td>Taur</td>
				<td>Лес</td>
			</tr>
			<tr>
				<td>Govad</td>
				<td>Встречать</td>
			</tr>
			<tr>
				<td>Arad</td>
				<td>День</td>
			</tr>
			<tr>
				<td>Tog</td>
				<td>Вести (кого-то), приносить</td>
			</tr>
			<tr>
				<td>Pol</td>
				<td>Мочь, быть способным</td>
			</tr>
			<tr>
				<td>Tulu</td>
				<td>Помогать, помощь</td>
			</tr>
			<tr>
				<td>Sí</td>
				<td>Здесь</td>
			</tr>
			<tr>
				<td>Ennas</td>
				<td>Там</td>
			</tr>
			<tr>
				<td>Men</td>
				<td>Нас, нами</td>
			</tr>
			<tr>
				<td>Dag</td>
				<td>Убивать</td>
			</tr>
			<tr>
				<td>Sain</td>
				<td>Их</td>
			</tr>
			<tr>
				<td>Gín</td>
				<td>Твой</td>
			</tr>
			<tr>
				<td>Fîr</td>
				<td>Умирать</td>
			</tr>
			<tr>
				<td>Nen (nîn)</td>
				<td>Вода (воды)</td>
			</tr>
			<tr>
				<td>A Elbereth</td>
				<td>А Элберет (Обращение к Варде – слава богу; о боже и т.д.)</td>
			</tr>
			<tr>
				<td>Hannon</td>
				<td>Благодарю</td>
			</tr>
			<tr>
				<td>Glassen</td>
				<td>Пожалуйста (ответ на спасибо)</td>
			</tr>
			<tr>
				<td colspan="2">Все цвета из таблицы</td>
			</tr>
		</tbody>
	</table>
	<div class="divider"></div>

	<div class="zadanie">
		<p class="textMain">Ответы</p>
	</div>
	<div class="zadanieText">
		<p class="textMain">1.</p>
		<p class="textMain">1) Cenin dhraug. E vithren.</p>
		<p class="textMain">2) Mellon nîn pêd man melin Eleniel dan sen ú-thand.</p>
		<p class="textMain">3) Padon na eryd.</p>
		<p class="textMain">4) Mithrandir bêd dan ú-laston. E na chaered.</p>
		<p class="textMain">5) Iston iChû. Ho mellon nîn.</p>
		<br />
		<p class="textMain">2.</p>
		<p class="textMain">1) iVrog</p>
		<p class="textMain">2) iLaboth</p>
		<p class="textMain">3) iGabor</p>
		<p class="textMain">4) i Aras</p>
		<p class="textMain">5) i Annabon</p>
		<p class="textMain">6) i Ithil</p>
		<p class="textMain">7) i ‘raw</p>
		<p class="textMain">8) i ‘aladh</p>
		<p class="textMain">9) iDiriel</p>
		<p class="textMain">10) iVellon</p>
		<p class="textMain">11) i Aew</p>
		<p class="textMain">12) iRusc</p>
		<p class="textMain">13) i ‘wilwileth</p>
		<p class="textMain">14) iChû</p>
		<p class="textMain">15) iBerian</p>
		<br />
		<p class="textMain">4.</p>
		<p class="textMain">
			1) Cenin ithron vith a berian. Cenin edaib elu. Cenin garas Imladris. Cenin edhil. Cenin sîr a
			lenthir.
		</p>
		<p class="textMain">2) Cenin ‘aladh elu ah ‘aladh valen. Cenin amon ah ost.</p>
		<p class="textMain">
			3) Cenin eryd vith. Cenin ost enan edain ah othronn en noeg. Ha Erebor. Cenin ‘wilith elu ah
			iLanthir.
		</p>
		<br />
		<p class="textMain">5.</p>
		<p class="textMain">
			Aragorn ‘obada adan gaeleb na Imladris. Reviar min daur galen. Govadar edhel.
		</p>
		<br />
		<p class="textMain"><span class="italic">Aragorn</span>: Mae govannen!</p>
		<p class="textMain"><span class="italic">Edhel</span>: Arad vaer! Man i eneth lîn?</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Im Aragorn Arathornion. Tegin vellon nîn na Imladris, e
			caeleb.
		</p>
		<p class="textMain"><span class="italic">Edhel</span>: Cenin. Im Eglerion. Pelin thaed?</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Ma. Sí yrch rim. Gobada ven a dago hain!
		</p>
		<p class="textMain"><span class="italic">Edhel</span>: Mae. Mellon gîn fîr. Tolo!</p>
		<br />
		<p class="textMain">Thinna. Aduial tel min Ennorath.</p>
		<br />
		<p class="textMain"><span class="italic">Edhe</span>: Aragorn, tiro!</p>
		<p class="textMain"><span class="italic">Aragorn</span>: Man cenig?</p>
		<p class="textMain">
			<span class="italic">Edhe</span>: Nîn luin Bruinen. A Elbereth, ennas Imladris!
		</p>
		<p class="textMain">
			<span class="italic">Aragorn</span>: Ma, ha ennas! Hannon, Eglerion. Novaer!
		</p>
		<p class="textMain">
			<span class="italic">Edhe</span>: Glassen. Cuio vae, Aragorn Arathornion!
		</p>
		<br />
		<p class="textMain">Перевод:</p>
		<p class="textMain">
			Арагорн идёт с больным человеком в Ривенделл. Они странствуют по зелёному лесу. Встретили
			эльфа.
		</p>
		<br />
		<p class="textMain">Арагорн: Здравствуй!</p>
		<p class="textMain">Эльф: Доброго дня! Как вас зовут?</p>
		<p class="textMain">
			Арагорн: Я Арагорн, сын Араторна. Я веду моего друга в Ривенделл, ему плохо.
		</p>
		<p class="textMain">Эльф: Я вижу. Меня зовут Эглерион. Я могу помочь?</p>
		<p class="textMain">Арагорн: Да. Здесь много орков. Иди с нами и убивай их!</p>
		<p class="textMain">Эльф: Хорошо. Твой друг умирает. Пошли!</p>
		<br />
		<p class="textMain">Смеркается. Вечер приходит в Средиземье.</p>
		<br />
		<p class="textMain">Эльф: Арагорн, смотри!</p>
		<p class="textMain">Арагорн: Что ты видишь?</p>
		<p class="textMain">Эльф: Синие воды Бруинена. О Элберет, там Ривенделл!</p>
		<p class="textMain">Арагорн: Да, он там! Спасибо, Эглерион. Пока!</p>
		<p class="textMain">Эльф: Пожалуйста. До встречи, Арагорн, сын Араторна!</p>
		<br />
		<p class="textMain">1) С Арагорном шёл человек.</p>
		<p class="textMain">2) Они направлялись в Ривенделл, потому что друг Арагорна заболел.</p>
		<p class="textMain">3) Арагорн встретил эльфа. Его звали Эглерион.</p>
		<p class="textMain">
			4) Арагорн попросил эльфа пойти с ними и помочь ему убивать орков по дороге, так как в тех
			краях их было много.
		</p>
		<p class="textMain">5) Эглерион увидел, что друг Арагорна умирает.</p>
		<p class="textMain">
			6) Эльф увидел воды реки Бруинен, а это значит, что они почти дошли до Ривенделла.
		</p>
	</div>
</div>

<style lang="scss">
	@import '$lib/styles/urok.scss';
</style>

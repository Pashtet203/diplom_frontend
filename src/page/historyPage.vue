<template>
    <div>
        <div class="container__hist">
            <h2 class="title__hist">Эпохи классической музыки</h2>
            <div class="line"></div>
            <div class="era__list">
                <div class="era__list-item">
                    <img src="../assets/classical_era/vozrozdenie.jpg" alt="" class="images">
                    <div @click="vozr" class="item__text">Возрождения</div>
                </div>
                <div class="era__list-item">
                    <img src="../assets/classical_era/barroko.jpg" alt="" class="images">
                    <div @click="barr" class="item__text">Барроко</div>
                </div>
                <div class="era__list-item">
                    <img src="../assets/classical_era/class.jpeg" alt="" class="images">
                    <div @click="classic" class="item__text">Классицизма</div>
                </div>
                <div class="era__list-item">
                    <img src="../assets/classical_era/roman.jpg" alt="" class="images">
                    <div @click="romantizm" class="item__text">Романтизма</div>
                </div>
                <div class="era__list-item">
                    <img src="../assets/classical_era/XX.jpg" alt="" class="images">
                    <div @click="XX_age" class="item__text">ХХ века</div>
                </div>
            </div>
            <div class="era__info vozrozdenie" v-if="vozrozdenie">
                <p class="era__title">Эпоха Возрождения</p>
                <div class="era__text">
                    Возрождение, или Ренессанс, — период в истории культуры Западной и Центральной Европы, охватывающий
                    примерно
                    XIV—XVI вв. Свое название этот период получил в связи с возрождением интереса к античному искусству,
                    ставшему идеалом для деятелей культуры нового времени. Композиторы и музыкальные теоретики — Й.
                    Тинкторис,
                    Дж. Царлино и другие — изучали древнегреческие музыкальные трактаты; в произведениях Жоскена Депре,
                    которого
                    сравнивали с Микеланджело, по словам современников, «возродилось утерянное совершенство музыки древних
                    греков»: появившаяся в конце XVI— начале XVII в. опера ориентировалась на законы античной драмы.
                </div>
                <div class="era__text">
                    Развитие культуры Возрождения связано с подъемом всех сторон жизни общества. Родилось новое
                    мировоззрение —
                    гуманизм (от латинского humanus — «человечный»). Раскрепощение творческих сил привело к бурному развитию
                    науки, торговли, ремесел, в экономике складывались новые, капиталистические отношения. Изобретение
                    книгопечатания способствовало распространению образования. Великие географические открытия и
                    гелиоцентрическая система мира Н. Коперника изменили представления о Земле и Вселенной.

                    Небывалого расцвета достигли изобразительное искусство, архитектура, литература. Новое мироощущение
                    отразилось в музыке и преобразило ее облик. Она постепенно отходит от норм средневекового канона,
                    индивидуализируется стиль, впервые появляется само понятие «композитор». Изменяется фактура
                    произведений,
                    число голосов увеличивается до четырех, шести и более (известен, например, 36-голосный канон,
                    приписываемый
                    крупнейшему представителю нидерландской школы Й. Окегему). В гармонии господствуют консонирующие
                    созвучия,
                    употребление диссонансов строго ограничивается специальными правилами.
                    Складываются мажорный и минорный лады и тактовая система ритмики, характерные для более поздней музыки.
                </div>
                <div class="era__text">
                    Все эти новые средства использовались композиторами для передачи особого строя чувств человека эпохи
                    Возрождения — возвышенного, гармоничного, спокойного и величественного. Более тесной становится связь
                    текста
                    и музыки, музыка начинает передавать настроение, или, как тогда говорили, аффекты текста, нередко
                    особыми
                    музыкальными средствами иллюстрируются отдельные слова, такие, как «жизнь», «смерть», «любовь» и др.

                    Музыка эпохи Возрождения развивалась в двух направлениях — церковном и светском. Основные жанры
                    церковной
                    музыки — месса и мотет — многоголосные полифонические произведения для хора без сопровождения или в
                    сопровождении инструментального ансамбля. Из инструментов предпочтение
                    отдавалось органу.

                    Развитию светской музыки способствовал рост любительского музицирования. Музыка звучала всюду: на
                    улицах, в
                    домах горожан, во дворцах знатных вельмож. Появились первые концертирующие исполнители-виртуозы на
                    лютне,
                    клавесине, органе, виоле, различных видах продольных флейт. В полифонических песнях (мадригале — в
                    Италии,
                    шансон — во Франции) композиторы рассказывали о любви, обо всем, что встречается в жизни. Вот названия
                    некоторых песен: «Охота на оленя», «Эхо», «Битва при Мариньяно».
                </div>
                <div class="era__text">
                    В XV—XVI вв. возрастает значение искусства танца, появляются многочисленные трактаты и практические
                    руководства по хореографии, сборники танцевальной музыки, в которые включаются популярные танцы того
                    времени
                    — бас-данс, бранль, павана, гальярда.

                    В эпоху Возрождения формируются национальные музыкальные школы. Самая крупная из них — нидерландская
                    (франко-фламандская) полифоническая школа. Ее представители — Г. Дюфаи, К. Жанекен, Й. Окегем, Я.
                    Обрехт,
                    Жоскен Депре, О. Лассо. Среди других национальных школ — итальянская (Дж. П. Палестрина), испанская (Т.
                    Л.
                    де Виктория), английская (У. Берд), немецкая (Л. Зенфль).

                    Эпоха Возрождения завершается появлением новых музыкальных жанров: сольной песни, оратории, оперы,
                    подлинный
                    расцвет которых наступает в последующем столетии (см. Западноевропейская музыка XVII—XX вв.).
                </div>

            </div>
            <div class="era__info barroko" v-if="barroko">
                <p class="era__title">Эпоха Барроко</p>
                <div class="era__text">Стиль барокко зародился в начале 17 века в Риме, Италии. Он быстро распространился по
                    Европе во Францию, Испанию, Португалию, а затем в Австрию, Германию и Россию. Этот стиль использовал
                    сложные орнаменты, насыщенные цвета, контрастность, а также элементы роскоши и торжественности, чтобы
                    вызывать удивление и чувство благоговения. Стиль барокко повлиял на все виды искусства, включая
                    архитектуру, литературу, живопись, скульптуру, танцы и музыку.
                </div>
                <div class="era__text">
                    В сфере музыки стиль барокко зародился в конце 16 века в нескольких итальянских городах. Благодаря
                    политической независимости и экономическому разнообразию появился ряд уникальных и индивидуальных
                    музыкальных стилей, которые сильно отличались от классических идеалов позднего Ренессанса,
                    использованных в произведениях Палестрины и Ди Лассо. Культурные и политические центры Венеции и
                    Флоренции заслуживают наибольшего внимания среди остальных городов.

                    Собор Святого Марка в Венеции служил географическим местом для развития полихоральной музыки Джованни
                    Габриели. Этот стиль был основан на принципе нескольких пространственно разделенных хоров с голосами и
                    инструментами, которые при одновременном исполнении требовали более простые гоморитмические аккордовые
                    текстуры. Такой подход концептуально разнился с идеальностью сложной имитационной полифонии позднего
                    Ренессанса.

                    Примерно в то же время во Флоренции группа интеллектуалов, гуманистов и художников, известная как
                    «Флорентийская камерата», стремилась подражать концепции классической греческой драмы, в которой слова и
                    музыка были объединены в отличие от мадригалов эпохи Ренессанса. Музыкальная обстановка не должна мешать
                    естественным разговорным интонациям текста, а слова должны быть выражены как можно более четко. Для
                    сопровождения нового музыкального формата сложная контрапунктовая природа мотета и мадригала эпохи
                    Ренессанса была заменена простой аккордовой текстурой, создаваемой инструментами, которые не отвлекали
                    от содержания текста. Эти разработки породили новый стиль пения, получивший название “монодия”, который
                    стал одним из самых важных нововведений музыки эпохи барокко.
                </div>
                <div class="era__text">
                    Самый влиятельный композитор и музыкант в стиле барокко всех времен, Иоганн Себастьян Бах, непрерывно
                    трудился над созданием более двухсот лютеранских кантат. Это был еще один важный вокальный жанр периода
                    барокко, который включал классические элементы лютеранских обрядов, таких как хорал и сольные песни, а
                    также новые разработки в виде речитатива и стиля арии итальянского происхождения.

                    Бах родился в центральном немецком городе Айзенах в 1685 году в уважаемой музыкальной семье. Его жизнь
                    была посвящена музыке и лютеранской церкви, в которой он был набожным протестантом и служителем.
                    Преемниками Баха стали его четверо успешных сыновей-музыкантов, которые вошли в число крупных
                    композиторов переходного периода классической эпохи. Бах установил дружеские отношения с несколькими
                    композиторами той эпохи, а именно, с Дитрихом Букстехуде и Георгом Филиппом Телеманом, ставшим крестным
                    отцом его сына Карла Филиппа Эммануэля. Букстехуде был известным композитором и органистом, виртуозность
                    и композиторское мастерство которого побудили Баха пройти 200 миль пешком, чтобы встретиться с ним, а
                    затем провести совместное представление. Сфера влияния Баха настолько широка, что историки искусства в
                    целом признают его смерть решающим событием, которое в 1750 году положило конец периоду барокко.
                </div>
                <div class="era__text">
                    В период эпохи барокко инструментальные жанры и стили претерпели ряд серьезных изменений. Это было
                    связано как с техническими достижениями в конструкции инструментов, так и с появлением великих
                    виртуозов, которые соревновались друг с другом, тем самым преодолевая границы возможного. Знаменитыми
                    эпизодами таких состязаний были несколько встреч Доменико Скарлатти и Генделя в ранние годы 18 века. Два
                    композитора устроили дружеское музыкальное соревнование, в котором Скарлатти победил в игре на
                    клавесине, а Гендель - на органе.
                </div>
                <div class="era__text">
                    Три жанра эпохи барокко имеют особое значение для развития новых и уникальных характеристик.
                    Соло-концерт в стиле барокко - это произведение для оркестра и одного сольного инструмента. Такой формат
                    предоставил прекрасную среду для исследования эффекта контрастных звуков, различной плотности звука и
                    драматических виртуозных пассажей солиста, которые были привлекательны как для публики, так и для
                    эстетики барокко. В то же время появился другой вариант концерта - барочный Кончерто Гроссо. Такой
                    формат включал оркестр, но вместо отдельного солиста в нем использовалась небольшая группа или ансамбль
                    сольных инструментов, которые играли как единое целое.

                    И наконец, что не менее важно, в период барокко произошли глубокие изменения в области камерной музыки
                    для инструментов. Так изобретение сонаты для сольного инструмента и клавишных в конечном итоге
                    становится основным жанром на протяжении остальной части 19 и 20 веков. Трио-соната содержала две
                    мелодические линии и аккомпанемент «бассо континуо», фактически состоящий из полифонического
                    инструмента, такого как клавесин, а также мелодичного басового инструмента, который обеспечивал басовую
                    линию и гармоническое содержание.
                </div>
            </div>
            <div class="era__info class" v-if="class">
                <p class="era__title">Эпоха Классицизма</p>
                <div class="era__text">
                    Классицизм, сменивший через несколько этапов Эпоху Возрождения, сложился во Франции в конце XVII века,
                    отразив в своём искусстве отчасти серьёзный подъём абсолютной монархии, отчасти смену мировоззрения с
                    религиозного на светское.
                    В XVIII столетии начался новый виток развития общественного сознания – настала
                    Эпоха Просвещения. На смену пышности и высокопарности барокко, непосредственного предшественника
                    классицизма, пришёл стиль, основанный на простоте и естественности.
                </div>
                <div class="era__text">
                    Развитие новой музыкальной культуры в середине XVIII века породило возникновение множества частных
                    салонов, музыкальных обществ и оркестров, проведение открытых концертов и оперных представлений.
                    Столицей музыкального мира в те времена была Вена. Йозеф Гайдн, Вольфганг Амадей Моцарт и Людвиг ван
                    Бетховен – три великих имени, вошедших в историю, как венские классики. Композиторы венской школы
                    виртуозно владели самыми разными жанрами музыки – от бытовых песенок до симфоний. Высокий стиль музыки,
                    в котором богатое образное содержание воплощено в простой, но совершенной художественной форме, – вот
                    главная черта творчества венских классиков.
                </div>
                <div class="era__text">
                    Музыкальная культура классицизма, как и литература, а также изобразительное искусство, воспевает
                    поступки человека, его эмоции и чувства, над которыми царит разум. Художникам-творцам в их сочинениях
                    присущи логичность мышления, гармония и ясность формы. Простота и непринуждённость высказывания
                    композиторов-классиков могла бы показаться современному уху банальной (в некоторых случаях, разумеется),
                    если бы музыка их не была столь гениальной. Каждый из венских классиков обладал яркой, неповторимой
                    индивидуальностью. Гайдн и Бетховен более тяготели к инструментальной музыке – к сонатам, концертам и
                    симфониям. Моцарт был универсален во всем – он с легкостью творил в любом жанре. Он оказал огромное
                    влияние на развитие оперы, создавая и совершенствуя различные ее типы – от оперы буфф до музыкальной
                    драмы. В плане предпочтений композиторами тех или иных образных сфер для Гайдна более характерны
                    объективные народно-жанровые зарисовки, пастораль, галантность, Бетховену близка героика и драматизм, а
                    также философичность, ну и, конечно, природа, в небольшой степени и утончённая лирика. Моцарт охватил,
                    пожалуй, все существующие образные сферы.
                </div>
                <div class="era__text">
                    Музыкальная культура классицизма связана с созданием многих жанров инструментальной музыки – таких, как
                    соната, симфония, концерт. Сформировалась многочастная сонатно-симфоническая форма (4-частный цикл), до
                    сих пор являющаяся основой многих инструментальных сочинений. В эпоху классицизма сложились главные типы
                    камерных ансамблей – трио, струнный квартет. Система разработанных венской школой форм актуальна до сих
                    пор – современные «навороты» наслаиваются на неё, как на основу.
                </div>
                <div class="era__text">
                    Музыка классицизма удивительным образом сочетает в себе внешнюю простоту и ясность с глубоким внутренним
                    содержанием, которому не чужды сильные чувства и драматизм. Классицизм, кроме того, является стилем
                    определенной исторической эпохи, причём стиль этот не забыт, а имеет серьёзные связи с музыкой
                    современности (неоклассицизм, полистилистика).
                </div>
            </div>
            <div class="era__info romantizm" v-if="roman">
                <p class="era__title">Эпоха Романтизма</p>
                <div class="era__text">
                    Музыкальный романтизм, ощутимо проявивший себя во втором десятилетии XIX в., был
                    явлением исторически новым и вместе с тем обнаруживал глубокие преемственные связи с музыкальной
                    классикой. Непосредственными предшественниками романтизма были Людвиг Ван Бетховен и Луиджи Керубини;
                    более отдалённым своим предшественником многие романтики (например, Шуберт, Вагнер, Берлиоз) считали
                    К.В. Глюка. Идеи, структура произведений, которые установились или только наметились в их некоторых их
                    сочинениях, были развиты при романтизме.
                </div>
                <div class="era__text">
                    Произведения, относящиеся к романтизму, воспринимаются как более пылкие и эмоционально выразительные.
                    Композиторы-романтики старались с помощью музыкальных средств выразить глубину и богатство внутреннего
                    мира человека. Музыка становится более рельефной, индивидуальной. Получают развитие песенные жанры, в
                    том числе баллада.
                </div>
                <div class="era__text">
                    В качестве основной проблемы романтической музыки выдвигается проблема личности, причем в новом
                    освещении – в ее конфликте с окружающим миром. Романтический герой всегда одинок. Тема одиночества –
                    едва ли не самая популярная во всем романтическом искусстве. Очень часто с ней связана мысль о
                    творческой личности: человек одинок, когда он является именно незаурядной, одаренной личностью. Артист,
                    поэт, музыкант – излюбленные герои в произведениях романтиков
                    С темой «лирической исповеди» очень часто переплетается тема природы. Резонируя с душевным состоянием
                    человека, она обычно окрашивается чувством дисгармонии. С образами природы тесно связано развитие
                    жанрового и лирико-эпического симфонизма (одно из первых сочинений – «большая» симфония C-dur Шуберта).
                </div>
                <div class="era__text">
                    Настоящим открытием композиторов-романтиков стала тема фантастики. Музыка впервые научилась воплощать
                    сказочно-фантастические образы чисто музыкальными средствами. В операх XVII – XVIII веков «неземные»
                    персонажи (как, например, Царица ночи из моцартовской «Волшебной флейты») разговаривали на
                    «общепринятом» музыкальном языке, мало выделяясь на фоне реальных людей. Композиторы-романтики научились
                    передавать фантастический мир как нечто совершенно специфическое (при помощи необычных оркестровых и
                    гармонических красок). Яркий образец – «Сцена в волчьем ущелье» в «Волшебном стрелке» Вебера.
                    В высшей степени характерен для музыкального романтизма интерес к народному творчеству. Подобно
                    поэтам-романтикам, которые за счет фольклора обогаща­ли и обновляли литературный язык, музыканты широко
                    обращались к национальному фольклору – народным песням, балладам, эпосу (Ф. Шуберт, Р. Шуман, Ф. Шопен,
                    И. Брамс, Б. Сметана, Э. Григ и др.). Воплощая образы национальной литературы, истории, родной природы,
                    они опирались на интонации и ритмы национального фольклора, возрождали старинные диатонические лады. Под
                    влиянием фольклора содержание европейской музыки ярко преобразилось.
                </div>
                <div class="era__text">
                    Новые темы и образы потребовали от романтиков разработки новых средств музыкального языка и принципов
                    формообразования, индивидуализа­ции мелодики и внедрения речевых интонаций, расширения тембровой и
                    гармонической палитры музыки (натуральные лады, красочные сопостав­ления мажора и минора, и т. д.).

                    Поскольку в центре внимания романтиков уже не человечество в целом, а конкретный человек с его
                    неповторимым чувствованием, соответственно и в средствах выражения общее все больше уступает место
                    единичному, индивидуально своеобразному. Уменьшается доля обобщенных интонаций в мелодике,
                    общеупотребительных аккордовых последований в гармонии, типовых рисунков в фактуре – все эти средства
                    индивидуализируются. В оркестровке принцип ансамблевых групп уступил место солированию почти всех
                    оркестровых голосов.
                </div>

            </div>
            <div class="era__info XX" v-if="XX">
                <p class="era__title">Музыка 20 века</p>
                <div class="era__text">Музыка в период 1910 - 1960 гг.
                    ХХ век - время, когда технологии изменили мир. Музыка как неотъемлемая часть человеческой жизни также
                    претерпела глобальные изменения. Композиторы опрокинули многие музыкальные правила прошлого и нашли
                    новые, смелые темы и новые способы их выражения.</div>
                <div class="era__text">Одной из значительных фигур, изменивших музыку в первой половине столетия, был
                    Арнольд Шёнберг - австрийский, затем американский композитор, дирижёр, музыковед. Возглавляемая им
                    группа музыкантов решила, что тональная музыка (логическое построение соразмерных аккордов) исчерпала
                    себя, и они предложили так называемую атональную музыку и 12-тоновой систему композиции (известную как
                    "додекафония" или "серийная техника"). Такая музыка перестала быть мелодичной и гармоничной, не все
                    композиторы восприняли их идеи.
                    Сергей Рахманинов продолжал сочинять в своем собственном богатом, романтическом стиле. Другие
                    композиторы, например Ян Сибелиус, чувствовали себя отставшими от времени и просто прекратили сочинять
                    музыку.
                    Успешными стали те композиторы, которые сумели найти золотую середину. Рихард Штраус начинал в 1890-ых в
                    романтическом стиле, но стал одним из первых крупных композиторов, перешедших к модернизму. Игорь
                    Стравинский, один из самых успешных композиторов двадцатого века, потрясал и восхищал зрителей на
                    протяжении всей своей 70-летней карьеры своими неистовыми "механическими" ритмами и новым типом
                    гармонии.</div>
                <div class="era__text">Как никогда прежде, огромное влияние на музыку оказали политические события первой
                    половины XX века. Войны, революции, социальные и экономические потрясения встряхнули мир в прошлом веке.
                    Многие композиторы и исполнители были отправлены в нацистские концентрационные лагеря из-за своих
                    убеждений, вероисповедания или национальности, было много ограничений и запретов на музыку, которая
                    создавалась.
                    Многие, спасаясь от сложившихся обстоятельств, вынуждены были иммигрировать со своей родины и искать
                    себя в других странах.
                    Многие не смогли показать весь свой потенциал, например Дмитрий Дмитриевич Шостакович - русский
                    советский композитор, пианист, педагог и общественный деятель, крупнейший композитор XX века, оказавший
                    огромное влияние на развитие мировой музыкальной культуры, который несмотря на все свои заслуги, имел
                    очень сложные отношения с властью и вынужден был писать в двух стилях - симфонии для власти и более
                    мелкие работы, такие, как струнные квартеты, в которых проявлял собственные взгляды и стиль.
                    Многие композиторы в поисках вдохновения снова и снова обращаются к народной музыке. Бела Барток,
                    венгерский композитор, изучал крестьянский фольклор (венгерский, румынский, словацкий, турецкий и др.) и
                    соединил фольклорный мелос с приёмами музыкального авангарда, став одним из наиболее глубоких и
                    влиятельных новаторов в музыке XX века. Американские композиторы начали привлекать свою собственную
                    родную музыку - джаз, ведущими композиторами в этом направлении были Джордж Гершвин и Дюк Эллингтон.

                    Вторая мировая война, Холокост, Хиросима убедили многих послевоенных композиторов, что они должны были
                    оставить прошлое позади и находить все более прогрессивные методы и идеи. Модернизм в музыке был в том,
                    что впервые музыканты и слушатели поняли, что музыка не должна быть ограничена традиционными
                    направлениями, а может быть совершенно различной, и каждая имеет право на существование.</div>
            </div>
        </div>
    </div>
</template>


<script>
import Navbar from '@/components/Navbar'
import recognize from '@/components/recognize.vue';
export default {
    components: {
        Navbar,
        recognize
    },
    data() {
        return {
            vozrozdenie: false,
            barroko: false,
            class: false,
            roman: false,
            XX: false,
        }
    },
    methods: {
        vozr() {
            this.vozrozdenie = true
            this.barroko = false
            this.XX = false
            this.roman = false
            this.class = false
        },
        barr() {
            this.vozrozdenie = false
            this.barroko = true
            this.XX = false
            this.roman = false
            this.class = false
        },
        classic() {
            this.vozrozdenie = false
            this.barroko = false
            this.XX = false
            this.roman = false
            this.class = true
        },
        romantizm() {
            this.vozrozdenie = false
            this.barroko = false
            this.XX = false
            this.roman = true
            this.class = false
        },
        XX_age() {
            this.vozrozdenie = false
            this.barroko = false
            this.XX = true
            this.roman = false
            this.class = false
        },
    },

}
</script>

<style scoped >
.container__hist {
    width: 100%;
    max-width: 1200px;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
    color: #fff;
    padding: 0 10px;
    margin-top: 70px;
}

.title__hist {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    line-height: 56px;
}

.line {
    width: 100%;
    height: 1px;
    background-color: black;
    margin-top: 10px;
}

.era__list {
    width: 100%;
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
}

.era__list-item {
    width: 210px;
    height: 280px;
    position: relative;
    border-radius: 10px;
}

.item__text {
    border-radius: 30px;
    position: absolute;
    top: 0;
    text-align: center;
    background-color: #fff;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 56px;
    opacity: 0;
}

.item__text:hover {
    opacity: 0.6;
    transition: all .3s;

}

.images {
    width: 210px;
    min-height: 280px;
    object-fit: cover;
    border-radius: 30px;
}

.era__info {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 47px;
    align-items: center;
    text-indent: 30px;
    text-align: justify;
    margin-top: 50px;

}

.era__title {
    font-style: normal;
    font-weight: 700;
    font-size: 48px;
    line-height: 58px;
    text-align: center;
    margin-bottom: 20px;

}

.era__text::first-letter {
    color: #F9D209;
    font-weight: 700;
    font-size: 30px;
}</style>
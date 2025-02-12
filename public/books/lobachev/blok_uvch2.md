# БЛОК УВЧ


Блок УВЧ предназначен для усиления принятых антенной отраженных сигналов высокой частоты.

В состав блока входят:
 		- выпрямитель +400 В;
 		- выпрямитель накала;
 		- лампа бегущей волны (ЛБВ).
 
Принципиальная схема блока УВЧ приведена в альбоме схем.
В блоке УВЧ применена пакетированная ЛБВ типа УВ-75Б. 
 
Принцип работы ЛБВ заключается в следующем. Под воздействием СВЧ колебаний, подаваемых на вход ЛБВ и распространяющихся вдоль замедляющей системы, происходит группировка электронов в сгустки. Скорость электронных сгустков о несколько больше фазовой скорости ф  гармоник сигнала, поэтому сгустки движутся в тормозящем поле бегущей волны. В результате этого амплитуда высокочастотных колебаний  увеличивается. В конце замедляющей системы амплитуда высокочастотных колебаний оказывается значительно больше амплитуды колебаний, подаваемых на вход ЛБВ. 

Подача напряжений на электроды ЛБВ происходит только после подачи на нее напряжения накала и прогрева ЛБВ в течение 2…4 мин.

Напряжение с выхода выпрямителя накала, собранного на модуле УЗ, поступает на обмотку реле Р6, при этом замыкаются контакты 3-5 реле Р6 и напряжение +27 В с контакта 0с разъема Ш2 поступает на обмотки реле Р3 и Р4. Термореле Р3 срабатывает через 2…4 мин., после срабатывания реле Р6, обеспечивая тем самым задержку подачи питающих напряжений на электроды ЛБВ на время прогрева лампы. Через контакты 3-4 реле Р3 замыкается  цепь запитки реле Р2. Реле Р2 срабатывает, если данный приемник используется в качестве основного путем подачи напряжения +27 В на контакт 0а разъема Ш2 в виде команды «+27 В КОМ». После срабатывания реле Р2 напряжение сети 220 В 400 Гц подается на выпрямитель 400 В, выполненный на модуле У2 (контакты 2, 3 разъема модуля). После срабатывания реле Р4 замыкается цепь сигнала «Сеть». Сигнализация выведена на лицевую панель блока УВЧ (лампочка СЕТЬ). Диоды Д2 и Д3 служат для развязки цепей запитки реле Р2 и Р4.

В случае необходимости включения блока УВЧ без задержки на 2…4 минуты имеется возможность блокировки реле времени Р3 нажатием кнопки Кн2, при этом срабатывают реле Р2 и Р4, обеспечивая подачу питающего напряжения на выпрямитель 400 В и замыкание цепи сигнала «Сеть».

На лицевую панель блока выведены два волновода, к которым присоединены вход и выход ЛБВ (рис.4.3). Кроме того, на лицевой панели расположены измерительные приборы, предохранители, сигнальные лампы, контрольные гнезда и резисторы для регулировки питающих напряжений.

Достоинства УВЧ на ЛБВ:
 		- УВЧ является широкополосным, поэтому не требуется его перестройки при переходе с одного частотного канала на другой;
	 	- большой динамический диапазон входных сигналов (60…90 дБ);
	 	- УВЧ может выполнять роль автоматической регулировки усиления (АРУ);
	 	- приемное устройство, построенное с использованием УВЧ на ЛБВ, способно длительно выдерживать большие входные мощности при малом времени восстановления после воздействия сигнала, что позволяет обеспечить защиту кристаллических диодов смесителя приемника от «выгорания» за счет воздействия сигнала передатчика, просачивающегося через антенный переключатель.

К существенным недостаткам ЛБВ можно отнести:
 	- низкую стабильность фазовой характеристики ЛБВ, что  нежелательно для режима СДЦ;
 	- относительно высокий коэффициент шума 3…7 дБ;
 	- громоздкость конструкции УВЧ и  необходимость стабильного источника питания.



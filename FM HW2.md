# 1.

1. **Контекст**: 

> Israeli Prime Minister Ariel Sharon has said that Mahmoud Abbas is a man that Israel can do business with.

**Гипотеза**: 

> Israeli chief executive Ariel Sharon has said that Mahmoud Abbas is a man that the country can do business with.

**Лейбл отношения**: entailment

**Лингвистическая аннотация**: Алгоритм не имеет знаний о том, что премьер-министр Израиля является главой исполнительной власти (chief executive). Кроме этого, возможную сложность может представлять референция Israeli-the country.



2. **Контекст**: 

> The presidents of Ecuador and Peru say they have agreed to work together to try to find a peaceful solution to their long-running border dispute. 

**Гипотеза**: 

> Ecuador and Peru heads of state have resolved a conflict without resorting to violence.

**Лейбл отношения**: contradiction

**Лингвистическая аннотация**: Возможно, пресуппозиция "согласились работать вместе, чтобы попытаться найти решение" не равно "разрешили конфликт" запутает алгоритм. Также возможны лексические трудности (*peaceful solution* - *without resorting to violence*), которые, хоть и синонимичны, но не приравнивают семантически два предложения.



3. **Контекст**: 

> This will be a major incentive to universities and teaching and research hospitals across Canada to not only take advantage of the foundation for innovation and its assistance in upgrading and building research infrastructure but also to make use of the $400 million that has been made available to the university research granting councils to further support the performance of international quality research in this country. 

**Гипотеза**: 

> $400 million has been made available to carry out medical research in Canada.

**Лейбл отношения**: entailment

**Лингвистическая аннотация**: Модель предсказывает отношение neutral. Вероятно, причина в слове *medical*. В конце предлагаемого контекста речь идет просто про исследования, однако, благодаря тому, что в начале упоминаются больницы, мы понимаем, что имеются в виду именно медицинские исследования. Модель не имеет доступа к этой пресуппозиции.



4. **Контекст**: 

> Last Saturday I was thrilled to read about a school in Co Antrim which has introduced the study of philosophy for students of four years of age and upwards. According to both teachers and parents, the benefits are felt far beyond the classroom, "not just in terms of increased confidence, motivation and ability, but in a heightened respect for the differing views of others". In 1999, I walked through the gates of Trinity College to enrol as an undergraduate in the philosophy department. I had just returned home from years living in another city; I was recently married, unemployed and had been diagnosed with a mental illness I didn't quite believe I had. I wasn't sure if I could cope.

**Гипотеза**: 

> I was excited about studying philosophy when I read about it.

**Лейбл отношения**: neutral

**Лингвистическая аннотация**: Логическое рассуждение (reasoning) в гипотезе нарушено, поэтому отношение neutral. Однако модель может предсказать entailment, потому что в начале контекста упоминается изучение философии, однако не автором текста, а детьми.



# 2.

1. **Context**: 

   >  Знать, где упасть, соломки постлать. Нет, непонятно. Но с другой стороны ― что я об этом знаю? И почему я **должен** **чувствовать** себя виноватым?

   **Target**: И почему я должен чувствовать себя виноватым? 
   **Verb**: чувствовать
   **Оператор, отменяющий следствие**:  вопрос, модальный глагол
   **Источник**: [НКРЯ](https://processing.ruscorpora.ru/search.xml?docid=bWFpbi9zdGFuZGFyZC9wb3N0MTk1MC9maWN0aW9uL2NvcnAyL3ZvbG9zL3JlYWx0eS54bWw%3D&dpp=10&expand=full&format=html&g=i_doc&kwsz=5&lang=ru&mode=main&nodia=1&out=normal&req=%D0%B4%D0%BE%D0%BB%D0%B6%D0%B5%D0%BD+%D1%87%D1%83%D0%B2%D1%81%D1%82%D0%B2%D0%BE%D0%B2%D0%B0%D1%82%D1%8C&sampling=1&sid=9304&sort=i_grtagging&spd=10&spp=50&sr=1&text=lexform)
   **Оценка комитмента**: -3/говорящий уверен, что комплемент ложен
   **Комментарий**: спикер использует вопросительное предложение и модальный глагол с высокой степенью коммитмента (*должен*), чтобы выразить отсутствие комитмента в комплементе.

2. **Context**: 

   > От всей души желаю Вам найти подходящую работу, ведь «учителем сначала нужно родиться, а потом уже стать».
   >
   > Я так **не** **думаю**.

   **Target**: *я так не думаю*
   **Verb**: *думаю*
   **Оператор, отменяющий следствие**:  отрицание (*не думаю*)
   **Источник**: [НКРЯ](https://processing.ruscorpora.ru/search.xml?docid=bWFpbi9zdGFuZGFyZC9wb3N0MTk1MC9mb3J1bS9lbGVjdHJvY29tL2J5bGlfbGlfdl9zdHJhbmVfZGlzYW1iLnhtbA%3D%3D&dpp=5&format=html&g=i_doc&kwsz=5&lang=ru&mode=main&nodia=1&out=normal&req=%D0%BD%D0%B5+%D0%B4%D1%83%D0%BC%D0%B0%D1%8E&sampling=1&sort=i_grtagging&spd=10&spp=50&sr=1&text=lexform)
   **Оценка комитмента**: -3/говорящий уверен, что комплемент ложен
   **Комментарий**: говорящий напрямую отрицает предикат, используя отрицательную частицу *не* и соотносит ее с комплементом *так*. 

3. **Context**: 

   >  Словом, Аркадий, при первом появлении, не сделал на меня никакого сильного впечатления: я видел перед собою обыкновенного молодого человека, обыкновенно одетого, и если бы кто-нибудь не сказал мне: «вот художник», ― я ничего не **подозревал** **бы** в этом правильном, приятном лице, в этой простой улыбке, этом обыкновенном наряде.

   **Target**: *я ничего не подозревал бы*
   **Verb**: *подозревал*
   **Оператор, отменяющий следствие**:  условный оператор (*бы*), отрицание (*ничего не*)
   **Источник**: [НКРЯ](https://processing.ruscorpora.ru/search.xml?docid=bWFpbi9zb3VyY2UvcHJlMTk1MC94aXgvcG9sZXZvai9wb2xldm95X2dpdm9waXNlYy54bWw%3D&dpp=5&format=html&g=i_doc&kwsz=5&lang=ru&mode=main&nodia=1&out=normal&req=%D0%BF%D0%BE%D0%B4%D0%BE%D0%B7%D1%80%D0%B5%D0%B2%D0%B0%D0%BB+%D0%B1%D1%8B&sampling=1&sort=i_grtagging&spd=10&spp=50&sr=1&text=lexform)
   **Оценка комитмента**: -3/говорящий уверен, что комплемент ложен
   **Комментарий**: интересная ситуация, когда два отменяющих следствие опервтора не отменяют друг друга, а дополняют, усиливая коммитмент говорящего.

4. **Context**: 

   >   По-моему, следует заняться этой Наталией. **Она** **может** **знать** что-то.

   **Target**: *она может знать*
   **Verb**:  *знать*
   **Оператор, отменяющий следствие**: модальный глагол *может* 
   **Источник**: [НКРЯ](https://processing.ruscorpora.ru/search.xml?docid=bWFpbi9zb3VyY2UvcG9zdDE5NTAvemh1cl9ydXNzcnUvenZlemRhL3Ryb2ZpbW92YS90cm9mLnhtbA%3D%3D&dpp=5&format=html&g=i_doc&kwsz=5&lang=ru&mode=main&nodia=1&out=normal&req=%D0%BE%D0%BD%D0%B0+%D0%BC%D0%BE%D0%B6%D0%B5%D1%82+%D0%B7%D0%BD%D0%B0%D1%82%D1%8C&sampling=1&sort=i_grtagging&spd=10&spp=50&sr=1&text=lexform)
   **Оценка комитмента**: 0/говорящий не уверен, что комплемент истинен или ложен
   **Комментарий**: модальный глагол показывает на вероятное состояние Наталии, поэтому говорящий не уверен, следовательно, предполагаем нулевой коммитмент.



# 3.

Пространство отношений, разбитое на **две части (entailment и non-entailment)** не кажется мне достаточно исчерпывающей. При такой бинарной классификации не исключена двусмысленность интерпретации:

| Premise             | Relation       | Hypothesis             |
| ------------------- | -------------- | ---------------------- |
| All mammals danced. | entailment     | All elephants danced.  |
| All mammals danced. | non-entailment | Some elephants danced. |
| All mammals danced. | non-entailment | Crocodiles danced.     |

Вторая гипотеза не является строгим противоречием, так как не отрицает посылку, а является как бы ее частью. На мой взгляд, при подобной классификации точность разделения отношений не будет достаточно высокой.

Классификация, разделяющая пространство отношений на **четыре части (equivalence, forward, reverse, non-entailment)**, требует от аннотатора (или от модели) много дополнительных логических операций, а также общих знаний о мире.

| Premise | Relation       | Hypothesis |
| ------- | -------------- | ---------- |
| couch   | equivalence    | sofa       |
| crow    | forward        | bird       |
| bird    | reverse        | crow       |
| hippo   | non-entailment | hungry     |
| hippo   | non-entailment | linguist   |

Если разметка отношений производится моделью, то в этом случае она должна обладать знаниями о том, что ворона -- это птица, и что класс птиц шире класса ворон, а также модель не должна приравнять бегемота и лингвиста на основе того, что оба они, например, млекопитающие или просто живые существа. Таким образом, для модели, разделяющей отношения на четыре части, необходимы широкие общие знания о мире, а также широкий контекст для точного определения отношений. Кроме того, hippo и hungry, с моей точки зрения, не являются строгим противоречием, а скорее нейтральным отношением, так как принадлежат к разным частям речи и могут сочетаться в определенном контексте, что вряд ли можно отметить о паре hippo-linguist.

Пресуппозициональные отношения и конверсациональные импликатуры могут дополнить знания модели о мире и расширить контекст, что, возможно, сделает модель более эффективной в определении отношений включения и обратного включения.

Таким образом, разделение отношений на **три части (entailmet, non-entailmet, contradiction)** является наиболее точной и исчерпывающей классификацией. Она учитывает как общее следствие (которое, например, может включать в себя полную тождественность, включение и обратное включение), так и нейтральные отношения (когда никакая связь между двумя утверждениями не устанавливается) и противоречие (когда два утверждения исключают друг друга).



# 4.

Вместо семи лейблов я бы предложила структуру покороче. На мой взгляд, аннотаторам проще было бы оценивать, исходя из следующей шкалы:

-2 *certainly false*

-1 *possibly false*

0 *neutral*

+1 *possibly true*

+2 *certainly true*

Граница между *possibly* и *probably*, предложенными в шкале Commitment Bank, довольно размыта и субъективна. Уменьшение количества лейблов, возможно, приведет к уменьшению разногласий между аннотаторами и, следовательно, к более объективной и четкой оценке. Пример из Commitment Bank: 

> ```
> He was engaging in a war of nerves with her, Isabel realised at last, but he didn't remember. She stared back at him, unable to speak, terrified of betraying the slightest clue that might jolt his memory, but conscious of a heartfelt sense of gratitude for the fever that had kept her so busy during the morning hours.
> ```

Пример был размечен девятью аннотаторами. Из них двое дали оценку 2 и двое дали оценку 1, остальные -- 0. Это размывает статистику и придает ненужный больший вес коммитмента, когда мы точно видим, что большинство аннонаторов сошлись на нейтральном и слабоотрицательном коммитменте. 

Оценивать лучше только коммитмент говорящего, на мой взгляд. Например, 

> Я уверена, что Маша догадывается, что сейчас идет дождь. 

В этом предложении коммитмент говорящего не равен коммитменту субъекта пропозиционального глагола. Если наша цель -- оценивать коммитмент высказывания в целом, то лучше ориентироваться только на говорящего, а не на ситуацию им описываемую, ведь нам интересно, насколько уверен человек в том, что он говорит, а не в реальности описываемой ситуации.



# 5.

ВАРИАНТ 2

а) The Commitment Bank использует следующую [разметку](https://github.com/mcdm/CommitmentBank): 

- Target: sentence of interest, containing a clause-embedding predicate under an entailment canceling operator
- Context: preceding context of the target sentence (up to 2 sentences/turns) - **стоит взять не только предшествующие, но и одно последующее предложение. Например, "...я почти был уверен, что она мне солгала. Но через два дня я убедился в обратном" -- здесь последующее предложение разворачивает коммитмент автора в противоположную сторону.**
- Prompt: prompt used in the experiment to gather projection judgments
- Verb: clause-embedding predicate
- Embedding: type of entailment canceling operator - **можно не указывать отменяющий следствие оператор, потому что он не обязательно может присутствовать в предложении с отсутствующим следствием. См. пример из пункта context - "убедился в обратном".**
- factive: whether the verb is canonically considered factive or not
- ModalType: for modal embedding, type of modal (AB: ability, CI: circumstancial, DE: deontic, EP: epistemic)
- MatTense: tense of the matrix verb
- MatSubjLemma: lemma of the matrix verb subject
- MatSubjPer: person of the matrix verb subject
- MatSubjNum: number of the matrix verb subject
- genre: corpus from which the item has been extracted - **здесь можно добавить не только название корпуса, но и жанр высказывания, чтобы можно было проанализировать, как выражается коммитмент в разных жанрах**
- Answer/Responses: projection judgments to the prompt, using a 7-point Likert scale (-3/the author is certain that the prompt is false, 0/the author is not certain whether the prompt is true or false, 3/the author is certain that the prompt is true)
- mean.noTarget: mean of responses to the "plausibility of the content of the complement given context" (see Section 2.6 in the paper)
- sd.noTarget: standard deviation of responses to the "plausibility of the content of the complement given context" (see Section 2.6 in the paper)

б) 

*Я знаю, что завтра пойдет снег.*

*Я понимаю, что завтра пойдет снег.*

*Я надеюсь, что завтра пойдет снег.*

*Я чувствую, что завтра пойдет снег.*

*Я подозреваю, что завтра пойдет снег.*

*Я воображаю, что завтра пойдет снег.*

Выше приведены примеры, в которых коммитмент предиката по моей субъективной оценке снижается от максимального к минимальному. В статье приводился анализ роли предикатов, и был сделан вывод о том, что фактивность глагола влияет на оценку коммитмента (например, глаголы *understand, notice, learn, forget* имеют наивысшую оценку коммитмента). На мой взгляд, в русском языка ситуация аналогичная: фактивные глаголы *знать, понимать* выражают гораздо большую уверенность говорящего, чем нефактивные *подозревать, воображать*. Интересно отметить предикат *думать, что*: хоть этот глагол и относится к т.н. глаголам знания, его нельзя назвать фактивным, ведь он не выражает твердой уверенности говорящего. 

*Я **думаю, что** завтра пойдет снег* != *Я **знаю**, что завтра пойдет снег*


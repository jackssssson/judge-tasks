Учениците от група D на националната школа по информатика обичат да играят на следтана игра: „играта на Йосиф”. В класическия вид на играта учениците се нареждат в кръг и започвайки от случайно избран ученик, получават последователни номера от **1** до **N** в посока на часовниковата стрелка. Така след ученика с номер **N** по посока на часовниковата стрелка ще се окаже ученика с номер **1**. Ръководителката на групата избра положително цяло число **K**. Започвайки от ученика с номер **1** и вървейки по кръга в посока на часовниковата стрелка, учителката преброява **K** ученика и този, който се окаже **K-ти** подред, напуска кръга. Играта продължава с ново броене до **K**, което започва от ученика, който е първи по посока на часовниковата стрелка, след току-що напусналия. Ученикът, който е **K-ти** подред при новото броене напуска кръга и т.н., докато остане само един ученик, който е победител. В новия вариaнт на играта всеки ученик си избира число **Ki**. Първото броене става с избраното от учителката число **K**. Следващото броене става с числото на току-що напусналия играта ученик. Напишете програма **ring**, която да намери номера на ученика, който ще спечели играта при така модифицираните правила.


# Вход 
На първия ред на стандартния вход ще бъдат зададени числата **N** и **K** (**N ≤ 1000000,2 < K ≤ 100**), разделени с интервал. На i-тия от следващите N реда ще бъде зададено число **Ki**, избрано от ученика с номер **i** (**2 < Ki < 100**).

# Изход
На единствения ред на стандартния изход програмата трябва да изведе номера на ученика, който ще остане последен и ще спечели играта.

# Примерни тестове 
## Вход
```
5 3 
3
7
4
3
5
```
## Изход
``` 
1
```

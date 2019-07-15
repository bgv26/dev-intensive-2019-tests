# HomeTask_3: тесты на задания "Dev Intensive 2019" от Skill Branch

<b>ВНИМАНИЕ!</b> тесты нужно засунуть в дирректорию с <b>ANDROID</b> тестами (androidTests)

<b>ВНИМАНИЕ!</b> Не копируйте к себе мой build.gradle! Необходимо добавить в свой зависимость в dependencies:
Над на блоком dependencies в строчке `testInstrumentationRunner` раннер может начинаться с `android.support.test`, либо `androidx.test`. </br>Если у вас `android.support.test`, то в dependencies добавляем: </br>
>  ` androidTestImplementation 'com.android.support.test:rules:1.0.2' ` 

а если `androidx.test`, то </br>
>  ` androidTestImplementation 'androidx.test:rules:1.2.0' `
</br> `androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0'` </br>
> `androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0'`

<b>ВНИМАНИЕ!</b> если у вас runner androidx, то после добавления всех зависимостей, нужно будет удалить конфликтующий импорт в классах тестов и добавить свой (через Alt+Enter) из пакета androidx.</br>
</br></br>
* Здесь лежат тесты уже для всех заданий.
* Для вашего удобства тесты разбиты по названию в соответствии с нумерацией заданий.
* Методы, на которые составлены тесты, <b>успешно</b> прошли проверку ботом. Если проверка ещё не пройдена - тест будет в конце этого описания в списке <b>"Непроверенные методы"</b>.
* Так как функционал классов и методов от урока к уроку может отличаться, каждый этап будет в отдельной ветке.
* Ветки нумеруются согласно рабочим веткам. Т.е. hometask_3 в вашем репозитории == hometask_3_tests этого репозитория.
* Тесты можно и нужно дополнять, если хотите - можете форкаться, можете писать в телеграмме (@Igatroll), а можете просто пользоваться.
  
  
> Непроверенные методы:
* --отсутствуют--

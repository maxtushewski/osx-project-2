Проект 2. Идея и интерфейс приложения SportTimer
=============

Проблема
========
Люди занимающиеся спортом дома испытывают нехватку в удобном таймере для тренировок. Таймер должен отмерять интервалы для выполнения упражнения и для отдыха между подходами. С использованием таймера не нужно будет отвлекаться, для учета повторов.

Аудитория
=========
Аудиторию приложения составляют люди занимающиеся спортом дома. 

Пример сценария использования приложения
=======================================
Пользователь выставляет количество подходов, интервал выполнения упражнения, и интервал отдыха между подходами с помощью текстовых полей. Нажимает кнопку «Старт», слышит звуковой сигнал, и приступает к выполнению упражнения. Упражнение выполняется до второго звукового сигнала, поле него пользователь останавливается, и начинает отдыхать, до следующего сигнала. Данное действие происходит пока не будут выполнены все подходы. После отсчета последнего рабочего интервала программа издает двойной звуковой сигнал, что означает конец цикла.

Описание поведения
==================
После нажатия на кнопку «Старт», кнопка становится не активной, звучит звуковой сигнал, счетчик секунд в поле «Интервал работы» начинает уменьшаться каждую секунду на единицу, пока не станет равным нулю, после чего поле вернется к своему исходному значению, прозвучит звуковой сигнал, и начнет уменьшатся время в поле «Интервал отдыха», затем когда один цикл пройдет поле «Количество подходов» снизится на единицу. Как только «Количество подходов» станет равно нулю, прозвучит двойной сигнал, кнопка станет активной, значения всех полей вернутся к исходным.

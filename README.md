<table>
	<tr><th>Идентификатор</th>	<th>Название тест-кейса</th>							<th>Шаги</th>						<th>Ожидаемый результат</th>		<th>Комментарий</th></tr> <!--ряд с ячейками заголовков-->
	<tr><td>1.</td>				<td>Ввод отрицательного значения на счетчике СО2</td>	<td>С бэка подать значение "-1"</td><td>Должен отобразить 0 или ошибка</td>		<td>Уточнить в ТЗ или у бэка о наличии ошибки при передаче отрицательного значения</td></tr> 
	<tr><td>2.</td>				<td>Ввод нулевого значения на счетчике СО2</td>			<td>С бэка подать значение "0"</td>	<td>Должен отобразить 0</td>		<td></td></tr> 
	<tr><td>3.</td>				<td>Ввод значения равного 99,01 кг на счетчике СО2</td>	<td>С бэка подать значение "99,01"</td>	<td>Должен отобразить 99,01 кг</td><td>Уточнить у аналитика как отображается должно: центнер или кг. Есть ли такая величина? Сколько знаков после запятой должно отображаться?</td></tr> 
	<tr><td>4.</td>				<td>Ввод значения равного 101 кг на счетчике СО2</td>	<td>С бэка подать значение "101"</td>	<td>Должен отобразить 1,01 ц</td><td>Уточнить у аналитика должно быть округление?</td></tr> 	
	<tr><td>5.</td>				<td>Ввод значения равного 999 кг на счетчике СО2</td>	<td>С бэка подать значение "999"</td>	<td>Должен отобразить 0,999 т</td><td>Уточнить у аналитика какая величина должна быть т или кг или ц.</td></tr> 	
	<tr><td>6.</td>				<td>Ввод значения равного 1000 кг на счетчике СО2</td>	<td>С бэка подать значение "1000"</td>	<td>Должен отобразить 1 т</td><td></td></tr> 	
	<tr><td>7.</td>				<td>Ввод значения равного 1001,01 кг на счетчике СО2</td>	<td>С бэка подать значение "1001,01"</td>	<td>Должен отобразить 1,00101 т</td><td>Уточнить у аналитика должно быть округление? Сколько знаков после запятой?</td></tr> 	
	<tr><td>8.</td>				<td>Ввод значения равного 0 л на счетчике воды</td>	<td>С бэка подать значение "0"</td>	<td>Должен отобразить о л</td><td></td></tr> 	
	<tr><td>9.</td>				<td>Ввод значения равного 0,001 л на счетчике воды</td>	<td>С бэка подать значение "0,001"</td>	<td>Должен отобразить 1 мл</td><td>Уточнить у аналитика какие величины: л, мл, куб.метр?</td></tr> 	
	<tr><td>10.</td>				<td>Ввод отрицательного значения равного на счетчике воды</td>	<td>С бэка подать значение "-1"</td>	<td>Должен отобразить 0 или ошибка</td><td>Уточнить в ТЗ или у бэка о наличии ошибки при передаче отрицательного значения</td></tr> 	
	<tr><td>11.</td>			<td>Ввод значения равного 999 л на счетчике воды</td>	<td>С бэка подать значение "999"</td>	<td>Должен отобразить 999 л</td><td>Уточнить у аналитика: 999 л или 0,999 куб.метр?</td></tr> 	
	<tr><td>12.</td>			<td>Ввод значения равного 1000 л на счетчике воды</td>	<td>С бэка подать значение "1000"</td>	<td>Должен отобразить 1 м3</td><td>Уточнить у аналитика как это должно выглядеть: метр кубический м^3?</td></tr> 	
	<tr><td>13.</td>			<td>Ввод значения равного 0 кВТ*ч на счетчике электричества</td>	<td>С бэка подать значение "0"</td>	<td>Должен отобразить 0 кВт*ч</td><td></td></tr> 	
	<tr><td>14.</td>			<td>Ввод отрицательного значения равного на счетчике электричества</td>	<td>С бэка подать значение "-1"</td>	<td>Должен отобразить 0 кВт*ч или ошибка</td><td>Уточнить у аналитика</td></tr> 	
	<tr><td>15.</td>			<td>Ввод значения равного 999 кВт*ч на счетчике электричества</td>	<td>С бэка подать значение "999"</td>	<td>Должен отобразить 999 кВт*ч</td><td>Уточнить у аналитика</td></tr> 	
	<tr><td>16.</td>			<td>Ввод значения равного 1000 кВт*ч л на счетчике электричества</td>	<td>С бэка подать значение "1000"</td>	<td>Должен отобразить 1 мВт*ч</td><td>Уточнить у аналитика какая единица измерения дб</td></tr> 	
	<tr><td>17.</td>				<td>Ввод значения равного 0,001 кВт*ч на счетчике электричества</td>	<td>С бэка подать значение "0,001"</td>	<td>Должен отобразить 1 Вт*ч</td><td>Уточнить у аналитика</td></tr> 	
	<tr><td>18.</td>				<td>Ввод значения равного 9223372036854775808 кг на счетчике СО2</td>	<td>С бэка подать значение "9223372036854775808"</td>	<td>Должна отобразиться ошибка</td><td>Число превышает 2^64</td></tr> 
	<tr><td>19.</td>				<td>Ввод текстового значения на счетчике СО2</td>	<td>С бэка подать значение "Тестовое слово"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>20.</td>				<td>Ввод символьного значения на счетчике СО2</td>	<td>С бэка подать значение "=)"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>21.</td>				<td>Ввод пустого на счетчике СО2</td>	<td>С бэка подать значение ""</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>22.</td>				<td>Ввод значения равного 9223372036854775808 кг на счетчике воды</td>	<td>С бэка подать значение "9223372036854775808"</td>	<td>Должна отобразиться ошибка</td><td>Число превышает 2^64</td></tr> 
	<tr><td>23.</td>				<td>Ввод текстового значения на счетчике воды</td>	<td>С бэка подать значение "Тестовое слово"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>24.</td>				<td>Ввод символьного значения на счетчике воды</td>	<td>С бэка подать значение "=)"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>25.</td>				<td>Ввод пустого на счетчике воды</td>	<td>С бэка подать значение ""</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>26.</td>				<td>Ввод значения равного 9223372036854775808 кг на счетчике электричества</td>	<td>С бэка подать значение "9223372036854775808"</td>	<td>Должна отобразиться ошибка</td><td>Число превышает 2^64</td></tr> 
	<tr><td>27.</td>				<td>Ввод текстового значения на счетчике электричества</td>	<td>С бэка подать значение "Тестовое слово"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>28.</td>				<td>Ввод символьного значения на счетчике электричества</td>	<td>С бэка подать значение "=)"</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>29.</td>				<td>Ввод пустого на счетчике электричества</td>	<td>С бэка подать значение ""</td>	<td>Должна отобразиться ошибка</td><td></td></tr> 
	<tr><td>30.</td>				<td>Ввод 0,001 кг на счетчике СО2</td>	<td>С бэка подать значение "0,001"</td><td>Должен отобразить 1 гр</td>		<td>Уточнить у аналитика гр или кг?</td></tr> 
	<!--ряд с ячейками тела таблицы-->
</table>

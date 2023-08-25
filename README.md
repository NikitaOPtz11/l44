<div id="parent">
	<div id="calendar">
		<div class="info">Jan 2020</div>
		<table>
			<thead>
				<tr>
					<th>Mon</th>
					<th>Tue</th>
					<th>Wed</th>
					<th>Thu</th>
					<th>Fri</th>
					<th>Sat</th>
					<th>Sun</th>
				</tr>
			</thead>
			<tbody class="body"></tbody>
		</table>
	</div>
</div>

#parent {
	text-align: center;
}
#calendar {
	display: inline-block;
}
#calendar td, #calendar th {
	padding: 10px;
	border: 1px solid black;
	text-align: center;
}

#calendar .info {
	text-align: center;
}

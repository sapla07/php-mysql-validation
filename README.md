# php-mysql-validation
validation of  form using PHP and mysql, this form will inform you if you have not fill any of the data in the form wherever it is necessary before  submitting it,  

<html>
    <head>
	    <title> signup page</title>
	</head>
	<body>
	    <table cellspacing="15px"  border="0px" >
		<form  action="signup_destination.php" method="POST" >
		    <tr>
			<td> First Name </td>
			<td><input type="text" name="first_name" /></td>
			</tr>
			<tr>
			<td> Last Name </td>
			<td><input type="text" name="last_name" /></td>
			</tr>
			<tr>
			<td> Email </td>
			<td><input type="text" name="Email" /></td>
			</tr>
			<tr>
			<td> Date of Birth </td>
			            <td><Select name="year" />
						    <option>year</option>
							<option>1995</option>
							<option>1996</option>
							<option>1997</option>
							<option>1998</option>
							<option>1999</option>
						</select>
						    <select name="month" />
							<option>month</option>
							<option>1</option>
							<option>2</option>
							<option>3</option>
							<option>4</option>
							<option>5</option>
							<option>6</option>
							<option>7</option>
							<option>8</option>
							<option>9</option>
							<option>10</option>
							<option>11</option>
							<option>12</option>
						</select>
						    <select name="date" />
							<option>date</option>
							<option>1</option>
							<option>2</option>
							<option>3</option>
							<option>4</option>
							<option>5</option>
							<option>6</option>
							<option>7</option>
							<option>8</option>
							<option>9</option>
							<option>10</option>
							<option>11</option>
							<option>12</option>
							<option>13</option>
							<option>14</option>
							<option>15</option>
							<option>16</option>
							<option>17</option>
							<option>18</option>
							<option>19</option>
							<option>20</option>
							<option>21</option>
							<option>22</option>
							<option>23</option>
							<option>24</option>
							<option>25</option>
							<option>26</option>
							<option>27</option>
							<option>28</option>
							<option>29</option>
							<option>30</option>
							<option>31</option>
					    </select></td>
		        </tr>
				<tr>
				<td> Gender </td>
				   <td><input type="radio" name="gender" value="male">Male
                        <input type="radio" name="gender" value="female">Female</td>
                </tr>
                <tr>
                <td> Password</td>
                  <td><input type="password" name="pass" ></td>
                </tr>
                <tr>
				<td> Retype Password </td>
				<td><input type="password" name="repass" ></td>
				</tr>
				<tr>
				<td><input type="submit"  name="submit" value="submit" ></td>
				</tr>
	</body>
</html>

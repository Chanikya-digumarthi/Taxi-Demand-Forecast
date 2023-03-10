<h1>Taxi Demand Forecast</h1>


<h2>Description</h2>
The goal of this project is to accurately predict the number of taxi bookings for a given time period, such as an hour, a day, or a week. This information can be valuable to taxi companies and drivers, as it can help them optimize their resources and better serve their customers.
<br />

<h2>Data description:</h2>
Dataset contains hourly renting data in the span of two years. Data is randomly divided into train and test set. The total count of cabs booked in each hour covered by the test set, using the information available prior to the booking period is predicted. The train_label dataset is appended to train.csv as ‘Total_booking’ column.

<h2>Descriptions of the columns present in the dataset</h2>
- <b>datetime ->  hourly date +timestamp<br />
- <b>season -> spring, summer, autumn, winter<br />
- <b>holiday -> whether the day is considered a holiday<br />
- <b>workingday -> whether the day is neither a weekend nor holiday<br />
- <b>season -> spring, summer, autumn, winter<br />
- <b>weather -> Clear , Cloudy, Light Rain, Heavy<br />
- <b>temp -> temperature in Celsius<br />
- <b>atemp -> "feels like" temperature in Celsius<br />
- <b>humidity -> relative humidity<br />
- <b>windspeed -> wind speed<br />
- <b>Total_booking -> number of total booking (train_label contains the data)<br />


<h2>Languages and Utilities Used</h2>

- <b>Python 3.0<br />
- <b>Jupyter Notebooks<br />

Examples in Action
------------------

*Shape of the problem equals shape of the solution.*

- BACnet Objects and Trend Logs are heterogeneous data.  Non-SQL MongoDB is designed for such data.
- Clients, Users, Device settings are rectangular data.  SQL (Postgresql) is designed for such data.
- BAS (building automation system) data streams into Kaizen.  AMQP (RabbitMQ) is designed handling streams of data.

*Size Matters.  Performance matters.*

	The BAS data from hundreds of buildings consists of millions of controller objects, 100's of millions 
	of trend log days, and billions of sensor samples.  Kaizen's database (mongoDB), its design (schema), 
	and Intake system are built for large data volumes.

*Simple is better than complex.*

	The Kaizen analytic engines are single-purpose, stand-alone tasks.  By performing only one task, 
	by reading data from only one data collection or data stream, and by generating a single stream of 
	output – these engines remain simple.  They are easy to understand.  Easy to deploy.  Easy to monitor 
	in operation.  It is the combining of these simple tasks that allows Kaizen to perform the complex 
	functions it does.

*Results are Pushed.  Users shouldn't need to Pull information.*

	Kaizen generates reports on a daily, weekly, monthly basis and sends those reports via email to the 
	users that have subscribed to them.

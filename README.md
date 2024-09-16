1.Create the JMeter Collections:
booking.jmx: Create a JMeter test plan that simulates logging in, creating a booking, and searching for a booking with 120,000 users over a 12-hour period.
dmoney.jmx: Create a JMeter test plan that simulates different financial operations (deposits, money transfers, payments) using multiple CSV files and applying boundary value analysis (BVA) for withdrawals.
2.Create and upload the following CSV files:
deposit.csv: Data for 5 agents performing deposits for 10 customers.
sendMoney.csv: Data for 5 customers sending money to 10 other customers.
payment.csv: Data for 5 customers making payments to 2 merchants.
withdraw.csv: Data for the withdrawal amount based on BVA strategy.
3.Perform Load and Stress Tests:
Run the tests for 20 minutes to analyze throughput and ensure the server can handle the load.
If the load test passes, increase the load gradually for the stress test to identify the bottleneck throughput.
4.Generate and Add Reports:
Generate HTML reports for both the load test and stress test.
Add the HTML report folder to .gitignore to avoid committing large files.
List the prerequisites:
1.Apache JMeter installed
Instructions to Run Tests:
1. Open JMeter and load the booking.jmx file.
2. Ensure the restful-booker API server is accessible.
3. Run the test plan for the specified number of users.
4. Repeat the process for the dmoney.jmx test plan.
![Request Summery of dmoney](https://github.com/user-attachments/assets/c4b3b0c2-ace4-4191-b4b2-72b04e584fc4)
![Statistices of Dmoney ](https://github.com/user-attachments/assets/df7d9d99-2afc-489f-973e-2b901fb542cd)
![Stress testing report request summary](https://github.com/user-attachments/assets/decfaf1e-70a4-4614-88e4-d15f7f3a6e7a)
![Stress testing report statistics](https://github.com/user-attachments/assets/6154a32f-5f97-4ecf-a36a-21e566f3a10f)
![Load testing report request summary](https://github.com/user-attachments/assets/079b60bc-42b1-40e6-9c35-f6ceabb7c497)
![Load testing report statistics](https://github.com/user-attachments/assets/659207dc-ed10-48b1-b094-f07a4e66d483)
https://docs.google.com/spreadsheets/d/1kP9yuXioZpx4l33Ty5BpWIx1hDvAT79F/edit?usp=sharing&ouid=109854678976585134033&rtpof=true&sd=true
https://docs.google.com/spreadsheets/d/1gwuLiQNXcvAldwG38ZaKixwugzWU1veV/edit?usp=sharing&ouid=109854678976585134033&rtpof=true&sd=true
or To show all in one folder below link provided :
https://drive.google.com/drive/folders/1plnqFHtQCXjCrozh7u8cWmo04wHh653w?usp=sharing


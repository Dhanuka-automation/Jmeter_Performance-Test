🧘ERL Performance Testing Project

This is a performance testing project done for one of Sri Lanka’s busiest government institutions: ERL (Electronic Revenue License).

The ERL system is designed for internal officers to issue vehicle revenue licenses across Sri Lanka.

Over 1,000+ officers work across 9 districts.

On average, more than 100,000 vehicle licenses are issued daily through this system.

Because of the high transaction volume, the client required performance, load, and endurance testing to ensure system stability and reliability under heavy demand.

This project uses JMeter test plans (.jmx files) designed for each type of test scenario.

🛠️ Technologies Used

Apache JMeter – for load, performance, and endurance testing.

Grafana – for real-time test monitoring and visualization.

InfluxDB – as a time-series database to store performance metrics.

📌 JMeter Features Used

Thread Groups (to simulate concurrent users).

CSV Data Set Config (to manage dynamic test data).

Regular Expression Extractor (to capture dynamic values from responses).

Beanshell PreProcessor (for custom scripting and parameter handling).

Listeners for results visualization and debugging.

Timers and Assertions for realistic testing.

Backend Listener (for integration with InfluxDB & Grafana).

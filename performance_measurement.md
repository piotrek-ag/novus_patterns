Measuring application performance is a multifaceted task that involves various metrics, tools, and methodologies. Below are some common ways to assess the performance of an application, covering both technical and user experience aspects:

### Key Performance Indicators (KPIs)

#### Technical Metrics

1. **Latency**: The time it takes for a system to respond to a request. 
2. **Throughput**: The number of requests handled by the system per unit time.
3. **Resource Utilization**: CPU, memory, disk, and network usage.
4. **Error Rate**: The number of error messages or failed transactions as a percentage of total transactions.
5. **Availability**: Uptime and downtime statistics.

#### User Experience Metrics

1. **Load Time**: Time it takes for the application to load initially.
2. **Time to First Byte (TTFB)**: Time taken to receive the first byte of data.
3. **Time to Interactive**: Time it takes for the application to become fully interactive.
4. **Frame Rate**: Especially important for video games and real-time simulations.
5. **User Satisfaction Surveys**: Sometimes qualitative feedback is just as important.

### Tools

1. **Profiling Tools**: Built into most IDEs and available as standalone applications.
2. **Application Performance Management (APM) Tools**: Such as New Relic, Datadog, or AppDynamics.
3. **Custom Logging**: Instrumenting code to collect custom metrics.
4. **Browser DevTools**: For web applications, tools like Chrome DevTools can be very useful.
5. **Benchmarking Tools**: Like Apache JMeter, Artillery, or custom-made benchmarking scripts.

### Methodologies

1. **Load Testing**: Simulating high traffic loads to measure how the application performs under pressure.
2. **Stress Testing**: Identifying the limits at which the application fails and how it recovers.
3. **End-to-End Testing**: Ensuring the entire process flow of an application is performing as designed.
4. **Real User Monitoring (RUM)**: Collecting data from real users' interactions with the application.
5. **Synthetic Monitoring**: Using bots to simulate user behavior.

### Data Analysis

1. **Average, 95th percentile, 99th percentile**: It's often useful to look at statistical measures to understand the distribution of performance metrics.
2. **Correlation Analysis**: Finding out if any metrics are correlated can help in identifying bottlenecks or issues.

### Continuous Monitoring

1. **Alerts**: Set up alerts for critical issues.
2. **Dashboards**: Use dashboards to monitor real-time metrics.
3. **Regular Audits**: Periodic performance audits can catch issues before they become critical.

Given your background in software engineering and interest in problem-solving, you might find it beneficial to not just use existing tools but also to build custom solutions tailored to the specific needs and nuances of your application. Would you like to dive deeper into any specific area of application performance measurement?
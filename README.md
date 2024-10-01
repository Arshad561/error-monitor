# **Error-Monitor**
**Error-Monitor** is an open-source, fully customizable error monitoring and logging solution. The benefits of this app insights include its capability of tracking, summing and analyzing errors occurring within applications in real-time, hence minimizing any impending downtimes which in turn increases the stability of applications. **Error-Monitor** is compatible with web, mobile, and any type of backend service and provides real-time notification and error analytics.

## **Features**
- **Error logger**: Logs the error with the log level specified
- **Real-time error tracking**: Gather and show errors as soon as possible so that the speed can be given.
- **Error summary and trends**: Errors should be analyzed on the basis of their frequency, regularity and the extent of their consequences.
- **Customizad notifications**: You can receive notifications of the errors via Slack, email or webhooks based on the error priorities.
- **Error context**: Additional log context including but not limited to method name, error stack trace and the content of the request.
- **Error dashboard**: While using the system, the error data can be viewed using an easy to use dashboard.
- **Third party integrations**: Can be integrated with popular error tracing tools such as Grafana, Datadog etc.

## **Getting Started**
### **Prerequisites**
Before using **Error-Monitor**, ensure you have the following softwares installed:
- **Node.js** (version 18 or higher)
- **PostgreSQL** or **MongoDB** for error data storage
- **Redis** (optional but recommended) for queue management

### **Installation**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Arshad561/error-monitor.git
   ```
   
2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**: Create a `.env` file in the root directory of ypur project and configure the below variables:
   - `ERROR_MONITOR_DATABASE_URL`: PostgreSQL or MongoDB database connection string
   - `ERROR_MONITOR_REDIS_URL`: Redis instance connection string
   - `ERROR_MONITOR_PORT`: The port on which you want the error-monitor server to run (defaults to `6000`)

4. **Run database migrations**: If using PostgreSQL, run the migrations to set up the necessary tables:
   ```bash
   npm run migrate
   ```

5. **Start the server**: Start the error-monitor service to begin monitoring errors:
   ```bash
   npm start
   ```

6. **Access the dashboard**: Open your browser and navigate to `http://localhost:4000` to view and configure your error monitor dashboard.

### **Usage**
Generally, integrating **Error-Monitor** into any application is as easy as starting to monitor errors and receive notifications after the program is running.

- **Error Logging**: Tracks errors from your application and report it to the backend of **Error-Monitor**.
- **Notifications**: Learn how to set up the system so it informs you whenever some errors that are of high importance are recorded.
- **Dashboards**: Errors can be seen in terms of details, times they occurred, and how often they reoccur in real-time and then can be sorted by type, platform, or severity level.

## **Notification Integrations**
**Error-Monitor** can handle an unlimited number of notification services, so you don’t miss out the critical errors. You can configure:
- **Email notifications**: It may be formatted to alert the user by email.
- **Slack notifications**: Recieve error reports directly in the Slack channels.
- **Webhook integrations**: Set up personal webhooks for other services.

An individual notification can be configured on the **Settings** page of the dashboard.

## **Roadmap**
Our roadmap includes the following:
- [ ] **Error analytics**: Analyze patterns of mistakes made and learn some of the underlying issues that pertain to them.
- [ ] **Notification integrations**: More coverage for Microsoft Teams, and other communications tools.
- [ ] **Expanded SDKs**: Propose adding support for such languages like Python, Java, Ruby etc.
- [ ] **Dashboard Enhancements**: Increase support for error visualization.

## **Contributing**
We welcome contributions from the community at all times! Here’s how you can contribute:
1. Clone repository through GitHub.
2. Make sure to create a feature branch for this changes.
3. When you have the changes, create a new branch, commit the changes then open pull request and make sure to elaborate on the changes made.

For contribution guidelines, please review the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## **Code of Conduct**
We appreciate togetherness; therefore, we are an equal-opportunity organization. With your participation in this project you are expected to adhere to this projects [Code of Conduct](CODE_OF_CONDUCT.md).

## **License**
This project is licensed under the **MIT License**. See the license terms in the [LICENSE](LICENSE) file.

## **Community**
Join the **Error-Monitor** community:
- **GitHub Issues**: Submit Your Bug or Feature requests.
- **Slack/Discord**: Visit this link to find a constantly updating live chat for the development team and contributors.
- **GitHub Discussions**: Join general discussions about the project and the future of the project.


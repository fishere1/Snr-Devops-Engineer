Application context 
HealthSignal is a public-facing health information platform operated by a UK public health organisation. The application allows members of the public to view health alerts and guidance during public health incidents. Partner organisations also use the platform during outbreaks to monitor trends and publish rapid reports.
The platform has approximately 1 million registered users and experiences predictable daily traffic spikes. During public health incidents, traffic may increase five to ten times with little notice. Availability and reliability during these periods are considered critical.
HealthSignal is implemented as a three-tier web application, consisting of a frontend, an API, and a database. The accompanying AWS infrastructure diagram represents the current production environment. The infrastructure is managed by Terraform and deployed via GitHub Actions workflows.

<img width="452" height="313" alt="snr-devops-architecture" src="https://github.com/user-attachments/assets/5cc40eee-a593-4774-8090-ded682740a1c" />

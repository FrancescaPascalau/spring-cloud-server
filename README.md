# spring-cloud-server

The server enables access to a config repo that contains config files for multiple applications, based on different
environments.

Examples:

- accessing some-app prod config file: http://localhost:8888/some-app/prod
- accessing the main, default, application.yml: http://localhost:8888/application/default
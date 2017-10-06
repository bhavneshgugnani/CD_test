Spring Boot is build around spring framework and works best for conventional uses cases. It seems to be a fast track process for building a microservice from ground zero while delaying customization steps untill needed by supporting convention over configuration. Along with handling the build part of service, it also integrates the shallow deployment environment requirements as part of packaging of service to reduce, if not avoid, environment dependency and requirements. But, this also means integration of deployment behaviour too early in the product’s development lifecycle.  

However, it does not seems to be the best choice for building micro services for a platform. Tying deployment environment dependency too early in the product development lifecycle significantly reduces flexibility in the deployment environment. Each layer from Design to Dev to QA to Prod needs enough open ended configuration for better handling of the service. Spring boot seems to be going in reverse by tying the soft links to deployment environment too early in the lifecycle. 
Also security and vulnerability in the underlying layers have come to be know as the potentially fatal to any established business. Bugs and vulnerabilities like heartbleed can compromise the complete system and the easiest way to handle such issues is to be flexible enough to patch the production environment as quickly as possible with least service interruption. Integrating the deployment parameters in the build system fo product can be too early integration and can cause a nightmare in such cases.

TESTING 1 added
TESTING 2 added
TESTING 3 added
TESTING 4 added
TESTING 5 added
TESTING 6 added
TESTING 7 added






# CommunicationOfTwoMicroServiceBoot_v1
version 1.00 . it's just communication of microservices. this is step 1

Micro Services With Boot

	Step 1 : create separate one rest api with port 9001 (i.e user microservice)
	Step 2: create separate one other rest api with port 9002 (i.e contact microservice)
	Step 3 : now for communication of both the service we need of RestTemplate
	so first of all declare the RestTemplate as bean in main file, so we can Autowired the our RestTemplate in user service
	using the RestTemplate we can communicate the both microservices

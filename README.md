Git_Base_Project
Installations nécéssaires : yarn

Importer le projet sur eclipse : 
	- import
	- maven existing projects

1. Lancer le jhipster-registry : cd jhipster-registry && yarn install && ./mvnw
2. 	Lancer le gateway

	a. cd gateway
	
	b. npm update -g generator-jhipster
	
	c. yo jhipster ("a" overwrite all)
	
	d. ./mvnw


To update databases correctly, running yojhipster in gateway may be necessary


3. 	Lancer le/les microservices
	
	a. cd microservicefolder
	
	b. yojhipster
	
	c. ./mvnw

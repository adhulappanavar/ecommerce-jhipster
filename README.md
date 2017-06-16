# ecommerce-jhipster

1. Switch to gateway directory

  a. $ yo jhipster
  
2. Starting Eureka/JHipster Registry

  a. Switch to gateway/src/main/docker
  
  b. $ docker-compose -f jhipster-registry.yml up
  
  
3. Switch to BrandProducts directory & Create the API CRUD operations using Entities

  a. Create jhipster API basic Scaffolding - generates source code only
  
            $ yo jhipster
            
  b. Create source code only for all the entities
  
            $ yo jhipster:entity Brand &&  yo jhipster:entity Product &&  yo jhipster:entity Category &&  yo jhipster:entity Subcategory
            
  c. Compile & Start the api server 
  
     $ ./gradlew
  
4. Switch to Gateway & Create the HTML & Angular files using Entities

  a. $ yo jhipster:entity Brand &&  yo jhipster:entity Product &&  yo jhipster:entity Category &&  yo jhipster:entity Subcategory
  
  b. $ ./gradlew
  
  
5. Visulaise the Entity Model using JDL-Studio 

  a. Browse to https://jhipster.github.io/jdl-studio/
  
  b. Paste the contents of jhipster.jdl on the studio
  
  [![mutt dark](https://github.com/adhulappanavar/ecommerce-jhipster/blob/master/JhipsterJDLStudioEntityDiagram4Ecomm.png)](https://github.com/adhulappanavar/ecommerce-jhipster/blob/master/JhipsterJDLStudioEntityDiagram4Ecomm.png)
  

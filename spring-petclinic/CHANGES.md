CHANGES TO SPRING PETCLINIC EXAMPLE
===================================

ORIGINAL SOURCE
---------------
[Spring PetClinic](<https://github.com/SpringSource/spring-petclinic>)

CHANGES
-------

1) Addition of `webapp/WEB-INF/jboss-deployment-structure.xml`, ensuring no conflict with JBOSS' Hibernate module with those packaged by this quickstart. See [JBOSS DEPLOYMENT STRUCTURE](<https://docs.jboss.org/author/display/AS7/Class+Loading+in+AS7#ClassLoadinginAS7-JBossDeploymentStructureFile>) for more details.
2) Regressed the jQuery version to 1.9 as that is what is currently certified on EAP.
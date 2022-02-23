Gatling Demo-store Code Repository
=========================
Execution Command
mvn gatling:test

To test it out, simply execute the following command:
//  gatlingdemostore/DemostoreSimulation.scala
    $mvn gatling:test -Dgatling.simulationClass=computerdatabase.BasicSimulation  
    
    mvn gatling:test -Dgatling.simulationClass=session2.DemoStore
    
    mvn gatling:test -Dgatling.simulationClass=gatlingdemostore.DemostoreSimulation
    mvn gatling:test -Dgatling.simulationClass=gatlingdemostore.DemostoreSimulation –DUSERS =10 -DRAMP_DURATION=20 –DDURATION=90
    
    mvn gatling:test –DUSERS =10 -DRAMP_DURATION=20 –DDURATION=90
    
or simply:

    $mvn gatling:test


Git Branches
 20-FrontLine
 
  B2_HomeAbout
  B3_Category
* B4_Product
  B5_AddProduct
  B6_ViewCart
  B7_Login
  B8_CompleteCheckout
  B9_InitSession
  B10_LoginRefactor
  B11_CartTotal
    
  C2_RegularSim
  C3_ClosedModel
  C4_ThrottleSim
  C5_UserJourneys
  C6_Scenarios
  C7_RuntimeParams
  C8_SeqAndPara
  C9_Refactor
  master

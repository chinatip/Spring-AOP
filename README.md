# Spring-AOP

Chinatip Vichian  5710546551

### Output
```sh
1438 [main] INFO sample.spring.aspects.LoggingAspect  - Entering BankAccountServiceImpl's createBankAccount
1438 [main] INFO sample.spring.aspects.LoggingAspect  - args[0] -> 5710546551 sample.spring.BankAccountDetails [accountId=0, balanceAmount=1000, lastTransactionTimestamp=Thu Apr 20 15:41:58 ICT 2017]
1438 [main] INFO sample.spring.BankAccountServiceImpl  - createBankAccount method invoked with params (BankAccountDetails=5710546551 sample.spring.BankAccountDetails [accountId=0, balanceAmount=1000, lastTransactionTimestamp=Thu Apr 20 15:41:58 ICT 2017]
1442 [main] INFO sample.spring.BankAccountDaoImpl  - createBankAccount method invoked with params (BankAccountDetails=5710546551 sample.spring.BankAccountDetails [accountId=0, balanceAmount=1000, lastTransactionTimestamp=Thu Apr 20 15:41:58 ICT 2017]

Process finished with exit code 0

```

### XML file

Link: [XML file](https://github.com/chinatip/Spring-AOP/blob/master/out/production/spring_softwarePattern1/META-INF/spring/applicationContext.xml)
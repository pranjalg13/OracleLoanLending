# (Assignment) Loan Lending Oracle
A application which is used to optimize the loan distribution and subsequently keeping maximum in hand cash

# Tech Stack , Requirements & Tools
- Java
- Java Development Kit (1.8)
- Maven
- Intellij or Eclipse


## Steps to Run Project
- Go into project directory 
- Run **mvn clean package** in terminal to compile jar or in intellij use the Maven Panel to compile
- Now run the generated jar with following command
```
java -jar target/loan-lending-jar-with-dependencies.jar (input-json-location) (output-file-location) (N) (K)
```

### Example
```
java -jar target/loan-lending-jar-with-dependencies.jar input.json output.txt 50000 1000
```

## Submission By
- Name: Pranjal Goyal 
- Email: pranjalgoyal13@gmail.com

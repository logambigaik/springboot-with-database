# springboot-with-database

# Pre-Requisites:
    Install GIT
    Install Maven
    Mysql Database Installation
# Install GIT
    yum install git -y
# Install Maven
    yum install maven -y
# SetUP MYSQL in EC2-Instance
  [Mysql-Setup](https://github.com/Naresh240/Mysql-Setup/blob/main/README.md)
# Clone the code to local machine
    git clone https://github.com/Naresh240/springboot-with-database.git
# Build Artifact using maven command
    cd springboot-with-database
    mvn clean install
# Run Springboot application
    java -jar target/springboot-with-database-1.0-SNAPSHOT.jar
# Create new customer using "/createnewcustomer" API
  Open Post-man app and git URL with API as shown in below
  
  ![image](https://user-images.githubusercontent.com/58024415/104095630-ea695400-52bd-11eb-8b2c-43cb06b118f0.png)

  Raw Data:
  
    {
      "name": "Naresh",
      "country_of_birth": "INDIA",
      "country_of_residence": "AP",
      "segment": "retail"
    }
# Check List of customer in UI using "/listallcustomers" API
  ![image](https://user-images.githubusercontent.com/58024415/104095650-0b31a980-52be-11eb-9038-ccb44155cdc0.png)

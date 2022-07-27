# Mastering Grails

- The project is about customer reward program
- The appllication name is Demitasse
- It will be designed to be accessed in a computer or on a tablet
- Customers enter their phone number on the pad, and it records their purchase
- They can also login to the cafe's web site where they can modify their profile and view rewards

# What will be covered by the project

1. Create database
2. Tools to create web pages

# Setup Project

```bash
sudo apt update

sudo apt-get install openjdk-11-jre
sudo update-alternatives --config javac
sudo update-alternatives --config java

curl -s "https://get.sdkman.io" | bash

sdk install grails 4.0.4
sdk default grails 4.0.4
sdk use grails 4.0.4

sdk install groovy 2.5.6
sdk default groovy 2.5.6
sdk use groovy 2.5.6

# way 01
mkdir Rewards
cd Rewards
grails create-app --inplace

# way 02
grails create-app Rewards
```

# Run project

```bash
grails run-app -port=8081
```
# learning-grails

- Grails use the model/view/controller paradigm

- Use groovy (java subset)

# Model-View-Controller

- <code>Model</code>: data
- <code>View</code>: display in the browser
- <code>Controller</code>: everything between Model and View. Holds the business rules

## Controller

- <code>Spring</code> framework

## Models

- <code>Hibernate</code> framework

## View

- <code>SiteMesh</code> template framework

# Flow

1. Browser
2. Web Server / Dispatcher
3. Controller / Model / Database
4. Controller / View

# Grails Architecture

- Java Language
- Java SDK
- Both on top of Java Virtual Machine

- Grails is prepacked with tomcat java application server

# Installation

-  Install java jdk
```bash
sudo apt update
sudo apt install openjdk-11-jre
```

- Switch java version
```bash
sudo update-alternatives --config javac
sudo update-alternatives --config java
```

- Check java version
```bash
java -version
javac -version
```

- Install sdkman
```bash
curl -s "https://get.sdkman.io" | bash
```

- Install grails
```bash
sdkman install grails 4.0.4
```
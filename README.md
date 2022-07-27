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

- Create grails project (<a href="https://docs.grails.org/3.1.1/ref/Command%20Line/create-app.html">Documentation<a/>)

```bash
grails create-app [name] [--skip-wrapper] [--profile] [profile name] [--features] [FEATURE NAMES]
```

```bash
# way 01
cd project-folder/
grails create-app --inplace

# way 02
grails create-app project-folder
```

- Run application (<a href="https://docs.grails.org/latest/ref/Command%20Line/run-app.html">Documentation</a>)

```bash
grails <<env>>* run-app
```

```bash
grails run-app
grails run-app -https
grails test run-app
```
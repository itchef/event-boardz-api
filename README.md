# Event Boardz API
Event Boardz is an open source event management application.

### Prerequisites

* Java - 1.8
* Git - 2.17
* Postgresql - 10.4

### Development

Want to contribute? Great!

#### Setup Dependencies
Add the following on your *.bashrc* file

```
export EB_DB_HOST=localhost
export EB_DB_PORT=5432
export EB_DB_NAME=<DATABASE NAME>
export EB_DB_USERNAME=<DATABASE_USERNAME>
export EB_DB_PASSWORD=<DATABASE_PASSWORD>
export EB_DB_DDL=create | create-drop | update
```
*Note that: HOST and PORT can be changed based on the environment configuration*

#### Building for source
```
git clone https://github.com/itchef/event-boardz-api.git
cd event-boardz-api
./gradlew build
```

#### Running the server
```
./gradlew run
```

Access the server on http://localhost:8090

# The ReportToMarriage API


## Getting started

### Modules

- `ns`: namespace definitions (ontologies and properties), Semantic schema repository
- `api`: rest-api's for reporting an upcoming marriage
- `service`: services to execute remotely

Reporttomarriage modules are available for Scala 2.12.x. 
To include `xx` add the following to your `build.sbt`:
```
libraryDependencies += "nl.convenantgemeenten.reporttomarriage" %% "{xx}" % "{version}"
```

## Examples
Run local:
```
sbt service/run
```
or with docker:
```
cd examples
docker-compose up
```

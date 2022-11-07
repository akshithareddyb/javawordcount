## Commands and Links to work on word count program
```
mvn archetype:generate `
  -D archetypeGroupId=org.apache.beam `
  -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  -D archetypeVersion=2.42.0 `
  -D groupId=org.example `
  -D artifactId=word-count-beam `
  -D version="0.1" `
  -D package=org.apache.beam.examples `
  -D interactiveMode=false
  ```
  
## Maven creates a new project in the word-count-beam directory.

## Change into word-count-beam:
```
cd .\word-count-beam
```
## Example file:
 dir .\src\main\java\org\apache\beam\examples

## Run with powershell:
```
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

 ```
 [Quick Start Link](https://beam.apache.org/get-started/quickstart-java/)
 
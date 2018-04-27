# my-grpc-sample
Just a hello world grpc sample

# Build
`mvn compile`

# Run Server
`mvn exec:java -Dexec.mainClass='com.mycompany.app.helloworld.HelloWorldServer' -Dexec.classpathScope=compile`

# Run Client
`mvn exec:java -Dexec.mainClass='com.mycompany.app.helloworld.HelloWorldClient' -Dexec.classpathScope=compile`

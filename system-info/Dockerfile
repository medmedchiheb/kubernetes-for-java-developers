FROM hypriot/rpi-java:latest
COPY target/*.jar /opt/systeminfo/
EXPOSE 8080
ENTRYPOINT java -cp /opt/systeminfo/* -XshowSettings:vm $JAVA_OPTIONS com.example.systeminfo.App

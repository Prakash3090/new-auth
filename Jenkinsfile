#!groovy
@Library(['jenkins-shared-pipelines@ocpGradle', 'jenkins-shared-libraries@ocpGradle'])

Map appData = [
    jdkVersion: "17",
    gradleVersion: "7.4.2",
    ocpApp: "lsl-marmsui-qual",
    ocpDeploy: "true", 
    ocpEnvironment: "SIT",
    ocpProject: 'MTP',
    uploadArtifact: true,
    failOnXray: false,
    failOnSonar: false,
    binaryFile: "samples/spa/build/libs/webauthn4j-spring-security-sample-spa.jar",
    gradleTask: "bootJar"
]

dev_ocpGradle(appData)

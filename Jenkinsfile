checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/bhanu6549/WebProject.git']]])
emailext body: 'Test phase', subject: 'Jenkins', to: 'bhanumindtree2020@gmail.com'
build 'Bhanu-Web-Email-Notification'
deploy adapters: [tomcat8(path: '', url: 'http://52.177.179.150:8081/')], contextPath: null, war: 'WAR'

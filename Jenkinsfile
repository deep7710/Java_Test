node {
    
   stage ("Checkout")
   {
       checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'git@github.com:deep7710/Java_Test.git']]]
   }
   
   stage('Build') {
    echo "Build success."
}

}

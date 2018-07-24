node {

stage 'checkout'
git 'https://github.com/narrasubbarao/dev1_repo.git'

stage 'compile'
sh 'mvn compile'

stage 'test'
sh 'mvn test'

stage 'package'
sh 'mvn package'

stage 'artifacts'
archiveArtifacts 'target/*.war'

}

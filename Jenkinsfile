echo 'This is a new feature branch for amuniz'
node {
  stage 'Checkout'
  checkout scm
  stage 'Build'
  sh "${tool 'Maven 3.x'}/bin/mvn clean install"
}

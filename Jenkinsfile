node {
  echo 'Otra ramita!'
  stage 'Checkout'
  checkout scm
  stage 'Build'
  sh "${tool 'Maven 3.x'}/bin/mvn clean install"
}

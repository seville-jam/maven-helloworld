echo 'Hello, my name is Antonio!'
node {
  stage 'Checkout'
  checkout scm
  stage 'Build'
  sh "${tool 'Maven 3.x'}/bin/mvn clean install"
}

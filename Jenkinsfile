node {
  echo 'Hello Seville JAM!'
  stage 'Checkout'
  checkout scm
  stage 'Build'
  sh "${tool 'Maven 3.x'}/bin/mvn clean install"
}

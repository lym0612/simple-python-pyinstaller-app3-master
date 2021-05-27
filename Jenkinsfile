pipeline{
  agent any
    stages{
      stage('测试'){
        steps{
          bat 'python --version'
          bat 'pytest sources/test_calc.py'
        }
    }
}
}

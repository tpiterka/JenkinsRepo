pipeline{
  agent any
  stages{
    stage('syntax'){
      steps{
        sh 'python -m py_compile program.py'
      }
    }
    stage('Testing'){
     steps{
       sh 'bash test.sh'
      }
    }
    stage('deploy'){
      steps{
      sh 'echo "It is dangerous to go alone, take this!"'
      }
    }
  }

}

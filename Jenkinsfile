pipeline
{
agent any
environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
stages
    { 
      stage ('please print hello')
        { steps
            { 
                sh ( '''#!C:\\Program Files\\Git\\usr\\bin\\bash.exe
                "echo Hello"
                 '''   )
             } 
        }
    }
 }
}

pipeline {
 agent {
          label {
               label "built-in"
               customWorkspace "/mnt/dev"
                }
        }
          stages {
                  stage ("first stage") {
                                         steps {
                                                    echo "hello"
                                               } 
                                        }
                  stage ("second stage") {
                              steps {
                                    echo "how are you"
                                     }
                                         }
                 }

}

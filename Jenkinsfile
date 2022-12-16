pipeline{

    agent any

    stages{

        stage('CloneGHRepo'){

            steps{

                echo "This is a stage where we clone the GH Repo."
            }
        }

        stage('CompileGHRepoCode'){

            steps{

                echo "This is a stage where we compile the cloned code"
            }
        }

        stage('CodeReviewGHRepoCode'){

            steps{

                echo "This is a stage where we review the compiled code"
            }
        }

        stage('TestReviewedGHRepoCode'){

            steps{

                echo "This is a stage where we test the reviewed code"
            }
        }

        stage('PackageTestedGHRepoCode'){

            steps{

                echo "This is a stage where we package the tested code"
            }
        }
    }
}
@Library('jenkins-shared-library') _

def mymap = [
    project : "roboshop",
    component: "shipping",
    acc_id: '406682759639'
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
    javaEKSPipeline(mymap) // by default it will call, call function inside this pipeline
}
else{
    echo "Please proceed with PROD process"
}

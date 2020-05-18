properties([[$class: 'JiraProjectProperty'], parameters([string(defaultValue: '31', description: '', name: 'NAME', trim: false)]), pipelineTriggers([pollSCM('* * * * *')])])

node {
    stage("clone"){
        git "https://github.com/dmatan45/MySoftware.git"
    }
    stage("run"){
        python "click.py"
    }
    
}

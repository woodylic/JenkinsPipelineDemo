
//@Library('github.com/woodylic/JenkinsSharedLibraryDemo@master') _
library identifier: 'JenkinsSharedLibraryDemo@master', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/woodylic/JenkinsSharedLibraryDemo.git'])

sharedPipeline {
    repository = 'param1'
    tag = 'param2'
    registry = 'hub.docker.com/woodylic'
    dockerfilePath = '.'
}
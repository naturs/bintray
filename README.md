# bintray

## Usage

### gradle

    apply from 'https://raw.githubusercontent.com/naturs/bintray/master/bintrayUpload.gradle'

### config

    // necessary
    PROJECT_GROUP_ID = 'com.yourname'
    PROJECT_VERSION_NAME = '1.0.0'
    PROJECT_DESCRIPTION = 'desc'
    PROJECT_PACKAGING = 'aar / jar'
    PROJECT_SITE_URL = 'github.com'

    // unnecessary
    PROJECT_ARTIFACT_ID = 'library-xxx' // default is project.name
    PROJECT_JAVA_DOC_NAME = 'library-xxx' // default is project.name

    PROJECT_GIT_URL = 'xxx.git'
    PROJECT_ISSUE_TRACKER = 'xxx/issue'

    DEVELOPER_ID = 'developer_id'
    DEVELOPER_NAME = 'developer_name'
    DEVELOPER_EMAIL = 'developer@xx.com'

    // best in local.properties
    BINTRAY_USER = 'yourname'
    BINTRAY_API_KEY = 'abcdxxxxxx'
pipeline {
agent any
   tools {
        maven 'Maven3.6.3' 
    }
stages {
stage ('Compile Stage') {
steps {
bat 'mvn -B -U -s C:\\talend\\TOS_DI-Win32-20200219_1130-V7.3.1\\configuration\\maven_user_settings.xml compile -P default-settings'

}
}
stage ('Testing Stage') {
steps {
bat 'mvn -B -U -s C:\\talend\\TOS_DI-Win32-20200219_1130-V7.3.1\\configuration\\maven_user_settings.xml test -P default-settings'
}
}

}
}

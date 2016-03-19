Bash:
export ANDROID_HOME=/usr/local/opt/android-sdk

Fish:
set -x ANDROID_HOME /usr/local/opt/android-sdk

android {
    lintOptions {
        abortOnError false
    }
}

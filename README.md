# firebase_commands
flutter_firebase
Source Code:
// firebse initialization
  WidgetsFlutterBinding.ensureInitialized();
  await Firebase.initializeApp();
// root level build.gradel
buildscript {
    ext.kotlin_version = '1.7.10'
    repositories {
        google()
        mavenCentral()
    }
     dependencies { 
        classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:$kotlin_version"
        classpath 'com.google.gms:google-services:4.3.15'
    }
    

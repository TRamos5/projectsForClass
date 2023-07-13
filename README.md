# projectsForClass



In Gradle Module file in dependencies:

    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.5.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'
    implementation "androidx.room:room-runtime:$rootProject.roomVersion"
    annotationProcessor "androidx.room:room-compiler:$rootProject.roomVersion"
    androidTestImplementation "androidx.room:room-testing:$rootProject.roomVersion"

    implementation "androidx.lifecycle:lifecycle-viewmodel:$rootProject.lifecycleVersion"
    implementation "androidx.lifecycle:lifecycle-livedata:$rootProject.lifecycleVersion"
    implementation "androidx.lifecycle:lifecycle-common-java8:$rootProject.lifecycleVersion"



In Gradle Project file under plugins:
```
  ext {
    lifecycleVersion = '2.3.1'
    roomVersion = '2.4.0-alpha05'
}
```



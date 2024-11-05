Solving this type of error while running the project in flutter is explained in the video 
Video Link : 



Error of this Type 👇👇👇
-----------------------------------------------------------------------------
What went wrong:
Execution failed for task ':app:checkDebugDuplicateClasses'.
> A failure occurred while executing com.android.build.gradle.internal.tasks.CheckDuplicatesRunnable
   > Duplicate class kotlin.collections.jdk8.CollectionsJDK8Kt found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk8-1.7.10.jar -> jetified-kotlin-stdlib-jdk8-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.7.10)
     Duplicate class kotlin.internal.jdk7.JDK7PlatformImplementations found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk7-1.7.10.jar -> jetified-kotlin-stdlib-jdk7-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.7.10)
     Duplicate class kotlin.internal.jdk7.JDK7PlatformImplementations$ReflectSdkVersion found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk7-1.7.10.jar -> jetified-kotlin-stdlib-jdk7-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.7.10)
     Duplicate class kotlin.internal.jdk8.JDK8PlatformImplementations found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk8-1.7.10.jar -> jetified-kotlin-stdlib-jdk8-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.7.10)
     Duplicate class kotlin.internal.jdk8.JDK8PlatformImplementations$ReflectSdkVersion found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk8-1.7.10.jar -> jetified-kotlin-stdlib-jdk8-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.7.10)
     Duplicate class kotlin.io.path.ExperimentalPathApi found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk7-1.7.10.jar -> jetified-kotlin-stdlib-jdk7-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.7.10)
     Duplicate class kotlin.io.path.PathRelativizer found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk7-1.7.10.jar -> jetified-kotlin-stdlib-jdk7-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.7.10)
     Duplicate class kotlin.io.path.PathsKt found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) 
     Duplicate class kotlin.streams.jdk8.StreamsKt$asSequence$$inlined$Sequence$1 found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-stdlib:1.8.22) and kotlin-stdlib-jdk8-1.7.10.jar -> jetified-kotlin-stdlib-jdk8-1.7.10 (org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.7.10)
     Duplicate class kotlin.text.jdk8.RegexExtensionsJDK8Kt found in modules kotlin-stdlib-1.8.22.jar -> jetified-kotlin-stdlib-1.8.22 (org.jetbrains.kotlin:kotlin-
     Go to the documentation to learn how to <a href="d.android.com/r/tools/classpath-sync-errors">Fix dependency resolution errors</a>.

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
> Get more help at https://help.gradle.org.

BUILD FAILED in 1m 3s
Error: Gradle task assembleDebug failed with exit code 1

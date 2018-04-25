# Reproduce

    ./gradlew build

    FAILURE: Build failed with an exception.

    * Where:
    Build file '/Users/tolkv/git/tmp/gradle-artifactory-bug/build.gradle' line: 21

    * What went wrong:
    A problem occurred configuring project ':foo-client'.
    > Failed to notify project evaluation listener.
       > A problem occurred configuring project ':foo-common'.
          > Cannot notify listeners of type ProjectEvaluationListener as these listeners are already being notified.
       > A problem occurred configuring project ':foo-common'.
          > Cannot notify listeners of type ProjectEvaluationListener as these listeners are already being notified.
       > A problem occurred configuring project ':foo-common'.
          > Cannot notify listeners of type ProjectEvaluationListener as these listeners are already being notified.
       > A problem occurred configuring project ':foo-common'.
          > Cannot notify listeners of type ProjectEvaluationListener as these listeners are already being notified.

    * Try:
    Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

    * Get more help at https://help.gradle.org



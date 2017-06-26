# PermissionsDispatcher lint failed sample

## Using

* Kotlin 1.1.3
* PermissionsDispatcher 2.4.0

## Condition

1. Use **kapt**
2. Add `@RuntimePermissions` to Activity or Fragment, written by **Java**
3. Run `./gradlew lint`
4. Failed

> NeedOnRequestPermissionsResult: Call the "onRequestPermissionsResult" method of the generated PermissionsDispatcher class in the respective method of your Activity or Fragment

## Log

* lint.txt
* lint-results.html
* lint-results.xml
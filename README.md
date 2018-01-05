# RandomNumberAnimation
Easily create random number change animation to a TextView

<a href="http://www.methodscount.com/?lib=com.github.IONsoft-Indonesia%3ARandomNumberAnimation%3A1.0"><img src="https://img.shields.io/badge/Methods and size-core: 37 | deps: 29878 | 21 KB-e91e63.svg"/></a>

## How to use?
### Step 1. Add the JitPack repository to your build file
```gradle
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
### Step 2. Add the dependency
```gradle
dependencies {
  compile 'com.github.IONsoft-Indonesia:RandomNumberAnimation:1.0'
}
```
### Step 3. Initialize
```kotlin
val randomNumberAnimation = RandomNumberAnimation(yourTextView)
```
### Step 4. Start
```kotlin
randomNumberAnimation.start()
```
### Step 5. Stop
```kotlin
randomNumberAnimation.stop()
// or
randomNumberAnimation.stop(true)// to keep the random number change inside the text
```
## License
```
MIT License

Copyright (c) 2018 PT. IONsoft

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

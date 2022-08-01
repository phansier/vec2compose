# vec2compose

<p align=center>
<img width=400 src="https://user-images.githubusercontent.com/26793300/182098686-b0c5d225-5751-496d-88a2-ccaf49e48cc9.png" alt="xml to compose"/>
</p>


A CLI tool to create `ImageVector` from Androids vector XML files.

## Usage
There are two options to create the `ImageVector`. The first option is to create a Kotlin file
directly
```
./vec2compose -i ic_done.xml -o DoneIcon.kt
```
And the second option is to print the `ImageVector` directly to the console.
```
./vec2compose -i ic_done.xml
```

## Setup
Currently this is only available after a local gradle build
```bash
$ ./gradlew clean jar packageDistribution
```
A `dist` folder is created with the script and the `jar`.

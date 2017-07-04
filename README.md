# m2-repo

```
repositories {
	mavenCentral()
	
	maven {
		url "http://peterlavalle.com/m2-repo/"
	}
}
```

something like

```
dependencies {
  compile "com.peterlavalle:peterlavalle_${scalaFlavour}:2017.06.22"
}
```

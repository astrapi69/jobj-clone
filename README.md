# Overview

<div align="center">

[![Build Status](https://travis-ci.org/astrapi69/jobj-clone.svg?branch=develop)](https://travis-ci.org/astrapi69/jobj-clone) 
[![Coverage Status](https://coveralls.io/repos/github/astrapi69/jobj-clone/badge.svg?branch=develop)](https://coveralls.io/github/astrapi69/jobj-clone?branch=develop) 
[![Open Issues](https://img.shields.io/github/issues/astrapi69/jobj-clone.svg?style=flat)](https://github.com/astrapi69/jobj-clone/issues) 
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/jobj-clone/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/jobj-clone)
[![Javadocs](http://www.javadoc.io/badge/de.alpharogroup/jobj-clone.svg)](http://www.javadoc.io/doc/de.alpharogroup/jobj-clone)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](http://opensource.org/licenses/MIT)

</div>

Utility library for simply clone java objects.

If you like this project put a ⭐ and donate.

# Donations

If you like this library, please consider a donation through paypal: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MJ7V43GU2H386" target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="PayPal this" title="PayPal – The safer, easier way to pay online!" border="0" />
</a>

or over bitcoin or bitcoin-cash with:

36JxRRDfRazLNqUV6NsywCw1q7TK38ukpC

or over ether with:

0x588Aa02De98B1Ef70afeDC3ec5290130a3E5e273

or over the donation buttons at the top.

## Note

No animals were harmed in the making of this library.

## License

The source code comes under the liberal MIT License, making jobj-clone great for all types of applications.

## Maven dependency

Maven dependency is now on sonatype.
Check out [sonatype repository](https://oss.sonatype.org/index.html#nexus-search;gav~de.alpharogroup~jobj-clone~~~) for latest snapshots and releases.

Add the following maven dependency to your project `pom.xml` if you want to import the core functionality of jobj-clone:

Than you can add the dependency to your dependencies:

	<properties>
			...
		<!-- JOBJ-CLONE version -->
		<jobj-clone.version>3.2</jobj-clone.version>
			...
	</properties>
			...
		<dependencies>
			...
			<!-- JOBJ-CLONE DEPENDENCY -->
			<dependency>
				<groupId>de.alpharogroup</groupId>
				<artifactId>jobj-clone</artifactId>
				<version>${jobj-clone.version}</version>
			</dependency>
			...
		</dependencies>
	
			
## gradle dependency

You can first define the version in the ext section and add than the following gradle dependency to your project `build.gradle` if you want to import the core functionality of jobj-clone:

```
ext {
			...
    jobjCloneVersion = "3.2"
			...
}
dependencies {
			...
compile "de.alpharogroup:jobj-clone:${jobjCloneVersion}"
			...
}
```

## Semantic Versioning

The versions of jobj-clone are maintained with the Simplified Semantic Versioning guidelines.

Release version numbers will be incremented in the following format:

`<major>.<minor>.<patch>`

For detailed information on versioning for this project you can visit this [wiki page](https://github.com/lightblueseas/mvn-parent-projects/wiki/Simplified-Semantic-Versioning).

## Want to Help and improve it? ###

The source code for jobj-clone are on GitHub. Please feel free to fork and send pull requests!

Create your own fork of [astrapi69/jobj-clone/fork](https://github.com/astrapi69/jobj-clone/fork)

To share your changes, [submit a pull request](https://github.com/astrapi69/jobj-clone/pull/new/develop).

Don't forget to add new units tests on your changes.

## Contacting the Developers

Do not hesitate to contact the jobj-clone developers with your questions, concerns, comments, bug reports, or feature requests.
- Feature requests, questions and bug reports can be reported at the [issues page](https://github.com/astrapi69/jobj-clone/issues).

# Similar projects

- [cloning](https://github.com/kostaskougios/cloning) deep clone java objects

## Credits

|**Travis CI**|
|     :---:      |
|[![Travis CI](https://travis-ci.com/images/logos/TravisCI-Full-Color.png)](https://coveralls.io/github/astrapi69/jobj-clone?branch=master)|
|Special thanks to [Travis CI](https://travis-ci.org) for providing a free continuous integration service for open source projects|
|     <img width=1000/>     |

|**Nexus Sonatype repositories**|
|     :---:      |
|[![sonatype repository](https://img.shields.io/nexus/r/https/oss.sonatype.org/de.alpharogroup/jobj-clone.svg?style=for-the-badge)](https://oss.sonatype.org/index.html#nexus-search;gav~de.alpharogroup~jobj-clone~~~)|
|Special thanks to [sonatype repository](https://www.sonatype.com) for providing a free maven repository service for open source projects|
|     <img width=1000/>     |

|**coveralls.io**|
|     :---:      |
|[![Coverage Status](https://coveralls.io/repos/github/astrapi69/jobj-clone/badge.svg?branch=develop)](https://coveralls.io/github/astrapi69/jobj-clone?branch=master)|
|Special thanks to [coveralls.io](https://coveralls.io) for providing a free code coverage for open source projects|
|     <img width=1000/>     |

|**javadoc.io**|
|     :---:      |
|[![Javadocs](http://www.javadoc.io/badge/de.alpharogroup/jobj-clone.svg)](http://www.javadoc.io/doc/de.alpharogroup/jobj-clone)|
|Special thanks to [javadoc.io](http://www.javadoc.io) for providing a free javadoc documentation for open source projects|
|     <img width=1000/>     |

# Overview

<div style="text-align: center">

[![Build Status](https://api.travis-ci.com/astrapi69/jobj-clone.svg?branch=master)](https://travis-ci.com/github/astrapi69/jobj-clone)
[![Coverage Status](https://coveralls.io/repos/github/astrapi69/jobj-clone/badge.svg?branch=develop)](https://coveralls.io/github/astrapi69/jobj-clone?branch=develop)
[![Open Issues](https://img.shields.io/github/issues/astrapi69/jobj-clone.svg?style=flat)](https://github.com/astrapi69/jobj-clone/issues)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.astrapi69/jobj-clone/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.astrapi69/jobj-clone)
[![Javadocs](http://www.javadoc.io/badge/io.github.astrapi69/jobj-clone.svg)](http://www.javadoc.io/doc/io.github.astrapi69/jobj-clone)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](http://opensource.org/licenses/MIT)

</div>

Utility library for simply clone java objects.

> Please support this project by simply putting a Github <!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/astrapi69/jobj-clone" data-icon="octicon-star" aria-label="Star astrapi69/jobj-clone on GitHub">Star ⭐</a>
>
> Share this library with friends on Twitter and everywhere else you can
>
> If you love this project [![donation](https://img.shields.io/badge/donate-❤-ff2244.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GVBTWLRAZ7HB8)

# Donations

This project is kept as an open source product and relies on contributions to remain being
developed. If you like this library, please consider a donation

over paypal: <br><br>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MJ7V43GU2H386" target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="PayPal this" title="PayPal – The safer, easier way to pay online!" style="border: none" />
</a>
<br><br>
or over bitcoin(BTC) with this address:

bc1ql2y99q7e8psndhcc3gferk03esw3qqf677rhjy

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/bc1ql2y99q7e8psndhcc3gferk03esw3qqf677rhjy.png"
alt="Donation Bitcoin Wallet" width="250"/>

or over FIO with this address:

FIO7tFMUVAA9cHiPPqKMfMXiSxHrbpiFyRYqTketNuM67aULuwjop

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/FIO7tFMUVAA9cHiPPqKMfMXiSxHrbpiFyRYqTketNuM67aULuwjop.png"
alt="Donation FIO Wallet" width="250"/>

or over Ethereum(ETH) with:

0xc057D159D3C8f3311E73568b334FF6fE82EB2b7D

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/0xc057D159D3C8f3311E73568b334FF6fE82EB2b7D.png"
alt="Donation Ethereum Wallet" width="250"/>

or over Ethereum Classic(ETC) with:

0xF708cA86D86C246B69c3F4BAe431eBbe0c2bfddD

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/0xF708cA86D86C246B69c3F4BAe431eBbe0c2bfddD.png"
alt="Donation Ethereum Classic Wallet" width="250"/>

or over Dogecoin(DOGE) with:

D5yi4Um8cpakd6yPRm2hGWuQ5nrVzhSSW1

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/D5yi4Um8cpakd6yPRm2hGWuQ5nrVzhSSW1.png"
alt="Donation Dogecoin Wallet" width="250"/>

or over Monero(XMR) with:

49bqeRQ7Bf49oJFVC72pqpe5hFbb62pfXDYPdLsadGGF81KZW2ZfrPZ8PbAVu5X2v1TYAspeczMya3cYQysNS4usRRPQHVw

<img
src="https://github.com/astrapi69/jgeohash/blob/master/src/main/resources/img/49bqeRQ7Bf49oJFVC72pqpe5hFbb62pfXDYPdLsadGGF81KZW2ZfrPZ8PbAVu5X2v1TYAspeczMya3cYQysNS4usRRPQHVw.png"
alt="Donation Monero Wallet" width="250"/>

or over the donation buttons at the top.

## Note

No animals were harmed in the making of this library.

## License

The source code comes under the liberal MIT License, making jobj-clone great for all types of
applications.

## Maven dependency

Maven dependency is now on sonatype. Check
out [sonatype repository](https://oss.sonatype.org/index.html#nexus-search;gav~io.github.astrapi69~jobj-clone~~~)
for latest snapshots and releases.

Add the following maven dependency to your project `pom.xml` if you want to import the core
functionality of jobj-clone:

Than you can add the dependency to your dependencies:

	<properties>
			...
		<!-- JOBJ-CLONE version -->
		<jobj-clone.version>3.4</jobj-clone.version>
			...
	</properties>
			...
		<dependencies>
			...
			<!-- JOBJ-CLONE DEPENDENCY -->
			<dependency>
				<groupId>io.github.astrapi69</groupId>
				<artifactId>jobj-clone</artifactId>
				<version>${jobj-clone.version}</version>
			</dependency>
			...
		</dependencies>

## gradle dependency

You can first define the version in the ext section and add than the following gradle dependency to
your project `build.gradle` if you want to import the core functionality of jobj-clone:

define version in file gradle.properties

```

jobjCloneVersion=3.4
```

or in build.gradle ext area

```
ext {
			...
    jobjCloneVersion = "3.4"
			...
}
```

and then add the dependency to the dependencies area

```
dependencies {
			...
    implementation("io.github.astrapi69:jobj-clone:$jobjCloneVersion")
			...
}
```

## Semantic Versioning

The versions of jobj-clone are maintained with the Simplified Semantic Versioning guidelines.

Release version numbers will be incremented in the following format:

`<major>.<minor>.<patch>`

For detailed information on versioning for this project you can visit
this [wiki page](https://github.com/lightblueseas/mvn-parent-projects/wiki/Simplified-Semantic-Versioning)
.

## Want to Help and improve it? ###

The source code for jobj-clone are on GitHub. Please feel free to fork and send pull requests!

Create your own fork of [astrapi69/jobj-clone/fork](https://github.com/astrapi69/jobj-clone/fork)

To share your
changes, [submit a pull request](https://github.com/astrapi69/jobj-clone/pull/new/develop).

Don't forget to add new units tests on your changes.

## Contacting the Developers

Do not hesitate to contact the jobj-clone developers with your questions, concerns, comments, bug
reports, or feature requests.

- Feature requests, questions and bug reports can be reported at
  the [issues page](https://github.com/astrapi69/jobj-clone/issues).

# Similar projects

- [cloning](https://github.com/kostaskougios/cloning) deep clone java objects

## Credits

|**Travis CI**|
|     :---:      |
|[![Travis CI](https://travis-ci.com/images/logos/TravisCI-Full-Color.png)](https://coveralls.io/github/astrapi69/jobj-clone?branch=master)|
|Special thanks to [Travis CI](https://travis-ci.com) for providing a free continuous integration service for open source projects|
|     <img width=1000/>     |

|**Nexus Sonatype repositories**|
|     :---:      |
|[![sonatype repository](https://img.shields.io/nexus/r/https/oss.sonatype.org/io.github.astrapi69/jobj-clone.svg?style=for-the-badge)](https://oss.sonatype.org/index.html#nexus-search;gav~io.github.astrapi69~jobj-clone~~~)|
|Special thanks to [sonatype repository](https://www.sonatype.com) for providing a free maven repository service for open source projects|
|     <img width=1000/>     |

|**coveralls.io**|
|     :---:      |
|[![Coverage Status](https://coveralls.io/repos/github/astrapi69/jobj-clone/badge.svg?branch=develop)](https://coveralls.io/github/astrapi69/jobj-clone?branch=master)|
|Special thanks to [coveralls.io](https://coveralls.io) for providing a free code coverage for open source projects|
|     <img width=1000/>     |

|**javadoc.io**|
|     :---:      |
|[![Javadocs](http://www.javadoc.io/badge/io.github.astrapi69/jobj-clone.svg)](http://www.javadoc.io/doc/io.github.astrapi69/jobj-clone)|
|Special thanks to [javadoc.io](http://www.javadoc.io) for providing a free javadoc documentation for open source projects|
|     <img width=1000/>     |

[org.apache.maven:maven](https://central.sonatype.com/artifact/org.apache.maven/maven/versions) RB check
=======

[![Reproducible Builds](https://reproducible-builds.org/images/logos/rb.svg) an independently-verifiable path from source to binary code](https://reproducible-builds.org/)

## Project: [org.apache.maven:maven](https://central.sonatype.com/artifact/org.apache.maven/maven/versions)

Source code: [https://github.com/apache/maven.git](https://github.com/apache/maven.git)

<details><summary>This project defines 37 modules:</summary>

* [org.apache.maven:apache-maven](https://central.sonatype.com/artifact/org.apache.maven/apache-maven/4.0.0-beta-3)
* [org.apache.maven:maven](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-beta-3)
* [org.apache.maven:maven-api](https://central.sonatype.com/artifact/org.apache.maven/maven-api/4.0.0-beta-3)
* [org.apache.maven:maven-api-core](https://central.sonatype.com/artifact/org.apache.maven/maven-api-core/4.0.0-beta-3)
* [org.apache.maven:maven-api-di](https://central.sonatype.com/artifact/org.apache.maven/maven-api-di/4.0.0-beta-3)
* [org.apache.maven:maven-api-impl](https://central.sonatype.com/artifact/org.apache.maven/maven-api-impl/4.0.0-beta-3)
* [org.apache.maven:maven-api-meta](https://central.sonatype.com/artifact/org.apache.maven/maven-api-meta/4.0.0-beta-3)
* [org.apache.maven:maven-api-metadata](https://central.sonatype.com/artifact/org.apache.maven/maven-api-metadata/4.0.0-beta-3)
* [org.apache.maven:maven-api-model](https://central.sonatype.com/artifact/org.apache.maven/maven-api-model/4.0.0-beta-3)
* [org.apache.maven:maven-api-plugin](https://central.sonatype.com/artifact/org.apache.maven/maven-api-plugin/4.0.0-beta-3)
* [org.apache.maven:maven-api-settings](https://central.sonatype.com/artifact/org.apache.maven/maven-api-settings/4.0.0-beta-3)
* [org.apache.maven:maven-api-spi](https://central.sonatype.com/artifact/org.apache.maven/maven-api-spi/4.0.0-beta-3)
* [org.apache.maven:maven-api-toolchain](https://central.sonatype.com/artifact/org.apache.maven/maven-api-toolchain/4.0.0-beta-3)
* [org.apache.maven:maven-api-xml](https://central.sonatype.com/artifact/org.apache.maven/maven-api-xml/4.0.0-beta-3)
* [org.apache.maven:maven-artifact](https://central.sonatype.com/artifact/org.apache.maven/maven-artifact/4.0.0-beta-3)
* [org.apache.maven:maven-bom](https://central.sonatype.com/artifact/org.apache.maven/maven-bom/4.0.0-beta-3)
* [org.apache.maven:maven-builder-support](https://central.sonatype.com/artifact/org.apache.maven/maven-builder-support/4.0.0-beta-3)
* [org.apache.maven:maven-compat](https://central.sonatype.com/artifact/org.apache.maven/maven-compat/4.0.0-beta-3)
* [org.apache.maven:maven-core](https://central.sonatype.com/artifact/org.apache.maven/maven-core/4.0.0-beta-3)
* [org.apache.maven:maven-di](https://central.sonatype.com/artifact/org.apache.maven/maven-di/4.0.0-beta-3)
* [org.apache.maven:maven-embedder](https://central.sonatype.com/artifact/org.apache.maven/maven-embedder/4.0.0-beta-3)
* [org.apache.maven:maven-jline](https://central.sonatype.com/artifact/org.apache.maven/maven-jline/4.0.0-beta-3)
* [org.apache.maven:maven-model](https://central.sonatype.com/artifact/org.apache.maven/maven-model/4.0.0-beta-3)
* [org.apache.maven:maven-model-builder](https://central.sonatype.com/artifact/org.apache.maven/maven-model-builder/4.0.0-beta-3)
* [org.apache.maven:maven-model-transform](https://central.sonatype.com/artifact/org.apache.maven/maven-model-transform/4.0.0-beta-3)
* [org.apache.maven:maven-plugin-api](https://central.sonatype.com/artifact/org.apache.maven/maven-plugin-api/4.0.0-beta-3)
* [org.apache.maven:maven-repository-metadata](https://central.sonatype.com/artifact/org.apache.maven/maven-repository-metadata/4.0.0-beta-3)
* [org.apache.maven:maven-resolver-provider](https://central.sonatype.com/artifact/org.apache.maven/maven-resolver-provider/4.0.0-beta-3)
* [org.apache.maven:maven-settings](https://central.sonatype.com/artifact/org.apache.maven/maven-settings/4.0.0-beta-3)
* [org.apache.maven:maven-settings-builder](https://central.sonatype.com/artifact/org.apache.maven/maven-settings-builder/4.0.0-beta-3)
* [org.apache.maven:maven-slf4j-provider](https://central.sonatype.com/artifact/org.apache.maven/maven-slf4j-provider/4.0.0-beta-3)
* [org.apache.maven:maven-slf4j-wrapper](https://central.sonatype.com/artifact/org.apache.maven/maven-slf4j-wrapper/4.0.0-beta-3)
* [org.apache.maven:maven-toolchain-builder](https://central.sonatype.com/artifact/org.apache.maven/maven-toolchain-builder/4.0.0-beta-3)
* [org.apache.maven:maven-toolchain-model](https://central.sonatype.com/artifact/org.apache.maven/maven-toolchain-model/4.0.0-beta-3)
* [org.apache.maven:maven-xml-impl](https://central.sonatype.com/artifact/org.apache.maven/maven-xml-impl/4.0.0-beta-3)
* [org.apache.maven:modello-plugin-velocity](https://central.sonatype.com/artifact/org.apache.maven/modello-plugin-velocity/4.0.0-beta-3)
* [org.apache.maven:plexus-utils](https://central.sonatype.com/artifact/org.apache.maven/plexus-utils/4.0.0-beta-3)
</details>

rebuilding **28 releases** of org.apache.maven:maven:
- **25** releases were found successfully **fully reproducible** (100% reproducible artifacts :white_check_mark:),
- 3 had issues (some unreproducible artifacts :warning:, see eventual :mag: diffoscope and/or :memo: issue tracker links):

| version | [build spec](/BUILDSPEC.md) | [result](https://reproducible-builds.org/docs/jvm/): reproducible? | size |
| -- | --------- | ------ | -- |
| [4.0.0-beta-3](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-beta-3/pom) | [mvn jdk21](maven-4.0.0-beta-3.buildspec) | [result](maven-4.0.0-beta-3.buildinfo): [165 :white_check_mark: ](maven-4.0.0-beta-3.buildcompare) | 49M |
| [4.0.0-alpha-13](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-13/pom) | [mvn jdk21](maven-4.0.0-alpha-13.buildspec) | [result](maven-4.0.0-alpha-13.buildinfo): [159 :white_check_mark: ](maven-4.0.0-alpha-13.buildcompare) | 45M |
| [4.0.0-alpha-12](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-12/pom) | [mvn jdk21](maven-4.0.0-alpha-12.buildspec) | [result](maven-4.0.0-alpha-12.buildinfo): [144 :white_check_mark: ](maven-4.0.0-alpha-12.buildcompare) | 44M |
| [4.0.0-alpha-10](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-10/pom) | [mvn jdk17](maven-4.0.0-alpha-10.buildspec) | [result](maven-4.0.0-alpha-10.buildinfo): [146 :white_check_mark: ](maven-4.0.0-alpha-10.buildcompare) | 41M |
| [4.0.0-alpha-9](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-9/pom) | [mvn jdk21](maven-4.0.0-alpha-9.buildspec) | [result](maven-4.0.0-alpha-9.buildinfo): [146 :white_check_mark: ](maven-4.0.0-alpha-9.buildcompare) | 41M |
| [4.0.0-alpha-8](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-8/pom) | [mvn jdk21](maven-4.0.0-alpha-8.buildspec) | [result](maven-4.0.0-alpha-8.buildinfo): [141 :white_check_mark: ](maven-4.0.0-alpha-8.buildcompare) | 41M |
| [4.0.0-alpha-7](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-7/pom) | [mvn jdk17](maven-4.0.0-alpha-7.buildspec) | [result](maven-4.0.0-alpha-7.buildinfo): [140 :white_check_mark: ](maven-4.0.0-alpha-7.buildcompare) | 37M |
| [4.0.0-alpha-5](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-5/pom) | [mvn jdk17](maven-4.0.0-alpha-5.buildspec) | [result](maven-4.0.0-alpha-5.buildinfo): [87 :white_check_mark: ](maven-4.0.0-alpha-5.buildcompare) | 35M |
| [4.0.0-alpha-4](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-4/pom) | [mvn jdk17](maven-4.0.0-alpha-4.buildspec) | [result](maven-4.0.0-alpha-4.buildinfo): [87 :white_check_mark: ](maven-4.0.0-alpha-4.buildcompare) | 36M |
| [4.0.0-alpha-3](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-3/pom) | [mvn jdk8](maven-4.0.0-alpha-3.buildspec) | [result](maven-4.0.0-alpha-3.buildinfo): [92 :white_check_mark: ](maven-4.0.0-alpha-3.buildcompare) | 36M |
| [4.0.0-alpha-2](https://central.sonatype.com/artifact/org.apache.maven/maven/4.0.0-alpha-2/pom) | | | |
| [3.9.8](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.8/pom) | [mvn jdk21](maven-3.9.8.buildspec) | [result](maven-3.9.8.buildinfo): [75 :white_check_mark: ](maven-3.9.8.buildcompare) | 30M |
| [3.9.7](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.7/pom) | [mvn jdk21](maven-3.9.7.buildspec) | [result](maven-3.9.7.buildinfo): [75 :white_check_mark: ](maven-3.9.7.buildcompare) | 31M |
| [3.9.6](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.6/pom) | [mvn jdk21](maven-3.9.6.buildspec) | [result](maven-3.9.6.buildinfo): [77 :white_check_mark: ](maven-3.9.6.buildcompare) | 30M |
| [3.9.5](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.5/pom) | [mvn jdk17](maven-3.9.5.buildspec) | [result](maven-3.9.5.buildinfo): [77 :white_check_mark: ](maven-3.9.5.buildcompare) | 30M |
| [3.9.4](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.4/pom) | [mvn jdk17](maven-3.9.4.buildspec) | [result](maven-3.9.4.buildinfo): [77 :white_check_mark: ](maven-3.9.4.buildcompare) | 30M |
| [3.9.3](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.3/pom) | [mvn jdk17](maven-3.9.3.buildspec) | [result](maven-3.9.3.buildinfo): [77 :white_check_mark: ](maven-3.9.3.buildcompare) | 30M |
| [3.9.2](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.2/pom) | [mvn jdk17](maven-3.9.2.buildspec) | [result](maven-3.9.2.buildinfo): [47 :white_check_mark: ](maven-3.9.2.buildcompare) | 29M |
| [3.9.1](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.1/pom) | [mvn jdk17](maven-3.9.1.buildspec) | [result](maven-3.9.1.buildinfo): [47 :white_check_mark: ](maven-3.9.1.buildcompare) | 28M |
| [3.9.0](https://central.sonatype.com/artifact/org.apache.maven/maven/3.9.0/pom) | [mvn jdk17](maven-3.9.0.buildspec) | [result](maven-3.9.0.buildinfo): [47 :white_check_mark: ](maven-3.9.0.buildcompare) | 28M |
| [3.8.8](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.8/pom) | [mvn jdk8 w](maven-3.8.8.buildspec) | [result](maven-3.8.8.buildinfo): [47 :white_check_mark: ](maven-3.8.8.buildcompare) | 27M |
| [3.8.7](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.7/pom) | [mvn jdk8 w](maven-3.8.7.buildspec) | [result](maven-3.8.7.buildinfo): [47 :white_check_mark: ](maven-3.8.7.buildcompare) | 27M |
| [3.8.6](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.6/pom) | [mvn jdk8 w](maven-3.8.6.buildspec) | [result](maven-3.8.6.buildinfo): [47 :white_check_mark: ](maven-3.8.6.buildcompare) | 27M |
| [3.8.5](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.5/pom) | [mvn jdk8 w](maven-3.8.5.buildspec) | [result](maven-3.8.5.buildinfo): [43 :white_check_mark:  4 :warning:](maven-3.8.5.buildcompare) [:mag:](maven-3.8.5.diffoscope) | 27M |
| [3.8.4](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.4/pom) | [mvn jdk8 w](maven-3.8.4.buildspec) | [result](maven-3.8.4.buildinfo): [47 :white_check_mark: ](maven-3.8.4.buildcompare) | 28M |
| [3.8.3](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.3/pom) | [mvn jdk8 w](maven-3.8.3.buildspec) | [result](maven-3.8.3.buildinfo): [47 :white_check_mark: ](maven-3.8.3.buildcompare) | 28M |
| [3.8.2](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.2/pom) | [mvn jdk8 w](maven-3.8.2.buildspec) | [result](maven-3.8.2.buildinfo): [47 :white_check_mark: ](maven-3.8.2.buildcompare) | 29M |
| [3.8.1](https://central.sonatype.com/artifact/org.apache.maven/maven/3.8.1/pom) | [mvn jdk8 w](maven-3.8.1.buildspec) | [result](maven-3.8.1.buildinfo): [17 :white_check_mark:  15 :warning:](maven-3.8.1.buildcompare) [:mag:](maven-3.8.1.diffoscope) [:memo:](https://issues.apache.org/jira/browse/MNG-7155) | 29M |
| [3.6.3](https://central.sonatype.com/artifact/org.apache.maven/maven/3.6.3/pom) | [mvn jdk8 w](maven-3.6.3.buildspec) | [result](apache-maven-3.6.3.buildinfo): [2 :white_check_mark:  30 :warning:](apache-maven-3.6.3.buildcompare) [:memo:](https://issues.apache.org/jira/browse/MNG-6859) | 29M |

<i>(size is calculated without javadoc, that has been excluded from reproducibility checks)</i>

# Security vulnerabilites in deployed Galasa

## Vulnerabilities

### Summary

- [sonatype-2015-0002](https://ossindex.sonatype.org/vulnerability/sonatype-2015-0002?component-type=maven&component-name=commons-collections%2Fcommons-collections&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Critical - 2 projects
- [CVE-2020-13936](https://ossindex.sonatype.org/vulnerability/CVE-2020-13936?component-type=maven&component-name=org.apache.velocity%2Fvelocity&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 2 projects
- [sonatype-2021-0789](https://ossindex.sonatype.org/vulnerability/sonatype-2021-0789?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 1 project
- [CVE-2021-37136](https://ossindex.sonatype.org/vulnerability/CVE-2021-37136?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 1 project
- [CVE-2021-37137](https://ossindex.sonatype.org/vulnerability/CVE-2021-37137?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 1 project
- [CVE-2022-25647](https://ossindex.sonatype.org/vulnerability/sonatype-2021-1694?component-type=maven&component-name=com.google.code.gson%2Fgson&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 17 projects
- [sonatype-2020-1031](https://ossindex.sonatype.org/vulnerability/sonatype-2020-1031?component-type=maven&component-name=io.netty%2Fnetty-codec-http&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - High - 1 project
- [CVE-2021-43797](https://ossindex.sonatype.org/vulnerability/CVE-2021-43797?component-type=maven&component-name=io.netty%2Fnetty-codec-http&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [sonatype-2020-0026](https://ossindex.sonatype.org/vulnerability/sonatype-2020-0026?component-type=maven&component-name=io.netty%2Fnetty-handler&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [sonatype-2021-0818](https://ossindex.sonatype.org/vulnerability/sonatype-2021-0818?component-type=maven&component-name=io.grpc%2Fgrpc-core&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [sonatype-2020-0926](https://ossindex.sonatype.org/vulnerability/sonatype-2020-0926?component-type=maven&component-name=com.google.guava%2Fguava&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [CVE-2021-21295](https://ossindex.sonatype.org/vulnerability/CVE-2021-21295?component-type=maven&component-name=io.netty%2Fnetty-codec-http2&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [CVE-2021-21290](https://ossindex.sonatype.org/vulnerability/CVE-2021-21290?component-type=maven&component-name=io.netty%2Fnetty-common&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project
- [CVE-2021-22569](https://ossindex.sonatype.org/vulnerability/CVE-2021-22569?component-type=maven&component-name=com.google.protobuf%2Fprotobuf-java&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1) - Medium - 1 project

### sonatype-2015-0002

Severity: **Critical**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2015-0002?component-type=maven&component-name=commons-collections%2Fcommons-collections&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

commons-collections:commons-collections:3.2.1

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.artifact.manager
  - org.apache.velocity:velocity:1.7
  - commons-collections:commons-collections:3.2.1

- dev.galasa:dev.galasa.sem.manager
  - org.apache.velocity:velocity:1.7
  - commons-collections:commons-collections:3.2.1


### CVE-2020-13936

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2020-13936?component-type=maven&component-name=org.apache.velocity%2Fvelocity&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

org.apache.velocity:velocity:1.7

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.artifact.manager
  - org.apache.velocity:velocity:1.7

- dev.galasa:dev.galasa.sem.manager
  - org.apache.velocity:velocity:1.7


### sonatype-2021-0789

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2021-0789?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final


### CVE-2021-37136

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-37136?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final


### CVE-2021-37137

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-37137?component-type=maven&component-name=io.netty%2Fnetty-codec&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final


### CVE-2022-25647

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2021-1694?component-type=maven&component-name=com.google.code.gson%2Fgson&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

com.google.code.gson:gson:2.7

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.framework
  - com.google.code.gson:gson:2.7

com.google.code.gson:gson:2.8.5

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.core.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.elasticlog.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.bootstrap
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.cps
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.health
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.ras
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.runs
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.testcatalog
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.framework.api.webui
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.http.manager.ivt
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.phoenix2.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.zos3270.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.zosconsole.zosmf.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.zosfile.zosmf.manager
  - com.google.code.gson:gson:2.8.5

- dev.galasa:dev.galasa.zosrseapi.manager
  - com.google.code.gson:gson:2.8.5


### sonatype-2020-1031

Severity: **High**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2020-1031?component-type=maven&component-name=io.netty%2Fnetty-codec-http&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec-http:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final


### CVE-2021-43797

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-43797?component-type=maven&component-name=io.netty%2Fnetty-codec-http&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec-http:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final


### sonatype-2020-0026

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2020-0026?component-type=maven&component-name=io.netty%2Fnetty-handler&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-handler:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final
  - io.netty:netty-handler:4.1.52.Final


### sonatype-2021-0818

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2021-0818?component-type=maven&component-name=io.grpc%2Fgrpc-core&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.grpc:grpc-core:1.39.0

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.etcd:jetcd-core:0.5.9
  - io.grpc:grpc-core:1.39.0


### sonatype-2020-0926

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/sonatype-2020-0926?component-type=maven&component-name=com.google.guava%2Fguava&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

com.google.guava:guava:30.1.1-jre

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - com.google.guava:guava:30.1.1-jre


### CVE-2021-21295

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-21295?component-type=maven&component-name=io.netty%2Fnetty-codec-http2&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec-http2:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.etcd:jetcd-core:0.5.9
  - io.grpc:grpc-netty:1.39.0
  - io.netty:netty-codec-http2:4.1.52.Final

io.netty:netty-codec-http:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final


### CVE-2021-21290

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-21290?component-type=maven&component-name=io.netty%2Fnetty-common&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

io.netty:netty-codec-http:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final

io.netty:netty-common:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-common:4.1.52.Final

io.netty:netty-handler:4.1.52.Final

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final
  - io.netty:netty-handler:4.1.52.Final


### CVE-2021-22569

Severity: **Medium**

[Link](https://ossindex.sonatype.org/vulnerability/CVE-2021-22569?component-type=maven&component-name=com.google.protobuf%2Fprotobuf-java&utm_source=ossindex-client&utm_medium=integration&utm_content=1.1.1)

Vulnerable artifacts:

com.google.protobuf:protobuf-java:3.17.2

Galasa Projects/Images directly affected:

- dev.galasa:dev.galasa.cps.etcd
  - com.google.protobuf:protobuf-java-util:3.17.2
  - com.google.protobuf:protobuf-java:3.17.2




## Galasa Projects/Images

### Summary

- dev.galasa:dev.galasa.artifact.manager - 2 High+, 18 dependents
- dev.galasa:dev.galasa.core.manager - 1 High+, 8 dependents
- dev.galasa:dev.galasa.cps.etcd - 4 High+, 7 Other
- dev.galasa:dev.galasa.elasticlog.manager - 1 High+, 1 dependents
- dev.galasa:dev.galasa.framework - 1 High+, 28 dependents
- dev.galasa:dev.galasa.framework.api - 1 High+
- dev.galasa:dev.galasa.framework.api.bootstrap - 1 High+
- dev.galasa:dev.galasa.framework.api.cps - 1 High+
- dev.galasa:dev.galasa.framework.api.health - 1 High+
- dev.galasa:dev.galasa.framework.api.ras - 1 High+
- dev.galasa:dev.galasa.framework.api.runs - 1 High+
- dev.galasa:dev.galasa.framework.api.testcatalog - 1 High+
- dev.galasa:dev.galasa.framework.api.webui - 1 High+
- dev.galasa:dev.galasa.http.manager.ivt - 1 High+
- dev.galasa:dev.galasa.phoenix2.manager - 1 High+
- dev.galasa:dev.galasa.sem.manager - 2 High+
- dev.galasa:dev.galasa.zos3270.manager - 1 High+, 1 dependents
- dev.galasa:dev.galasa.zosconsole.zosmf.manager - 1 High+
- dev.galasa:dev.galasa.zosfile.zosmf.manager - 1 High+
- dev.galasa:dev.galasa.zosrseapi.manager - 1 High+

### dev.galasa:dev.galasa.artifact.manager

- sonatype-2015-0002 - **Critical**
  - org.apache.velocity:velocity:1.7
  - commons-collections:commons-collections:3.2.1

- CVE-2020-13936 - **High**
  - org.apache.velocity:velocity:1.7


### dev.galasa:dev.galasa.core.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.cps.etcd

- sonatype-2021-0789 - **High**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final

- CVE-2021-37137 - **High**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final

- CVE-2021-37136 - **High**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec:4.1.52.Final

- sonatype-2020-1031 - **High**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final

- sonatype-2020-0026 - **Medium**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final
  - io.netty:netty-handler:4.1.52.Final

- CVE-2021-43797 - **Medium**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-codec-http:4.1.52.Final

- sonatype-2021-0818 - **Medium**
  - io.etcd:jetcd-core:0.5.9
  - io.grpc:grpc-core:1.39.0

- sonatype-2020-0926 - **Medium**
  - com.google.guava:guava:30.1.1-jre

- CVE-2021-21295 - **Medium**
  - io.etcd:jetcd-core:0.5.9
  - io.grpc:grpc-netty:1.39.0
  - io.netty:netty-codec-http2:4.1.52.Final

- CVE-2021-22569 - **Medium**
  - com.google.protobuf:protobuf-java-util:3.17.2
  - com.google.protobuf:protobuf-java:3.17.2

- CVE-2021-21290 - **Medium**
  - io.netty:netty-handler-proxy:4.1.52.Final
  - io.netty:netty-common:4.1.52.Final


### dev.galasa:dev.galasa.elasticlog.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.7


### dev.galasa:dev.galasa.framework.api

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.bootstrap

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.cps

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.health

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.ras

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.runs

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.testcatalog

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.framework.api.webui

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.http.manager.ivt

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.phoenix2.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.sem.manager

- sonatype-2015-0002 - **Critical**
  - org.apache.velocity:velocity:1.7
  - commons-collections:commons-collections:3.2.1

- CVE-2020-13936 - **High**
  - org.apache.velocity:velocity:1.7


### dev.galasa:dev.galasa.zos3270.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.zosconsole.zosmf.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.zosfile.zosmf.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


### dev.galasa:dev.galasa.zosrseapi.manager

- CVE-2022-25647 - **High**
  - com.google.code.gson:gson:2.8.5


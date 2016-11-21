Add the following section to the maven settings.xml file:
<server>
  <id>local.nexus.repo</id>
   <username>admin</username>
   <password>admin123</password>
</server>

To perfor a release:
1) mvn --batch-mode release:prepare
2) mvn release:perform


autoVersionSubmodules
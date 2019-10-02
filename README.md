bonitamavenrepository
All Bonita Community library should be store here. Then, in a pom.xml, add this definition to let's the POM retrieve the Bonita Livrairy


<repositories>
	    <repository>
	      <releases>
	        <enabled>true</enabled>
	        <checksumPolicy>warn</checksumPolicy>
	      </releases>
	      <snapshots>
	        <enabled>false</enabled>
	      </snapshots>
	      <id>logPageBonita</id>
	      <name>logPageBonita</name>
	      <url>https://raw.githubusercontent.com/Bonitasoft-Community/bonitamavenrepository/master</url>
	      <layout>default</layout>
	    </repository>
	</repositories>
  

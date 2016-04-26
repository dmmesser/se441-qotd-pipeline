stage "DEV"

node {
	
	git url: 'https://github.com/dmmesser/se441-qotd.git'

	def gradleHome = tool 'Gradle 2.11'
	sh "${gradleHome}/2.11/bin/gradle assemble uploadArchives"

}
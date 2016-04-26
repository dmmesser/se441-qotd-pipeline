stage "DEV"

node {
	
	git ’https://github.com/dmmesser/se441-qotd.git'
	def gradleHome = tool 'Gradle 2.11'
	sh “${gradleHome}/bin/ assemble uploadArchives”

}
# tpargain
JarUsageFinder:

Usecase: If you need to find out usage of any particular package in a jar, this utility can be used by passing argument:
	 "/Users/test/git/jars/,/Users/test/git/jars" "com.test.jar.used"
	First argument is comma separated location where the jars to be analyzed are present,
	Second argument is the package of dependency jar we are looking for.
	
Functionality: The utility makes use of objectweb's asm4, the ASM library was therefore designed to
work on compiled Java classes. It was also designed to be as fast and as small as possible. The goal of the ASM library is to generate, transform and analyze compiled Java classes, represented as byte arrays
	

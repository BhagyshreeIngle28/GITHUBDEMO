set projectLocation=C:\Users\Bhagyshree\eclipse-workspace\JenkinsTestngDemo1
cd %projectLocation%
set classpath=%projectLocation%\bin;%projectLocation%\lib\*
java org.testng.TestNG %projectLocation%\testng.xml
pause
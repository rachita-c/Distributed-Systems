all:

	javac -d . src/Message.java
	javac -d . src/Rule.java
	javac -d . src/User.java
	javac -classpath lib/snakeyaml-1.14.jar:. -d . src/MessagePasser.java

clean:
	rm *.class
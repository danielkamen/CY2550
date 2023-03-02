JFLAGS = -g
JC = javac
JVM = java 
FILE=
.SUFFIXES: .java .class

.java.class:
	$(JC) $(JFLAGS) $*.java

MAIN = Experiment 

classes: $(Mainxkcdpwgen:.java=.class)

run: $(MAIN).class
	$(JVM) $(MAIN) $(FILE)
clean:
	$(RM) *.class


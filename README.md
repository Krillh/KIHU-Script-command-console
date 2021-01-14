# KIHU-Script-command-console

what is WIP(don't use if you want good results)
    -file.add.fileType    (currently, you can make new file types, but they function the same as a .txt file)
    -.json files    (currently has no implementation)

syntax:
    -(function, written as object)~(arg1)//(arg2)
commands:
    -test~(any)    -just to test, to make sure things are working
    -console.clear   -clears the output text area
    -file.set~(fileName)//(contents)   -sets the contents of a file, creates one if there isn't one, or replaces one if there is
    -file.read~(tileName)    -outputs the contents of a file
    -file.delete~(fileName)    -deletes a file(no going back)
    -file.run~(fileName(.js))  -runs .js files
    -file.add.fileType~(type)  -_(WIP)_   it will add a file type
    -file.list.all   -lists all of the files as an object
    -file.list.txt   -lists .txt files as an object
    -file.list.js    -lists .js files as an object
    -file.list.json  -lists .json files as an object
    -msg.encode~(message to encode)    -outputs an encoded version of a message encoded with KIHU Encoding
    -msg.decode~(message to decode)    -outputs a decoded version of a message that was encoded with KIHU Encoding
    -note.write~(str)    -writes a note to the next open enrire
    -note.read~(num/'all')   -if arg is a number, outputs the entire of that number. if arg is "all" outputs all of the entires
    -note.delete~(num/'all')   -if arg is a number, deletes the entire of that number. if arg is "all" deletes all of the entires

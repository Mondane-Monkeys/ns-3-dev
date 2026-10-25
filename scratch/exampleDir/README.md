# Example of running your own project
- The project name is the directory name
- The system automatically starts with the file containing "main()"

## To run:*
1. `./ns3 configure --enable-examples --enable-tests`
2. `./ns3 build`
3. `./ns3 run exmapleDir/exampleMain`
Replace "exmapleDir/exampleMain" with the name of the directory and main file in your scratch folder that has your code.

*Note, just using the run command should automatically build it, so you can generally skip steps 1 and 2

Your programs should be written same as the examples provided, referencing dependancies with the same reference and pathing.
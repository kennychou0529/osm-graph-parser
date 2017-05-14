# osm-graph-parser
Java program that parses OSM XML files into a graph representation.

## Getting Started

1. [Download](https://github.com/rovaniemi/osm-graph-parser/releases) the latest versions under the releases tab.
2. [Download](https://www.openstreetmap.org/) openstreetmap data. (Click export, select area, and then export)
3. Make directory called `map` in the directory where you have .jar file.
4. Change If you have multiple osm files name them like `map-01.map`, `map-02.map` etc. and put them in map directory.
5. Now your tree should look like this. ![img](http://imgur.com/ntvFUQN.png)
6. Run the jar file. (Terminal `java -jar <jar-file-name>.jar`)
7. Now you have `graph.json` in the same directory where the .jar file is
8. If you use this data in your own service read[openstreetmap licence](https://opendatacommons.org/licenses/odbl/1.0/)


### Prerequisites

You will need a Java Runtime Environment (JRE) to run java programs. You can downlowd it [here](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Contributing

Please read [CONTRIBUTING.md](contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Mauri Karlin** - *Owner* - [Rovaniemi](https://github.com/Rovaniemi)

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE.md](LICENSE.md) file for details
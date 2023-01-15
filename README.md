# neo4j-exposed-ports
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add emonidi https://emonidi.github.io/neo4j-exposed-ports/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
emonidi` to see the charts.

To install the neo4j-exposed-ports chart:

    helm install my-neo4j-exposed-ports emonidi/neo4j-exposed-ports

To uninstall the chart:

    helm delete my-neo4j-exposed-ports

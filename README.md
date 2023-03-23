# M3-Operator Helm Chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add m3db https://mdfaizsiddiqui.github.io/m3db-operator

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
m3db` to see the charts.

To install the m3db-operator chart:

    helm install my-m3db-operator m3db/m3db-operator

To uninstall the chart:

    helm delete my-m3db-operator

* * *

This project is released under the [Apache License, Version 2.0](https://github.com/m3db/m3/blob/master/LICENSE).

# tchap-web-helm-charts

Helm charts for tchap-web

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add tchap-web https://tchapgouv.github.io/tchap-web-helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
tchap-web` to see the charts.

To install the tchap-web chart:

    helm install my-tchap-web tchap-web/tchap-web

To uninstall the chart:

    helm delete my-tchap-web


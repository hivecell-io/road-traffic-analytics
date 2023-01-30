## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add hivecell https://hivecell-io.github.io/road-traffic-analytics
    helm repo update

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo hivecell` to see the charts.

To install the Road Traffic Analytics chart:

    helm install helm-demo hivecell/helm-demo

To uninstall the chart:

    helm delete helm-demo
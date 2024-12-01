# k8s-summit-2024
A sample helm chart repo created in k8s summit 2024.


為您的 Helm chart 新增 charts/myapi/README.md，請將下列字串進行替換：

<alias> -> $YOUR_GITHUB_ACCOUNT-k8s-summit-2024
<orgname> -> $YOUR_GITHUB_ACCOUNT
<chart-name> -> myapi
helm-charts -> k8s-summit-2024

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add <alias> https://<orgname>.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo <alias>` to see the charts.

To install the <chart-name> chart:

    helm install <orgname>-<chart-name> <alias>/<chart-name>

To uninstall the chart:

    helm delete <orgname>-<chart-name>

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add menghsin-2021-k8s-summit-2024 https://menghsin-2021.github.io/k8s-summit-2024

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo menghsin-2021-k8s-summit-2024` to see the charts.

To install the myapi chart:

    helm install menghsin-2021-myapi menghsin-2021-k8s-summit-2024/myapi

To uninstall the chart:

    helm delete menghsin-2021-myapi

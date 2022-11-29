
# Helm Charts

The canonical source for Helm charts is the [Artifact Hub](https://artifacthub.io), an aggregator for distributed chart repos.

## Supported Kubernetes Versions

This chart repository supports the latest and previous minor versions of Kubernetes. For example, if the latest minor release of Kubernetes is 1.8 then 1.7 and 1.8 are supported. Charts may still work on previous versions of Kubernertes even though they are outside the target supported window.

To provide that support the API versions of objects should be those that work for both the latest minor release and the previous one.

## Happy Helming in China

If you are in China, there are some problems to use upstream Helm Charts directly (e.g. images hosted on `gcr.io`, `quay.io`, and Charts hosted on `googleapis.com` etc), you can use this mirror repo at https://github.com/cloudnativeapp/charts which automatically sync & replace unavailable image & repo URLs in every Chart.

# managed-kubernetes-pricing

This notebook is meant to provide a mechanism to efficiently evaluate the price of running Kubernetes across the three major cloud providers:

 - Elastic Kubernetes Service (AWS)
 - Azure Kubernetes Service (Azure)
 - Google Kubernetes Engine (GCP)

I pulled the prices from each cloud providers pricing page, but if I made a mistake on any, feel free to let me know (via a github issue -- or even better a pull request!).

![](images/interactive-plot.png)
*The End Result*

Because Azure doesn't charge for the compute used for the control plane, AKS is cheapest when running many, smaller clusters, but for more, larger clusters GKE is the least expensive option.

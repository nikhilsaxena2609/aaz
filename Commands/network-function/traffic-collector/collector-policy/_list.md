# [Command] _network-function traffic-collector collector-policy list_

List Collector policies

## Versions

### [2022-08-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrZnVuY3Rpb24vYXp1cmV0cmFmZmljY29sbGVjdG9ycy97fS9jb2xsZWN0b3Jwb2xpY2llcw==/2022-08-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.networkfunction/azuretrafficcollectors/{}/collectorpolicies 2022-08-01 -->

#### examples

- Return a list of collector policies by resource group and traffic-collector name
    ```bash
        network-function traffic-collector collector-policy list --resource-group rg1 --traffic-collector-name atc1
    ```

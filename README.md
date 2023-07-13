# Enterprise Contract Configuration Files

This repo contains a set of `policy.yaml` files which can be used with
Enterprise Contract and the Red Hat Trusted Application Pipeline.

There is a predefined RHTAP Integration Test pipeline definition for each of
these configs which can be used when creating an Integration Test in RHTAP as
per the [documentation
here](https://redhat-appstudio.github.io/docs.appstudio.io/Documentation/main/how-to-guides/proc_managing-compliance-with-the-enterprise-contract/).

The policy configuration files are:

### Default

Includes rules for levels 1, 2 & 3 of SLSA v0.1.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//default`
* Source: [default/policy.yaml](https://github.com/enterprise-contract/config/blob/main/default/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract.yaml)

### Redhat

Include the set of policy rules required for Red Hat products.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//redhat`
* Source: [redhat/policy.yaml](https://github.com/enterprise-contract/config/blob/main/redhat/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract-redhat.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract-redhat.yaml)

### SLSA1

The minimal rules plus the rules for level 1 of SLSA v0.1.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//slsa1`
* Source: [slsa1/policy.yaml](https://github.com/enterprise-contract/config/blob/main/slsa1/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract-slsa1.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract-slsa1.yaml)

### SLSA2

The minimal rules plus the rules for levels 1 & 2 of SLSA v0.1.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//slsa2`
* Source: [slsa2/policy.yaml](https://github.com/enterprise-contract/config/blob/main/slsa2/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract-slsa2.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract-slsa2.yaml)

### SLSA3

The minimal rules plus the rules for levels 1, 2 & 3 of SLSA v0.1.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//slsa3`
* Source: [slsa3/policy.yaml](https://github.com/enterprise-contract/config/blob/main/slsa3/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract-slsa3.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract-slsa3.yaml)

### Everything

Include every rule in the default policy source.

* URL for Enterprise Contract: `github.com/enterprise-contract/config//everything`
* Source: [everything/policy.yaml](https://github.com/enterprise-contract/config/blob/main/everything/policy.yaml)
* RHTAP Integration Test pipeline definition:
    * Github URL: `https://github.com/redhat-appstudio/build-definitions.git`
    * Path in repository: [`pipelines/enterprise-contract-everything.yaml`](https://github.com/redhat-appstudio/build-definitions/blob/main/pipelines/enterprise-contract-everything.yaml)

## See also

* [Policy Rule Documentation](https://enterprisecontract.dev/docs/ec-policies/release_policy.html)
* [Getting Started with Enterprise Contract &amp; Red Hat Trusted Application Pipeline](https://enterprisecontract.dev/docs/user-guide/main/getting-started.html)

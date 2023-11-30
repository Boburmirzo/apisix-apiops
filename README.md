# Exploring APIOps with APISIX

This repo demonstrates how you can use [Apache APISIX](https://apisix.apache.org/) to automate developer pipeline with APIOps (DevOps + GitOps).

## How does it work?

Using the [standalone deployment](https://apisix.apache.org/docs/apisix/deployment-modes/#standalone) mode, [declarative configuration](https://docs.api7.ai/apisix/reference/configuration-files#config-defaultyaml-and-configyaml) and [APISIX Declarative CLI](https://github.com/api7/adc), aka ADC is one of the quickest and easiest ways to get started with the APIOps.

You start with designing an [apisix.yml](https://github.com/Boburmirzo/apisix-standalone-deployment-mode/blob/main/apisix/apisix.yml) file (which includes **declarative configuration** for APISIX objects like *upstreams, plugins, and routes*). Use [APISIX Declarative CLI](https://github.com/api7/adc) (ADC) tool to capture APISIX configuration changes, and synchronize change back into a running instance. Then, you connect APISIX to continuous integration and continuous delivery of CI/CD tools such as GitHub actions in the same way you update and deliver code to enable APIOps.



## How to run this demo?

**Prerequisites**

• [Docker](https://docs.docker.com/get-docker/) is used to install the containerized example backend service(You can use your own API backend service) and APISIX.

To start the project run simply the following command from the project root directory:

```bash
docker compose up
```


### Community

🙋 [Join the Apache APISIX Community](https://apisix.apache.org/docs/general/join/)

🐦 [Follow us on Twitter](https://twitter.com/ApacheAPISIX)

📝 [Find us on Slack](https://join.slack.com/t/the-asf/shared_invite/zt-vlfbf7ch-HkbNHiU_uDlcH_RvaHv9gQ)

💁 [How to contribute page](https://apisix.apache.org/docs/general/how-to-contribute/)

### About the author

Follow me on Twitter: [@BoburUmurzokov](https://twitter.com/BoburUmurzokov)

Visit my blog: [www.iambobur.com](https://www.iambobur.com/)

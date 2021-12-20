# neo-insomnia

Last Updated: Neo **v3.1.0**

A full collection of requests for use with Neo N3 RPC endpoints. The collection is based on the core [Neo node](https://github.com/neo-project/neo-node) API; other clients (e.g. [NeoGo](https://github.com/nspcc-dev/neo-go/blob/master/docs/rpc.md#implementation-notices) may have slight differences in supported methods or behavior.

Three environments are provided: one for MainNet, one for TestNet, and one set up following the [Neo Express](https://github.com/neo-project/neo-express) defaults. 

![neo-insomnia](https://github.com/EdgeDLT/neo-insomnia/blob/main/neo-insomnia.png)

The collection is divided into 5 categories by request type:

* Blockchain
* Node
* Contract
* Plugin
* Wallet

The structure follows the official API reference, except `listplugins` has been moved to **Node**, and `validateaddress` has been added to **Wallet**.

# Quickstart

## 1. Download Insomnia
Get the desktop client for your OS.
> https://insomnia.rest/download

## 2. Import the collection
Save the `Insomnia-neo-n3-api.json` file and import it via **Preferences** > **Data**
> https://docs.insomnia.rest/insomnia/import-export-data

## 3. (Optional) Change endpoints
Use the `Manage Environments` menu if you want to change the nodes used across each environment. You can open the menu quickly using **CTRL+E**. You can supply your own endpoint, or select a public one. Several public nodes for the N3 MainNet and TestNet can be found on Dora.
> https://dora.coz.io/monitor

## 4. Send requests
Select your activate environment (e.g. MainNet or TestNet) and choose a request to perform. Modify the parameters as desired. Visit the `Docs` tab for detailed instructions and examples for each request.

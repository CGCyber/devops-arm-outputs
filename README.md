<h1 align="center"> 
<img src="https://raw.githubusercontent.com/keesschollaart81/vsts-arm-outputs/dev/images/banner.png" width=500 alt="ARM Outputs Banner"/> 
</h1>

<div align="center">

[Click here to view this extension in the Azure DevOps Marketplace](https://marketplace.visualstudio.com/items?itemName=keesschollaart.arm-outputs)

This extension enables you to use the ARM Deployment outputs in your Azure Pipelines.

[![Build Status](https://caseonline.visualstudio.com/ARM%20Outputs/_apis/build/status/ARM%20Outputs-CI?branchName=dev)](https://caseonline.visualstudio.com/ARM%20Outputs/_build/latest?definitionId=19?branchName=dev) [![Dev Deploy](https://caseonline.vsrm.visualstudio.com/_apis/public/Release/badge/0b79a2e6-b205-45d0-a677-ad0688669d24/1/1)](https://caseonline.visualstudio.com/ARM%20Outputs/_release?definitionId=1) [![Production](https://caseonline.vsrm.visualstudio.com/_apis/public/Release/badge/0b79a2e6-b205-45d0-a677-ad0688669d24/1/3)](https://caseonline.visualstudio.com/ARM%20Outputs/_release?definitionId=1)

</div>

This step will use the last successful deployment within the selected resource group. If this deployent has outputs, all of them are copied to Pipelines variables by the ARM Output key: 

[![screenshot-1](images/screenshot.png "Screenshot-1")](images/screenshot.png)

This outputs can then be used by default Azure DevOps Pipelines ways: ```$(same-key-as-in-arm-template)```

Usually this task is ran directly after the 'Azure Resource Group Deployment' task.

[![screenshot-2](images/screenshot2.png "Screenshot-1")](images/screenshot2.png)

## How to use

Checkout the docs in the [Marketplace page](Marketplace.md)

## Help & Contact

Find me at http://case.schollaart.net/. Experiencing problems, or do you have an idea? Please let me know via [Twitter](https://twitter.com/keesschollaart) or by [mail](mailto:keesschollaart81@hotmail.com). Or even better, raise an issue on [GitHub](https://github.com/keesschollaart81/vsts-arm-outputs/issues).

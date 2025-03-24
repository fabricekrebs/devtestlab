# Demo DevTestLabs Custom Artifacts Repository

This repository serves as a demo to showcase how custom artifacts can be managed with Azure DevTest Labs. Artifacts are reusable components that can be applied to virtual machines in a lab to automate software installation, configuration, or other tasks.

## About Azure DevTest Labs Artifacts

Azure DevTest Labs provides built-in artifacts that can be used to quickly set up virtual machines. You can find the official built-in artifacts here:  
[Azure DevTest Labs Built-in Artifacts](https://github.com/Azure/azure-devtestlab/tree/master/Artifacts/linux-apt-package)

## Custom Artifacts in This Repository

This repository demonstrates how to create and manage custom artifacts for specific use cases. Custom artifacts allow you to extend the functionality of Azure DevTest Labs by adding your own scripts and configurations.

### Features

- **Customizable**: Tailor artifacts to meet your specific requirements.
- **Reusable**: Apply artifacts across multiple virtual machines.
- **Extensible**: Add new artifacts as your needs evolve.

## Repository Structure

The repository is organized as follows:

```
artifacts/
    <artifact-name>/
        Artifactfile.json   # Metadata for the artifact
        <script-files>      # Scripts or other resources for the artifact
        <optional-assets>   # Icons or additional files
```

## How to Use

1. (optional) Clone this repository to your local machine or integrate it with your Azure DevTest Labs environment.
2. Add the custom artifacts to your lab configuration.
3. Apply the artifacts to your virtual machines during or after provisioning.

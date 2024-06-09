# Steps to support new python version

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#1890ff', 'secondaryColor': '#ff4d4f', 'tertiaryColor': '#52c41a', 'primaryTextColor': '#ffffff', 'secondaryTextColor': '#ffffff', 'tertiaryTextColor': '#ffffff', 'edgeLabelBackground':'#f0f0f0'}}}%%
graph LR
    A[Build Image] --> B[Build Underthesea Core]
    B --> C[Build Underthesea]
```

## Step 1: Build Image

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#1890ff', 'secondaryColor': '#ff4d4f', 'tertiaryColor': '#52c41a', 'primaryTextColor': '#ffffff', 'secondaryTextColor': '#ffffff', 'tertiaryTextColor': '#ffffff', 'edgeLabelBackground':'#f0f0f0'}}}%%
graph LR
    subgraph A[Build Image - CentOS]
        B[Conda]
        subgraph Python
            P7[Python 3.7]
            P8[Python 3.8]
            P9[Python 3.9]
            P10[Python 3.10]
            P11[Python 3.11]
            P12[Python 3.12]
        end
    E[Rust]
    F[Poetry]
    end
```

First, create a CentOS image with Rust and Python environments. This image will be used to build Underthesea Core in Step 2.

## Step 2: Build Underthesea Core

Build the Underthesea Core using the previously created CentOS image.

## Step 3: Build Underthesea

Finally, build Underthesea.

For more details, refer to the [GitHub Actions Documentation](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#choosing-github-hosted-runners).
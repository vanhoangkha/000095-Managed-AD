# Windows On AWS - AWS Managed Directory Service

> AWS Managed Microsoft AD.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series.

**Read the workshop online:** https://vanhoangkha.github.io/000095-Managed-AD/

## Overview

Your company has been planning to move the business's infrastructure to AWS. However, both CTO and CIO have been concerning about the Windows Server Active Directory Services. As a System and Network Engineer, you are tasked to research about the built-in AWS Directory Service.

This lab will help you out about how to deploy AWS Managed Directory Service as well as how to manage AWS Directory Service

## Workshop contents

1. Introduction
2. Preparation
   - Deploy AWS Managed Directory Service
   - Deploy EC2
3. EC2 Configuration
   - Edit Computer Name (Optional)
   - EC2 Configuration
   - Testing Servers Communication
4. Clean Up Services

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone --recurse-submodules https://github.com/vanhoangkha/000095-Managed-AD.git
cd 000095-Managed-AD
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

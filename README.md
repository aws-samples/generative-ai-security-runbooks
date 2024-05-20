## Create Generative AI runbooks to resolve security findings

Generative AI has the potential to accelerate and streamline security analysis, response, and recovery, enhancing the effectiveness of human engagement. In this workshop, learn how to use [Amazon SageMaker](https://aws.amazon.com/sagemaker/) notebooks and [Amazon Bedrock](https://aws.amazon.com/bedrock/) to quickly resolve security findings in your AWS account. You rely on runbooks for the day-to-day operations, maintenance, and troubleshooting of AWS services. With generative AI, you can gain deeper insights into security findings and take the necessary actions to streamline security analysis and response. You must bring your laptop to participate.

In this workshop, you will learn the art of the possible and how Generative AI can improve your security posture by assisting in remediation of findings. Each module is designed to focus on different techniques.

- In [Module 1](./notebooks/Module1.ipynb) - you will use Claude 3 from Anthropic to summarize a security findings, provide next steps for remediation, and create code to resolve the finding.
- In [Module 2](./notebooks/Module2.ipynb) - you will learn tool use (also referred to as function calling), an advanced technique to expand Claude 3's capabilities to get real time data.
- In [Module 3](./notebooks/Module3.ipynb) - you will demonstrate what you learned from Module 1 to investigate a finding, provide next steps, and create code to resolve.

This workshop is intended for people with security roles. There is no prior experience required, though some background Generative AI, Python, and Security Hub will help. This workshop takes approximately 45 minutes to complete. By the end of this workshop, you will understand some techniques to use Generative AI in your runbooks.

These notebooks are intended to be used on Amazon SageMaker. They have been tested on a ml.t3.medium with Amazon Linux 2, Jupyter Lab 3 in us-west-2.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.


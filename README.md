# Awesome Security Hub [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome AWS Security Hub tools, integrations and resources

## Contents

- [Utilities](#utilities)
- [Reporting](#reporting)
- [Management](#management)
- [Integrations](#integrations)
- [Remediations](#remediations)
- [Workshops](#workshops)

## Utilities

- [MetaHub](https://github.com/gabrielsoltz/metahub) - Impact and context automation for AWS Security Hub and ASFF. HTML, CSV, XLSX and JSON enriched reports. Powerfull query engine.
- [aws-securityhub-score-generator](https://github.com/aws-samples/aws-securityhub-score-generator) - A simple python script to generate security hub scores within your AWS account.
- [mitre-attack-with-aws-security-hub-example](https://github.com/aws-samples/mitre-attack-with-aws-security-hub-example) - Virtual SOC with MITRE Attack integration with AWS Security Hub example

## Reporting

- [steampipe-mod-aws-securityhub](https://github.com/gabrielsoltz/steampipe-mod-aws-securityhub) - Steampipe Mod for AWS Security Hub with different Dashboards
- [aws-security-hub-summary-email](https://github.com/aws-samples/aws-security-hub-summary-email) - Solution and deployment for recurring Security Hub Summary email to provide recipients with a proactive communication summarizing the security posture and improvement within their AWS Accounts.
- [aws-security-hub-full-report-email](https://github.com/aws-samples/aws-security-hub-full-report-email) - Solution to setup a recurring Security Hub CSV full report with email notification to provide detailed report of the security posture.
- [aws-security-hub-analytic-pipeline](https://github.com/aws-samples/aws-security-hub-analytic-pipeline) - AWS Security Hub Analytic Pipeline with Athena
- [automated-security-hub-account-findings-reports](https://github.com/aws-samples/automated-security-hub-account-findings-reports) - Automated Security Hub Account Findings Reports
- [aws-securityhub-findings-to-msteams](https://github.com/aws-samples/aws-securityhub-findings-to-msteams) - Demonstrates sending AWS Security Hub findings to your Microsoft Teams channel
- [aws-security-hub-glue-aggregator-terraform](https://github.com/aws-samples/aws-security-hub-glue-aggregator-terraform) - Code to deploy a solution to aggregate the findings from Security Hub from different accounts to a centralized account using Amazon Kinesis Data Firehose and AWS Glue
- [aws-security-hub-findings-historical-export](https://github.com/aws-samples/aws-security-hub-findings-historical-export) - The CDK project will deploy all AWS resources and infrastructure required to automatically and continually export up to 100 million\* Security Hub Findings in an AWS account as objects in a S3 bucket in JSON format.
- [aws-security-hub-correlation](https://github.com/aws-samples/aws-security-hub-correlation) - The CDK project to correlate Security Hub Findings from multiple AWS Security Services to generate a new Security Hub Finding to indicate a higher chance of a compromise or breach.
- [aws-security-hub-findings-account-data-enrichment](https://github.com/aws-samples/aws-security-hub-findings-account-data-enrichment) - This project contains source code and supporting files for a serverless pipeline for automatically updated AWS Security Hub findings with Account Metadata that you can deploy with the SAM CLI.
- [aws-security-hub-findings-export](https://github.com/aws-samples/aws-security-hub-findings-export) - This solution exports Security Hub Findings to a S3 bucket. We use a CloudWatch Event Rule to forward all Security Hub events to a Kinesis Firehose Data Stream, then a S3 bucket.

## Management

- [aws-security-hub-csv-manager](https://github.com/aws-samples/aws-security-hub-csv-manager) - CSV Manager for AWS Security Hub exports SecurityHub findings to a CSV file and allows you to mass-update SecurityHub findings by modifying that CSV file.
- [SecurityHub-Multiaccount-UpdateControls](https://github.com/aws-samples/SecurityHub-Multiaccount-UpdateControls) - Disabling Security Hub Controls in a Multi Account Environment
- [aws-cfn-for-optimizing-aws-config-for-aws-security-hub](https://github.com/aws-samples/aws-cfn-for-optimizing-aws-config-for-aws-security-hub) - AWS CloudFormation template to set up AWS Config to record only what’s needed for Security Hub.
- [aws-security-hub-cross-account-controls-disabler](https://github.com/aws-samples/aws-security-hub-cross-account-controls-disabler) - AWS Security Hub Cross-Account Controls Disabler
- [aws-security-hub-controls-cli](https://github.com/aws-samples/aws-security-hub-controls-cli) - A CLI tool to disable and enable security standards controls in AWS Security Hub. It is designed to work together with AWS Security Hub Cross-Account Controls Disabler.
- [aws-security-hub-automatic-suppression-rules](https://github.com/aws-samples/aws-security-hub-automatic-suppression-rules) - This project is for SecurityHub auto supression of findings using the batch_update_findings API call.
- [terraform-aws-mcaf-securityhub-findings-manager](https://github.com/schubergphilis/terraform-aws-mcaf-securityhub-findings-manager) - Terraform module to suppress specific events from security hub based on a dynamodb based configuration.
- [terraform-aws-tardigrade-security-hub](https://github.com/plus3it/terraform-aws-tardigrade-security-hub) - Terraform module to enable and configure SecurityHub. The module supports independent accounts with the top-level module, and the cross-account invite/accept workflow with the modules/cross-account-member module.

## Integrations

- [aws-security-hub-ssm-inspec-integration](https://github.com/aws-samples/aws-security-hub-ssm-inspec-integration) - Continuous compliance monitoring with Chef InSpec and AWS Security Hub
- [iot-device-defender-integration-with-securityhub](https://github.com/aws-samples/iot-device-defender-integration-with-securityhub) - How to import AWS IoT Device Defender audit and detect findings into Security Hub
- [aws-security-hub-scan-with-trivy](https://github.com/aws-samples/aws-security-hub-scan-with-trivy) - How to build a CI/CD pipeline for container vulnerability scanning with Trivy and AWS Security Hub
- [streaming-syslog-to-aws-security-hub-sample](https://github.com/aws-samples/streaming-syslog-to-aws-security-hub-sample) - Streaming Syslog to AWS Security Hub sample project
- [aws-securityhub-config-integration](https://github.com/aws-samples/aws-securityhub-config-integration) - This repository contains Python code to import the findings from AWS Config into AWS Security Hub.
- [amazon-ec2-aws-security-hub-event-monitoring](https://github.com/aws-samples/amazon-ec2-aws-security-hub-event-monitoring) - Monitor and respond to security events in Amazon EC2 instances using Security Hub and CloudWatch Logs Insights
- [aws-systemsmanager-patchcompliance-to-securityhub](https://github.com/aws-samples/aws-systemsmanager-patchcompliance-to-securityhub) - Reporting AWS Systems Manager patch compliance data to AWS Security Hub for multiple accounts under AWS Organizations
- [aws-security-hub-prowler-integrations](https://github.com/aws-samples/aws-security-hub-prowler-integrations) - Use AWS Fargate and Prowler to send AWS Service security configuration findings to Security Hub
- [aws-securityhub-jira-software-integration](https://github.com/aws-samples/aws-securityhub-jira-software-integration) - This solution supports a bidirectional integration between Security Hub and JIRA. Issues can be either created automatically or manually by using custom actions.
- [Security-Hub-Custom-Provider-Demo](https://github.com/iann0036/Security-Hub-Custom-Provider-Demo) - This project shows you how you can integrate with AWS Security Hub to provide your own custom findings. In this example, we periodically check the Troy Hunt's Have I Been Pwned API and report findings whenever a breach is added.
- [custom-securityhub-findings](https://github.com/YogitaDSurve/custom-securityhub-findings) - Custom Security Hub Findings is a repository that allows AWS users to import custom findings into Security Hub using AWS Lambda and get email notifications.
- [SecurityHub_to_AWSChatBot](https://raw.githubusercontent.com/aws-samples/aws-securityhub-to-slack/master/SecurityHub_to_AWSChatBot.yml) - Deploys CustomAction in SecurityHub to enable sending findings to Slack via AWS Chatbot

## Remediations

- (automated-security-response-on-aws)[https://github.com/aws-solutions/automated-security-response-on-aws] - Automated Security Response on AWS is an add-on solution that works with AWS Security Hub to provide a ready-to-deploy architecture and a library of automated playbooks.
- [security-hub-macie-remediation](https://github.com/aws-samples/security-hub-macie-remediation) - Macie Remediation using Security Hub Custom Actions
- [aws-security-hub-response-and-remediation](https://github.com/aws-samples/aws-security-hub-response-and-remediation) - Pre-configured response & remediation playbooks for AWS Security Hub

## Workshops

- [aws-security-hub-workshop](https://github.com/aws-samples/aws-security-hub-workshop)
- [aws-securityhub-automated-remediations-workshop](https://github.com/aws-samples/aws-securityhub-automated-remediations-workshop)

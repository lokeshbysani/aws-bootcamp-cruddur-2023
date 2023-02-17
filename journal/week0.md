# Week 0 — Billing and Architecture

### Install and Configure AWS CLI
<ol>
  <li>Created IAM user with console and programmatic Access. </li>
  <li>Configured AWS CLI in gitpod workspace</li>
  <li>validated user information with the command aws sts get-caller-identity function and validated account number information</li>
  <li>Please do validate gitpod.yaml.</li>
</ol>

### Create Budget

<ul>
  <li>Created Budget with a limit of 5 USD in AWS. Explored both GUI and CLI method to create the budget.</li>
  <li>Considering the free tier limitaions below budget is configured</li>
  <li>Please do validate the JSON files present in aws/json directory in workspace.</li>
</ul>


### Create Billing Alarm
<ul>
  <li>Created SNS topic using CLI approach.</li>
  <li>Created billing alarm with a limit of 1 USD</li>
</ul>

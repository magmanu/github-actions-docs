# github-actions-docs

Github Action to generate github-actions docs for a composite action.

<!-- BEGIN_ACTION_DOCS -->

# github-actions-docs

Generate GitHub action docs for action

# inputs

| Title | Required | Type | Description |
|-----|-----|-----|-----|
| ACTION_FILE_NAME | True |  |The name of the file to be processed |
| OUTPUT_FILE_NAME | True |  |The file that the output report will be written to |
| OUTPUT_MODE | True |  |The output mode, [update/overwrite]. Update will be inserted after a line containing <!-- INSERT_ACTION_DOCS -->, overwrite will overwrite the whole file |
<!-- END_ACTION_DOCS -->

# Local development

To develop locally, install requirements to ensure the .env file is used in the project root:

```
pip3 install -r requirements.txt
```
# reliza-pr-action

## About

GitHub Action to submit the pull request metadata to RelizaHub.

## Note

This action should be used on a workflow triggered by pull_request event.

## Usage

```yaml
steps:
- uses: relizaio/reliza-pr-action@1.0
  with:
    reliza_api_id: <api-id-obtained-from-relizahub>
    reliza_api_key: <api-key-obtained-from-relizahub>
```

## Inputs
The actions supports the following inputs:

- `reliza_api_id`: The project API ID obtained from RelizaHub.
- `reliza_api_key`: The project API Key obtained from RelizaHub.
- `path`: Path to the relative to root of the repo (default is '.').
- `reliza_project_id`: Project UUID if an org-wide key is used.


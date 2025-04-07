# Hello World docker action

This action prints "Hello World" or "Hello" + the name of the person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The Name of the person to greet. Default "World".

## Outputs

### `time`

The time we greeted you.

## Example Usage

```yaml
uses: kurt-opel/github-action-docker-hello-world@v1
with:
  who-to-greet: Kurt
```
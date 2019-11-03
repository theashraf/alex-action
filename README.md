# Alex Github Action

> GitHub Action to automate catching insensitive ,inconsiderate writing.

## What

GitHub Action for [alex](https://alexjs.com/).

alex helps you find gender favouring, polarising, race related, religion inconsiderate, or other unequal phrasing in text.

## Why

- Helps to get better at considerate writing
- Catches many possible offences
- Suggests helpful alternatives

## Usage

On your GitHub Actions workflow file, add the following step:

```yaml
steps:
  uses: theashraf/alex-action@master
```

This will run the "alex ." command without arguments.

# HiveSight Documentation

This repository contains the documentation for HiveSight - the best way to get in front of your buyers on LinkedIn.

HiveSight is a social listening and creator discovery platform that helps businesses discover and engage with content creators across Reddit and LinkedIn.

## Development

This documentation is built with [Mintlify](https://mintlify.com).

### Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

### Publishing Changes

Changes pushed to the main branch are automatically deployed to production.

## Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [HiveSight](https://hivesight.so)

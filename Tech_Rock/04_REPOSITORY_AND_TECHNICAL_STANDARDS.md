# Tech Rock — Repository and Technical Standards

## Repository purpose

Use GitHub for code, versioned technical documentation and portable context. A repository should make it possible to understand what a system is, how it is deployed and which decisions are current.

Keep church institutional context separate from application source code when the application has become a substantial standalone product. Link the two rather than duplicating competing sources of truth.

## Documentation

Prefer Markdown for portable context and technical documentation.

A maintained repository should normally explain:
- purpose and scope;
- architecture;
- setup;
- deployment;
- configuration;
- dependencies;
- data sources;
- known limitations;
- current project state;
- maintenance and handover.

Use a clear entry page such as README or START_HERE.

## Secrets

Never commit:
- passwords;
- API keys;
- access tokens;
- private credentials;
- sensitive exports.

Use environment variables or the deployment platform's secret/configuration mechanism. A committed example file may show variable names but must not contain real secret values.

## Change discipline

Do not silently rewrite working functionality while addressing an unrelated defect. Preserve established requirements and verify the requested change.

For moves or restructures:
1. read the original;
2. create the destination with the original content;
3. verify the destination;
4. update navigation/references;
5. remove the obsolete copy.

## Technical quality

For web systems, favour:
- responsive interfaces;
- clear loading and failure states;
- deliberate data models;
- observable integration failures;
- reasonable sync latency;
- a test-connection or health-check mechanism where useful;
- recoverable deployment instructions.

Do not describe a requirement as implemented until the current code and environment have been inspected or tested.

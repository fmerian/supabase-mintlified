<p align="center">
<img src="https://user-images.githubusercontent.com/8291514/213727234-cda046d6-28c6-491a-b284-b86c5cede25d.png#gh-light-mode-only" >
<img src="https://user-images.githubusercontent.com/8291514/213727225-56186826-bee8-43b5-9b15-86e839d89393.png#gh-dark-mode-only" >
</p>

# Supabase

[Supabase](https://supabase.com) is an open source Firebase alternative. We're building the features of Firebase using enterprise-grade open source tools.

- [x] Hosted Postgres Database. [Docs](https://supabase.com/docs/guides/database)
- [x] Authentication and Authorization. [Docs](https://supabase.com/docs/guides/auth)
- [x] Auto-generated APIs.
  - [x] REST. [Docs](https://supabase.com/docs/guides/api)
  - [x] GraphQL. [Docs](https://supabase.com/docs/guides/graphql)
  - [x] Realtime subscriptions. [Docs](https://supabase.com/docs/guides/realtime)
- [x] Functions.
  - [x] Database Functions. [Docs](https://supabase.com/docs/guides/database/functions)
  - [x] Edge Functions [Docs](https://supabase.com/docs/guides/functions)
- [x] File Storage. [Docs](https://supabase.com/docs/guides/storage)
- [x] AI + Vector/Embeddings Toolkit. [Docs](https://supabase.com/docs/guides/ai)
- [x] Dashboard

## Documentation

For full documentation, visit [supabase.com/docs](https://supabase.com/docs)

To see how to Contribute, visit [Getting Started](https://github.com/supabase/supabase/blob/master/DEVELOPERS.md)

## Community & Support

- [Community Forum](https://github.com/supabase/supabase/discussions). Best for: help with building, discussion about database best practices.
- [GitHub Issues](https://github.com/supabase/supabase/issues). Best for: bugs and errors you encounter using Supabase.
- [Email Support](https://supabase.com/docs/support#business-support). Best for: problems with your database or infrastructure.
- [Discord](https://discord.supabase.com). Best for: sharing your applications and hanging out with the community.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where `mint.json` is):

```
mintlify dev
```

## Publishing Changes

Install the Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it will re-install dependencies.
- Page loads as a 404 - Make sure you're running in a folder with `mint.json`.

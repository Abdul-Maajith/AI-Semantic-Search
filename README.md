# AI Semantic Search using OpenAI and Supabase

Built with:
- ✅ Next.js 12
- ✅ Supabase - PGVector to store and query vector Embeddings
- ✅ Shadcn-ui
- ✅ Langchain TypeScript integration
- ✅ Supabase as the knowledge store

## 🗃️ Pre-requisites
- Create a free account and get an OPEN_AI key from platform.openai.com
- Create a free account and get access to Supabase
- Migrate the Existing Database Schema, which is in the folder supabase/migrations.
- And populate your `.env` file with the required information.


All commands are run from the root of the project, from a terminal:

| Command               | Action                                          |
| :-------------------- | :-----------------------------------------------|
| `npm install`         | Installs dependencies                           |
| `npm run embedding`| Splits your Md file under the /docs folder into chunks, embeds them, uploads them to supabase|
| `npm run dev`         | Starts the local dev server at `localhost:3000` |
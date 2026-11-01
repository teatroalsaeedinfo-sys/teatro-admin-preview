# Teatro AlSaeed Admin Preview

Standalone preview repository for the Teatro AlSaeed content-management panel.

## Deploy with GitHub Pages

1. Open the repository **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for the Pages deployment to complete.

The expected site URL is:

https://teatroalsaeedinfo-sys.github.io/teatro-admin-preview/

## Security notes

- This repository contains only the admin panel frontend.
- It uses the Supabase publishable key, which is intended for browser use. Database access must remain protected by Supabase Row Level Security and the admin membership policies.
- Never add a Supabase `service_role` key, passwords, access tokens, or other secrets to this repository.
- The panel requires an existing Supabase Auth account that is present in `public.admin_members`.
- This preview is separate from the official `teatro-alsaeed` website repository. Do not change the official website's GitHub Pages settings to deploy this preview.

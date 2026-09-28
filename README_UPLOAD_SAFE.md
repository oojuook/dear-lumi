# Dear Lumi web-upload-safe package

Use this package only if GitHub web upload keeps flattening your `src` and `public` folders.

How to use:
1. Unzip this package.
2. Upload everything in this folder to your GitHub repo root.
3. Do NOT unzip `src.tar.gz` or `public.tar.gz`.
4. In Vercel, keep Root Directory as `./` and leave the build/install commands blank.
5. Vercel will restore the folders automatically during `pnpm run build`.

Expected root files after upload:
- package.json
- index.html
- src.tar.gz
- public.tar.gz
- restore-folders.sh
- other config files

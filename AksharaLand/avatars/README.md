# Avatars — drop your Ready Player Me files here

Final files this folder needs (exact names matter — the code looks for these):

- `her.glb`  — full-body rigged avatar for Akshara
- `him.glb`  — full-body rigged avatar for you

## How to make each one (~5 min each)

1. Go to **https://readyplayer.me/** → "Create Avatar".
2. Choose **"Take a photo / Upload"** and give it a clear, front-facing face photo.
   - `boy.jpeg` / `girl.jpeg` in the project root work, but a tight face crop is better.
3. Tweak hair / body / outfit so it looks like the person.
4. Click **Download** (or copy the `.glb` URL). You want the **full-body GLB**.
5. Rename the downloaded file to `her.glb` / `him.glb` and put it in this folder.

That's it — tell Claude once the files are here and the in-game character gets built around them.

## Notes
- RPM avatars come **rigged but with no animations** — the walk/wave/hug clips
  are added in code (from the RPM / Mixamo animation library). You don't need to
  do anything about that.
- Keep the download **full-body**, not half-body, or the legs won't exist.

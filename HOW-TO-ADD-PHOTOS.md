# How to update the Marea website

This is your living portfolio. Everything lives in **index.html**. You can update it
yourself (right here on GitHub) or ask Claude to do it in a future session.

---

## Add a new photo to a gallery

1. Open **index.html** and click the pencil (Edit) icon.
2. Find the section that begins with `<!-- WORK / GALLERY -->`.
3. Copy one existing photo line. Each looks like this:

   <div class="shot" data-cat="landscape"><img loading="lazy" src="IMAGE_URL" alt="Title"><div class="meta"><span class="cat">landscape</span><span class="ttl">Title</span></div></div>

4. Paste it on a new line and change three things:
   - **data-cat** and the **cat** text -> the category (see list below)
   - **src="IMAGE_URL"** -> the link to your photo
   - **alt** and **ttl** -> the photo's title

5. Scroll down, click **Commit changes**. The live site updates in ~1 minute.

## The six categories (use these exact words)

| Use this word | Shows under |
|---------------|-------------|
| landscape     | Landscape |
| nature        | Nature |
| portrait      | Portraits |
| maternity     | Maternity |
| animal        | Animal Portraits |
| architecture  | Architecture |

## Where do photo links come from?

Right now the site uses placeholder photos. To use YOUR photos, you have two easy paths:

- **Upload them to this repo:** create a folder called `photos`, drag your images in,
  then use `src="photos/your-file.jpg"`. Simplest, everything in one place.
- **Use a free image host** (Cloudinary, Imgur, etc.) and paste the link they give you.

Tip: keep images around 1600px wide and saved at ~70-80% quality so the site stays fast.

## Other quick edits

- **Email:** search index.html for `hello@studiomarea.com` and replace it.
- **Instagram / socials:** search for `instagram.com` and paste your real profile URL.
- **About text / titles / hero words:** all plain text in index.html, edit freely.

## Working with Claude again

Next session, just share this repo link
(https://github.com/StudioMarea/studiomarea.github.io) and say what you want changed.
Claude can read the current site and pick up right where we left off.

---
*Marea — Seattle & Costa Rica.*

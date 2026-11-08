# Nails at Moi — Website

A one-page, mobile-friendly website for Nails at Moi, a nail studio in Johannesburg.

Plain HTML and CSS. No build step and no dependencies.

## Sections
- Hero with Book and WhatsApp buttons
- Services and price list
- Gallery
- How booking works and the deposit policy
- Location, hours and map

## Customising
Search `index.html` for `[` to find every placeholder:
- `[R price]`, `[R amount]`: prices and deposit
- `[Area]`, `[Street address]`, `[hours]`: location details
- `27XXXXXXXXX`: WhatsApp number in international format
- `[Photo: …]`: replace with `<img src="images/your-photo.jpg" alt="Description">`

Change the brand colour with `--accent` at the top of the `<style>` block.

## Hosting on GitHub Pages
1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. The site goes live at `https://<username>.github.io/<repo-name>/`.

# A Little Universe For You — Vercel Static Site

This is a static HTML website. The complete HTML, CSS, JavaScript, and all five memory photos are embedded in `index.html`, so no image folder, build step, framework, or server is required.

## Deploy with Vercel CLI (macOS)

1. Install Node.js LTS if `node` and `npm` are not already installed: https://nodejs.org/
2. Open Terminal and change directory to this project folder.
3. Run:

   ```sh
   npm install -g vercel
   vercel --prod
   ```

4. Follow the prompts and open the Production URL printed by Vercel.

## Deploy through GitHub

1. Create a GitHub repository and upload `index.html`, `vercel.json`, and this README to the repository root.
2. In Vercel, choose **Add New → Project**, import that repository, and deploy it as a static site. No framework or build command is needed; use the repository root as the root directory.

## Notes

- Keep `index.html` at the project root. Renaming it or placing it in a subfolder can cause a 404 at the main URL.
- The five memory photos are embedded as Base64 JPEGs in the HTML. They preserve their aspect ratio and use `object-fit: contain`, so the full photos are shown without cropping.

# Alex Barbachov Volleyball Recruiting Profile

Static volleyball recruiting website for Alex Barbachov, designed for
deployment as a GitHub Pages user site.

## Site

Once published from the `AlexBarbachov/alexbarbachov.github.io` repository, the
recruiting profile will be available at:

<https://alexbarbachov.github.io/mit/>

The root URL, <https://alexbarbachov.github.io/>, redirects to the profile.

## Pages

- `index.html`: root redirect to `/mit/`
- `mit/index.html`: recruiting overview and contact information
- `mit/videos.html`: videos and highlights
- `mit/club-achievements.html`: club volleyball achievements
- `mit/high-school-achievements.html`: high school volleyball achievements
- `mit/academic-profile.html`: academic profile
- `mit/styles.css`: shared site styles

## Publish

1. Create a public GitHub repository named `alexbarbachov.github.io` under the
   `alexbarbachov` account. Do not initialize it with another README.
2. Add the repository as the local remote:

   ```sh
   git remote add origin git@github.com:alexbarbachov/alexbarbachov.github.io.git
   git push -u origin main
   ```

3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

GitHub Pages may take a few minutes to publish the first deployment.

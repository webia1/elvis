# ELVIS Intro

## Goal

The goal of this session was to create a webpage that displays a video of ASCII art. The video should autoplay, loop, and take up the full width of the browser. The video should also play at 90% of the normal speed. Finally, the webpage should be published on GitHub Pages.

## Steps

1. We started by creating the ASCII art video and saving it as `ELVIS.webm`.

2. We then created an `index.html` file that includes a `video` element to display the video. We set the `autoplay`, `loop`, and `muted` attributes on the `video` element to make the video autoplay, loop, and play without sound. We also set the width of the video to 100% of the browser width.

3. To make the video play at 80% of the normal speed, we added a small JavaScript snippet to the `index.html` file that sets the `playbackRate` of the video to 0.8.

4. We added the `index.html` and `ELVIS.webm` files to the Git repository and committed the changes.

5. We pushed the changes to the GitHub repository.

6. To publish the webpage on GitHub Pages, we created a new branch named `gh-pages` and pushed the changes to this branch.

7. We then went to the repository settings on GitHub and enabled GitHub Pages:

   - We selected the `main` branch as the source for the GitHub Pages site.
   - We set the folder to `/ (root)` to publish the site from the root of the repository.
   - We add a deploy.yaml file to the `.github/workflows` folder to deploy the site to GitHub Pages.

## Result

On Merge with main branch, the deploy.yaml file will deploy the site to GitHub Pages. (TODO: Re-Check!)

The webpage is now published on GitHub Pages at `https://webia1.github.io/elvis`. The webpage displays the ASCII art video, which autoplays, loops, takes up the full width of the browser, and plays at 80% of the normal speed.

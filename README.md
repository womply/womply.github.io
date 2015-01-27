# Womply Developer Blog

An [Octopress v3](https://github.com/octopress/octopress) blog wherein Womply developers write posts.

## Local Setup

1. Clone it.
   ```
   git clone git@github.com:womply/womply.github.io.git
   ```

2. Bundle it.
   ```
   cd womply.github.io && bundle install
   ```

3. Serve it.
   ```
   jekyll serve --detach && open http://127.0.0.1:4000/
   ```

4. Write a draft.
   ```
   octopress new draft 'Advances in Bliggity Blah' && vim _drafts/advances-in-bliggity-blah.markdown
   ```

5. Publish a post.
   ```
   octopress publish 'Advances in Bliggity Blah' && open http://127.0.0.1:4000/2015/01/27/advances-in-bliggity-blah.html
   ```

# Copy Paste operation for Falco blog creation

This branch is ```NOT up to date``` with ```falcosecurity/falco-website:master```. <br/>
Click ```Sync Fork``` in the UI of ```https://github.com/nigel-falco/falco-website``` to use the latest version of the project.

```
git clone https://github.com/nigel-falco/falco-website.git
cd falco-website/content/en/blog
mkdir falco-okta-identity
cd falco-okta-identity
cp -r Desktop/images falco-website/content/en/blog/falco-okta-identity
vi index.md
git remote add upstream https://github.com/falcosecurity/falco-website.git
git checkout -b falco-okta-identity
git add . && git commit -s -m "Falco Blog about Okta Plugin" && git push upstream falco-okta-identity
git push origin falco-okta-identity
```

uncomment ```blog``` and ```community``` since it's a community-focused blog.


<img width="1424" alt="Screenshot 2023-12-12 at 16 40 20" src="https://github.com/nigel-falco/Disregard/assets/152274017/cf062551-7d2e-44ea-b8a0-44dc4a4c4e1b">

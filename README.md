# Disregard

```
git clone https://github.com/nigel-falco/falco-website.git
cd falco-website/content/en/blog
mkdir falco-okta-identity
cd falco-okta-identity
cp -r Desktop/images falco-website/content/en/blog/falco-okta-identity
vi index.md
git remote add upstream https://github.com/nigel-falco/falco-website.git
git checkout -b falco-okta-identity
git add . && git commit -s -m "Falco Blog about Okta Plugin" && git push origin falco-okta-identity
```

### Redirecting a subdomain to freeCodeCamp.org home

Add domain aliases on [Netlify dashboard](https://app.netlify.com/sites/freecodecamp-redirect-to-home/settings/domain) for subdomain(s) and update Cloudfare DNS settings by creating a CNAME for the subdomain(s) and point it to `freecodecamp-redirect-to-home.netlify.com`

### Redirecting a subdomain to a Developer News page

Run the generator.sh like so:

```
./generator.sh shop
```

Setup a new Netlify site from Git using this repo and use the created directory as the publish directory. This should be followed by updating the Cloudflare DNS settings by creating a CNAME for the domain and pointing it to the netlify global URL

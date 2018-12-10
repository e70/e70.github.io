# TODO

Add a  LICENSE
See README.md for further content related TODOs

Add all READMEs to a private Bitbucket repository, see https://confluence.atlassian.com/bitbucket/publishing-a-website-on-bitbucket-cloud-221449776.html

Implementation based on https://www.toptal.com/github/unlimited-scale-web-hosting-github-pages-cloudflare, but be aware that some stuff may be outdated.

My OneTab contains several Cloudflare related stuff around their 1.1.1.1 DNS service and DDNS setup

## Static landing page

Something like <https://github.com/BlackrockDigital/startbootstrap-coming-soon/blob/master/README.md> but replace the email sign-up with an access token.



# DONE

echo "# e70.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/e70/e70.github.io.git
git push -u origin master

Started gitignore



## setup https

Works,  but test, fine-tune and document

## Setup custom domain

1. Add a CNAME in your DNS zone, for `eniederacher.com` see
   https://dash.cloudflare.com/f1cf607e32aedc064d3064a9925bd089/eniederacher.com/dns
2. Add that custom domain to your repository, see <https://github.com/e70/e70.github.io/settings>

## Setup Jekyll

GitHub pages supports [Jekyll themes](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site-with-the-jekyll-theme-chooser/).

From the [supported](https://pages.github.com/themes/) themes only the very basic [minima](https://github.com/jekyll/minima) or [minimal](https://pages-themes.github.io/minimal/) themes look promising.

But we go better with static landing pages
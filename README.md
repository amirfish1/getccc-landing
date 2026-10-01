# getccc-landing

Serves https://getccc.dev/ — a redirect to https://ccc.amirfish.ai/ that
preserves the incoming query string and adds email-outreach attribution.
`getccc.dev` is the cold-outreach sender domain (amir@getccc.dev), so
links in those emails share the sender's domain instead of a UTM-laden
amirfish.ai URL.

GitHub Pages (this repo, main, root) + CNAME file. DNS lives at Spaceship:
apex A records -> 185.199.108.153, .109.153, .110.153, .111.153;
`www` CNAME -> amirfish1.github.io.

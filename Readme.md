Currently, this site only exists to give support to the github repository [vibes](https://github.com/igncp/vibes) auth flow

### Explanation

To work with the *Meetup API*, as the `redirect_uri` parameter it requires the exact url as the Origin header sent with the Ajax requests (to enable CORS), which will be `igncp.github.io` and not `igncp.github.io/vibes`.

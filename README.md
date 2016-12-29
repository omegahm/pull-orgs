## NO LONGER MAINTAINED

Take a look at https://github.com/omegahm/openpull instead.

---

pull-orgs
=========

Get all open pull-requests for all repositories within organization

![Screenshot](http://ohm.sh/img/2014-08-21-get-pulls.png)

It needs an `GITHUB_ACCESS_TOKEN` set in the environment as well. 
This you can get by accessing your Github account, venturing into settings and then applications and here clicking on "Generate new token". 
Remember that these tokens are only shown once, so copy it into some secret dotfile or something.

It will default to my username and organization, so set the `GITHUB_USERNAME` and `GITHUB_ORGANISATION` environment variables as well.

You can also envoke it with the username and organization as arguments, calling it with:

```bash
get-pulls omegahm lokalebasen
```

Blog Post
=========

http://ohm.sh/2014/08/21/pull-requests.html

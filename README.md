# Resources
<a rel="Delivery" href="https://github.com/BCDevExchange/docs/blob/master/discussion/projectstates.md"><img alt="In production, but maybe in Alpha or Beta. Intended to persist and be supported." style="border-width:0" src="http://bcdevexchange.org/badge/3.svg" title="In production, but maybe in Alpha or Beta. Intended to persist and be supported." /></a>

Contains data used by BCDevExchange.org Resource Search

# Administration

As an admin of this repo, you can add/edit the `resources.yml` file.  You may also allow others to fork it and you may accept pull requests.  

`resources.yml` is a list of resources as they will appear on [bcdevexchange.org/#/resources](https://bcdevexchange.org/#/resources).  The server will read the file from GitHub, parse the YAML and display the content.  

In the event the YAML has a parsing error, check the server logs `log/stderr.log` for details on the problem. If you run into a lot of problems with YAML, I suggest creating a branch or fork it while you work through the issues.  Then once validated, merge back to master via pull request.  

A helpful tool for validating the syntax:

[yaml-online-parser.appspot.com](http://yaml-online-parser.appspot.com/?url=https%3A%2F%2Fraw.githubusercontent.com%2FBCDevExchange%2FBCDevExchange-Resources%2Fmaster%2Fresources.yml)


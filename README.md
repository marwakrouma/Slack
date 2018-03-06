Slack Plugin
=============

Send notifications to Slack depending on customers.

For help, join [![Gitter chat](https://badges.gitter.im/alerta/chat.png)](https://gitter.im/alerta/chat)

Installation
------------

Clone the GitHub repo and run:

    $ python setup.py install

Or, to install remotely from GitHub run:

    $ pip install git+https://github.com/marwakrouma/Slack.git

Configuration
-------------

Add `SlackCustomers` to the list of enabled `PLUGINS` in `alertad.conf` server
configuration file.
Set the list of webhooks URL in SLACK_WEBHOOK_URL_LIST and the list of correspondant channels' names in ALERTA_CUSTOMERS_LIST (in alerta_slack.py)

Run 
$ python setup.py install to update the modifications
and restart alerta service
$ sudo service uwsgi restart

# PullRequest.Club

Sign up to receive monthly GitHub issues as your homework!

## Development

Run the app locally:

    script/prc_server.pl

Running the app in the cloud:

    script/prc_fastcgi.pl -l /tmp/prc.socket -n 5 -p /tmp/prc.pid -d

Run all tests:

    prove -lmv t/*
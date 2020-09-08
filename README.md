# snowpack-dev-problem

> Issues when updating to `snowpack@2.10.2`.

How to reproduce:

1. check out `master` branch
2. npm install
3. npm start

Fixing the "culprit":

It seems the issue is related to the `favicon.ico` on the master branch. This is removed in the `works` branch.

How to test:

1. check out `works` branch
2. npm start

Downgrading to `snowpack@2.10.1` works on both branches.


# scala-cli-bazel-crypto-3des-encrypted-scrypt-encoded

## Description
Encrypt and decrypt password with 3des
encoded scrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- scala
- bazel
  - 3des
  - scrypt

## Docker stack
- l.gcr.io/google/bazel

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

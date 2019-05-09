# Brainstorming 

## Social Network Server API

Graphql with subscriptions support will be used for the main API of the social network server

## Direct Messaging

By default all direct messaging will be whitelisted by the reciprocal relationships between users that follow each other. However, we will also support the ability to allow anyone to direct message a user if the user opts in via a preference.

## Usernames

This is probably going to be source of contention but the proposed format for usernames for the social network is: username@domain.tld

## DNS

We will use something similar to SPF records to verify that a message coming from another social network is coming from an authorized ip address.

## Encrtyption

All communication, without exception, between client and server and server and server will be encrypted.

## Initial technology choices:
  - Elixir
  - Phoenix Framework
  - Graphql/Absinthe
  - Postgres/Cassandra/Redis/Kafka

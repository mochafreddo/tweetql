# TweetQL

TweetQL is a simple GraphQL server that provides a basic API for tweets and users.

## Installation

To install the dependencies, run:

```sh
npm install
```

## Running the Server

To start the server, run:

```sh
npm run dev
```

This will start the server on `localhost:4000` (or the port specified in your environment variables).

## API

The server provides the following GraphQL queries:

- `allTweets`: Returns all tweets.
- `tweet(id: ID!)`: Returns a specific tweet by its ID.
- `allUsers`: Returns all users.

And the following GraphQL mutations:

- `postTweet(text: String!, userId: ID!)`: Posts a new tweet.
- `deleteTweet(id: ID!)`: Deletes a tweet by its ID.

## Dependencies

- apollo-server: ^3.13.0
- graphql: ^16.8.1
- node-fetch: ^3.3.2

## Dev Dependencies

- nodemon: ^3.0.3

## Reference

- [NOMAD CODERS: GraphQL로 영화 API 만들기](https://nomadcoders.co/graphql-for-beginners)

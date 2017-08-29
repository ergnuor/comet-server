
# What is “the public developer’s ID” and “the secret developer’s key”?

The public developer’s ID and secret developer’s key are given while registration and connecting an additional services. 

The public developer’s ID serves as a login on the comet-server and the secret developer’s key serves as password on the comet-server. That’s why new requirements appear to storage and publication of these values.

The public developer’s ID may be not hidden – it is needed to pass both in using JavaScript API and in using with CometQL.

The secret developer’s key – is needed for using CometQL (and its secure may refer to like every other password). This value is encouraged not to publish and in the case of exposure it is necessary to get online support.

In some examples of documentation you can find open developer’s ID and secret key – it was done to show how system really works with these both values. You can use these keys only as demo data because many people can send messages at the same time with you.


# Public identifier Developer

In the examples, commonly referred to as dev_id. It represents a positive integer. Issued when registering on the website https://comet-server.com  
# Secret developer key

Secret Developer key, it is composed of 64 characters and is used for authentication to the comet server. No it does not tell anyone. And if he made a publicized contact Technical Support with a request to change it. In the examples, commonly referred to as dev_key. 
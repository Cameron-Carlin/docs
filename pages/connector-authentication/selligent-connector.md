---
title: Selligent Authentication
sidebar: cyclr_sidebar
permalink: selligent-connector
tags: [connector]
---

# Selligent

## Partner Setup

To use the Selligent connector, you will need 

1. The name of your server (e.g. someserver.com)
2. Your Username
3. A Secret Key (aka Password).

# Username

To be able to use the REST API a dedicated API user has to be created.

![connector setup](./images/APIUserCreate.png)

A name and login needs to be entered for the API user. 

The user's password is generated automatically and is used for hashing. The refresh button to the right of the field allows regenerating the password.

The API user must assign specific rights, indicating what operations can be performed through the API by that user and what operations can't.

![connector setup](./images/APIUserRights.png)

Once this is done, the Server, Username and Password(Key) can be entered when installing the connector.